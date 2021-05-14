---
description: Adobe Experience Cloud裝置合作計畫可讓參與者合作，透過數位接觸點更好地識別消費者，同時確保最高等級的隱私權和透明度。 Experience CloudDevice Co-op可讓參與品牌識別其消費者，以便他們能夠大規模跨裝置和應用程式提供更個人化的體驗。 Device Co-op是Adobe Experience Cloud的核心服務。 它適用於Adobe使用Analytics、Audience Manager、Media Optimizer或Target的客戶。
seo-description: Adobe Experience Cloud裝置合作計畫可讓參與者合作，透過數位接觸點更好地識別消費者，同時確保最高等級的隱私權和透明度。 Experience CloudDevice Co-op可讓參與品牌識別其消費者，以便他們能夠大規模跨裝置和應用程式提供更個人化的體驗。 Device Co-op是Adobe Experience Cloud的核心服務。 它適用於Adobe使用Analytics、Audience Manager、Media Optimizer或Target的客戶。
seo-title: 概述
title: 概述
uuid: 9e2502db-0dc6-4b0f-965f-71894fb1f9d4
exl-id: 8195162c-fab4-49d8-8f6f-1e9ed96ffaa7
source-git-commit: e7a53a4892a8769fc178f5f3f2b82201589177b2
workflow-type: tm+mt
source-wordcount: '879'
ht-degree: 1%

---

# 概述{#overview}

Adobe Experience Cloud裝置合作計畫可讓參與者合作，透過數位接觸點更好地識別消費者，同時確保最高等級的隱私權和透明度。 Experience CloudDevice Co-op可讓參與品牌識別其消費者，以便他們能夠大規模跨裝置和應用程式提供更個人化的體驗。 Device Co-op是Adobe Experience Cloud的核心服務。 它適用於Adobe使用Analytics、Audience Manager、Media Optimizer或Target的客戶。

## 優勢 {#section-ba8d23e1e5174bea8f84aab4642d4809}

Device Co-op可讓參與者在跨裝置移轉時，為其消費者提供更好、更一致的內容體驗。 它透過建立未知消費者使用之裝置群組之間的連結來達成此目的。 此技術可協助行銷人員瞭解並回應各種裝置上的消費者行為。 結果可提供更精確的網站參與度量、更個人化的內容，以及更針對性的廣告體驗，涵蓋搜尋、展示廣告和社交媒體。 參與[!DNL Adobe Experience Cloud] Device Co-op可協助我們的會員改善：

* **客戶瞭解：傳** 統報表可揭示特定裝置的見解。但是，設備和通道不買東西。 人們是這樣。 Device Co-op提供更佳的報告功能，協助分析人員和行銷人員回答其業務所提出的以人為本的真實問題。
* **內容個** 人化：未登入品牌網站或應用程式的消費者通常會獲得與目前使用的裝置連結的體驗。Device Co-op可協助行銷人員根據品牌擁有的個人相關資訊（而不只是使用的裝置），提供一致且有價值的體驗。
* **廣告支出效率：** Device Co-op將展示廣告重點放在人上，而非裝置上，有助於節省行銷預算。由於頻率上限通常適用於單一裝置，因此每位消費者最多可以在每部裝置上製作5個廣告。 借助Device Co-op，行銷人員可以鎖定目標對象而非裝置，進而提升投資報酬率。
* **跨裝置重新定位：** 透過在日常使用的行動裝置、平板電腦、瀏覽器和其他裝置上解除鎖定鎖定的功能，觸及您的消費者。如果您能隨時掌握心態，廣告會大幅提高效率，而跨裝置重新定位可讓您的品牌做到這一點。

<!--
we may not want to share info in this with customers who have not signed. Also, removed directory from S3.
<p>Download our white-paper, <a href="https://marketing-stage.adobe.com/resources/help/en_US/mcdc/downloads/what_to_expect.pdf" format="https" scope="external"> What to Expect from the Device Co-op</a> for more information. </p>
-->

## Adobe在Device Co-op {#section-f23c1c442ceb4c44821f10ec9aa7b828}中的角色

在[!DNL Device Co-op]中，[!DNL Adobe]:

* **是資料管理員：** Device Co-op成員不會直接彼此共用資料。相反，[!DNL Adobe]可充當代理，使設備連結資料可通過[!DNL Device Graph]提供給co-op。 Device Co-op會員可透過其啟用的[!DNL Experience Cloud]解決方案中的功能，使用此資料。

* **相信資料公平：公平** 的資料分享是Device Co-op中的重要概念。所有[!DNL Device Co-op]成員都會收到與其貢獻值相關的值。 如果您從未透過網站造訪或廣告曝光與匿名人員互動，則不會在[!DNL Device Graph]中取得任何有關其裝置的資訊。 Device Co-op可協助品牌識別使用陌生裝置的熟悉消費者。

* **支援隱私權標** [!DNL Device Graph] 準：資料不包含個人識別資訊(PII)。將PII從裝置圖表中排除，有助於[!DNL Adobe]維護隱私權標準，並維持合作會員和消費者的信任。

## 運作方式 {#section-7f7a0138e54349278fc463764f03cd4b}

Co-op會員會提供Adobe存取權，以存取經密碼雜湊處理的登入ID和HTTP標題資料，以完全隱藏消費者的身分。 Adobe會處理此資料，以建立未知人員或家庭使用的裝置群組（「裝置叢集」）。 然後，Adobe會透過其數位行銷解決方案，將這些裝置群組呈現出來，讓Co-op會員可以直接在所有裝置上測量、細分、鎖定和廣告給個人。 所有這一切都可能不揭露使用者身分，因為[!DNL Device Co-op] *不*&#x200B;共用個人資料，例如姓名、電子郵件地址、電話號碼或網站造訪資料等。 在其成員中。

這些規則有助於解決與跨裝置技術通常相關的重要隱私權問題。 事實上，使用[!DNL Device Co-op]，消費者將擁有超過業界標準的隱私權控制。 [!DNL Device Co-op]可讓消費者深入瞭解參與的品牌以及所有與目前使用之裝置相關的裝置，提供前所未有的透明度。 請參閱[裝置圖表：Internal Processes and Output](../processes/links.md#concept-e9526af3476b478aab7c57b9ed0bab7c)部分，以瞭解詳細資訊。

## 快速入門 {#section-53a47ffdc5bf47c88cedcb92dd65444b}

請花點時間檢閱[會籍要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)（如果您想要參與，或進一步瞭解[!DNL Device Co-op]）。 此外，如需其他[!DNL Adobe]產品如何使用此資料的摘要，請參閱[在其他Experience Cloud解決方案中使用Device Co-op資料](../other-solutions/other-solutions.md#concept-46278a50cfca4e1ab83a3b35077a585f)。
