---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: June 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 7ea7898bf65132824a5944dd9e936a1344d5a213
workflow-type: tm+mt
source-wordcount: '4696'
ht-degree: 54%

---

# Adobe Experience Cloud 发行说明 - 2022 年 6 月

![横幅](assets/experience-cloud-banner-3.png)

作为一个 Experience Maker，您的成功之路始于 [Experience League](https://experienceleague.adobe.com/?lang=en#home)。在您需要时查找适合各种水平和角色的详尽的操作方法文档库、自学教程、操作方法视频和课程、同行的网络社区以及专家支持。

>[!NOTE]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)。经常回来查看 Experience League 的最新动态。

最新更新日期：**2022 年 6 月 10 日**

* [[!DNL Experience League] 活动](#events)
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

Experience League 活动是您向 Adobe 产品专家学习、与之互动以及获得答案的绝佳方式！

更新日期：**2022 年 6 月 10 日**

| 活动 | 类型 | 描述 |
| -----------|---------- | ----|
| Adobe Campaign、Journey Optimizer- [跨渠道挑战：大规模个性化](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) | 虚拟事件 | 请听Director研究部451 Research的Sheryl Kingstone讲授如何跟上变化的步伐，将营销技术作为关键的推动因素，以及如何实现更多数据驱动。 我们还重温了2022年Adobe Summit期间共享的重要会议以及提示和技巧，在2022年，您可以从专家那里了解到如何跨渠道大规模推动个性化。<br>**日期：** 6月14日 —  [详细信息和注册](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) |
| [正在揭秘 — Cloud Manager 2022](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) | AEM Gems — 虚拟事件 | 探索去年发布的新功能、幕后开发的最新信息，并展望2022年的剩余时间。 <br>**日期：** 6月15日 — [详细信息和注册](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) |
| [如何构建信任并传达影响以扩展您的数字战略](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) | 大师圆桌会议 | 与我们一起进行独家而亲密的对话，我们将在此讨论如何有效地传达您的数字战略的影响。 <br>**日期：** 6月21日 —  [详细信息和注册](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) |
| [Experience Makers Live](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) | 视频和虚拟事件 | 2022年Adobe体验制作者奖将为改变游戏规则的客户体验和令人瞠目结舌的数字转型而庆祝。 <br>参加美洲、日本、印度、澳大利亚和新西兰的盛会 **6月22日**<br>&#x200B;参加欧洲、中东和非洲的盛会 **6月23日** <br> [详细信息和注册事宜](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) |
| [咨询专家 — Real-Time CDP连接](https://www.youtube.com/watch?v=hVwtxDYvzw4) | Experience League LIVE | 我们最喜爱的Adobe专家将对Adobe的Real-Time CDP连接产品进行广泛的了解，客户可以在该产品中使用服务器端标签管理系统将事件转发到任何目标。<br>**日期：** 6月23日上午9点- [详细信息](https://www.youtube.com/watch?v=hVwtxDYvzw4) |
| [咨询专家：Web SDK 基础](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-05-26-22.html) | Experience League实时 | 了解和利用数据收集最佳实践。<br>[计划和过去的活动](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hans) |
| [技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/overview.html?lang=en) | 录制的会议 | 访问技能交流活动，观看我们全球系列的虚拟客户学习活动，重点是深入挖掘Adobe Experience Cloud解决方案。 |
| [Experience Maker 政府版论坛](https://adobegovforum.govexec.com/agenda/) | 点播视频 | 第 13 届年度 AEMGF 已于 5 月 10 日成功举行，参会方式为线上和线下相结合。全体和分组会议的主题为&#x200B;_以人为本的数字体验_。主要会议主题包括&#x200B;_缉逃者：我们如何缉捕 Pablo Escobar_、_CX 的未来_&#x200B;以及&#x200B;_创造力和现代工作场所的黄金时代_。 |
| [Adobe [!DNL Developers Live]：Commerce](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=cn) | 点播视频 | _Adobe Developers Live：Commerce 2022_ 汇聚背景各异但目标一致的开发和体验构建人员，共同创造超乎想象的端到端体验。该为期一天的虚拟会议将提供重要的 Commerce 和开放源开发人员更新、技术会议、社区社交机会等。 |
| [Marketo 技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=cn) | 点播视频 | 了解 Marketo 路线图的重要性以及如何避免规划不当。从 2021 年 8 月开始，在[!DNL Marketo] 技能交流中了解如何解锁项目会员自定义字段、Marketo Engage 技巧和窍门等功能的潜力（现在可在 Experience League 上获得）。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

有关最新发行信息，请参阅 Adobe 系统状态[发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hans#status)。

## ![图标](/assets/ec_appicon_24.png) Experience Cloud — 中央界面组件和管理 {#ecloud}

Experience Cloud [中央 UI 组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hans)包括主页和永久性产品标题上可用的功能。这些功能包括用户配置文件设置、偏好设置和搜索。您还可以找到有关用户和产品管理、客户属性和 Experience Cloud Audiences 的帮助。

计划发行版本： **2022年7月11日**

| 功能 | 描述 |
| ------- | ------- |
| 统一主页 — 快速访问小组件 | **更快导航：** 您现在可以进一步个性化您的家庭体验，并决定哪些应用程序触手可及。 使用新的固定功能选择哪些应用程序显示在您的 [!UICONTROL 快速访问]. <br>**通过智能固定保持信息灵活：** 现在，您的新应用程序更易于查找。 新分配的应用程序将显示 _新建_ 徽章和自动固定到 [!UICONTROL 快速访问]. |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理的更多帮助资源**

* Experience Cloud 中央 UI 组件的[发行说明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hans)
* Experience Cloud 的[用户和产品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)（管理）
* 放置服务[发行说明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)
* [人员 — 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hans)的产品文档
* [统一搜索对象和实体](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新发行信息和新文档：

计划发行版本： **2022年6月22日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### 新的 [!DNL Experience Platform] 教程和课程 {#tutorials-platform}

针对 [!DNL Experience Platform] 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 6 月 | [管理员Real-time CDP快速入门](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2022.1.rtcdp) | 课程 | 了解启动并运行所需的管理员任务 [!DNL Real-time Customer Data Platform]. 了解用户管理以及如何与其他合作伙伴和系统建立连接。 | [!DNL Real-time CDP] |
| 2022 年 6 月 | [监控区段激活成功与否](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-the-success-of-segment-activation.html?lang=en) | 视频 | 了解监控区段流向目标的两种主要方法。 在向激活合作伙伴发送区段用户档案时，务必要查看有关此数据传输成功的信息，特别是要了解这些信息，以便您能够解决问题。 | [!DNL Real-time CDP] |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

下一版本： **2022年6月15日**

最新更新日期：**2022 年 6 月 8 日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### 新的 [!DNL Analytics] 教程和课程 {#tutorials-analytics}

针对 Adobe Analytics 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [导出Adobe Analytics数据并实现其大众化](https://experienceleague.adobe.com/docs/courses/using/analytics-a-1-2022-1-democratizing.html?lang=en) | 课程 | 了解Adobe Analytics中支持您实现数字数据民主化的功能。 数据民主化是消除瓶颈并让您组织中的关键人员能够轻松处理数据以便他们能够根据数据做出决策的过程。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最新更新日期：**2022 年 5 月 19 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

### 新的Customer Journey Analytics教程和课程 {#tutorials-cja}

发布的关于CJA的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [数据视图中的绑定维度](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/binding-dimensions-in-data-views.html?lang=en) | 视频 | 了解捆绑维度。 此功能允许您获取一个维度并将其连接到另一个维度，以便更细化持久性分配。 |
| 2022 年 6 月 | [Customer Journey Analytics 登陆页面](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/cja-basics/customer-journey-analytics-landing-page.html) | 视频 | Customer Journey Analytics 的登陆页面提供项目和移动记分卡的默认视图以及学习分区，帮助您更有效地开始使用。 |
| 2022 年 6 月 | [摄取、映射和转换 Adobe Analytics 数据](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-prep/ingest-map-and-transform-adobe-analytics-data.html) | 视频 | 了解如何将数据准备功能用于 [!DNL Analytics] 数据，包括数据操作功能。 例如，您可以将Analytics变量映射到新的自定义字段，并执行转换和计算。 |
| 2022 年 6 月 | [配置子字符串组件设置](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configure-substring-component-settings.html) | 视频 | 了解如何使用字符串处理方法在Customer Journey Analytics报表中获取所需的维度值部分。 应用后，数据转换会立即进行逆向转换。 |
| 2022 年 6 月 | [创建移动记分卡](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html) | 视频 | 了解如何为执行用户配置和显示功能板。 |
| 2022 年 6 月 | [连接创建和编辑体验](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/cja-connections-creation-and-edit-experience.html) | 视频 | 了解如何启用滚动数据保留窗口、启用并请求基于事件时间戳的回填数据，以及按数据集导入现有数据。 |

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

### Experience Manager 产品更新

* **Experience Manager as a Cloud Service**

   观看 [2022年5月版概述视频](https://video.tv.adobe.com/v/343321/?quality=12) 有关2022.5.0（2022年5月）版本中添加的功能的摘要。 <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [2022年4月版本概述视频](https://video.tv.adobe.com/v/342612?quality=12)
   * [2022 年 3 月发布概述视频](https://video.tv.adobe.com/v/341465)。
   * [2022 年 1 月发布概述视频](https://video.tv.adobe.com/v/340120)。
   * [2021 年 12 月发布概述视频](https://video.tv.adobe.com/v/339278)。
   * [2021 年 10 月发布概述视频](https://video.tv.adobe.com/v/338253)。
   * [2021 年 9 月发布概述视频](https://video.tv.adobe.com/v/337381)。

* **Experience Manager Sites as a Cloud Service**

   _预发布频道中的新增功能_

   * 各种GraphQL功能。
   * A [新控制台](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/content-fragments/content-fragment-console.html?lang=en) 针对内容片段的无头使用进行了优化。

* **Experience Manager Assets as a Cloud Service**

   _新增功能_

   * [Dynamic Media Smart Imaging现在支持AVIF文件格式](https://medium.com/adobetech/one-solution-fits-all-smart-imaging-with-aem-dynamic-media-be690b62df9f)  — 进一步改进Google Core Web Vital（最大内容绘画），AVIF提供比WebP大20%的额外尺寸缩减。 与JPEG相比，AVIF的平均大小缩减率高达41%（在某些图像中甚至高达76%）。
   * Experience Manager Assets Brand Portal现在每12小时运行一次自动作业，以删除已发布到Experience Manager的所有Brand Portal资产。 因此，您无需手动删除Contribution文件夹中的资产，即可将文件夹大小保持在阈值限制以下。 请参阅 [Experience Manager Assets·Brand Portal的新增功能](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/whats-new.html?lang=zh-Hans).

   _预发布频道中的新增功能_

   * Experience Manager Assets现在使用Adobe Sensei AI功能 [区分图像中的颜色，并在摄取时自动将差异作为标记应用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=en). 这些标记可根据图像颜色组合来增强搜索体验。 您可以配置在1到40之间标记为图像的颜色数量，以便以后可以根据这些颜色搜索图像。


* **Experience Manager Forms as a Cloud Service**

   _预发行渠道中的新增功能_

   * **将自适应Forms与Microsoft® Power自动集成**  — 您现在可以配置自适应表单，以在提交时运行Microsoft® Power Automate Cloud Flow。 配置的自适应表单会发送捕获的数据、附件和记录文档，以增强云流自动化以进行处理。 它可帮助您构建自定义数据捕获体验，同时利用Microsoft® Power Automate的强大功能围绕捕获的数据构建业务逻辑并自动执行客户工作流。
   * **创建自适应表单的向导**  — 您可以使用业务用户友好向导快速创作自适应Forms。 该向导提供了快速的选项卡导航，以便轻松选择预配置的模板、样式、字段和提交选项以创建自适应表单。

* **Experience Manager as a Cloud Service 基础**

   _新增功能_

   * 的 **[!UICONTROL 添加树]** 选项。 **[!UICONTROL 分发]** 选项卡（之前被宣布为已弃用）将于2022年6月20日或不久之后被删除。 而应使用以树层次结构表示的内容包进行复制 [管理发布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) 或 [发布内容树工作流](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow).
   * 将复制代理管理屏幕或复制API用于分发大于10 MB的内容包（具有属性的节点，不包括二进制文件）已弃用，将于2022年9月12日或之后不久实施该功能。 相反， [管理发布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) 或 [发布内容树工作流](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow) 必须用于复制这些大型内容包。 2022年7月，复制代理管理屏幕的 **[!UICONTROL 分发]** 选项卡。 如果您尝试复制这些大型内容包，则每当使用复制API复制这些大型内容包时，系统都会在Experience Manager错误日志中显示该文件包。 在9月，警告将被替换为错误。 Adobe建议您相应地调整流程。

   _预发布频道中的新增功能_

   * Experience Manageras a Cloud Service现已与统一Shell集成，以改进用户体验并将其与所有其他Experience Cloud应用程序相统一。 请参阅 [Experience Manageras a Cloud Service于统一Shell](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/overview/aem-cloud-service-on-unified-shell.html?lang=en) 以了解更多详细信息。


* **Experience Manageras a Cloud Service基础安全**

   * **弃用TLS 1.0和TLS 1.1**  — 从2022年6月30日开始，Experience Manageras a Cloud Service将需要与用户系统进行更加安全的网络通信和数据交换。 Experience Manager将仅使用TLS（传输层安全性）1.2协议。 TLS 1.0和1.1将被弃用。

      如果您继续使用TLS 1.0或TLS 1.1，则可能会失去对Experience Manageras a Cloud Service的访问权限。

### 社区

* 播放 [Experience Manageras a Cloud Service2022.5.0版本更新视频](https://adobe.ly/3NDPR8Y) 就是那些被释放的东西。 (10 分钟)
* GEM网络研讨会 —  _看着引擎盖下面：Cloud Manager 2022_
   * 2022 年 6 月 15 日，星期三
   * 太平洋时间08:00;中欧时间17时；20:30印度标准时间
   * [请在此处登记](https://adobe.ly/3t4jfgp).
   * [讨论主题](https://adobe.ly/3O0rdzd).

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 6 月 | [[!DNL Forms] 门户组件](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/forms-portal-components.html?lang=en) | 视频 | 了解如何启用 [!DNL AEM Forms] [!UICONTROL 门户] 组件在FormsCloud Service中。 | AEM Forms CS |
| 2022 年 6 月 | [集成AEM和CIF框架，打造丰富而沉浸式的电子商务体验](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aem-and-cif-framework-integration.html?lang=en) | 视频 | 了解如何使用Adobe的CIF框架来构建一致且内容丰富且沉浸式的商业体验。 | AEM和CIF框架 |
| 2022 年 6 月 | [SAML 2.0身份验证](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/authentication/saml-2-0.html) | 视频 | 了解如何设置最终用户(而非AEM作者)并对所选的SAML 2.0兼容IDP进行身份验证。 | AEM CS |
| 2022 年 6 月 | [上下文感知云配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/context-aware-fdm.html?lang=en) | 视频 | 了解如何在AEM Forms中在Cloud Service上定义上下文感知云配置。 | AEM Forms |

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

## ![图标](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] (以前称为 [!DNL XML Documentation for Experience Manager])是部署在AEM上的应用程序。 这是一个功能强大的企业级组件内容管理解决方案 (CCMS)，可在 Adobe Experience Manager 中启用原生 DITA 支持，使 AEM 能够处理基于 DITA 的内容创建和交付。

详细了解 [[!DNL Experience Manager Guides]](https://www.adobe.com/cn/products/xml-documentation-for-experience-manager/features.html).

### 其他资源

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hans)  — 关于Experience League的教程
* [[!DNL Experience Manager Guides] 学习和支持](https://helpx.adobe.com/cn/support/xml-documentation-for-experience-manager.html)  — 产品文档

## ![图标](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source 2.4.x 发行说明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 发行说明](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的Adobe Commerce教程和文档 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [MBI快速入门](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/getting-started.html?lang=en) | 视频 | 通过深入了解预配置的功能板和可用的自定义选项，直接从商务产品团队了解MBI的核心功能。 |
| 2022 年 6 月 | [在MBI中管理数据集](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/manage-data-sets.html?lang=en) | 视频 | 直接从Adobe Commerce产品团队了解MBIData warehouse管理器的一些强大功能。 超越基本报表构建，了解如何使用数据做更多工作。 |
| 2022 年 6 月 | [优化MBIData warehouse](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/optimize-data-warehouse.html?lang=en) | 视频 | 了解如何管理表和列同步设置，深入到表的架构中，以及创建要在报表中使用的计算列。 |
| 2022 年 6 月 | [MBI为假日准备](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/holiday-readiness.html?lang=en) | 视频 | 了解常见的季节性分析用例和方法，以使用关键MBI功能解决这些问题。 |
| 2022 年 6 月 | [MBI — 咨询专家](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/ask-expert.html?lang=en) | 视频 | 在这个分为两部分的网络研讨会中，了解客户对Business Intelligence的看法。 通过Business Intelligence、使用常用表表达式进行SQL优化等了解业务转型。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新时间： **2022年6月7日**

* 有关预发行信息，请参阅 [Adobe Target 预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [Adobe Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

### Adobe Target 的新课程和教程 {#tutorials-target}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [linktext](https://experienceleague.adobe.com/?recommended=Target-D-1-2021.1) | 课程 | 了解如何在您的网站上实施Adobe Target。 从管理主题（包括要求和用户权限）开始，本课程涵盖实施方法、注意事项和最佳实践。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

**最新发行版：**[Campaign Standard 发行版 22.2](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/e-release-notes.html)（2022 年 6 月）

通过 [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)、[Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=zh-Hans) 和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans) 发行说明了解有关最新功能、改进和修复的更多信息。

### 新的 [!DNL Campaign] 教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 6 月 | [配置投放模板](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/configure-a-delivery-template.html) | 视频 | 了解如何为临时投放配置模板。 | Campaign v8 |
| 2022 年 6 月 | [创建定期和连续的电子邮件投放](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/recurring-deliveries.html) | 视频 | 了解如何配置定期投放和调度程序活动。 | Campaign v8 |
| 2022 年 6 月 | [配置扩充活动](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/enrichment-activity.html) | 视频 | 了解如何根据投放日志信息配置扩充活动。 | Campaign v8 |
| 2022 年 6 月 | [短信简介](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/introduction-to-sms.html) | 视频 | 了解短信的含义、短信服务提供商的角色、Adobe Campaign如何连接到服务提供商。 了解哪些信息通过服务提供商传递以及哪些技术说明可用。 | Campaign v8,Campaign Standard,Campaign Classicv7 |
| 2022 年 6 月 | [为标准SMPP提供商设置短信帐户](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/set-up-account-for-standard-smpp-provider.html?lang=en) | 视频 | 了解如何使用Adobe Campaign设置SMPP帐户，如何分析短信投放结果，以及根据SMPP提供商的规范自定义SR处理。 | Campaign v8,Campaign Classicv7 |
| 2022 年 6 月 | [根据您的SMPP提供商调整SMS连接器](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/adapt-sms-connector-to-smpp-provider.html) | 视频 | 了解如何根据您的SMPP提供商调整SMS连接器。 优化短信设置以处理连接限制、设置最大吞吐量、发送窗口，以及使用TLS进行加密。 | Campaign v8,Campaign Classicv7,Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Campaign 帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，只需单个应用程序即可为数百万客户管理预定的全渠道营销活动和一对一互动时刻，并用智能决策和见解优化了整个历程。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

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

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅 [!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

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

上次更新时间： **2022年6月8日** 适用于5月31日版本

| 功能 | 描述 |
| ------- | ----------- |
| 自定义报表 | （测试版功能）Advertising Cloud DSP现在可以摄取由在客户数据平台(CDP)中构建的经过验证的信号组成的第一方区段。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新日期：**** 2022 年 6 月 8 日，为 6 月 11 日发布的版本进行更新

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 分析] | “展示共享丢失”分析现已再次作为测试版功能提供。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

为 Adobe Document Cloud 发布的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [使用委派者角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | 视频 | 了解如何使用委派人角色将文档发送给中间人，中间人随后可以将文档路由以进行签名。 |
| 2022 年 6 月 | [配置事件和警报的通知](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/set-up-shared-events-and-alert.html?lang=en) | 视频 | 了解可在Acrobat Sign中配置的共享事件和警报设置。 警报是指在特定时间范围内未发生的操作，事件是指已发生的操作。 |
| 2022 年 6 月 | [高级帐户共享](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/advanced-account-sharing.html?lang=en) | 视频 | 了解如何设置高级帐户共享 — 允许管理员和用户委派其发送、修改和查看权限。 |

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
