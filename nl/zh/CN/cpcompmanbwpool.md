---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-16"

keywords: bandwidth pool, bandwidth usage, Add Servers list, optimizing badwidth 

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# 优化带宽使用情况
{: #cp_manbdwpool}

从全球 IBM Cloud 数据中心传出的公用数据网络流量按出站带宽费用进行评估。费用取决于传输数据的资源所在的位置、传出的数据量，以及所购买 IBM Cloud 产品有资格使用的任何带宽限额。
{:shortdesc} 

客户可以通过将服务器的所有带宽“汇集”到带宽池来优化带宽使用情况。带宽池中服务器的带宽平均量会作为总体进行汇总，并且仅当所有服务器的总带宽超过为所有服务器分配的总带宽而不是按单个服务器级别计量时，才会计算平均量。
 

下表中列出了池定义： 

| 池        | 位置          |
| ------------- |:-------------:|
| 美国    | DAL01<br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07<br/><br/>DAL09<br/><br/>DAL10<br/><br/>DAL12<br/><br/>DAL13<br/><br/>HOU02<br/><br/>MON01<br/><br/>SEA01<br/><br/>SJC01<br/><br/>SJC03<br/><br/>SJC04<br/><br/>TOR01<br/><br/>WDC01<br/><br/>WDC04<br/><br/>WDC06<br/><br/>WDC07|
| 阿姆斯特丹和伦敦 | AMS01<br/><br/>AMS03<br/><br/>LON01<br/><br/>LON02<br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01 |
| 澳大利亚 | MEL01<br/><br/>SYD01<br/><br/>SYD04<br/><br/>SYD05 |
| 巴西 |SAO01  |
| 法兰克福| FRA02<br/><br/>FRA04<br/><br/>FRA05 |
| 印度 |CHE01  |
| 意大利 |MIL01  |
| 韩国 |SEO01  | 
| 墨西哥 |MEX01  | 
| 挪威 |OSL01  | 
| 新加坡、中国香港特别行政区和东京 | HKG02<br/><br/>SNG01<br/><br/>TOK02<br/><br/>TOK04<br/><br/>TOK05 |
{:caption="表 1. 池定义" caption-side="top"}


## 修改带宽池
{: #cp_modbdwpool}

创建带宽池后，如果您是授权用户，那么可以随时访问该池。您可以访问带宽池来查看与池关联的设备，将设备添加到池中或从池中除去设备。使用以下步骤访问池：

1. 使用您的唯一凭证登录到客户门户网站。
2. 从菜单中选择**网络** > **带宽** > **池**，以访问“带宽池”窗口。
3. 单击**池名**以访问池。这将显示与该池关联的每个设备。
4. 在**修改**选项卡中，可以重命名池，添加设备或从池中除去设备：
  * 要重命名池，请在包含当前池名的字段中输入新的池名。
  * 要向池添加设备，请从**添加服务器**列表中选择设备名，然后单击**选择**。
  * 要从池中除去设备，请从**除去服务器**列表中选择设备，然后单击**选择**。
5. 单击**修改机架**。
6. 单击**查看所有带宽池**链接以返回到“带宽池”窗口。
