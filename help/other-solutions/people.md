---
description: 人員量度是基於 Adobe 裝置圖表的人員 (或裝置群組) 的計數。您可以在 Analysis Workspace 中套用人員量度以在訪客的裝置間識別訪客。
seo-description: 人員量度是基於 Adobe 裝置圖表的人員 (或裝置群組) 的計數。您可以在 Analysis Workspace 中套用人員量度以在訪客的裝置間識別訪客。
seo-title: 人員量度
title: 人員量度
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# 人員量度{#people-metric}

人員量度是基於 Adobe 裝置圖表的人員 (或裝置群組) 的計數。您可以在 Analysis Workspace 中套用人員量度以在訪客的裝置間識別訪客。

## People Metric Prerequisites and Considerations {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 先決條件或考慮事項 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Device Co-op </p> </td> 
   <td colname="col2"> <p> To use the People metric, become a member of the <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. Co-op可識別個人的多種裝置（或Experience Cloud ID）。 Analytics 運用此項資訊，以統計方式推導出與一個品牌互動的人數。量度精確到5%以內。 </p> <p><b>地區</b>: Device Co-op 目前僅在美國和加拿大提供。因此，在評估人員量度時，應該套用區段至您的分析中，僅篩選美國和加拿大的資料。 </p> <p>裝置圖表每週會計算合作社的新版本並發佈它供使用。在星期二，系統會收集最新的資料並發佈更新版本的圖表。然後，Experience Cloud解決方案會使用圖形的最新版本。 尤其是Analytics，變更會在星期三讀入，而處理變更通常需要1到2個工作天。 </p> <p> <p>重要： 每週更新圖表時，它會影響「人員」量度的歷史記錄。 換言之，歷史「人員」計數會隨著圖形學習和更新而隨時間而變更。 例如，如果您今天執行上個月計算人數的報表，然後在圖形更新後一週內執行相同的報表，則歷史人數會稍有變更。 </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 量度權限 </td> 
   <td colname="col2"> <p>您只有在已授予存取權時，才可使用「人員」量度。 管理員可<a href="https://marketing.adobe.com/resources/help/en_US/reference/groups-metrics.html" format="html" scope="external"> 在「管理工具</a> 」中自訂量度權限。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 對應至IMS組織 </td> 
   <td colname="col2"> <p>「人員量度」將會針對對應至IMSORG的所有報 <a href="https://marketing.adobe.com/resources/help/en_US/mcloud/map-report-suite.html" format="html" scope="external"> 表套裝啟用</a>。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>分析專案/工具 </p> </td> 
   <td colname="col2"> <p>使用 <span class="wintitle">Analysis Workspace</span> 中的人員量度、<span class="wintitle">臨機分析</span>、<span class="wintitle">報告建立工具</span>和透過 API。只要會用到「獨特訪客」量度的地方 (包括計算量度)，都可使用它。 </p> <p>例如，您可建立每人收入量度來取代每個獨特訪客收入量度。 </p> <p><a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html" format="html" scope="external">人員專案範本</a>可在 Analysis Workspace 中使用人員量度來開始使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>開啟 bot 規則 </p> </td> 
   <td colname="col2"> <p>Adobe 建議您開啟 <a href="https://marketing.adobe.com/resources/help/en_US/reference/bot_rules.html" format="html" scope="external">bot 規則</a>，特別是使用人員量度時。 </p> <p>當 bot 抓取您的網站時，它會特意增加您的獨特訪客計數。從您的報表套裝中移除 bot 流量，可為您的數位財產上的活動提供更準確的測量，同時就獨特訪客和人員方面。 </p> <p>若要這麼做，請導覽「<span class="uicontrol">Analytics</span> &gt; <span class="uicontrol">管理員</span> &gt; <span class="uicontrol">報表套裝</span>」。選取正確的報表套裝，然後前往「<span class="uicontrol">編輯設定</span> &gt; <span class="uicontrol">一般</span> &gt; <span class="uicontrol">Bot 規則</span>」。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>劃分考量 </p> </td> 
   <td colname="col2"> <p> 使用區段搭配人員量度時，量度報告可能會較預期大幅降低。 </p> <p>請參閱<a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local">使用人員量度搭配區段</a>。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 人員量度是什麼? {#section-89e2b8f5e80f480391449fc8d1117a6a}

人員量度是 Analytics 報告量度，可幫助您將裝置歸屬於人員。它提供以人員為基礎的行銷檢視，讓您測量跨訪客的所有裝置上訪客的活動。將它視為獨特訪客去除重複的版本，而您可以使用人員量度對您先前使用的獨特訪客的位置進行分析。

**裝置為人員**

在人員量度可供使用之前，人員 (舉例) 可能造訪您的網站，並在三個不同裝置上參與促銷活動或品牌，且進行購買，甚至是在數分鐘內這麼做。視您的實作而定，Analytics 可能會將每個裝置報告為獨特訪客，並在 $30 的購買中將 $10 歸屬於三個裝置。

人員量度可讓您準確地將該 $30 購買歸屬於一個人員:

![](assets/people-centric-results.png)

**增加報告中的準確性**

「人員」量度可將多部裝置視同單一實體。下列 Analysis Workspace 專案會顯示獨特訪客報告與人員報告之間增加的準確性比較:

![](assets/people_report.png)

並排比較人員和獨特訪客:

![](assets/people-report.png)

**定義**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 項目 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>People </p> </td> 
   <td colname="col2"> <p>人員量度是根據消費者使用多個裝置與您的品牌互動的概念。將您的資料分割或分段愈多，在該資料片段內相同人員使用多個裝置的機會愈小。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>獨特訪客 </p> </td> 
   <td colname="col2"> <p>例如，依日期或時間將資料分割的愈多，人員和獨特訪客之間的差異愈小。如果您想要深入瞭解Device Co-op的整體影響，Adobe建議使用過去90天的日期範圍 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>壓縮 </p> </td> 
   <td colname="col2"> <p>使用簡單的計算量度，您可以以獨特訪客百分比的形式查看人員量度有多小。按一下上表中「壓縮」旁的資訊圖示來查看如何建立此量度。 </p> <p>可以在其他計算量度中使用人員來取代獨特訪客。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 如何計算人員量度? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

下圖顯示如何計算人員量度，以及針對過去的相同報告日期範圍，它如何會隨著時間降低。

![](assets/people-calculations.png)

在此範例中，假設有固定的一組訪客。如果針對過去的固定時段執行報告，它會顯示固定的一組訪客。如果裝置圖表輸出的資料顯示在圖形左側的第 1 週，結果是 90 個人員。一週後，在裝置圖表下一次執行之後，會將新資訊納入考量。如果您執行與一週前所執行相同的報告，人員的數量已下降為 84。因為裝置圖表提供關於哪些裝置應該群組在一起的新資訊，歷史記錄已變更。

## 使用人員量度搭配區段 {#section-d03525420dbe48379fd95b230ef05885}

使用區段搭配人員量度時，量度結果可能會較預期大幅降低。發生此問題是因為在劃分中，沒有 *`person`* container. 劃分會使用訪客容器，它是定義中的最高層級容器，並且是根據裝置而不是人員。

此問題主要發生在堆疊區段與人員量度時。

![](assets/people-stacked-segments.png)

堆疊區段會建立代表區段組合的新區段。每當您執行下列動作時，會發生堆疊區段:

* 在 Analysis Workspace 中將區段放置在另一個區段上方。(這些是自動加入，使用&#x200B;*`And`*&#x200B;運算子。)
* Apply a single segment that contains the *`And`* operator.
* 同時在專案層級和表格層級套用區段。
* 對另一個區段使用虛擬報表套裝。

例如，假設您在人員量度上堆疊下列區段:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Only the number of people who qualify in both segments *`using a single device`* are counted. (人員量度不會顯示裝置間合格人員的數量。)

同時，不建議在此情況下使用&#x200B;*`Or`*&#x200B;運算子。這麼做會產生看見一個或另一個的人員計數，而沒有方法計算符合這兩個區段的人員數量。

如需相關資訊，請參閱劃分說明中的[建立區段](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_build.html)。

## 裝置類型 {#section-8ab378c84ff34574b9c20fecb3848a86}

當您的報表套裝包含來自多個裝置類型的資料時，Device Co-op 和人員量度最適合 Adobe Analytics。例如，在相同的報表套裝中結合 Web 和應用程式資料，可讓人員量度功能更強大且更有效。資料中有更多交叉裝置，多個獨特訪客將群組在一起成為單一人員的機會愈大。

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-op要求您的數位屬性必須使用Experience Cloud ID(MCID)服務進行檢測。 如果報表套裝中的資料包含大量不具 MCID 的訪客，Device Co-op 與人物量度的有效性將會縮減。

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, create a [project](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/t_freeform_project.html), then drag the **[!UICONTROL People]** metric to the project table:

![](assets/people-metric.png)

