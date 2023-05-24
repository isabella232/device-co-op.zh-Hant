---
description: 關於Device Co-op （Identity Services Cooperative和Identity Graph）常見問題的解答。
title: Device Co-op常見問題集
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# 常見問題集{#faq}

關於Identity Services Cooperative和Identity Graph的說明和常見問題解答。

**什麼是 [!DNL Device Co-op]？**

Device Co-op是參與Adobe Experience Cloud客戶的數位合作社，可共同合作以更清楚識別跨裝置的客戶。

**Device Co-op使用哪些技術？**

Device Co-op包含兩項技術：

* **Experience CloudID服務：** Adobe Experience Cloud的這項核心服務會提供通用ID，方便在不同解決方案、管道、體驗和裝置間以一致的方式識別消費者。
* **Adobe Experience Cloud Device Co-op：** 此技術可連結消費者或家庭使用的不同裝置。

**如何 [!DNL Device Co-op] 工作？**

當品牌透過匿名登入和網站造訪，在跨裝置謎題中展開攻勢時，Adobe會處理這些資料以形成裝置叢集，這些裝置叢集代表不明人士使用的一組裝置。 這些裝置叢集會提供給Device Co-op成員，並用來為其消費者提供更好、更一致的跨裝置體驗。

**如何 [!DNL Device Co-op] 連結裝置？**

另請參閱 [確定性連結和概率性連結](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**參與者提供哪些資料 [!DNL Adobe]？**

另請參閱 [消費者選擇退出工具、隱私權和裝置圖表](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**哪些資料會在以下兩者之間共用： [!DNL Device Co-op] 成員？**

另請參閱 [裝置圖表中的連結共用](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**可以是 [!DNL Device Co-op] 成員是否看到從未看過的裝置連結？**

不可以。 Device Co-op成員只能根據已瀏覽其品牌其中一項網頁屬性的裝置來取得資料。 另請參閱 [已知裝置](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知的裝置](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**我是否需要分享我公司的任何行銷資訊？**

不可以。 品牌僅向Adobe提供匿名裝置資料。

**會 [!DNL Adobe] 在中使用個人識別資訊(PII) [!DNL Device Co-op]？**

不可以。 所有個人識別資訊都會在傳入任何Adobe系統之前經過雜湊處理，因此您的客戶資訊絕不會傳輸至Adobe系統。

**相較於大型同行，對Device Co-op貢獻較少裝置資料的小品牌是否獲得較之投入更多的價值？**

不可以。 所有合作社成員都能獲得與其投入內容相關的價值。 舉例來說，如果品牌貢獻了10,000部裝置，他們便能收到與這10,000部裝置相關聯的額外連結裝置資訊。 縱觀全貌，這項貢獻似乎微不足道；但隨著越來越多不同規模的品牌加入，彙總的貢獻也相當顯著，且將為許多其他品牌（也許規模更大）正在尋找的裝置提供缺失的連結。 另請參閱 [公平性與已知裝置](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**如何 [!DNL Adobe] 如果某些國家/地區將IP位址視為個人資訊，是否要管理IP位址？**

Device Co-op首先在美國和加拿大發行，因為這兩個國家的IP位址不被視為個人資訊。 當Cooperative在IP位址被視為個人資訊的國家發行時，將不使用IP位址。
