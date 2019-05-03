---

copyright:

  years: 2019

lastupdated: "2019-05-03"

keywords: help managing tickets, resolve issues managing tickets, trouble working with tickets

subcollection: customer-portal

---


{:tsSymptoms: .tsSymptoms}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:new_window: target="_blank"}
{:troubleshoot: data-hd-content-type='troubleshoot'}


# Troubleshooting for managing tickets with {{site.data.keyword.BluSoftlayer_notm}} infrastructure
{: #Supporttickets_infra}

You might encounter problems with managing tickets with {{site.data.keyword.BluSoftlayer}} infrastructure. In many cases, you can recover from these problems by following a few easy steps.
{:shortdesc}

## Why can't I view all tickets in the account?
{: #ts_viewtickdetails}

You can't view all of the tickets in the account, because you don't have access to view all users in the account. 
{:shortdesc}

When you try to view the support tickets, you can't view any tickets that are opened by other users in the account. 
{: tsSymptoms}

The account owner hasn't assigned you the permissions to view tickets in the account opened by other users. At this time, you can only view tickets that are assigned to yourself. 
{: tsCauses}
 
If you’re using the [customer portal](https://control.softlayer.com/){: new_window} ![External link icon](../icons/launch-glyph.svg "External link icon"), you must make sure you're assigned the View All Tickets and Add New User permissions. To resolve the issue, contact the account owner to request the appropriate access. 

If you're an account owner, complete the following steps to assign a user View All Tickets and Add New User permissions: 

1. From the menu bar, click **Account** &gt; **Users** and select **Portal permissions** from the actions menu of the user you wish to assign access. 
2. On the Portal Permissions page, select **View All Tickets** and **Add New User Permissions**, and then click **Edit Portal Permissions**. 
{: tsResolve}
