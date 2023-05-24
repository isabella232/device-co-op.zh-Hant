---
description: 當使用者擁有未用來與您的品牌互動的裝置時，這些裝置稱為未知裝置。
seo-description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-title: Unknown devices
title: 未知的裝置
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
exl-id: 7841bf32-7327-4981-86a2-600e2bfe5901
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---

# 未知的裝置{#unknown-devices}

當使用者擁有未用來與您的品牌互動的裝置時，這些裝置稱為未知裝置。

## 未知的裝置類別 {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

有幾種方式或類別會將裝置視為您「未知」。 這些類別包括：

* **其他Device Co-op成員的第一方造訪：** 其他專案的造訪次數 [!DNL Device Co-op] 成員網站或裝置的廣告本身不會讓您的品牌知道裝置。

* **未追蹤的廣告詳細目錄：** 可用但尚未提供或內嵌的廣告詳細目錄不會讓您的品牌知道裝置。
* **消費者選擇退出：** 為了尊重消費者的需求，已選擇退出的裝置不被視為已知裝置。

與已知裝置不同，未知裝置未連結至其他裝置或與個人相關聯。

## 設定已知/未知狀態的規則 {#section-fa5c85e59e2d4f88bb79f27f17f02344}

此 [!DNL Device Graph] 將裝置分類為「已知」與「未知」時，會儘可能讓裝置包含。 協助判斷已知/未知狀態的規則會依優先順序（1為最高）運作，如下所示：

* **規則1：** 裝置是否已選擇退出？ 如果是，則表示裝置為未知。
* **規則2：** 裝置是否由所知 *任何* 方法？ 如果是，則表示裝置已知。

* **規則3： **如果上一個不適用，則表示裝置未知。

>[!MORELIKETHIS]
>
>* [已知裝置](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

