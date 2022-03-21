---
title: 最新发行说明
description: 了解 [!DNL Experience Cloud] 产品和服务的最新发行说明、新增功能和新文档。查找有关  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 的新的帮助内容和教程。
doc-type: release notes
last-update: March 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 06f9e80782bf7c1f34feda8ab39e6832d76f0bc1
workflow-type: tm+mt
source-wordcount: '5696'
ht-degree: 49%

---

# Adobe Experience Cloud 发行说明 - 2022 年 3 月

![横幅](assets/experience-cloud-banner-3.png)

作为体验创造者，您的成功之路始于 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)。查找适用于所有级别和角色的庞大操作文档库、自学教程、操作视频和课程，还有同行网络社区以及需要时的专家支持。

准备好开始了吗？[参加 5 分钟的测验并获胜](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)！

>[!NOTE]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)。经常回来查看 Experience League 的最新动态。

最新更新日期：**2022 年 3 月 18 日**

* [[!DNL Experience League] 事件](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud — 中央界面组件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
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
* [数字体验 Blueprint - 教程](#blueprints)

需要帮助？请访问 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hans/#home)，获取产品和技术文档、Adobe 策划课程、视频教程、快速解答、社区洞察以及由讲师指导的培训。

## ![图标](/assets/experience-league.png) [!DNL Experience League] 事件 {#events}

Experience League活动是您学习、互动和从Adobe的产品专家那里获得答案的绝佳场所！

| 活动 | 类型 | 描述 |
| -----------|---------- | ----|
| [Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | 实时和按需视频 | 由Experience League团队制作的实时流播放节目。 利用这个机会，您可以与 Adobe 产品专家联系。学习可用于 Adobe Experience Cloud 应用程序的可操作性提示、技巧和策略。<br> [详细信息和过去事件](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [AEM GEMS](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) | Adobe Live网络研讨会 | 使用Adobe快速Bootstrap和部署单页应用程序(SPA) [!UICONTROL 应用程序生成器] 工作流和工具，无需具备Java™和Sling等传统Experience Manager技能。 借助Experience Manager无头，营销人员和开发人员可以各自拥有自己领域的专业知识 — 开发人员可以控制整个应用程序框架、样式和路由，同时营销人员可以确定内容及其显示方式。<br>**日期：** 3月23日星期三 —  [详细信息和注册](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) |
| [Adobe Analytics:用数据讲述有影响力的故事](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b%E2%80%A6%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) | Adobe Live网络研讨会 | 当数据讲述是艺术和科学的平衡时，数据讲述是很好的。 那么，为什么要过度设计？ Adobe Analytics冠军Amy Ard讨论了三个部分，旨在指导您在不削弱创造力的情况下讲述数据故事：<ul><li>确定机会或问题</li><li>通过数据说明</li><li>提供解决方案</li></ul>**日期：** 3月31日星期四 —  [详细信息和注册](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b...%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) |
| [体验创造者 — Adobe Workfront的技能交流](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Adobe Live网络研讨会 | 我们很高兴地宣布，4月13日将推出第一版Experience Maker -Adobe Workfront技能交流。 这个3小时免费数字学习活动完全以Workfront为中心，客户有机会在最了解工作管理的专家和同行的现场提问。 无论你是Workfront的新人，还是经验丰富的专家，我们都为所有人着想。 <br>**日期：** 4月13日星期三 —  [详细信息和注册](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=zh-Hans) | 视频 | [!DNL Developers Live] 展示了跨行业推动设计、内容创建工作流、文档服务和客户体验管理的最新技术进步和开发人员工具。查看主题演讲，了解 Analytics API、客户端数据层、Adobe I/O 开源项目等内容。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务中断和维护活动的详细信息、状态更新以及电子邮件通知。请访问 [status.adobe.com](https://status.adobe.com/) 查看。

有关最新发行信息，请参阅Adobe系统状态 [发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![图标](/assets/ec_appicon_24.png) Experience Cloud — 中央界面组件和管理 {#ecloud}

Experience Cloud [中央UI组件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) 包括主页和永久性产品标题上可用的功能。 这些功能包括用户配置文件设置、首选项和搜索。 您还可以找到有关用户和产品管理、客户属性和Experience Cloud受众的帮助。

| 功能 | 描述 |
| ------- |-------|
| 访问 _[!UICONTROL 收件人]_ 跨Experience Platform和Journey Optimizer使用 [!UICONTROL 统一搜索] | 您可以通过以下路径访问最近访问过的对象：从Experience Platform和Journey Optimizer的每个页面 [!UICONTROL 统一搜索] 字段。<br>请参阅 [统一搜索对象和实体](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en) 以了解更多信息。 |

{style=&quot;table-layout:auto&quot;}

**关于 [!DNL Experience Cloud Central UI Components] 和管理**&#x200B;的更多帮助资源

* Experience Cloud 中央 UI 组件的[发行说明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en)
* Experience Cloud 的[用户和产品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)（管理）
* 放置服务[发行说明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hans)
* [人员 - 客户属性和受众库](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)的产品文档
* [统一搜索对象和实体](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![图标](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform 和 [!UICONTROL Mobile SDK] 的最新发行信息和新文档：

发布日期：**2022 年 3 月 7 日**

* [Experience Platform 发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)

### Experience Platform 的新教程和课程 {#tutorials-platform}

为 Experience Platform 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [在移动设备应用程序中实施Adobe Experience Cloud教程](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/overview.html) | 课程 | 了解如何使用Adobe Experience Platform Mobile SDK在移动设备应用程序中实施Adobe Experience Cloud应用程序。 |
| 2022 年 3 月 | [生成第一方设备ID](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/generate-first-party-device-ids.html) | 视频 | 了解如何生成第一方设备ID及其工作方式。 |
| 2022 年 3 月 | [配置数据流](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/configure-datastreams.html) | 视频 | 了解如何为Web和Mobile SDK实施创建和配置数据流。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

请参阅 Adobe Experience Platform Mobile SDK 的[发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![图标](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

发布日期：**2022 年 3 月 23 日**

* Adobe Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)（**新位置**）
* Adobe Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.22.4**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### Analytics 的新教程和课程 {#tutorials-analytics}

为 Adobe Analytics 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [有关如何简化和减少用户培训时间的提示和技巧](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/simplify-training-users.html?lang=en) | 视频和文章 | 了解训练有素的Adobe Analytics组织对于您的业务有多么重要。 |
| 2022 年 3 月 | [创建赋权社区](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/empowered-community.html) | 视频和文章 | 了解增强Analytics社区的价值，以及如何创建和支持社区。 |
| 2022 年 3 月 | [创建营销渠道处理规则](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/create-marketing-channel-processing-rules.html?lang=en) | 视频 | 了解如何配置 [!UICONTROL 处理规则] 表示 [!UICONTROL 营销渠道]. |
| 2022 年 3 月 | [在报表包中设置营销渠道](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/set-up-marketing-channels.html) | 视频 | 在此视频中，了解如何在Analytics报表包中配置营销渠道报表。 |
| 2022 年 3 月 | [从Adobe Analytics过渡到Google Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/transitioning-from-other-platforms/transition-from-google-analytics.html?lang=en) | 视频 | 过渡到的全面指南 [!DNL Adobe Analytics] 从 [!DNL Google Analytics]. |
| 2022 年 3 月 | [配置层级变量](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-hierarchy-variables.html?lang=en) | 视频 | 了解如何以及何时为您的网站设置和配置层级变量。 此功能可用于显示网站上页面的分层视图以及每个节点的流量。 |
| 2022 年 3 月 | [在Analysis Workspace中组织和共享](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/curation-and-sharing-in-analysis-workspace.html?lang=en) | 视频 | 了解如何在Analysis Workspace中处理策划和共享项目。 |
| 2022 年 3 月 | [指向Analysis Workspace中项目的直接链接](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/direct-link-to-a-project.html?lang=en) | 视频 | 了解如何通过创建可将同事直接转到您的Analysis Workspace项目的缩短链接，更好地实现分析大众化。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

发布日期：**2022 年 3 月 23 日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)（**新位置**）
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

## ![图标](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager的修复和改进功能：

| 改进 | 描述 |
| -----------| ---------- |  
| 属于其他公司的目标数据源验证器 | Audience Manager对 [批量数据载入过程](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en). 为防止意外将文件和数据载入到其他合作伙伴拥有的目标数据源中，Audience Manager在合作伙伴ID(PID)和其他合作伙伴拥有的数据源(DPID)之间添加了映射要求。 <ul><li>另见__DPID_TARGET_DATA_OWNER_ 字段 [Amazon入站数据文件的S3名称和文件大小要求](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements).</li><li>Adobe内部顾问和客户关怀应阅读 [管理第二方数据的入门访问](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) 有关新映射的信息需要改进以及如何请求新映射</li><li>是 _not_ 请求现有数据共享关系的映射时需要。 此映射也 _not_ 将数据载入属于您PID的目标数据源时需要。</li></ul> |

{style=&quot;table-layout:auto&quot;}

有关自助资源，请参阅 Experience League 上的 [Audience Manager 文档和教程.](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hans)

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建议访问 [Experience Manager 版本更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans)页面以及时了解版本信息。

### Experience Manager 产品更新

* **Experience Manager6.5,Service Pack 12(6.5.12.0)**

   Adobe Experience Manager 6.5.12.0包含自2019年4月6.5版发布以来发布的新功能、客户请求的关键增强功能以及性能、稳定性和安全性改进。 Service Pack安装在Adobe Experience Manager 6.5上。

   请参阅 [发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=zh-Hans).

### Experience Manager 产品版本

* **Experience Manager as a Cloud Service**

   * [2022年1月版概述视频](https://video.tv.adobe.com/v/340120) 新增功能。
   * [](https://video.tv.adobe.com/v/339278)2021 年 12 月版新增功能概述视频。
   * [2021 年 10 月版新增功能概述视频](https://video.tv.adobe.com/v/338253)。
   * [2021 年 9 月版新增功能概述视频](https://video.tv.adobe.com/v/337381)。

   * **Experience Manager Assets as a Cloud Service**

      _Experience Manager Assets 的新增功能_

      * Dynamic Media - 您现在可以使用 Experience Manager - Dynamic Media 界面配置[常规设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=zh-Hans)和[发布设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=zh-Hans)，而不必使用 Dynamic Media Classic 桌面应用程序。
      * Dynamic Media 现在支持 MXF 视频的提取、预览、播放和发布。尚不支持 MXF 视频的注释和可购买视频。
      * 在配置远程 DAM 和 Sites 部署之间的连接后，远程 DAM 上的资源即可用于 Sites 部署。您现在可以对远程 DAM 资源或文件夹执行[更新、删除、重命名和移动操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=zh-Hans)。更新会在 Sites 部署中自动提供，但会有一些延迟。

      _Experience Manager Assets 预发行渠道中的新增功能_

      * Dynamic Media 现在提供了灵活性，让您可以在用户界面中[配置一个公司别名账户](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=zh-Hans)，以便开箱即用的 Dynamic Media URL 和查看器嵌入代码实时更新。该操作会对 SEO 产生积极影响，以反映对您的业务环境（如品牌再造）所做的更新。
      * 您现在可以使用 Experience Manager Assets 用户界面执行以下操作：

         * 配置对存储库中重复资源的检测。
         * 配置向图像添加数字水印。
      * 管理员现在可以为大型下载配置电子邮件服务。它让用户可以从 Experience Manager Assets 界面为[大型下载启用电子邮件通知](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=zh-Hans#enable-email-notifications-for-large-downloads)。下载过程完成后，用户会收到电子邮件通知，其中包含已存档 zip 文件夹的下载链接。
      * [管理发布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans)功能通过改进的用户界面得到增强。用户可以在所选目的地发布或取消发布内容，以及向 DAM 存储库中的发布列表[添加内容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans#add-content)。它们还可以[包括文件夹设置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans#include-folder-settings)以发布所选文件夹的内容并应用过滤器，以及[将发布安排](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hans#publish-assets-later)到以后的日期或时间。

      _错误修复_

      * 将资产从 Experience Manager 内部部署迁移到云服务时，没有原始演绎版的未处理资产将被发送到 Asset Compute 进行处理。
   * **Experience Manager Forms as a Cloud Service**

      _Forms 的新增功能_

      * **Experience Manager Forms as a Cloud Service - 通信** — [通信 API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=zh-Hans) 可帮助您组合模板和 XML 数据以生成各种格式的打印文档。该服务让您能够以同步和批处理模式生成文档。这些 API 帮助您创建可让您完成以下任务的应用程序：

         * 使用 XML 数据填充模板文件来生成文档。
         * 生成各种格式的表单，包括非交互式 PDF 打印流。
         * 从 XFA 表单 PDF 生成打印 PDF。
         * 通过将多组数据与源模板合并，批量生成 PDF、PostScript、PCL 和 ZPL 文档。
      * **使用 Communications API 创建的记录文档和 PDF 文档的自定义字体** — 您现在可以在使用 Communications API 生成的 PDF 文档中使用品牌批准的字体，以满足贵企业的要求。

      _Forms 预发行渠道中的新增功能_

      * [Assembler API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) — Assembler API 用于组合、重新排列、扩充和获取有关 PDF 文档的信息。
   * **Cloud Manager**

      _发行日期_

      Experience Manager as a Cloud Service 2022.01.0 中的 Cloud Manager 的发布日期是 2022 年 1 月 20 日。下一版本计划于2022年3月31日发布。

      _新增功能_

      * 当检测到在多个全栈管道执行中使用了](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=zh-Hans#build-artifact-reuse)相同的 git commit 时，Cloud Manager [可避免重建代码库。
      * 访问 Experience Manager 环境日志现在需要 **[!UICONTROL Deployment Manager]** 产品配置文件。没有此配置文件的用户会在用户界面中看到一个禁用的按钮。
      * 用户界面不允许为未启用站点作为解决方案的程序进行前端管道配置。
      * 生成 git 密码后，将会显示到期日期。








### 社区

* **Experience Manager GEM 网络研讨会：_使用 Experience Manager Headless 和 App Builder 更快地构建站点_**

   * 你错过了《Adobe Summit2022》的开场主旨吗？ Watch [让数字经济成为个人经济](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2022-opening-keynote-make-the-digital-economy/td-p/444612).
   * Adobe Summit2022 | [完成Experience Manager会话列表](https://adobe.ly/3rti6gF).
   * Experience ManagerGEM。 |网络研讨会 | 2022年3月23日星期三
      * 主题： *利用Experience Manager无头和应用程序生成器，更快地构建站点*
      * [请在此处登记](https://adobe.ly/3oCkEsh)
      * [对于Q&amp;A](https://adobe.ly/3LkSWdm)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 3 月 | [开始使用AEM Headless进行开发](https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=zh-Hans) | 课程 | 创建AEM无头登陆页面，以在ExL上将AEM无头上的所有内容汇总在一起。 | AEM Headless |
| 2022 年 3 月 | [在Adobe Experience Manager as a Cloud Service中创建您的第一个网站](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.1.aemcs.website) | 课程 | 使用预定义的网站模板快速在Experience Manager中生成新网站。 | AEM Sites |
| 2022 年 3 月 | [从提交的数据xml中提取节点](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/extract-xml-node.html?lang=en) | 视频 | 了解此自定义流程步骤，以通过从另一个XML文档中提取节点来创建XML文档。 如果要将提交的数据与XDP模板合并以生成PDF，请使用此流程。 | AEM Forms |
| 2022 年 3 月 | [将文档写入文件系统](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/write-payload-document.html?lang=en) | 视频 | 了解如何将工作流中生成的文档写入文件系统。 | AEM Forms |
| 2022 年 3 月 | [自定义函数](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/custom-functions-aem-forms.html?lang=en) | 视频 | AEM Forms 6.5引入了定义JavaScript函数的功能，这些函数可用于使用规则编辑器定义复杂的业务规则。 | AEM Forms |
| 2022 年 3 月 | [Workfront for Experience Manager增强型连接器专家系列](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html?lang=en) | 视频 | 与Adobe的Workfront和Experience Manager Assets专家一起观看这四个部分视频系列，共同演示和讨论Workfront中用于Experience Manager增强连接器的内部和外部。 | AEM Assets、Workfront |
| 2022 年 3 月 | [级联下拉列表](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/geonames-org.html?lang=en) | 视频 | 此教程介绍了使用级联下拉列表创建表单的示例资产。 | AEM Forms |
| 2022 年 3 月 | [初始设置和配置](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/setup.html?lang=en) | 视频 | 了解如何为Experience Manager增强的连接器设置和配置Workfront，从而解锁AEM Assets和Workfront的组合电源。 | AEM Assets、Workfront |
| 2022 年 3 月 | [Workfront自定义表单和元数据映射](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/custom-forms.html?lang=en) | 视频 | 了解如何配置Workfront和AEM Assets，以使用Workfront自定义表单和AEM元数据架构来管理和同步资产元数据。 | AEM Assets、Workfront |
| 2022 年 3 月 | [AEM标记、项目链接的文件夹和文件夹元数据](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/aem-tags-project-linked-folders-and-folder-metadata.html?lang=en) | 视频 | 了解如何通过Workfront数据推动AEM标记在资产上使用，设置并使用项目链接文件夹，以及将Workfront数据引入到AEM资产文件夹元数据架构。 | AEM Assets、Workfront |
| 2022 年 3 月 | [高级设置和工作流](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/advanced-settings-and-workflows.html?lang=en) | 视频 | 了解AEM增强型连接器的Workfront的高级设置，以及如何在AEM中配置高级工作流和启动器，以管理AEM和Workfront之间的数据同步。 | AEM Assets、Workfront |
| 2022 年 3 月 | [创建和配置Dynamics帐户](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/formscs-dynamics-crm/create-dynamics-account.html?lang=en) | 视频 | 了解在Azure Active Directory中注册Microsoft® Dynamics的步骤。 | AEM CS |
| 2022 年 3 月 | [公共链接共享](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/link-sharing.html) | 视频 | 了解Assets Essentials的共享链接如何允许用户与内部和外部利益相关方共享资产，同时最大限度地降低共享错误资产或信息的风险。 | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 发行信息

所有的 Experience Manager 发行说明均保留在以下页面：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hans)
* [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hans)
* [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hans)
* [Experience Manager 6.5 Service Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 发行说明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hans)
* [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hans)
* [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hans)
* [Experience Manager 桌面应用程序发行说明](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hans)
* [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hans)
* [Adobe Primetime 发行说明](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hans)
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hans)

### Experience Manager 的其他帮助资源

* [Experience Manager Sites as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=zh-Hans)
* [Cloud Manager 用户指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
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

### 的新教程 [!DNL XML Documentation for Adobe Experience Manager] {#tutorials-xml-doc}

发布的关于 [!DNL XML Documentation for Adobe Experience Manager].

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [使用XML文档生成输出](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2022.2.xmldocs) | 课程 | 了解如何使用 [!DNL XML Documentation for Adobe Experience Manager]. 了解可用于生成输出的各种功能，包括报表、基线、条件、疑难解答、批量发布和激活。 |

{style=&quot;table-layout:auto&quot;}

### 其他资源

* [Adobe Experience Manager 的 XML 文档](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hans) - Experience League 上的教程
* [Adobe Experience Manager 学习和支持的 XML 文档](https://helpx.adobe.com/cn/support/xml-documentation-for-experience-manager.html) - 产品文档

## ![图标](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

有关 Adobe Commerce 发行说明，请参阅以下链接：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [适用于 Adobe Commerce 的云套件](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新Adobe Commerce资源 {#new-commerce}

有关Adobe Commerce的新文档和教程，介绍Experience League。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [Payment Services 指南](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/guide-overview.html) | 指南 | 面向Adobe Commerce和Magento Open Source管理员的指南。 它包含有关支付服务安装和载入以及服务配置和管理的详细信息。 该指南假定您基本了解核心商务配置和功能。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新时间：**2022 年 2 月 1 日**

* 有关预发行信息，请参阅 [Adobe Target 预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [Adobe Target 发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

## ![图标](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 提供了一种直观、自动的方式，以通过在线和离线营销渠道来交付一对一的消息。您现在可以利用根据客户习惯和偏好确定的体验，来预测客户的需求。

### 最新营销活动产品版本

详细了解最新发布的功能、改进和修复：

* [Campaign Classic v7.2.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)

### [!DNL Campaign] 的新教程和课程 {#tutorials-campaign}

发布的关于Adobe Campaign的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| ------| ----- | -----| ------ | --- |
| 2022 年 3 月 | [与 Experience Manager 集成 - 概述](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/overview.html?lang=zh-Hans) | 视频 | 将 Adobe Campaign 与 Adobe Experience Manager 连接起来，以便在 Experience Manager 中管理电子邮件投放模板、资源和表单。 | AEM, Campaign v8 |
| 2022 年 3 月 | [为 Experience Manager 集成配置 Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/configure-campaign-for-aem-integration.html?lang=en) | 视频 | 了解如何设置Experience Manager与Campaign之间的集成，包括要查找的重要设置以及可能要避免的“难题”。 | AEM, Campaign v8 |
| 2022 年 3 月 | [批准 Experience Manager 页面并将其发布到 Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/approve-and-publish-aem-content-to-campaign.html?lang=en) | 视频 | 了解如何在 Experience Manager 中创建新闻稿，以及如何批准新闻稿并将其发布到 Campaign。 | AEM, Campaign v8 |
| 2022 年 3 月 | [在Campaign中同步和发送Experience Manager电子邮件投放](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/synchronize-and-send-an-aem-delivery-in-campaign.html?lang=en) | 视频 | 了解如何使用在Adobe Campaign中创建的新闻稿来测试和发送来自Experience Manager的电子邮件。 | AEM, Campaign v8 |
| 2022 年 3 月 | [与Adobe Target集成](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/connect/target-integration.html) | 视频 | 了解如何使用Adobe Target提供的动态内容对投放进行个性化。 | Adobe Target, Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### 营销活动帮助资源

* Adobe Campaign v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) — [《实施指南》](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hans)
* Adobe Campaign Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) — [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) — [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* Adobe Campaign 控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hans) - 有关 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hans)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hans) 的操作方法视频

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

借助 Journey Optimizer，您可以通过单个应用程序为数百万客户管理预定的全渠道营销活动和一对一互动时刻，整个历程都通过智能决策和见解得到了优化。

### 最新 Journey Optimizer 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### Journey Optimizer 教程和课程 {#tutorials-ajo}

最新 Journey Optimizer 教程：

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [使用和管理个性化库中保存的表达式](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/personalize-content/use-and-manage-saved-expressions-in-personalization-library.html?lang=en) | 视频 | 了解如何在消息中使用保存的个性化库项目，以及如何创建和管理个性化库项目。 |

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

凭借 Experience Platform，可以实时智能化预测每位客户的需求，从而实现跨体验渠道大规模编排客户历程。

### 最新 [!DNL Journey Orchestration] 产品版本

有关最新的功能、改进和修复的详细信息，请参阅[[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration 文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

## ![图标](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是一个全面的应用程序，适用于寻求通过积极参与复杂购买过程的每个阶段而改善客户体验的销售线索管理和 B2B 营销人员。

### 核心 Marketo Engage 更新

有关最新的发布计划信息和发行说明，请参阅[!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

### Marketo的新教程和课程 {#tutorials-marketo}

发布的关于AdobeMarketo的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [创建和管理个性化对话](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dialogue-management.html?lang=en) | 视频 | 了解如何创建和管理 _[!UICONTROL 对话框]_. 设计有针对性的个性化对话是为每个Web访客创建出色对话体验的关键。 |
| 2022 年 3 月 | [设置和安装聊天机器人](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/setup.html?lang=en) | 视频 | 该指南可帮助您将JavaScript聊天机器人安装到您的网站或登陆页面上，并自定义其外观以与您的品牌相匹配。 |
| 2022 年 3 月 | [使人员能够与您的销售团队预订会议](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/meeting-booking.html?lang=en) | 视频 | 使用 [!UICONTROL 动态聊天] 以加速与目标客户潜在客户销售的连接。 |
| 2022 年 3 月 | [激活Marketo集成 [!UICONTROL 动态聊天]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/marketo-integration.html?lang=en) | 视频 | [!UICONTROL 动态聊天] 本地集成到Marketo Engage中，允许您使用聊天机器人对话中的上下文来重新定位或对潜在客户进行评分。 |
| 2022 年 3 月 | [管理的用户 [!UICONTROL 动态聊天]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/user-management.html?lang=en) | 视频 | 管理 [!UICONTROL 动态聊天] 用户通过Adobe Admin Console。 |
| 2022 年 3 月 | [产品导览 [!UICONTROL 动态聊天]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/product-tour.html?lang=en) | 视频 | [!UICONTROL 动态聊天] 是为营销和销售而构建的新查特机器人解决方案。 它与Marketo Engage本地集成，使您能够将动态聊天用作跨渠道营销中的新渠道。 使用简单，设置方便。 |

## ![图标](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是一个统一的工作管理应用程序，可用于分享创意、创建内容、管理复杂的流程以及将工作做到尽善尽美。

请参阅[[!DNL Workfront] 版本](https://one.workfront.com/s/product-releases)页面，查看所有产品的最新信息综述。

## ![图标](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 的发行说明。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [ [!DNL Advertising Cloud Search] 中的新增功能](#adcloud-search)
* [ [!DNL Advertising Cloud] 的新教程](#tutorials-ad-cloud)

<!-- 
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

{style="table-layout:auto"}
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

<!--
{style="table-layout:auto"}
-->

### [!DNL Advertising Cloud Search] 中的新增功能 {#adcloud-search}

上次更新时间： **2022年3月14日** 对于3月12日版本

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 组合] | 默认情况下，混合优化在营销活动级别可用。 您现在可以选择在广告组级别启用混合优化，优化功能已为其设置 [!DNL Google] CPA或ROAS在广告组级别定位，以更精确地控制性能。<br>对于任何项目组合，在启动项目组合之前必须允许一段学习时间，以确保其具有足够的模型覆盖范围。 同样，如果将混合组合从促销活动级别更改为广告组级别的优化，则将组合设置为活动状态大约两周。 这可确保优化功能有时间了解所包含的广告组并生成目标。<br>为了支持广告组级别的优化，自定义模拟现在可以按广告组包含结果。 在启动具有广告组级别优化的混合项目组合之前，使用广告组级别的结果运行自定义模拟。 |
| [!UICONTROL 作品集] <br> [!UICONTROL 促销活动] | (测试版功能， [!DNL Microsoft® Advertising] 促销活动) — 您现在可以将搜索促销活动配置为使用 [!UICONTROL 最大化转化] 竞价策略，并可选择设置每次点击的最大成本。<br>如果您已经参与了用于其他自动竞价策略的混合优化测试版，则您可以自动访问 [!UICONTROL 最大化转化] 策略，并且您可以在 [!UICONTROL 最大化转化] 策略。 要在混合产品组合中使用此策略，您必须启用将Advertising Cloud Search目标上传到 [!DNL Microsoft® Ads]. 如果您尚未参与测试版并且想要加入，请联系您的 [!DNL Adobe] 客户经理。 |
| Campaign [!UICONTROL 受众]<br><br>Campaign [!UICONTROL 批量工作表] | ([!DNL Microsoft® Advertising] 营销活动) — 您现在可以使用 [!DNL Microsoft® Advertising] 受众，但作为促销活动级别目标或 [!UICONTROL adgroup] — 级别目标。 以前，只能将它们用作 [!UICONTROL adgroup] — 级别目标。 |
| Campaign [!UICONTROL 受众] | (测试版功能， [!DNL Microsoft® Advertising] 符合 [!UICONTROL 客户匹配])现在，您可以通过上传包含电子邮件地址的CSV文件来创建和管理符合客户要求的受众。 数据必须使用SHA-256算法进行哈希处理。 |

{style=&quot;table-layout:auto&quot;}

### Advertising Cloud 的新教程 {#tutorials-ad-cloud}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [如何创建标准显示版面](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/placement-create.html) | 视频 | 了解如何为Advertising Cloud DSP促销活动创建标准展示版面。 |

{style=&quot;table-layout:auto&quot;}

## ![图标](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

发布的关于Adobe Document Cloud的新教程和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [自定义命令和工具](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/custom.html?lang=en) | 视频 | 了解如何使用自定义命令和工具提高文档工作流的工作效率。 然后，与同事共享您的新命令和工具，以帮助提高组织效率。 |
| 2022 年 3 月 | [添加书签和超链接](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/bookmarks.html?lang=en) | 视频 | 了解如何添加书签和超链接，以更好地导航并与PDF文件交互。 |
| 2022 年 3 月 | [优化扫描的文档](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizescan.html) | 视频 | 无论您的文档来自摄像头还是扫描仪，了解如何在Acrobat中增强效果，以获得更好的PDF查看和搜索体验。 |
| 2022 年 3 月 | [将Word转换为包含表单字段的PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/wordform.html?lang=en) | 视频 | 在这个60秒的视频教程中，了解如何将Word文件和表单转换为PDF并自动构建表单字段。 |
| 2022 年 3 月 | [高级表单字段](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/advancedforms.html?lang=en) | 视频 | 在本动手实践教程中，了解如何设置计算、创建电子邮件提交按钮以及快速更新表单页面，而无需重建所有现有表单字段。 |
| 2022 年 3 月 | [在快照中创建更高效的PDF文件](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/optimize.html?lang=en) | 视频 | 在这个60秒的视频教程中，了解如何使用Optimize PDF工具显着减小PDF文件的大小。 |
| 2022 年 3 月 | [识别扫描的PDF文件中的文本](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/textrecognition.html?lang=en) | 视频 | 在此60秒视频教程中，了解如何转换扫描的PDF，以便在PDF中搜索文本。 |
| 2022 年 3 月 | [让Acrobat帮助您创建无障碍PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/accessible.html?lang=en) | 视频 | 在此60秒的视频教程中，了解如何检查PDF是否可访问。 |
| 2022 年 3 月 | [Export PDF到Word](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/exportwordphone.html?lang=en) | 视频 | 在此60秒的视频教程中，了解如何使用Acrobat移动应用程序将PDF文件转换为完全可编辑的Microsoft® Word文档。 |
| 2022 年 3 月 | [使用密码Protect您的PDF文件](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/protect.html?lang=en) | 视频 | 在此60秒视频教程中，了解如何保护PDF，以便需要密码才能打开或编辑PDF。 |

{style=&quot;table-layout:auto&quot;}

有关 Document Cloud 的帮助，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

## ![图标](/assets/creative-cloud-24.png) Adobe Creative Cloud 企业版 {#creative-cloud}

有关最新教程，请参阅 [Creative Cloud 企业版教程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hans)。

## ![图标](/assets/experience-league.png) 客户数据管理 — Voices {#voices}

[客户数据管理声音](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) 作为客户数据管理技术和营销实践的领导者和专家，您是您的目标。 本教程集合是您一站式服务，旨在听取同行的意见、获得灵感并了解MarTech的发展。 无需注册，单击并观看。

## ![图标](/assets/experience-league.png) 数字体验 Blueprint {#blueprints}

[数字体验 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hans) 是可重复的实施，让您可以满足战略需求和解决已确定的业务问题。每个 Blueprint 都提供了一系列构件，这些构件说明了高价值业务问题、体系结构、实施步骤、技术注意事项以及指向相关文档的链接。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [客户历程](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=zh-Hans) | 视频 | 客户历程能让品牌商通过电子邮件、短信和移动提醒等渠道，积极与客户互动和通信。 |
| 2022 年 2 月 | [Campaign v7 Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=zh-Hans) | 视频 | Adobe Campaign v7 是为传统营销渠道（如电子邮件和直邮）构建的营销工具。它提供强大的 ETL 和数据管理功能，以帮助制作和策划完美的活动。 |

{style=&quot;table-layout:auto&quot;}
