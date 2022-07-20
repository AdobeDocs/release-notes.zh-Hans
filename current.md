---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 5c20e56d96b6fbe571cc686e2b4ed27559f39a3d
workflow-type: tm+mt
source-wordcount: '5576'
ht-degree: 49%

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

Experience League 活动是您向 Adobe 产品专家学习、与之互动以及获得答案的绝佳方式！请参阅 [事件](https://experienceleague.adobe.com/events/?lang=en) Experience League2022年7月保持更新。

已更新 **2022年7月17日**

| 活动 | 类型 | 描述 |
| -----------|---------- | ----|
| [询问专家：数据流和数据准备](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) | Experience League LIVE | 在为Adobe Experience Cloud收集数据的三场会议的最后一场会议中，我们的专家将更深入地了解Adobe的高级数据收集功能，包括用于数据收集的数据准备等功能。 在本次会议结束时，与会者将对从数字体验中收集数据的最新、最强大的功能充满信心&#x200B;<br>**日期：** 7月21日太平洋夏季时间上午9点 —  [详细信息](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

请参阅 [事件](https://experienceleague.adobe.com/events/?lang=en) Experience League，以便对即将发生的事件和过去的事件保持更新。

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

有关最新发行信息，请参阅 Adobe 系统状态[发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hans#status)。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud — 中央界面组件和管理 {#ecloud}

Experience Cloud [中央 UI 组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)包括主页和永久性产品标题上可用的功能。这些功能包括用户配置文件设置、偏好设置和搜索。您还可以找到有关用户和产品管理、客户属性和 Experience Cloud Audiences 的帮助。

### 配置更新

更新日期： **2022年7月19日**

>[!IMPORTANT]
>
>请查看以下有关Experience Cloud配置的通知。

Adobe正在更新其配置，以便让所有Experience Cloud客户都能够访问基础功能，这些功能有助于某些Experience Cloud产品之间的互操作性。 用户将将Adobe Experience Platform作为新授权添加到其Experience Cloud组织，其中 [!UICONTROL 数据收集] 作为包含的服务。

Adobe Experience Platform [!UICONTROL 数据收集] 包括 [标记](https://experienceleague.adobe.com/docs/tags.html?lang=en) 简化的通用标签管理，并提供可信、强大且完整的流数据基础架构。 标记可简化客户体验数据收集并简化体验交付。

通过此更新，管理员可能会看到对Admin Console的更改或添加内容：

1. Admin Console中的Adobe Experience Platform产品卡将包括：

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

1. Adobe Experience Platform数据收集（以前称为Launch）和隐私功能将继续显示为与其他Experience Platform功能不同的产品信息卡。

有关新功能的更多详细信息，请访问其各自的Experience League页面：

* [数据收集](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [场所](https://experienceleague.adobe.com/docs/places/using/home.html?lang=en)
* [保证](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html%3Flang%3Dde)
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

计划发布日期：**2022 年 7 月 27 日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### 新的 [!DNL Experience Platform] 教程和课程 {#tutorials-platform}

针对 [!DNL Experience Platform] 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [监视事件转发](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html) | 视频 | 了解如何在数据收集界面中监控事件转发。 | 数据收集 |
| 2022 年 7 月 | [监控数据摄取](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html) | 视频 | 了解如何使用监控仪表板监控和跟踪摄取到Adobe Experience Platform中的数据。 | 数据收集 |
| 2022 年 7 月 | [将示例数据导入Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=zh-Hans) | 文章 | 了解如何设置包含示例数据的Experience Platform沙盒环境。 使用Postman集合，您可以创建字段组、架构和数据集，然后将示例数据导入Experience Platform。 | Experience Platform |
| 2022 年 7 月 | [区段匹配接收数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html) | 视频 | 通过区段匹配，您的战略合作伙伴可以向您共享数据。 在此视频中，了解如何批准和接收数据，以及在何处可以看到数据并将其添加到您自己的区段。 | Experience Platform — 区段 |
| 2022 年 7 月 | [询问专家：Real-Time CDP连接](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=en) | Experience League实时视频 | 在有关数据收集的三场实时流会议的第二场会议中，我们最喜爱的专家对AdobeRTCDP进行了详尽的介绍 [!UICONTROL 连接]，客户可以使用服务器端标签管理系统将事件转发到非Adobe目标。 | 数据收集 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

下一版本： **2022年7月20日**

上次更新： **2022年7月13日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### 新的 [!DNL Analytics] 教程和课程 {#tutorials-analytics}

针对 Adobe Analytics 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [2022 年流改进](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html) | 视频 | 了解 [!UICONTROL 流量] 可视化图表。 改进包括您可以配置感兴趣的路径的开头和结尾，对某列进行筛选以包含或排除特定项，以及可预配置的高级设置。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最新更新日期：**2022 年 7 月 12 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

### 新的 Customer Journey Analytics 教程和课程 {#tutorials-cja}

为 CJA 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [配置下一项或上一项面板](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html) | 视频 | 了解如何在 [!DNL Customer Journey Analytics] 中配置下一项和上一项面板。此面板生成表和可视化效果以标识特定维度值的下一项或上一项。 |
| 2022 年 7 月 | [创建注释](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=en) | 视频 | 了解如何在 [!DNL Customer Journey Analytics] 当发生营销活动启动次数、数据问题和假日等事件时进行项目。 此功能会通知您的用户这些日期或日期范围内的量度差异。 |
| 2022 年 7 月 | [创建快速过滤器](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html) | 视频 | 直接在您的 [!DNL Customer Journey Analytics] 项目中创建快速过滤器，并绕过完整过滤器构建器的复杂性。 |

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

* [2022年6月版概述视频](https://video.tv.adobe.com/v/344308/?quality=12) 2022.6版本的摘要。

旧版产品更新视频：

* [2022年5月版概述视频](https://video.tv.adobe.com/v/343321/?quality=12) 有关2022.5.0（2022年5月）版本中添加的功能的摘要。
* [2022 年 4 月发行版概述视频](https://video.tv.adobe.com/v/342612?quality=12)
* [2022年3月版本概述视频](https://video.tv.adobe.com/v/341465)
* [2022年1月版概述视频](https://video.tv.adobe.com/v/340120)
* [2021年12月版本概述视频](https://video.tv.adobe.com/v/339278)
* [2021年10月版本概述视频](https://video.tv.adobe.com/v/338253)
* [2021年9月版概述视频](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

的新增功能 [!DNL Sites]:

* A [新用户界面](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=en) 现在，内容管理员和内容作者可以高效管理（执行发布、取消发布、复制和移动等操作）、搜索/筛选和为无头用例创建内容片段。

* 新 [目录组件](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=en) 不仅适用于 [!UICONTROL 核心组件] 但使用所有组件，会自动渲染内容页面上的目录。 而且，由于它呈现在服务器端并由调度程序完全缓存，因此也可以有效地加载。

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

的新增功能 [!DNL Assets]:

* Experience Manager [!DNL Assets] 现在使用Adobe Sensei AI功能 [区分图像中的颜色，并在摄取时自动将这些颜色作为标记应用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=cn). 这些标记可根据图像颜色组合增强搜索体验。您可以配置标记为图像的颜色数量（在1到40之间），以便以后可以根据这些颜色搜索图像。

### Experience Manager Forms as a Cloud Service

的新增功能 [!DNL Forms]:

* [集成 [!UICONTROL 自适应Forms] 使用Microsoft® Power自动化](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=en):现在，您可以配置自适应表单以在提交时运行Microsoft® Power Automate Cloud Flow。 配置的自适应表单将捕获的数据、附件和记录文档发送到 Power Automate Cloud Flow 进行处理。它可以帮助您构建自定义数据捕获体验，同时利用 Microsoft® Power Automate 的强大功能围绕捕获的数据构建业务逻辑并自动化客户工作流。

**创建自适应表单的向导：** 您可以使用商业用户友好向导快速创作 [!UICONTROL 自适应Forms]. 该向导提供快速选项卡导航，以轻松选择预配置的模板、样式、字段和提交选项以创建自适应表单。

### Experience Manager as a Cloud Service 基础

新增功能:

如5月(2022.5.0)发行说明中所述，已删除复制代理管理员屏幕的“分发”选项卡下的“添加树”选项。 应该使用管理发布或发布内容树工作流来复制具有内容树层次结构的包。

### [!DNL Cloud Manager]

新增功能：

* [!DNL Cloud Manager] 用户现在可以从 [!UICONTROL 欢迎] 卡。

* 上的弹出窗口 [恢复内容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=en) “环境详细信息”页面的选项卡现在显示一个方便易用的git命令列表，允许用户在本地查看更改。

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [充分利用企业工作流管理](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=en) | 视频 | 了解将工作流用于资产管理的好处，以及如何快速创建工作流。 | AEM — 体验工作流管理 |
| 2022 年 7 月 | [使用Adobe Experience Manager提供无头体验](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=en) | 视频 | 了解使用最新体验管理的无外设Experience Manager [!UICONTROL 内容片段] 增强功能和用于无头内容交付的新GraphQL API。 | Experience Manager [!DNL Sites] |
| 2022 年 7 月 | [在Adobe Experience Manager Assets中使元数据适合您的业务](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=en) | 视频 | 了解如何通过减少标记资产的工作量并提高资产的搜索能力，来充分利用AEM Assets中的元数据。 | Experience Manager [!DNL Assets] |
| 2022 年 7 月 | [iOS应用程序](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html) | 视频 | 示例应用程序是探索Adobe Experience Manager无头功能的绝佳方法。 此iOS应用程序演示了如何使用AEM查询内容 [!UICONTROL GraphQL API] 使用持久化查询。 | Experience Manager [!DNL Assets], [!DNL Sites] |
| 2022 年 7 月 | [Android™应用程序](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html) | 视频 | 此Android™应用程序演示了如何使用 [!UICONTROL GraphQL API] 的AEM。 | Experience Manager [!DNL Assets], [!DNL Sites] |
| 2022 年 7 月 | [为Adobe Experience Manager as a Cloud Service配置OSGi](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=en) | 视频 | 了解如何为AEM CS配置OSGI。 例如，了解如何管理OSGi包，以及如何通过AEM代码项目中的配置文件来管理OSGi组件的配置设置。 | AEM as a Cloud Service |
| 2022 年 7 月 | [覆盖表单数据模型属性](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=en) | 视频 | 了解如何覆盖表单数据模型属性，以便更轻松地针对不同端点测试一个表单数据模型。 | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hans)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=en)
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
* [《Cloud Manager 用户指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=en)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![图标](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] 是部署在AEM上的应用程序。 这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。

详细了解 [[!DNL Experience Manager Guides]](https://www.adobe.com/cn/products/xml-documentation-for-experience-manager/features.html)。

### 其他资源

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) – Experience League 教程
* [[!DNL Experience Manager Guides] 学习和支持](https://helpx.adobe.com/cn/support/xml-documentation-for-experience-manager.html) – 产品文档

## ![图标](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source 2.4.x 发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 发行说明](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教程和文档 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [Adobe Commerce快速入门指南](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html) | 产品文档 | 本指南面向初次接触Adobe Commerce和Magento Open Source的商家和系统管理员。 从他们的角度获取该平台的概述，以及有关启用功能存储的基本功能的一些详细信息。 |
| 2022 年 7 月 | [Page Builder用户指南](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html) | 产品文档 | 了解页面生成器功能，包括用于构建基本内容组件的三步演练。 本指南面向管理员。 该指南假定您基本了解核心Adobe Commerce配置和功能。 |
| 2022 年 7 月 | [B2B for Adobe Commerce指南](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html) | 管理指南 | 获取有关安装和启用此模块的详细信息，包括其功能的配置和管理。 |
| 2022 年 7 月 | [Adobe Commerce B2B — 教程](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=en) | 视频（多个） | 了解 [!UICONTROL 公司] 页面。 您可以管理公司帐户，任何待批准的请求都会显示在列表顶部。 |
| 2022 年 7 月 | [使用质量修补工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html) | 视频 | 了解 [!UICONTROL 质量修补工具]，这是一个命令行工具，可为Adobe Commerce和Magento Open Source提供质量修补程序。 |
| 2022 年 7 月 | [站点范围分析工具功能板](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html) | 视频 | 了解站点范围的分析工具。 此功能是主动的自助工具和中央存储库，其中包含详细的系统分析和建议，可确保Adobe Commerce安装的安全性和可操作性。 |
| 2022 年 7 月 | [使用支付服务](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html) | 视频 | 了解如何使用 [!UICONTROL 支付服务] 为减少运营开销，增加收入。 |
| 2022 年 7 月 | [管理订单状态](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html) | 视频 | 了解如何检查订单状态及其详细信息，以及如何根据需要更改订单状态。 |
| 2022 年 7 月 | [营销工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=en) | 视频（多个） | 了解有关创建目录价格规则、购物车价格规则、管理相关产品规则、实时搜索等的信息。 |
| 2022 年 7 月 | [内容个性化创新，可带来业务价值](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=en) | 视频 | 查看技能培养演示并了解Adobe内容解决方案中的最新创新，这些创新可帮助您实现内容创作大众化、实现全渠道交付并扩展个性化。 |
| 2022 年 7 月 | [目录管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html) | 视频 | 了解Adobe Commerce中的目录管理。 创建类别、管理类别中的产品、管理库存等。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新日期：**2022 年 6 月 30 日**

* 有关预发行信息，请参阅 [Adobe Target 预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [Adobe Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

### Adobe Target 的新课程和教程 {#tutorials-target}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [创建受众](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html) | 视频 | 了解如何在中创建和保存自定义受众 [!DNL Target] 以在您的活动中使用。 |
| 2022 年 7 月 | [使用Adobe Target进行个性化和自动化](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=en) | 视频 | 了解使用自动化和优化Adobe Target功能的核心概念 [!UICONTROL 自动定位] 和 [!UICONTROL 自动个性化]. |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

* [Campaign v7.3版本](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans)
* [控制面板6月版](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)
* [教程和课程](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) Experience League

### 新的 [!DNL Campaign] 教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [适用于混合托管模型的控制面板](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html) | 视频 | 了解如何为 Adobe Campaign 混合托管模型启用控制面板、访问控制面板以及解锁关键功能。 | 控制面板 |
| 2022 年 7 月 | [监视通入和延迟](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=zh-Hans) | 视频 | 了解如何监控营销活动实例的投放方式和事务型消息延迟。 | 控制面板 |
| 2022 年 7 月 | [监控工作流以优化资源使用](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=zh-Hans) | 视频 | 了解如何监控工作流的临时存储使用情况以及在何处配置工作流设置以避免实例上出现数据库或工作流问题。 | 控制面板 |
| 2022 年 7 月 | [在Adobe Campaign Classic中开发和自定义数据模型](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en) | 视频（技能培养事件） | 与我们的Campaign培训师一起参加此会议，了解如何在Campaign Classic的数据模型内开发数据模式。 | Campaign Classic v7 |
| 2022 年 7 月 | [可交付性最佳实践和策略，以促进成果](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html) | 视频 | 了解如何最大限度地减少策划和制作电子邮件活动所花费的无数小时。 | Campaign Classicv7 |
| 2022 年 7 月 | [利用Adobe Campaign Classic提高跨渠道营销水平](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en) | 视频 | 观看此深入网络研讨会，重点讨论针对Adobe Campaign Classic客户的工作流、自动化、个性化和测量。 | Campaign Classicv7 |
| 2022 年 7 月 | [从专业人员那里节省时间的提示！](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en) | 视频 | 借助Adobe Campaign专业版的提示和技巧，开始新的一年！ 了解如何通过创建和启动营销活动来提高效率，以及如何提供更有意义、量身定制的跨渠道体验。 | Campaign Classicv7 |
| 2022 年 7 月 | [Adobe Campaign与营销生态系统集成](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en) | 视频 | 了解Adobe Campaign与营销生态系统的集成。 跨渠道营销解决方案(如Adobe Campaign)不应与其他技术或团队孤立无援。 不要让不同的系统妨碍客户的完全了解并破坏跨渠道策略。 | Campaign Classicv7 |
| 2022 年 7 月 | [Adobe Campaign Standard客户焦点 — Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en) | 视频 | 听取Microsoft®的营销团队的意见，以分享他们如何使用Adobe Campaign Standard、其架构和指导原则以及最佳实践。 | Campaign Standard |
| 2022 年 7 月 | [Adobe Campaign客户焦点 — 中心合作伙伴](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en) | 视频 | 聆听Adobe Campaign客户分享他们克服挑战的方式、适应新常态、提高营销活动管理效率，并通过Adobe Campaign创造有意义的价值。 | Campaign Classicv7 |
| 2022 年 7 月 | [Adobe Campaign Classic V7与V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en) | 视频 | 了解最新的产品更新，并了解我们的产品经理对V7和V8之间的差异。 | Campaign Classicv7、Campaign v8 |
| 2022 年 7 月 | [Keynote — 跨B2B和B2C的客户历程趋势和创新](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en) | 视频 | 了解跨B2B和B2C的客户历程管理的最新趋势。 了解关键历程应用程序以及更广泛的Adobe Experience Cloud和平台中的最新创新。 | Marketo、Campaign Classicv7、Campaign v8 |
| 2022 年 7 月 | [Adobe Campaign Standard的主要提示和技巧](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en) | 视频 | 插入您的Adobe Campaign Standard实例，并了解有关定位、个性化和营销疲劳度的最佳实践，以便更好地使用ACS。 | Campaign Standard |
| 2022 年 7 月 | [支持跨渠道营销所需的团队、技能和组织设计](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html) | 视频 | 了解如何有能力随时随地参与您的活动。 了解拥有支持规划、执行和衡量的营销组织的重要性。 | Campaign Classicv7、促销活动v8、Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Campaign 帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=zh-Hans) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，只需单个应用程序即可为数百万客户管理预定的全渠道营销活动和一对一互动时刻，并用智能决策和见解优化了整个历程。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)。

### Journey Optimizer 的新教程和课程 {#tutorials-ajo}

发布的关于Adobe Journey Optimizer的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [配置消息频率规则](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html) | 视频 | 了解如何创建、激活、测试和报告频率规则。了解如何确定将为消息继承哪些频率规则。 |
| 2022 年 7 月 | [配置、创建和投放短信消息](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html) | 视频 | 了解如何配置、创作短信消息，并将其包含在客户历程中。 |
| 2022 年 7 月 | [短信的入站关键词支持](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html) | 视频 | 了解针对短信的原生入站关键词支持（开始、停止、不停止）的工作方式。 |

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

发布的关于AdobeMarketo的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [使用Marketo Engage和Adobe Experience Cloud的B2B体验](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=en) | 视频 | 了解Marketo Engage与Adobe Experience Cloud应用程序之间的集成，以及将解决哪些棘手问题。 | Marketo Engage |
| 2022 年 7 月 | [更好地结合在一起 — Adobe Marketo Engage和Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=en) | 视频 | 了解如何使用Marketo Engage和RT-CDP（B2B版本）编排B2B活动，以及哪些是最常用的用例和优势得到释放。 | Marketo、Real-time Customer Data Platform |

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

上次更新时间： **2022年7月14日**

| 功能 | 描述 |
| ------- | ----------- |
| 自定义报表 | (5月31日发布；测试版功能)Advertising Cloud DSP现在可以摄取由在客户数据平台(CDP)中构建的经过验证的信号组成的第一方区段。 |
| [!UICONTROL 内容库] | （6月29日发布）新 [!UICONTROL 库存] > [!UICONTROL 交易] 视图包含与 [!UICONTROL 促销活动] 视图，包括其他过滤器、列自定义以及用于保存自定义视图、列排序和数据可视化（图表）视图的选项。 通过单击交易名称后面的省略号(...)，可以在每行中打开一个命令菜单。 |
| [!UICONTROL 清单检查器] | （6月29日发布） [!UICONTROL 库存] 选项卡 [!UICONTROL 检查员] 现在包括可自定义的数据可视化图表和扩展的性能量度，例如 [!UICONTROL 可视性比率], [!UICONTROL 点击次数]和 [!UICONTROL 昨天的CPM]. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新时间： **2022年7月14日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 见解] | （6月11日发布）“展示共享丢失”分析现已再次作为测试版功能提供。 |
| [!DNL Advanced Campaign Management] | （6月20日）([!DNL Google Ads] 和 [!DNL Microsoft Advertising] 促销活动)现在，您可以使用特定于搜索引擎的广告模板，根据库存内容，从 [!UICONTROL 促销活动] > [!UICONTROL 高级(ACM)]. |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [使用审批者角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=en) | 视频（更新） | 了解如何通过批准流程发送文档。 | Adobe Sign |
| 2022 年 7 月 | [设置Web窗体](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html) | 视频（更新） | 了解如何创建可直接在您的网站上以电子方式签名的文档。 | Adobe Sign |
| 2022 年 7 月 | [使用委托人角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | 视频 （已更新） | 描述 | Adobe Sign |
| 2022 年 7 月 | [以电子方式签署文档](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=en) | 视频（更新） | 了解使用Acrobat Sign签署发送给您的文档是多么简单。 | Adobe Sign |
| 2022 年 7 月 | [为Acrobat Sign管理员启动和运行](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=en) | 视频（更新） | 了解管理员应重点关注的七个关键方面，以便在Acrobat Sign中快速启动和运行。 | Adobe Sign |
| 2022 年 7 月 | [Outlook中的Send for Signature](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=en#) | 视频（更新） | 了解如何通过在Microsoft® Outlook中直接发送文档以进行签名来简化文档工作流。 | Adobe Sign |
| 2022 年 7 月 | [填写和登录Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=en) | 视频（更新） | 了解如何通过直接在Microsoft Outlook中填写和签署表单来简化文档工作流程。 | Adobe Sign |
| 2022 年 7 月 | [创建和管理组](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=en) | 视频（更新） | 了解如何创建群组、将用户添加到群组以及编辑群组设置。 | Adobe Sign |
| 2022 年 7 月 | [将签名委派给其他人](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=en) | 视频（更新） | 了解如何将文档的签名委派给其他人。 | Adobe Sign |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Adobe Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。

## ![图标](/assets/experience-league.png) 客户数据管理 — 意见 {#voices}

[客户数据管理意见](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=zh-Hans)是您作为客户数据管理技术和营销实践领导者和专家的目标。本教程集是供您听取同行意见、获得灵感并了解营销技术发展的一站式服务。无需注册，只需点击即可观看。

## ![图标](/assets/experience-league.png) 数字体验 Blueprint {#blueprints}

[数字体验 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hans) 是可重复的实施，让您可以满足战略需求和解决已确定的业务问题。每个 Blueprint 都提供了一系列构件，这些构件说明了高价值业务问题、体系结构、实施步骤、技术注意事项以及指向相关文档的链接。

[回到顶部](#events)
