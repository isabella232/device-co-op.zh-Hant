---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op；終止服務
title: Device Co-op服務終止常見問題集
description: 了解Device Co-op的服務終止計畫。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: 8896718ce5fec25cb72f7a2a5ccb4573433e0bb1
workflow-type: tm+mt
source-wordcount: '1019'
ht-degree: 4%

---

# Device Co-op服務終止常見問題集

本檔案提供Adobe Experience Cloud Device Co-op服務終止(EOL)計畫常見問題的解答。 當此計畫生效時，Adobe會在 [Experience Cloud發行說明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hant) 和 [優先順序產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html).

## 常見問題集

以下是關於 [!DNL Device Co-op] EOL計畫。

## 為什麼 [!DNL Device Co-op] 被廢止？

AdTech環境即將進行的變更預計會導致 [!DNL Device Co-op] 成為未來幾年的過時解決方案。 [!DNL Device Co-op] 主要由第三方cookie組成，且 [!DNL Google's] 宣告他們將封鎖 [!DNL Google Chrome] 到2022年， [!DNL Device Co-op]. [!DNL Chrome] 擁有約65%的瀏覽器市場份額，而其他主要瀏覽器已實作封鎖第三方Cookie的功能。 一次 [!DNL Chrome] 封鎖第三方cookie，則大部分的第三方cookie都會遭到封鎖，且 [!DNL Device Co-op] 會被淘汰。

## 為什麼Adobe結束 [!DNL Device Co-op] 現在註冊？

註冊即將終止，以避免因第三方Cookie的業界即將變更而無法達到客戶期望的風險。 [!DNL Device Co-op] 需要幾個月的時間才能從服務中獲得價值。 此時，任何進一步註冊都可能導致品牌未達到 [!DNL Device Co-op].

## 新客戶能註冊嗎？

自2021年6月11日起，Adobe將不再接受 [!DNL Device Co-op].

## 現有合同是否續訂？

自2021年6月11日起，Adobe將不再續約 [!DNL Device Co-op] 合約。 如果您想繼續使用 [!DNL Device Co-op] 服務，您可以繼續根據目前的授權條款執行此操作，直到程式結束為止。

## 確切的結束日期為 [!DNL Device Co-op] 程式？

此 [!DNL Device Co-op] 計畫將於2022年結束。 特定的時間和日期取決於 [!DNL Google] 開始封鎖第三方cookie。

## 終止Device Co-op會影響哪些應用程式？

下列應用程式將受 [!DNL Device Co-op] 終止程式：

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## 我有哪些選項可替代 [!DNL Device Co-op]?

### [!DNL Analytics]

您可以使用 [!DNL Analytics] [跨裝置分析(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 功能，因為它同時支援Adobe Experience Platform Identity Service [專用圖表](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) 和 [依欄位匯整](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en).

### [!DNL Audience Manager]

[!DNL Audience Manager] 維護與協力廠商裝置圖表合作夥伴的整合，包括 [!DNL LiveRamp] 和 [!DNL Tapad]，但您必須直接與圖表合作夥伴建立商業關係，才能運用 [!DNL Audience Manager].

### [!DNL Real-time Customer Data Platform]

沒有修改當前 [!DNL Audience Manager Data Management Platform] (DMP)。 不過，取代協力廠商Cookie可能會對大部分DMP使用者造成規模挑戰。 為協助客戶改進其資料管理作法，Adobe鼓勵減少對識別碼的依賴，這些識別碼在來年將面臨限制。 行銷團隊必須建立第一方資料策略，著重於包含個人識別資訊(PII)的耐用識別碼，這可透過 [!DNL Real-time Customer Data Platform] （即時CDP）。

[!DNL Real-time CDP] 將可用於建立受眾的識別碼集擴充至包含PII，以減少對協力廠商cookie和裝置ID的相依性。 基礎 [!DNL Real-time CDP] 是即時客戶設定檔，可即時將人員屬性資料與行為資料結合在一起，並可讓行銷人員使用獲專利的資料控管功能建立豐富的對象區段。 贊 [!DNL Audience Manager], [!DNL Real-time CDP] 可支援前瞻分析和個人化使用案例，也可產生更精細的人員層級前瞻分析，並可針對橫跨廣告技術和行銷技術（包括付費媒體、社交媒體、電子郵件和客戶系統）的更廣泛目的地啟用對象。

[!DNL Real-time CDP] 也將包含存取權 [Adobe Experience Platform區段比對（測試版）](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en)，這可讓品牌透過合作關係擴展自己的第一方資料集，並達成改善的前瞻分析和個人化。

### [!DNL Target]

目前沒有可供 [!DNL Target] 因為 [!DNL Target] 提供決定性的跨裝置身分匯整功能，稱為 `mbox3rdPartyId`，其功能與Adobe的客戶ID類似。 此功能可讓 [!DNL Target] 合併設定檔和活動參與率的客戶 [!DNL Target] 在傳入頻道中完成的測試和個人化。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客戶將無法再使用 [!DNL Device Co-op] 用於跨裝置對象鎖定目標和測量。 使用 [!DNL Advertising Cloud]，您仍可運用Adobe [!DNL Device Graph] 與 [!DNL LiveRamp] 繼續履行這些職能 [!DNL LiveRamp’s] 能力和規模。 您必須允許使用 [!DNL Device Co-op] 結束，然後切換到 [!DNL LiveRamp] 裝置圖表提供者，或不再使用以人物為基礎的鎖定目標。

## 哪些現有功能和實作可協助我為沒有Cookie的未來做準備？

您現有的訪客ID服務實作可提供Analytics的強大功能 [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). 如果您現有的宣告ID是雜湊電子郵件，則可使用此ID來支援下列功能：

- [!DNL Audience Manager] [以人物為基礎的目的地](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform區段符合（測試版）](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en).

## 我是否可以將資料 [!DNL Device Co-op]?

針對 [!DNL Audience Manager] 和 [!DNL Advertising Cloud] 使用者、來自 [!DNL Device Co-op] 將無法傳輸至協力廠商圖表。 [!DNL Device Co-op] 資料只會移轉 [!DNL Analytics Ultimate] 使用CDA搭配 [!DNL Device Co-op] 切換為依欄位匯整。 其他所有解決方案都不會移轉其資料。

## 是否強制採用其他功能？

雖然採用其他Adobe功能並非強制性，但您應盡快開始實作其他功能，以在 [!DNL Device Co-op] 淘汰。

## 如果我選擇採用替代方案，我何時必須採用？

採用其他功能並非強制性。 只有當您希望繼續處理已處理的使用案例時，才建議使用 [!DNL Device Co-op]. 如果您選擇採用其他功能，則必須在2022年前採用（確切宣佈時間）, [!DNL Device Co-op] 程式結束。

## 收養要多久？

這取決於功能。 例如，如果Analytics Ultimate客戶使用跨裝置分析搭配 [!DNL Device Co-op] 需要移轉至「即時專用裝置圖表」或「依欄位匯整」，採用需要一些時間。
