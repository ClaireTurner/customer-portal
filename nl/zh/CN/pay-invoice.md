---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: credit card, payment information, payment method changes

subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:screen: .screen}
{:new_window: target="_blank"}


# 付款
{: #cp_makepayment}

所有 {{site.data.keyword.Bluemix}} 基础架构记帐详细信息（从发票到付款信息）都安全地存储在客户门户网站中。如果付款方式发生变化，或者您的信用卡被取消或到期，请更新付款信息以避免发生逾期罚款。
{:shortdesc}

## 查看发票
{: #cp_viewinvoice}

在“发票”窗口上，每张发票都按“发票编号”、“日期”、“发票类型”和各种货币余额列出摘要信息。发票可以为以下任一类型：

<dl>
<dt>新发票</dt>
<dd>一系列周期性发票中的第一张发票。</dd>
<dt>周期性</dt>
<dd>在帐户上保持活动超过一个月的周期性收费的发票。</dd>
<dt>一次性费用</dt>
<dd>一次性收取各种费用，可能包含超额费。</dd>
<dt>信用值</dt>
<dd>{{site.data.keyword.BluSoftlayer_notm}} 基础架构给帐户余额的信用值。</dd>
<dt>退款</dt>
<dd>针对一次性费用或周期性费用的退款。</dd>
</dl>

您还可以查看帐户的计费摘要，包括以下信息：
  * 当前余额和估计的下一次余额
  * 付款方式
  * 上一个和下一个周期性发票日期

1. 从菜单中选择**帐户** > **计费** > **发票**。
2. 可以在客户门户网站中查看发票，也可以下载发票。

如果是在客户门户网站中查看发票，那么将显示所选发票的计费项目的逐项列记列表。单击计费项目行上的任意位置可查看有关费用的更多逐项列记详细信息。如果下载了发票，那么可以根据您的浏览器设置进行查看。下载的发票提供每个计费项目的逐项列记摘要和逐项列记详细计费。

如果您位于美国境外，那么可使用名为[发票](http://www.ibm.com/support/customer/invoices){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 的工具来查看自己的发票。每个国家或地区的具体步骤列在 [https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html](https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标") 上。如果您有任何问题，请致电 1-866-325-0045 与我们联系，并请求访问您的发票。
{: note}

## 添加付款方式
{: #cp_billpay}

每个 SoftLayer 帐户都需要存档信用卡，用于每月自动按发票金额收费。这些信息必须始终保持最新状态，以避免逾期付款；可以随时更新这些信息，以确保付款信息始终准确。如果存档的信用卡信息正确，但要对当前余额应用备用付款方式，请参阅[管理计费项目](/docs/customer-portal?topic=customer-portal-manage-billing#manage-billing)。使用以下步骤在客户门户网站中为帐户添加付款方式。

1. 从菜单中单击**帐户** > **计费** > **付款方式**。
2. 在**帐单地址**部分的每个字段中，输入必需的信用卡记帐详细信息。
> **注：**单击**使用公司信息**复选框可自动使用 {{site.data.keyword.BluSoftlayer_notm}} 基础架构为帐户存档的公司信息来填充相应字段。
3. 在**付款信息**部分的每个字段中，输入信用卡信息。
4. 单击**添加信用卡**以将信用卡添加为每月付款方式。
5. （可选）选择**欧盟支持**以确保欧洲支持团队处理您的维护和支持问题。有关此选项的更多信息，请参阅[设置欧洲支持的选项](/docs/customer-portal?topic=customer-portal-cp_seteusupported#cp_seteusupported)。

在添加付款方式后，请求将由 SoftLayer 帐户代表进行处理，以确保信用卡的有效性。通过验证的信用卡在 24 小时内可在帐户上使用。付款方式的状态更改会通过电子邮件发送给添加付款方式时提供的联系人。

## 一次性付款
{: #cp-one-payment}

您可以使用 PayPal 帐户或主信用卡进行一次性付款，您可以支付全部或部分余额。不会记录一次性付款详细信息以备将来使用，也不会修改帐户当前的每月付款方式。

1. 在客户门户网站中转至“一次性付款”页面。
 * 在菜单中：转至**帐户** > **付款**。
 * 在“发票”页面中：单击**支付余额**。
2. 在**付款金额**字段中，输入付款金额。
3. 如果要使用 PayPal 付款，请单击 **PayPal**，然后按照 PayPal 的提示来完成付款。不需要执行进一步的操作。如果要使用信用卡付款，请在相应字段中输入**信用卡号、到期日期和安全代码**。
4. 在**信用卡帐单地址**部分的相应字段中，输入记帐信息。
5. （可选）选择**欧盟支持**以确保欧洲支持团队处理您的维护和支持问题。有关此选项的更多信息，请参阅[设置欧洲支持的选项](/docs/customer-portal?topic=customer-portal-cp_seteusupported#cp_seteusupported)。
6. 单击**使用信用卡付款**以发起付款。

发起付款后，将处理相应付款。如果付款出现问题，请按照 {{site.data.keyword.BluSoftlayer_notm}} 基础架构或 PayPal 中的提示操作，直到问题解决。系统会处理付款。然后，会应用金额，并更新当前余额。
