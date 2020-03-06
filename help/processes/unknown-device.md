---
description: 當人員的裝置未用來與您的品牌互動時，這些裝置稱為未知裝置。
seo-description: 當人員的裝置未用來與您的品牌互動時，這些裝置稱為未知裝置。
seo-title: 未知設備
title: 未知設備
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Unknown devices{#unknown-devices}

當人員的裝置未用來與您的品牌互動時，這些裝置稱為未知裝置。

## Unknown device categories {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

有數個方式或類別使得裝置對您而言可能是「未知」。這些包括:

* **第一方造訪其他 成員:** 對其他 [!DNL Device Co-op]Device Co-op 成員網站的造訪，或對裝置的廣告本身未使得裝置對您的品牌而言成為已知。

* **未追蹤的廣告存貨:** 廣告存貨可用，但尚未被提供或已吸納的部分未使得裝置對您的品牌而言成為已知。
* **消費者選擇退出:** 為了尊重消費者的需要，已選擇退出的裝置不會被視為已知裝置。

與已知裝置不同，未知裝置不會與其他裝置連結，也不會與個別人員相關聯。

## Rules for setting known/unknown status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

The [!DNL Device Graph] tries to be inclusive as possible when classifying devices as known compared to unknown. 可幫助決定已知/未知狀態的規則，其運作的優先順序 (1 最高) 如下所示:

* **規則 1:** 裝置是否選擇退出?如果是，則裝置為未知。
* **規則 2:** 裝置是否已透過&#x200B;*任何*&#x200B;方法成為已知?如果是，則裝置為已知。

* **規則3:**如果上一個不適用，則設備為未知。

>[!MORELIKETHIS]
>
>* [已知裝置](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

