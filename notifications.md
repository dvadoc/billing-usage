---

copyright:
  years: 2015, 2021
lastupdated: "2021-11-22"

keywords: spending notification, spending alert, cost threshold, spending threshold, service notifications, preset notifications, notification, 

subcollection: billing-usage

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:help: data-hd-content-type='help'} 
{:support: data-reuse='support'} 
{:note: .note}

# Setting spending notifications
{: #spending}
{: help} 
{: support}

If you have an {{site.data.keyword.cloud}} Pay-As-You-Go or Subscription account, you can set up email spending notifications. Now, in addition to account owners, any user on the account with the editor role or higher on the billing service can set spending notifications. You can enable spending notifications for total account, Cloud Foundry runtime, container, and service spending, or add spending for individual services, including third-party services. 
{: shortdesc}

You receive notifications when you reach 80%, 90%, and 100% of the spending thresholds that you specify. As your needs change, you can edit the spending threshold. If you're interested, you can use our latest enhancement to select up to 10 users from your account to receive notifications about the service. 

Lite accounts can't enable spending notifications because they can use only no-cost services, so you never have any spending. After you upgrade to a Pay-As-You-Go or Subscription account, you can set spending thresholds. For more information, see [Account types](/docs/account?topic=account-accounts).
{: note}

To set up your notifications:

1. In the {{site.data.keyword.cloud}} console, go to **Manage** > **Billing and usage**, and select **Spending notifications**.
2. Set the **Enable** option to on for the specific service area to enable email notifications. 
3. Click the **Edit** option from the **Actions** icon ![Actions icon](../icons/action-menu-icon.svg "Actions") menu.
4. Next, you can add email recipients. You can select up to 10 users from your account to receive email notifications about a service.
5. Enter the dollar amount to set a spending threshold. 
6. When you are finished, click **Save** to save your changes.

You can also set spending notifications for individual services: 

1. From the console, go to **Manage > Billing and usage**, and select **Spending notifications**.
2. From the **Add a service** section, click  **Create**. 
3. Enter the service name or search from the list to add the service. 
4. You can add email recipients. Select up to 10 users from your account to receive email notifications about a service.
5. Next, enter the dollar amount to set a spending threshold. 
6. When you are finished, click **Save** to save your changes.
7. After the spending notification is added for the service, set the **Enable** option to on for the specific service area to enable email notifications. 

Notifications don't include costs for classic infrastructure services. 
{: note}
