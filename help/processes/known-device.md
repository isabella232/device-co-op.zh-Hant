---
description: 關於裝置圖表中的已知裝置。
seo-description: 關於裝置圖表中的已知裝置。
seo-title: 已知裝置
title: 已知裝置
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Known devices{#known-devices}

關於裝置圖表中的已知裝置。

在裝置圖表中，我們具有 *`known device`*. 已知裝置是客戶用來與您的品牌的裝置。

>[!NOTE]
>
>在中 [!DNL Adobe Experience Cloud Device Co-op]，詞語 *`device`*&#x200B;如 *`person`*、 *`identity`* 等。 有特定意義。例如，「裝置」可能是指實體硬體，例如手機或平板電腦與在該硬體上執行的應用程式。請參閱[名詞解釋](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c)以取得定義。

## Supporting goals with the known device {#section-80deae33660e4280ac65c659ceff5601}

已知裝置的概念支援建立與維護有效 [!DNL Device Co-op] 計劃的一些基本目標。已知裝置是 [!DNL Device Co-op] 成員從與消費者的互動 (例如網站造訪或使用行動應用程式) 而得知的裝置。Based on these actions, the [!DNL Device Graph] links the known devices of a [!DNL Device Co-op] member to devices contributed by other [!DNL Device Co-op] members. 這些連結可以是確定性 [或概率性的](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)。 This benefits [!DNL Device Co-op] members because they receive:

* 其已知裝置的更多資料。
* 其他連結裝置的相關新資訊。

![](assets/known-device.png)

The [!DNL Device Graph] will not provide information about device-clusters that a Device Co-op member has not seen.

## Device Co-op goals {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Three main goals animate the [!DNL Device Co-op]. 這些包括:

* **規模:** 在各種使用案例間分享最大數量的可能性連結。
* **公平性:** 確保 [!DNL Device Co-op] 的每個成員能夠以與他們的貢獻相當的方式獲益。

* **消費者信任:** 透過確定消費者跨裝置體驗牽涉到他們已知和信任的品牌，保有並建立消費者信賴。

## Scale and the known device {#section-67f734109762457ca62ec306284ea082}

以下方法是裝置符合已知裝置資格的較常見方式。 提供這些方法，[!DNL Device Co-op] 成員將幾乎一律具備至少 1 個已知裝置。這可支援提供最大規模給 [!DNL Device Co-op] 所有成員的目標。

**自然**

* 來自客戶造訪您的網站或透過使用您的應用程式。來自第一方的資料即符合資格。
* 透過 CRM 系統將客戶上架。

**Marketplace**

* 自 Audience Marketplace 購買區段資料。
* 來自向第三方資料提供者購買資料。

**廣告**

透過贏得拍賣中的存貨，以及對裝置提供廣告。如果該廣告包含 [!DNL Audience Manager] 像素，裝置會變成已知裝置。

## Known devices and fairness use cases {#section-0543188729d845d6b95db70b8b25e9f8}

Members of the [!DNL Device Co-op] get links commensurate with their contributions to the [!DNL Device Graph]. Companies that contribute a lot of devices to the [!DNL Device Graph] receive more links than members who contribute just a few. 我們相信，這有助於讓 [!DNL Device Co-op] 對所有成員公平。讓我們看一下其對於以下所述的大型和小型使用案例的運作方式。

**品牌A:大用案**

在此範例中，品牌 A 每個月有 100 個網站訪客，並且開始了新的跨裝置品牌促銷活動。For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand A are linked to 1 additional device. 這表示品牌A可能會觸及另外100台裝置。 Additionally, the [!DNL Device Graph] contains about 200 devices linked together.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 已知裝置/月 </th> 
   <th colname="col2" class="entry"> 從 Device Co-op 接收的連結裝置 </th> 
   <th colname="col3" class="entry"> 行銷活動的裝置總計 </th> 
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

**品牌 B: 小型使用案例**

在此範例中，品牌 B 每個月有 100 個網站訪客，並且開始了新的跨裝置品牌促銷活動。For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand B are linked to 50 additional devices. 這表示品牌 B 可以觸及 150 個裝置。Additionally, the [!DNL Device Graph] contains about 1,000 devices linked together.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 已知裝置/月 </th> 
   <th colname="col2" class="entry"> 從 Device Co-op 接收的連結裝置 </th> 
   <th colname="col3" class="entry"> 行銷活動的裝置總計 </th> 
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
>* [未知裝置](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

