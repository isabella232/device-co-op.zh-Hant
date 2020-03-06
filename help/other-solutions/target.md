---
description: 瞭解如何在Adobe Target活動中使用Device Co-op資料。
seo-description: 瞭解如何在Adobe Target活動中使用Device Co-op資料。
seo-title: Target - A/B測試、多變數測試和體驗定位
title: Target - A/B測試、多變數測試和體驗定位
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

瞭解如何在Adobe Target活動中使用Device Co-op資料。

您可以在A/B測試、多變數(MVT)測試和體驗定位活動中使用Device Co-op資料。 The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

您不可以在自動的個人化活動、建議的活動或使用 [!DNL Adobe Analytics] 作為報告來源 ([!DNL Target] 和 [!DNL Analytics] 整合，即 A4T) 的活動中使用 Device Co-op 資料。

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. 您可以使用任何版本的 `at.js`。如需詳細資訊，請參閱會 [員資格要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)。

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

行銷人員想要提供最相關的體驗給每個訪客，而不論訪客目前用來與其公司或品牌互動的裝置為何。

使用者從許多不同的裝置與相同的公司或品牌互動: 工作用筆記型電腦、家用電腦、iPad、iPhone、各種瀏覽器等等。如果您無法識別出每個特定裝置或瀏覽器正由先前在其他裝置或瀏覽器上與您的品牌互動的相同人員使用，則無法對該人員提供一致和鎖定的體驗。

利用 Device Co-op，使用者的各種裝置可被識別為由相同的使用者所使用。當該使用者看見頁面具有 [!DNL Target] 活動—活動或鎖定的內容—[!DNL Target] 可確保使用者會在另一個裝置看見相同的體驗。

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

行銷人員想要依「人員」而非「訪客」分析 [!DNL Target] 活動。

每個人員可能會跨裝置和瀏覽器與相同的公司或品牌互動，但若沒有 Device Co-op，每個個別裝置或瀏覽器在 [!DNL Target] 報告中會被視為個別的「訪客」。

依個人裝置和瀏覽器檢視報告，會使得「訪客」計數膨脹為高於與公司或品牌互動的不同人員的數量。這些人員一般只會在各種裝置和瀏覽器間轉換一次，所以轉換率將低於實際，因為單一轉換將會計入更多「訪客」。

有了 Device Co-op，內容提供和報告是在「人員」層級完成，因此報告會準確地顯示看見活動的不同人員數量，以及轉換的人員數量。

若沒有 Device Co-op 資料，您可能會判定特定活動為贏家；不過，因為使用 Device Co-op 的報告更準確，另一個活動可能實際上會有較高的轉換率，因此才是贏家。

如需此概念的相關資訊，請參閱 分 [析：人員量度](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)。

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

行銷人員可以選擇使用每一活動 Device Co-op 資料。某些 [!DNL Target] 活動對 Device Co-op 資料可能不適當，例如:

* 特定內容適合 iPad 上的使用者。

   先在 iPad 上有檢視體驗的使用者，將繼續在家用電腦上看見該體驗。

* 僅針對嚴格的訪客區段提供利率項目。
* 允許廣告的產品僅限處於特定狀態 (例如，具有授權限制的保險政策)。

當行銷人員在 [!DNL Target] 中建立對象時，如果該對象不適合 Device Co-op 資料啟用的活動，他們會收到警示。適當的對象包括所有訪客、新訪客和回訪訪客。
