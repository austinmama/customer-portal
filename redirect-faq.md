---

copyright:

  years: 2019

lastupdated: "2019-09-27"

keywords: IBM Cloud user, control portal, SoftLayer, IBM Cloud console, FAQ, frequently asked questions, migrate, devices


subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:screen: .screen}
{:faq: data-hd-content-type='faq'}


# FAQs about migrating from the customer portal to the console
{: #redirect-faq}

FAQs about migrating from the customer portal to the {{site.data.keyword.cloud}} console might include questions about navigating the {{site.data.keyword.Bluemix_notm}} console, setting the operating system (OS) for a new device, access for working with support cases, or managing a user's access to infrastructure resources. 
{:shortdesc}

The formerly named SoftLayer is now called {{site.data.keyword.cloud_notm}} classic infrastructure. 
{: note}

## Where can I learn about navigating the {{site.data.keyword.Bluemix_notm}} console?
{: #learn-redirect}
{: faq}

For information about placing orders, accessing your invoices and sales items, managing your users and their access, and more, see [Transitioning to the {{site.data.keyword.Bluemix_notm}} experience](/docs/overview?topic=overview-ui#redirect-cloud). 

## Can I log in to the console with my SoftLayer ID?
{: #slid}
{: faq}

Yes, you can use your SoftLayer ID to log in to the console. Go to the [login page](https://cloud.ibm.com/login){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), and select **SoftLayer ID** from the **ID** list.  

## Where can I find my SoftLayer resources in the console?
{: #slitems}
{: faq}

To view your devices, storage, network, security, and services, you can use any of the following options:

* Click the **Menu icon** ![Menu icon](../icons/icon_hamburger.svg) > **Classic Infrastructure**.
* Click the **Menu icon** ![Menu icon](../icons/icon_hamburger.svg) > **Resource list**. 
* Click any of the links that are listed in the Classic infrastructure widget on your dashboard. Go to **Menu icon** ![Menu icon](../icons/icon_hamburger.svg) > **Dashboard**.

## How can I find the list of VPN access points?
{: #vpn-access}
{: faq}

When you try to access the Software Library in the customer portal, you might find that the link to more options for establishing a VPN connection is broken in the Downloads page prompt. See [VPN Access](https://www.ibm.com/cloud/vpn-access){: external} for the list of VPN access points. 

## Why can't I see my support tickets? 
{: #view-support-cases}
{: faq}

Support tickets are now called support cases in IBM Cloud. To access support cases, go to **Support** > **Manage cases**. 

If you're unable to view your cases, try clicking **View archived cases**. If you still can't view them, you might not have the required permission. Ask your account owner to add you to the support case access group. For more information, see [SoftLayer account permissions](https://test.cloud.ibm.com/docs/iam?topic=iam-migrated_permissions). 

## What access is needed to work with support cases? 
{: #access_supportcases}
{: faq}

By default, users in your account don't have access to create, update, search, or view cases. As the account owner, you must provide users access by assigning an Identity and Access Management (IAM) access policy. 

When you create a case, you can give other users full access to that case by adding their email on the **Add another person to this case** field. Any added users have access to view, edit, and update only that case in the account. They also receive notifications when the case is updated. 

For classic infrastructure users, the permissions to assign support case access is now available in [migrated classic infrastructure permission access groups](/docs/iam?topic=iam-infrapermission).

## Where do I manage a user's access to infrastructure? 
{: #infrastructure-devices}
{: faq}
{: support}

Access for classic infrastructure starts with the user. For more information, see [Managing classic infrastructure access](/docs/iam?topic=iam-mngclassicinfra).

If you need to assign access to IAM-enabled infrastructure services, such as {{site.data.keyword.vpc_full}}, you assign access to a user or access group from the **Access policies** tab.

## How do I manage access for users previously assigned billing and support permissions in my SoftLayer account?
{: #migrated-permissions-faq}
{: faq}
{: support}

All permissions that were previously assigned in your SoftLayer account can be managed in the {{site.data.keyword.Bluemix_notm}} console. Account permissions for managing billing information and support cases are now available in [migrated permissions access groups](/docs/iam?topic=iam-migrated_permissions). All users who were previously assigned these permissions in your SoftLayer account were migrated to these access groups, which are assigned the same level of access by using an IAM policy on the access group.

## How do I set the OS for a new bare metal server?
{: #set-os-bm}
{: faq}

When you're creating a bare metal server from the {{site.data.keyword.cloud_notm}} catalog, you can set the OS by scrolling to the Image section on the configuration page and selecting from the available options. 

## How do I reconfigure my device with different software?
{: #reload-os}
{: faq}

Perform an OS reload to reconfigure your device with different software. From your console dashboard, click **Devices** in the Resource summary widget > *device-name* > **Actions** > **OS reload**. For more information, see [Reloading the OS](/docs/infrastructure/software?topic=software-reloading-the-os#reloading-the-os). 
