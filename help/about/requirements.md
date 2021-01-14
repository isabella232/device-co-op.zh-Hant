---
description: 您的公司必須符合這些最低標準，才能開始使用Experience Cloud Device Co-op。
seo-description: 您的公司必須符合這些最低標準，才能開始使用Experience Cloud Device Co-op。
seo-title: 會籍需求
title: 會籍需求
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 1ab7be570ea63645c6d6065341d31bf170f79715
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 16%

---


# 會籍要求{#membership-requirements}

您的公司必須符合這些最低標準，才能開始使用Experience Cloud Device Co-op。

## 要求 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

與[!DNL Adobe representative to get started]通話。 如果Adobe認定潛在客戶可能(1)違反任何適用法律；或(2)對Adobe或其任何客戶的安全性或營運造成重大風險。

## Experience Cloud需求{#section-76218a50385d43e6b9323e49f598394a}

您必須已啟用[!DNL Adobe Experience Cloud]，並使用下列解決方案和服務來參與合作計畫。

**解決方案**

申請人必須至少使用下列其中一個[!DNL Adobe]解決方案：

* [Analytics](http://www.adobe.com/tw/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/tw/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**核心服務**

申請人必須實作[Experience Cloud ID服務](https://docs.adobe.com/content/help/zh-Hant/id-service/using/home.html)。

## Adobe程式碼庫需求{#section-931a3fca1ce54afd90b88ba032e75f05}

下表列出各種[!DNL Experience Cloud]解決方案與服務所使用之程式碼庫或SDK的最低版本。 如果您使用任何此程式碼並想要參與Device Co-op，請確定您符合這些最低要求。

>[!TIP]
>
>建議您使用最新的程式碼版本，而非所需的最低版本，這是最佳實務。

**AppMeasurement(Flash)**

需要4.1版。請參閱[ AppMeasurement for Flash、Flex和AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md)。

**AppMeasurement(JavaScript)**

需要1.5.4版。請參閱[ AppMeasurement for Flash、Flex和AIR](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/js/migrate-from-hcode.html)。

**行動 SDK**

最低行動SDK需求：

* Android 4.8.3 版.
* iOS 4.8.5 版.

您的SDK程式碼必須已啟用[!DNL Experience Cloud] ID服務。 為[Adobe Mobile Services](https://mobilemarketing.adobe.com/)帳戶中的每個應用程式啟用並下載最新的SDK程式碼。 請參閱[設定SDK訪客ID服務選項](https://docs.adobe.com/content/help/zh-Hant/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html)。

對於每個SDK，請使用符合您需求的適當`visitorSyncIdentifier`方法。 請參閱：

* [Android Experience Cloud ID服務方法](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS Experience Cloud ID服務方法](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

需要1.5.4版。

[!DNL Analytics] 客戶可從下載VisitorAPI.js程式庫 [!DNL Code Manager]。它位於JavaScript（新）或JavaScript（舊版）檔案中。 如果您沒有[!DNL Code Manager]的存取權，請聯絡[客戶服務](https://helpx.adobe.com/tw/marketing-cloud/contact-support.html)。

**目標程式庫**

需要下列其中一個[!DNL Target] JavaScript程式庫：

* at.js（任何版本）
* mbox.js 58版或更新版本

