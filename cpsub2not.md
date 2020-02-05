---

copyright:

  years: 1994, 2020

lastupdated: "2020-02-05"

keywords: infrastructure, account IBM Cloud infrastructure notifications, unplanned infrastructure issues, notifications 

subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Subscribing to notifications
{: #cp_bpnotifications}

Sometimes, events occur in {{site.data.keyword.BluSoftlayer_notm}} infrastructure that require action. Some are unexpected and some are planned maintenance activities that are required to keep {{site.data.keyword.BluSoftlayer_notm}} infrastructure operating at its peak condition. Customers are isolated from these events as much as possible but sometimes it's necessary to take equipment offline. It's always necessary to be transparent, timely, and informative to the customer.
{:shortdesc}

Because you are in control of your cloud experience, you need timely information about maintenance activities. To get this information, you can subscribe to notifications from the customer portal. {{site.data.keyword.BluSoftlayer_notm}} infrastructure uses the Event Management System (EMS) notification process for the following types of important operational events:
* Unplanned infrastructure issues: Issues that might cause an outage under certain conditions for specific customers
* Planned service maintenance: Maintenance that is required to keep the infrastructure operating at optimal status
* Opened support tickets: Alerts subscribed users of tickets that are opened on their account

{{site.data.keyword.BluSoftlayer_notm}} infrastructure notifications have been designed for cloud environments by adhering to the following key principles:
* Automated through the customer portal
* Scalable to reach a large and growing community
* Targeted enabling {{site.data.keyword.BluSoftlayer_notm}} infrastructure to identify only the customers and subset of resources that are affected by the event.

For the notification system to be fully effective, subscribe to the process. If you have a critical environment that requires it, also establish 24-hour coverage.


## Notification timing policy
{: #cp_bpgsnotiftimpol}

The period of time {{site.data.keyword.BluSoftlayer_notm}} infrastructure gives to users in advance of a pending event differs, depending on whether the event is an unplanned infrastructure issue or planned or scheduled maintenance. Generally, the {{site.data.keyword.BluSoftlayer_notm}} infrastructure policy is to remedy problems as quickly as possible to remove or minimize the risk of further issues developing which might have a larger impact. This means that sometimes even planned maintenance is performed with only a short advanced notification.

### Policy overview
{: #cp_bpgsnotifpolover}

You're notified of the following types of outages or issues as described in each section.

#### Unplanned issues or outages
{: #cp_unplanned-issue}

{{site.data.keyword.BluSoftlayer_notm}} infrastructure communicates with affected customers as quickly as possible with information about infrastructure scope, workarounds, or resolution estimates as soon as that information is known. Timely communication gives you the information that you need to plan for contingencies and provides assurance that {{site.data.keyword.BluSoftlayer_notm}} infrastructure is addressing the issue.

#### Scheduled maintenance
{: #cp_maintenance}
{{site.data.keyword.BluSoftlayer_notm}} infrastructure provides notification for scheduled maintenance in advance of the event. There are times when {{site.data.keyword.BluSoftlayer_notm}} infrastructure maintenance is an emergency, which might result in shorter advanced notification. The goal is always to find the ideal balance between giving a reasonable amount of advanced notice to allow you to plan for contingencies and upgrading or enhancing infrastructure, which typically results in improvements to overall stability or adding needed capabilities.

#### Security vulnerabilities
{: #cp_vulnerabilities}

{{site.data.keyword.BluSoftlayer_notm}} infrastructure isolates the affected area, creates a patch to close the vulnerability, and tests the patch to ensure that no collateral function is impacted. Often, this work is done with another vendor that might supply parts of the affected technology. There's typically a public notification embargo for security patches, which are kept short to protect the public, but this necessitates a shorter advanced notification period. {{site.data.keyword.BluSoftlayer_notm}} infrastructure implements the patches across the affected infrastructure before the public is made aware of the issue, which would otherwise heighten the risk. The faster the vulnerability is closed, the sooner your risk is removed, which means that security issues require a short notification window.

One of the more frequent targets for security breaches is virtual infrastructure software. {{site.data.keyword.BluSoftlayer_notm}} infrastructure uses popular open source and partner technology to deliver its Virtual Server offering. To implement a security fix, customer servers running virtual infrastructure software might have to be taken offline to patch and restart the environment, causing disruption. To minimize the impact to customers, {{site.data.keyword.BluSoftlayer_notm}} infrastructure has recently implemented an enhancement to the notification process for virtual infrastructure: Improved communications. Customers are notified with a specific start time and a 90-minute window for each pod, which results in a shorter disruption time and more accurate timing to help you better prepare. The notification system isolates maintenance to each account, allowing {{site.data.keyword.BluSoftlayer_notm}} infrastructure to notify customers as soon as their specific hosts are serviced, which most often occurs well before the 90-minute window.

#### Multiple PODs or data centers affected
{: #cp_multi_pod}

{{site.data.keyword.BluSoftlayer_notm}} infrastructure endeavors to give longer advanced notice, unless there's an extreme urgency to implement the fix to avoid even greater secondary impact.


## Adding subscribers to event notifications
{: #cp_bpaddsub2eventnotcp}

Increasingly, IBM customers rely on {{site.data.keyword.BluSoftlayer_notm}} infrastructure services (IaaS), either by contracting with IBM for managed infrastructure services, by contracting for cloud services that run on {{site.data.keyword.BluSoftlayer_notm}} infrastructure, or by contracting directly with {{site.data.keyword.BluSoftlayer_notm}} infrastructure services. When cloud services involve infrastructure, only SoftLayer account users are authorized to receive notifications, as described in the preceding section. In some cases, you might not want the IBM Account or Managed Service teams that are involved in the operations or support of infrastructure services to access your SoftLayer accounts. A new feature has been added to the {{site.data.keyword.BluSoftlayer_notm}} infrastructure customer portal that allows you to designate a list of subscribers, for example IBM personnel, to receive notifications without having any privileges on your accounts.

To create a list of subscribers, master users can log in to their account and use the following steps:
1. Go to the [Additional Subscribers](https://cloud.ibm.com/classic/support/subscribers) page.
2. Click **Create**.
2. Enter the subscriber's email address, and click **Create**.

Email addresses added as additional subscribers receive planned and unplanned event notifications, and opened support tickets. The notifications have technical details so you can take that into consideration when you add subscribers. Because of the detailed technical nature of the notifications, the intended subscribers are those who can understand, in detail, how the notification impacts your {{site.data.keyword.BluSoftlayer_notm}} infrastructure environment. Subscribing recipients who aren't able to understand the potential client impact based on the details in the notification is counter-productive and strongly advised against.
