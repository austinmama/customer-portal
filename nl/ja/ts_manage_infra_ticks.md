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


# {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーでのチケットの管理に関するトラブルシューティング
{: #Supporttickets_infra}

{{site.data.keyword.BluSoftlayer}} インフラストラクチャーでチケットを管理するときに、問題が発生することがあります。 多くの場合、いくつかの簡単なステップを実行することで、これらの問題から復旧することが可能です。
{:shortdesc}

## アカウント内のすべてのチケットを表示できないのはなぜですか?
{: #ts_viewtickdetails}

アカウント内のすべてのユーザーを表示する権限がないため、アカウント内のすべてのチケットを表示することができません。 
{:shortdesc}

サポート・チケットを表示しようとしたとき、アカウント内の他のユーザーによって開かれたチケットを表示できません。 
{: tsSymptoms}

アカウント所有者には、他のユーザーが開いたアカウントのチケットを表示するための許可が割り当てられていません。 現時点では、自分に割り当てられているチケットのみを表示できます。 
{: tsCauses}
 
[カスタマー・ポータル](https://control.softlayer.com/){: new_window} ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン") を使用している場合は、確実に「すべてのチケットの表示」許可と「新規ユーザーの追加」許可が割り当てられている必要があります。 この問題を解決するには、アカウント所有者に連絡して適切なアクセス権限を要求してください。 

アカウント所有者の場合は、以下の手順を実行して、ユーザーに「すべてのチケットの表示」許可と「新規ユーザーの追加」許可を割り当てます。 

1. メニュー・バーで**「アカウント」** &gt; **「ユーザー」**をクリックし、アクセス権限を割り当てるユーザーの「アクション」メニューから**「ポータル許可 (Portal permissions)」**を選択します。 
2. 「ポータル許可 (Portal permissions)」ページで、**「すべてのチケットの表示」**と**「新規ユーザー許可の追加 (Add New User Permissions)」**を選択し、**「ポータル許可の編集 (Edit Portal Permissions)」**をクリックします。 
{: tsResolve}
