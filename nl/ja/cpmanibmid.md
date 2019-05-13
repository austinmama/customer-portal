---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-03"

keywords: IBMid accounts, softLayer account, IBM Cloud infrastructure authentication

subcollection: customer-portal
---

{:shortdesc: .shortdesc}
{:screen: .screen}
{:tip: .tip}
{:codeblock: .codeblock}
{:pre: .pre}
{:new_window: target="_blank"}

# {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーでの IBMid アカウントの使用
{: #customerportal_ibmid}

{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーでの認証では、{{site.data.keyword.Bluemix_notm}} 用の単一のログインを提供するために IBMid を使用するようになりました。
{:shortdesc}

既存の SoftLayer アカウントがある場合、IBMid に切り替えることができます。 この切り替えにはマイグレーション・ウィザードが役立ちます。 詳しくは、[IBMid への切り替え](/docs/account?topic=account-unifyingaccounts#switchtoIBMid)を参照してください。

## 単一の IBMid への複数の SoftLayer アカウントのマップ
{: #cp_mapmultclinfrto1ibmid}

アカウントのセットアップ時に既存の IBMid の E メール・アドレスを使用することで、単一の IBMid を複数の SoftLayer アカウントに関連付けることができます。 単一の IBMid にマップできるのは、アカウントごとに 1 つのみの {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・ユーザーです。 IBMid は、各 SoftLayer アカウント内で固有でなければなりません。 ただし、複数の SoftLayer アカウントにアクセスできる単一のユーザーが、単一の IBMid を使用して複数の SoftLayer アカウントにアクセスできます。

例えば、ある IBMid をアカウント A と B のマスター・ユーザーにマップし、さらにアカウント C と D の別のユーザーにマップできます。その IBMid にマップされた、アカウントの 1 つが、デフォルト・アカウントになります。 通常、デフォルト・アカウントは、IBMid に最初にマップされたアカウントです。 カスタマー・ポータルのアカウント切り替え機能を使用して、デフォルトのアカウントにするアカウントを切り替えることができます。

![単一の IBMid に対する複数の SoftLayer アカウント](images/ibmid-image.png)

2 要素認証が有効になっていて、複数のアカウントに IBMid でアクセスできるユーザーの場合、2 要素認証検証コードが必要です。 検証コードは、アカウントのログイン時とデフォルト・アカウントの切り替え時に、アカウントごとに必要です。
