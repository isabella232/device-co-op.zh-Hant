---
description: Identity Services Cooperative 和身分圖表相關常見問題的說明與解答。
seo-description: Identity Services Cooperative 和身分圖表相關常見問題的說明與解答。
seo-title: 常見問題集
title: 常見問題集
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# 常見問題集{#faq}

Identity Services Cooperative 和身分圖表相關常見問題的說明與解答。

**什麼[!DNL Device Co-op]?**

Device Co-op是數位合作社，可讓參與Adobe Experience Cloud客戶攜手合作，以更好地識別不同裝置上的消費者。

**Device Co-op 中使用什麼技術?**

Device Co-op 包含兩個技術:

* **Experience Cloud ID服務：** 此Adobe Experience Cloud核心服務提供通用ID，讓您在解決方案、通道、體驗和裝置上一致識別消費者。
* **Adobe Experience Cloud Device Co-op:** 此技術可連結消費者或家庭使用的不同裝置。

**如何運[!DNL Device Co-op]作？**

由於品牌會透過匿名登入和網站造訪投入跨裝置難題的部分，Adobe 會處理此資料以形成代表未知人員所使用的一組裝置的裝置叢集。這些裝置叢集會提供給 Device Co-op 成員，並用來提供消費者更好、更為一致的跨裝置體驗。

**如何連結[!DNL Device Co-op]裝置？**

See [Deterministic and Probabilistic Links](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**參與者提供哪些資料[!DNL Adobe]?**

請參閱[消費者選擇退出工具、隱私權和裝置圖表](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)。

**哪些資料會在成員之間[!DNL Device Co-op]共用？**

See [Link Sharing in the Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**[!DNL Device Co-op]成員能夠看見他們未曾看見的裝置連結嗎?**

不會。Device Co-op 成員僅能根據已造訪他們其中一個品牌 Web 屬性的裝置取得資料。請參閱 已知 [設備](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知設備](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。

**我將需要分享我的公司的任何行銷資訊嗎?**

不會。品牌只需提供匿名裝置資料給 Adobe。

**在[!DNL Adobe]中是否使用個人識別資訊(PII)[!DNL Device Co-op]?**

不會。所有個人可識別資訊會經過雜湊處理，之後才帶入 Adobe 系統，因此您的客戶的資訊絕不會傳送至 Adobe 系統。

**貢獻較少裝置資料給 Device Co-op 的小型品牌，相較於其較大型相應品牌，是否能獲得比其所提供內容更多的價值?**

不會。Cooperative 的所有成員可取回與他們所提供內容相對的價值。例如，如果某個品牌貢獻 10,000 個裝置，它們將可獲得與這 10,000 裝置關聯的其他連結的裝置資訊。從全貌的觀點看，此貢獻似乎很小；但隨著愈來愈多的各種規模品牌加入，彙總的貢獻即很明顯，並將提供其他品牌 (也許是更大型品牌) 正在尋求的許多裝置的遺漏連結。請參 [閱公平與已知裝置](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)。

**如果某些國家/地區將 IP 位址視為個人資訊，[!DNL Adobe]將如何管理 IP 位址?**

Device Co-op 最先在美國和加拿大釋出，在這些國家或地區未將 IP 位址視為個人資訊。在將 IP 位址視為個人資訊的國家或地區中釋出 Cooperative 時，將不會使用 IP 位址。
