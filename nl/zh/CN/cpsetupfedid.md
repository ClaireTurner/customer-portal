---

copyright:

  years: 1994, 2019

lastupdated: "2019-06-18"

keywords: service provider, identity federation, IBM Cloud infrastructure SSO

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}

# 设置身份联合
{: #cp_setupidfed}

您可以设置身份联合，以允许服务提供者（例如，{{site.data.keyword.BluSoftlayer_full}} 基础架构管理系统 (IMS)）使用从可信身份系统生成的安全令牌进行认证和授权。
{:shortdesc}

可以通过以下其中一种方式在 {{site.data.keyword.BluSoftlayer_notm}} 基础架构 SSO 中设置身份联合：
* 在身份提供者和 {{site.data.keyword.BluSoftlayer_notm}} 基础架构中创建用户
* 在身份提供者中创建用户

对于服务提供者，角色定义了在对用户进行认证后，用户有权在其系统中（通过许可权）执行的操作。例如，*用户*角色可能只被允许查看不同的屏幕，但不能执行更新或添加操作。

可以将单个角色分配给多个用户。此外，如果某个角色在身份提供者中存在，但在 {{site.data.keyword.BluSoftlayer}} 基础架构中不存在，那么用户仍可以登录到 {{site.data.keyword.BluSoftlayer}} 基础架构，但用户不会有分配给角色的任何许可权。
{: tip}


## 在身份提供者和 {{site.data.keyword.BluSoftlayer_notm}} 基础架构中创建用户
{: #cp_scenario1both}

在此模型中，将执行以下过程：
* 在身份提供者和 {{site.data.keyword.BluSoftlayer_notm}} 基础架构中创建用户。
* 使用 {{site.data.keyword.BluSoftlayer}} 基础架构客户门户网站或 API 在 {{site.data.keyword.BluSoftlayer}} 基础架构 IMS 中分配用户许可权。
* 用户向身份提供者进行认证，并联合他们的用户身份。
* {{site.data.keyword.BluSoftlayer}} 基础架构使用用户标识，并且访问控制是基于为 {{site.data.keyword.BluSoftlayer}} 基础架构 IMS 中的用户定义的许可权。

首先，会在 {{site.data.keyword.BluSoftlayer}} 基础架构中使用随机密码为需要访问 {{site.data.keyword.BluSoftlayer}} 基础架构的用户创建帐户。必须先在 {{site.data.keyword.BluSoftlayer}} 基础架构中配置所有许可权，然后用户才能通过身份提供者使用 SSO。目前，许可权是基于单个用户设置的。

### 设置用户
{: #cp_user-setup}

使用以下步骤设置用户：

1. [向 SoftLayer 帐户添加用户](/docs/customer-portal?topic=customer-portal-customerportal_addusertocpacct#customerportal_addusertocpacct)。
2. 在 {{site.data.keyword.BluSoftlayer}} 基础架构中分配许可权。
3. 在身份提供者中创建用户。

单个用户概要文件中的**电子邮件**或**用户名**字段用于 Security Assertion Markup Language&trade; (SAML&trade;) 2.0 令牌。此令牌会在身份提供者和 {{site.data.keyword.BluSoftlayer}} 基础架构之间映射用户。

### 登录认证的示例流程
{: #exlogauthflowidprovicloud}

以下示例流程显示了在身份提供者和 {{site.data.keyword.BluSoftlayer_notm}} 基础架构中创建用户时，如何进行用户登录认证：
1. 用户通过浏览器会话访问身份提供者 URL。
2. 身份提供者对用户进行认证，例如通过其 LDAP。
3. 身份提供者返回 SAML 2.0 响应。
4. 身份提供者向服务提供者（在本例中为 {{site.data.keyword.BluSoftlayer}} 基础架构）发送 SAML 2.0 响应，以对用户标识进行认证。
5. {{site.data.keyword.BluSoftlayer}} 基础架构验证 SAML 2.0 响应。
6. 用户基于身份提供者与 {{site.data.keyword.BluSoftlayer}} 基础架构之间的可信设置，登录到 {{site.data.keyword.BluSoftlayer}} 基础架构客户门户网站。


## 在身份提供者中创建用户
{: #cp_scenario2idp}

在此模型中，将执行以下操作：
* 在身份提供者中创建角色，并将其分配给用户。
* 使用 {{site.data.keyword.BluSoftlayer}} 基础架构 API 在 {{site.data.keyword.BluSoftlayer}} 基础架构 IMS 中设置角色和许可权分配。
* 用户向身份提供者进行认证，并联合他们的用户身份和角色属性。
* {{site.data.keyword.BluSoftlayer}} 基础架构验证用户标识和角色属性。如果通过用户的身份提供者为用户分配的角色与 {{site.data.keyword.BluSoftlayer}} 基础架构中的角色相匹配，那么当用户登录到 {{site.data.keyword.BluSoftlayer}} 基础架构时，会为用户授予这些角色的许可权。
* 身份提供者创建用户时，会将这些用户视为联合用户，因为这些用户及其角色将通过 SAML 2.0 进行认证。

### 设置用户的角色
{: #cp_set-up-user-role}

使用以下步骤设置用户的角色：

1. 通过 {{site.data.keyword.BluSoftlayer}} 基础架构 API 来设置角色。
2. 在身份提供者中设置角色。
3. 确保在 {{site.data.keyword.BluSoftlayer}} 基础架构和身份提供者中定义的角色具有相同名称。

### 设置用户
{: #identity-setupuser}

使用以下步骤设置用户：

1. 在身份提供者中设置用户。
2. 在身份提供者中向用户分配角色。

在此场景中，您无需在 {{site.data.keyword.BluSoftlayer}} 基础架构中手动创建用户。

### 用户登录认证的示例流程
{: #exlogauthflowidprov}

以下示例流程显示了在身份提供者中创建用户时，如何进行用户登录认证：
1. 用户通过浏览器会话访问身份提供者 URL。
2. 身份提供者对用户进行认证，例如通过其 LDAP。
3. 身份提供者返回 SAML 2.0 响应。
4. 身份提供者向服务提供者（在本例中为 {{site.data.keyword.BluSoftlayer}} 基础架构）发送 SAML 2.0 响应，以对用户角色进行认证。
5. {{site.data.keyword.BluSoftlayer}} 基础架构验证 SAML 2.0 响应。
6. {{site.data.keyword.BluSoftlayer}} 基础架构将用户重定向到客户门户网站。
7. 用户登录到 {{site.data.keyword.BluSoftlayer}} 基础架构客户门户网站。

查看身份提供者的新角色设置过程，以及如何将其与 {{site.data.keyword.BluSoftlayer}} 基础架构相关联的过程。
