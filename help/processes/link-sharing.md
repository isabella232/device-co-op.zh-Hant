---
description: 關於裝置圖表中的連結共用。
seo-description: About link sharing in the Device Graph.
seo-title: Link sharing in the Device Graph
title: 裝置圖表中的連結共用
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
exl-id: 91ecc493-89d8-40d6-a98b-c2349e25c854
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---

# 裝置圖表中的連結共用{#link-sharing-in-the-device-graph}

關於裝置圖表中的連結共用。

此 [!DNL Device Graph] 與Adobe Experience Cloud Device Co-op的不同成員分享確定性連結和機率連結。 連結共用會導致 [!DNL Device Co-op] 如此強大。 它擴展了每個成員對於與匿名人士相關聯之裝置的瞭解，但前提是您之前至少見過該匿名人士其中一部裝置。

## 裝置圖表摘要稽核 {#section-7858e9f61b5644c981ffb53626fcc19d}

在開始之前，讓我們花點時間檢閱以下內容 [!DNL Device Graph] 有效。 成員 [!DNL Device Co-op] 將資料傳送至 [!DNL Device Graph]. 此 [!DNL Device Graph] 使用此資料從以下來源建構個人身分 [確定性連結和概率性連結](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) 裝置之間。 As a [!DNL Device Co-op] 參與者，這些連結可讓您深入瞭解已驗證身分的使用者、其他使用者與其裝置之間的關係。 讓我們在下節中瞭解其運作方式。

## 連結共用範例 {#section-cb410d827cf14f76bc9b0bd4d31ed767}

下列範例說明Device Co-op中連結共用的強大功能。 在此範例中，我們有2家虛構的公司：新聞公司和財務公司。 這兩家公司都是 [!DNL Device Co-op]. 人員A是從多部裝置登入或瀏覽每間公司網站的消費者。

![](assets/share1.png)

由於人員A已透過其行動電話和平板電腦在新聞網站進行驗證，因此新聞公司會以消費者ID識別他們。 這會將該ID傳送至 [!DNL Device Graph] 作為密碼編譯雜湊。 財務公司以前見過這些裝置，但人員A尚未登入網站。 因此，財務公司不知道這些裝置是否或如何彼此相關，或它們如何與人員A相關聯。

![](assets/share2.png)

指定消費者ID的密碼編譯雜湊， [!DNL Device Graph] 會辨識這些裝置彼此相關，且與特定人員相關。 不參與本計畫的公司 [!DNL Device Co-op] 這些網站造訪似乎來自不同的隨機裝置。 無論如何，一旦 [!DNL Device Graph] 具有雜湊ID：

* 知道行動電話和筆記型電腦有連結。
* 已辨識到財務公司想知道行動電話和筆記型電腦是否連結。

基於這些條件， [!DNL Device Graph] 現在與財務公司共用連線新聞公司這些裝置的連結。 在此過程中， [!DNL Device Graph] 複製並共用從一個co-op成員到另一個成員的連結。

![](assets/share3.png)

此時， [!DNL Device Graph] 已成功執行其角色。 新聞公司和財務公司都有清楚的身分識別。 他們可以透過其所有裝置準確地聯絡人A。

## 隱私權與連結共用 {#section-7b566018b3304420a4b3e4c079826110}

維護消費者隱私權與資料完整性 [!DNL Device Co-op] 成員在整個連結共用程式中非常重要。 在此客戶身分識別與連結共用程式期間， [!DNL Device Graph] 沒有：

* 告知財務公司，該連結來自新聞公司。
* 共用其中一個使用的客戶ID [!DNL Device Co-op] 成員與另一個成員。
* 提供行動裝置和筆記型電腦共用共同連結以外的任何資訊。

## 後續步驟 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

閱讀有關身分、連結和連結共用的檔案，應能讓您充分瞭解 [!DNL Device Graph] 在內部組合資料。 下一步，建議您檢視說明「 」概念的檔案 *`known device`* 會傳送跨裝置連結至Device Co-op成員。 另請參閱 [已知裝置](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知的裝置](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
