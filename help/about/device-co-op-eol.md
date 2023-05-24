---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op;生命週期結束
title: Device Co-op生命週期結束常見問題集
description: 了解 Device Co-op 的生命週期結束計劃。
source-git-commit: 8c372964824a33f31a5a3b11a38ebe1a49df35ea
workflow-type: tm+mt
source-wordcount: '1106'
ht-degree: 88%

---

# Device Co-op生命週期結束常見問題集

本檔案提供有關Adobe Experience Cloud Device Co-op生命週期結束(EOL)計畫的常見問題解答。 當此計劃生效後，Adobe 將於 [Experience Cloud 版本資訊](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hant)和[優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)中提供進一步的通知。

Device Co-op是可讓參與者共同合作，以在數位接觸點間更有效識別消費者的計畫，同時確保最高層級的隱私權和透明度。

## 常見問題集

以下是有關 [!DNL Device Co-op] EOL 計劃的常見問題解答清單。

## 為什麼 [!DNL Device Co-op] 會被淘汰？

AdTech 環境即將發生的變化，預計將導致 [!DNL Device Co-op] 在未來幾年成為過時的解決方案。[!DNL Device Co-op] 主要是由第三方 Cookie 所組成，而 [!DNL Google's] 宣佈他們將在 2022 年之前於 [!DNL Google Chrome] 上封鎖第三方 Cookie，這將會降低 [!DNL Device Co-op] 的有效性。[!DNL Chrome] 擁有約 65% 的瀏覽器市場佔有率，其他主要瀏覽器已實作對第三方 Cookie 的封鎖行為。一旦 [!DNL Chrome] 封鎖第三方 Cookie，大部分第三方 Cookie 都會被封鎖，而 [!DNL Device Co-op] 將會被淘汰。

## Adobe 為什麼現在要終止 [!DNL Device Co-op] 註冊？

我們即將終止註冊，是為了避免由於第三方 Cookie 即將發生的產業變化，而導致無法滿足客戶期望的風險。[!DNL Device Co-op] 需要幾個月的時間來準備，另外也需要幾個月的時間來從服務中提取價值。目前任何進一步的註冊，都可能導致品牌無法體驗到 [!DNL Device Co-op] 的完整價值。

## 在 2022 年 7 月，Google 已宣佈將 Chrome 上的第三方 Cookie 淘汰計劃延遲到 2024 年。這是否會影響到 [!DNL Device Co-op] 的 EOL 計劃？

不會，Adobe 的 [!DNL Device Co-op] EOL 計劃依然保持不變，不會延長。

## 新客戶是否可以註冊？

自 2021 年 6 月 11 日起，Adobe 已不再接受新客戶註冊 [!DNL Device Co-op]。

## 現有合約是否仍能續約？

自 2021 年 6 月 11 日起，Adobe 已不再提供 [!DNL Device Co-op] 合約的續約。如果您想要繼續使用 [!DNL Device Co-op] 服務，可以根據最新的授權條款繼續使用，直到方案結束為止。

## [!DNL Device Co-op] 方案的確切結束日期是哪一天？

[!DNL Device Co-op] 方案將於 2022 年結束。具體的時間和日期取決於 [!DNL Google] 何時開始封鎖第三方 Cookie。其淘汰作業預計將於 2022 年 9 月開始。

## 哪些應用程式會受到 Device Co-op 生命週期結束的影響？

以下應用程式會受到 [!DNL Device Co-op] 生命週期結束程序的影響：

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=zh-Hant)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=zh-Hant)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=zh-Hant)

## 有哪些選項可用來替代 [!DNL Device Co-op]？

### [!DNL Analytics]

您可以使用[!DNL Analytics] [跨裝置分析 (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 功能，因為此功能可支援 Adobe Experience Platform 身分識別服務[專用圖表](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=zh-Hant)和[欄位式拼接](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=zh-Hant)。

### [!DNL Audience Manager]

[!DNL Audience Manager] 會維護與第三方裝置圖表合作夥伴的整合，包括 [!DNL LiveRamp] 和 [!DNL Tapad]，儘管您必須直接與圖表合作夥伴建立商業關係，才能利用 [!DNL Audience Manager]。所有客戶皆應更新任何合作設定檔合併規則，以使用除了 [!DNL Device Co-op.] 以外的任何選項

### [!DNL Real-time Customer Data Platform]

我們目前沒有修改最新 [!DNL Audience Manager Data Management Platform] (DMP) 的計劃。不過，停用第三方 Cookie 可能會給大多數 DMP 使用者帶來許多挑戰。為了幫助客戶改進他們的資料管理做法，Adobe 鼓勵減少對識別碼的依賴，這些識別碼將從明年起受到限制。行銷團隊必須制定第一方資料策略，聚焦於包含個人識別資訊 (PII) 的持久性識別碼，這可以透過 [!DNL Real-time Customer Data Platform] (Real-time CDP) 加以解決。

[!DNL Real-time CDP] 藉由擴充可用於建立對象的識別碼組來包含 PII，以減少對於第三方 Cookie 和裝置 ID 的依賴。[!DNL Real-time CDP] 的基礎部分是即時客戶設定檔，它能即時整合個人屬性資料與行為資料，並允許行銷人員透過專利的資料治理控制項，建立豐富的對象區段。與 [!DNL Audience Manager] 一樣，[!DNL Real-time CDP] 也能提供見解及個人化使用案例，但會同時產生更細微的個人層級見解，而且可以將對象啟用到更廣泛的目標範圍 (橫跨廣告技術和行銷技術)，包括付費媒體、社交媒體、電子郵件和客戶系統。

[!DNL Real-time CDP] 也包括對 [Adobe Experience Platform Segment Match (Beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=zh-Hant) 的存取權，此服務可讓品牌透過合作關係擴充其自身的第一方資料集，並獲得改良的見解和個人化。

### [!DNL Target]

目前 [!DNL Target] 沒有可用的替代方案，因為 [!DNL Target] 提供決定性的跨裝置身分識別拼接功能 `mbox3rdPartyId`，其運作方式類似於 Adobe 的客戶 ID。此功能可讓 [!DNL Target] 客戶在傳入通道中所完成的各項 [!DNL Target] 測試和個人化中合併設定檔和活動參與。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客戶無法再將 [!DNL Device Co-op] 用於跨裝置對象目標定位和測量。有了 [!DNL Advertising Cloud]，您還是可以利用 Adobe 與 [!DNL LiveRamp] 的 [!DNL Device Graph] 合作關係，在 [!DNL LiveRamp's] 的能力和規模範圍內繼續執行這些功能。您必須允許正在使用 [!DNL Device Co-op] 的行銷活動結束，然後切換到 [!DNL LiveRamp] 裝置圖表供應商，或是停止使用以人物為基礎的目標定位。

## 哪些現有功能和實作可以幫助我準備好迎接無 Cookie 的未來？

您現有的訪客ID服務實作可支援Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). 如果您的現有宣告ID是雜湊電子郵件，則可使用此資訊來強化下列功能：

- [!DNL Audience Manager][以人物為基礎的目標](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)。
- [Experience Platform Segment Match (Beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=zh-Hant)。

## 我是否可以保留 [!DNL Device Co-op] 中的資料？

對象 [!DNL Audience Manager] 和 [!DNL Advertising Cloud] 使用者，資料來自 [!DNL Device Co-op] 無法傳輸至協力廠商圖形。 [!DNL Device Co-op] 資料只會針對 [!DNL Analytics Ultimate] 使用者移轉，其方式是搭配 [!DNL Device Co-op] 使用 CDA 以切換到欄位式拼接。所有其他解決方案都不會移轉其資料。

## 是否必須採用其他功能？

雖然採用其他Adobe功能並非強制性，但您應儘快開始實施其他功能，以提前獲得時間並進行適當的協調 [!DNL Device Co-op] 淘汰。

## 如果我選擇這麼做的話，何時必須採用替代解決方案？

採用其他功能不是強制性的。只有當您想要繼續處理先前由 [!DNL Device Co-op] 處理的使用案例時，才建議使用。如果您選擇採用其他功能，您必須在 2022 年 [!DNL Device Co-op] 方案結束之前這樣做 (確切的時間有待公佈)。

## 採用需要多久的時間？

這取決於功能。舉例來說，如果搭配 [!DNL Device Co-op] 使用跨裝置分析的 Analytics Ultimate 客戶需要移轉到即時私人裝置圖表或欄位式拼接，則採用需要一些時間。
