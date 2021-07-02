---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op；終止服務
title: Device Co-op服務終止常見問題集
description: 了解Device Co-op的服務終止計畫。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: c19e8425d5d6c2498186c19929907d2ee5327b31
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 2%

---

# Device Co-op服務終止常見問題集

本檔案提供Adobe Experience Cloud Device Co-op服務終止(EOL)計畫常見問題的解答。 此計畫生效後，Adobe將在[Experience Cloud發行說明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hant)和[優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)中提供進階通知。

## 常見問題集

以下是關於[!DNL Device Co-op] EOL計畫的常見問題解答清單。

## 為何[!DNL Device Co-op]被廢止？

AdTech環境即將發生的變更，預計會在未來數年內導致[!DNL Device Co-op]成為過時的解決方案。 [!DNL Device Co-op] 主要包含協力廠商cookie, [!DNL Google's] 並宣佈將於2022年前封鎖協力廠 [!DNL Google Chrome] 商cookie，將會降低 [!DNL Device Co-op]效率。[!DNL Chrome] 擁有約65%的瀏覽器市場份額，而其他主要瀏覽器已實作封鎖第三方Cookie的功能。一旦[!DNL Chrome]封鎖第三方Cookie，大部分的第三方Cookie都會遭到封鎖，而且[!DNL Device Co-op]將會變成淘汰。

## 為什麼Adobe現在結束[!DNL Device Co-op]註冊？

註冊即將終止，以避免因第三方Cookie的業界即將變更而無法達到客戶期望的風險。 [!DNL Device Co-op] 需要幾個月的時間才能從服務中獲得價值。此時任何進一步註冊都可能導致品牌未達到[!DNL Device Co-op]的完整值。

## 新客戶能註冊嗎？

自2021年6月11日起，Adobe將不再接受[!DNL Device Co-op]的新註冊。

## 現有合同是否續訂？

自2021年6月11日起，Adobe將不再續約[!DNL Device Co-op]合約。 如果您希望繼續使用[!DNL Device Co-op]服務，則可繼續使用當前許可條款，直到程式結束。

## [!DNL Device Co-op]程式的確切結束日期是多少？

[!DNL Device Co-op]程式將於2022年結束。 具體的時間和日期取決於[!DNL Google]何時開始封鎖第三方Cookie。

## 終止Device Co-op會影響哪些應用程式？

[!DNL Device Co-op]生命週期結束過程將影響以下應用程式：

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## 除了[!DNL Device Co-op]之外，我有哪些替代選項？

### [!DNL Analytics]

您可以使用[!DNL Analytics] [跨裝置分析(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)功能，因為它同時支援Adobe Experience Platform Identity Service [私密圖表](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en)和[欄位匯整](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en)。

### [!DNL Audience Manager]

[!DNL Audience Manager] 維護與協力廠商裝置圖表合作夥伴( [!DNL LiveRamp] 包括 [!DNL Tapad]和)的整合，不過您必須直接與圖表合作夥伴建立商業關係，才能充分運用 [!DNL Audience Manager]。

### [!DNL Real-time Customer Data Platform]

沒有修改當前[!DNL Audience Manager Data Management Platform](DMP)的計畫。 不過，取代協力廠商Cookie可能會對大部分DMP使用者造成規模挑戰。 為協助客戶改進其資料管理作法，Adobe鼓勵減少對識別碼的依賴，這些識別碼在來年將面臨限制。 行銷團隊必須建立第一方資料策略，著重於包含個人識別資訊(PII)的持久識別碼，這可透過[!DNL Real-time Customer Data Platform]（即時CDP）解決。

[!DNL Real-time CDP] 將可用於建立受眾的識別碼集擴充至包含PII，以減少對協力廠商cookie和裝置ID的相依性。[!DNL Real-time CDP]的基礎是即時客戶設定檔，它將人員屬性資料與行為資料即時結合在一起，讓行銷人員能透過獲專利的資料控管控制功能建立豐富的受眾區段。 如同[!DNL Audience Manager],[!DNL Real-time CDP]可提供深入分析和個人化使用案例，但也可產生更精細的人員層級深入分析，並可針對橫跨廣告技術和行銷技術（包括付費媒體、社交媒體、電子郵件和客戶系統）的更廣泛目的地啟用對象。

[!DNL Real-time CDP] 也包含對 [Adobe Experience Platform區段比對(Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)的存取，可讓品牌透過合作關係擴充自己的第一方資料集，並達成改善的前瞻分析和個人化。

### [!DNL Target]

目前沒有可用於[!DNL Target]的替代方案，因為[!DNL Target]提供確定性的跨裝置身分拼接功能，稱為`mbox3rdPartyId`，其功能與Adobe的客戶ID類似。 此功能可讓[!DNL Target]客戶合併在傳入管道中完成之[!DNL Target]測試和個人化的設定檔與活動參與率。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客戶將無法再使用於 [!DNL Device Co-op] 跨裝置對象鎖定目標和測量。使用[!DNL Advertising Cloud]，您仍然能夠利用Adobe與[!DNL LiveRamp]的[!DNL Device Graph]合作關係，以在[!DNL LiveRamp’s]能力和規模方面繼續執行這些功能。 您必須允許使用[!DNL Device Co-op]的促銷活動結束，然後切換至[!DNL LiveRamp]裝置圖表提供者，或不再使用以人物為基礎的定位。

## 哪些現有功能和實作可協助我為沒有Cookie的未來做準備？

您現有的訪客ID服務實作可提供Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)的支援。 如果您現有的宣告ID是雜湊電子郵件，則可使用此ID來支援下列功能：

- [!DNL Audience Manager] [以人物為基礎的目的地](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform區段比對(Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)。

## 我可以保留[!DNL Device Co-op]中的資料嗎？

對於[!DNL Audience Manager]和[!DNL Advertising Cloud]使用者，來自[!DNL Device Co-op]的資料將無法傳輸至第三方圖表。 [!DNL Device Co-op] 只有使用CDA，並切換 [!DNL Analytics Ultimate] 至依欄位匯整的使 [!DNL Device Co-op] 用者才會移轉資料。其他所有解決方案都不會移轉其資料。

## 是否強制採用其他功能？

雖然不強制採用其他Adobe功能，但您應盡快開始實作其他功能，以在[!DNL Device Co-op]淘汰之前提供時間和適當的協調。

## 如果我選擇採用替代方案，我何時必須採用？

採用其他功能並非強制性。 只有當您希望繼續處理[!DNL Device Co-op]已處理的使用案例時，才建議使用。 如果您選擇採用其他功能，則必須在[!DNL Device Co-op]程式結束前在2022年之前（要宣佈的確切時間）採用。

## 收養要多久？

這取決於功能。 例如，使用[!DNL Device Co-op]跨裝置分析的Analytics Ultimate客戶若需要移轉至即時專用裝置圖表或依欄位匯整，則採用起來需要一些時間。
