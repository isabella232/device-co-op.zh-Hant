---
description: 裝置圖表如何分析確定性資料和概率資料，以建立將裝置連結在一起的地圖。
seo-description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-title: Deterministic and probabilistic links
title: 確定性連結和概率性連結
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
exl-id: e9bd2b7a-7d39-425d-adbb-298944009fcc
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '845'
ht-degree: 0%

---

# 確定性連結和概率性連結{#deterministic-and-probabilistic-links}

裝置圖表如何分析確定性資料和概率資料，以建立將裝置連結在一起的地圖。

在 [!DNL Device Graph]，內部程式會建立對應裝置的身分階層，並將其連結至個別匿名人員。 圖形輸出包含可用於定位的跨裝置連結，以及特定Experience Cloud解決方案中公開的資料。 搭配使用的Adobe解決方案 [!DNL Device Graph] 資料包括Analytics、Audience Manager、Media Optimizer和Target。

此 [!DNL Device Graph] 分析確定性和可能性資料，以建立將裝置連結在一起的地圖。 根據雜湊登入資訊的確定性資料將裝置連結在一起。 機率資料會根據IP位址和其他中繼資料等資訊，將裝置連結在一起。 此 [!DNL Device Graph] 將連結的裝置叢集與匿名的個人建立關聯這些連線可讓數位行銷人員觸及個人，而非裝置。 在 [!DNL Device Graph]，裝置的擁有者是真實人物的匿名代表。 確定性連結和概率性連結都有助於建立使用者身分的結構。

>[!NOTE]
>
>Adobe Experience Cloud Device Co-op中的辭彙，例如 *裝置*， *人員*、和 *身分* 具有特定意義。 例如， *裝置* 可以指代實體硬體，例如手機或平板電腦，以及在該硬體上執行的應用程式。 請參閱 [字彙表](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) 定義。

## 什麼是連結？ {#section-2df4c6f01eba49369993146df0661f13}

當我們談論連結時，請務必牢記這些連結的內容究竟是什麼 [!DNL Experience Cloud] 裝置圖表。 在這種情況下，連結不是裝置之間的實體連線。 相反地，連結是裝置圖表將不同裝置連結至同一個不明人員的方式。 例如，假設我們有一部行動電話和一部桌上型瀏覽器。 一旦裝置圖表判斷這兩個裝置是由同一個不明人士使用，即可將電話和瀏覽器視為「已連結」。 如下所述，裝置圖表會使用確定性連結和機率連結來建立身分識別。 而在裝置圖表中，裝置的擁有者是真實人物的匿名代表。

## 確定性連結 {#section-33d41e828a674b398e36fe63da20ac09}

根據驗證事件（例如，從裝置登入網站的行為）將裝置與個人建立關聯的確定性連結。 此動作會建立稱為消費者ID的匿名識別碼。 讓我們來看看決定性連結如何運作。 在此範例中，人員A透過其行動裝置上的應用程式登入新聞網站。 當天晚些時候，A個人再次登入，但這次是透過筆記型電腦上的瀏覽器登入。

![](assets/link1.png)

根據登入資訊，裝置圖表：

* 知道透過行動電話/應用程式和筆記型電腦/瀏覽器裝置組合，人員A已驗證至新聞網站。
* 將這些裝置連結至人員A。
* 根據與匿名人員相關聯的連結裝置來建立身分。

![](assets/link2.png)

>[!NOTE]
>
>兩者都不 [!DNL Adobe Experience Cloud Device Co-op] 或 [!DNL Device Graph] 接收此資料中的實際驗證資訊或個人識別資訊(PII)。 成員 [!DNL Experience Cloud Device Co-op]，將經過雜湊加密的不重複消費者ID傳遞至裝置圖表。 消費者ID代表圖表中的已驗證使用者，並保護消費者隱私權。

## 機率連結 {#section-5f5aa755da984f9d851f7cb380262998}

機率連結會根據特徵和中繼資料（例如），以演演算法方式將裝置連結至人員：

* 瀏覽行為
* ip位址
* 作業系統
* IDFA和GAID識別碼

讓我們來看看機率連結如何運作。 在此範例中，人員A在其平板電腦上瀏覽新聞網站，之後再從桌上型電腦瀏覽。 瀏覽時，人員A未登入新聞網站。 在每次個別造訪期間，平板電腦和桌上型電腦會共用相同的IP位址。

![](assets/link3.png)

根據此資訊， [!DNL Device Graph] 評估兩個裝置之間的IP位址共用模式，如果結果指出這些裝置屬於人員A，則將這些裝置連結在一起。最終結果是從演演算法機率計算衍生出的身分階層。

![](assets/link4.png)

在此範例中，兩個裝置在使用來存取相同的新聞網站後，裝置圖表就會連結這些裝置。 但是，裝置不需出現在相同網站上即可連結。 為了說明這一點，假設此範例中的每個裝置造訪完全不同的網站。 此 [!DNL Device Graph] 演演算法仍可根據共用IP位址和其他資料分析，建立機率連結。 此程式有助於讓可能連結對成員如此強大 [!DNL Experience Cloud] Device Co-op。

## 兩種資料型別都有提供價值 {#section-43d22d8c10634edcb261e7bda6fdf323}

確定性資料和概率性資料相輔相成。 相較之下，僅包含確定性資料的裝置圖表可提供您有限的個人身分檢視。 若沒有驗證，裝置圖表就無法告訴您瀏覽網站的其他裝置和人員。 機率資料可以建立這些連線，並協助您觸及未經驗證的裝置、人員和家庭。

不過，確定性資料也很重要。 例如，它可以移除在機率訊號豐富且重疊的地方（例如咖啡館、圖書館、機場等）產生的虛假連結，藉此改善機率決策。

透過這兩種型別的資料，裝置圖表可讓您比單獨使用其中一種型別更全面地瞭解個人的身分。

![](assets/link5.png)
