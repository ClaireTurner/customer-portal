---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-03"

keywords: SoftLayer account, new users, IBM Cloud account

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Getting started tutorial
{: #getting-started}

In this tutorial, we walk through the process of getting you up and running with your SoftLayer account so you can begin ordering and managing your infrastructure resources.
{:shortdesc}

## Before you begin
{: #prereqs}

You need an [{{site.data.keyword.Bluemix}} account ![External link icon](../icons/launch-glyph.svg "External link icon")](https://cloud.ibm.com){:new_window}. Log in to the customer portal with your IBMid credentials. Most new users use [IBMid](/docs/account?topic=account-unifyingaccounts#switchtoIBMid) for authentication.

If you don't use IBMid for authentication to log in to your account, log in to the customer portal with your unique {{site.data.keyword.BluSoftlayer_notm}} infrastructure credentials.
{: tip}

## Step 1. Set up your account
{: #account-setup}

Setting up your account includes verifying your account contact information and billing details:
 * To verify your company contact details, go to **Account** > **Manage** > **Company Contacts**. Your account's company contact information is used to notify you of any issues with or changes to your account.
 * To verify your company profile details, go to **Account** > **Manage** > **Company Profile**. The company profile information has details about the primary account holder.
 * To verify your billing details, go to **Account** > **Billing** > **Payment Method**. The monthly payment method is the credit card that is billed on a recurring basis for payments that are associated with your account.

## Step 2. Add users and assign permissions
{: #users-permissions}

To add users to your account and set initial permissions, go to **Account** > **Users**.
 * To invite users to both platform and infrastructure resources in your account based on the specific permissions you assign, click **Invite Users**. You're then directed to the {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) UI to invite users and assign access. See [Inviting users](/docs/iam?topic=iam-iamuserinv#iamuserinv) for more information.
 * To add users with VPN access only, click **Add VPN Only User**. Enter the personal information, set portal permissions, and set device access for the user.

When you set infrastructure permissions in the initial invitation, you choose from one of three permission sets: View Only, Basic User, Super User. After users accept the invitation, you can customize their access by editing their portal permissions. For more information, see [Infrastructure permissions](/docs/iam?topic=iam-infrapermission#infrapermission).
{: tip}

## Step 3. Enable access to the {{site.data.keyword.Bluemix_notm}} infrastructure private network
{: #enable-private-network}

The {{site.data.keyword.Bluemix_notm}} infrastructure private network is offered to users and devices free of charge. All bandwidth on the private network is unmetered and complimentary. The private network offers many benefits that include the following benefits:
  * Replicating device environments to other data centers for failover
  * Front-end system accessibility to database servers
  * Secure access and management to your systems

To enable user access to the private network, edit the VPN access in the customer portal:
  1. Select **Account** > **VPN Access** from the menu bar.  
  2. Click the link in the VPN Access column.
  3. Select an option from the **VPN Type** menu and click **Save**.  

For users in accounts that use IBMid authentication, the SoftLayer VPN user name for VPN access is used. The VPN user name is defined in the user profile. The VPN user name is different from the user name that defaults to the IBMid email address and account ID.
{: tip}

For more information about using a VPN connection, see [About VPN](/docs/infrastructure/iaas-vpn?topic=VPN-about-iaas-vpn#about-iaas-vpn).

## Step 4. Subscribe to notifications
{: #get-notified}

To get notified about system issues and planned maintenance events, you can subscribe to notifications through the Event Management System. When you create an account or you're added to an account, you're unsubscribed to notifications by default.

Access the Event Management System in the customer portal to choose which notifications you want to subscribe to:
  1. Select **Account** > **Manage** > **Subscriptions** from the menu bar.
  2. Click a specific subscription from the list.
  3. Select **Yes** in the Subscribed column.
  4. Click **View All Subscriptions** to return to the list of available subscriptions and subscribe to other types if necessary.

## Next steps
{: #next-steps}

After your account is set up, go to the [{{site.data.keyword.Bluemix_notm}} catalog ![External link icon](../icons/launch-glyph.svg)](https://{DomainName}/catalog/?category=infrastructure){:new_window} and start ordering devices.
