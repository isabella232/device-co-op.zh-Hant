---
description: Adobe Experience Cloud Device Co-op是一項計畫，可讓參與者共同合作，在數位觸點上更好地識別消費者，同時確保最高等級的隱私權和透明度。 Experience Cloud Device Co-op可讓參與的品牌識別其消費者，讓他們能夠大規模跨裝置和應用程式提供更個人化的體驗。 Device Co-op是Adobe Experience Cloud的核心服務。 它適用於使用Analytics、Audience Manager、Media Optimizer或Target的Adobe客戶。
seo-description: Adobe Experience Cloud Device Co-op是一項計畫，可讓參與者共同合作，在數位觸點上更好地識別消費者，同時確保最高等級的隱私權和透明度。 Experience Cloud Device Co-op可讓參與的品牌識別其消費者，讓他們能夠大規模跨裝置和應用程式提供更個人化的體驗。 Device Co-op是Adobe Experience Cloud的核心服務。 它適用於使用Analytics、Audience Manager、Media Optimizer或Target的Adobe客戶。
seo-title: 概述
title: 概述
uuid: 9e2502db-0dc6-4b0f-965f-71894fb1f9d4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '879'
ht-degree: 1%

---


# 概述{#overview}

Adobe Experience Cloud Device Co-op是一項計畫，可讓參與者共同合作，在數位觸點上更好地識別消費者，同時確保最高等級的隱私權和透明度。 Experience Cloud Device Co-op可讓參與的品牌識別其消費者，讓他們能夠大規模跨裝置和應用程式提供更個人化的體驗。 Device Co-op是Adobe Experience Cloud的核心服務。 它適用於使用Analytics、Audience Manager、Media Optimizer或Target的Adobe客戶。

## 優勢 {#section-ba8d23e1e5174bea8f84aab4642d4809}

Device Co-op可讓參與者在跨裝置移轉時，為其消費者提供更好、更一致的內容體驗。 它透過建立未知消費者使用之裝置群組之間的連結來達成此目的。 此技術可協助行銷人員瞭解並回應各種裝置上的消費者行為。 結果可提供更精確的網站參與度量、更個人化的內容，以及更針對性的廣告體驗，涵蓋搜尋、展示廣告和社交媒體。 參與 [!DNL Adobe Experience Cloud] Device Co-op有助於我們的會員改善：

* **客戶瞭解：** 傳統報表可顯示特定裝置的見解。 但是，設備和通道不買東西。 人們是這樣。 Device Co-op提供更佳的報告功能，協助分析人員和行銷人員回答其業務所提出的以人為本的真實問題。
* **內容個人化：** 未登入品牌網站或應用程式的消費者通常會獲得與目前使用的裝置連結的體驗。 Device Co-op可協助行銷人員根據品牌擁有的個人相關資訊（而不只是使用的裝置），提供一致且有價值的體驗。
* **廣告支出效率：** Device Co-op將展示廣告重點放在人上，而非裝置上，有助於節省行銷預算。 由於頻率上限通常適用於單一裝置，因此每位消費者最多可以在每部裝置上製作5個廣告。 借助Device Co-op，行銷人員可以鎖定目標對象而非裝置，進而提升投資報酬率。
* **跨裝置重新定位：** 透過在日常使用的行動裝置、平板電腦、瀏覽器和其他裝置上重新鎖定鎖定目標，觸及您的消費者。 如果您能隨時掌握心態，廣告會大幅提高效率，而跨裝置重新定位可讓您的品牌做到這一點。

<!--
we may not want to share info in this with customers who have not signed. Also, removed directory from S3.
<p>Download our white-paper, <a href="https://marketing-stage.adobe.com/resources/help/en_US/mcdc/downloads/what_to_expect.pdf" format="https" scope="external"> What to Expect from the Device Co-op</a> for more information. </p>
-->

## Adobe在Device Co-op中的角色 {#section-f23c1c442ceb4c44821f10ec9aa7b828}

在中 [!DNL Device Co-op], [!DNL Adobe]:

* **是資料管家：**Device Co-op會員不會直接彼此共用資料。 相反地， [!DNL Adobe]它可充當代理，讓co-op可透過的裝置連結資料取得 [!DNL Device Graph]。 Device Co-op會員可透過其啟用的解決方案中的功能，使用這些 [!DNL Experience Cloud] 資料。

* **相信資料公平：** 公平的資料分享是Device Co-op中的重要概念。 所有 [!DNL Device Co-op] 成員都會獲得與其貢獻相對的價值。 如果您從未透過網站造訪或廣告印象與匿名人員互動，您將無法在中取得任何有關其裝置的資訊 [!DNL Device Graph]。 Device Co-op可協助品牌識別使用陌生裝置的熟悉消費者。

* **支援隱私權標準：**[!DNL Device Graph] 資料不包含個人識別資訊(PII)。 將PII排除在裝置圖表中 [!DNL Adobe] 有助於維護隱私權標準，並維持合作會員和消費者的信任。

## 運作方式 {#section-7f7a0138e54349278fc463764f03cd4b}

Co-op會員會讓Adobe存取經密碼雜湊處理的登入ID和HTTP標題資料，這些資料會完全隱藏消費者的身分。 Adobe會處理此資料，以建立未知個人或家庭使用的裝置群組（「裝置叢集」）。 然後Adobe將透過其數位行銷解決方案呈現這些裝置群組，讓Co-op會員可以直接在所有裝置上測量、細分、鎖定和廣告給個人。 所有這一切都可能發生，而不會透露使用者的身 [!DNL Device Co-op] 分，因 *為不會共用個人資料* ，例如姓名、電子郵件地址、電話號碼或網站造訪資料等。 在其成員中。

這些規則有助於解決與跨裝置技術通常相關的重要隱私權問題。 事實上，有了這項 [!DNL Device Co-op]計畫，消費者將擁有超過業界標準的隱私權控制。 它 [!DNL Device Co-op] 為消費者提供參與品牌以及所有與目前使用之裝置相關的裝置見解，提供前所未有的透明度。 請參 [閱裝置圖表：內部流程與輸出](../processes/links.md#concept-e9526af3476b478aab7c57b9ed0bab7c) ，以取得詳細資訊。

## 快速入門 {#section-53a47ffdc5bf47c88cedcb92dd65444b}

如果您想要參與或 [進一步瞭解](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43) ，請花點時間檢閱會籍要求 [!DNL Device Co-op]。 此外，如需 [其他Experience Cloud解決方案中其他產品使用此資料的摘要，請](../other-solutions/other-solutions.md#concept-46278a50cfca4e1ab83a3b35077a585f)[!DNL Adobe] 參閱使用Device Co-op資料。
