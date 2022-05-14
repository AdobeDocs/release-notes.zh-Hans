---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: May 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: c3e59ee55c248878950ccf28a97b778dac69e31a
workflow-type: tm+mt
source-wordcount: '4977'
ht-degree: 52%

---

# Adobe Experience Cloud 发行说明 - 2022 年 5 月

![横幅](assets/experience-cloud-banner-3.png)

作为体验创造者，您的成功之路始于 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)。在您需要时查找适合各种水平和角色的详尽的操作方法文档库、自学教程、操作方法视频和课程、同行的网络社区以及专家支持。

准备好开始了吗？[参加 5 分钟的测验并获胜](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)！

>[!NOTE]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)。经常回来查看 Experience League 的最新动态。

最新更新：**2022 年 5 月 14 日**

* [[!DNL Experience League] 活动](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud — 中央界面组件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
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

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，获取产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 活动 {#events}

Experience League 活动是您向 Adobe 产品专家学习、与之互动以及获得答案的绝佳方式！

更新日期：**2022 年 5 月 13 日**

| 活动 | 类型 | 描述 |
| -----------|---------- | ----|
| [Adobe Analytics — 体验创造者 — 技能交流](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) | 技能交流 | 与我们一起参加这个免费的、三小时的数字活动，该活动完全集中在Adobe Analytics。 通过对工作区最了解的专家和同行实时提问。<br>2022年5月18日@ 1:30pm-4:东部标准时间晚30点<br> [详细信息和注册](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) |
| [Adobe Campaign — 客户成功网络研讨会系列](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) | Peer2Peer:通过Adobe Campaign增强客户历程。 | 与Streamotion旗下Kayo、Wibald和Flash品牌的参与运营总监Anja Starun一起参加这次Peer2Peer的现场讨论。 直接向她了解她的团队为使用Adobe Campaign创建个性化客户旅程而实施的成功策略。 <br>**日期：** 5月26日东部标准时间下午3点 <br>[详细信息和注册](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) |
| [Journey Optimizer的推送通知 — 如何轻松配置移动应用程序以进行推送](https://www.youtube.com/watch?v=t36Xjhukmro) | Experience League LIVE | 了解Adobe Journey Optimizer推送通知的常见用例，并深入探讨如何配置由Adobe Experience Platform提供支持的推送应用程序的技术详细信息。 <br>**日期：** 2022年5月12日太平洋夏季时间上午9:30<br>[计划和过去的事件](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hans) |
| [Adobe Target社区](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940#M3096) | 问答喝咖啡休息时间 | 与Adobe Target产品团队的Brent Kostak和Drew Burns一起参加，他们可以回答您的Adobe Target关于共享受众、Real-Time CDP、第一方数据、端到端个性化工作流等的问题。<br>观看最近 [实时个性化网络研讨会](https://experienceleaguecommunities.adobe.com:443/t5/adobe-target-discussions/webinar-recording-4-28-22-real-time-personalization-with-adobe/td-p/449012) 并向专家提出关于 [断咖啡线](https://adobe.ly/3MyiDHa) 在Adobe Target社区！<br>**日期：** 2022年5月25日太平洋夏季时间早8点<br>[详细信息和注册](https://adobe.ly/3MyiDHa) |
| [Adobe [!DNL Developers Live]:商务](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | 按需视频 | _Adobe Developers Live:《2022年商业》_ 将具有不同背景和独特用途的开发人员和体验构建者整合在一起，以创造令人难以置信的端到端体验。 此为期一天的虚拟会议提供重要的商务和开源开发人员更新、技术会议、社区网络机会等。 |
| [Marketo技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | 按需视频 | 了解Marketo路线图的重要性以及如何避免规划不周。 在 [!DNL Marketo] 技能交流于2021年8月开始，现在Experience League。 |
| [Adobe Summit 2022](https://business.adobe.com/summit/adobe-summit.html) | 按需会议 | 向 Adobe 高管 Ryan Reynolds、Rosalind Brewer、Walgreens Boots Alliance， Inc. 首席执行官 John Donahoe 和 Gail J. McGovern（美国红十字会首席执行官）学习，他们分享客户体验如何成为我们数字经济的货币。<br>探索 Adobe Summit 2022 [按需会议](https://business.adobe.com/summit/2022/sessions.html)。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

有关最新发行信息，请参阅 Adobe 系统状态[发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hans#status)。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud — 中央界面组件和管理 {#ecloud}

Experience Cloud [中央 UI 组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)包括主页和永久性产品标题上可用的功能。这些功能包括用户配置文件设置、偏好设置和搜索。您还可以找到有关用户和产品管理、客户属性和 Experience Cloud Audiences 的帮助。

未更新。

**关于 [!DNL Experience Cloud Central UI Components] 和管理的更多帮助资源**

* Experience Cloud 中央 UI 组件的[发行说明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hans)
* Experience Cloud 的[用户和产品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)（管理）
* 放置服务[发行说明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)
* [人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hans)的产品文档
* [统一搜索对象和实体](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新发行信息和新文档：

计划发行日期： **2022年5月25日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### 新的 [!DNL Experience Platform] 教程和课程 {#tutorials-platform}

为发布的新视频教程、文章和课程 [!DNL Experience Platform].

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 5 月 | [区段匹配预共享分析](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-pre-share-insights.html) | 视频 | 当您决定与战略合作伙伴共享数据时，务必要了解客户的匹配方式，以便您了解数据共享的用处。 区段匹配允许您在共享任何数据之前查看与潜在数据合作伙伴的重叠。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [区段匹配连接设置](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-connection-setup.html?lang=en) | 视频 | 了解如何设置您与合作伙伴之间的连接，以便能够共享受众。 配置此区段匹配功能后，您将能够与数据合作伙伴来回共享数据。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [区段匹配数据管理](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-data-governance.html?lang=en) | 视频 | 了解如何在Real-Time CDP中设置和使用数据管理控制，以便限制可以与数据合作伙伴共享的数据集（以及使用这些数据集的区段）。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [区段匹配配置流程](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-configuration-flow.html?lang=en) | 视频 | 了解配置 [!UICONTROL 区段匹配] 数据共享的实例。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [连接到目标](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/connecting-to-destinations.html) | 视频 | 在从Real-time CDP向目标合作伙伴发送数据之前，您首先需要与这些合作伙伴建立连接。 此视频将逐步介绍该过程，通常由管理员执行。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [创建模式](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html) | 视频 | 此视频向您展示如何使用XDM Individual Profile类和各个字段组在Adobe Experience Platform中创建架构。 | Experience Platform |
| 2022 年 5 月 | [使用查询服务在表格中分析和可视化全渠道分析](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/analyze-and-visualize.html) | 视频 | 通过流失分析示例，了解如何将Adobe Experience Platform的查询服务与外部数据可视化工具结合使用。 | Experience Platform |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发行日期：**2022 年 5 月 18 日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### 新的 [!DNL Analytics] 教程和课程 {#tutorials-analytics}

发布的关于Adobe Analytics的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 5 月 | [开始使用Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/get-started-with-report-builder.html?lang=en) | 视频 | 了解使用Report Builder的基础知识，包括安装、登录和数据请求。 |
| 2022 年 5 月 | [导航新登陆页面](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/navigating-the-new-landing-page.html?lang=en) | 视频 | 了解如何充分利用新的Analytics登陆页面及其功能。 |
| 2022 年 5 月 | [“下一页”/“上一页”和“页面摘要”工作区面板和报表](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/next-previous-and-page-summary-workspace-panels-reports.html) | 视频 | 请参阅Analysis Workspace中的两种新面板类型 — “下一页/上一页”和“页面摘要”。 这些功能使工作区与一些更受欢迎的 [!UICONTROL Reports &amp; Analytics] 报表。 |
| 2022 年 5 月 | [Analysis Workspace登陆页面更新](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-landing-page-updates.html?lang=en) | 视频 | 了解新登陆页面的一些重大改进和添加内容。 我们收集了您的客户反馈，并尝试融入最突出的功能，例如列大小调整、新列类型、指向实时和机器人报表的链接以及许多其他功能。 |
| 2022 年 5 月 | [你问的对吗？](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/are-you-asking-the-right-questions.html) | 视频 | 了解与记录每个可能的元素相比，如何更有价值地识别和收集可操作数据点。 要有效地确定这些数据点，需要与利益相关方进行基本的规划和创造性讨论。 |
| 2022 年 5 月 | [使用 [!UICONTROL Report Builder] 高级提交选项以用于Power BI](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/use-report-builder-advanced-delivery-options-for-power-bi.html?lang=en) | 视频 | 了解如何设置高级计划以将Report Builder工作簿发送到Power BI。 |
| 2022 年 5 月 | [计划Report Builder请求](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/schedule-a-report-builder-request.html?lang=en) | 视频 | 了解如何为Report Builder工作簿设置基本计划。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

发行日期：**2022 年 5 月 18 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

## ![图标](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

上次更新： **2022年3月23日**

* [!DNL Streaming Media Analytics] [发行说明](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=zh-Hans)
* [!DNL Streaming Media Analytics] [产品文档和教程](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=zh-Hans)

<!-- ### New Customer Journey Analytics tutorials and courses {#tutorials-cja}

New video tutorials, articles, and courses published for Customer Journey Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2022|[Overview of configuring Data Views for Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en)|Video |Learn about configuring [!UICONTROL Data Views] for Customer Journey Analytics. [!UICONTROL Data Views] are similar to [!UICONTROL Virtual Report Suites] in Adobe Analytics. They allow you to configure the incoming data so that it can be most useful for your reporting and analysis. |
|April 2022|[Connections Details Experience in CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en)|Video |Learn how to check the status of your connection’s datasets and of the ingestion process.|
-->

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

### Experience Manager 产品版本

* **Experience Manager as a Cloud Service**

   观看 [2022年4月版本概述视频](https://video.tv.adobe.com/v/342612?quality=12) 有关2022.4.0（2022年4月）版本中添加的功能的摘要。 <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [2022年3月版本概述视频](https://video.tv.adobe.com/v/341465).
   * [2022年1月版概述视频](https://video.tv.adobe.com/v/340120).
   * [2021年12月版本概述视频](https://video.tv.adobe.com/v/339278).
   * [2021年10月版本概述视频](https://video.tv.adobe.com/v/338253).
   * [2021年9月版概述视频](https://video.tv.adobe.com/v/337381).

* **Experience Manager Sites as a Cloud Service**

   _新增功能_

   * 您现在可以将内容模型数据类型定义为 [可翻译](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/content-fragments/content-fragments-models.html?lang=en#properties) 在内容模型编辑器中使用复选框。 此外，Experience Manager翻译规则和配置会自动更新。

   _预发行渠道中的新增功能_

   * 将体验片段发布到预览 — 要预览访客能够看到的最终体验，您可以发布独立的体验片段以Experience Manageras a Cloud Service预览服务。


* **Experience Manager Assets as a Cloud Service**

   _新增功能_

   * 您现在可以 [排序标记](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=zh-Hans#use-tags-to-organize-assets) 根据标记名称、创建日期或修改日期，在标记选取器窗口中以升序或降序显示。

* **Experience Manager Forms as a Cloud Service**

   _新增功能_

   * **通信 — Formsas a Cloud ServiceSDK中的文档操作API支持** - [文档操作API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=zh-Hans) 帮助合并、重新排列和验证PDF文档。 现在，您可以借助Experience Manager Forms as a Cloud ServiceSDK在本地开发环境中使用通信 — 文档生成API。
   * **使用自定义XCI生成记录文档**  — 您现在可以 [使用自定义XCI文件设置记录文档的各种属性](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html?lang=en#use-a-custom-xci-file). 它用自定义更改覆盖主要 XCI。它可以更好地控制记录文档的生成，增加个性化和定制机会。
   * **在自适应表单中使用不可见的CAPTCHA**  — 您可以使用 [不可见的验证码，仅在存在可疑活动时显示验证码挑战](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/add-components-to-an-adaptive-form/captcha-adaptive-forms.html?lang=en). 如果未发现可疑活动，则不显示 CAPTCHA 质询。它有助于评估人工表单的完成情况，而无需使用复选框要求，减少自定义工作，并改善最终用户体验。
   * **表单数据模型配置**  — 您现在可以 [跨环境重复使用表单数据模型配置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/create-form-data-models.html?lang=en#runmode-specific-context-aware-config)，简化数据集成并降低IT成本。

* **Experience Manager Screens as a Cloud Service**

   _新增功能_

   * 批量渠道分配 — 用户可以在一个操作中选择多个渠道并同时分配到多个显示屏。

* **Experience Manager as a Cloud Service 基础**

   _**SDK 版本分析器**_

   Experience Manageras a Cloud Service的SDK生成分析器Maven插件会检测Maven项目中的问题，包括缺少依赖项的问题。 它使开发人员有机会在本地开发过程中发现问题，而且在使用Cloud Manager部署到云环境之前就已经很早。

   最近添加了一个新分析器：

   * content-packages-validation — 验证在部署期间安装的包的格式正确的内容语法和结构。
   Adobe建议您使用最新版本的分析器来更新maven项目，或者包含分析器（如果尚未更新）。 有关详细信息，请参阅 [ 文档](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=zh-Hans)。

* **Cloud Manager**

   _新增功能_

   * “环境”页面有一列，用于显示环境的Experience Manager版本。
   * 管道执行现在在执行屏幕上显示用户界面顶级错误。
   * 通过Cloud Manager用户界面重新执行生产部署步骤。
   * 重复使用生成图像以重新执行生产部署步骤。
   * 新的API可实现网络基础架构的自助删除。

* **Best Practices Analyzer**

   _新增功能_

   * 能够检测和报告不受支持的Asset Manager API的使用情况。 有四个API在Experience Manageras a Cloud Service中不再受支持。 客户应确保不再使用这些API，并且应使用新的资产上传方法。
   * 能够检测内容片段模板的使用情况。 不再支持在Experience Manageras a Cloud Service上创建新内容片段模板。 客户必须创建内容片段模型才能替换内容片段模板。
   * 能够检测存储库中资产元数据节点下具有100个以上子项的资产。 Adobe建议您删除不需要的元数据节点，以便在加载包含此类资产的文件夹时提高性能。
   * 能够检测并报告所使用的数据存储类型。
   * 更新了Experience Manager表单门户的模式。

### 社区

* **录制的Experience ManagerGEM网络研讨会**

   * [_集成AEM和CIF框架，打造丰富而沉浸式的电子商务体验_](https://adobe.ly/3jorz5r).

* Experience Manageras a Cloud Service [2022.4.0版本更新](https://adobe.ly/3LO0gOo).

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 5 月 | [AEM as a Cloud Service 2021.4.0 发行版更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2021/2021-4-0.html?lang=en) | 视频 | 听取AEM产品团队的意见，并了解最新版本的Adobe Experience Manager的功能和创新。 | AEM Asset Essentials、Sites、Screens、Forms和Cloud Foundation |
| 2022 年 5 月 | [Cloud 5 AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-introduction.html) | 视频 | 在5分钟或更短的短视频中，获取您所需的有关AEMas a Cloud Service的所有有用信息。 从第一季开始。 | AEM CS |
| 2022 年 5 月 | [获取集成的登录令牌](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-getting-login-token-integrations.html) | 视频 | 有关如何为Cloud Service集成获取登录令牌的详细指南以及执行此操作的一些用例。 | AEM CS |
| 2022 年 5 月 | [以轮播方式显示多个PDF文档](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/display-pdf-in-carousel.html?lang=en) | 视频 | 了解在提交表单之前，将多个PDF文档显示给表单填充器以供审阅的常见用例。 | AEM Forms |
| 2022 年 5 月 | [使用AEM Headless的图像](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/images.html) | 视频 | 了解如何使用图像等开发丰富、引人入胜的AEM Headless体验。 | AEM Headless |
| 2022 年 5 月 | [富文本，带AEM Headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/localized-content.html) | 视频 | 了解如何使用多行文本字段，该字段是允许作者创建富文本内容的内容类型。 | AEM Headless |
| 2022 年 5 月 | [专用出口 IP 地址](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html) | 视频 | 了解如何设置和使用专用出口 IP 地址，该地址允许来自 AEM 的出站连接源自专用 IP。 | AEM CS |
| 2022 年 5 月 | [部署代码](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/deploy-code.html) | 视频 | 了解如何在AEMas a Cloud Service中使用Cloud Manager管道将代码部署到生产环境。 | AEM CS， Cloud Manager |
| 2022 年 5 月 | [禁用后处理工作流执行](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/asset-microservices-configure-and-use.html#disable-post-processing-workflow-execution) | 文档 | 了解如何在不需要后处理时在自动启动工作流部分中创建空的工作流模型。 | AEM CS |
| 2022 年 5 月 | [水印](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/watermarks.html?lang=en) | 视频 | AEMas a Cloud Service水印功能允许使用任何PNG图像对自定义图像呈现进行加水印。 | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hans)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hans)
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
* [《Cloud Manager 用户指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 6.3 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans)
* [Experience Manager 6.2 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hans#previous-updates)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

## ![Icon](/assets/ec_appicon_24.png)Adobe Experience Manager 的 XML 文档 {#xml-doc}

Adobe Experience Manager 的 XML 文档是部署在 AEM 上的应用程序。这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。

详细了解 [AEM 的 XML 文档](https://www.adobe.com/cn/products/xml-documentation-for-experience-manager/features.html)。

### 其他资源

* [Adobe Experience Manager 的 XML 文档](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hans) — Experience League 上的教程
* [Adobe Experience Manager 学习和支持的 XML 文档](https://helpx.adobe.com/cn/support/xml-documentation-for-experience-manager.html) — 产品文档

## ![图标](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source 2.4.x 发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 发行说明](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新时间： **2022年5月9日**

* 有关预发行信息，请参阅 [Adobe Target 预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [Adobe Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

在 [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans), [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=zh-Hans)和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans) 发行说明。

### 营销活动帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，只需单个应用程序即可为数百万客户管理预定的全渠道营销活动和一对一互动时刻，并用智能决策和见解优化了整个历程。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### Journey Optimizer 教程和课程 {#tutorials-ajo}

最新 Journey Optimizer 教程：

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 5 月 | [创建决策规则](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-rules.html?lang=en) | 视频 | 了解如何为决策管理创建决策规则。规则或 _决策规则_ 是个性化选件的必需构建基块组件之一。 |
| 2022 年 5 月 | [创建投放位置](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-placements.html) | 视频 | 了解如何为决策管理创建投放位置。投放位置是优惠的构建基块组件之一。投放位置是内容类型和渠道的组合，如电子邮件中的图像或网站上的 HTML 代码。 |
| 2022 年 5 月 | [创建决策](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-decisions.html) | 视频 | 了解如何为决策管理创建决策。决策可将您的投放位置和收藏集合并为一个实体，以便做出可以为客户提供最相关优惠的决策。 |
| 2022 年 5 月 | [通过 Decisions Hub API 提供优惠](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/deliver-offers-with-the-decisions-api.html) | 视频 | 了解如何通过 Decisions Hub API 提供优惠。 |
| 2022 年 5 月 | [创建后备优惠](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-fallback-offers.html) | 视频 | 了解如何为决策管理创建后备优惠。备用选件是默认选件，会向不符合任何个性化选件资格的客户显示这些选件。 |
| 2022 年 5 月 | [创建集合](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-collections.html?lang=en) | 视频 | 了解如何为决策管理创建收藏集。收藏集用于管理逻辑组中的选件，并需要为决策管理活动构建收藏集 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新 [!DNL Journey Orchestration] 产品版本

有关最新的功能、改进和修复的详细信息，请参阅[[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration 文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

新发布的视频事件Experience League:

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 5 月 | [Marketo技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | 视频 | 首先了解您的Marketo路线图。 然后，了解将Marketo实例视为产品的重要性。 在此新发布的文章中，获取有关释放计划成员自定义字段、Marketo Engage提示和技巧等潜力的建议 [Marketo技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) 2021年8月开始Experience League。 |

{style=&quot;table-layout:auto&quot;}

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅 [!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

## ![图标](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)

<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

<!--
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新：**** 2022 年 14 月 12 日发布 5 月 5 日版

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 促销活动] | 以下测试版功能可供所有广告商使用：<ul><li>（[!DNL Microsoft® Advertising] 客户）对于您在 [!DNL Microsoft® Audience Network] 上现有的原生广告营销活动（包括 [!DNL Microsoft® Audience Ads]）支持同步、只读可见性和报表（包括浏览转化数据）。</li><li>([!DNL Google Ads] 和 [!DNL Microsoft® Advertising] 帐户)能够导入 [!DNL Google Ads] 营销活动和营销活动结构 [!DNL Microsoft® Advertising] 从 [!UICONTROL 搜索] > [!UICONTROL 工具] > [!UICONTROL 导入促销活动测试版].<br><br>导入营销活动后，您可以检查导入作业的状态，查看任何错误日志，以及编辑、暂停或删除导入计划。</li></ul> |
| [!UICONTROL 营销活动]<br><br>[!UICONTROL 项目组合] | ([!DNL Microsoft® Advertising] 促销活动)以下竞价策略现在可供所有用户使用：<ul><li>[!UICONTROL 目标展示共享]:您可以使用此策略配置营销活动，并（可选）设置目标展示共享、目标广告位置和每次点击的最大成本。 注意：混合项目组合中尚不支持此选项，并且无法将此选项添加到标准项目组合。</li><li>[!UICONTROL 最大化点击量]:您可以使用此策略配置营销活动，也可以选择设置每次点击的目标最大成本。 可在标准或混合项目组合中包括具有此策略的营销活动。要在混合项目组合中使用此策略，该项目组合的目标只能包括 [!DNL Adobe] 属性（指标），并且您必须启用将 Advertising Cloud Search 目标上传到 [!DNL Microsoft® Ads]。</li></ul> |
| 与 Adobe Analytics 集成 | （4月7日）在Advertising Cloud发送至 [!DNL Analytics]，数据 [!DNL Google Ads] 动态搜索广告仅可从2022年5月7日开始精确到广告组级别。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 5 月 | [共享帐户访问权限](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/share-account-access.html) | 视频 | 了解如何在其他用户的帐户中设置对交易的仅查看访问权限。 | [!DNL Acrobat Sign] |
| 2022 年 5 月 | [管理文档模板](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/edit-a-template.html?lang=en) | 视频 | 了解如何编辑或删除库中的模板。 | [!DNL Acrobat Sign] |
| 2022 年 5 月 | [在Microsoft®电源自动化中创建您的第一个流](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/create-workflow-power-automate.html?lang=en) | 文章 | 了解如何在Microsoft® Power中使用Adobe PDF Services连接器自动创建您的第一个流。 | Document Services |
| 2022 年 5 月 | [自动获取Microsoft®电源的凭据](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/getting-credentials-power-automate.html?lang=en) | 文章 | 了解如何获取凭据以开始使用或测试Adobe PDF服务。 根据您是试用用户还是现有客户，本教程将逐步介绍获取凭据的正确步骤。 | 文档服务 |

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
