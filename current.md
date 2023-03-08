---
title: 最新发行说明
description: 阅读 Adobe [!DNL Experience Cloud]  产品和服务的最新发行说明。 了解即将举行的活动以及 Experience League 的新文档。 了解 [!DNL Experience Cloud] 应用程序的最新教程和课程。
doc-type: release notes
last-update: March 2023
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: d340d4d039920764e3853f0f86e9049cf4b4ccfd
workflow-type: tm+mt
source-wordcount: '4620'
ht-degree: 45%

---

# Experience Cloud 发行说明

![横幅](assets/release-notes-header.png)

## 2023 年 3 月

此页面可帮助您随时了解 Experience League 的产品发布信息、活动和学习机会。

>[!TIP]
>
>要收到有关此页面更新的每月电子邮件通知，请订阅 [Adobe 优先产品更新](https://www.adobe.com/subscription/priority-product-update.html)。经常回来查看 Adobe 的企业应用程序的最新动态。

**需要帮助？**

您的成功之路始于 [Experience League](https://experienceleague.adobe.com/?lang=en#home)。浏览我们庞大的自助[产品文档](https://experienceleague.adobe.com/docs/?lang=en)和指导[教程视频](https://experienceleague.adobe.com/docs/home-tutorials.html?lang=en)库。查找适合所有级别和角色的[课程](https://experienceleague.adobe.com/?lang=en#courses)，向我们由同行组成的在线[社区](https://experienceleaguecommunities.adobe.com/?profile.language=en)提问，并在您需要时获得专家[支持](https://experienceleague.adobe.com/?support-tab=home#support)。

## 产品版本更新和事件

最新更新日期：**2023 年 3 月 8 日**

* [[!DNL Experience League] 活动](#events)
* [[!DNL Adobe System Status]](#status)
* [[!DNL Experience Cloud] 界面和管理](#ecloud)
* [[!DNL Experience Platform]](#platform)
* [[!DNL Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)<!-- * [[!DNL Streaming Media Analytics]](#sma) -->
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Commerce]](#commerce)
* [[!DNL Target]](#target)
* [[!DNL Campaign]](#ac)
* [[!DNL Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [[!DNL Advertising]](#advertising)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)<!-- * [Digital Experience Blueprints - tutorials](#blueprints) -->

## ![图标](/assets/experience-league.png) [!DNL Experience League] 活动 {#events}

了解Experience League上发生了什么。 活动是您向Adobe产品专家学习、与之互动以及获得答案的绝佳方式！

+++即将举行的活动

* **[!DNL Analytics]** | _利用Adobe Analytics加快洞察时间_ | **3月9日太平洋时间上午8:00** |  [注册](https://adobeanalyticsvirtualanalyst2023.experienceleague.adobeevents.com/)

* **[!DNL Marketo Engage]** | _Marketo和Mochas：可投放性（第1部分）_ | **3月9日下午1:00 （东部时间）** | [注册](https://register.gotowebinar.com/register/6250682251177513567)

* **[!DNL Workfront]** | _连接：战略管理员聊天_ | **3月13日上午7:00 MT** | [注册](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,lgDkllfW8EatH2CVDH9nVQ,JWCg6TzBMUS5dX7i0qHSsA,CjE7t_FXgEaepx27DZn_7g?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Workfront]** | _System Admin Essentials：通过界面设计改善用户体验_ | **3月15日太平洋时间上午8:00** | [注册](https://event.on24.com/wcc/r/4123271/D486841B3D743479F12BAC0C583C10ED?partnerref=exl)

* **[!DNL Marketo Engage]** | _Marketo社区问答喝咖啡休息时间_ | **3月15日太平洋时间上午8:00** | [注册](https://mecommunityqacoffeebreak0315.splashthat.com/?utm_source=email&amp;utm_medium=Outbound&amp;utm_campaign=coffee_talk_ME&amp;utm_content=230315)

* **[!DNL Adobe Summit]** |_终极体验又回来了。 加入我们在维加斯的行列，培养技能，向世界顶级品牌学习，并获得灵感_ | **3月19日太平洋时间上午9:00** | [注册](https://summit.adobe.com/na/?promoid=2K4PC9V3&amp;mv=other)

参见 [Experience League事件](https://experienceleague.adobe.com/events/?lang=zh-Hans) 获取即将举行的活动和按需过去活动的完整计划。

+++

## ![图标](/assets/system-status.png) [!DNL Adobe System Status] {#status}

了解中的最新功能和更新 [!DNL Adobe System Status].

+++详细信息

[!DNL Adobe System Status] 提供有关Adobe产品及服务中断、中断和维护事件的详细信息、状态更新以及电子邮件通知。 请访问 [status.adobe.com](https://status.adobe.com/) 查看。

发行日期：**2023 年 2 月 15 日**

**新增功能**

* [!DNL Status] 添加了API支持，允许您直接调用Adobe的服务器以查询和查看事件，例如 [status.adobe.com](https://status.adobe.com/) UI。 您可以使用这些API集成到您的监视系统或功能板中，以查看Adobe状态的实时事件。 可以基于产品、产品、区域、环境（如果可用）、区域设置和事件类型对事件进行过滤。

| 功能 | 描述 |
| ------- | -------|
| Adobe状态API | <ul><li>Adobe状态API提供有关Adobe云产品及服务的宕机、中断和维护事件的详细信息和实时更新。</li><li>API需要在中设置 [Adobe Developer控制台](https://developer.adobe.com/console) 才能使用。 您的组织必须具有至少一个Adobe产品的权利才能访问AdobeAPI。 需要具有正确权限的开发人员控制台帐户。</li><li>请查看文档 [此处](https://developer.adobe.com/adobe-status/) 并遵循设置指南。</li><li>完成设置后，您可以使用 [API参考文档](https://developer.adobe.com/adobe-status/api/) 查看可用的API以及调用它们的签名。</li></ul> |

{style="table-layout:auto"}

+++

## ![图标](/assets/ec_appicon_24.png) Experience Cloud 界面和管理 {#ecloud}

查找对Experience Cloud界面主页、管理（产品和用户管理）、用户配置文件设置、首选项、搜索和Cookie的更新。

+++详细信息

_3月未更新。_

如需帮助，请参阅 [Experience Cloud界面和管理指南](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) (包括 [!UICONTROL 客户属性] 和 [!UICONTROL 受众])。

+++

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Experience Platform] {#platform}

查找的最新发行信息和新文档 [!DNL Experience Platform] 和 [!UICONTROL 移动SDK]. 查看有关Experience League的新教程和知识库文章。

+++详细信息

* [Experience Platform发行说明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hans)  — 计划发行版 —  **2032年3月29日**

### 新的 [!DNL Experience Platform] 教程和课程

为 Adobe Experience Platform 发布的新视频、教程或课程。

| 类型 | 产品功能 | 描述 | 应用程序 |
| -----------| ---------- |---------- |---------- |
| 2023 年 3 月 | [使用Adobe Analytics源连接器引入数据](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=zh-Hans) | 更新的视频 | 将数据从Adobe Analytics流式传输、映射和过滤到Adobe Experience Platform的Real-Time Customer Profile和Experience Data Lake。 | 数据引入 |

{style="table-layout:auto"}

### [!DNL Experience Platform] 支持知识库

[!DNL Experience Platform] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 2 月 | [中没有受众规模 [!DNL Microsoft Bing] AEP目标](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21544.html) | 新文章 | 了解原因 [!DNL Bing] 不显示发送到AEP的AEP区段的受众规模 [!DNL Bing] 目标。 |
| 2023 年 2 月 | [RTCDP许可证随附的环境数量（开发、暂存、生产）是多少？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21590.html) | 新文章 | 详细了解RTCDP许可证随附的环境和沙盒数量。 |
| 2023 年 2 月 | [是否 _应用转换_ 目标激活选项在经过哈希处理之前是否进行标准化（例如小写）？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21591.html) | 新文章 | 详细了解一般数据标准化及其解决方法。 |

{style="table-layout:auto"}

### [!DNL Mobile] SDK

已更新： **2022年11月11日**  — 请参阅 [发行说明和更改日志](https://aep-sdks.gitbook.io/docs/release-notes) 对于 [!DNL Adobe Experience Platform] [!DNL Mobile SDKs].

+++

## ![图标](/assets/analytics.png) [!DNL Analytics] {#analytics}

查找的最新版本信息 [!DNL Adobe Analytics] 和 [!DNL AppMeasurement]. 查看有关Experience League的新教程和课程。

+++详细信息

发布日期：**2023 年 3 月 8 日**

* [!DNL Analytics] [发行说明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hans)
* [!DNL Analytics] [产品文档和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hans)

### AppMeasurement {#appm}

发行版本：**2.23.0**

* [AppMeasurement for JavaScript 发行说明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hans)

### 新的 [!DNL Analytics] 教程和课程 {#tutorials-analytics}

针对 Adobe Analytics 发布的新视频教程、文章和课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [Analysis Workspace 中的富文本编辑器](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/rich-text-editor-in-analysis-workspace.html?lang=en) | 更新的视频 | 了解可让分析人员和营销人员对 Analysis Workspace 中的文本可视化图表（或描述）进行编辑的功能：粗体、斜体、标题、超链接等。 |

{style="table-layout:auto"}

+++

## ![图标](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

查找的最新版本信息 [!DNL Customer Journey Analytics]. 查看有关Experience League的新教程和课程。

+++详细信息

下一个版本： **2023年3月8日**

* Customer Journey Analytics [发行说明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hans)
* Customer Journey Analytics [产品文档和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hans)

### 新的 Customer Journey Analytics 教程和课程 {#tutorials-cja}

为 CJA 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [将 Customer Journey Analytics 连接到 Experience Platform 数据源](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=en) | 视频 | Customer Journey Analytics使用摄取到Adobe Experience Platform中的数据集。 在 Workspace 中开始数据分析之前需要创建连接。 |

{style="table-layout:auto"}

+++

<!-- ## ![Icon](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Latest release: **September 22, 2022**

* [!DNL Streaming Media Analytics] [release notes](https://experienceleague.adobe.com/docs/media-analytics/using/release-notes/release-notes.html?lang=en)
* [!DNL Streaming Media Analytics] [product documentation and tutorials](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Updates and new content for [!DNL Audience Manager]. -->

<!--### [!DNL Audience Manager] support knowledge base

New articles and updates to existing articles for [!DNL Adobe Audience Manager]

For self-help resources, see [Audience Manager documentation and tutorials](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) on Experience League.-->

## ![图标](/assets/aem.png) Adobe Experience Manager {#aem}

了解Experience Manager中的新增功能、修复和更新。 查看有关Experience League的最新教程和知识库文章。

+++详细信息

### [!DNL Experience Manager] 路线图和发布视频

Adobe 建议访问以下资源以随时了解发布信息：

* [Experience Manager 发布更新和路线图](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hans) - 了解 Experience Manager 版本路线图、先前版本更新和文档更新。
* [Experience Manager as a Cloud Service 版本更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/overview.html?lang=zh-Hans) - 观看当前版本和过去版本的 [!DNL Experience Manager as a Cloud Service] 的功能概览视频。
* [Adobe Experience Manager as a Cloud Service 的最新发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=zh-Hans) - 阅读 [!DNL Experience Manager as a Cloud Service] 的最新发行说明。

### 最新发行版概述视频

观看 [2023 年 1 月发布概述视频](https://video.tv.adobe.com/v/3413479/?quality=12)，大致了解 2023.01.0 版（2023 年 1 月）的新增功能。

### [!DNL Experience Manager Sites] as a [!DNL Cloud Service]

_新增功能_

* 此 [!DNL Experience Manager] GraphQL内容交付API现在支持GraphQL [分页](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/graphql-api/content-fragments.html?lang=en#paging) 和 [排序](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/graphql-api/content-fragments.html?lang=en#sorting)，以提高获取和渲染大型内容集的效率。 GraphQL分页通过返回子集中的结果而不是一次返回所有结果来缩短查询响应时间。 GraphQL排序允许您按所需的顺序放置内容集，使客户端应用程序更轻松地处理内容。 查询响应时间通过中的混合过滤得到进一步改进 [!DNL Experience Manager] GraphQL引擎。 现在，会以与查询过滤器对应的较小集从JCR中读取内容。

### [!DNL Experience Manager Assets] as a [!DNL Cloud Service]

_新增功能_

* Assets Reports现在包含管理员执行以下操作的能力： [生成资源下载报表](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/asset-reports.html?lang=en) 从 [!DNL Experience Manager Assets] as a [!DNL Cloud Service] 部署。 此数据使管理员能够进一步从关键成功指标中获得见解，以衡量在您的企业内和客户采用资源的情况。
* [!DNL Experience Manager Assets]除了用于身份验证的访问密钥外， 现在还[支持 SAS 令牌](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=zh-Hans#asset-bulk-ingestor)，同时还连接到 Azure Blob 存储数据源，从而使用“批量导入”工具摄取资产。
* 改进了Asset compute中CMYK图像的管理，允许您为CMYK图像生成智能裁剪和智能标记。

_预发行渠道中可用的新功能_

* [!DNL Experience Manager Assets] 现在支持 [从Google Cloud Platform大规模引入资源](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=zh-Hans#asset-bulk-ingestor) 使用“批量导入”工具。

### [!DNL Experience Manager Forms] as a [!DNL Cloud Service]

_新增功能_

* **[用于生成非交互式PDF文档和可打印输出的工作流步骤](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-form-centric-workflows/aem-forms-workflow-step-reference.html?lang=en)**  — 使用为您的业务流程自动创建非交互式PDF文档和可打印输出 [!DNL Experience Manager] 工作流步骤，简化文档生成过程并节省时间。
* **[在自适应Forms中使用脚注提供引用或附加信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/add-components-to-an-adaptive-form/footnotes-richtextsupport.html?lang=en)**  — 在自适应表单中使用脚注以显示有关如何完成或使用表单的信息。 您还可以使用它来提供括号信息、版权权限和其他有用信息。


_预发行渠道中可用的新功能_

* [使用数据捕获核心组件构建自适应Forms](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/adaptive-forms/introduction.html?lang=en) - [使用自适应Forms编辑器](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/creating-adaptive-form-core-components.html?lang=en) 创建基于标准化数据捕获组件（核心组件）的表单。 这些组件为您的数字注册体验提供自定义功能、缩短开发时间并降低维护成本。
* [基于自适应Forms的核心组件样式的前端管道支持](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/using-themes-in-core-components.html?lang=en)  — 通过将基于核心组件的自适应Forms的主题与前端部署管道一起部署，使用可轻松自定义的基于BEM的主题来增强表单的外观和感觉。
* [为基于核心组件的自适应Forms生成记录文档](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/generate-document-of-record-core-components.html?lang=en)  — 为基于核心组件的自适应表单创建记录，以打印或文档格式提交以进行长期存档。
* [将自适应Forms提交到Microsoft®SharePoint和Microsoft® OneDrive](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/configure-submit-actions-and-metadata-submission/configuring-submit-actions.html?lang=en)  — 可直接将自适应表单数据发送到Microsoft®SharePoint和Microsoft® OneDrive，从而简化数据提交。 您可以提交基于架构的数据和无架构的数据。 这些提交操作是对已可用提交操作的补充。
* [使用将自适应表单另存为模板功能构建高效表单](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/create-an-adaptive-form-on-forms-cs/template-editor.html?lang=en#save-an-adaptive-form-as-template-saving-adaptive-form-as-template)  — 通过将自适应表单另存为模板并为下一个自适应表单重用模板来简化表单构建过程。
* [Connect [!DNL Experience Manager Forms] 到JDBC支持的数据库](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/use-form-data-model/configure-data-sources.html?lang=en#configure-relational-database-configure-relational-database)  — 轻松连接 [!DNL Experience Manager Forms] 数据模型到支持JDBC的数据库，允许您无缝地读取和写入数据。
* [使用Open API 3.0与REST端点集成](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/use-form-data-model/configure-data-sources.html?lang=en#configure-restful-services-open-api-specification-version-20-configure-restful-services-swagger-version30)  — 连接 [!DNL Experience Manager Forms] as a [!DNL Cloud Service] 将数据模型表单到支持Open API规范版本3.0的REST端点，使您能够轻松发送和接收数据。
* [共享自适应表单以供审阅](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/create-reviews-forms.html?lang=en)  — 使用自适应Forms审阅机制让一个或多个人员审阅表单。

### CIF 加载项

_新增功能_

* 作者可以使用体验片段动态丰富产品列表（例如：在产品列表之间放置横幅）。
* 列表组件现在支持关联产品/类别页面，可动态显示相关页面。
* 添加了对 Peregrine 12.5 组件的支持。
* 添加了对产品 Teaser 和轮播中客户端价格加载的支持。

### [!DNL Experience Manager as a Cloud Service] 基础

_新增功能_

* [快速开发环境](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/rapid-development-environments.html?lang=en) - RDE可让开发人员快速排除问题并在上部署新功能 [!DNL Experience Manager] as a [!DNL Cloud Service].

   快速开发环境是一种新型的云环境，旨在作为一种快速、一致且可扩展的方式，用于验证在本地工作的代码能否在云中正常工作。 使用命令行工具，快速将内容包、捆绑包、内容文件、OSGI配置或Dispatcher配置“同步”到RDE。

   在RDE中成功验证代码后，建议将其部署到云开发环境。 在环境中，您可以通过生产管道将Cloud Manager质量关卡部署到暂存和生产环境之前，先对其进行练习。

   每个程序都包含一个RDE，并且还可以选择许可更多的RDE。

   >[!NOTE]
   >
   >计划在未来几周内逐步推出RDE。 您可以发送电子邮件至 [aemcs-rde-support@adobe.com](mailto:aemcs-rde-support@adobe.com) 跳到队伍前面。

* [对服务器端API访问令牌的扩展支持](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/generating-access-tokens-for-server-side-apis.html?lang=zh-Hans)  — 您现在可以生成多个凭据，这对于API具有不同特征的情况非常有用。 现在，还可以以自助方式撤销凭据。

### [!DNL Cloud Manager]

_新增功能_

* 用户可以下载 [自定义用户界面测试](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/ui-testing.html?lang=en) 来自UI的结果。
* [快速开发环境](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/rapid-development-environments.html?lang=en) (RDE)是一种新型云环境，旨在提供一种快速、一致且可扩展的方式，来验证可在本地工作的代码是否也能按云中的预期工作。
   * RDE使开发人员能够快速排除问题并在上部署新功能 [!DNL Experience Manager] as a [!DNL Cloud Service].
   * 使用命令行工具，开发人员可以快速将内容包、捆绑包、内容文件、OSGi配置或Dispatcher配置同步到RDE。

_API更改_

* 已更改API以支持 [RDE](https://developer.adobe.com/experience-cloud/cloud-manager/reference/api/#tag/Rapid-Development-Environments).
* 该API现在允许检索 [执行对象](https://developer.adobe.com/experience-cloud/cloud-manager/reference/api/#tag/Execution-Artifacts).

### Experience Manager 发行信息

全部 [!DNL Experience Manager] 发行信息可在以下网址找到：

* [Experience Manager as a Cloud Service 版本信息](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hans)
* [Experience Manager as a Cloud Service 发行版更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/overview.html?lang=zh-Hans)
* [Adobe Experience Manager as a Cloud Service 当前发行说明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=zh-Hans)
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
* [Livefyre 发行说明](https://experienceleague.adobe.com/docs/discontinued/using/livefyre.html)

### Experience Manager 的新课程和教程 {#tutorials-aem}

过去一个月发布的新视频、教程及课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2023 年 3 月 | [快速开发环境](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/rde/overview.html) | 视频 | 了解快速开发环境(RDE)、如何设置和使用它，并了解使用RDE的开发生命周期。 | AEM CS |
| 2023 年 3 月 | [Asset Share Commons资产套件](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/assets-share/asset-share-commons-asset-kits.html) | 视频 | 了解如何使用Asset Share Common的资产套件功能生成定制的可共享网页，这些网页列出来自AEM Assets文件夹或收藏集的资产。 | AEM Assets |

{style="table-layout:auto"}

### [!DNL Experience Manager] 支持知识库

[!DNL Adobe Experience Manager] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
|---------|--------|---------|---------|
| 2023 年 2 月 | [如何允许非管理员用户访问Web控制台？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21527.html) | 新文章 | 了解如何允许非管理员用户访问Web控制台（OSGi控制台）。 |
| 2023 年 2 月 | [如何通过cURL下载资产？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21528.html) | 新文章 | 了解如何使用cURL下载资产。 |
| 2023 年 2 月 | [错误：中的BUILD_MAVEN_PACKAGE_ERROR [!DNL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21577.html) | 新文章 | 了解如何解决错误 —  `Build_Maven_Package_Error` 在 [!DNL Cloud Manager]. |
| 2023 年 2 月 | [在构建步骤中部署管道失败](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21419.html) | 新文章 | 找出问题的解决方案，即在构建步骤期间，由于中出现错误而导致管道执行失败。 `ui.frontend` 代码。 |
| 2023 年 2 月 | [封装令牌不支持令牌刷新](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21491.html) | 新文章 | 找到不支持对封装令牌进行令牌刷新的问题的解决方案。 |

{style="table-layout:auto"}

### Experience Manager 的其他帮助资源

* [《Experience Manager as a Cloud Service 指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=zh-Hans)
* [《Cloud Manager 用户指南》](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=zh-Hans)
* [Experience Manager 6.5 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hans)
* [Experience Manager 6.4 学习和支持主页](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hans)
* [Experience Manager 文档的旧版本](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 帮助主页](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hans)
* [Experience Manager 文档：最近的更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hans#aem-as-a-cloud-service)

+++

<!-- ## ![Icon](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] is an application deployed onto AEM. It is a powerful, enterprise-grade component content management solution (CCMS) which enables native DITA support in Adobe Experience Manager, empowering AEM to handle DITA-based content creation and delivery.

Learn more about [[!DNL Experience Manager Guides]](https://business.adobe.com/products/experience-manager/guides/features.html).

### Additional resources

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - tutorials on Experience League
* [[!DNL Experience Manager Guides] Learn & Support](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - product documentation -->

## ![图标](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

访问相关的发行说明、新教程和知识库文章 [!DNL Adobe Commerce] 在Experience League时。

+++详细信息

* 请参阅 [Adobe Commerce 和 Magento Open Source 的发行说明](https://experienceleague.adobe.com/docs/commerce-operations/release/notes/overview.html)以了解最新信息。

>[!NOTE]
>
>[!DNL Adobe Search&Promote]服务终止发生在 **2022 年 9 月 1 日**。 对于产品和商业搜索，[实时搜索](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html?lang=zh-Hans)是 Adobe 的搜索应用程序。 请参阅[服务结束公告](https://experienceleague.adobe.com/docs/discontinued/using/search-promote.html?lang=zh-Hans)，了解更多信息。

### [!DNL Adobe Commerce] 的新教程和文档 {#tutorials-commerce}

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [配置Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/io-events/configure-commerce.html) | 视频 | 了解如何配置Adobe Commerce以公开事件。 |
| 2023 年 3 月 | [开始使用API网格](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/api-mesh/getting-started-api-mesh.html?lang=en) | 视频 | 了解如何在 Adobe Commerce 和 Adobe App Builder 上使用 API Mesh。了解安装AdobeApp Builder、处理项目、创建graphql反向代理等内容。 |
| 2023 年 3 月 | [Adobe Commerce的I/O事件](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/io-events/2-4-5-installation.html?lang=en) | 视频（多个） | 了解如何使用Composer for version 2.4.5、2.4.6等在Adobe Commerce中安装多个新模块。 这将设置在Adobe Commerce应用程序中使用的所需模块。 |

{style="table-layout:auto"}

### [!DNL Commerce] 支持知识库

Adobe Commerce 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
|---------|--------|---------|---------|
| 2023 年 2 月 | [质量补丁工具 (QPT)](https://experienceleague.adobe.com/docs/commerce-knowledge-base/kb/support-tools/patches/patches-available-in-qpt-tool-overview.html) | 新文章 | 关于如何应用 QPT 1.1.26 和 QPT 1.1.27 中可用的补丁的新文章已经发布，并可见于相应分区。 |

{style="table-layout:auto"}

+++

## ![图标](/assets/target.png) [!DNL Target] {#target}

访问预发行说明、当前发行说明和Adobe Target的新教程。

+++详细信息

* 有关预发行信息，请参阅 [[!DNL Adobe Target]  预发行](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hans)
* 有关最新信息，请参阅 [[!DNL Adobe Target]  发行说明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hans)

+++

## ![图标](/assets/campaign.png) [!DNL Campaign] {#ac}

获取的最新更新 [!DNL Adobe Campaign]. 查找有关Experience League的新教程、课程和知识库支持文章。

+++详细信息

### 最新营销活动产品版本

请转到此处以了解中的最新功能、改进和修复 [!DNL Adobe Campaign]：

通过 [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans)、[Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/releases/release-notes.html?lang=zh-Hans) 和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans) 发行说明了解有关最新功能、改进和修复的更多信息。

### 新的 [!DNL Campaign] 教程和课程 {#tutorials-campaign}

为 Adobe Campaign 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2023 年 2 月 | _营销人员借助 Adobe Campaign 取得成功的十大最佳实践_ | 文章 | 了解十大最佳实践，它们有助于使用 Adobe Campaign 的从业人员解锁并加快数字消费者转型，为其客户提供更好的体验。 | 请参阅： <ul><li>[Campaign v8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/strategy/10-best-practices-for-marketers.html)<li>[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/strategy/10-best-practices-for-marketers.html)</li><li>[Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/strategy/10-best-practices-for-marketers.html?lang=en) |

{style="table-layout:auto"}

### [!DNL Campaign] 支持知识库

[!DNL Adobe Campaign] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
|---------|----|----|-----------|
| 2023 年 2 月 | [是否支持TLS 1.3？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21516.html) | 新文章 | 了解TLS 1.3的支持状态。 |
| 2023 年 2 月 | [不显示针对配置文件和服务的 API 更新](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21517.html) | 新文章 | 了解在最新版本的ACS中发布对长文本属性的自定义资源更改时，API未更新的问题的解决方法。 |

{style="table-layout:auto"}

### [!DNL Campaign] 帮助资源

* [!DNL Campaign] v8：[文档](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hans) ‑ [发行说明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=zh-Hans) ‑ [实施指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/config/implement/implement.html)
* [!DNL Campaign] Standard：[Campaign Standard 文档](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hans) ‑ [发行说明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hans) ‑ [操作方法视频](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hans) ‑ [发行计划](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hans) ‑ [最新文档更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hans)
* [!DNL Campaign] Classic：[Campaign Classic v7 文档](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hans) ‑ [发行说明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hans) ‑ [操作方法视频](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hans) ‑ [最新文档更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hans)
* [!DNL Campaign]控制面板：[文档](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans) - [发行说明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=zh-Hans) - [操作方法视频](https://experienceleague.adobe.com/docs/control-panel-learn/tutorials/control-panel-overview.html?lang=zh-Hans)

+++

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Journey Optimizer] {#journey-opt}

了解的最新发行信息 [!DNL Journey Optimizer]. 查看有关Experience League的最新教程和知识库支持文章。

+++详细信息

### 最新 [!DNL Journey Optimizer] 产品版本

有关最新的功能、改进和修复的详细信息，请参见 [Journey Optimizer 发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans)。

### 新的 [!DNL Journey Optimizer] 教程和课程 {#tutorials-ajo}

为 Adobe [!DNL Journey Optimizer] 发布的新视频、教程或课程。

| 发布日期 | 名称 | 类型 | 描述 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [配置培训沙盒](https://experienceleague.adobe.com/docs/journey-optimizer-learn/configure-a-training-sandbox/introduction-and-prerequisites.html?lang=en) | 教程 | 了解如何为培训目的配置沙盒。 完成配置架构、摄取示例数据和创建事件所需的步骤。 |
| 2023 年 3 月 | [Journey Optimizer挑战](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/introduction-and-prerequisites.html?lang=en) | 挑战 | 挑战提供了一种场景和练习运用所学知识的必需要求。每个挑战都涉及您实施的一个独特用例。 <p>新的挑战：<ul><li>[创建夏季系列发布公告](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/summer-collection-announcement-challenge.html?lang=en)  </li><li>[  创建订单确认](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/order-confirmation-challenge.html?lang=en)  </li><li>[创建产品补货通知](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/product-replenishment-challenge.html?lang=en)</li></ul> |

{style="table-layout:auto"}

### [!DNL Journey Optimizer] 支持知识库

[!DNL Adobe Journey Optimizer] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
|---------|-------|--------|---------|
| 2023 年 2 月 | [选择加入不在登陆页面上](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21416.html) | 新文章 | 了解登陆页面上未显示选择加入的问题的解决方案。 |
| 2023 年 2 月 | [缺少数据流通知](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21415.html) | 新文章 | 找出无法接收有关数据流通知的问题的解决方案。 |

{style="table-layout:auto"}

### [!DNL Journey Optimizer] 的更多资源

* [Journey Optimizer 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hans) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hans)
* [Decision Management 文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html) — [发行说明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hans) — [操作方法视频](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=zh-Hans) — [最新文档更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hans)

+++

## ![图标](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

访问最新的发行说明以了解Experience League上的Journey Orchestration。

+++详细信息

### 最新 [!DNL Journey Orchestration] 产品版本

有关最新的功能、改进和修复的详细信息，请参阅[[!DNL Journey Orchestration] 发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)。

#### [!DNL Journey Orchestration] 的更多资源

* [Journey Orchestration文档](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans)

* [发行说明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hans)

* [操作方法视频](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hans)

* [最新文档更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hans)

+++

## ![图标](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

了解的最新发行说明和发行计划 [!DNL Marketo Engage].

+++详细信息

### 核心 Marketo Engage 更新

* 参见 [2023年3月 — 最新发行说明](https://experienceleague.adobe.com/docs/marketo/using/release-notes/current.html?lang=zh-Hans) 了解最新信息
* 有关最新的发布计划信息和发行说明，请参阅 [!DNL Marketo Engage] [发布计划](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hans)。

<!-- ### New Marketo tutorials and courses {#tutorials-marketo}

New videos, tutorials, or courses published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|August 2022 |[Marketo Engage tutorials](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en)|Videos |Visit the [Marketo Engage tutorial home](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) on Experience League for all past and new tutorials for Marketo Engage.|

{style="table-layout:auto"} -->

有关最新的产品文档，请参阅 [Marketo 产品文档](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=zh-Hans)主页。

+++

## ![图标](/assets/workfront.png) [!DNL Workfront] {#workfront}

了解的最新发行说明 [!DNL Adobe Workfront]. 查找有关Experience League的新教程。

+++详细信息

<!-- ### New Adobe [!DNL Workfront] courses and tutorials {#tutorials-workfront}

New [!DNL Workfront] course and collections of tutorials on Experience League.

**Note:** Translation on Experience League for all [[!DNL Workfront]](https://experienceleague.adobe.com/docs/workfront.html?lang=en) tutorials and product documentation is coming soon!

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2023|[Take charge of an existing Adobe Workfront instance](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/system-perfomance-and-maintenance/take-charge-of-an-existing-workfront-instance.html?lang=en)|Video |Learn the key phases to evaluate, understand, and optimize your instance of [!DNL Workfront] as a new system or group administrator.|
|February 2023|[Customize project headers with layout templates](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-project-headers-with-layout-templates.html)|Video |Learn how to add and remove fields from project headers through layout templates.|

{style="table-layout:auto"} -->

请参阅 [[!DNL Workfront]  产品版本](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html)页面，查看所有产品的最新信息综述。

+++

## ![图标](/assets/advertising-cloud.png) Adobe Advertising {#advertising}

[!DNL Adobe Advertising] 的发行说明。

+++详细信息

<!-- * [New features across [!DNL Advertising]](#advertising-all) -->
* [ [!DNL Advertising DSP] 中的新增功能](#advertising-dsp)
* [ [!DNL Advertising Search] 中的新增功能](#advertising-search)
<!-- * [New [!DNL Advertising] tutorials](#tutorials-advertising) -->

<!--
### New features across [!DNL Advertising] {#advertising-all}

Last updated: **August 9, 2022**

| Feature | Description |
| ------- | ----------- |
| Integration with [!DNL Adobe Analytics] | (August 6 release) Improvements to the data feed that Advertising sends to [!DNL Analytics] result in fewer mismatches between click/cost/impression data from the search engines and related conversion data in [!DNL Analytics]. |

{style="table-layout:auto"}

-->

### [!DNL Advertising DSP] 中的新增功能 {#advertising-dsp}

了解Adobe广告的最新功能。

上次更新时间： **2023年3月2日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 营销活动] | （2月15日版）您现在可以在图表表单中查看更改日志，还可以向任何条目添加注释。 |

{style="table-layout:auto"}

### [!DNL Advertising Search] 中的新增功能 {#advertising-search}

上次更新时间： **2023年3月2日**

| 功能 | 描述 |
| ------- | ----------- |
| [!UICONTROL 营销活动] | (Google Ads帐户；打开测试版功能；2月23日发布)的只读同步支持 [!DNL Google Ads] 对于所有广告商，发现营销活动处于测试版模式。 发现营销活动具有 [!UICONTROL 营销活动类型] ”[!UICONTROL 发现]，” [!UICONTROL 广告组类型] ”[!UICONTROL 发现]，”和 [!UICONTROL 创意类型] ”[!UICONTROL 发现广告]“（对于单图像广告）或”[!UICONTROL 发现轮播广告]“”（用于多图像轮播广告）。 可在标准和混合项目组合中包括发现营销活动。<br><br>报告中提供了发现活动的广告级数据。对于具有 Adobe Analytics 集成的广告商，[!DNL Analytics] 中提供了广告级数据。同样，[!DNL Analytics] 数据在 [!DNL Search] 中可用；这些数据是使用升级后的 `s_kwcid` 跟踪参数发送的，无论您通常为帐户使用的 `s_kwcid` 格式如何。如果您通常使用旧版本的 `s_kwcid`，那么您的点击/成本数据和收入数据将使用不同的 `s_kwcids` 进行跟踪，但两组数据都会被完全分类并汇总在相同的营销活动和帐户中。 |
|  | ([!DNL Google Ads] 帐户；2月11日发布)对“[!UICONTROL 目标展示份额]“竞价策略现在仅适用于搜索网络上的促销活动。 对于此竞价策略， [!DNL Google Ads] (非 [!DNL Search])优化竞价以实现目标展示份额和广告位置。 您可以选择输入 [!UICONTROL 目标展示份额] 以百分比表示， [!UICONTROL 目标广告位置]，和 [!UICONTROL 最大CPC] （每次点击成本）。 混合项目组合中尚不支持此选项。 |
| [!UICONTROL 批量处理工作表] | ([!DNL Microsoft] 营销活动；2月11日版)批量工作表现在包含&quot;[!UICONTROL 行动号召]“ ”和“ ”[!UICONTROL 行动动员语言]”列（响应式广告格式），使用“[!UICONTROL 创意（RSA除外）]”行。 |
| Google Manager帐户 | （2月23日发布）新的 [!UICONTROL 管理员] > [!UICONTROL 经理帐户] 功能允许您为以下对象提供身份验证 [!DNL Google Ads] 经理帐户 [!DNL Search] 将上传跨帐户转化。 如果您想要)上传，请使用此功能 [!DNL Adobe]-tracked、跨帐户转化指标 [!DNL Google Ads] 经理帐户或b)上传包含跨帐户转换的项目组合目标 [!DNL Google Ads] 进行混合优化。<br><br>为经理帐户添加凭据后，可选»[!UICONTROL 跨帐户转化的经理帐户]中的“ ”列 [!UICONTROL 营销活动] > [!UICONTROL 帐户] 视图指示每个子帐户的manager帐户ID，当未验证manager帐户时，列会显示错误。 |

{style="table-layout:auto"}

+++

## ![图标](/assets/document-cloud-24.png) [!DNL Document Cloud] {#doc-cloud}

为 [!DNL Document Cloud] 发布的新教程和课程，包括 [!DNL Document Services] 和 [!DNL Acrobat Sign]。 

+++详细信息

| 发布日期 | 名称 | 类型 | 描述 | 应用程序 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2023 年 3 月 | [发送公证](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/notarize/send-document-notarize.html?lang=en) | 视频 | 了解如何发送文档进行公证、查看签名者的体验并接收结果。 | Acrobat Sign |

{style="table-layout:auto"}

对于有关 [!DNL Document Cloud] 的帮助，请参见：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hans)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hans)
* [Document Cloud 学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

+++

<!-- ## ![Icon](/assets/creative-cloud-24.png) [!DNL Creative Cloud] for enterprise {#creative-cloud}

New videos, tutorials, or courses published for [!DNL Creative Cloud] for enterprise.

+++Details

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2023|[Professional motion graphics templates](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/videooverview/videotutorials/motion-graphics-templates.html?lang=en)|PDF tutorial|Using the Essential Graphics workflow in Adobe After Effects and Adobe Premiere Pro, editors can import MOGRTs and set properties. Properties include text, fonts, color, size, speed, or layout editable, while maintaining the sequence's consistent look and design.|
|January 2023|[Collaboration: The Future of Creativity](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/collaboration-the-future-of-creativity.html?lang=en)|PDF tutorial |Get free access to more than 20,000 professionally designed and curated fonts from Adobe Fonts. Originally known as Typekit, Adobe Fonts are available through a single licensing agreement that gives designers unlimited creative use for personal or commercial projects.|
|January 2023|[3D design and rendering](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/substance-3d-stager.html?lang=en)|PDF tutorial |Import content, arrange your scene, apply materials and textures, adjust image-based and physical lighting, save cameras with different resolutions, and render photorealistic imagery - all in Adobe Substance 3D Stager.|
|January 2023|[Adobe Express: Content that stands out](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/adobe-express-content-that-stands-out.html?lang=en)|PDF tutorial |Create beautiful graphics, web pages, and video stories in minutes with Adobe Express (formerly known as Adobe Spark). Working from thousands of professionally designed templates, make social posts and stories, flyers, logos, booklets, posters, and more. Start for free, and make content that always stands out.|

{style="table-layout:auto"} 

See [Creative Cloud for enterprise tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.

+++
-->

<!-- ## ![Icon](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) is your destination as a customer data management technical and marketing practice leader and specialist. This collection of tutorials is your one-stop-shop to hear from your peers, get inspired, and learn about developments in MarTech. No registration required, simply click and watch.

## ![Icon](/assets/experience-league.png) Digital Experience Blueprints {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) are repeatable implementations that let you address strategy and quickly solve established business problems. Each Blueprint provides a series of artifacts that explain the high-value business problem, architectures, implementation steps, technical considerations, and links to the relevant documentation.

### New Digital Experience Blueprints tutorials

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2023|[Customer Journeys - AEP + Apps & AJO Architecture](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en)|Diagram updates|Deliver individual, just-in-time customer experiences across screens.| 
-->

