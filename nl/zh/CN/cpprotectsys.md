---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: aregular backups, private network, IBM Cloud infrastructure, 


subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# 保护系统
{: #customerportal_protsys}

保护系统可确保系统平稳运行，没有不必要的中断。

## 使用专用网络
{: #cp_bpuseprivnet}

您可以使用 {{site.data.keyword.BluSoftlayer_notm}} 基础架构专用网络在尽可能最安全的环境中管理设备。如果可能，请使用 VPN 连接与设备进行交互并启用网络生成，以便系统可通过专用网络进行通信。要访问专用网络，请编辑[用户列表 ![外部链接图标](../icons/launch-glyph.svg)](https://control.softlayer.com/account/user/list){:new_window} 中用户的 VPN 访问。使用[虚拟专用网 ![外部链接图标](../icons/launch-glyph.svg)](http://www.softlayer.com/vpn-access){:new_window} 列表来连接到各种 VPN 选项中的一个选项。

有关使用 VPN 连接的更多信息，请参阅[关于 VPN](/docs/infrastructure/iaas-vpn?topic=VPN-about-vpn#about-vpn)。

### 请勿在公用网络上打开 RDP、SSH 或控制端口
{: #cp_bpnordpsshcponpubnet}

虽然通过公用网络可完成许多任务，但在公用网络上通过打开的端口提供某些服务时，系统容易受到攻击。通过在公用网络上禁用 RDP 或限制 SSH 来保护您自己。如果这些服务必须在公用网络上提供，请考虑将 RDP 或 SSH 移至定制端口号。

## 通过定期备份保护数据
{: #cp_bpsafedataregback}

您可以安排备份，以确保数据安全存储于设备外部，并可在数据丢失时重新装入。

{{site.data.keyword.BluSoftlayer_notm}} 基础架构提供了多种备份解决方案，以确保您可以在驱动器发生故障或用户出错时取回数据。目前，备份解决方案包括 NAS、EVault Backup 和 R1Soft CDP，它们全都可用于各种存储选项。
例如，您可以选择以下其中一个备份服务，以将数据存储于安全位置：
  * EVault Backup 是一种基于代理程序的自动备份系统，也是十分受欢迎的“一劳永逸”设备管理解决方案。它通过插件兼容 Microsoft 软件，包括 Exchange 和 SQL。EVault 用户通过 EVault 的基于 Web 的 WebCC 应用程序与此服务进行交互。
  * R1Soft Continuous Data Protection (CDP) 可安装在服务器或自我管理的虚拟机上。如果您希望在单个界面上管理所有备份，那么可以使用此软件。您可以通过专有管理系统与 R1Soft CDP 进行交互，该系统允许在虚拟机上安装代理程序并提供数据库插件以获得更多功能。

 有关每种备份解决方案的更多信息，请查看[存储器 ![外部链接图标](../icons/launch-glyph.svg)](http://www.softlayer.com/services/storagelayer/){:new_window} 页面；有关备份数据的更多信息，请查看[备份服务入门](/docs/infrastructure/Backup?topic=Backup-GettingStarted#GettingStarted)。

### 不要假定您有冗余；请确认您有冗余。
{: #cp_bpknowredundant}

{{site.data.keyword.BluSoftlayer_notm}} 基础架构提供了多种附加冗余，包括双路径、冗余电源和 RAID 配置。请验证您是否已供应其中一个或多个功能，以确保您在冗余环境中工作，并可在发生故障时受到保护。

### 重装操作系统之前，确认信息是否已备份
{: #cp_bpnoperfOSwobackupconf}

重装操作系统会从设备的硬盘中除去所有数据。在启动操作系统重装前，请备份您的信息并验证是否已成功完成此备份而没有丢失任何信息。在完成操作系统重装后，无法取回丢失的信息。

## 请勿除去 Adaptec Storage Manager (ASM)
{: #cp_bpsupdontremovasm}

 {{site.data.keyword.BluSoftlayer_notm}} 基础架构使用 ASM 来监视 RAID 阵列状态。如果删除此软件，那么支持团队将无法监视设备。如果从设备中除去了 ASM，那么设备上的 RAID 故障警报会不可用，并且您不会收到通过自动通知系统发送的故障通知。
