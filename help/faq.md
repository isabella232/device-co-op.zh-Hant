---
description: 對Device Co-op（Identity Services Cooperative和Identity Graph）的常見問題的解答。
title: Device Co-op常見問答集
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: e7a53a4892a8769fc178f5f3f2b82201589177b2
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# 常見問題集{#faq}

關於身分服務合作社和身分圖表的常見問題說明與解答。

**什麼東西 [!DNL Device Co-op]?**

Device Co-op是數位合作社，讓參與Adobe Experience Cloud客戶合作，以更好地識別不同裝置的消費者。

**Device Co-op中使用哪些技術？**

Device Co-op包含兩項技術：

* **Experience CloudID服務：** Adobe Experience Cloud的這項核心服務提供通用ID，以便在解決方案、通道、體驗和裝置上一致識別消費者。
* **Adobe Experience CloudDevice Co-op：此** 技術可連結消費者或家庭使用的不同裝置。

**如何運 [!DNL Device Co-op] 作？**

當品牌透過匿名登入和網站造訪，在跨裝置拼圖中拼湊素材時，Adobe會處理這些資料，以形成裝置叢集，代表未知人士使用的一組裝置。 這些裝置叢集會提供給Device Co-op會員，用來為其消費者提供更好、更一致的跨裝置體驗。

**連結裝置 [!DNL Device Co-op] 的方式？**

請參閱[確定性和概率性連結](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)。

**參與者提供哪些資料 [!DNL Adobe]?**

請參閱[消費者選擇退出工具、隱私權和裝置圖表](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)。

**成員之間共用哪些 [!DNL Device Co-op] 資料？**

請參閱「裝置圖表」中的[連結共用。](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf)

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**會員可 [!DNL Device Co-op] 以看到他們以前從未見過的裝置連結嗎？**

否。Device Co-op會員只能根據造訪過其品牌其中一個Web屬性的裝置取得資料。 請參閱[已知設備](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)和[未知設備](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。

**我是否需要分享公司的行銷資訊？**

否。品牌僅提供匿名裝置資料給Adobe。

**在 [!DNL Adobe] 中是否使用個人識別資訊(PII) [!DNL Device Co-op]?**

否。所有個人識別資訊在匯入任何Adobe系統之前都會雜湊，因此客戶的資訊永遠不會傳輸至Adobe系統。

**較小品牌對Device Co-op貢獻較少的裝置資料，與較大品牌相比，其價值是否高於所投入的價值？**

否。合作社的所有成員都會獲得相對於他們投入的價值。 例如，如果品牌貢獻了10,000台裝置，他們將能夠接收與這10,000台裝置相關的其他連結裝置資訊。 從全局看，這一貢獻可能微不足道；但隨著越來越多各種規模的品牌加入，總體貢獻相當可觀，而且會為許多其他品牌所尋找的許多裝置提供缺失的連結。 請參閱[公平性和已知設備](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)。

**如果有 [!DNL Adobe] 些國家將IP位址視為個人資訊，如何管理IP位址？**

Device Co-op首先在美國和加拿大發行，IP位址不被視為個人資訊。 在將IP位址視為個人資訊的國家／地區中發行合作社時，將不會使用IP位址。
