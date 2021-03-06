---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 32c6aff94fda6fa1a7d916b440aea7d656eafa44
workflow-type: tm+mt
source-wordcount: '5575'
ht-degree: 94%

---

# Adobe Experience Cloud 发行说明 - 2022 年 7 月

![横幅](assets/experience-cloud-banner-3.png)

作为一个 Experience Maker，您的成功之路始于 [Experience League](https://experienceleague.adobe.com/?lang=en#home)。查找适用于所有级别和角色的庞大操作文档库、自学教程、操作视频和课程，还有同行网络社区以及需要时的专家支持。

>[!NOTE]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)。经常回来查看 Experience League 的最新动态。

最新更新日期：**2022 年 7 月 19 日**

* [[!DNL Experience League] 事件](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud — 中央界面组件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [数字体验 Blueprint — 教程](#blueprints)

需要帮助？访问 [Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，获取产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 活动 {#events}

Experience League 活动是您向 Adobe 产品专家学习、与之互动以及获得答案的绝佳方式！请参阅 Experience League 上的[活动](https://experienceleague.adobe.com/events/?lang=en)以了解 2022 年 7 月的最新信息。

更新日期：**2022 年 7 月 17 日**

| 活动 | 类型 | 描述 |
| -----------|---------- | ----|
| [询问专家：数据流和数据准备](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=zh-Hans) | Experience League LIVE | 这是有关 Adobe Experience Cloud 的数据收集的三场研讨会中的最后一场，我们的专家将更深入地探讨 Adobe 的高级数据收集功能，包括用于数据收集的数据准备等功能。在本次会议结束时，与会者将对从数字体验中收集数据的最新、最强大的功能充满信心&#x200B;<br>**日期：** 7月21日太平洋夏季时间上午9点 —  [详细信息](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

请参阅 Experience League 上的[活动](https://experienceleague.adobe.com/events/?lang=en)以了解即将举行活动的最新信息以及过去的视频。

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

有关最新发行信息，请参阅 Adobe 系统状态[发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hans#status)。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud — 中央界面组件和管理 {#ecloud}

Experience Cloud [中央 UI 组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)包括主页和永久性产品标题上可用的功能。这些功能包括用户配置文件设置、偏好设置和搜索。您还可以找到有关用户和产品管理、客户属性和 Experience Cloud Audiences 的帮助。

### 配置更新

>[!IMPORTANT]
>
>请查看以下有关Experience Cloud配置的通知。

Adobe正在更新其配置，以便让所有Experience Cloud客户都能够访问基础功能，这些功能有助于某些Experience Cloud产品之间的互操作性。 用户将将Adobe Experience Platform作为新授权添加到其Experience Cloud组织，其中 [!UICONTROL 数据收集] 作为包含的服务。

Adobe Experience Platform [!UICONTROL 数据收集] 包括 [标记](https://experienceleague.adobe.com/docs/tags.html?lang=en) 简化的通用标签管理，并提供可信、强大且完整的流数据基础架构。 标记可简化客户体验数据收集并简化体验交付。

**更改Admin Console**

管理员可以按如下方式查看Admin Console的更改或添加内容：

* Admin Console中的Adobe Experience Platform产品卡将包括：

   * 场所
   * 保证
   * 身份命名空间
   * 沙盒
   * 体验数据模型
   * 架构
   * 数据流
   * Visitor ID

   对于当前未使用Experience Platform的组织，您现在将看到 _Adobe Experience Platform_ 产品，包括上面列出的功能。

   对于当前使用Experience Platform的组织， _位置_ 现在将合并到Experience Platform卡中。

* Adobe Experience Platform数据收集（以前称为Launch）和隐私功能将继续显示为与其他Experience Platform功能不同的产品信息卡。

有关新功能的更多详细信息，请访问其各自的Experience League页面：

* [数据收集](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [场所](https://experienceleague.adobe.com/docs/places/using/home.html?lang=en)
* [保证](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html)
* [身份命名空间](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=zh-Hans)
* [沙箱](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=zh-Hans)
* [体验数据模型](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=zh-Hans)
* [架构](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html?lang=zh-Hans)
* [数据流](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=en)
* [Visitor ID](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=en#section_3C9F6DF37C654D939625BB4D485E4354)
* [隐私](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=zh-Hans)

### 功能更新

发布的功能： **2022年7月11日**

| 功能 | 描述 |
| ------- | ------- |
| 统一主页 - 快速访问构件 | **导航速度更快：**&#x200B;您现在可以对您的主页体验进行进一步个性化设置，并决定哪些应用程序触手可及。使用新的固定功能选择哪些应用程序显示在您的[!UICONTROL 快速访问]的前面和中心。<br>**利用智能固定功能随时了解最新动态：**&#x200B;您的新应用程序现在更容易找到。新分配的应用程序显示&#x200B;_新_&#x200B;徽章并自动固定到[!UICONTROL 快速访问]。 |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理的更多帮助资源**

* Experience Cloud 中央 UI 组件的[发行说明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hans)
* Experience Cloud 的[用户和产品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)（管理）
* 放置服务[发行说明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)
* [人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hans)的产品文档
* [统一搜索对象和实体](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新发行信息和新文档：

计划发行日期：**2022 年 7 月 27 日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### 新的 [!DNL Experience Platform] 教程和课程 {#tutorials-platform}

针对 [!DNL Experience Platform] 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [监测事件转发](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html?lang=zh-Hans) | 视频 | 了解如何在“数据收集”界面中监测事件转发。 | 数据收集 |
| 2022 年 7 月 | [监测数据提取](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html?lang=zh-Hans) | 视频 | 了解如何使用监测仪表板，监测和跟踪提取到 Adobe Experience Platform 中的数据。 | 数据收集 |
| 2022 年 7 月 | [将样本数据导入到 Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=zh-Hans) | 文章 | 了解如何使用示例数据设置 Experience Platform 沙盒环境。使用 Postman 集合，您可以创建字段组、架构和数据集，然后将示例数据导入 Experience Platform。 | Experience Platform |
| 2022 年 7 月 | [区段匹配接收数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html?lang=zh-Hans) | 视频 | 通过区段匹配，您的战略合作伙伴可以向您共享数据。在此视频中，了解如何批准和接收数据，以及在哪里查看这些数据并将其添加到您自己的区段。 | Experience Platform - 区段 |
| 2022 年 7 月 | [询问专家：Real-Time CDP 连接](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=zh-Hans) | Experience League 直播视频 | 在有关数据收集的三场直播研讨会的第二场中，我们备受欢迎的的专家将全面地介绍 Adobe RTCDP [!UICONTROL 连接]，通过它，客户可以使用服务器端标记管理系统将事件转发到非 Adobe 目标。 | 数据收集 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

下一版本：**2022 年 7 月 20 日**

上次更新：**2022 年 7 月 13 日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### 新的 [!DNL Analytics] 教程和课程 {#tutorials-analytics}

针对 Adobe Analytics 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [2022 年流改进](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html?lang=zh-Hans) | 视频 | 了解[!UICONTROL 流]可视化的一些重大改进。改进包括您可以配置感兴趣的路径的开头和结尾，对某列进行筛选以包含或排除特定项，以及可预配置的高级设置。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最新更新日期：**2022 年 7 月 12 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

### 新的 Customer Journey Analytics 教程和课程 {#tutorials-cja}

为 CJA 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [配置下一项或上一项面板](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html?lang=zh-Hans) | 视频 | 了解如何在 [!DNL Customer Journey Analytics] 中配置下一项和上一项面板。此面板生成表和可视化效果以标识特定维度值的下一项或上一项。 |
| 2022 年 7 月 | [创建注释](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=zh-Hans) | 视频 | 了解出现营销活动发布、数据问题以及假日等事件时，如何在您的 [!DNL Customer Journey Analytics] 项目中创建批注。此功能会通知您的用户这些日期或日期范围内的量度差异。 |
| 2022 年 7 月 | [创建快速过滤器](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html?lang=zh-Hans) | 视频 | 直接在您的 [!DNL Customer Journey Analytics] 项目中创建快速过滤器，并避开完整过滤器构建器的复杂性。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

上次更新时间：**2022 年 3 月 23 日**

* [!DNL Streaming Media Analytics] [发行说明](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=zh-Hans)
* [!DNL Streaming Media Analytics] [产品文档和教程](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修复和改进：

| 改进 | 描述 |
| -----------| ---------- |  
| 属于其他公司的目标数据源的验证器 | Audience Manager 发布了对[批量数据载入流程](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=zh-Hans)的改进。为了防止文件和数据意外载入其他合作伙伴拥有的目标数据源中，Audience Manager 在合作伙伴 ID (PID) 和其他合作伙伴拥有的数据源 (DPID) 之间添加了映射要求。 <ul><li>另请参阅[入站数据文件的 Amazon S3 名称和文件大小要求](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=zh-Hans#name-elements)中的 __DPID_TARGET_DATA_OWNER_ 字段。</li><li>Adobe 内部顾问和客户关怀部门应参阅[管理对第二方数据的载入访问](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=zh-Hans)，了解有关新映射要求改进以及如何请求新映射的信息</li><li>_不_&#x200B;需要为现有的数据共享关系请求映射。在数据载入属于 PID 的目标数据源时，也&#x200B;_不_&#x200B;需要映射。</li></ul> |

{style=&quot;table-layout:auto&quot;}

有关自助资源，请参阅 Experience League 上的 [Audience Manager 文档和教程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hans)。

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Experience Manager 中的新增功能、修复和更新。Adobe 建议采用内部部署的客户部署最新的修补程序以确保稳定性、安全性和性能得到提高。

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

### 产品更新视频

* [2022 年 6 月发布概述视频](https://video.tv.adobe.com/v/344308/?quality=12)，概要介绍 2022.6 版。

较早产品更新视频：

* [2022 年 5 月版概述视频](https://video.tv.adobe.com/v/343321/?quality=12)，概要介绍 2022.5.0（2022 年 5 月）版本中的功能。
* [2022 年 4 月发行版概述视频](https://video.tv.adobe.com/v/342612?quality=12)
* [2022年3月版本概述视频](https://video.tv.adobe.com/v/341465)
* [2022年1月版概述视频](https://video.tv.adobe.com/v/340120)
* [2021年12月版本概述视频](https://video.tv.adobe.com/v/339278)
* [2021年10月版本概述视频](https://video.tv.adobe.com/v/338253)
* [2021年9月版概述视频](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

[!DNL Sites] 中的新增功能：

* 内容管理员和内容作者现在可以利用[全新用户界面](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=zh-Hans)，高效地管理（执行发布、取消发布、复制和移动等操作）、搜索/筛选和为 Headless 用例创建内容片段。

* 全新[目录组件](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=zh-Hans)不仅适用于[!UICONTROL 核心组件]，而且可用于所有组件，自动在内容页面上呈现目录。而且，由于它在服务器端呈现并由 Dispatcher 完全缓存，因此也可以高效地加载。

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

[!DNL Assets] 中的新增功能：

* Experience Manager [!DNL Assets] 现在使用 Adobe Sensei AI 功能，[区分图像中的颜色并在提取时自动将其作为标记应用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=cn)。这些标记可根据图像颜色组合增强搜索体验。您可以配置在图像上标记的颜色数量，其范围在 1 到 40 之间，这样以后就可以根据这些颜色搜索图像。

### Experience Manager Forms as a Cloud Service

[!DNL Forms] 中的新增功能：

* [将[!UICONTROL 自适应表单]与 Microsoft® Power Automate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=zh-Hans) 集成：现在，您可以配置自适应表单在提交时运行 Microsoft® Power Automate Cloud Flow。配置的自适应表单将捕获的数据、附件和记录文档发送到 Power Automate Cloud Flow 进行处理。它可以帮助您构建自定义数据捕获体验，同时利用 Microsoft® Power Automate 的强大功能围绕捕获的数据构建业务逻辑并自动化客户工作流。

**创建自适应表单向导：**&#x200B;您可以使用便于企业用户使用的向导来快速创作[!UICONTROL 自适应表单]。该向导提供快速选项卡导航，以轻松选择预配置的模板、样式、字段和提交选项以创建自适应表单。

### Experience Manager as a Cloud Service 基础

新增功能：

如 5 月 (2022.5.0) 发行说明中所述，复制代理管理屏幕的“分发”选项卡下的“添加树”选项已删除。应该使用管理发布或发布内容树工作流来复制具有内容树层次结构的包。

### [!DNL Cloud Manager]

新增功能：

* [!DNL Cloud Manager] 用户现在可以随时从登陆页面的[!UICONTROL 欢迎]卡查看有用的视频教程。

* 环境详细信息页面的[恢复内容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=zh-Hans)选项卡上的弹出窗口现在会显示一个方便的 git 命令列表，以便用户在本地查看更改。

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [充分利用企业工作流管理](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=zh-Hans) | 视频 | 了解将工作流用于资源管理的好处，以及如何快速创建工作流。 | AEM - Experience 工作流管理 |
| 2022 年 7 月 | [使用 Adobe Experience Manager 提供 Headless 体验](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=zh-Hans) | 视频 | 了解使用最新 Experience Manager [!UICONTROL 内容片段] 增强功能进行 Headless 体验管理，以及用于 Headless 内容交付的新GraphQL API。 | Experience Manager [!DNL Sites] |
| 2022 年 7 月 | [在 Adobe Experience Manager Assets 中让元数据为您的业务所用](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=zh-Hans) | 视频 | 了解如何通过减少标记资源的工作量并提高资源可搜索性，在 AEM Assets 中充分利用元数据。 | Experience Manager [!DNL Assets] |
| 2022 年 7 月 | [iOS 应用程序](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html?lang=zh-Hans) | 视频 | 示例应用程序是探索 Adobe Experience Manager 的 Headless 的绝佳方法。此 iOS 应用程序演示了如何通过 AEM 的 [!UICONTROL GraphQL API]，使用持久化查询来查询内容。 | Experience Manager [!DNL Assets]，[!DNL Sites] |
| 2022 年 7 月 | [Android™应用程序](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html?lang=zh-Hans) | 视频 | 此 Android™ 应用程序演示了如何使用 AEM 的 [!UICONTROL GraphQL API] 查询内容。 | Experience Manager [!DNL Assets]，[!DNL Sites] |
| 2022 年 7 月 | [为 Adobe Experience Manager as a Cloud Service 配置 OSGi](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=zh-Hans) | 视频 | 了解如何为 AEM CS 配置 OSGI。例如，了解如何管理 OSGi 包，以及如何通过 AEM 代码项目中的配置文件来管理 OSGi 组件的配置设置。 | AEM as a Cloud Service |
| 2022 年 7 月 | [覆盖表单数据模型属性](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=zh-Hans) | 视频 | 了解如何覆盖表单数据模型属性，以便轻松地针对不同端点测试一个表单数据模型。 | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hans)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=zh-Hans)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的其他帮助资源

* [《Experience Manager as a Cloud Service 指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=zh-Hans)
* [《Cloud Manager 用户指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=zh-Hans)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] 是部署在 AEM 上的应用程序。这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。

详细了解 [[!DNL Experience Manager Guides]](https://www.adobe.com/cn/products/xml-documentation-for-experience-manager/features.html)。

### 其他资源

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=zh-Hans) – Experience League 教程
* [[!DNL Experience Manager Guides] 学习和支持](https://helpx.adobe.com/cn/support/xml-documentation-for-experience-manager.html) – 产品文档

## ![图标](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source 2.4.x 发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 发行说明](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教程和文档 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [Adobe Commerce 快速入门指南](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html) | 产品文档 | 本指南面向初次接触 Adobe Commerce 和 Magento Open Source 的商家和系统管理员。从他们的角度来概要了解该平台，并详细了解开办正常运营的网店的基本功能。 |
| 2022 年 7 月 | [Page Builder 用户指南](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html) | 产品文档 | 了解 Page Builder 功能，包括用于构建基本内容组件的三步演练。本指南面向管理员。其中假设管理员了解核心 Adobe Commerce 配置和功能。 |
| 2022 年 7 月 | [Adobe Commerce 的 B2B 指南](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html) | 管理指南 | 获取有关安装和启用此模块的详细信息，包括其功能的配置和管理。 |
| 2022 年 7 月 | [Adobe Commerce 的 B2B - 教程](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=zh-Hans) | 视频（多个） | 了解 Adobe Commerce 中的[!UICONTROL 公司]页面。您可以管理公司帐户，任何待批准的请求都会显示在列表顶部。 |
| 2022 年 7 月 | [使用 Quality Patch Tool](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html?lang=zh-Hans) | 视频 | 了解 [!UICONTROL Quality Patch Tool]，这是一个命令行工具，可为 Adobe Commerce 和 Magento Open Source 提供质量修补。 |
| 2022 年 7 月 | [站点范围分析工具仪表板](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html?lang=zh-Hans) | 视频 | 了解站点范围的分析工具。此功能是主动式自助服务工具，发挥中央存储库的作用，其中包含详细的系统分析和建议，确保 Adobe Commerce 安装的安全性和可操作性。 |
| 2022 年 7 月 | [使用付款服务](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html?lang=zh-Hans) | 视频 | 了解如何使用[!UICONTROL 付款服务]来减少运营开销，增加收入。 |
| 2022 年 7 月 | [管理订单状态](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html?lang=zh-Hans) | 视频 | 了解如何检查订单状态及其详细信息，以及如何根据需要更改订单状态。 |
| 2022 年 7 月 | [营销工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=zh-Hans) | 视频（多个） | 了解有关创建目录价格规则、购物车价格规则、管理相关产品规则、实时搜索等的信息。 |
| 2022 年 7 月 | [带来业务价值的内容个性化创新](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=zh-Hans) | 视频 | 查看 Skill Builder 演示并了解 Adobe 内容解决方案中的最新创新，这些创新可帮助您实现内容创作大众化、轻松实现全渠道交付并扩展个性化体验。 |
| 2022 年 7 月 | [目录管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html?lang=zh-Hans) | 视频 | 了解 Adobe Commerce 中的目录管理。创建类别、管理类别中的产品、管理库存等。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新日期：**2022 年 6 月 30 日**

* 有关预发行信息，请参阅 [Adobe Target 预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [Adobe Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

### Adobe Target 的新课程和教程 {#tutorials-target}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [创建受众](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html?lang=zh-Hans) | 视频 | 了解如何在 [!DNL Target] 中创建和保存自定义受众以用于您的活动。 |
| 2022 年 7 月 | [使用 Adobe Target 打造个性化和自动化](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=zh-Hans) | 视频 | 了解使用[!UICONTROL 自动定位]和[!UICONTROL 自动个性化]来实现 Adobe Target 功能自动化和优化的核心概念。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

* [Campaign v7.3 发布](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)
* [控制面板 6 月版发布](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=zh-Hans)
* Experience League 上的[教程和课程](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign?lang=zh-Hans)

### 新的 [!DNL Campaign] 教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [适用于混合托管模型的控制面板](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html?lang=zh-Hans) | 视频 | 了解如何为 Adobe Campaign 混合托管模型启用控制面板、访问控制面板以及解锁关键功能。 | 控制面板 |
| 2022 年 7 月 | [监测吞吐量和延迟](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=zh-Hans) | 视频 | 了解如何监测营销活动实例的传送吞吐量和事务性消息延迟。 | 控制面板 |
| 2022 年 7 月 | [监控工作流以优化资源使用](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=zh-Hans) | 视频 | 了解如何监测工作流的临时存储使用情况，以及在哪里配置工作流设置以避免实例上的数据库或工作流问题。 | 控制面板 |
| 2022 年 7 月 | [在 Adobe Campaign Classic 中开发和自定义数据模型](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=zh-Hans) | 视频（Skill Builder 活动） | 与我们的 Campaign 培训师一起加入此研讨会，了解如何在 Campaign Classic 的数据模型中开发数据架构。 | Campaign Classic v7 |
| 2022 年 7 月 | [推动实现成果的可交付性最佳实践和策略](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html) | 视频 | 了解如何最大限度地减少策划和制作电子邮件营销活动所花费的无数个小时。 | Campaign Classicv7 |
| 2022 年 7 月 | [利用 Adobe Campaign Classic 提高跨渠道营销水平](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=zh-Hans) | 视频 | 观看此深入分析网络研讨会，其中重点讨论了面向 Adobe Campaign Classic 客户的工作流、自动化、个性化和量度。 | Campaign Classicv7 |
| 2022 年 7 月 | [来自专家的节省时间提示！](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=zh-Hans) | 视频 | 利用 Adobe Campaign 专家介绍提示和技巧，开始新的一年！了解如何更高效地创建和启动营销活动，以及如何提供更有意义、量身定制的跨渠道体验。 | Campaign Classicv7 |
| 2022 年 7 月 | [Adobe Campaign 与营销生态系统集成](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=zh-Hans) | 视频 | 了解 Adobe Campaign 与营销生态系统的集成。像 Adobe Campaign 这样的跨渠道营销解决方案不应该与其他技术和团队隔离开来。不要让离散的系统妨碍全面了解客户并破坏跨渠道战略。 | Campaign Classicv7 |
| 2022 年 7 月 | [Adobe Campaign Standard 客户焦点 - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=zh-Hans) | 视频 | 听取 Microsoft® 的营销团队的意见，了解他们如何使用 Adobe Campaign Standard、其架构及指导原则和最佳实践。 | Campaign Standard |
| 2022 年 7 月 | [Adobe Campaign 客户焦点 - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=zh-Hans) | 视频 | 听取 Adobe Campaign 客户介绍他们如何通过 Adobe Campaign 克服挑战、适应新常态、提高营销活动管理效率并创造有意义的价值。 | Campaign Classicv7 |
| 2022 年 7 月 | [Adobe Campaign Classic V7 与 V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=zh-Hans) | 视频 | 听取我们产品经理介绍的最新的产品更新，以及 V7 和 V8 之间的差异。 | Campaign Classic v7，Campaign v8 |
| 2022 年 7 月 | [主题演讲 - 跨 B2B 和 B2C 的 Customer Journey 趋势和创新](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=zh-Hans) | 视频 | 了解跨 B2B 和 B2C 的 Customer Journey 管理的最新趋势。了解关键历程应用程序以及更广泛的 Adobe Experience Cloud 和 Adobe Experience Platform 中的最新创新。 | Marketo，Campaign Classic v7，Campaign v8 |
| 2022 年 7 月 | [Adobe Campaign Standard 的关键提示和技巧](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=zh-Hans) | 视频 | 接入您的 Adobe Campaign Standard 实例，并了解有关定位、个性化和营销疲劳度的最佳实践，以便更好地使用 ACS。 | Campaign Standard |
| 2022 年 7 月 | [支持跨渠道营销所需的团队、技能和组织设计](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html) | 视频 | 了解如何增强能力，以便按照您所需的方式随时随地进行互动。了解能够支持规划、执行和衡量的营销组织的重要性。 | Campaign Classic v7，Campaign v8，Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Campaign 帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=zh-Hans) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，只需单个应用程序即可为数百万客户管理预定的全渠道营销活动和一对一互动时刻，并用智能决策和见解优化了整个历程。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### Journey Optimizer 的新教程和课程 {#tutorials-ajo}

为 Adobe Journey Optimizer 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [配置消息频率规则](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html?lang=zh-Hans) | 视频 | 了解如何创建、激活、测试和报告频率规则。了解如何确定将为消息继承哪些频率规则。 |
| 2022 年 7 月 | [配置、创作和投放短信消息](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html?lang=zh-Hans) | 视频 | 了解如何配置、创作短信消息，并将其包含在客户历程中。 |
| 2022 年 7 月 | [短信的入站关键词支持](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html?lang=zh-Hans) | 视频 | 了解针对短信的原生入站关键词支持（开始、停止、不停止）的工作方式。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新 [!DNL Journey Orchestration] 产品版本

有关最新的功能、改进和修复的详细信息，请参阅[[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration 文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅 [!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

### 新的 Marketo 教程和课程 {#tutorials-marketo}

为 Adobe Marketo 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [使用 Marketo Engage 和 Adobe Experience Cloud 的 B2B 体验](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=zh-Hans) | 视频 | 了解 Marketo Engage 与 Adobe Experience Cloud 应用程序之间的集成，以及可以解决哪些棘手问题。 | Marketo Engage |
| 2022 年 7 月 | [携手共进 - Adobe Marketo Engage 和 Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=zh-Hans) | 视频 | 了解如何使用 Marketo Engage 和 RT-CDP（B2B 版本）编排 B2B 活动，以及有哪些最常用的用例和带来哪些优势。 | Marketo，Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [ [!DNL Advertising Cloud DSP] 中的新增功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### [!DNL Advertising Cloud DSP] 中的新增功能 {#adcloud-dsp}

上次更新时间：**2022 年 7 月 14 日**

| 功能 | 描述 |
| ------- | ----------- |
| 自定义报表 | （5 月 31 日发布，测试版功能）Advertising Cloud DSP 现在可以提取第一方区段，这些区段由在 Customer Data Platform (CDP) 中构建的经身份验证信号组成。 |
| [!UICONTROL 库存] | （6 月 29 日发布）新[!UICONTROL 库存] > [!UICONTROL 交易]视图包含与[!UICONTROL 营销活动]视图相同的数据自定义功能，包括额外的筛选条件、列自定义以及用于保存自定义视图、列排序和数据可视化（图表）视图的选项。单击交易名称后面的省略号 (...) 可在每行中打开一个命令菜单。 |
| [!UICONTROL 库存检查器] | （6 月 29 日发布）投放位置[!UICONTROL 检查器]的[!UICONTROL 库存]选项卡现在包括可自定义的数据可视化图表和扩展的性能指标，例如[!UICONTROL 可视性比率]、[!UICONTROL 点击次数]和[!UICONTROL 昨天的 CPM]。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新时间：**2022 年 7 月 14 日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 见解] | （6 月 11 日发布）印象共享损失分析现已再次作为测试版功能提供。 |
| [!DNL Advanced Campaign Management] | （6 月 20 日）（[!DNL Google Ads] 和 [!DNL Microsoft Advertising] 营销活动）现在，您可以使用特定于搜索引擎的广告模板，根据库存内容，从[!UICONTROL 营销活动] > [!UICONTROL 高级 (ACM)] 创建动态响应的搜索广告变体。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [使用审批者角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=zh-Hans) | 视频（更新） | 了解如何通过审批流程发送文档。 | Adobe Sign |
| 2022 年 7 月 | [设置 Web 表单](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html?lang=zh-Hans) | 视频（更新） | 了解如何创建可直接在您的网站上以电子方式签名的文档。 | Adobe Sign |
| 2022 年 7 月 | [使用委托人角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=cn) | 视频（更新） | 描述 | Adobe Sign |
| 2022 年 7 月 | [以电子方式签署文档](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=zh-Hans) | 视频（更新） | 了解使用 Acrobat Sign 签署发送给您的文档是何等简单。 | Adobe Sign |
| 2022 年 7 月 | [作为 Acrobat Sign 管理员启动和运行服务](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=zh-Hans) | 视频（更新） | 了解管理员应重点关注的七个关键领域，以便在 Acrobat Sign 中快速启动和运行。 | Adobe Sign |
| 2022 年 7 月 | [在 Outlook 中发送供签名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=zh-Hans) | 视频（更新） | 了解如何直接在 Microsoft® Outlook 中发送文档供签名来简化文档工作流。 | Adobe Sign |
| 2022 年 7 月 | [填写和登录 Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=zh-Hans) | 视频（更新） | 了解如何直接在 Microsoft Outlook 中填写和签名表单来简化文档工作流。 | Adobe Sign |
| 2022 年 7 月 | [创建和管理组](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=zh-Hans) | 视频（更新） | 了解如何创建组、将用户添加到组以及编辑组设置。 | Adobe Sign |
| 2022 年 7 月 | [将签署委派给其他人](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=zh-Hans) | 视频（更新） | 了解如何将签署文档委派给其他人。 | Adobe Sign |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Adobe Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。

## ![图标](/assets/experience-league.png) 客户数据管理 — 意见 {#voices}

[客户数据管理意见](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=zh-Hans)是您作为客户数据管理技术和营销实践领导者和专家的目标。本教程集是供您听取同行意见、获得灵感并了解 MarTech 发展的一站式服务。无需注册，只需点击即可观看。

## ![图标](/assets/experience-league.png) 数字体验 Blueprint {#blueprints}

[数字体验 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hans) 是可重复的实施，让您可以满足战略需求和解决已确定的业务问题。每个 Blueprint 都提供了一系列构件，这些构件说明了高价值业务问题、体系结构、实施步骤、技术注意事项以及指向相关文档的链接。

[回到顶部](#events)
