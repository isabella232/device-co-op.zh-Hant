---
description: 「裝置圖」如何分析確定性和概率性資料，以建立將裝置連結在一起的地圖。
seo-description: 「裝置圖」如何分析確定性和概率性資料，以建立將裝置連結在一起的地圖。
seo-title: 確定性和概率性連結
title: 確定性和概率性連結
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Deterministic and probabilistic links{#deterministic-and-probabilistic-links}

「裝置圖」如何分析確定性和概率性資料，以建立將裝置連結在一起的地圖。

In the [!DNL Device Graph], internal processes build an identity hierarchy that maps devices and connects them to individual, anonymized people. 圖表的輸出包括可用於定位的跨裝置連結，以及精選Experience Cloud解決方案中公開的資料。 The Adobe solutions that work with [!DNL Device Graph] data include Analytics, Audience Manager, Media Optimizer, and Target.

The [!DNL Device Graph] analyzes deterministic and probabilistic data to build a map that links devices together. 決定性資料會根據雜湊的登入資訊將裝置連結在一起。可能性資料會根據 IP 位址與其他中繼資料之類的資訊將裝置連結在一起。The [!DNL Device Graph] associates the linked device clusters to an anonymous individual person These connections let digital marketers reach people instead of devices. In the [!DNL Device Graph], the owner of a device is the anonymous representation of a real-life person. 決定性和可能性連結均有助於建立使用者身分的結構。

>[!NOTE]
>
>在Adobe Experience Cloud Device Co-op中，裝置、人員和身分等 *詞語**有*&#x200B;特定意義 ** 。 For example, *device* can refer to physical hardware such as a phone or tablet and the applications that run on that hardware. 請參閱[名詞解釋](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c)以取得定義。

## What are links? {#section-2df4c6f01eba49369993146df0661f13}

談到連結時，務必記得這些連結實際是在 [!DNL Experience Cloud] 裝置圖表的內容中。在此內容中，連結不是裝置之間的實體連線。相反的，連結是裝置圖表將不同的裝置與相同的未知人員產生關聯的方式。例如，假設我們有行動電話和桌面瀏覽器。一旦裝置圖表判定這兩個裝置均是由相相同的未知人員使用時，電話和瀏覽器都可被視為「已連結」。您將在以下閱讀到，裝置圖表會使用決定性和可能性連結建立身分。同時，在裝置圖表中，裝置的擁有者為實際人員的匿名表示。

## Deterministic links {#section-33d41e828a674b398e36fe63da20ac09}

決定性連結會根據驗證事件 (例如從裝置對網站的登入動作) 將裝置與人員相關聯。此動作會建立匿名的識別碼，即消費者識別碼。讓我們看一下決定性連結的運作方式。在此範例中，人員 A 透過其行動裝置上的應用程式登入至新聞網站。當天稍後，人員 A 再次登入，但此時是透過其筆記型電腦上的瀏覽器。

![](assets/link1.png)

根據登入資訊，裝置圖表:

* 得知人員 A 利用行動電話/應用程式和筆記型電腦/瀏覽器裝置的組合，向新聞網站進行驗證。
* 將這些裝置連結至人員 A。
* 根據與匿名人員相關聯的連結裝置建立身分。

![](assets/link2.png)

>[!NOTE]
>
>此資料中 [!DNL Adobe Experience Cloud Device Co-op] 的或者 [!DNL Device Graph] 都不會收到實際的驗證資訊或個人識別資訊(PII)。 Members of the [!DNL Experience Cloud Device Co-op], pass in cryptographically hashed, unique consumer IDs to the Device Graph. 消費者識別碼代表圖表中經驗證的使用者，並且保護消費者隱私權。

## Probabilistic links {#section-5f5aa755da984f9d851f7cb380262998}

可能性連結會以演算法形式將裝置連線至人員，根據特質和中繼資料，例如:

* 瀏覽行為
* IP 位址
* 作業系統
* IDFA 和 GAID 識別碼

讓我們看一下可能性連結的運作方式。在此範例中，人員 A 在其平板電腦上然後從桌面電腦瀏覽新聞網站。瀏覽時，人員 A 沒有登入新聞網站。在每個個別造訪期間，平板電腦和桌面分享相同的 IP 位址。

![](assets/link3.png)

Based on this information, the [!DNL Device Graph] evaluates IP address sharing patterns between both devices and links these devices together if the results suggest they belong to Person A. The end result is hierarchy of identity derived from algorithmic probability calculations.

![](assets/link4.png)

在此範例中，在使用兩個裝置來存取相同的新聞網站之後，裝置圖表會將這兩個裝置連結。但是，不需在要連結的相同網站上看見這些裝置。為了說明這一點，讓我們假設此範例中的每個裝置會造訪完全不同的網站。The [!DNL Device Graph] algorithm can still make a probabilistic link based on their shared IP address and from an analysis of other data. 此程序有助於讓可能性連結對 [!DNL Experience Cloud] Device Co-op 的成員功能如此強大。

## Both types of data provide value {#section-43d22d8c10634edcb261e7bda6fdf323}

決定性和可能性資料彼此相輔相成。相對之下，僅包括決定性資料的裝置圖表提供您人員身分的有限檢視。若無驗證，裝置圖表無法告知您瀏覽您的網站的相關其他裝置和人員。可能性資料可以進行這些連線，並幫助您觸及未經驗證的裝置、人員和家庭。

不過，決定性資料也很重要。例如，透過移除在可能性信號充足和重複 (例如咖啡館、圖書館、機場等等) 的地點中所產生的錯誤連結，它可以改善可能性決策制定。

相較於單獨利用一種類型，利用這兩種資料類型，裝置圖表可提供對於人員的身分更全面的樣貌。

![](assets/link5.png)

