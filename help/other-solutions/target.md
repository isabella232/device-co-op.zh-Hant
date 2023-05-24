---
description: 瞭解如何在Adobe Target活動中使用Device Co-op資料。
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - A/B測試、多變數測試和體驗鎖定目標
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target - A/B測試、多變數測試和體驗鎖定目標{#target-a-b-tests-multivariate-tests-and-experience-targeting}

瞭解如何在Adobe Target活動中使用Device Co-op資料。

您可以在A/B測試、多變數(MVT)測試和體驗鎖定目標活動中使用Device Co-op資料。 Device Co-op選項可在活動建立期間，於 [!DNL Goals & Settings] 中的頁面 [!DNL Target] 三步驟引導式工作流程。

您無法在Automated Personalization活動、Recommendation活動或使用的活動中使用Device Co-op資料 [!DNL Adobe Analytics] 作為報表來源( [!DNL Target] 和 [!DNL Analytics] 整合（稱為A4T）。

>[!NOTE]
>
>確保您擁有所需版本的 `mbox.js`. 您可以使用任何版本的 `at.js`. 如需詳細資訊，請參閱 [成員資格要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## 無論裝置為何，皆可傳遞相關內容 {#section-bba8d41e96914c82a6d267a54f776354}

行銷人員想要提供最相關的體驗給每位訪客，無論訪客目前使用哪個裝置與其公司或品牌互動。

使用者從許多不同裝置與相同公司或品牌互動：工作用筆記型電腦、家用電腦、iPad、iPhone、各種瀏覽器等。 如果您無法辨識出使用每個特定裝置或瀏覽器的都是同一個人，而此人之前曾在其他裝置或瀏覽器上與您的品牌互動，則您無法為該人提供一致且目標明確的體驗。

透過Device Co-op，使用者的各種裝置都可識別為正由同一位使用者使用。 當使用者看到具有的頁面時 [!DNL Target] 活動 — 活動或目標內容 —  [!DNL Target] 可確保使用者看到與其他裝置相同的體驗。

## 依人員而非訪客分析Target活動 {#section-c25cf4f8483942d7836d60756235e62c}

行銷人員想要分析 [!DNL Target] 活動依據「人物」而非「訪客」。

每個人都可能透過裝置和瀏覽器與相同公司或品牌互動，但若沒有Device Co-op，每個個別裝置或瀏覽器都視為單獨的「訪客」。 [!DNL Target] 報表。

依個別裝置和瀏覽器檢視報表，會將「訪客」計數誇大為高於與公司或品牌互動的不同人員數量。 這些人通常在這些不同的裝置和瀏覽器中只轉換一次，因此轉換率會低於實際值，因為一次轉換會計算更多「訪客」。

有了Device Co-op，內容傳遞和報告會在「人員」層級完成，因此報告可準確顯示有多少不同人員觀看了活動，以及有多少人員轉換。

如果沒有Device Co-op資料，您可以判斷特定活動是獲勝者；不過，由於Device Co-op的報表更準確，其他活動實際上可能會有較高的轉換率，因此會成為獲勝者。

如需此概念的詳細資訊，請參閱 [Analytics：人員量度](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## 根據活動使用Device Co-op資料 {#section-fb46fae482654023abb1a1e26564db9a}

行銷人員可選擇針對每個活動使用Device Co-op資料。 特定 [!DNL Target] 活動可能不適用於Device Co-op資料，例如：

* 適用於iPad使用者的特定內容。

   第一次在iPad上檢視體驗的使用者，將繼續在家用電腦上看到該體驗。

* 利率優惠方案僅適用於嚴格的訪客區段。
* 產品僅可在特定狀態中廣告（例如，具有授許可權制的保單）。

當行銷人員在中建立受眾時 [!DNL Target]，如果對象不適合Device Co-op資料啟用的活動，系統會提醒他們。 適當的受眾包括所有訪客、新訪客和回訪訪客。
