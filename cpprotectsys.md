---

copyright:

  years: 1994, 2018

lastupdated: "2018-03-07"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Protecting your systems
{: #customerportal_protsys}

Protecting your systems ensures that your systems are running smoothly and without unnecessary interruptions.

## Use the private network
{: #cp_bpuseprivnet}

You can manage your devices in the most secure environment possible using the  {{site.data.keyword.BluSoftlayer_notm}} infrastructure private network. When possible, interact with your devices using a VPN connection and enable network spanning so that your systems communicate over the private network. To access the private network, edit the user’s VPN access from the [User List ![External link icon](../icons/launch-glyph.svg)](https://control.softlayer.com/account/user/list){:new_window}. Use the [Virtual Private Network ![External link icon](../icons/launch-glyph.svg)](http://www.softlayer.com/vpn-access){:new_window} instructions to connect to one of the various VPN options.

### Don't leave RDP, SSH, or control ports on the public network
{: #cp_bpnordpsshcponpubnet}

The public network is great for many things, but there are certain aspects that, when left available on the public network through open ports, can leave your system vulnerable. Protect yourself by disabling RDP or restricting SSH on the public network. If these services must be available on the public network, consider moving RDP or SSH to a custom port number.

## Safeguard your data through regular backups
{: #cp_bpsafedataregback}

Schedule backups to ensure that your data is safely stored outside of your device and to be able to reload it if it is lost.

{{site.data.keyword.BluSoftlayer_notm}} infrastructure offers multiple backup solutions to ensure that you can retrieve your data in the event of drive failure or user error. Backup solutions currently include NAS, EVault Backup and R1Soft CDP, which are all available in a variety of storage options.
For example, you can choose one of the following backup services to store your data in a secure location:
  * EVault Backup is an automated, agent-based backup system. This is a popular “set-and-forget” solution for managing your device. It is compatible with Microsoft software including Exchange and SQL through additional plug-ins. EVault users interact with this service through EVault’s WebCC Web-based application.
  * R1Soft Continuous Data Protection (CDP) can be installed on your server or self-managed virtual machine. It is recommended if you are looking for a single interface to manage all of your backups. You interact with R1Soft CDP through your proprietary management system, which allows agents to be installed on virtual machines and offers database plug-ins for additional functionality.

 Check out the [Storage ![External link icon](../icons/launch-glyph.svg)](http://www.softlayer.com/services/storagelayer/){:new_window} page for more information on each backup solution and see [Getting started with backup services](/docs/infrastructure/Backup/index.html) for more information about backing up your data.

### Don't assume you have redundancy; know that you do
{: #cp_bpknowredundant}

{{site.data.keyword.BluSoftlayer_notm}} infrastructure offers multiple add-on redundancies, including dual-path, redundant power supplies, and RAID configurations. Verify that you have provisioned one or more of these features to ensure you are working in a redundant environment and are protected in the event of a failure.

### Confirm that your information is backed before performing an OS reload
{: #cp_bpnoperfOSwobackupconf}

Reloading your operating system removes all data from the hard drive of the device. Prior to initiating the OS reload, back up your information and verify the success of that backup so no information is lost. After an OS reload has been completed, lost information cannot be retrieved.

## Don’t remove Adaptec Storage Manager (ASM)
{: #cp_bpsupdontremovasm}

 {{site.data.keyword.BluSoftlayer_notm}} infrastructure uses ASM to monitor your RAID array status. If you delete this software, the support team cannot monitor your device. If ASM is removed from your device, RAID failure alerts on your device are not available and you are not notified of the failure through the automatic notification system.
