---
keywords: adobe體驗雲；Adobe Experience Cloud；設備合作；設備合作；壽命結束
title: 設備合作停產常見問題
description: 瞭解設備合作計畫的報廢計畫。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: 952fe1bc73efd99812f3f2950b009ff8dcd83ae1
workflow-type: tm+mt
source-wordcount: '1053'
ht-degree: 4%

---

# 設備合作停產常見問題

本文檔提供有關Adobe Experience Cloud設備合作計畫(EOL)計畫的常見問題的答案。 此計畫生效後，Adobe將在 [Experience Cloud發行說明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hant) 和 [優先順序產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。

## 常見問題集

以下是對有關Windows Server的 [!DNL Device Co-op] EOL計畫。

## 為什麼 [!DNL Device Co-op] 正被棄用？

AdTech環境即將發生的變化預計將導致 [!DNL Device Co-op] 成為未來幾年的過時解決方案。 [!DNL Device Co-op] 主要由第三方餅乾和 [!DNL Google's] 宣佈他們將阻止第三方Cookie [!DNL Google Chrome] 到2022年， [!DNL Device Co-op]。 [!DNL Chrome] 擁有約65%的瀏覽器市場份額，其他主要瀏覽器已經實施了第三方cookie的攔截。 一次 [!DNL Chrome] 阻止第三方Cookie，大多數第三方Cookie將被阻止並 [!DNL Device Co-op] 會被淘汰。

## 為什麼Adobe結束 [!DNL Device Co-op] 立即註冊？

註冊結束是為了防止由於即將到來的圍繞第三方Cookie的行業變化而達不到客戶預期的風險。 [!DNL Device Co-op] 要準備好幾個月，再花幾個月時間從服務中獲取價值。 此時，任何進一步的註冊都可能導致品牌沒有充分體驗到 [!DNL Device Co-op]。

## 2022年7月，Google宣佈將第三方Cookie的棄用推遲到2024年。 這會影響 [!DNL Device Co-op] EOL計畫？

不，Adobe [!DNL Device Co-op] EOL計畫將繼續保持不變，不會延長。

## 新客戶能否註冊？

從2021年6月11日起，Adobe將不再接受新的註冊 [!DNL Device Co-op]。

## 現有合同是否正在續訂？

從2021年6月11日起，Adobe將不再續期 [!DNL Device Co-op] 合同。 如果要繼續使用 [!DNL Device Co-op] 服務，您可以繼續按照當前許可條款執行此操作，直到程式結束。

## 具體結束日期是 [!DNL Device Co-op] 程式？

的 [!DNL Device Co-op] 計畫將於2022年結束。 具體時間和日期取決於 [!DNL Google] 開始阻止第三方Cookie。

## 哪些應用程式將受設備合作計畫終止的影響？

以下應用程式將受 [!DNL Device Co-op] 終止使用程式：

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## 我有哪些選項 [!DNL Device Co-op]?

### [!DNL Analytics]

您可以使用 [!DNL Analytics] [跨設備分析(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 功能，因為它同時支援Adobe Experience Platform身份服務 [專用圖](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) 和 [基於欄位的縫合](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en)。

### [!DNL Audience Manager]

[!DNL Audience Manager] 維護與第三方設備圖形合作夥伴的整合，包括 [!DNL LiveRamp] 和 [!DNL Tapad]，儘管您必須直接與圖形合作夥伴建立商業關係，以便利用 [!DNL Audience Manager]。

### [!DNL Real-time Customer Data Platform]

沒有修改當前 [!DNL Audience Manager Data Management Platform] (DMP)。 但是，第三方Cookie的棄用可能會給大多數DMP用戶帶來規模挑戰。 為幫助客戶發展其資料管理做法，Adobe鼓勵減少對識別符的依賴性，這些依賴性在來年將面臨限制。 營銷團隊必須構建以持久標識符為重點的第一方資料策略，該標識符包括個人識別資訊(PII)，可通過 [!DNL Real-time Customer Data Platform] （即時CDP）。

[!DNL Real-time CDP] 通過擴展可用於建立受眾的標識符集以包括PII，減少對第三方cookie和設備ID的依賴性。 基礎 [!DNL Real-time CDP] 是即時客戶配置檔案，它將人員屬性資料與行為資料即時匯集在一起，並使營銷人員能夠使用專利資料治理控制建立豐富的受眾群。 像 [!DNL Audience Manager]。 [!DNL Real-time CDP] 強大的洞察力和個性化使用案例，但也能生成更細的個人級洞察力，並能夠將受眾激活到範圍更廣的目標，包括廣告技術和營銷技術，包括付費媒體、社交媒體、電子郵件和客戶系統。

[!DNL Real-time CDP] 還將包括訪問 [Adobe Experience Platform段匹配(Beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en)它允許品牌通過合作夥伴關係擴展自己的第一方資料集，並實現改進的洞察力和個性化。

### [!DNL Target]

目前沒有可供選擇的 [!DNL Target] 因為 [!DNL Target] 提供了確定性的跨設備標識縫合功能，稱為 `mbox3rdPartyId`，其功能與Adobe的客戶ID類似。 此功能允許 [!DNL Target] 合併配置檔案和活動參與的客戶 [!DNL Target] test和個性化正在入站通道中完成。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客戶將不再能夠使用 [!DNL Device Co-op] 用於跨設備目標和測量。 與 [!DNL Advertising Cloud]你仍然能利用Adobe [!DNL Device Graph] 合作 [!DNL LiveRamp] 繼續履行這些職能， [!DNL LiveRamp’s] 能力和規模。 您必須允許您使用的市場活動 [!DNL Device Co-op] 結束，然後切換到 [!DNL LiveRamp] 設備圖形提供商，或不再利用基於人的目標。

## 哪些現有功能和實施可以幫助我為無餅乾的未來做好準備？

您現有的訪問者ID服務實施支援分析 [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)。 如果您現有聲明的ID是散列電子郵件，則可以使用它為以下功能供電：

- [!DNL Audience Manager] [以人物為基礎的目的地](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform段匹配(Beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en)。

## 我能不能 [!DNL Device Co-op]?

對於 [!DNL Audience Manager] 和 [!DNL Advertising Cloud] 用戶，資料 [!DNL Device Co-op] 將無法傳輸到第三方圖表。 [!DNL Device Co-op] 資料將僅遷移 [!DNL Analytics Ultimate] 使用CDA的用戶 [!DNL Device Co-op] 切換到基於欄位的縫合。 所有其他解決方案都不會遷移其資料。

## 是否必須採用其他功能？

雖然採用其他Adobe功能並非強制性的，但您應盡快開始實施其他功能，以便在開始之前提供時間和適當的協調 [!DNL Device Co-op] 棄用。

## 如果我願意，我何時必須採用替代方案？

採用其他功能並非強制性的。 只有在您希望繼續處理由 [!DNL Device Co-op]。 如果您選擇採用其它功能，則必須在2022年之前（確切宣佈的時間）採用 [!DNL Device Co-op] 程式結束。

## 收養要多久？

這取決於功能。 例如，如果Analytics最終客戶使用跨設備分析 [!DNL Device Co-op] 需要遷移到即時專用設備圖形或基於現場的縫合，採用需要一些時間。
