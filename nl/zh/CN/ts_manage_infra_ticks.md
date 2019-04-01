---

copyright:

  years: 2019

lastupdated: "2019-03-22"

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


# 有关管理 {{site.data.keyword.BluSoftlayer_notm}} 基础架构凭单的故障诊断
{: #Supporttickets_infra}

您可能会遇到有关管理 {{site.data.keyword.BluSoftlayer}} 基础架构凭单的问题。在许多情况下，只需执行几个简单的步骤即可解决这些问题。
{:shortdesc}

## 为什么无法查看帐户中的所有凭单？
{: #ts_viewtickdetails}

您无法查看帐户中的所有凭单，因为您无权查看帐户中的所有用户。
{:shortdesc}

尝试查看支持凭单时，无法查看帐户中其他用户开具的任何凭单。
{: tsSymptoms}

帐户所有者尚未为您分配许可权来查看帐户中其他用户开具的凭单。目前，您只能查看分配给您自己的凭单。
{: tsCauses}
 
如果使用的是[客户门户网站](control.softlayer.com){: new_window} ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")，您必须确保自己分配有“查看所有凭单”和“添加新用户”许可权。要解决此问题，请与帐户所有者联系以请求相应的访问权。 

如果您是帐户所有者，请完成以下步骤，为用户分配“查看所有凭单”和“添加新用户”许可权： 

1. 在菜单栏中，单击**帐户** &gt; **用户**，然后从要为其分配访问权的用户的操作菜单中，选择**门户网站许可权**。 
2. 在“门户网站许可权”页面上，选择**查看所有凭单**和**添加新用户**许可权，然后单击**编辑门户网站许可权**。
{: tsResolve}
