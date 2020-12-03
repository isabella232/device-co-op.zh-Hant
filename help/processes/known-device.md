---
description: 關於裝置圖表中的已知裝置。
seo-description: 關於裝置圖表中的已知裝置。
seo-title: 已知裝置
title: 已知裝置
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '571'
ht-degree: 1%

---


# 已知裝置{#known-devices}

關於裝置圖表中的已知裝置。

在「裝置圖」中，我們有概念 *`known device`*。 已知裝置是客戶用來與品牌互動的裝置。

>[!NOTE]
>
>在中 [!DNL Adobe Experience Cloud Device Co-op]，詞語 *`device`*&#x200B;如 *`person`*、 *`identity`* 等。 有著特殊意義。 例如，「裝置」可指實體硬體，例如手機或平板電腦，以及在該硬體上執行的應用程式。 請參閱詞 [匯表](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) ，以瞭解定義。

## 使用已知裝置支援目標 {#section-80deae33660e4280ac65c659ceff5601}

已知的裝置概念支援建立和維護有效程式所必須的幾項 [!DNL Device Co-op] 目標。 已知裝置是會員 [!DNL Device Co-op] 透過與消費者的互動（例如網站造訪或使用行動應用程式）所瞭解的裝置。 基於這些操作，會將成 [!DNL Device Graph] 員的已知設備鏈 [!DNL Device Co-op] 接到其他成員提供的設 [!DNL Device Co-op] 備。 這些連結可以是確定性 [或概率性的](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)。 這可讓會 [!DNL Device Co-op] 員獲益，因為他們可獲得：

* 更多有關其已知裝置的資料。
* 其他連結裝置的新資訊。

![](assets/known-device.png)

將 [!DNL Device Graph] 不提供Device Co-op成員未看到的裝置叢集資訊。

## Device Co-op目標 {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

三個主要目標為這個計畫注入了活力 [!DNL Device Co-op]。 這些類別包括：

* **規模：** 在各種使用案例中共用最大可能的連結數。
* **公平：** 確保每位成員的 [!DNL Device Co-op] 利益均與其貢獻相符。

* **消費者信任：** 透過確保消費者跨裝置體驗與他們已熟悉和信賴的品牌相關，來維持和建立消費者信心。

## 縮放和已知裝置 {#section-67f734109762457ca62ec306284ea082}

以下方法是裝置符合已知裝置資格的較常見方式。 基於這些方法， [!DNL Device Co-op] 成員幾乎總有至少1個已知設備。 這支援向所有成員提供最大規模的目標 [!DNL Device Co-op]。

**有機**

* 從客戶造訪您的網站或使用您的應用程式。 這是來自第一方資料的資格。
* 透過CRM系統的入門客戶。

**Marketplace**

* 從Audience Marketplace購買區段資料。
* 從第三方資料供應商購買資料。

**廣告**

透過在拍賣中贏取庫存並將廣告提供至裝置。 如果廣告包含像素，則裝置會變成已知 [!DNL Audience Manager] 裝置。

## 已知裝置與公平性使用案例 {#section-0543188729d845d6b95db70b8b25e9f8}

成員可 [!DNL Device Co-op] 獲得與其對本公司貢獻相稱的聯繫 [!DNL Device Graph]。 提供大量裝置的公司會收到比只提供 [!DNL Device Graph] 少量裝置的會員更多的連結。 我們相信，這有助於 [!DNL Device Co-op] 讓所有成員公平。 讓我們來看看以下說明的大小使用案例如何運作。

**品牌A:大用案**

在此範例中，品牌A每個月有100位網站訪客，並開始新的跨裝置品牌促銷活動。 為簡單起見，假設 [!DNL Device Graph] 知道品牌A的所有訪客都連結至另外1個裝置。 這表示品牌A可能會觸及另外100台裝置。 此外，它包 [!DNL Device Graph] 含大約200種連結在一起的裝置。

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 已知裝置／月 </th> 
   <th colname="col2" class="entry"> 從Device Co-op收到的連結裝置 </th> 
   <th colname="col3" class="entry"> 促銷活動的裝置總數 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**品牌B:小型使用案例**

在此範例中，品牌B每個月有100位網站訪客，並開始新的跨裝置品牌促銷活動。 為簡單起見，假設 [!DNL Device Graph] 所有品牌B的訪客都連結至另外50部裝置。 這表示B品牌可觸及150部裝置。 此外，它 [!DNL Device Graph] 包含大約1,000個連結在一起的裝置。

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 已知裝置／月 </th> 
   <th colname="col2" class="entry"> 從Device Co-op收到的連結裝置 </th> 
   <th colname="col3" class="entry"> 促銷活動的裝置總數 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [未知設備](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

