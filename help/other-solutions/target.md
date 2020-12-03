---
description: 瞭解如何在Adobe Target活動中使用Device Co-op資料。
seo-description: 瞭解如何在Adobe Target活動中使用Device Co-op資料。
seo-title: Target - A/B測試、多變數測試和體驗定位
title: Target - A/B測試、多變數測試和體驗定位
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---


# Target - A/B測試、多變數測試和體驗定位{#target-a-b-tests-multivariate-tests-and-experience-targeting}

瞭解如何在Adobe Target活動中使用Device Co-op資料。

您可以在A/B測試、多變數(MVT)測試和體驗定位活動中使用Device Co-op資料。 The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

您無法在Automated Personalization活動、建議活動或活動中使用Device Co-op [!DNL Adobe Analytics] 資料作為報告來源( [!DNL Target][!DNL Analytics] 和整合，稱為A4T)。

>[!NOTE]
>
>請確定您擁有所需的版本 `mbox.js`。 您可使用任何版本 `at.js`。 如需詳細資訊，請參閱會 [員資格要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)。

## 不論裝置為何，都能提供相關內容 {#section-bba8d41e96914c82a6d267a54f776354}

行銷人員希望向每位訪客傳遞最相關的體驗，不論訪客目前使用何種裝置與其公司或品牌互動。

使用者從許多不同裝置與相同的公司或品牌互動：工作筆記型電腦、家用電腦、iPad、iPhone、各種瀏覽器等。 如果您無法識別之前在其他裝置或瀏覽器上與品牌互動過的相同人員使用每個特定裝置或瀏覽器，則無法向該人員提供一致且有針對性的體驗。

透過Device Co-op，使用者的各種裝置可識別為由同一使用者使用。 當使用者看到含有活動(活 [!DNL Target] 動或目標內容)的頁面時， [!DNL Target] 可確保使用者看到的體驗與在其他裝置上看到的相同。

## 依人員而非訪客分析Target活動 {#section-c25cf4f8483942d7836d60756235e62c}

行銷人員想要依 [!DNL Target] 據「人」而非「訪客」來分析活動。

每個人可能會跨裝置和瀏覽器與相同的公司或品牌互動，但若沒有Device Co-op，每個個別裝置或瀏覽器在報表中會被視為個別的「訪客」 [!DNL Target] 。

依個別裝置和瀏覽器檢視報表時，「訪客」計數會增加到比與公司或品牌互動的不同訪客數更高的數目。 這些人通常只在這些不同的裝置和瀏覽器上轉換一次，因此轉換率會低於實際，因為單次轉換會計入更多「訪客」。

透過Device Co-op，內容傳送和報告是在「人員」層級進行，因此報表會準確顯示有多少不同的人員看過活動，以及有多少人已轉換。

若沒有Device Co-op資料，您可能會判斷特定活動是贏家；不過，由於Device Co-op的報告更精確，因此其他活動實際上的轉換率可能更高，因此成為贏家。

如需此概念的詳細資訊，請參閱 [Analytics:人員量度](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)。

## 依活動使用Device Co-op資料 {#section-fb46fae482654023abb1a1e26564db9a}

行銷人員可以選擇針對每個活動使用Device Co-op資料。 某 [!DNL Target] 些活動可能不適合Device Co-op資料，例如：

* 適合iPad使用者的特定內容。

   首次在iPad上檢視體驗的使用者，將會繼續在家用電腦上檢視該體驗。

* 利率優惠僅適用於嚴格訪客區段。
* 僅允許在特定狀態（例如，具有授權限制的保險單）進行廣告的產品。

當行銷人員在中建立 [!DNL Target]對象時，如果對象不適用於Device Co-op資料啟用活動，他們會收到警告。 適當的對象包括所有訪客、新訪客和舊訪客。
