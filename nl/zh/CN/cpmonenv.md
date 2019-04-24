---

copyright:

  years: 1994, 2019

lastupdated: "2019-01-31"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# 监视环境和系统事件
{: #cp_environment-events}

监视环境意味着您可以随时检查设备，并且在某个设备发生故障时自动收到通知。您还可以监视系统事件以保持系统平稳运行。  
{: shortdesc}

## 监视环境
{: #cp-monitorenvi}

至少使用基本的 ping 监视，但您也可以使用最适合您的业务需求的方式来定制监视选项。

### 随时了解网络维护和计划外事件
{: #cp-informedmaintenance}

有时，执行安排的网络维护和紧急网络维护是不可避免的。{{site.data.keyword.BluSoftlayer_full}} 基础架构会维护许多通道，以便及时向您通知所有安排的维护事件和紧急维护事件。此外，可以通过事件管理系统[预订电子邮件通知 ](/docs/customer-portal?topic=customer-portal-cp_bpnotifications#cp_bpnotifications)。此免费服务会自动向预订用户发送有关可能影响服务的计划外事件的电子邮件。

### 使用 {{site.data.keyword.BluSoftlayer_notm}} Infrastructure Mobile
{: #cp_bmxinframobile}

使用 iOS 或 Android 移动设备，通过 {{site.data.keyword.BluSoftlayer_notm}} Infrastructure Mobile 持续管理 {{site.data.keyword.BluSoftlayer_notm}} 基础架构设备。{{site.data.keyword.BluSoftlayer_notm}} Infrastructure Mobile 中的功能包括凭单支持、基本设备控制和带宽监视。

{{site.data.keyword.BluSoftlayer_notm}} Infrastructure Mobile 应用程序认可客户门户网站的功能，因为您可在任何位置使用连接网络的移动设备监视有关基础架构的关键信息。该应用程序发展很快，并定期添加新功能，但您可使用移动应用程序执行类似如下任务：
  * 查看、创建和更新支持凭单
  * 监视设备状态，包括带宽和警报
  * 关闭并重新启动裸机服务器和虚拟服务器
  * 查看帐户发票并进行一次性付款
  * 访问并检查 Object Storage 中存储的内容

{{site.data.keyword.BluSoftlayer_notm}} Infrastructure Mobile 应用程序在多个常用移动设备平台上可用，其中每个平台的相关应用程序商店均免费提供该应用程序。

## 监视服务器
{: #cp_monservers}

设置监视以检查服务器的状态，并确定何时进行扩展。您可以使用标准监视或 Nimsoft 监视服务。您可以从 {{site.data.keyword.BluSoftlayer_notm}} 基础架构客户门户网站使用缓慢或服务 ping，采用“执行 ping 操作并获取响应”方法进行标准（即基本）监视。您还可以在客户门户网站中或在基本、高级和高端这三个层中的其中一层中使用 Nimsoft（即高级）监视。有关裸机服务器的更多具体信息，请参阅[裸机服务器入门](/docs/bare-metal?topic=bare-metal-getting-started#getting-started)。

## 监视系统事件
{: #cp_monevent}

可以通过查看审计日志和访问日志来监视系统事件。

### 查看帐户的审计日志
{: #cp_viewacctauditlog}

每个客户门户网站帐户均随附审计日志，用于跟踪客户门户网站内每个用户的交互。例如，会跟踪以下交互：
  * 登录尝试（成功和失败）
  * 端口速度更新
  * 打开电源或关闭电源并重新启动
  * {{site.data.keyword.BluSoftlayer_notm}} 基础架构支持人员进行的交互。

使用以下步骤查看用户帐户的审计日志。

1. 使用您的唯一凭证来访问[客户门户网站 ![外部链接图标](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window}。
2. 从导航栏中选择**帐户** > **管理** > **审计日志**以访问审计日志。

审计日志初始会显示帐户上的用户所做的最后 25 个交互。您可以随时查看多达 200 个交互。更新**显示**下拉列表中显示的结果数。如果更改了设置，那么交互的**操作**列将包含链接。单击任一链接可查看受此操作影响的设置以及有关更改的详细信息。单击任何交互的设备名或用户名可使您重定向到“设备详细信息”屏幕或“用户概要文件”屏幕。

### 查看用户的访问日志
{: #cp_viewuserlogs}

访问日志显示由特定客户门户网站用户进行的每次访问尝试的数据。该日志显示每次访问尝试的日期和时间戳记以及 IP 地址。使用以下步骤查看用户的访问日志。

1. 使用您的唯一凭证来访问[客户门户网站 ![外部链接图标](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window}。
2. 从菜单栏中选择**帐户** > **用户**以访问“用户”窗口。
3. 从**操作**下拉列表中，选择**查看审计日志**以查看用户的访问日志。

每个用户的访问日志都会按日期显示该用户进行的访问尝试，以及用于进行访问尝试的 IP 地址。访问日志中的信息是只读的，因此任何时候都无法对其内容进行编辑。您可以通过重复上述步骤，随时重新查看访问日志。要退出日志并返回到“用户”屏幕，请单击**查看所有用户**链接。
