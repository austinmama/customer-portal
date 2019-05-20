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


# 대역폭 사용량 최적화
{: #cp_manbdwpool}

전세계적으로 IBM Cloud 데이터 센터에서 아웃바운드로 전송된 공용 데이터 네트워크 트래픽에는 아웃바운드 대역폭 비용이 책정됩니다. 비용은 데이터를 전송하는 리소스가 상주하는 위치, 유출된 데이터의 양, 그리고 구매한 IBM Cloud 제품이 적격인 대역폭 할당량에 따라 결정됩니다. 
{:shortdesc} 

고객은 서버에 대해 모든 대역폭을 대역폭 풀로 함께 "풀링"하여 대역폭 사용량을 최적화할 수 있습니다. 대역폭 풀에서 서버의 대역폭 평균은 전체로 합산되며, 개별 서버 레벨에서의 계량과는 대조적으로 모든 서버의 총 대역폭이 모든 서버의 총 할당 대역폭을 초과하는 경우에만 평균이 계산됩니다. 

풀 정의는 다음 표에 나열되어 있습니다. 

| 풀      | 위치          |
| ------------- |:-------------:|
|미국    | DAL01<br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07<br/><br/>DAL09<br/><br/>DAL10<br/><br/>DAL12<br/><br/>DAL13<br/><br/>HOU02<br/><br/>MON01<br/><br/>SEA01<br/><br/>SJC01<br/><br/>SJC03<br/><br/>SJC04<br/><br/>TOR01<br/><br/>WDC01<br/><br/>WDC04<br/><br/>WDC06<br/><br/>WDC07|
| 암스테르담 및 런던 | AMS01<br/><br/>AMS03<br/><br/>LON01<br/><br/>LON02<br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01 |
|오스트레일리아 | MEL01<br/><br/>SYD01<br/><br/>SYD04<br/><br/>SYD05 |
|브라질 |SAO01 |
| 프랑크푸르트 | FRA02<br/><br/>FRA04<br/><br/>FRA05 |
|인도 |CHE01 |
|이탈리아 |MIL01 |
|대한민국 |SEO01 | 
|멕시코 |MEX01 | 
|노르웨이 |OSL01 | 
| 싱가포르, 홍콩 및 도쿄 | HKG02<br/><br/>SNG01<br/><br/>TOK02<br/><br/>TOK04<br/><br/>TOK05 |
{:caption="표 1. 풀 정의" caption-side="top"}


## 대역폭 풀 수정
{: #cp_modbdwpool}

대역폭 풀이 작성된 후 권한이 부여되면 언제든지 풀에 액세스할 수 있습니다. 풀과 연관된 디바이스를 보거나 디바이스를 풀에 추가하거나 풀에서 디바이스를 제거하기 위해 대역폭 풀에 액세스합니다. 풀에 액세스하려면 다음 단계를 수행하십시오.

1. 고유 인증 정보를 사용하여 고객 포털에 로그인하십시오.
2. 메뉴에서 **네트워크** > **대역폭** > **풀**을 선택하여 대역폭 풀 창에 액세스하십시오.
3. **풀 이름**을 클릭하여 풀에 액세스하십시오. 풀과 연관된 각 디바이스가 표시됩니다.
4. **수정** 탭에서 풀의 이름을 변경하거나 디바이스를 추거하거나 풀에서 디바이스를 제거할 수 있습니다.
  * 풀의 이름을 변경하려면 현재 풀 이름이 있는 필드에 새 풀 이름을 입력하십시오.
  * 디바이스를 풀에 추가하려면 **서버 추가** 목록에서 디바이스 이름을 선택한 후 **선택**을 클릭하십시오.
  * 풀에서 디바이스를 제거하려면 **서버 제거** 목록에서 디바이스를 선택한 후 **선택**을 클릭하십시오.
5. **랙 수정**을 클릭하십시오.
6. **모든 대역폭 풀 보기** 링크를 클릭하여 대역폭 풀 창으로 돌아가십시오.
