---
description: 當某人的裝置不用於與您的品牌互動時，這些裝置稱為未知裝置。
seo-description: 當某人的裝置不用於與您的品牌互動時，這些裝置稱為未知裝置。
seo-title: 未知設備
title: 未知設備
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---


# 未知設備{#unknown-devices}

當某人的裝置不用於與您的品牌互動時，這些裝置稱為未知裝置。

## 未知的設備類別 {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

您有幾種方式或類別可能會將裝置視為「未知」。 這些類別包括：

* **對其他Device Co-op會員的第一方瀏覽：** 造訪其他會 [!DNL Device Co-op] 員網站或廣告到裝置本身並不會讓裝置為您的品牌所知。

* **未追蹤廣告庫存：** 可用但尚未提供或吸收的廣告庫存並不會讓您的品牌知道裝置。
* **消費者選擇退出：** 為尊重消費者的需求，已選擇退出的裝置不被視為已知裝置。

與已知裝置不同，未知裝置不會連結至其他裝置或與個人相關聯。

## 設定已知／未知狀態的規則 {#section-fa5c85e59e2d4f88bb79f27f17f02344}

當將 [!DNL Device Graph] 設備分類為已知設備與未知設備時，這些設備盡可能包容。 幫助確定已知／未知狀態的規則按優先順序順序工作（1最高），如下所示：

* **規則1:** 裝置是否已選擇退出？ 如果是，則設備未知。
* **規則2:** 此裝置是否使用任何方 *法* ? 如果是，則設備已知。

* **規則3:**如果上一個不適用，則設備為未知。

>[!MORELIKETHIS]
>
>* [已知裝置](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

