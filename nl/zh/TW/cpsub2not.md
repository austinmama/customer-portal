---

copyright:

  years: 1994, 2018

lastupdated: "2018-02-02"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# 訂閱通知
{: #cp_bpnotifications}

有時，{{site.data.keyword.BluSoftlayer_notm}} 基礎架構中會發生需要採取動作的事件；有些是非預期的，有些則是讓 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構依其尖峰情況運作所需的計劃性維護活動。會盡可能隔離客戶與這些事件，但有時需要讓設備離線。不論對客戶的影響為何，它一律都必須是透明、及時及資訊性。
{:shortdesc}

因為您應該控制雲端體驗，所以需要維護活動的及時資訊。若要取得此資訊，您可以從客戶入口網站訂閱通知。{{site.data.keyword.BluSoftlayer_notm}} 基礎架構會將「事件管理系統 (EMS)」通知處理程序用於下列類型的重要作業事件：
* 非計劃性基礎架構問題：在特定客戶的特定情況下可能會導致運作中斷的問題
* 計劃性服務維護：讓基礎架構依最佳狀態運作所需的維護
* 已開立的支援問題單：警示已訂閱使用者其帳戶有已開立的問題單

針對雲端環境設計 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構通知，已遵循下列主要原則：
* 透過客戶入口網站自動化
* 可擴充以觸及龐大且持續成長的社群
* 目標是讓 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構僅識別受到事件影響的客戶及資源子集。

若要讓通知系統完全生效，請訂閱此處理程序。如果您有需要它的重要環境，也請建立 24 小時涵蓋範圍。

如需如何提供 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構通知的概觀，請參閱 [Improving communications for customer-affecting planned events ![外部鏈結圖示](../icons/launch-glyph.svg)](http://blog.softlayer.com/2014/improving-communications-customer-affecting-planned-events){:new_window}。

## 通知計時原則
{: #cp_bpgsnotiftimpol}

{{site.data.keyword.BluSoftlayer_notm}} 基礎架構事先提供給使用者來處理擱置事件的時間期間會不同（取決於事件是非計劃性基礎架構問題還是計劃性或排定的維護）。一般而言，{{site.data.keyword.BluSoftlayer_notm}} 基礎架構原則是盡快補救問題，以移除或最小化未來可能會產生較大影響的問題的風險。這表示有時即使是執行計劃性維護，也只提前很短的時間進行通知。

### 原則概觀
{: #cp_bpgsnotifpolover}

您會收到下列類型的運作中斷或問題的通知，如下列各節中所述。

#### 非計劃性問題或運作中斷
在了解與基礎架構範圍、暫行解決方法或解決預估值相關的資訊之後，{{site.data.keyword.BluSoftlayer_notm}} 會盡快地與受影響的客戶通訊。及時通訊可提供規劃偶發事件所需的資訊，以及確認 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構正在處理問題。

#### 排定的維護
{{site.data.keyword.BluSoftlayer_notm}} 基礎架構會事先提供排定維護的通知。有時 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構維護是緊急事件，通知提前的時間更短。我們的目標始終是提供合理的通知提前時間以容許您規劃偶發事件與在升級或加強基礎架構兩者間找到理想平衡，從而提高整體穩定性或增加所需功能。

#### 安全漏洞
{{site.data.keyword.BluSoftlayer_notm}} 基礎架構會隔離受影響的區域、建立修補程式來關閉漏洞，以及測試修補程式，確保不會影響附屬功能。通常，此工作是與另一個可能會提供受影響技術的部分的供應商一起完成。可盡快保護大眾的安全修補程式一般會有大眾禁止通知，但這需要縮短提前通知期間。{{site.data.keyword.BluSoftlayer_notm}} 基礎架構會在大眾知道問題之前跨受影響的基礎架構來實作修補程式，否則會提高風險。漏洞關閉的越快，風險移除就越快，這表示安全問題需要短暫的通知時間範圍。

安全侵害的其中一個較常見目標是虛擬基礎架構軟體。{{site.data.keyword.BluSoftlayer_notm}} 基礎架構會使用常用的開放程式碼及夥伴技術，來提供其「虛擬伺服器」供應項目。為了實作安全修正程式，執行虛擬基礎架構軟體的客戶伺服器可能需要離線進行修補並將環境重新開機，因而導致毀壞。為了最小化對客戶的影響，{{site.data.keyword.BluSoftlayer_notm}} 基礎架構最近已加強虛擬基礎架構的通知處理程序：改良的通訊。向客戶通知特定開始時間以及每一個 Pod 的 90 分鐘時間範圍，進而導致較短的毀壞時間以及更精確的計時，以協助您更恰當地做好準備。通知系統會隔離每一個帳戶的維護，容許 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構在服務其特定主機（最常發生在 90 分鐘時間範圍之前）時盡快通知客戶。

#### 影響多個 POD 或資料中心
除非十分緊急需要實作修正程式來避免更大的次要影響，否則 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構會致力於提前更長的時間先通知。


## 將訂閱者新增至事件通知
{: #cp_bpaddsub2eventnotcp}

IBM 客戶逐漸地依賴 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構服務 (IaaS)，不論是與 IBM 簽約以使用受管理基礎架構服務、簽約以使用在 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構上執行的雲端服務，或是直接簽約使用 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構服務。雲端服務涉及基礎架構時，只有 SoftLayer 帳戶使用者才有權接收通知（如上節所述）。在部分情況下，您可能不希望 IBM 帳戶或受管理服務團隊參與操作或支援基礎架構服務，來存取您的 SoftLayer 帳戶。{{site.data.keyword.BluSoftlayer_notm}} 基礎架構客戶入口網站中已新增特性，容許您指定不需要有您帳戶的任何專用權即可接收通知的訂閱者清單（例如 IBM 人員）。

若要指定訂閱者清單，主要使用者可以登入其客戶入口網站帳戶，以及使用下列步驟：
1. 從功能表列中，按一下**帳戶** > **管理** > **訂閱**。
2. 選擇要新增訂閱者的事件類型。
2. 從蹦現視窗中，新增一個以上的電子郵件位址。電子郵件位址可以是 IBM 或非 IBM 的電子郵件位址。
3. 按一下**建立**。

新增為其他訂閱者的電子郵件位址會收到計劃性及非計劃性事件通知，以及已開立的支援問題單。通知會包含技術詳細資料，因此您在新增訂閱者時應該考慮到它。基於通知的詳細技術本質，預期的訂閱者可以詳細瞭解通知對 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構環境的影響。無法根據通知中詳細資料瞭解潛在客戶影響的訂閱收件者將適得其反，而且強烈建議不予使用。