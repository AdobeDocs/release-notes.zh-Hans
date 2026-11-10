---
title: 中央发行说明
description: 查找指向Experience Cloud应用程序发行说明的链接。 查看新的教程视频、阅读支持文章并找到有关Experience League的自助资源。
doc-type: release notes
last-update: November 2026
author: mfrei
mini-toc-levels: 2
source-git-commit: 1dec9473ee9a93bdd9ae5c9ce10bd3801c8ae131
workflow-type: tm+mt
source-wordcount: '34822'
ht-degree: 11%
---
# [!DNL CX Enterprise]中央发行说明 — 2026年11月 {#top}

此页面可帮助您查找最新信息：

* 所有[!DNL CX Enterprise]应用程序的[发行说明](#application-release-notes)汇总（更新日期： **11月8日**）
* 每个应用程序[新视频和支持文章](#articles)

要查找并注册活动，请访问[Experience League活动](https://experienceleague.adobe.com/zh-hans/events)

>[!TIP]
>
>若要接收有关此页面的新[!DNL CX Enterprise]功能和更新的每月电子邮件，请在[[!UICONTROL 新闻稿]](https://account.adobe.com/magazines)页面上启用&#x200B;**[!UICONTROL 产品更新优先级]**。

## [!DNL CX Enterprise] 发行说明 {#application-release-notes}

了解所有[!DNL CX Enterprise]应用程序的新（和计划）更新。

**重要信息：**&#x200B;某些应用程序每周发布一次。 要了解最新信息，请经常访问这些页面。

上次更新：**2026年11月8日**

| 应用程序 | 发行日期 | 发行说明 URL | 更新 |
| ------------- | ------------- | ------------- | ------------- |
| **[!DNL Adobe Commerce]as a Cloud Service** | 2026年11月10日 | [Adobe Commerce as a Cloud Service发行说明](https://experienceleague.adobe.com/zh-hans/docs/commerce/cloud-service/release-notes){target="_blank"} | <ul><li>购物车项目的自定义属性通过`addProductsToCart`突变；装运项目过滤器webhook以排除由第三方履行的项目（11月10日；立即沙盒）</li><li>新`observer.rma_save_before` webhook，可在保存返回数据之前读取和修改该数据（11月10日）</li><li>现在，通过REST API创建的非虚拟订单需要一个送货地址（11月10日）</li><li>存储信用余额的`GET /V1/customers/:customerId/balance`终结点；`InvoiceItemInterface`上的`row_total`字段（11月10日）</li><li>Webhook在呈现评论电子邮件之前添加或更改模板变量（10月28日）</li><li>将批准的产品审查计数和平均评级作为系统属性导出到目录服务（10月28日）</li></ul>[教程和支持文章](#tutorials-commerce) |
| **[!DNL Adobe Marketo Engage]** | 2026年11月6 | [Marketo Engage 当前发行说明](https://experienceleague.adobe.com/zh-hans/docs/marketo/using/release-notes/current){target="_blank"} | <ul><li>[!DNL CX Enterprise Coworker]计划营销活动技能：将营销活动简报转换为[!DNL Marketo Engage]项目设置文档</li><li>可调用代理：作为智能营销活动流步骤运行并将结果写回潜在客户字段的AI代理（即将推出）</li><li>克隆到此程序/文件夹选项以克隆目标（即将推出）</li><li>即时提醒已订阅管理员的CRM同步状态更改</li><li>[!DNL Marketo Engage]个新UI：刷新了菜单、图标和布局</li></ul>[教程和支持文章](#tutorials-marketo) |
| **[!DNL Adobe Journey Optimizer B2B Edition]** | 2026年11月6 | [Journey Optimizer B2B Edition 发行说明](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-b2b/user/release-notes){target="_blank"} | <ul><li>用于定向用户档案的静态和动态人员列表，以及人员列表过滤器，用于按列表成员资格包含或排除用户档案</li><li>历程操作，以将用户添加到静态用户列表或从静态用户列表中删除用户</li><li>历程节点标签以标识画布上的节点</li><li>使用变体拆分路径旅程节点(Beta)以进行A/B测试</li><li>增强&#x200B;_侦听支持多个触发器的事件_&#x200B;节点</li></ul>[教程和支持文章](#tutorials-ajo-b2b) |
| **[!DNL Adobe Journey Optimizer]** | 2026年11月5日 | [[!DNL Journey Optimizer] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer/using/whats-new/release-notes){target="_blank"} | <ul><li>Experience Manager片段的动态令牌替换：直接在内容片段中使用配置文件属性路径，无需令牌映射（限量发布）（11月5日）</li><li>用于个性化优化模型的配置文件和上下文功能以提高选件相关性（限量发布）（11月3日）</li><li>在[!DNL CX Enterprise Coworker]中编排了营销活动技能：列出并过滤营销活动，检索详细信息和历史记录，以及呈现工作流图形（11月3日）</li><li>促销活动、历程和编排促销活动的统一日历（限量发布）（10月29日）</li><li>营销活动和历程的自定义元数据：每个实体类型最多10个自定义业务字段（限量发布）（10月29日）</li></ul>[教程和支持文章](#tutorials-ajo) |
| **[!DNL Adobe Experience Manager]&#x200B;[!DNL Cloud Manager]** | 2026年11月5日 | [Experience Manager Cloud Manager 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-manager/content/release-notes/current){target="_blank"} | <ul><li>2026.11.0： AMS程序的Web层管道与全栈部署分开部署Dispatcher和Web层配置</li><li>2026.11.0：代码质量(SonarQube)扫描不再在大型项目中失败</li><li>2026.11.0：站点使用CSV导出显示正确的月份标签；重用访问令牌名称不再覆盖现有令牌</li><li>通过智能构建模块级缓存提高了构建性能</li><li>客户管理密钥（CMK）自助服务</li></ul>[教程和支持文章](#tutorials-aem) |
| **Adobe Advertising** | 搜索、社交和Commerce： 2026年11月4日<br>DSP： 2026年8月14日<br>Creative： 2026年7月1日 | <ul><li>[搜索、社交和Commerce的新增功能](https://experienceleague.adobe.com/zh-hans/docs/advertising/search-social-commerce/home){target="_blank"}</li><li>[DSP的新增功能](https://experienceleague.adobe.com/zh-hans/docs/advertising/dsp/home){target="_blank"}</li><li>[Creative的新增功能](https://experienceleague.adobe.com/zh-hans/docs/advertising/creative/home){target="_blank"}</li></ul> | <ul><li>搜索、社交和Commerce：在优化项目组合中选择使用Google广告预算推荐；预算可保留或提高，不得降低</li><li>搜索、社交和Commerce：使用AI Max的Google广告促销活动的促销活动级别的品牌包含、品牌排除和URL包含（以及广告组级别的URL包含），并提供批量处理工作表支持</li><li>搜索、社交和Commerce：ChatGPT广告支持(Beta)</li><li>搜索、社交和Commerce： Google AI最大搜索词组合报表通过转化操作添加转化</li><li>DSP：自归因转化报表</li><li>DSP：Creative Studio，具有创作AI (Beta)和品牌配置文件；邮政编码定位列表</li><li>Creative：具有AI和品牌配置文件的Creative Studio，用于生成显示广告</li><li>Creative：Adobe Analytics中的变量和分支级别性能；基于信息源的模板中符合VAST标准的视频广告</li></ul> |
| **[!DNL Adobe Customer Journey Analytics]** | 2026年11月3日 | [Customer Journey Analytics 发行说明](https://experienceleague.adobe.com/zh-hans/docs/analytics-platform/using/releases/latest?lang=en#releases){target="_blank"} | <ul><li>[!DNL CX Enterprise Coworker]：使用Content Analytics数据询问有关您内容的问题（正式发布）（11月3日）</li><li>同事的产品内体验： Analysis Workspace中将打开项目用作上下文的聊天面板（10月29日）</li><li>自动生成组件和项目的描述（10月29日；GA 11月18日）</li><li>Adobe Brand Visibility集成，用于衡量AI驱动的发现如何推动网站参与（10月29日）</li><li>历程画布：比较百分比选项显示节点、箭头和流失与上一时段（10月19日）相比的百分点变化</li></ul>[教程和支持文章](#tutorials-cja) |
| **[!DNL Adobe Analytics]** | 2026年10月29日 | [[!DNL Analytics] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/analytics/release-notes/latest){target="_blank"} | <ul><li>可视化图表中的简洁图例标签（10月29日）</li><li>自动生成组件和项目的描述（10月29日；GA 11月18日）</li><li>[!DNL Coworker Chat]：高级分析、量度更改的根本原因分析以及在Analysis Workspace中打开可视化图表（10月29日）</li><li>[!DNL CX Enterprise Coworker]可以将[!DNL Adobe Analytics]个项目和组件迁移到Customer Journey Analytics（10月26日）</li><li>Data Warehouse报表中的分类数据改进，包括已删除值的空白（10月14日）</li></ul>[教程和支持文章](#tutorials-analytics) |
| **[!DNL Adobe Experience Manager]as a Cloud Service** | 2026年10月29日 | [Adobe Experience Manager as a Cloud Service 当前发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current){target="_blank"} | <ul><li>功能版本2026.10.0现已更新；2026.11.0计划于2026年11月19日发布</li><li>AEM Cloud Service SDK支持用于本地开发的Java 25运行时（10月29日）</li><li>Assets：多语言字幕和音轨、人工智能生成的字幕、品牌视频查看器；Content Hub获得AI 搜索和智能收藏集</li><li>AEM治理代理优先考虑漏洞发现；[!DNL CX Enterprise Coworker]可以检查工作流并调查Dispatcher行为</li><li>Forms：自适应Forms的表组件、新的文档转换API以及文件附件的病毒扫描</li><li>OpenTelemetry for APM有限可用（10月19日）</li></ul>[教程和支持文章](#tutorials-aem) |
| **[!DNL Adobe Marketing Campaign Analytics]**（以前称为 [!DNL Adobe Mix Modeler]） | 2026年10月29日 | [Marketing Campaign Analytics发行说明](https://experienceleague.adobe.com/zh-hans/docs/marketing-campaign-analytics/using/releases/latest){target="_blank"} | <ul><li>完整funnel建模：在构建模型时启用，以显示营销如何通过funnel移动客户；模型见解添加了funnel流量可视化图表（10月29日）</li><li>付费媒体渠道聚焦：关于付费媒体渠道贡献的焦点模型见解（8月19日）</li><li>营销绩效摘要配置：为基于收入的模型选择量度及其显示方式（8月19日）</li><li>在协调的数据集配置中，按源、粒度和一周的开始过滤数据集规则（8月19日）</li><li>渠道adstock （3月30日）</li></ul>[教程和支持文章](#tutorials-mca) |
| **[!DNL CX Enterprise Coworker]** | 2026年10月28日 | [[!DNL CX Enterprise Coworker] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/more-resources/release-notes){target="_blank"} | <ul><li>[!DNL Coworker Chat]： [!DNL Experience Platform]发行说明中列出的功能增强和修复</li><li>适用于团队的[!DNL Coworker]：功能增强和修复，持续交付</li><li>[!DNL CX Enterprise]中心发行说明的链接</li></ul> |
| **[!DNL Experience Platform]移动设备SDK** | 2026年10月28日 | [[!DNL Experience Platform] Mobile SDK 发行说明](https://developer.adobe.com/client-sdks/home/release-notes/){target="_blank"} | <ul><li>Brand Concierge iOS 5.10.2和Android 3.10.2：隐私声明、代理消息填充主题令牌和对齐修复（10月27日）</li><li>消息：iOS 5.18.0和Android 3.14.0推送令牌同步更新；Android BOM 3.25.0（10月22日）</li><li>Edge：iOS 5.3.0和Android 3.2.0将设备属性发送到Edge Network，而不依赖于收集同意（10月21日）</li><li>EdgeIdentity： iOS 5.2.0和Android 3.2.0添加updateOperationalData API（10月21日）</li><li>核心：iOS 5.13.0和Android 3.11.0添加了转发操作数据规则结果（10月19日）</li></ul> |
| **[!DNL Adobe Experience Platform and Real-Time CDP]** | 2026年10月27日 | [[!DNL Experience Platform] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-platform/release-notes/latest){target="_blank"} | <ul><li>[!DNL CX Enterprise Coworker]：异常检测技能（可用性限制）和通知技能；在Microsoft 365 Copilot、ChatGPT和Claude中提供了同事</li><li>目标：6sense帐户（测试版）、交易台第三方受众、交易台的新UID2转化命名空间 — CRM以及何时激活正式可用</li><li>Real-Time Customer Profile：支持非结构化数据（测试版）</li><li>目标：数据登录区支持手动删除Azure和AWS的导出文件</li><li>来源：Azure事件中心虚拟网络已弃用</li></ul>[教程和支持文章](#tutorials-aep) |
| **[!DNL Adobe Brand Visibility]（以前为[!DNL Adobe LLM Optimizer]）** | 2026年10月24日 | [品牌可见度发行说明](https://abv.adobe.com/articles/release-notes){target="_blank"} | <ul><li>提示库：自定义标记（付费客户），用于按您自己的类别对大型提示库进行排序</li><li>Opportunity Workspace：试验完成后包含指向结果的链接的通知</li><li>AI可见性：选择在跟踪主题时要添加的单个提示</li><li>品牌声明：在“所有声明”列表中搜索声明文本</li><li>提示库：导入、写入和删除操作的状态更可靠</li><li>正式发布：在品牌可见度中统一的AI可见性测量、优化和影响跟踪（从LLM Optimizer中重新命名）</li></ul>[教程和支持文章](#tutorials-llm-optimizer) |
| **[!DNL Adobe Workfront]** | 2026年10月22日（2026年第四季度） | [Adobe Workfront 产品发布](https://experienceleague.adobe.com/zh-hans/docs/workfront/using/product-announcements/product-releases/product-releases){target="_blank"} | <ul><li>[!DNL CX Enterprise Coworker]取代AI助手作为在[!DNL Workfront]和连接的Adobe系统中工作的对话界面（从10月22日起分阶段推出）</li><li>将多个文档分组到一个审批工作流中</li><li>Workfront MCP服务器工具集：将MCP目录限制为特定工具集并按产品权利进行筛选</li><li>适用于Google Cloud Platform和Azure上的实例的画布功能板打开测试版</li><li>费率属性层级自动保持连接（工作流Ultimate）</li></ul>[教程和支持文章](#tutorials-workfront) |
| **[!DNL Adobe Target]** | 2026年10月15日 | [[!DNL Adobe Target] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/target/using/release-notes/release-notes){target="_blank"} | <ul><li>26.10.2：修复了活动概述中错误显示的目标设置、在编辑促销活动后创建的备份推荐以及大约两周后删除的报告预设；添加了Safari支持（在可视化体验编辑器或增强型体验编辑器中不受支持）</li><li>26.10.1：修复了A4T报表错误，修复了在可视化体验编辑器中显示新添加报表包和原始HTML而非体验片段的选件名称</li><li>26.9.8：样本量计算器（Beta版），用于通过估算流量、持续时间和最低可检测效果来计划试验</li><li>26.9.8：A/B测试（手动）活动的人工智能见解（测试版）</li><li>26.9.8：修复了阻止用户授予AI权限的问题</li></ul>[教程和支持文章](#tutorials-target) |
| **[!DNL Adobe Campaign Classic]v7** | 2026年10月15日 | [[!DNL Campaign Classic] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/campaign-classic/using/release-notes/latest-release){target="_blank"} | <ul><li>7.4.5（内部版本9420,10月15日）：修复了Analytics外部帐户`Gone`错误、投放停滞在个性化待处理中、高CPU来自锁定循环、误报的“垃圾邮件检查失败”错误，以及软退回后未隔离收件人</li><li>关键漏洞的安全更新（7.4.4，内部版本9403,10月15日；需要重新启动nlserver）</li><li>关键漏洞的安全更新（v7.4.3，内部版本9401,8月25日）</li><li>Adobe Analytics连接器已迁移到Analytics 2.0 API（内部版本9400,8月11日）</li></ul>[教程和支持文章](#tutorials-campaign) |
| **[!DNL Adobe Campaign]Web用户界面** | 2026年9月22日 | [Campaign Web UI 发行说明](https://experienceleague.adobe.com/zh-hans/docs/campaign-web/v8/release-notes/release-notes){target="_blank"} | <ul><li>LINE渠道支持：在独立投放或工作流中创建和发送LINE消息</li><li>预算和投放开始审批类型</li><li>短信投放现在支持基于访客的定位</li><li>在扩充和构建受众活动中扩充外部数据库</li><li>管理员可以限制特定的侧面导航菜单条目</li></ul>[教程和支持文章](#tutorials-campaign) |
| **[!DNL Adobe System Status]** | 2026年9月16日 | [Adobe系统状态发行说明](system-status-release-notes.md) | <ul><li>AI虚拟助理中连续提示的上下文</li><li>基于您的权利和订阅的默认主页、云和产品页面（在&#x200B;**所有**&#x200B;和&#x200B;**我的事件**&#x200B;之间切换）</li><li>状态MCP（测试版）：通过模型上下文协议将状态API连接到人工智能代理和LLM</li><li>AI虚拟助理正式发布（6月4日）</li><li>Microsoft Teams的状态订阅通知（6月4日）</li></ul>[教程和支持文章](#status) |
| **[!DNL Adobe GenStudio for Performance Marketing]** | 2026年9月15日 | [GenStudio for Performance Marketing 发行说明](https://experienceleague.adobe.com/zh-hans/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest){target="_blank"} | <ul><li>批量激活：从单个激活表跨付费广告渠道（[!DNL Meta]、[!DNL LinkedIn]、Google Campaign Manager 360、Amazon Ads、Innovid、[!DNL TikTok]、[!DNL YouTube]、ChatGPT、交易台）发布多个批准的体验</li><li>在Horizon画布上进行批量编辑（链接的文本/图像字段将跨大小和页面传播编辑内容）</li><li>向交易台显示广告激活</li><li>内容片段交换：将文本块替换为AEM中预批准、可重用的内容片段</li></ul>[教程和支持文章](#tutorials-genstudio-marketing) |
| **[!DNL Adobe Commerce Optimizer]** | 2026年9月9日 | [Adobe Commerce Optimizer发行说明](https://experienceleague.adobe.com/zh-hans/docs/commerce/optimizer/release-notes){target="_blank"} | <ul><li>多值HTTP标头触发器策略（匹配单个标头中的多个逗号分隔值）</li><li>属性排名(Beta)：自动提升、隐藏或隐藏每个符合属性条件的产品</li><li>目录服务GraphQL中的新[!DNL externalIds]字段公开产品的原始外部数据源</li><li>高级搜索选项卡中的语义搜索（AI支持），默认情况下对符合条件的英语目录启用</li><li>产品推荐单位的推荐价格过滤器（测试版）</li></ul>[教程和支持文章](#tutorials-commerce) |
| **[!DNL CX Enterprise]** | 2026年7月10日 | [[!DNL CX Enterprise] 中央UI和管理](https://experienceleague.adobe.com/zh-hans/docs/core-services/interface/more-resources/release-notes){target="_blank"} | <ul><li>对Federated Guest帐户的[!DNL CX Enterprise]支持（7月10日）</li><li>[!DNL CX Enterprise Coworker]：用于CX工作流的代理AI应用程序（6月11日）</li><li>Agentic AI使用监控仪表板（6月1日）</li><li>Adobe [!DNL CX Enterprise]界面刷新（深色模式，改进了可访问性）（4月20日）</li></ul> |
| **[!DNL Adobe Commerce]** | 持续发布 | [Adobe Commerce 和 Magento Open Source 发行说明](https://experienceleague.adobe.com/zh-hans/docs/commerce-operations/release/notes/adobe-commerce/2-4-9){target="_blank"} | <ul><li>REST API 产品图库继承控制（店面视图级别）</li><li>clearCart GraphQL突变现在可供Open Source使用</li><li>添加了PHP 8.5支持；删除了PHP 8.2支持</li><li>为REST和GraphQL API强制实施验证码验证</li><li>USPS集成已通过OAuth 2.0迁移到RESTful API</li><li>支持MariaDB 11.8/12.x和OpenSearch 3.x</li></ul>[教程和支持文章](#tutorials-commerce) |
| **[!DNL Adobe Workfront Fusion]** | 2026 年 6 月 | [Adobe Workfront Fusion 发行活动](https://experienceleague.adobe.com/zh-hans/docs/workfront-fusion/using/fusion-release-activity/fusion-releases-2026/fusion-2026-6-1){target="_blank"} | <ul><li>重新触发特定场景执行</li><li>Run Once 功能更新</li></ul>[教程和支持文章](#tutorials-workfront) |
| **[!DNL Adobe Experience Manager]6.5** | 2026 年 5 月 21 日 | [[!DNL Experience Manager] 6.5 服务包发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-65/content/release-notes/release-notes){target="_blank"} | <ul><li>6.5.25.0：跨Sites、Assets和Foundation的275个后端口</li><li>Crosswalk 默认可用</li><li>广泛的键盘导航、焦点管理以及其他辅助功能改进</li><li>内容片段和 GraphQL API 可靠性改进</li><li>安全性补丁回移</li></ul>[教程和支持文章](#tutorials-aem) |
| **[!DNL Experience Manager]桌面应用程序** | 2026 年 5 月 13 日 | [[!DNL Experience Manager] 桌面应用程序发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-desktop-app/using/release-notes){target="_blank"} | <ul><li>修复问题以提升整体稳定性和性能（v3.0.2）</li></ul> |
| **[!DNL Adobe Pass]** | 2026 年 5 月（3.7.0.2） | [Adobe Pass 3.7.0 发行说明](https://experienceleague.adobe.com/zh-hans/docs/pass/authentication/product-releases/2026/auth-rn-370){target="_blank"} | <ul><li>支持基于 OAuth2 的 MVPD 身份验证 PKCE</li><li>TVE Dashboard 1.5.1</li><li>修复 Apple SSO 配置不匹配问题</li><li>修复 HTTP 500 授权拒绝问题</li></ul>[教程和支持文章](#tutorials-pass) |
| **[!DNL Experience Manager]Assets Dynamic Media** | 2026 年 5 月 9 日 | [[!DNL Experience Manager] AEM Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/zh-hans/docs/dynamic-media-developer-resources/release-notes/s7rn2017){target="_blank"} | <ul><li>HTTP/2 内容交付</li><li>为 Scene7 Servlet 添加身份验证</li><li>支持 FTP WebAdmin 的 OKTA 身份验证</li><li>Viewer Analytics 现支持 Experience Cloud 组织 ID</li><li>HTML5 查看器中的键盘无障碍支持（Image Serving 5.8.1）</li></ul> |
| **[!DNL Adobe Brand Concierge]** | 2026 年 5 月 8 日 | [Brand Concierge 发行说明](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/release-notes/current){target="_blank"} | <ul><li>Brand Concierge 与 Real-Time CDP 集成</li><li>自助调优增强功能</li><li>上下文感知产品推荐</li><li>并排比较</li><li>支持代理（故障排查和操作指导）</li></ul>[教程和支持文章](#tutorials-brand-concierge) |
| **[!DNL Adobe Campaign]v8** | 2026 年 5 月 3 日 | [[!DNL Campaign] v8 发行说明](https://experienceleague.adobe.com/zh-hans/docs/campaign/campaign-v8/releases/release-notes){target="_blank"} | <ul><li>Debian 13 和 PostgreSQL 17 升级</li><li>修复了服务器崩溃和电子邮件管道内存问题</li><li>解决了跟踪工作流和类型规则失败的问题</li><li>30多种稳定性和安全修复</li></ul>[教程和支持文章](#tutorials-campaign) |
| **[!DNL Adobe Campaign Standard]** | 2026年4月24日(26.2) | [[!DNL Campaign Standard] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/campaign-standard/using/release-notes/release-notes){target="_blank"} | <ul><li>Debian 13 和 PostgreSQL 17 升级</li><li>增强的动态报告可靠性</li><li>增强的IMS身份验证</li><li>选项中的加密密码类型字段</li><li>修复了AEM内容检索错误</li></ul>[教程和支持文章](#tutorials-campaign) |
| **[!DNL Marketo Engage]&#x200B;[!DNL Dynamic Chat]** | 2026年3月 | [Dynamic Chat 发行说明](https://experienceleague.adobe.com/zh-hans/docs/marketo/using/release-notes/dynamic-chat){target="_blank"} | <ul><li>访客等待时间限制</li><li>下载对话记录</li><li>路由逻辑重构</li></ul>[教程和支持文章](#tutorials-marketo) |
| **[!DNL Experience Manager]&#x200B;[!DNL Brand Portal]** | 2026 年 1 月 1 日 | [Experience Manager Brand Portal 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes){target="_blank"} | <ul><li>Dynamic Media 配置重置按钮</li><li>发布前验证源文件夹</li></ul> |
| **[!DNL Experience Manager]&#x200B;[!DNL Dispatcher]** | 2025 年 11 月 20 日 | [Experience Manager Dispatcher 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-dispatcher/using/getting-started/release-notes){target="_blank"} | <ul><li>Dispatcher 配置中的 /allowedClients 控制项</li><li>针对 429 响应的 stale-while-error 处理机制</li><li>虚名 URL 加载优化</li></ul> |
| **[!DNL Adobe Streaming Media Analytics]** | 2025 年 10 月 7 日 | [Streaming Media Analytics 发行说明](https://experienceleague.adobe.com/zh-hans/docs/media-analytics/using/release-notes/release-notes){target="_blank"} | <ul><li>支持计划数据</li></ul> |
| **[!DNL Experience Manager]&#x200B;[!DNL Assets Essentials]** | 2024 年 7 月 25 日 | [Experience Manager Assets Dynamic Media 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/release-notes){target="_blank"} | <ul><li>Content Credentials 集成</li><li>文件夹内容的视觉预览</li><li>上下文搜索</li><li>就地重命名资源和文件夹</li><li>Express 视频快速操作</li></ul> |
| **[!DNL Experience Manager]自动表单转换服务** | 2022 年 2 月 24 日 | [Automated Forms Conversion Service 发行说明](https://experienceleague.adobe.com/zh-hans/docs/aem-forms-automated-conversion-service/using/release-notes){target="_blank"} | <ul><li>自动将章节转换为片段，以提升渲染速度</li></ul> |

[回到顶部](#top)

## 新视频和支持文章 {#articles}

按应用程序链接到最新的视频教程和[支持](https://experienceleague.adobe.com/support/v2/en/?lang=zh-Hans)文章。 （有关功能和修复的产品文档，请转到[应用程序发行说明](#application-release-notes)，或者使用每个部分中的发行说明链接。）

* [Adobe [!DNL CX Enterprise Coworker]](#ai)
* [[!DNL Adobe Experience Platform]](#tutorials-aep)
* [[!DNL Adobe Real-Time CDP]](#tutorials-rtcdp)
* [[!DNL Adobe Analytics]](#tutorials-analytics)
* [[!DNL Adobe Customer Journey Analytics]](#tutorials-cja)
* [[!DNL Adobe Streaming Media Analytics]](#tutorials-sma)
* [[!DNL Adobe Marketing Campaign Analytics]](#tutorials-mca)
* [[!DNL Adobe Experience Manager]](#tutorials-aem)
* [[!DNL Adobe Commerce]](#tutorials-commerce)
* [[!DNL Adobe Target]](#tutorials-target)
* [[!DNL Adobe Campaign]](#tutorials-campaign)
* [[!DNL Adobe Journey Optimizer]](#tutorials-ajo)
* [[!DNL Adobe Journey Optimizer B2B Edition]](#tutorials-ajo-b2b)
* [[!DNL Adobe Marketo Engage]](#tutorials-marketo)
* [[!DNL Adobe Workfront]](#tutorials-workfront)
* [[!DNL Adobe GenStudio for Performance Marketing]](#tutorials-genstudio-marketing)
* [[!DNL Adobe Pass]](#tutorials-pass)
* [[!DNL Adobe Document Cloud]](#tutorials-document-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#tutorials-creative-cloud)
* [[!DNL Adobe Brand Concierge]](#tutorials-brand-concierge)
* [[!DNL Adobe LLM Optimizer]](#tutorials-llm-optimizer)
* [客户数据管理 — 意见](#tutorials-voices)
* [客户体验编排Blueprint](#tutorials-blueprints)
* [Adobe 认证](https://experienceleague.adobe.com/zh-hans/certification-home){target="_blank"}
* [Adobe产品安全漏洞](https://helpx.adobe.com/cn/security.html){target="_blank"}

### [!DNL CX Enterprise Coworker]和AI资源 {#ai}

在[!DNL CX Enterprise]应用程序中查找为[[!DNL Coworker]](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/home)和AI功能发布的最新学习资源。

| 应用程序 | 更新 | 描述 | 更新 |
| ------- | ------- | ------- | ------- |
| [!DNL Coworker] | **历程** | [与同事一起加速客户历程编排](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/journeys/accelerate-personalized-customer-engagement){target="_blank"} — 了解[!DNL Coworker]如何通过识别访客受众、在[!DNL Journey Optimizer]中创建历程以及准备促销消息，将营销目标转化为个性化参与历程。 | 2026年11月5日 |
| [!DNL Coworker] | **受众** | [为什么我的受众规模会增加或减少？](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/audiences/why-your-audience-size-changed){target="_blank"}  — 了解如何在[!DNL Coworker]中使用纯语言提示来调查意外的受众规模更改，使用因果分析将其与操作数据连接并排除配置更改。 | 2026年11月5日 |
| [!DNL Coworker] | **历程** | [使用辅助进程比较历程版本](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/journeys/journey-version-comparison){target="_blank"} — 了解如何将[!DNL Journey Optimizer]历程的版本与活动、分支和历程属性的可视化比较和详细更改摘要进行比较。 | 2026年11月4 |
| [!DNL Coworker] | **历程** | [使用同事模拟历程](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/journeys/simulate-journey-using-coworker){target="_blank"} — 了解如何在发布之前模拟[!DNL Journey Optimizer]历程以测试路径、接收校样消息和查看路径覆盖率。 | 2026年11月3日 |
| [!DNL Coworker] | **工作流** | [同事聊天工作流](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/workflows){target="_blank"} — 现在列出了检查[!DNL Experience Manager]工作流和探索Dispatcher见解的技能，以及清单分发、清单运行状况、谱系和重复检测的新受众技能。 | 2026年11月2 |
| [!DNL Coworker] | **开始使用** | [开始使用同事聊天](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/ui-guide){target="_blank"} — 重写以匹配当前界面，包括帐户菜单、导航边栏、**项目**、**体验上下文**，以及如何选择组织和沙盒。 | 2026年10月26日 |
| [!DNL Coworker] | **历程** | [从图像创建历程](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/journeys/create-journey-from-image){target="_blank"} — 查看[!DNL Coworker]如何在[!DNL Journey Optimizer]中将流程图图像（如营销团队的幻灯片）转换为准备编辑的历程。 | 2026年10月23日 |
| [!DNL Experience Manager] | **登陆页面** | [与同事一起创建和优化AEM登陆页面](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/brand-visibility/create-and-refine-aem-landing-page){target="_blank"} — 了解如何使用现有[!DNL Experience Manager]页面作为模板、应用营销活动内容和SEO元数据以及在通用编辑器中优化图像和副本，将营销活动简介转换为草稿登陆页面。 | 2026年10月23日 |
| [!DNL Coworker] | **警报** | [客户与Experience Platform和同事的警报](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/alerts/customer-alerts){target="_blank"} — 了解同事如何为[!DNL Experience Platform]管理员提供有关警报严重性、状态、顶级警报类型和受严重警报影响最大的对象的对话摘要，以及如何管理订阅。 | 2026年10月16日 |
| [!DNL Coworker] | **数据分析** | [通过同事、AEM和CJA加速数据洞察](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/data-insights/accelerate-data-insights){target="_blank"} — 了解[!DNL Coworker]如何连接[!DNL Experience Manager]、[!DNL Experience Platform]、Web SDK和[!DNL Customer Journey Analytics]来计划和实施实施，以便网站参与数据随时可供分析。 | 2026年10月14 |
| [!DNL Coworker] | **Experience League LIVE** | [同事已解锁](https://www.youtube.com/live/hrNuDVQFtLA){target="_blank"}：同事中的受众和历程B2C功能 | 2026年10月8 |
| [!DNL Coworker] | **营销活动** | [与同事一起计划数字营销活动启动](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/workflow-and-planning/plan-digital-campaign-launch){target="_blank"} — 了解如何通过一次聊天中构建受众、历程、内容和登陆页面来计划和启动B2C营销活动。 | 2026年10月8 |
| [!DNL Adobe Target] | **优化** | [加速使用同事、AEM和Target的试验](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/optimization/accelerate-experimentation){target="_blank"} — 查看跨产品工作流程，该流程会在WKND Magazine页面上创建一个试验，让同事协调实现目标所需的Adobe功能。 | 2026年10月8 |
| [!DNL Coworker] | **技能** | [使用数据验证技能验证数据集质量](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/data-insights/validate-dataset-quality-for-cja){target="_blank"} — 了解数据验证技能如何在构建功能板和历程之前检查Customer Journey Analytics数据集的架构、标识和字段质量问题。 | 2026年10月8 |
| [!DNL Coworker] | **技能** | [管理和迭代技能](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/customizations/skills/manage-and-iterate-on-skills){target="_blank"} — 了解如何编辑、通过基线比较进行评估以及随时间推移删除技能。 | 2026年10月8 |
| [!DNL Coworker] | **集成** | [了解同事中的集成](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/customizations/integrations/understanding-integrations-in-coworker){target="_blank"} — 获取同事中的集成导览，包括它们是什么、为什么要使用集成以及如何使用界面。 | 2026年10月8 |
| [!DNL Coworker] | **插件** | [管理您组织的插件](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/customizations/plugins/manage-plugins-for-your-org){target="_blank"} — 了解管理员如何使用批准的插件扩展同事聊天，并管理对技能和关联工具的访问。 | 2026年10月8 |

[回到顶部](#top)

### [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 提供了关于 Adobe 产品与服务的详细信息、状态更新以及电子邮件通知。 获取有关故障、中断和维护活动的通知。 在[status.adobe.com](https://status.adobe.com/zh-cn/){target="_blank"}查看状态更新。 有关新功能和修复，请参阅[[!DNL Adobe System Status] 发行说明](system-status-release-notes.md)。

有关累积的发行说明，请参阅[Adobe系统状态发行说明](system-status-release-notes.md)。

### [!DNL Adobe Experience Platform] — 最新资源 {#tutorials-aep}

有关新功能和修复，请参阅[[!DNL Experience Platform] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-platform/release-notes/latest){target="_blank"}。

### 新的AEP教程

查看[!DNL Experience Platform]的最新视频教程。

| 发布日期 | 应用程序 | 名称 | 类型 | 描述 |
| ---------- | ---------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [!DNL Experience Platform] | [AI Assistant安全概述](https://experienceleague.adobe.com/zh-hans/docs/platform-learn/tutorials/ai-assistant/security-overview){target="_blank"} | 视频 | 根据Adobe的AI Assistant安全情况说明书，大致了解Adobe Experience Platform中AI Assistant背后的安全功能。 |
| 2026 年 10 月 | [!DNL Real-Time CDP] | [监控和解决增长信用超额](https://experienceleague.adobe.com/zh-hans/docs/platform-learn/tutorials/license-usage/growth-credits/monitor-and-address-growth-credit-overage){target="_blank"} | 教程 | 了解如何在Adobe Experience Platform中监控增长信用使用情况，并在过度使用影响您的帐户之前解决过度使用问题。 |
| 2026 年 10 月 | [!DNL Real-Time CDP] | [计划流容量](https://experienceleague.adobe.com/zh-hans/docs/platform-learn/tutorials/license-usage/growth-credits/schedule-streaming-capacity){target="_blank"} | 视频 | 了解如何在重大业务事件之前安排额外的流容量，以便Experience Platform在流量激增期间保持实时服务平稳运行。 |
| 2026 年 10 月 | [!DNL Real-Time CDP] | [增长积分](https://experienceleague.adobe.com/zh-hans/docs/platform-learn/tutorials/license-usage/growth-credits/what-are-growth-credits){target="_blank"} | 视频 | 了解增长积分是什么，以及它们如何帮助Adobe Experience Platform客户在超出合同限制的情况下管理使用情况。 |
| 2026 年 10 月 | [!DNL Real-Time CDP] | [管理批次受众容量](https://experienceleague.adobe.com/zh-hans/docs/platform-learn/tutorials/license-usage/growth-credits/manage-batch-audience-capacity){target="_blank"} | 视频 | 了解如何使用增长点数来添加批量受众评估容量，以便Experience Platform能够满足营销团队的需求。 |

<!-- 
#### New [!DNL Experience Platform] support knowledge base articles{#kb-aep}

New articles and updates to existing articles for [!DNL Experience Platform].

| Published | Name | Type | Description |
| --------- | ---- | ---- | ----------- |
| June 2026 | [SFTP destination connection fails in Adobe Experience Platform](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-33771) | New article | Learn about the solutions to the issue when the SFTP destination connection fails in Adobe Experience Platform even when all required IP addresses are allow-listed and the credentials are correct because the SFTP server supports only outdated SSH key exchange algorithms that are incompatible with the validator. |
-->

### [!DNL Adobe Real-Time CDP] {#tutorials-rtcdp}

有关新功能和修复，请参阅[[!DNL Experience Platform] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-platform/release-notes/latest){target="_blank"}，其中也涵盖[!DNL Real-Time CDP]。

#### Real-Time CDP教程

查看 Real-Time CDP 的最新视频教程和支持文章。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 8 月 | [了解您的受众及其激活位置](https://experienceleague.adobe.com/zh-hans/docs/cx-enterprise-agentic-tools/using/in-action/query-audiences){target="_blank"} | 文章 | 了解如何使用通过CX [!DNL Coworker]网关连接到Real-Time CDP的AI客户端来评估受众运行状况、发现激活差距并为您的区段获取战略建议，而无需导航多个平台屏幕。 |

**更多帮助**

* 视频教程： [Real-Time CDP教程](https://experienceleague.adobe.com/zh-hans/docs/platform-learn/tutorials/rtcdp/understanding-the-real-time-customer-data-platform){target="_blank"}

* 产品文档： [Real-Time CDP](https://experienceleague.adobe.com/zh-hans/docs/real-time-customer-data-platform){target="_blank"}

### [!DNL Adobe Analytics] {#tutorials-analytics}

Adobe Analytics 的发布采用持续投放模型，从而支持更具扩展性、分阶段的功能部署方式。 发行说明每月会更新多次。 有关新功能和修复，请参阅[[!DNL Analytics] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/analytics/release-notes/latest){target="_blank"}。

#### AppMeasurement {#appm}

* [AppMeasurement for JavaScript发行说明](https://github.com/adobe/appmeasurement/releases){target="_blank"}

<!--
#### New [!DNL Analytics] support knowledge base{#kb-analytics}

New articles and updates to existing articles for [!DNL Analytics].

| Published | Name | Type | Description |
| --------- | -------- | --------- | --------- |
| February 2026 | [Data Warehouse export contains values exceeding 255 bytes due to escape sequences](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-29977){target="_blank"} | New article | Learn about the solutions to the issue when Data Warehouse export contains field values that exceed the 255-byte limit because special characters are escaped with additional backslashes. |
-->

### [!DNL Adobe Customer Journey Analytics] {#tutorials-cja}

有关新功能和修复，请参阅[[!DNL Customer Journey Analytics] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/analytics-platform/using/releases/latest?lang=en#releases){target="_blank"}。

#### [!DNL Customer Journey Analytics] 的新教程

[!DNL Customer Journey Analytics] 新发布的教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 9 月 | [在Analysis Workspace项目中将区段用作维度](https://experienceleague.adobe.com/zh-hans/docs/customer-journey-analytics-learn/tutorials/components/filters/use-filters-as-dimensions){target="_blank"} | 视频 | 了解如何在Analysis Workspace项目中将区段用作维度时比较和可视化区段。 |
| 2026 年 9 月 | [创建快速区段](https://experienceleague.adobe.com/zh-hans/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter){target="_blank"} | 视频 | 了解如何直接在您的项目中创建快速区段，以根据简单标准分段组件数据并立即查看结果。 |
| 2026 年 9 月 | [区段概述](https://experienceleague.adobe.com/zh-hans/docs/customer-journey-analytics-learn/tutorials/components/filters/introduction-to-filters-in-cja){target="_blank"} | 视频 | 了解Customer Journey Analytics中区段生成器的关键组件。 |
| 2026 年 9 月 | [浏览自由格式表中的行和列设置](https://experienceleague.adobe.com/zh-hans/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/freeform-tables/cja-explore-row-and-column-settings-in-freeform-tables){target="_blank"} | 视频 | 了解Analysis Workspace中自由格式表中的设置，以及它们如何影响进入这些表的数据。 |
| 2026 年 9 月 | [在Analysis Workspace中使用日期范围和比较](https://experienceleague.adobe.com/zh-hans/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/cja-use-date-ranges-and-comparisons){target="_blank"} | 视频 | 了解如何在项目中使用日期范围比较来分析性能。 |

#### 新的 [!DNL Customer Journey Analytics] 支持知识库{#kb-cja}

[!DNL Customer Journey Analytics] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
| --------- | ---- | ---- | ----------- |
| 2026 年 10 月 | [派生的字段容器仅限于事件、会话和人员范围](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50143) | 新文章 | 了解当Customer Journey Analytics中的派生字段函数仅支持事件、会话和人员范围容器，并且不允许维度充当容器时问题的解决方案。 |

### [!DNL Marketing Campaign Analytics]（以前称为 [!DNL Mix Modeler]） {#tutorials-mca}

[!DNL Marketing Campaign Analytics]基于[!DNL Adobe Experience Platform]构建，可衡量营销活动效果并帮助跨付费、免费和自有渠道优化营销计划。 有关新功能和修复，请参阅[[!DNL Marketing Campaign Analytics] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/marketing-campaign-analytics/using/releases/latest){target="_blank"}。

* [Marketing Campaign Analytics文档](https://experienceleague.adobe.com/zh-hans/docs/marketing-campaign-analytics/using/overview){target="_blank"}，用于查找产品概述、操作指南和发行信息。

### [!DNL Adobe Experience Manager] {#tutorials-aem}

有关新增功能和修复，请参阅[[!DNL Experience Manager] as a Cloud Service发行说明](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current){target="_blank"}。

#### [!DNL Experience Manager] 的新教程

Experience Manager as a Cloud Service的最新视频教程和支持文章。

* [最新的AEM CS发行版概述视频](https://experienceleague.adobe.com/zh-hans/events#f-el_product=Experience%20Manager%20as%20a%20Cloud%20Service){target="_blank"}

为 [!DNL Experience Manager as a Cloud Service] 发布了新的视频和图文教程（文章）。

| 发布日期 | 应用程序 | 名称 | 格式 | 描述 |
| ---------- | ---------- | ---------- | ---------- | ---------- |
| 2026年11 | [!DNL AEM Assets] | [处理轮廓](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/authoring/processing-profiles){target="_blank"} | 视频 | 了解如何在AEM Assets中处理用户档案。 |
| 2026年11 | [!DNL AEM Assets] | [设置和配置品牌感知元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/metadata/brand-aware-metadata#set-up-and-configure-brand-aware-metadata){target="_blank"} | 视频 | 了解如何在AEM Assets中设置和配置品牌感知元数据。 |
| 2026 年 10 月 | [!DNL AEM Sites] | [Adobe LLM应用概述](https://experienceleague.adobe.com/zh-hans/docs/llm-apps/using/overview){target="_blank"} | 视频 | 了解什么是Adobe LLM应用程序以及它可以为您的品牌做什么。 |
| 2026 年 10 月 | [!DNL AEM Forms] | [创建通用映射组件以显示按状态提交的表单](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/cloud-service/forms/generic-map-component/introduction){target="_blank"} | 代码示例 | 了解如何在AEM Sites中构建通用的交互式USA映射组件，该组件可按状态显示表单提交。 |
| 2026 年 10 月 | [!DNL AEM Sites], [!DNL AEM Assets], [!DNL AEM Forms] | [通过OpenTelemetry的可观察性概述](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/cloud-service/observability-via-opentelemetry/opentelemetry-in-aem){target="_blank"} | 文章 | 了解AEM as a Cloud Service中通过OpenTelemetry实现什么可观察性，以及为何使用、何时使用以及如何使用。 |
| 2026 年 10 月 | [!DNL AEM Sites], [!DNL AEM Assets], [!DNL AEM Forms] | [配置OpenTelemetry以深入了解AEM应用程序](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/cloud-service/observability-via-opentelemetry/configure-opentelemetry){target="_blank"} | 教程 | 了解如何在AEM as a Cloud Service中设置OpenTelemetry，包括YAML配置文件、Cloud Manager密钥、配置管道和验证。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [管理权限](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/governance/permissions-management){target="_blank"} | 视频 | 了解如何在AEM Assets Assets视图中管理权限和访问权限。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [管理对AEM Assets的访问](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/governance/grant-access){target="_blank"} | 视频 | 了解如何授予和管理AEM Assets的访问权限。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [Assets视图中的智能标记和分类管理](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/metadata/tagging-and-taxonomy){target="_blank"} | 视频 | 了解智能标记、如何阻止不需要的智能标记，以及如何在AEM Assets Assets视图中管理和使用标记分类。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [品牌感知元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/metadata/brand-aware-metadata){target="_blank"} | 视频 | 了解AEM Assets提示编辑器如何通过AI生成的品牌感知元数据自动增强您的资源。 |
| 2026 年 10 月 | [!DNL AEM Sites], [!DNL AEM Forms] | [使用Co-worker创建带有自适应表单的AEM Sites联系页面](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/cloud-service/forms/aem-forms-coworker/using-coworker-with-aem-forms){target="_blank"} | 文章 | 了解如何使用同事构建一个嵌入了自适应表单的AEM Sites联系我们页面，该页面包括一个自动填充城市和州的邮政编码查找功能和一个在Azure Storage中存储数据的提交流程。 |
| 2026 年 10 月 | [!DNL AEM Sites] | [使用CX Enterprise Coworker创作AEM Sites页面](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/brand-visibility/author-web-pages){target="_blank"} | 视频 | 了解CX Enterprise Coworker如何帮助您在AEM Sites页面上创作新体验，包括使用可视化内容片段创建主页促销活动。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [与同事一起在AEM Assets中载入您的品牌](https://experienceleague.adobe.com/zh-hans/docs/coworker/content/chat/use-cases/brand-visibility/onboard-aem-assets){target="_blank"} | 视频 | 了解如何使用同事在AEM Assets中设置和配置DAM。 |
| 2026 年 10 月 | [!DNL AEM Assets] | Assets视图中的[元数据表单](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/metadata/metadata-schemas-and-forms){target="_blank"} | 视频 | 了解如何在AEM Assets Assets视图中配置和使用元数据表单。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [使用资源视图](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/overview#browse-search-and-download-assets-in-the-assets-view){target="_blank"} | 视频 | 了解在AEM Assets Assets视图中浏览、搜索和下载资源的基础知识。 |
| 2026 年 10 月 | [!DNL AEM Forms] | 使用Microsoft Entra [安全AEM Forms门户](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/cloud-service/forms/aem-with-entra-id/secure-forms-portal-wth-entra){target="_blank"} | 教程 | 了解如何使用AEM Forms Entra ID保护Microsoft Portal的安全。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [AEM Assets Assets视图中的Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/asset-distribution/dynamic-media){target="_blank"} | 视频 | 了解如何在AEM Assets Assets视图中查看Dynamic Media演绎版。 |
| 2026 年 10 月 | [!DNL AEM Assets] | [Assets查看报表和分析](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-learn/assets/governance/insights){target="_blank"} | 视频 | 了解如何使用AEM Assets Assets视图中的分析和报表来了解资源使用情况。 |

#### 新的 [!DNL Experience Manager] 支持知识库{#kb-aem}

[!DNL Experience Manager] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
| --------- | -------- | --------- | --------- |
| 2026 年 10 月 | [在AEM Dynamic Media中批量删除产品图像中的阴影和背景](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43970) | 新文章 | 了解当AEM Dynamic Media中的产品图像包含不需要的阴影或背景时，您需要以编程方式批量删除这些阴影或背景的问题解决方案。 |
| 2026 年 10 月 | [在Dynamic Media Classic中将[!UICONTROL 发布的服务器名称]从HTTP更新为HTTPS](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43612) | 新文章 | 了解当您的Dynamic Media Classic生产实例中的[!UICONTROL 发布的服务器名称]使用HTTP而不是HTTPS，并且您需要对其进行更新以便安全交付资产时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service Dynamic Media：当预设正则表达式包含文件扩展名](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43268)时，不会创建多轴旋转集 | 新文章 | 了解当多轴旋转集未在AEM as a Cloud Service Dynamic Media中使用批次集预设自动创建时，即使资产同步到Dynamic Media Classic成功的解决方案。 |
| 2026 年 10 月 | [DAM资产未同步到Dynamic Media或生成智能裁剪](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43319) | 新文章 | 了解当在AEM Managed Services中上传到DAM的资产未同步到Dynamic Media，并且没有为受影响的资产生成智能裁剪时问题的解决方案。 |
| 2026 年 10 月 | AEM as a Cloud Service中的[复制代理和Dynamic Media设置](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43603) | 新文章 | 了解复制代理在AEM as a Cloud Service创作环境中的[!UICONTROL 工具] > [!UICONTROL 部署]下不可见或不可访问时的问题的解决方案，您需要有关配置和配置Dynamic Media Cloud Service帐户和管理员的指导。 |
| 2026 年 10 月 | 迁移到AEM as a Cloud Service后[重新处理Dynamic Media资源](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43993) | 新文章 | 当您不确定在使用内容传输工具从本地AEM迁移到AEM as a Cloud Service后是否需要重新处理Dynamic Media资源时，了解该问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms 6.5 LTS：在SP24升级后，由于缺少启动委派项，PDF生成失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-34137) | 新文章 | 了解在升级到Service Pack 24后，当您尝试在AEM Forms 6.5 LTS中调用PDF生成服务时因服务器错误而失败时，该问题的解决方案。 |
| 2026 年 10 月 | 当 [!DNL CloudFront] 原始策略不转发查询参数时，[AEM请求会丢失这些参数](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42654) | 新文章 | 了解当包含查询参数的请求在启动新域或更新现有域和CDN配置后在AEM网站上返回错误（例如缺少所需的参数）时问题的解决方案。 |
| 2026 年 10 月 | [在AEM 6.5.2](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42709)的内容片段RTE中显示双边框 | 新文章 | 了解当您在AEM 6.5.2 LTS中编辑内容片段时富文本编辑器周围出现双边框时问题的解决方案。 |
| 2026 年 10 月 | 加载权限时[AEM Managed Services登录暂停，阻止 [!DNL Synoptryx] 访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43099) | 新文章 | 了解当AEM Managed Services Monitoring Tools登录页面在加载权限时保持停滞状态并且不显示错误消息时问题的解决方案。 |
| 2026 年 10 月 | [Dynamic Media基本演绎版URL在AEM中包含不需要的查询参数](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43121) | 新文章 | 了解当AEM中的Dynamic Media基本演绎版URL默认包含查询参数（例如`width`、`quality`或`assetName`），并且下游系统或集成需要不包含这些参数的URL时，该问题的解决方案。 |
| 2026 年 10 月 | 在AEM Sites中嵌入Edge Delivery Services内容时出现[间歇性CORS违规](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43125) | 新文章 | 了解当嵌入到AEM Sites中的Edge Delivery Services资源的请求因CORS策略违规而间歇性失败，并且浏览器控制台错误指示与CORS相关的失败时，该问题的解决方案。 |
| 2026 年 10 月 | 启用SDI时，AEM导航中显示[未经授权的菜单项](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43139) | 新文章 | 了解当AEM中的自定义导航组件显示未经授权的菜单项，因为启用Sling动态包含(SDI)后它丢失原始页面上下文时，此问题的解决方案。 |
| 2026 年 10 月 | [ContextHub工具栏与Adobe Experience Manager创作UI中的侧面板重叠](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43145) | 新文章 | 了解当您在[!UICONTROL 预览]和[!UICONTROL 编辑]模式之间切换后，AEM创作UI中的ContextHub工具栏未正确定位并与侧面板重叠时问题的解决方案。 |
| 2026 年 10 月 | [自定义域缺少中间SSL证书颁发机构](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43149) | 新文章 | 了解当浏览器显示不受信任的证书警告、发生SSL/TLS握手错误以及SSL测试工具报告AEM中自定义域的证书链不完整或不受信任时，此问题的解决方案。 |
| 2026 年 10 月 | [复制队列在AEM Author](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43153)中有一个挂起项卡住 | 新文章 | 了解当AEM创作实例上的复制队列显示队列活动 — 1个挂起并且复制作业不进度时，甚至在您刷新队列、强制重试或禁用并重新启用复制代理后，此问题的解决方案。 |
| 2026 年 10 月 | [AEM LTS升级后，无法将标记添加到PDF文档](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43181) | 新文章 | 了解在长期支持(LTS)升级后，当用户无法在AEM中向PDF文档添加标记时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43193)中访问 [!DNL SAP] 文档主机时出现&#x200B;*未知主机异常*&#x200B;错误 | 新文章 | 了解当AEM无法解决[!DNL SAP]文档主机的主机名且请求失败并出现&#x200B;*java.net.UnknownHostException*&#x200B;错误时的问题的解决方案。 |
| 2026 年 10 月 | 在AEM Brand Portal中[管理员访问请求通知](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43202) | 新文章 | 了解当更多管理员收到来自AEM Brand Portal的访问请求电子邮件通知时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中登录期间[MNPR身份验证失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43246) | 新文章 | 了解当MNPR用户无法通过AEM中的MNPR登录页面登录，因为在密码和组验证之前身份验证失败（即使用户出现在用户管理界面中）时，该问题的解决方案。 |
| 2026 年 10 月 | 在AEM中LTS升级期间出现[紧急JDK修补问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43256) | 新文章 | 了解当您收到有关紧急JDK 8和JDK 11修补的安全公告时，该问题的解决方案，并需要了解它在LTS升级期间对生产和非生产AEM Managed Services实例的影响。 |
| 2026 年 10 月 | 在AEM Cloud Manager中升级管道版本后，[管道部署失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43258) | 新文章 | 了解当AEM Cloud Manager部署管道在管道版本升级后反复失败或长时间保持运行状态（即使之前成功构建了相同的代码）时，该问题的解决方案。 |
| 2026 年 10 月 | [用户尽管拥有编辑权限，但在Adobe Experience Manager中无法编辑体验片段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43300) | 新文章 | 了解当用户尽管拥有编辑权限，但在AEM中无法编辑体验片段，组件浏览器面板缺失或折叠，并且体验片段创建页面显示空白时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM：编辑资源元数据时，出现Assets已移除或无法访问的错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43304) | 新文章 | 了解出现&#x200B;*错误：某些资产被删除或不可访问时问题的解决方案。 请刷新资源并重试。* 某些用户在AEM中编辑和保存资源元数据时，会间歇性地显示消息。 |
| 2026 年 10 月 | 由于组筛选器语法不正确，[LDAP身份验证失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43342) | 新文章 | 了解当您无法通过AEM中的[!DNL Active Directory] LDAP身份验证登录并且AD组同步未按预期发生时问题的解决方案。 |
| 2026 年 10 月 | [AEM资源选择器：导入PDF资源时出现&#x200B;*上载失败*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43352) | 新文章 | 了解在使用AEM资产选择器导入特定PDF资产时，如果其他PDF资产导入成功，则导入失败并出现&#x200B;*上传失败*&#x200B;错误，此问题的解决方案。 |
| 2026 年 10 月 | [解决在Adobe Experience Manager中访问generatePdf API时&#x200B;*401未经授权*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43360) | 新文章 | 了解当在AEM中访问`generatePdf` API的应用程序收到&#x200B;*HTTP 401未授权*&#x200B;错误并且无法打开或生成PDF文件时问题的解决方案。 |
| 2026 年 10 月 | [解决由于大型资源请求的线程耗尽而导致的AEM生产中断问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43380) | 新文章 | 了解当大量并发请求未在Dispatcher层缓存的大型视频资产时，耗尽了AEM Publish上的请求处理线程并导致生产中断时，问题的解决方案。 |
| 2026 年 10 月 | [从Adobe Experience Manager发布实例中删除孤立的资源](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43384) | 新文章 | 了解从创作环境中删除资源后，资源仍保留在AEM发布实例上的问题的解决方案。 |
| 2026 年 10 月 | 维护后[在AEM Stage上解决 [!DNL CloudFront] 403和503错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43453) | 新文章 | 了解当AEM Stage环境的公共端点在计划维护后返回[!DNL CloudFront] HTTP 403或503错误，而对Apache/Dispatcher和AEM的直接请求返回HTTP 200响应时，此问题的解决方案。 |
| 2026 年 10 月 | [AEM Managed Services：过渡到每月的安全修补节奏](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43455) | 新文章 | 了解当AEM Managed Services安全修补计划从2026年9月1日起每季度更改到每月时，这个问题的解决方案，并且您需要为新的节奏做好准备。 |
| 2026 年 10 月 | [作者登录在Adobe Experience Manager](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43495)中显示&#x200B;*意外系统错误* | 新文章 | 了解当AEM作者登录页面上显示&#x200B;*意外系统错误*&#x200B;而不是“用户名和密码”提示并在服务器重新启动后持续存在时问题的解决方案。 |
| 2026 年 10 月 | [已发布的页面在Adobe Experience Manager中返回404错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43501) | 新文章 | 了解当页面无法从AEM创作环境发布到发布环境并在公共站点上访问它们时返回&#x200B;*404 Not Found*&#x200B;错误时问题的解决方案。 |
| 2026 年 10 月 | 通过Adobe Experience Manager中的域URL访问页面时[UI失真](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43503) | 新文章 | 了解当通过域URL访问时，由于客户端库资源加载失败并出现HTTP 404错误，AEM Sites中的页面显示UI损坏或扭曲时，此问题的解决方案。 |
| 2026 年 10 月 | 由于DNS解析错误，[[!DNL Groovy] 控制台无法在Adobe Experience Manager中启动](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43511) | 新文章 | 了解在非生产AEM环境中通过标准URL访问[!DNL Groovy]控制台时导致出现DNS错误，并指明域名无法解析的问题解决方案。 |
| 2026 年 10 月 | [如何清除Adobe Experience Manager中特定内容路径的Dispatcher缓存](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43525) | 新文章 | 了解当最近发布的内容或更新内容对最终用户不可见时（因为AEM Dispatcher提供过时的缓存版本）问题的解决方案。 |
| 2026 年 10 月 | [AEM Dispatcher：由于/etc.clientlibs缓存失效，未反映网站更改](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43527) | 新文章 | 了解当最近的网站更改（例如更新横幅或脚本）对最终用户不可见时（因为AEM Dispatcher在`/etc.clientlibs`下提供过期的缓存内容）这个问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager中解锁锁定的产品详细信息页面](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43532) | 新文章 | 了解当AEM中的产品详细信息页面(PDP)被锁定，从而阻止编辑或发布并阻止对时间敏感的活动（如产品发布）时的问题的解决方案。 |
| 2026 年 10 月 | 脱机存储库压缩后，[AEM产品导入失败，出现“命名空间前缀无效”](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43575) | 新文章 | 了解当AEM中的产品导入和保存操作失败并出现&#x200B;*OakName0001时，该问题的解决方案：离线存储库压缩后命名空间前缀无效*&#x200B;错误。 |
| 2026 年 10 月 | [AEM：使用SSO预览内容时，作者提示登录](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43579) | 新文章 | 了解当作者从AEM创作中打开预览环境时，即使配置了单点登录(SSO)，系统仍提示他们再次登录时问题的解决方案。 |
| 2026 年 10 月 | [Dynamic Media Scene7：二进制交换后未发布资产的预览渲染失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43596) | 新文章 | 了解在二进制交换后，当AEM Dynamic Media中的一批未发布的创作端资源的预览渲染失败时（即使`req=imageprops`返回正确的当前图像属性），该问题的解决方案。 |
| 2026 年 10 月 | [AEM Core和B2B-Core包在部署后未处于活动状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43608) | 新文章 | 了解当核心捆绑包和B2B核心捆绑包在AEM中的部署后保持不活动并且应用程序不可访问且没有特定错误消息时的问题解决方案。 |
| 2026 年 10 月 | [解析AEM MSM翻译工作流中的&#x200B;*进程资源为null*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43611) | 新文章 | 了解AEM MSM翻译项目保持在[!UICONTROL 草稿]状态、未提交到外部翻译提供商且日志显示&#x200B;*进程资源为null*&#x200B;错误时的问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager Managed Services中的Dispatcher刷新代理上解析&#x200B;*500服务器错误*](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43639) | 新文章 | 了解当AEM Managed Services中的Dispatcher刷新代理在与无响应的发布实例通信时报告&#x200B;*500服务器错误*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | [解决AEM中自定义索引选择导致的内容同步问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43646) | 新文章 | 了解当从AEM Author发布的内容未显示在Publisher上或组件在Publisher上返回的结果少于在Author上返回的结果或返回的结果已过期时（即使复制和缓存刷新代理正常运行）问题的解决方案。 |
| 2026 年 10 月 | [临时增加高流量事件的AEM生产创作容量](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43663) | 新文章 | 了解当您预计在大流量事件期间AEM生产创作环境性能缓慢或中断并且需要临时增加其容量时的问题的解决方案。 |
| 2026 年 10 月 | [由于AEM云站点中的收件人组为空，未发送电子邮件通知](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43673) | 新文章 | 了解当目标收件人在非生产AEM Cloud Sites环境中未收到工作流电子邮件通知，而同一工作流在生产环境中按预期发送电子邮件时，该问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager Managed Services中的慢结果页疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43677) | 新文章 | 了解当AEM Managed Services中的网页速度缓慢或间歇性不可访问、发布者实例显示关键或不健康状态，以及特定结果页面或搜索端点增加响应时间时问题的解决方案。 |
| 2026 年 10 月 | [由于CDN缓存，](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43745)已发布的页面更新或重定向在AEM中不会立即可见 | 新文章 | 了解当生产网站上看不到最近发布的AEM页面更改或更新重定向，且用户收到过时的内容或错误的重定向时，问题的解决方案。 |
| 2026 年 10 月 | [[!DNL Akamai] 源证书不匹配导致AEM中的SSL握手失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43748) | 新文章 | 了解当[!DNL Akamai]连接到AEM原始服务器并且用户无法通过[!DNL Akamai]访问AEM站点时，出现CN/SAN不匹配错误的SSL握手失败的问题解决方案。 |
| 2026 年 10 月 | [如何清除Adobe Experience Manager中的Dispatcher缓存](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43749) | 新文章 | 了解当AEM中的最新内容更改由于Dispatcher缓存提供过时版本的内容而未显示在实时站点上时问题的解决方案。 |
| 2026 年 10 月 | [从 [!DNL iPhone] 设备访问Adobe Experience Manager中的/bin/aforbes/pdf端点时解决503错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43756) | 新文章 | 了解当从[!DNL iPhone]设备向AEM Forms中的`/bin/aforbes/pdf`端点发出的请求返回&#x200B;*HTTP 503服务不可用*&#x200B;错误并显示&#x200B;*失败： DocAssuranceService不可用*&#x200B;消息时，此问题的解决方案。 |
| 2026 年 10 月 | 用于迁移静态AEM Sites页面的[HTML架构指南](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43774) | 新文章 | 了解问题的解决方案，此时您需要将大约100个不需要编辑的静态HTML和CSS页面迁移到AEM Sites中，同时保留现有布局。 |
| 2026 年 10 月 | [更新AEM中全部不匹配通知的收件人电子邮件地址](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43783) | 新文章 | 了解在需要更改AEM在理赔检测到完全不匹配条件时发送的通知的收件人电子邮件地址时该问题的解决方案。 |
| 2026 年 10 月 | [重命名AEM中内容片段变量的内部名称](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43791) | 新文章 | 了解在AEM内容片段编辑器中重命名内容片段变体时，仅更新其显示标签(`jcr:title`)，而`jcr:content/data`下的内部变体名称保持不变，此问题的解决方案。 |
| 2026 年 10 月 | [请求IMS客户端ID和作用域以将Adobe内容顾问与CMS集成](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43817) | 新文章 | 了解当您由于缺少IMS凭据而无法完成Adobe Content Advisor与第三方CMS的集成时，以及资产浏览和引用功能在CMS中不可用的问题的解决方案。 |
| 2026 年 10 月 | [AEM Publisher中未通过GET请求提供受保护的PDF](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43826) | 新文章 | 了解AEM Publisher未通过HTTP GET请求正确提供受保护的PDF文件，并且无法按预期下载或查看这些文件时问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager中封闭页面访问问题的疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43828) | 新文章 | 了解当AEM生产环境中的封闭页面在登录后呈现或加载速度不很慢，并出现错误或行为（例如&#x200B;*请求过多*、SAML重定向循环或&#x200B;*对此页面的访问受限制*）时，该问题的解决方案。 |
| 2026 年 10 月 | 在操作系统修补后[AEM Publisher在&#x200B;*SegmentNotFoundException*&#x200B;之后显示不正确的内容](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43836) | 新文章 | 了解当AEM Managed Services Publisher实例在修补操作系统后显示过时或不正确的内容，阻止向其复制内容，并在日志中显示&#x200B;*SegmentNotFoundException*&#x200B;错误时，该问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager生产上线期间疑难解答&#x200B;*503服务不可用*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43841) | 新文章 | 了解当AEM生产网站在上线部署等重要事件期间返回&#x200B;*503服务不可用*&#x200B;错误并变得无法访问时问题的解决方案。 |
| 2026 年 10 月 | [在AEM中执行JDK修补程序后，还原JDK密钥库中缺少的证书](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43867) | 新文章 | 了解当AEM创作和发布实例无法建立HTTPS连接且在JDK修补程序后出现与缺少证书相关的错误时，该问题的解决方案。 |
| 2026 年 10 月 | 由于.content.xml中的属性名称无效，[AEM包上载失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44397) | 新文章 | 了解在上载包含PDF资源的AEM包时问题的解决方案，该问题导致上传失败，因为该资源的`.content.xml`包含以数字开头的属性名称，未导入该资源，并且日志显示&#x200B;*DocViewParser$XmlParseException*&#x200B;错误。 |
| 2026 年 10 月 | 由于等待输入，[AEM Managed Services生产管道部署已取消](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48480) | 新文章 | 了解在等待客户长时间输入后取消通过AEM Managed Services管道部署生产代码时问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets：由于MIME类型配置，自定义资源类型筛选器未显示任何结果](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48483) | 新文章 | 了解当AEM Assets视图中的自定义[!UICONTROL 资源类型]筛选器未返回任何类型（例如配置为`document/*`的文档）的结果时问题的解决方案，即使存在这些类型的资源也是如此。 |
| 2026 年 10 月 | [AEM防火墙迁移和IP地址更改： Adobe 列入允许列表要求](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48498) | 新文章 | 了解当[!DNL Azure]环境中的防火墙迁移更改您的非生产和生产IP地址，并且您不确定是否需要在Adobe系统上管理新的IP地址时问题的解决方案。 |
| 2026 年 10 月 | [由于缺少库，Forms无法在AEM 6.5 LTS SP2的代理UI中打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48567) | 新文章 | 了解当您在[!DNL Linux]上的AEM 6.5 LTS SP2中使用带有示例数据的[!UICONTROL 预览]时，当表单未在代理UI中呈现或打开时，以及受影响服务器上缺少`libX11.x86_64`、`libxcb.x86_64`和`libXau.x86_64`库时，该问题的解决方案。 |
| 2026 年 10 月 | 在UI测试期间，[AEM Cloud Manager暂存部署失败，出现&#x200B;*OOMKilled*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48606) | 新文章 | 了解当AEM Cloud Manager暂存部署在UI测试阶段持续失败，并且日志显示&#x200B;*容器退出时带有非零退出代码： 137，原因： OOMKilled*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager生成的PDF中缺少图像和中文字体](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48660) | 新文章 | 了解从AEM中的富文本字段生成的PDF不显示嵌入的图像并将中文字符显示为空格或不可读符号时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：环境变量更改后管道重新执行](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48667) | 新文章 | 了解当您不确定在AEM as a Cloud Service中更新环境变量后是否需要重新执行全栈、配置或Web层(Dispatcher)管道时问题的解决方案。 |
| 2026 年 10 月 | 访问流量量度时出现[Dynamic Media Classic带宽错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48687) | 新文章 | 了解当在Dynamic Media Classic中查看带宽或流量指标时，如果错误消息间歇性出现，并且您无法检索每天或每月请求数，该问题的解决方案。 |
| 2026 年 10 月 | AEM Managed Services中仅[Dispatcher部署管道的可用性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48735) | 新文章 | 了解当AEM Managed Services通过Cloud Manager一起构建和部署所有应用程序和Dispatcher配置模块时，该问题的解决方案，并且没有选项只能独立部署Dispatcher更改。 |
| 2026 年 10 月 | [AEM内部部署：由于磁盘空间不足，区段存储清理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48790) | 新文章 | 了解当本地AEM 6.5.21发布服务器上的区段存储大小增长到接近文件系统限制以及自动修订清理（TarMK压缩）因可用磁盘空间不足而失败时，该问题的解决方案。 |
| 2026 年 10 月 | [Dynamic Media：未使用quality参数和preferwebp=true减小PNG文件大小](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48867) | 新文章 | 了解通过扩展名为`.png`且参数为`preferwebp=true`的Dynamic Media URL投放的图像在文件大小方面仍保持较大时问题的解决方案，即使`quality`参数设置为低于85也是如此。 |
| 2026 年 10 月 | 由于diff.json格式不正确，[AEM自定义索引在SIM部署后显示/dummy路径](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49182) | 新文章 | 了解当AEM中的所有完全自定义索引都将`/dummy`显示为路径，并在您使用智能索引管理(SIM)工具部署这些索引后有效停用的问题解决方案。 |
| 2026 年 10 月 | 升级到AEM SDK 2026.9.28386[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49184)后单元测试失败 | 新文章 | 了解当本地[!DNL Maven]构建在升级到AEM SDK 2026.9.28386后有大量先前通过的单元测试失败，并出现&#x200B;*NoClassDefFoundError*&#x200B;或&#x200B;*NoSuchMethodError*&#x200B;等错误时，该问题的解决方案。 |
| 2026 年 10 月 | 适用于Edge Delivery Services的[AEM代码同步应用域兼容性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49212) | 新文章 | 如果不清楚Edge Delivery Services的AEM Code Sync应用是否支持`github.com`以外的Git存储库域（如[!DNL GitHub Enterprise Server]、[!DNL Bitbucket]、[!DNL GitLab]或[!DNL Azure DevOps]），请了解此问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager中创建ACL的最佳实践](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49216) | 新文章 | 了解您需要有关在AEM中创建和管理ACL的最佳实践的指导时问题的解决方案。 |
| 2026 年 10 月 | [Dynamic Media：WebP格式不支持C2PA元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49242) | 新文章 | 了解C2PA元数据未保留在Dynamic Media以WebP格式交付的图像中的问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service中创建[RDE失败，并启用了参考演示加载项](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49264) | 新文章 | 了解当在AEM as a Cloud Service中创建快速开发环境(RDE)的尝试失败且没有特定错误消息时，以及在项目配置中启用参考演示加载项时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：正在解决Oak索引diff.json](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49418)的PackageOverlaps警告 | 新文章 | 了解当Cloud Manager代码质量步骤报告`/oak:index/diff.index`的&#x200B;*PackageOverlaps*&#x200B;警告时问题的解决方案，因为多个子项目将自己的`diff.json`文件交付到AEM as a Cloud Service中的同一存储库路径。 |
| 2026 年 10 月 | [AEM as a Cloud Service和 [!DNL Citrix NetScaler ADC/Gateway] 漏洞(CVE-2026-88771、CVE-2026-88772)](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-49455) | 新文章 | 了解当安全团队担心关键[!DNL Citrix NetScaler ADC]和[!DNL Citrix NetScaler Gateway]漏洞CVE-2026-88771和CVE-2026-88772是否会影响AEM as a Cloud Service时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service Dynamic Media：资源重新发布后缺少演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49535) | 新文章 | 了解当在AEM as a Cloud Service生产环境中完全重新发布或重新处理某些资源后缺少某些Dynamic Media演绎版（例如SwatchThumbnail）时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：自动页面版本清除配置](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49543) | 新文章 | 了解当您在AEM as a Cloud Service中配置和启用自动页面版本清除功能时遇到问题时，该问题的解决方案，包括保留的最大版本、最大版本保留时间和最小版本对应的值。 |
| 2026 年 10 月 | [AEM：特殊字符在 [!DNL Proxima Nova] font](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49588)的Teaser标题中无法正确呈现 | 新文章 | 了解当特殊字符（如e）与使用[!DNL Proxima Nova]字体的AEM Teaser标题中的其他字符出现格式不同时问题的解决方案。 |
| 2026 年 10 月 | [AEM 6.5.21与 [!DNL Oracle] JDK 8u503](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49595)的兼容性 | 新文章 | 了解当您出于安全原因并需要确认兼容性而计划将AEM 6.5.21从[!DNL Oracle] JDK 8u451升级到JDK 8u503时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：组件在本地部署，但由于SDK版本不匹配而不在Cloud中部署](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49623) | 新文章 | 了解当自定义组件在本地AEM Cloud SDK实例上成功部署，但在管道部署到AEM as a Cloud Service环境后未显示时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：复制API的行为setSynchronous(true)标志](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49814) | 新文章 | 当您不确定复制API中的`setSynchronous(true)`标记在AEM as a Cloud Service中可保证什么（包括发布实例上是否已存在内容）时，了解问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms Cloud Service： [!DNL reCAPTCHA Enterprise] 基于得分的阈值阻止重复提交](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49850) | 新文章 | 了解当使用基于分数的[!DNL Google reCAPTCHA Enterprise]的AEM Forms as a Cloud Service自适应表单从同一设备重复提交未通过验证时（因为该服务返回低分），该问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中配置自定义同义词文件简化了索引管理](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49888) | 新文章 | 了解将自定义索引迁移到AEM as a Cloud Service中的简化索引管理并需要支持索引分析器配置中的自定义同义词文件时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：内容复制后未重新处理Dynamic Media资源](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49894) | 新文章 | 了解当与内容副本一起复制的Dynamic Media资产显示在目标AEM as a Cloud Service环境的DAM中，但未根据其Dynamic Media配置进行处理，未在AEM Author中或前端中渲染，并且缺少智能裁剪时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM 6.5 TarMK冷备用： HTTP 503 *缺少AuthenticationSupport服务*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49908) | 新文章 | 了解在内部部署AEM 6.5中访问TarMK冷备用实例上的`/aem/start.html`时，在将主实例同步到备用实例后返回HTTP 503 *AuthenticationSupport服务缺失*&#x200B;错误时问题的解决方案。 |
| 2026 年 10 月 | 更改CNAME后[AEM Cloud Manager SSL证书续订失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49989) | 新文章 | 了解在导入续订的SSL证书或更新域映射以使其使用时，在AEM Cloud Manager中更改CNAME后失败的问题的解决方案。 |
| 2026 年 10 月 | [在AEM的Adobe Granite Bearer身份验证处理程序中配置多个路径](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50017) | 新文章 | 了解当AEM中适用于OAuth的Adobe Granite Bearer身份验证处理程序的[!UICONTROL Path]属性似乎只接受单个API路径时问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service的[!UICONTROL 体验审核概述]中[生产环境不可用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50083) | 新文章 | 了解当Cloud Manager中的[!UICONTROL 体验审核概述]的“环境”下拉列表中未显示生产环境，并且您无法查看其审核趋势或报告时问题的解决方案。 |
| 2026 年 10 月 | 由于不存在路径上的RepoInit ACL，[AEM as a Cloud Service Dev管道失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50099) | 新文章 | 了解当AEM as a Cloud Service Dev管道在`PREPARE_CONTENT/author`步骤期间失败，并出现错误&#x200B;*无法设置来自自定义RepoInit块的不存在路径的ACL*&#x200B;和&#x200B;*javax.jcr.PathNotFoundException*&#x200B;时，该问题的解决方案。 |
| 2026 年 10 月 | 由于不支持的Maven工具链，[AEM Cloud Manager暂存管道生成失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50115) | 新文章 | 了解当AEM Cloud Manager暂存管道构建失败不一致，且没有特定错误消息或栈栈跟踪时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms as a Cloud Service：正在解决因 [!DNL SLF4J] 依赖项不匹配而导致的包未解析错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50267) | 新文章 | 了解当在本地AEM Forms开发环境中安装AEM Forms附加组件包后，有多个AEM as a Cloud Service包保持在[!UICONTROL 已安装]状态而不是[!UICONTROL 活动]状态，并且日志显示依赖项错误&#x200B;*com.adobe.aem.dermis.aem-dermis-core需要： org.slf4j.spi >=1.7.0和&lt;2.0.0*&#x200B;时，问题的解决方案。 |
| 2026 年 10 月 | [AEM：没有为专家级帐户分配技术帐户经理](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50401) | 新文章 | 了解当您请求获取有关分配给您的专家级AEM帐户的技术客户经理的信息并且该帐户没有专门的TAM时，问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets：由于维护计划程序更新，WorkflowPurge日志超出计划时间](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50465) | 新文章 | 了解与WorkflowPurge相关的日志条目在超出配置计划的时间出现在AEM Assets `error.log`中的问题解决方案。 |
| 2026 年 10 月 | [如何在AEM Dispatcher筛选器规则中指定选择器](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50477) | 新文章 | 了解当您需要限制或允许在AEM Dispatcher筛选器规则中使用选择器（例如`search`或`children`）的请求时问题的解决方案，不清楚是否指定带有前导点的选择器。 |
| 2026 年 10 月 | [AEM as a Cloud Service CDN边缘IP地址用法](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50509) | 新文章 | 了解问题的解决方案，当您需要确定由DNS查找返回的与AEM as a Cloud Service集成的域的IP地址是专用于一个租户，还是跨Adobe的CDN基础设施共享时。 |
| 2026 年 10 月 | [AEM：通过[!UICONTROL 快速发布]发布的意外页面（由于引用链接）](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50736) | 新文章 | 了解对AEM中的特定页面使用[!UICONTROL Quick Publish]时问题的解决方案，该页面还会发布您未选择的其他页面和模板策略。 |
| 2026 年 10 月 | [AEM：尽管已编制索引，搜索结果中未返回博客文章](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50805) | 新文章 | 了解当某些AEM博客文章可通过其URL访问，但在您按其完整显示的标题进行搜索时不会显示在搜索结果中时的问题解决方案。 |
| 2026 年 10 月 | [AEM Assets管理员视图语言筛选器返回的资源元数据语言不正确](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50829) | 新文章 | 了解当AEM Assets管理视图中的[!UICONTROL 语言]过滤器返回语言元数据不同于所选值的资源时问题的解决方案。 |
| 2026 年 10 月 | 针对没有企业存储的非活动用户的[AEM内容保留策略通知](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50842) | 新文章 | 了解当您收到一封关于非活动用户的内容保留策略的通知电子邮件，指出他们的内容将在30天后删除，并且您不确定哪些内容受影响或是否需要执行操作时，此问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service日志轮换和保留 [!DNL Azure Blob Storage]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50925) | 新文章 | 了解当转发到[!DNL Azure Blob Storage]的AEM as a Cloud Service日志文件数日持续增长时问题的解决方案，不清楚日志轮换是基于时间、基于大小还是由面板更改触发。 |
| 2026 年 10 月 | [Adobe Experience Manager： DAM审核日志清除无法清除APPROVED或PREVIEW审核条目](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50983) | 新文章 | 了解当AEM as a Cloud Service中的标准审核日志清除无法删除使用Dynamic Media时记录的APPROVED或PREVIEW审核日志条目时问题的解决方案。 |
| 2026 年 10 月 | [未在Content Advisor呈现版本中应用Dynamic Media图像修饰符](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51081) | 新文章 | 了解当在Content Advisor中选择具有Dynamic Media演绎版的资源后，图像修饰符（如`rotate=90`）未更新图像预览并且仅显示基本演绎版时，问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：工作流清除计划程序激活和计时](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51464) | 新文章 | 了解这个问题的解决方案，即当您在AEM as a Cloud Service中部署工作流清除计划程序组件配置后，Developer Console中的该组件显示[!UICONTROL 激活延迟]状态，并且清除任务何时运行尚不清楚。 |
| 2026 年 10 月 | [AEM LTS SP03：使用自定义环境后未出现文件上传弹出窗口](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51507) | 新文章 | 了解在自定义AEM环境中操作并启动标准环境后，从本地AEM LTS SP03 Asset屏幕的[!UICONTROL 创建]按钮中选择[!UICONTROL 文件]后，文件上传弹出窗口未出现问题的解决方案。 |
| 2026 年 10 月 | Adobe Analytics 1.4 API弃用[AEM Forms Analytics报表不显示任何数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51729) | 新文章 | 了解当AEM Forms中的Forms Analytics功能板不显示跨环境的分析数据，并且日志在连接到`api.omniture.com`时显示超时时问题的解决方案。 |
| 2026 年 10 月 | [AEM内容片段：保存后未保留富文本字段中的深层链接](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51772) | 新文章 | 了解在保存片段后删除或更改插入到AEM内容片段的富文本字段中的深层链接时问题的解决方案。 |
| 2026 年 10 月 | AEM Assets中的某些用户缺少[上载按钮](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51796) | 新文章 | 了解当某些具有相同访问级别的AEM as a Cloud Service用户无法上传资源并且在Assets界面中看不到[!UICONTROL 创建]按钮或上传选项时，而具有相同配置文件的其他用户却可以上传时，该问题的解决方案。 |
| 2026 年 10 月 | [使用内容传输工具计算AEM as a Cloud Service迁移的磁盘空间需求](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51802) | 新文章 | 了解当您不确定在使用内容传输工具迁移到AEM as a Cloud Service时如何估计迁移包和临时文件所需的磁盘空间时问题的解决方案。 |
| 2026 年 10 月 | 由于浏览器扩展干扰，[元数据编辑在AEM Assets Essentials中失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51886) | 新文章 | 了解当您在AEM Assets Essentials视图中进行的元数据更改未保存在[!DNL Chrome]中，而问题未出现在AEM Assets默认视图或其他浏览器中时，该问题的解决方案。 |
| 2026 年 10 月 | [在 [!DNL JBoss]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43285)上的AEM 6.5 SP25的Configuration Manager中解决EAR合并失败 | 新文章 | 了解当EAR合并步骤在[!DNL JBoss]上的本地AEM 6.5 SP25中执行Configuration Manager期间失败并出现&#x200B;*无法合并Ears*&#x200B;错误时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中升级Service Pack后，[组件编辑对话框未关闭](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43338) | 新文章 | 了解当AEM Touch UI页面编辑器中的组件编辑对话框在Service Pack升级后未使用[!UICONTROL 完成]或[!UICONTROL 取消]按钮关闭时（即使更改已保存）问题的解决方案。 |
| 2026 年 10 月 | [限制浏览器直接访问Adobe Experience Manager中的DAM文件夹](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43648) | 新文章 | 了解当知道URL的任何人都可以通过Web浏览器直接访问和下载某些AEM DAM文件夹中的文件（如CSV）时，该问题的解决方案。 |
| 2026 年 10 月 | [正在升级Adobe Experience Manager中加密数据库连接的 [!DNL Oracle] JDBC驱动程序](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43115) | 新文章 | 了解当您的安全要求在JEE上的AEM Forms 6.5与[!DNL Oracle Database]之间调用SSL/TLS加密通信，但配置的[!DNL Oracle] JDBC驱动程序不支持所需的加密功能时，此问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager Forms 6.5的升级计划和先决条件](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43272) | 新文章 | 了解当您的组织计划升级到AEM Forms 6.5并需要阐明Service Pack发布时间表、支持的平台、支持的[!DNL JBoss]和JDK版本、磁盘空间以及迁移先决条件时，这个问题的解决方案。 |
| 2026 年 10 月 | [解决AEM 6.5创作对话框中的工具提示和验证消息文本环绕问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43954) | 新文章 | 了解当AEM 6.5创作对话框中的工具提示和验证消息文本显示不正确的分行符或视觉间距，并在中间拆分字词时问题的解决方案。 |
| 2026 年 10 月 | [对Adobe Experience Manager 6.5发布实例中的高CPU使用率和超时错误进行故障排除](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43731) | 新文章 | 了解当本地AEM 6.5发布实例的CPU利用率较高，并且最终用户在访问已发布的站点时收到超时错误时，该问题的解决方案。 |
| 2026 年 10 月 | [在AEM Cloud Manager中配置 [!DNL Cypress] 测试以进行QA，而无需在生产环境中强制执行](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43163) | 新文章 | 了解在`pom.xml`中添加`test/cypress`时在所有AEM Cloud Manager环境（包括生产环境）中强制执行[!DNL Cypress] UI测试时问题的解决方案，同时需要它们仅在QA中运行。 |
| 2026 年 10 月 | [在AEM Assets中扩展名大写的PNG文件返回404错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43216) | 新文章 | 了解在AEM Assets中发布大写文件扩展名的PNG资源时，当通过Dispatcher访问时返回&#x200B;*404 Not Found*，同时这些资源可在“创作”环境中访问，该问题的解决方案。 |
| 2026 年 10 月 | [Dynamic Media OpenAPI不支持直接交付渐进式MP4呈现版本](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43346) | 新文章 | 了解问题的解决方案，在具有OpenAPI的Dynamic Media中，您需要将每个自动生成的自适应视频表示作为一个完整的渐进式MP4文件，并且投放URL稳定。 |
| 2026 年 10 月 | [Assets视图与AEM Assets中的“管理员视图”的资源名称验证不同](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43497) | 新文章 | 了解这个问题的解决方案，当AEM Assets视图允许您上传或重命名具有不支持的字符（如`#`）的资源时不会出现验证错误，而管理员视图会阻止这些资源。 |
| 2026 年 10 月 | [在AEM Assets中自动为动态文件夹分配元数据架构](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43506) | 新文章 | 了解当您需要将元数据架构手动分配给大型或动态AEM Assets文件夹结构中的每个新文件夹时，该问题的解决方案，因为没有现成的功能按文件夹名称模式或路径分配它们。 |
| 2026 年 10 月 | [Adobe Experience Manager中的Dynamic Media查看器预设无响应](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43509) | 新文章 | 了解当AEM中的Dynamic Media查看器预设（如内联缩放或弹出查看器）在浏览器窗口或设备视区更改时未调整大小时问题的解决方案。 |
| 2026 年 10 月 | [使用Dispatcher筛选规则降低Adobe Experience Manager Assets中绕过身份验证的风险](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43558) | 新文章 | 了解当安全审查标识从SAML身份验证中排除的AEM Assets登录端点，并且Dispatcher配置不按照AEM as a Cloud Service中的预期限制对其请求时，该问题的解决方案。 |
| 2026 年 10 月 | AEM Assets中的[JPG上载失败，出现&#x200B;*进程失败*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43584) | 新文章 | 了解当上传到AEM Assets as a Cloud Service的所有JPG都失败，并显示多个用户的&#x200B;*进程失败*&#x200B;消息时，该问题的解决方案。 |
| 2026 年 10 月 | [解决AEM Dynamic Media中处理卡住的资源问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43588) | 新文章 | 了解当您在启用Dynamic Media的情况下上传到DAM的图像或视频停留在[!UICONTROL 正在处理]状态并且不生成演绎版或达到已发布状态时，问题的解决方案。 |
| 2026 年 10 月 | [解决Adobe Experience Manager模板助手中损坏或重复的资源文件夹缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43641) | 新文章 | 了解即使重新处理Design Assets文件夹，AEM Template Assistant资源选择器中资源文件夹缩略图显示已损坏或重复时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager Dynamic Media中为自定义域SSL配置CNAME和_acme-challenge DNS记录](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43780) | 新文章 | 了解在您需要配置CNAME记录（包括`_acme-challenge`记录）以便在AEM Dynamic Media中为自定义域启用SSL时问题的解决方案。 |
| 2026 年 10 月 | [作业标识符元数据未显示在Adobe Experience Manager Assets](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43793)中 | 新文章 | 了解在上传包含作业标识符或传输引用元数据的图像后，AEM Assets中的[!UICONTROL 作业ID#]字段保持空白时问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets：将文件名清理与标准上载工作流集成](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43997) | 新文章 | 了解当通过AEM as a Cloud Service中的自定义文件名清理流上传的资产未自动显示在Assets UI中，将系统用户显示为上传程序并且不会触发重复文件名检测时问题的解决方案。 |
| 2026 年 10 月 | [Creative Cloud和AEM Assets存储库架构的最佳实践](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44096) | 新文章 | 了解当企业团队需要有关存储库架构的指导以跨Adobe Creative Cloud和AEM Assets管理工作文件、批准的源文件和最终资源时，该问题的解决方案。 |
| 2026 年 10 月 | [管道执行失败，在AEM Cloud Manager](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43244)中出现&#x200B;*在存储库中未找到分支*&#x200B;错误 | 新文章 | 了解当AEM Cloud Manager管道作业无法执行，并出现存储库&#x200B;*中未找到分支错误，阻止生产部署时，该问题的解决方案。* |
| 2026 年 10 月 | 在Adobe Experience Manager Cloud Manager中添加Git存储库时出现[连接超时错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48658) | 新文章 | 了解在AEM Cloud Manager中添加Git存储库时因出现&#x200B;*与存储库的连接超时*&#x200B;错误而失败的问题解决方案，因为该存储库只能从内部网络或通过VPN访问。 |
| 2026 年 10 月 | 在AEM Cloud Manager中部署期间[OSGi包解析失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42925) | 新文章 | 了解当部署在AEM Cloud Manager中的OSGi捆绑包解析阶段失败，并且多个捆绑包保持不活动或未解析，在错误日志中有未解决的包要求和&#x200B;*ClassNotFoundException*&#x200B;错误时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中删除包后，[在AEM Forms中上传图像失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42931) | 新文章 | 了解当AEM Forms中的图像上传因&#x200B;*com.adobe.granite.asset.api.AssetException而失败时的问题的解决方案：从创作和发布实例手动卸载We.Retail包后无法在路径*&#x200B;处创建资产。 |
| 2026 年 10 月 | [AEM Forms输出PDF无法在 [!DNL Microsoft Edge]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42932)中打开 | 新文章 | 了解当由AEM Forms输出服务生成的PDF在大多数查看器中正确打开但在网络交付后[!DNL Microsoft Edge]中未能打开时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager Forms JEE中进行文档映射期间&#x200B;[*InvalidCoercionException*](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42933) | 新文章 | 了解当AEM Forms JEE 6.5.0中的Workbench进程对于具有&#x200B;*com.adobe.idp.dsc.util.InvalidCoercionException*&#x200B;错误的某些记录失败时问题的解决方案。 |
| 2026 年 10 月 | 在AEM Forms JEE群集上创建LCA文件时，[Workbench返回404错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43113) | 新文章 | 了解在AEM Forms Workbench中，在JEE上的集群AEM Forms上创建LCA(LiveCycle Archive)文件时问题的解决方案，返回HTTP 404。 |
| 2026 年 10 月 | [将Adobe Experience Manager从 [!DNL Red Hat JBoss] 迁移到Adobe捆绑包 [!DNL JBoss]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43159) | 新文章 | 了解当您的组织在[!DNL Red Hat JBoss]上运行AEM并且需要迁移到捆绑在Adobe中的[!DNL JBoss]分发并同时保留所有配置和自定义设置时，该问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Designer 6.5 PDF forms中启用附件字段和Reader扩展](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43161) | 新文章 | 了解当您在应用Reader扩展后使用Adobe Designer 6.5创建的PDF forms中附件功能无法正常使用时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms Workbench连接失败，因为SOAP服务返回HTTP 503](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43322) | 新文章 | 了解当AEM Forms Workbench无法连接到AEM Forms服务器且Workbench日志显示错误(如&#x200B;*无法验证用户*&#x200B;或&#x200B;*ALC-DSC-099-000： com.adobe.idp.dsc.DSCRuntimeException： org.apache.axis.AxisFault： (503)服务不可用*)时问题的解决方案。 |
| 2026 年 10 月 | [阻止在具有文件附件的AEM Adaptive Forms中重复提交](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43457) | 新文章 | 了解当用户在上传文件附件或处理表单时通过反复单击[!UICONTROL 提交]按钮多次提交同一AEM自适应表单时问题的解决方案。 |
| 2026 年 10 月 | [迁移签名者证书时在AEM Forms中启用LTV签名](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43514) | 新文章 | 了解当您在AEM Forms中迁移签名者证书并需要长期验证(LTV)签名以保持正常工作和合规性时，问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms：由于验证码处理程序功能切换，自适应表单提交因HTTP 500失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43569) | 新文章 | 了解当AEM Forms环境中的所有自适应表单提交失败并出现&#x200B;*HTTP 500错误*&#x200B;时（即使表单不包含验证码字段），该问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms as a Cloud Service：由于IMS SSO问题，创作UI加载停滞](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43571) | 新文章 | 了解当AEM Forms as a Cloud Service创作服务UI在多个浏览器中持续停滞加载且无明确错误消息且从未到达仪表板时问题的解决方案。 |
| 2026 年 10 月 | [在AEM Forms 6.5](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43618)中保存文档片段失败，出现XPath运算符限制错误 | 新文章 | 了解在AEM Forms 6.5中保存文档片段时遇到的问题的解决方案，该问题在UI中导致&#x200B;*文本创建失败*，并且在服务器日志中出现&#x200B;*javax.xml.xpath.XPathExpressionException*&#x200B;错误。 |
| 2026 年 10 月 | 升级Service Pack 25后[Adobe Experience Manager中的PDF打开速度缓慢](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43733) | 新文章 | 了解在JEE (Service Pack 25)上安装PDF 6.5.25.0后，AEM Forms文档（包括签名的PDF）打开缓慢时问题的解决方案。 |
| 2026 年 10 月 | [在AEM Forms 6.5.2 LTS中解析org.apache.xpath.XPathAPI的&#x200B;*ClassNotFoundException*](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43735) | 新文章 | 了解在新服务器上安装AEM Forms 6.5.2 LTS后应用程序部署失败且日志显示`org.apache.xpath.XPathAPI`的&#x200B;*ClassNotFoundException*&#x200B;时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms：通过更新signature-dsc组件](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43958)解决打开PDF速度缓慢的问题 | 新文章 | 了解当您部署新的内部版本或升级到最近的Service Pack后，当PDF文档在[!DNL JBoss]的AEM Forms中打开缓慢时问题的解决方案。 |
| 2026 年 10 月 | 在修补程序后，[AEM Forms Workbench连接失败，除非升级到SP25](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51108) | 新文章 | 了解当您应用修补程序6.5.0-0134后，AEM Forms Workbench客户端无法连接到AEM实例时该问题的解决方案，除非将其升级到Service Pack 25。 |
| 2026 年 10 月 | [AEM：由于Content-Disposition标头](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42364)，文本组件中的PDF链接始终下载 | 新文章 | 了解当在AEM文本组件中创作的PDF链接始终下载而不是在新选项卡中打开时（因为响应包含`content-disposition: attachment`标头）问题的解决方案。 |
| 2026 年 10 月 | AEM Sites输出中缺少[DITA映射容器元素](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43277) | 新文章 | 了解当DITA映射中定义的容器元素（如区段标题或任务分组）在生成的AEM Sites输出中缺失时问题的解决方案。 |
| 2026 年 10 月 | [AEM Sites：组件在自定义响应式网格创作期间自动滚动到顶部](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43499) | 新文章 | 了解当在使用自定义响应式网格的AEM Sites页面上创作组件时，文本或图像等组件自动滚动到页面顶部时问题的解决方案。 |
| 2026 年 10 月 | [AEM Sites：由于模板策略限制，页面移动失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43824) | 新文章 | 了解在AEM Sites中移动页面不会更新其URL时问题的解决方案，并且错误日志报告目标路径下不允许使用模板。 |
| 2026 年 10 月 | [AEM Sites：解决未缓存的服务器端渲染导致的店面性能问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43943) | 新文章 | 了解当AEM Sites B2B和B2C存储前端在高流量事件中响应时间较长或在关键页面（如产品概述和产品详细信息）上缺少内容时问题的解决方案。 |
| 2026 年 10 月 | AEM Sites[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44002)中的身份验证弹出窗口和&#x200B;*ERR_INVALID_RESPONSE* | 新文章 | 了解在访问AEM创作URL时显示意外身份验证弹出窗口而不是登录屏幕以及浏览器显示&#x200B;*ERR_INVALID_RESPONSE*&#x200B;错误时问题的解决方案。 |
| 2026 年 10 月 | [AEM Sites：使用模拟时，工具栏编辑工具有所不同](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44079) | 新文章 | 了解当管理员使用模拟时，AEM Sites工具栏为不同用户显示不同的编辑工具集时问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager LTS升级后计划资产停用问题疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43521) | 新文章 | 了解当资产在AEM长期支持(LTS)升级后在其配置的计划关闭时间未取消激活时问题的解决方案。 |
| 2026 年 10 月 | 在AEM 6.5 LTS中创建页面期间，[MSM转出配置返回null](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43741) | 新文章 | 了解当通过AEM 6.5 LTS中的工作流创建的页面缺少预期内容并出现MSM转出配置错误或空值时问题的解决方案。 |
| 2026 年 10 月 | [AEM：由于编码了个性化分隔符，Adobe Campaign Classic中的投放失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43760) | 新文章 | 了解当AEM创作的电子邮件模板的Adobe Campaign Classic投放准备失败时的问题的解决方案，因为升级后equals sign in personalization输出块是HTML编码的。 |
| 2026 年 10 月 | [从AEM 6.5 LTS中已弃用的经典Commerce API迁移](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44399) | 新文章 | 了解当您的项目依赖于已弃用的Classic Commerce和CommerceSession API时，这个问题的解决方案，这些API在内部部署AEM 6.5 LTS中不再可用。 |
| 2026 年 10 月 | [AEM LTS升级：脱机数据存储和索引一致性检查建议](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51428) | 新文章 | 了解在准备AEM 6.5 LTS升级以及需要了解是否需要离线数据存储和索引一致性检查时问题的解决方案。 |
| 2026 年 10 月 | 在AEM Assets中升级LTS后缺少[[!UICONTROL 修改日期]和[!UICONTROL 发布日期]字段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42819) | 新文章 | 了解在AEM Assets 6.5 LTS升级后，Assets控制台中某些资源缺少[!UICONTROL 修改日期]和[!UICONTROL 发布日期]字段时问题的解决方案。 |
| 2026 年 10 月 | [在 [!DNL Java] 17或21](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43865)上解决AEM 6.5 LTS中的空白[!UICONTROL 书信]预览 | 新文章 | 了解当[!DNL Java] 17或21上运行的AEM 6.5 LTS中的创建通信界面中的[!UICONTROL 书信]预览显示为空白时问题的解决方案。 |
| 2026 年 10 月 | [AEM LTS上的AEM Screens Cloud AMS包不支持本地设备注册](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43960) | 新文章 | 了解当您在AEM LTS上安装Screens Cloud AMS包并且`/screens/devices.html`页面不提供本地设备管理后，在本地注册设备的尝试失败时问题的解决方案。 |
| 2026 年 10 月 | [将 [!DNL Dynatrace] 和ELK与Adobe Experience Manager as a Cloud Service集成](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42480) | 新文章 | 了解在您需要使用[!DNL Dynatrace] APM监视AEM as a Cloud Service环境或将AEM日志转发到[!DNL Dynatrace]或基于[!DNL Elasticsearch]或[!DNL OpenSearch]的系统时问题的解决方案。 |
| 2026 年 10 月 | [无法在Adobe Experience Manager as a Cloud Service中启用用户同步配置](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42527) | 新文章 | 了解当在AEM as a Cloud Service Publisher环境中启用用户同步配置失败，而针对Target环境运行Cloud Manager管道时问题的解决方案。 |
| 2026 年 10 月 | [为Adobe Experience Manager URL配置自定义 [!DNL New Relic Synthetics] 监视器](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42762) | 新文章 | 了解当您需要使用自定义[!DNL New Relic Synthetics]监视器监视重要AEM发布的页面、CDN投放或第三方端点的可用性时的问题的解决方案。 |
| 2026 年 10 月 | [在创建EDS站点或访问日志查看器时解决403错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42764) | 新文章 | 了解当您通过组织范围内的管理API操作创建Edge Delivery Services站点或在没有所需日志权限的情况下打开日志查看器时收到&#x200B;*403 Forbidden*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中删除孤立的Dynamic Media云配置](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42830) | 新文章 | 了解当您在AEM as a Cloud Service中的`/conf/global/settings/cloudconfigs/`下发现孤立或重复的Dynamic Media配置节点并且无法删除这些节点时，该问题的解决方案。 |
| 2026 年 10 月 | [由于命名空间类型不受支持，AEM Cloud中已阻止高级网络迁移](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42890) | 新文章 | 了解针对特定AEM as a Cloud Service环境从旧版出口代理迁移到高级网络专用出口IP失败时问题的解决方案。 |
| 2026 年 10 月 | 使用Dynamic Media OpenAPI中的format修饰符时，[SVG资源未转换为PNG或JPEG](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42895) | 新文章 | 了解通过Dynamic Media OpenAPI为SVG源资源请求PNG或JPEG输出时问题的解决方案，它返回了原始的SVG而没有栅格化。 |
| 2026 年 10 月 | Adobe Experience Manager as a Cloud Service中的[用户帐户未同步IMS组](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42935) | 新文章 | 了解当具有Adobe ID和Federated ID的AEM as a Cloud Service用户登录后缺少一个或多个预期的IMS组时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中呈现页面时出现[HTTP 5xx错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42943) | 新文章 | 了解当网站访客收到更多HTTP 5xx错误（如503或504）时，以及AEM as a Cloud Service中的产品页面在流量尖峰期间变得缓慢或无响应时，问题的解决方案。 |
| 2026 年 10 月 | [访问AEM Sites Optimizer评估的沙盒环境](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42950) | 新文章 | 了解当您无法在标准沙盒环境中启用AEM Sites Optimizer以评估其功能时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42954)中生成&#x200B;*SSLHandshakeException PKIX路径失败* | 新文章 | 了解当[!DNL Java]应用程序无法连接到AEM as a Cloud Service终结点，并且&#x200B;*PKIX路径生成失败* / *SSLHandshakeException*&#x200B;错误时，同一服务器中的[!DNL OpenSSL]验证成功时问题的解决方案。 |
| 2026 年 10 月 | [使用自定义通用编辑器扩展在AEM Sites Cloud中自动锁定页面](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43064) | 新文章 | 了解当AEM as a Cloud Service中的AEM Sites页面在首次编辑后未自动锁定，需要手动操作并增加编辑冲突风险时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service部署失败，出现&#x200B;*KubernetesDeploymentTimeoutException*，尽管转出正常](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43066) | 新文章 | 了解当AEM as a Cloud Service生产部署失败并出现&#x200B;*KubernetesDeploymentTimeoutException*&#x200B;时，即使基础转出达到正常、已完成状态的问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager (AEM) Assets中配置资源过期行为](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43087) | 新文章 | 了解当AEM Assets as a Cloud Service自动取消发布其`prism:expirationDate`是过去的资产，并且您需要其他过期行为时，该问题的解决方案。 |
| 2026 年 10 月 | [DAM资源仍在处理中，不会在AEM as a Cloud Service中生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43102) | 新文章 | 了解当在AEM as a Cloud Service中上传到DAM的资源保持[!UICONTROL 正在处理]状态，不生成演绎版，且创作日志显示Adobe I/O Events注册失败时，问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service中的SSL证书续订责任因证书类型而异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43141) | 新文章 | 了解当监控工具报告AEM as a Cloud Service中Adobe管理的域的SSL证书即将到期并且您不确定是否需要操作时，该问题的解决方案。 |
| 2026 年 10 月 | [*在Sling JobConsumer](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43151)中无法派生包和子服务的用户名*&#x200B;错误 | 新文章 | 了解当AEM as a Cloud Service中的计划作业在队列中保持未处理状态并且日志显示错误消息，说明AEM无法派生包和子服务的用户名时问题的解决方案。 |
| 2026 年 10 月 | 在本地开发和 [!DNL Maven] 内部版本中支持[AEM as a Cloud Service  [!DNL Eclipse Temurin] JDK 25](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43155) | 新文章 | 当您不确定使用AEM as a Cloud Service时，[!DNL Eclipse Temurin] JDK 25是否可以替换[!DNL Oracle] JDK 21以用于本地开发、AEM SDK使用和[!DNL Maven]内部版本，了解该问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中使用OpenAPI投放URL的Dynamic Media上，更新的资源不会立即可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43157) | 新文章 | 了解当在AEM as a Cloud Service中使用OpenAPI投放URL超过15分钟且更新后的已批准资源在其Dynamic Media中不可用，并且当资源被推送到Dynamic Media时没有状态指示器确认时，该问题的解决方案。 |
| 2026 年 10 月 | 其他AEM发布区域缺少[[!DNL Dynatrace] 主机监视和标记](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43169) | 新文章 | 了解当附加AEM发布区域在[!DNL Dynatrace]中报告主机量度或标记时，即使日志从其发布pod转发成功，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Sites：移动操作后解析隐藏页面和重复节点](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43230) | 新文章 | 了解当AEM Sites创作中的页面移动操作在站点控制台中隐藏原始页面并创建重复节点，阻止进一步更新或重命名时，此问题的解决方案。 |
| 2026 年 10 月 | 由于TAR文件损坏，[AEM内容传输工具摄取失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43233) | 新文章 | 了解当AEM内容传输工具摄取在数小时后重复失败，并且日志显示&#x200B;*InvalidBinaryReferencesIndexException：处理区段存档文件时出现无法识别的幻数*&#x200B;错误时，该问题的解决方案。 |
| 2026 年 10 月 | 在AEM中迁移到AEM Cloud Service时出现&#x200B;[*区段未找到*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43250) | 新文章 | 了解在内容从AEM 6.5传输到AEM as a Cloud Service的过程中内容提取失败，出现&#x200B;*未找到区段*&#x200B;错误和日志报告TAR文件&#x200B;*无法识别的幻数*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中[启用 [!DNL Lucidworks] 爬虫](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43287) | 新文章 | 了解当[!DNL Lucidworks]爬虫在没有强身份验证（如SAML或OAuth）的情况下无法访问AEM as a Cloud Service Publish实例时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：项目团队所有者无法查看或添加其他用户](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43309) | 新文章 | 了解当AEM as a Cloud Service项目团队中具有[!UICONTROL 所有者]角色的用户只能看到他们自己的配置文件，而无法查看或添加其他用户时问题的解决方案。 |
| 2026 年 10 月 | [[!UICONTROL 内容片段]选项在Adobe Experience Manager](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43311)的站点控制台中不可见 | 新文章 | 了解当有人在AEM as a Cloud Service中启用或禁用Unified Shell导航叠加后[!UICONTROL 内容片段]选项未出现在所有用户的站点控制台中时问题的解决方案。 |
| 2026 年 10 月 | AEM as a Cloud Service中的[Content Hub链接重定向或显示空白屏幕](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43317) | 新文章 | 了解当在AEM as a Cloud Service中选择Content Hub链接时，问题的解决方案，重定向到AEM Sites或显示空白屏幕而不是加载Content Hub。 |
| 2026 年 10 月 | [AEM as a Cloud Service： Experience Production Agent内容更新作业失败，出现内部错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43324) | 新文章 | 了解当AEM as a Cloud Service中的Experience Production Agent内容更新作业失败并出现持久性内部错误消息时（即使对于简单的纯文本请求），该问题的解决方案。 |
| 2026 年 10 月 | 未在AEM Assets中加载资源时，[Content Hub仅显示标题栏和搜索栏](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43350) | 新文章 | 了解当AEM Assets中的Content Hub仅显示标题和搜索栏，并且资产网格、缩略图、筛选器和标记选项未加载时，该问题的解决方案。 |
| 2026 年 10 月 | [自定义工作流模型在AEM as a Cloud Service中部署后还原为默认值](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43372) | 新文章 | 了解在以后的部署或环境生命周期事件后，AEM as a Cloud Service中的自定义工作流模型恢复到`/var/workflow/models`下的默认定义时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：UTC午夜后日志流可用性的延迟](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43379) | 新文章 | 了解当AEM as a Cloud Service中的Adobe日志流在00:00 UTC的每日日志轮换失败和AIO `tail:logs`连接尝试失败后15到40分钟时间内不可用时的问题的解决方案。 |
| 2026 年 10 月 | [将生产克隆用于具有内容传输工具的AEM Assets迁移分析](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43382) | 新文章 | 了解直接在生产AEM创作实例上运行迁移分析时问题的解决方案，该问题会在您计划使用Content Transfer Tool将AEM Assets迁移到AEM as a Cloud Service时影响性能。 |
| 2026 年 10 月 | [Dynamic Media： [!DNL iPhone]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43391)上的图像格式回退和透明度损失不一致 | 新文章 | 了解当Dynamic Media通过具有`.avif`扩展的URL在[!DNL iPhone]设备上以JPEG格式提供一些PNG和GIF资源而导致透明度或动画丢失时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：尽管Assets Ultimate权利文件，仍缺少Assets View UI扩展性扩展点](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43394) | 新文章 | 了解当Assets视图UI扩展性扩展点（如`aem/assets/browse/1`和`aem/assets/details/1`）尽管具有Assets Ultimate权限，却未出现在AEM as a Cloud Service中的问题的解决方案。 |
| 2026 年 10 月 | [AEM：查询参数排序不一致会影响ETag和缓存](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43396) | 新文章 | 了解当资产交付API或核心图像组件生成的图像URL在AEM as a Cloud Service中以不一致的顺序包含查询参数，从而导致ETag值不稳定并返回`200 OK`而不是`304 Not Modified`的`If-None-Match`请求时，该问题的解决方案。 |
| 2026 年 10 月 | [在AEM 6.5 LTS SP3](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43400)中升级后，Classic兼容包不受支持，/libs/commerce组件不可用 | 新文章 | 了解从AEM 6.5 SP24升级到AEM 6.5 LTS SP3后缺少`/libs/commerce`组件库时问题的解决方案，以及依赖经典CIF组件的实施停止工作。 |
| 2026 年 10 月 | [在没有Workfront集成的AEM中生成资源上传报告](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43402) | 新文章 | 了解在您需要生成有关上传到AEM的所有资源的报告时该问题的解决方案，包括创作名称、上传日期、文件类型和内容路径，之前基于Workfront的流程不再可用。 |
| 2026 年 10 月 | 安装大型内容包后，[AEM Cloud Service RDE在部署中卡住](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43404) | 新文章 | 了解当AEM快速开发环境(RDE)在安装大型内容包且诸如`aio aem rde status`的CLI命令失败并出现内部错误后，其保留在[!UICONTROL 正在部署]中的问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager Assets中复制资源后，[粘贴选项间歇性不可用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43407) | 新文章 | 了解当您在复制资源并导航到目标文件夹后，AEM Assets中的[!UICONTROL 粘贴]菜单选项间歇性不可用时问题的解决方案。 |
| 2026 年 10 月 | AEM Dispatcher中的[gracePeriod参数影响过期后的缓存服务](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43430) | 新文章 | 当您不确定在缓存内容过期后的宽限期内以及在检索最新内容之前，AEM Dispatcher是否提供过时的缓存内容时，了解该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中激活内容后的[Dispatcher宽限期行为](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43433) | 新文章 | 了解问题的解决方案，其中您需要了解AEM Dispatcher在激活自动失效的资源后，是否在`/gracePeriod`期间提供缓存的内容。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43446)中为自定义Oak索引发出“检测到无索引的查询”警报 | 新文章 | 了解在部署新的自定义Oak索引期间，AEM as a Cloud Service中的自定义SQL-2查询触发了&#x200B;*检测到无索引查询*&#x200B;警报时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager as a Cloud Service中检索和管理特定日期的错误日志](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43451) | 新文章 | 了解当需要AEM as a Cloud Service生产发布特定日期的错误日志和大型日志文件使手动提取和关键词搜索变得困难时的问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager中选择正确的内容片段和模型管理API索引包](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43474) | 新文章 | 了解当AEM中的内容片段和模型管理API索引包不完整或过期导致缺少影响功能和性能的索引时，问题的解决方案。 |
| 2026 年 10 月 | 无法在Adobe Experience Manager as a Cloud Service中加载[图像](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43507) | 新文章 | 了解当AEM as a Cloud Service中的图像因图像请求重复重定向且响应为302或304，并且URL随重复的路径区段增长而加载失败时，该问题的解决方案。 |
| 2026 年 10 月 | 由于存储库访问令牌权限，[Cloud Manager分支选择字段为只读](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43517) | 新文章 | 了解当Cloud Manager中全栈开发管道的[!UICONTROL Source代码]选项卡上的[!UICONTROL 分支]选择字段为只读并显示连接到外部[!DNL GitLab]实例的存储库的错误消息时，问题的解决方案。 |
| 2026 年 10 月 | [如何清除Adobe Experience Manager中不正常的工作流实例](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43519) | 新文章 | 了解当AEM中的不正常或已完成工作流实例的构建降低系统健康度和工作流实例UI响应性，且UI显示许多具有[!UICONTROL 不正常]状态的工作流时，问题的解决方案。 |
| 2026 年 10 月 | [Edge Delivery Services：域映射失败，因为站点验证后源不正确](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43534) | 新文章 | 了解在网站验证和域映射失败后Edge Delivery Services网站源被错误地更新为`/well-known/adobe/cloudmanager-challenge.txt`路径时问题的解决方案。 |
| 2026 年 10 月 | [了解Adobe Experience Manager as a Cloud Service中的可计费内容请求](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43548) | 新文章 | 当您想要了解并减少贵组织在AEM as a Cloud Service中使用计费内容请求时，请了解问题的解决方案。 |
| 2026 年 10 月 | [解决Adobe Experience Manager中的性能延迟和重复数据导入作业失败问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43550) | 新文章 | 了解当AEM中的大型或并发导入导致性能延迟、导入作业失败并自动重新启动，以及日志中显示同一导入的多个工作流实例时，此问题的解决方案。 |
| 2026 年 10 月 | [将公共PDF从AEM Sites DAM迁移到AEM Assets交付URL时，SEO和索引的最佳实践](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43552) | 新文章 | 了解当您需要在不丢失搜索引擎索引或SEO信号的情况下将公共PDF资产从AEM Sites DAM URL迁移到AEM as a Cloud Service中的AEM Assets交付URL时，该问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager as a Cloud Service中ACS AEM Commons 6.17.4的OSS扫描发现](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43555) | 新文章 | 了解当OSS扫描程序（如[!DNL Sonatype]）报告AEM as a Cloud Service中针对ACS AEM Commons 6.17.4依赖项的调查结果（如CVE-2024-21490或CVE-2022-25844）时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中访问[OSGi控制台失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43636) | 新文章 | 了解当在AEM as a Cloud Service中尝试访问`/system/console`处的OSGi控制台失败，并且您无法查看或修改OSGi配置或监视捆绑包状态时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager as a Cloud Service中升级aem.js样板](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43651) | 新文章 | 了解当您想要将上游更改合并到现有AEM as a Cloud Service项目中的`aem.js`并需要检查对自定义块、脚本、预览或发布的影响时，该问题的解决方案。 |
| 2026 年 10 月 | [调查Adobe Experience Manager Assets访问日志中的特权操作警报](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43654) | 新文章 | 了解当安全监控工具检测到AEM访问日志条目指示资产共享服务帐户执行了特权操作时，该问题的解决方案。 |
| 2026 年 10 月 | [调查AEM TarMK冷待机中的日志增长和同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43655) | 新文章 | 了解在AEM TarMK冷待机中待机实例的`tarmk-coldstandby.log`快速增长、磁盘空间不足、同步失败以及日志包含重复的&#x200B;*StackOverflowError*&#x200B;条目时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中测试负载期间[监视发布性能](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43659) | 新文章 | 了解加载测试AEM as a Cloud Service发布层时需要评估增加的流量对响应时间、错误和吞吐量产生的影响时问题的解决方案。 |
| 2026 年 10 月 | [调查AEM as a Cloud Service中缺少或空的User-Agent标头的请求](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43661) | 新文章 | 了解AEM as a Cloud Service的CDN日志显示大量请求缺少`User-Agent`标头或标头为空时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service下载报告中缺少用户标识字段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43727) | 新文章 | 了解当AEM as a Cloud Service Assets下载报表中的[!UICONTROL Downloaded By]或[!UICONTROL Downloaded By User Name]值为空时问题的解决方案。 |
| 2026 年 10 月 | [发布的内容未在Adobe Experience Manager as a Cloud Service的CDN域中更新](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43754) | 新文章 | 了解当在AEM as a Cloud Service中发布的内容更改在CDN域URL上不可见，而创作环境正确显示更新时，问题的解决方案。 |
| 2026 年 10 月 | [将AEM Forms从 [!DNL Red Hat JBoss] 迁移到Adobe捆绑包 [!DNL JBoss]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43763) | 新文章 | 了解将AEM Forms从[!DNL Red Hat JBoss]迁移到Adobe捆绑的[!DNL JBoss]环境时问题的解决方案，以及出现配置不匹配和部署问题。 |
| 2026 年 10 月 | [AEM as a Cloud Service：由于Dynamic Media图像预设配置，[!UICONTROL 呈现版本]面板为空](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43769) | 新文章 | 了解当AEM as a Cloud Service Assets UI中的[!UICONTROL 演绎版]面板不显示DAM资源的任何演绎版时（即使存储库中存在演绎版二进制文件），问题的解决方案。 |
| 2026 年 10 月 | [为高流量事件准备Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43778) | 新文章 | 了解当您的组织托管大规模注册或营销活动事件，这些事件会向AEM as a Cloud Service产生大量流量，并且您需要保持生产基础设施和代理隧道稳定时，问题的解决方案。 |
| 2026 年 10 月 | 在AEMaaCS中上传后，[Assets卡在预处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43787) | 新文章 | 了解通过Workfront连接器上传到AEM as a Cloud Service的资源或在较长时间内手动保持`PREPROCESSING`状态时问题的解决方案。 |
| 2026 年 10 月 | NIMU或Release Orchestrator在环境所有权期间的[Cloud Manager部署超时](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43811) | 新文章 | 了解当Cloud Manager部署日志在步骤`wait-for-env-ready`显示扩展持续时间且AEM as a Cloud Service中的部署超时时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中删除自定义索引后，[批量引用处理器返回零结果](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43813) | 新文章 | 了解当您删除自定义`SlingOrderedFolder`索引后，AEM中的批量引用处理器实用程序针对资产查询返回零结果时问题的解决方案。 |
| 2026 年 10 月 | [解决由不必要的存储库节点导致的AEM as a Cloud Service创作环境变慢问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43820) | 新文章 | 了解当AEM as a Cloud Service创作环境的页面加载缓慢、Sites和Assets控制台出现延迟，并且由于不必要的节点位于存储库的根级别而难以编辑页面时，该问题的解决方案。 |
| 2026 年 10 月 | [正在解决AEM Cloud Manager CDN配置部署中的YAML分析错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43847) | 新文章 | 了解在部署`cdn.yaml`期间出现YAML解析错误时Cloud Manager管道失败的问题解决方案，即使文件在外部验证器中似乎有效也是如此。 |
| 2026 年 10 月 | 由于孤立的JCR版本引用，[AEM Guides输出生成失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43848) | 新文章 | 了解当DITA映射的AEM Guides输出生成未完成或保持停滞状态并且错误日志包含&#x200B;*javax.jcr.version.VersionException：没有此类版本*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | [在允许编辑访问AEM中的体验片段组件时，限制添加、移动和删除](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43941) | 新文章 | 了解当用户必须在AEM中编辑现有体验片段组件的内容，但不得添加、移动或删除组件时，该问题的解决方案。 |
| 2026 年 10 月 | [体验片段页面在Adobe Experience Manager as a Cloud Service中保持锁定状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43945) | 新文章 | 了解AEM as a Cloud Service中的体验片段页面保持锁定状态，并且无法使用[!UICONTROL 解锁]按钮解锁该问题的解决方案，即使具有适当权限的用户也无法解锁。 |
| 2026 年 10 月 | [无法从Adobe Experience Manager Sites中的语言母版分离Live Copy](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43947) | 新文章 | 了解从AEM Sites中的语言母版分离Live Copy时失败并阻止在转出和批量发布期间删除不需要的页面时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：间歇性缺少Adobe I/O页面版本事件](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43962) | 新文章 | 了解AEM as a Cloud Service中的某些页面版本间歇性地无法提供Adobe I/O页面版本事件(`aem.sites.page.versioned`)时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：本机Oak索引和QueryBuilder搜索的许可和使用情况](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43974) | 新文章 | 了解当您计划在AEM as a Cloud Service中从外部搜索引擎迁移到本机Oak索引和QueryBuilder API并需要确认许可成本和使用限制时，该问题的解决方案。 |
| 2026 年 10 月 | AEM内容传输工具提取密钥验证期间出现&#x200B;[*连接失败*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43981) | 新文章 | 了解当AEM内容传输工具UI中的提取密钥验证失败，并且网络响应显示带有&#x200B;*连接失败*&#x200B;错误的`validationSuccess: false`时问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中协调删除内容片段节点](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43984) | 新文章 | 了解您需要从AEM as a Cloud Service生产创作、发布和预览环境中删除大量内容片段节点和相关DAM路径时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：大型站点的内容复制操作可能需要较长时间](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43991) | 新文章 | 了解当大型网站在AEM as a Cloud Service中的内容复制操作需要许多小时才能完成，并且Cloud Manager中的进度百分比在很长时间内保持较低时，问题的解决方案。 |
| 2026 年 10 月 | 未在Adobe Experience Manager as a Cloud Service[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44004)中部署自定义cq:AuditEvent索引 | 新文章 | 了解针对部署后本地Oak SDK的`/oak:index`中显示针对`cq:AuditEvent`的自定义AEM as a Cloud Service索引，而非Cloud Service环境中的该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：站点产品配置文件用户看不到站点控制台](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44089) | 新文章 | 了解当在Adobe Admin Console中分配给站点产品配置文件的用户成功向AEM as a Cloud Service进行身份验证但看不到站点控制台时，此问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets：编辑带有特殊字符的标记时缺少标题字段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44330) | 新文章 | 了解当您在标记标题中使用某些特殊字符之后重新打开标记以在AEM Assets中进行编辑时，[!UICONTROL 标题]字段显示空白时问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service中发布后，[已删除的站点配置仍保留在发布中](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48672) | 新文章 | 了解当您从AEM as a Cloud Service创作和发布的站点配置页面中删除的配置节点在发布中保持可见时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：仅将自定义元数据表单分配给内容片段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50580) | 新文章 | 了解当您需要将Assets视图中的自定义元数据表单仅应用于内容片段，而不应用于AEM as a Cloud Service中同一文件夹中的页面类型资源时问题的解决方案。 |
| 2026 年 10 月 | [AEM Dispatcher：从生产响应中删除X-Vhost和X-Dispatcher标头](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50974) | 新文章 | 了解当来自AEM 6.5 LTS生产网站的HTTP响应包含`x-vhost`和`x-dispatcher`标头时问题的解决方案。 |
| 2026 年 10 月 | [AEMaaCS：内容片段发布API因片段无效而失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51104) | 新文章 | 了解在AEM as a Cloud Service中使用`/adobe/sites/cf/fragments/publish` API发布内容片段时无法将该片段推送到预览或发布环境并且错误日志中显示警告时问题的解决方案。 |
| 2026 年 10 月 | [AEM 6.5 LTS：在JEE和OSGi部署中需要32位 [!DNL Linux] 共享库](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51160) | 新文章 | 了解当您准备在[!DNL Linux]上部署AEM 6.5 LTS并需要确认文档中列出的32位[!DNL Linux]共享库是否仍需要时，该问题的解决方案。 |
| 2026 年 10 月 | [AEMaaCS：连接的Assets和内容片段资源同步](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51449) | 新文章 | 了解当您不确定在AEM as a Cloud Service中使用内容片段时图像等资产如何从AEM Assets同步到AEM Sites的问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：工作流实例在完成后仍处于[!UICONTROL 正在运行]状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51642) | 新文章 | 了解当AEM as a Cloud Service中的工作流实例成功完成但仍列在正在运行的实例下，并且资产继续显示[!UICONTROL 在工作流中]徽章时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service和PHP漏洞CVE-2026-109618和CVE-2026-109619](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-51874) | 新文章 | 了解在需要确定PHP漏洞CVE-2026-109618和CVE-2026-109619是否影响AEM as a Cloud Service时问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service中处理视频资源后缺少[Dynamic Media节点](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42459) | 新文章 | 了解当您在AEM as a Cloud Service中上传和处理的某些视频资源没有预期的Dynamic Media节点或元数据属性（如`dam:scene7ID`）时，问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets：没有为文件扩展名不正确的资源生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43289) | 新文章 | 了解问题的解决方案，即某些AEM Assets在运行更新元数据工作流并重新处理之后未生成智能裁剪演绎版，因为它们具有`.jpg`扩展名但实际上采用WEBP格式。 |
| 2026 年 10 月 | 登录AEM Assets后[出现意外的屏幕重定向](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43331) | 新文章 | 了解当用户登录AEM Assets后间歇性地重定向到Assets主登陆页面以外的屏幕时，该问题的解决方案。 |
| 2026 年 10 月 | [某些AEM Assets图像的WebP演绎版文件大于JPEG文件](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43376) | 新文章 | 了解当使用AEM Assets处理配置文件生成的WebP演绎版大于相同源图像和像素尺寸的相应JPEG演绎版时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service中的Dynamic Media视频处理失败，出现“NeedsReupload”和SmartCrop错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43492) | 新文章 | 了解当AEM as a Cloud Service中的Dynamic Media视频资源处理失败、停留在`NeedsReupload`或`process failed`状态，并且`dam:scene7Failure`属性报告未找到作业结果或失败消息时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager Assets中将资源元数据导出为CSV](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43542) | 新文章 | 了解当您需要AEM Assets中的资源元数据以进行报表或下游处理，但在搜索结果或收藏集视图中看不到CSV导出选项时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets [!UICONTROL 引用]边栏未显示所有资源引用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43544) | 新文章 | 了解当AEM Assets资源属性中的[!UICONTROL 引用]边栏显示的站点页面引用比预期为零或更少时，而移动或取消发布工作流会列出这些引用时，问题的解决方案。 |
| 2026 年 10 月 | 没有为AEM Assets中的图像资源生成[DPI元数据属性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43657) | 新文章 | 了解为您上传到AEM Assets的图像资源生成或填充`tiff:pixelDpi`元数据属性时问题的解决方案。 |
| 2026 年 10 月 | [在批量资源迁移期间连接的Assets面板加载或超时问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43930) | 新文章 | 了解当AEM Assets中的“连接的Assets”面板无限期加载或在具有受限DAM权限的最终用户批量资源迁移期间返回&#x200B;*网关超时*&#x200B;错误时，该问题的解决方案。 |
| 2026 年 10 月 | [枚举下拉选项未由AEM内容片段模型中的其他字段过滤](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43119) | 新文章 | 了解当您需要AEM内容片段模型的一个枚举下拉字段中的选项取决于另一个字段中的选择时，问题的解决方案。 |
| 2026 年 10 月 | [无法删除失败的AEM Cloud Manager开发环境，未释放积分](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42456) | 新文章 | 了解当无法通过UI或API删除失败的AEM Cloud Manager开发环境并且未发布其开发环境点数时问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud Manager管道在部署步骤失败，出现&#x200B;*HELM_RELEASE_FAILED*&#x200B;和503错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42815) | 新文章 | 了解当AEM Cloud Manager管道执行在部署步骤始终失败，出现&#x200B;*HELM_RELEASE_FAILED*&#x200B;错误并发布运行状况检查报告转出期间出现HTTP 503错误时，该问题的解决方案。 |
| 2026 年 10 月 | [安排有关部署的AEM as a Cloud Service维护更新并验证休眠状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42817) | 新文章 | 了解当自动AEM as a Cloud Service维护版本在部署窗口期间触发，并且暂存环境和生产环境标记为休眠，延迟部署验证时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager as a Cloud Service中管理发布层用户数据持久性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42941) | 新文章 | 了解在重建环境或Cloud Manager部署后未保留AEM as a Cloud Service发布层上的用户帐户或组成员身份时问题的解决方案。 |
| 2026 年 10 月 | [通过流式传输、转发或Java栈栈CDN日志访问AEM Edge函数日志](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43083) | 新文章 | 了解当Edge函数运行时日志未在Cloud Manager中作为单独的AEM服务日志类型列出，并且您需要找到访问这些日志的适当方法时问题的解决方案。 |
| 2026 年 10 月 | [解决在自定义UI测试期间由于ESM/CommonJS兼容性而导致AEM Cloud Manager部署失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43171) | 新文章 | 了解当AEM Cloud Manager部署管道在自定义UI测试步骤中失败，并出现&#x200B;*ERR_REQUIRE_ESM等错误时问题的解决方案：必须使用导入来加载ES模块*。 |
| 2026 年 10 月 | AEM as a Cloud Service[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43228)中的Cloud Manager部署失败，调度程序为空.zip | 新文章 | 了解当使用`ignoreWebTierConfig=true`配置的全栈栈管道在AEM as a Cloud Service中生成空`dispatcher.zip`并应用它导致部署错误时问题的解决方案。 |
| 2026 年 10 月 | 暂存环境中的[AEM Cloud Manager Dispatcher部署管道运行缓慢](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43315) | 新文章 | 了解针对以下问题的解决方案：在暂存转出期间，AEM Cloud Manager Dispatcher部署管道所需的时间显着比平常长，并且没有出现明确错误。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中将Cloud Manager可靠性等级从C提高为A](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43469) | 新文章 | 了解当Cloud Manager管道报告的可靠性等级为C并且代码质量报告在AEM as a Cloud Service中识别了多个OakPAL错误调查结果时问题的解决方案。 |
| 2026 年 10 月 | [在AEM Cloud Manager中无法只使用一个证书更新域映射的SSL证书](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43523) | 新文章 | 了解当在AEM Cloud Manager中为域映射更新SSL证书并且重新选择它不会将续订的证书推送到CDN时，选择下拉列表中只显示一个证书时问题的解决方案。 |
| 2026 年 10 月 | [正在解决AEM as a Cloud Service中CDN缓存清除的&#x200B;*未授权清除*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43800) | 新文章 | 了解当AEM as a Cloud Service中的CDN清除请求因&#x200B;*未授权清除而失败时问题的解决方案。 请通过配置管道设置PURGE密钥。* 错误，即使配置管道成功完成。 |
| 2026 年 10 月 | 在Adobe Experience Manager中进行NIMU升级期间，[Cloud Manager部署似乎卡住](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43808) | 新文章 | 了解当AEM Cloud Manager部署在`wait-for-env-ready`步骤暂停并在非中断维护升级(NIMU)过程中似乎无限期运行时的问题的解决方案。 |
| 2026 年 10 月 | [无法在Adobe Experience Manager Cloud Manager中加载Content AI源选项卡](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43852) | 新文章 | 了解当Cloud Manager中的[!UICONTROL Content AI源]选项卡加载失败并显示&#x200B;*出现问题 — 我们无法加载您的内容源时问题的解决方案。 请稍后重试。* 错误。 |
| 2026 年 10 月 | [Cloud Manager API返回&#x200B;*API密钥无效* (403003)错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50713) | 新文章 | 了解当对Cloud Manager API的调用返回&#x200B;*API密钥无效* (403003)错误，原因是未订阅Cloud Manager API的Adobe Developer Console项目的凭据存在此错误，此问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud Manager：暂存环境不可用于仅配置非生产管道](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51106) | 新文章 | 了解当您在AEM Cloud Manager中创建用于部署`/config`更改的非生产管道时，暂存环境未显示在环境选择器中时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：出站IP更改和IP允许列表要求](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43302) | 新文章 | 了解当出站IP地址发生更改并且与AEM as a Cloud Service或Workfront的连接因来自未列入允许列表的新IP的流量而失败时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中生成[文档失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42927) | 新文章 | 了解当AEM as a Cloud Service生产环境中的文档生成工作流失败，并且日志在对`/ims/exchange/jwt`的POST请求中显示HTTP 400错误且未返回访问令牌时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms as a Cloud Service：代码编辑器在自适应Forms规则编辑器中不可用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43336) | 新文章 | 了解当本地AEM Forms的自适应Forms规则编辑器中可用的代码编辑器在AEM Forms as a Cloud Service中不存在时问题的解决方案。 |
| 2026 年 10 月 | [在AEM自适应Forms中具有最小重复次数和可见性规则的可重复面板行为](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43739) | 新文章 | 了解在AEM自适应Forms核心组件的可重复面板上将[!UICONTROL 最小重复次数]设置为`0`时问题的解决方案。这样做不会生成零实例初始渲染，并且显示/隐藏规则无法可靠地控制每个实例。 |
| 2026 年 10 月 | [在AEM Sites环境中处理创作模式差异时出错](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-41834) | 新文章 | 了解当组件错误在较低的AEM as a Cloud Service环境中内联显示但导致整个页面在较高环境中的创作模式下呈现失败时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Sites：新编辑器中的[!UICONTROL 重命名]按钮不重命名内容片段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42463) | 新文章 | 了解当AEM Sites新编辑器中的[!UICONTROL 重命名]按钮似乎已完成但未更改内容片段名称时问题的解决方案。 |
| 2026 年 10 月 | [无法直接从AEM as a Cloud Service中的站点控制台复制站点资源详细信息](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42892) | 新文章 | 了解问题的解决方案，在迁移到AEM as a Cloud Service后，您无法直接从站点控制台高亮显示和复制站点资源详细信息，例如标题、名称、上次修改时间和发布时间。 |
| 2026 年 10 月 | [流量尖峰警报出现在AEM as a Cloud Service中的源位置](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43103) | 新文章 | 了解当您在AEM as a Cloud Service Sites生产环境中收到自动警报，指示源位置存在流量尖峰时问题的解决方案。 |
| 2026 年 10 月 | [功能分支代码更改未同步到AEM Cloud Service通用编辑器中的作者](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43235) | 新文章 | 了解当推送到功能分支的CSS或[!DNL JavaScript]更改出现在分支的预览URL中，但未在AEM Author上的通用编辑器画布中显示或严重延迟时，该问题的解决方案。 |
| 2026 年 10 月 | [GraphQL持久查询未在AEM创作实例中加载](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43237) | 新文章 | 了解当持久查询列表未在GraphQL编辑器中的Dispatcher后面的AEM 6.5 LTS Managed Services Author实例上加载，而列表在Publisher上正确加载时问题的解决方案。 |
| 2026 年 10 月 | AEM as a Cloud Service中的GraphQL持久查询出现[CORS错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43364) | 新文章 | 了解当浏览器向AEM as a Cloud Service中的GraphQL持久查询端点报告跨域请求的CORS错误，因为CDN响应缺少`Access-Control-Allow-Origin`标头时问题的解决方案。 |
| 2026 年 10 月 | [修复AEM as a Cloud Service中GraphQL持久查询的CORS标头缺失](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43368) | 新文章 | 了解当AEM as a Cloud Service中GraphQL持久查询的重复跨域请求收到缓存的CDN响应而没有所需的`Access-Control-Allow-Origin`标头时问题的解决方案。 |
| 2026 年 10 月 | [在AEM中进行语言复制期间，不会重写体验片段中嵌入的富文本链接](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43374) | 新文章 | 了解当体验片段中嵌入的富文本组件中的URL在AEM中的语言副本后仍指向源语言页面时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager中创建了内容片段内容还原和意外版本](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43460) | 新文章 | 了解当AEM中的内容片段内容在更新后恢复到旧版本，并且每次在不更改的情况下打开和关闭片段会创建新版本时问题的解决方案。 |
| 2026 年 10 月 | AEM Site Optimizer设置中缺少[[!DNL Jira] 集成部分](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43562) | 新文章 | 了解当AEM Sites Optimizer [!UICONTROL 设置]页面上不再显示授权[!DNL Jira]集成部分时问题的解决方案。 |
| 2026 年 10 月 | [在网络条件较差的情况下改进AEM as a Cloud Service中的通用编辑器性能](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43729) | 新文章 | 了解当AEM as a Cloud Service中的通用编辑器响应缓慢、画布更新延迟或作者使用高延迟或低带宽网络时出现超时对话框时问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud Sites：正文内容未在媒体模块组件中呈现](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44393) | 新文章 | 了解当媒体模块组件中的正文(RTE)内容在已发布的AEM Cloud Sites页面上未呈现给最终用户，而在创作和预览中按预期显示时，问题的解决方案。 |
| 2026 年 10 月 | [正在解决 [!DNL jackson-databind] 升级后的反序列化失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-48665) | 新文章 | 了解AEM Sites中的表单在升级[!DNL jackson-databind]后加载失败并且错误消息包含引用`PropertyNamingStrategy$SnakeCaseStrategy`的&#x200B;*TypeNotPresentException*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | 在AEM中导出内容片段后[语言变体重叠](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43252) | 新文章 | 了解当从AEM导出后，不同语言的内容片段在Adobe Target中显示为同一选件时（因为它们共享同一个Target选件ID），该问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets传输中缺少Workfront元数据的疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43559) | 新文章 | 了解当从Workfront发送的文件出现在AEM Assets中，但一个或多个预期的映射元数据值为空时，问题的解决方案。 |
| 2026 年 10 月 | [在AEM Guides publishditamap工作流程期间重新评估动态基线](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42346) | 新文章 | 了解问题的解决方案，以帮助您了解在AEM Guides的`publishditamap`工作流中，如何在发布时重新评估动态基线。 |
| 2026 年 10 月 | [Adobe Experience Manager 6.5.24中的Java栈和元空间内存不足问题疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43298) | 新文章 | 了解AEM 6.5.24 Author和Publisher实例无响应或出现重复&#x200B;*java.lang.OutOfMemoryError而崩溃时的问题的解决方案：随着栈或元空间使用率的增长，出现Java栈空间*&#x200B;错误。 |
| 2026 年 10 月 | [在安全修补程序之后，在AEM 6.5中验证 [!DNL Handlebars.js] 4.7.7是否移除或升级](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43340) | 新文章 | 了解当对本地AEM 6.5的安全扫描在针对其漏洞应用安全修补程序后继续检测到[!DNL Handlebars.js] 4.7.7时问题的解决方案。 |
| 2026 年 10 月 | [解决AEM 6.5创作速度缓慢和发布操作失败，原因是卡住了[!UICONTROL 测试连接]线程](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43427) | 新文章 | 了解当AEM 6.5创作实例缓慢或无响应、发布到发布者失败或延迟，以及线程转储显示多个停滞的复制[!UICONTROL 测试连接]线程时问题的解决方案。 |
| 2026 年 10 月 | 由于AEM缩小失败，[JavaScript 6.5 SP21导航无响应](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43448) | 新文章 | 了解当AEM 6.5 SP21中的控制台导航和用户图标操作在受影响的发布服务器上无响应，并且日志针对客户端库请求显示重复的HTTP 500错误时，该问题的解决方案。 |
| 2026 年 10 月 | [解决启动AEM Forms Designer 6.5时缺少的DLL错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43410) | 新文章 | 了解当AEM Forms Designer 6.5 （32位）无法在[!DNL Windows]上启动且出现错误&#x200B;*时问题的解决方案。由于您的计算机*&#x200B;中缺少DLL_NAME.dll，因此程序无法启动。 |
| 2026 年 10 月 | [视频字幕未在S7播放器](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-30379)中的正确时间消失 | 新文章 | 了解当S7 (Scene7)视频播放器中的视频字幕未在WebVTT结束时间消失并保持可见直到出现下一个字幕时问题的解决方案。 |
| 2026 年 10 月 | 由于缺少SSL客户端证书身份验证处理程序，AEM 6.5.1中的[MSSL复制失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43123) | 新文章 | 了解当AEM 6.5.1中的双方SSL (MSSL)复制失败并出现&#x200B;*401未授权*&#x200B;错误时（即使HTTPS以及KeyStore和TrustStore配置正确），该问题的解决方案。 |
| 2026 年 10 月 | [AEM Managed Services：通过OSGi配置在DAM中启用SVG摄取](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-31770) | 新文章 | 了解当您在AEM Managed Services上将SVG文件上传到DAM时，这些文件被拒绝时问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager Assets中的疑难解答 [!DNL YouTube] 发布问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42133) | 新文章 | 了解当视频资源在AEM DAM中可见，但未显示在连接的[!DNL YouTube]渠道上，且没有清除错误消息或上传状态时，问题的解决方案。 |
| 2026 年 10 月 | 在AEM Assets中生成PDF和HTML5输出期间[解决&#x200B;*DXML_MESSAGE_0002*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43356) | 新文章 | 了解在AEM Assets中使用发布微服务生成PDF和HTML5输出时断时续地失败并出现&#x200B;*DXML_MESSAGE_0002 (HTTP 400)*&#x200B;错误时，此问题的解决方案。 |
| 2026 年 10 月 | [访问Adobe Experience Manager Assets中的资源活动和审核日志](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43436) | 新文章 | 了解当您需要在AEM Assets中查看资源操作（例如上传、编辑、删除和共享）时（包括用户和每个操作的记录日期）问题的解决方案。 |
| 2026 年 10 月 | [按元数据字段自定义AEM Assets Insights仪表板筛选器](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43627) | 新文章 | 了解当您无法在AEM Assets Insights仪表板中按自定义元数据字段（如资源类型、收藏集或设计器）过滤、分组下载或查看计数时问题的解决方案。 |
| 2026 年 10 月 | [使用Editor 2.0](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43685)在AEM Assets创作模式下启用内联XML注释 | 新文章 | 了解当校样器和作者需要在AEM Assets创作模式下通过编辑器2.0添加内联XML注释时，该问题的解决方案，但默认情况下，注释仅在审阅者模式下可用。 |
| 2026 年 10 月 | [AEM Dynamic Media：将图像作为WebP传送时强制PNG输出](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43752) | 新文章 | 了解当配置用于PNG输出的AEM Dynamic Media预设中的图像作为WebP交付时（即使您将`bfc=off`参数添加到预设后），该问题的解决方案。 |
| 2026 年 10 月 | [由于音频编解码器不兼容，Dynamic Media视频无法在 [!DNL Firefox] 中播放](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43859) | 新文章 | 了解当使用现成视频预设编码的Dynamic Media视频在[!DNL Google Chrome]和[!DNL Microsoft Edge]中工作时，无法在[!DNL Mozilla Firefox]中加载或播放时问题的解决方案。 |
| 2026 年 10 月 | 对于Adobe Express中的有限许可证用户，[AEM Assets文件夹显示为空](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43896) | 新文章 | 了解当人员分配了有限许可证且投放产品配置文件在Adobe Express中看到空AEM Assets文件夹时问题的解决方案。 |
| 2026 年 10 月 | [自定义子域未显示在AEM Assets投放URL的[!UICONTROL 复制URL]中](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43904) | 新文章 | 了解当AEM Assets中的[!UICONTROL 复制URL]显示默认交付URL而不是您配置的自定义子域时问题的解决方案。 |
| 2026 年 10 月 | [从自定义AEM工作流中的页面发布中排除体验片段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43129) | 新文章 | 了解当自定义AEM Sites页面发布工作流使用页面发布引用的体验片段时，即使作者按单独的计划管理和发布这些片段时，该问题的解决方案。 |
| 2026 年 10 月 | [迁移后，AEM存储库搜索未返回带有DITA映射或主题过滤器的结果](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42828) | 新文章 | 了解当使用DITA Map或DITA主题过滤器进行存储库搜索时，当您迁移到新的本地AEM 6.5 LTS实例后，在没有这些过滤器的搜索下不会返回任何结果时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM Workfront增强型连接器错误： *找不到此云服务的连接配置*](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43797) | 新文章 | 了解在保存连接器配置后AEM Workfront增强型连接器集成失败并且显示&#x200B;*未找到此云服务的*&#x200B;连接配置时问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud Manager生产部署在长时间执行后失败，出现系统问题错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43806) | 新文章 | 了解当AEM Cloud Manager生产部署持续进行数小时，出现一般系统问题错误而失败并阻止后续部署时，该问题的解决方案。 |
| 2026 年 10 月 | 由于Oak索引版本冲突，[AEM Cloud Manager部署失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43834) | 新文章 | 了解当AEM Cloud Manager部署在重新索引步骤期间失败，并出现&#x200B;*无法比较索引*&#x200B;错误，因为存在具有较高主版本的索引时无法添加新的自定义索引时问题的解决方案。 |
| 2026 年 10 月 | [在AEM Managed Services中的蓝/绿部署期间，将绿色发布实例扩展到8XL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-46113) | 新文章 | 了解在活动Cloud Manager蓝/绿部署期间，无法在AEM Managed Services中将绿色发布实例扩展到8XL时问题的解决方案。 |
| 2026 年 10 月 | 升级AEM Forms后[修复反序列化错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-41270) | 新文章 | 了解在将AEM Forms JEE升级到[!DNL IBM WebSphere]上的6.5.25后，在服务器启动和Configuration Manager执行期间出现大量&#x200B;*不允许对类*&#x200B;进行反序列化错误时问题的解决方案。 |
| 2026 年 10 月 | 升级到 [!DNL Windows Server 2022]&#x200B;[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43370)后AEM Forms冒烟测试失败 | 新文章 | 了解当您从[!DNL Windows Server 2019]升级到[!DNL Windows Server 2022]后，AEM Forms烟雾测试失败并且文档生成无法正常工作时的问题的解决方案。 |
| 2026 年 10 月 | [AEM Forms 6.5 LTS支持 [!DNL Java] 8/11客户端](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44564) | 新文章 | 在不清楚使用AEM Forms 6.5 LTS的[!DNL Java 8]和[!DNL Java 11]客户端操作是否处于受支持和QA测试的范围内时，了解此问题的解决方案。 |
| 2026 年 10 月 | [请求Adobe Experience Manager Forms 6.5的支持扩展](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-47899) | 新文章 | 了解当您的组织在其发布的扩展支持结束日期之后需要对AEM Forms 6.5的支持时，该问题的解决方案。 |
| 2026 年 10 月 | [json2html服务在AEM云站点中返回&#x200B;*未授权*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43408) | 新文章 | 了解当您在AEM Cloud Sites中配置内容叠加时，如果对json2html服务的POST请求返回&#x200B;*未授权*&#x200B;错误，即使初始叠加配置成功也是如此，该问题的解决方案。 |
| 2026 年 10 月 | [正在解决单个AEM发布实例上由于OSGi包不一致而出现的HTTP 500错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43421) | 新文章 | 了解当一个AEM Managed Services发布实例在多个应用程序URL中返回大量HTTP 500错误，而其他Publish实例正常提供流量时，问题的解决方案。 |
| 2026 年 10 月 | [在AEM中使用statfileslevel配置Dispatcher缓存失效作用域](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43432) | 新文章 | 了解当您希望在一个网站子树下发布内容时，如何解决此问题，以便仅在AEM Dispatcher中使该网站的缓存内容失效，而不会使独立的同级网站子树失效。 |
| 2026 年 10 月 | [在Adobe Experience Manager Sites中按组限制体验片段删除操作可见性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43444) | 新文章 | 了解当体验片段的[!UICONTROL 删除]操作对主AEM Sites体验片段控制台中的所有用户可见时（无论组成员身份如何），该问题的解决方案。 |
| 2026 年 10 月 | AEM智能标记中缺少&#x200B;[*服务URL*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43175) | 新文章 | 了解当AEM LTS中的智能标记无法标记资产且日志显示&#x200B;*服务URL缺失*&#x200B;警告时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中寻址 [!DNL Underscore.js] 和 [!DNL jQuery] 的安全扫描结果[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43271) | 新文章 | 了解当AEM 6.5.x报告[!DNL Underscore.js] 1.13.4 (CVE-2026-27601)和[!DNL jQuery] 1.12.4具有多个漏洞时问题的解决方案。 |
| 2026 年 10 月 | AEM LTS升级和内容刷新后[信任库恢复失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-46961) | 新文章 | 了解当AEM LTS升级且内容从生产刷新到开发、SAML身份验证受到影响，并且AEM创作登录页面无法通过HTTPS访问后truststore无法恢复时的问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager： AEM 6.5 LTS SP1、SP2和SP3](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50991)的存储库要求 | 新文章 | 了解当AEM 6.5 LTS SP1、SP2和SP3中的已知问题损坏存储库并导致&#x200B;*SegmentNotFoundException* (SNFE)时问题的解决方案。 |
| 2026 年 10 月 | AEM 6.5 LTS升级期间的[MongoMK创作群集拓扑](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43416) | 新文章 | 了解在就地升级到AEM 6.5 LTS期间，当系统指示您将MongoMK创作群集减少到一个活动创作实例，并将[!DNL MongoDB]副本集减少到一个成员时，该问题的解决方案，并且您需要知道这从技术上是否必要。 |
| 2026 年 10 月 | [AEM Dispatcher：通过刷新缓存解决缺少的内容](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-41832) | 新文章 | 了解当您在AEM中发布的内容更新未以不一致的方式在某些实时网站上出现在不同的网站路径中时问题的解决方案。 |
| 2026 年 10 月 | [解决自定义索引配置导致AEM Cloud Service中的页面操作出现性能问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42087) | 新文章 | 了解当AEM Cloud Service中的页面移动、删除、复制或语言复制操作花费异常长时间或未完成并阻止内容创作时，问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中解决SMTP连接故障](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42399) | 新文章 | 了解从AEM as a Cloud Service发送到外部SMTP端点的电子邮件失败且连接超时，并且日志显示&#x200B;*MailConnectException*&#x200B;和&#x200B;*SocketTimeoutException*&#x200B;错误时问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager中，[IMS用户创建失败，出现不受信任或无人认领的域错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42454) | 新文章 | 了解当某些域中的电子邮件地址在AEM中创建用户失败，并出现IMS错误（如&#x200B;*从其他组织拥有的身份验证src*&#x200B;邀请用户非法，或&#x200B;*在请求中未找到有效用户*）时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM创作自定义servlet页面在Experience Cloud Shell中加载旋转图标时卡住](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42461) | 新文章 | 了解当通过Experience Cloud Shell iframe访问时，AEM Author中的自定义servlet页面仍然隐藏在加载旋转图标后面，而直接访问servlet URL时问题的解决方案。 |
| 2026 年 10 月 | 在AEM中配置预览IP允许列表后，[解决&#x200B;*403访问被拒绝*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42490) | 新文章 | 了解当向Cloud Manager中的预览IP允许列表添加特定IP地址后，访问AEM as a Cloud Service预览服务仍返回&#x200B;*403 Not allowed*&#x200B;错误时问题的解决方案。 |
| 2026 年 10 月 | [AEM收件箱通知计数在阅读或完成项目后不会立即更新](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42711) | 新文章 | 了解当全局标题中的AEM收件箱通知徽章在阅读或完成收件箱项目后未立即更新时问题的解决方案。 |
| 2026 年 10 月 | [对AEM as a Cloud Service Developer Console中的503和未知错误进行故障排除](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42755) | 新文章 | 了解当旧版AEM as a Cloud Service Developer Console返回&#x200B;*503服务不可用*&#x200B;并且新Developer Console显示未知错误，且OSGi包视图中未列出任何包时，问题的解决方案。 |
| 2026 年 10 月 | [使用专用出口IP](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42864)AEM as a Cloud Service出站流量 | 新文章 | 了解当外部服务在接受来自AEM as a Cloud Service的连接之前需要稳定的源IP，并且您无法依赖AEM的默认出站IP（因为它可以更改）时，该问题的解决方案。 |
| 2026 年 10 月 | [在缺少代理键时清除大量缓存的AEM内容](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42874) | 新文章 | 了解当AEM as a Cloud Service CDN中较旧的缓存对象没有新的`Surrogate-Key`标头，因此使用该键清除不会使这些对象无效，并且不希望完全清除CDN时问题的解决方案。 |
| 2026 年 10 月 | [识别Adobe Experience Manager as a Cloud Service中主区域和辅助区域的专用出口IP](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42884) | 新文章 | 了解当DNS查找程序主机名返回一个IP地址，并且您需要在AEM as a Cloud Service中为每个已配置的发布区域识别专用出口IP时，问题的解决方案。 |
| 2026 年 10 月 | [[!DNL Azure Blob] 日志转发未在AEM as a Cloud Service中创建日期分区文件夹](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42888) | 新文章 | 了解当AEM as a Cloud Service将日志转发到[!DNL Azure Blob Storage]的文件存储在日志类型文件夹而非日期分区文件夹下时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service环境在Developer Console中显示为休眠](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43093) | 新文章 | 了解当AEM as a Cloud Service环境在新版Developer Console中显示为[!UICONTROL 已休眠]状态时问题的解决方案，即使环境保持活动状态并且可供访问。 |
| 2026 年 10 月 | [DAM资源在AEM as a Cloud Service中仍处于处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43097) | 新文章 | 了解当在AEM as a Cloud Service中上传的资源保持在[!UICONTROL 正在处理]状态，未生成任何演绎版，无法发布资源且未生成Scene7 URL时问题的解决方案。 |
| 2026 年 10 月 | [[!DNL Lighthouse] 报告未在AEM as a Cloud Service中打开或从“体验审核”下载](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43110) | 新文章 | 了解当您无法从AEM as a Cloud Service中的[!UICONTROL 体验审核]报表打开或下载[!DNL Lighthouse]分数时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：访问资源报告需要管理员权限](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43127) | 新文章 | 了解当`/content/dam`上具有`jcr:all`权限的AEM as a Cloud Service用户无法访问[!UICONTROL 工具] > [!UICONTROL Assets] > [!UICONTROL 报告]时问题的解决方案。 |
| 2026 年 10 月 | [无法下载Adobe Experience Manager as a Cloud Service中的历史访问日志](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43134) | 新文章 | 了解当特定历史日期的发布、Dispatcher或其他AEM as a Cloud Service环境日志在Cloud Manager中不可下载时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：内容片段触屏UI编辑器中的复合字段编辑限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43168) | 新文章 | 了解当内容片段中的复合字段在AEM as a Cloud Service内容片段触屏UI编辑器中保持可编辑状态并且未强制执行预期的编辑限制时，问题的解决方案。 |
| 2026 年 10 月 | 在AEM的产品详细信息页面上切换产品配置时，出现[灰色框](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43173) | 新文章 | 了解当AEM产品详细信息页面上的主产品图像在产品配置之间切换时加载新图像之前短暂显示灰色框时该问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud中的计划启动项由于嵌套启动项结构而不发布](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43179) | 新文章 | 了解当从AEM as a Cloud Service中的其他启动项创建的计划启动项未在配置时间发布且源页面未更新时，该问题的解决方案。 |
| 2026 年 10 月 | 由于AEMaaCS中有多个Content-Disposition标头，[图像加载失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43186) | 新文章 | 了解当AEM as a Cloud Service中的某些JPEG图像无法在[!DNL Chrome]等浏览器中加载时出现错误（如&#x200B;*ERR_RESPONSE_HEADERS_MULTIPLE_CONTENT_DISPOSITION*）时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager中隐藏和安全删除大型DAM文件夹](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43196) | 新文章 | 了解当对大型AEM Assets DAM文件夹应用广泛拒绝权限时会降低性能，并且在一次操作中删除文件夹会降低系统速度时，该问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service创作环境返回HTTP 503且无法访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43198) | 新文章 | 了解当AEM as a Cloud Service创作环境变得不可访问并返回&#x200B;*HTTP 503服务不可用*&#x200B;错误（通常在严重缓慢之后）时问题的解决方案。 |
| 2026 年 10 月 | [解决Adobe Experience Manager as a Cloud Service中的创作权限问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43204) | 新文章 | 了解当创作用户组的成员无法在一个AEM as a Cloud Service环境中创建或编辑内容，而在配置相同的环境中成功创作时，问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43262)中执行意外的[!UICONTROL 还原树]操作后的恢复选项 | 新文章 | 了解当AEM as a Cloud Service中意外的[!UICONTROL 还原树]操作导致特定内容路径下的许多页面丢失或回滚时，该问题的解决方案。 |
| 2026 年 10 月 | [内容复制工具不支持AEM as a Cloud Service中的发布实例](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43266) | 新文章 | 了解当您需要直接将内容复制到AEM as a Cloud Service发布实例或从中复制内容时，该问题的解决方案，但内容复制工具仅支持创作环境。 |
| 2026 年 10 月 | [AEM Dispatcher：解决无法访问的内容路径](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43283) | 新文章 | 了解当特定内容路径无法通过AEM Dispatcher访问并在浏览器中返回错误，而其他内容路径仍可访问时的问题解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service：解决具有持久查询API和OAuth服务器到服务器的&#x200B;*403缺少所需作用域*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43296) | 新文章 | 了解当使用OAuth服务器到服务器凭据访问AEM as a Cloud Service持久查询API端点失败并出现&#x200B;*403禁止的缺少所需范围*&#x200B;错误时，此问题的解决方案。 |
| 2026 年 10 月 | [由于Dispatcher statfileslevel配置，Adobe Experience Manager中的内容更新延迟](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43326) | 新文章 | 了解当从AEM创作环境发布的页面或资产更新需要几个小时才能显示在发布环境中时问题的解决方案，即使复制队列会快速处理项目。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中为外部SaaS集成配置IP允许列表](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43328) | 新文章 | 了解当外部SaaS工具要求访问AEM as a Cloud Service Assets Author服务的网络权限，才能通过AEM Assets HTTP API查询资源元数据时问题的解决方案。 |
| 2026 年 10 月 | [AEM Content Hub功能、限制和迁移注意事项](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43344) | 新文章 | 了解在评估迁移到AEM Content Hub的过程中遇到的问题的解决方案，并需要了解其功能、许可模式、自定义选项和限制。 |
| 2026 年 10 月 | [AEM as a Cloud Service日志不能直接识别独特访客或并发用户](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43348) | 新文章 | 了解当您需要估算AEM as a Cloud Service网站的每日独特访客数和并发会话数，但CDN和AEM日志记录的是请求数据而非访客或会话数据时，该问题的解决方案。 |
| 2026 年 10 月 | [内容传输工具升级后，AEM Assets中基于CSV的资源引入失败疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43354) | 新文章 | 了解解决以下问题的方案：在内容传输工具升级后，即使资源提取成功完成，基于CSV的资源摄取到AEM as a Cloud Service时仍显示[!UICONTROL 失败]状态。 |
| 2026 年 10 月 | [[!DNL Dynatrace] 在Adobe Experience Manager as a Cloud Service中处理组命名还原为默认值](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43358) | 新文章 | 了解当AEM as a Cloud Service环境的[!DNL Dynatrace]进程组名称恢复为默认值、多个环境在同一个进程组下报告并触发错误警报时问题的解决方案。 |
| 2026 年 10 月 | 在Edge Delivery服务中使用 [!DNL Azure AD] 组时[解决&#x200B;*403禁止访问*&#x200B;错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43362) | 新文章 | 了解当权限配置文件中配置的[!DNL Azure AD]组的成员在AEM Edge Delivery Services中使用预览或发布时收到&#x200B;*403 Forbidden*&#x200B;错误时问题的解决方案。 |
| 2026 年 10 月 | [大型重定向电子表格可能会阻止Adobe Experience Manager中的分发队列](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43366) | 新文章 | 了解在AEM生产环境中发布大型重定向电子表格时阻止分发队列并阻止发布所有其他内容时问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service Edge Delivery Services[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43418)中，HTML title元素使用[!UICONTROL Page Title]而不是jcr:title | 新文章 | 了解在使用Franklin Page模板创建的AEM Edge Delivery Services页面上呈现的HTML `<title>`元素显示[!UICONTROL Page Title]值而不是`jcr:title`时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中为RSS馈送和公告提供[XML内容投放](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43423) | 新文章 | 了解这个问题的解决方案，此时您需要通过AEM as a Cloud Service中的公共URL以XML格式公开RSS馈送或公告内容，但不支持从AEM Assets直接交付XML文件。 |
| 2026 年 10 月 | [AEM文件夹API返回HTTP 200，而不是现有文件夹的HTTP 409](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43462) | 新文章 | 了解当您创建已存在的文件夹时，AEM as a Cloud Service文件夹API在有效负载而不是&#x200B;*HTTP 409冲突*&#x200B;中返回HTTP 200 OK且出现冲突错误时问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中修复过时的依赖项和已弃用的API](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43471) | 新文章 | 了解当Cloud Manager运行状况评估报告AEM as a Cloud Service中过时的依赖项和已弃用的API使用情况时问题的解决方案，即使环境运行的是最新的AEM SDK和[!DNL Java]版本时也是如此。 |
| 2026 年 10 月 | [WebP格式在AEM as a Cloud Service中的Dynamic Media图像预设中不可用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43485) | 新文章 | 了解AEM as a Cloud Service Dynamic Media中[!UICONTROL 工具] > [!UICONTROL Assets] > [!UICONTROL 图像预设]下的[!UICONTROL 格式]下拉菜单中无WebP可用时问题的解决方案。 |
| 2026 年 10 月 | 在AEM as a Cloud Service中，共享内容的[Dispatcher缓存失效](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43540) | 新文章 | 了解当您在AEM as a Cloud Service中发布共享内容后，使用体验片段、内容片段或DAM资源的页面显示较旧的输出时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager as a Cloud Service中验证并启用Assets视图UI可扩展性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43598) | 新文章 | 了解当已部署的自定义UI扩展（如Assets视图标题中的按钮）未显示在AEM as a Cloud Service中时，该问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service中管理页面版本和审核日志保留](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43601) | 新文章 | 了解当AEM as a Cloud Service创作中缺少历史页面版本并且某些日期或事件的审核日志条目不再可用时问题的解决方案。 |
| 2026 年 10 月 | [在 [!DNL New Relic] 中查找Adobe Experience Manager的创作和发布实例](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43616) | 新文章 | 了解当AEM Author和Publish实例由于名称包含区域标识符后缀而无法立即在[!DNL New Relic]监视仪表板中可见时问题的解决方案。 |
| 2026 年 10 月 | 由于AEM as a Cloud Service中的大型调试查询，[转出作业变慢或停滞](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43632) | 新文章 | 了解当AEM as a Cloud Service创作环境中的转出作业仍处于排队状态或未完成状态，延迟内容启动并且内存和CPU使用率较高时问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Experience Manager as a Cloud Service中响应递归目录列表请求](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43634) | 新文章 | 了解当安全评估请求为您的AEM as a Cloud Service环境提供Web服务器的完整递归目录列表(RDL)时问题的解决方案。 |
| 2026 年 10 月 | [使用statfileslevel和gracePeriod的AEM Dispatcher缓存失效](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43668) | 新文章 | 了解这个问题的解决方案，当您不确定在使用`statfileslevel`和`gracePeriod`配置的AEM Dispatcher中的内容更新后是否需要显式缓存清除以列出页面。 |
| 2026 年 10 月 | 在AEM as a Cloud Service中迁移内容传输工具后，[发布的查询结果不完整](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43771) | 新文章 | 了解当内容传输工具迁移后，即使存储库中存在内容，AEM as a Cloud Service发布层上的查询返回的结果也少于预期时，该问题的解决方案。 |
| 2026 年 10 月 | [解决AEM Content Hub中的ABAC规则引起的资源可见性问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43785) | 新文章 | 了解当组在AEM Content Hub中看不到预期资源、仅具有特定元数据值的资源可见，或者Content Hub UI对于某些组显示空白时，该问题的解决方案。 |
| 2026 年 10 月 | [在AEM as a Cloud Service的高流量营销活动中保持增加的面板容量](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43789) | 新文章 | 了解当您需要在AEM as a Cloud Service中增加发布和Dispatcher面板容量以在高流量的营销活动期间保持活动状态时，问题的解决方案。 |
| 2026 年 10 月 | [了解AEM as a Cloud Service中DAM资源的HTTP 302响应](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43802) | 新文章 | 了解当AEM as a Cloud Service中的Dispatcher访问日志针对无法从客户端复制的DAM资源显示间歇性HTTP 302响应时，问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service RDE中的表单提交失败并出现邮件服务配置错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43839) | 新文章 | 了解在电子邮件发送步骤期间，AEM as a Cloud Service快速开发环境(RDE)中的表单提交失败并出现&#x200B;*邮件服务配置无效*&#x200B;错误时，该问题的解决方案。 |
| 2026 年 10 月 | 由于AEMaaCS中的CORS配置，无法修改[通用编辑器组件属性](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43874) | 新文章 | 了解当AEM as a Cloud Service通用编辑器显示组件内容和属性但无法应用对组件数据的更改时，以及没有明确错误消息时，该问题的解决方案。 |
| 2026 年 10 月 | [由于CORS和HTTP 500错误，无法在通用编辑器中编辑或添加组件](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43881) | 新文章 | 了解在AEM通用编辑器中编辑或添加组件时问题的解决方案，浏览器控制台显示有关`x-aem-affinity-type`标头的CORS错误，并且`/details`请求返回&#x200B;*HTTP 500内部服务器错误*。 |
| 2026 年 10 月 | AEM as a Cloud Service[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43918)中的大型.mov文件出现&#x200B;*RenditionFormatUnsupported*&#x200B;错误 | 新文章 | 了解在将约17 GB或更高容量的`.mov`视频文件上传到AEM as a Cloud Service时出现的问题的解决方案，资源处理失败并出现&#x200B;*RenditionFormatUnsupported*&#x200B;错误且未生成任何演绎版。 |
| 2026 年 10 月 | 由于 [!DNL MongoDB] 不稳定[AEM as a Cloud Service创作中断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43920) | 新文章 | 了解当AEM as a Cloud Service创作环境暂时不可用数分钟且监控显示[!DNL MongoDB]写入延迟尖峰时问题的解决方案。 |
| 2026 年 10 月 | [AEM as a Cloud Service OIDC身份验证因JWK设置大小限制而失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43987) | 新文章 | 了解当AEM as a Cloud Service中的OIDC身份验证请求失败，并且日志显示&#x200B;*无法验证令牌：无法检索远程JWK集时问题的解决方案：超出配置的51200字节输入限制*。 |
| 2026 年 10 月 | [在Adobe Experience Manager中将自定义Brand Portal与发现代理集成](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44340) | 新文章 | 了解当您需要将自定义Brand Portal与AEM中的发现代理集成时问题的解决方案。 |
| 2026 年 10 月 | [AEM Publish实例重新启动后，通过CDN提供间歇性空白或不完整的页面](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-45480) | 新文章 | 了解当空白或部分呈现的具有HTTP 200 OK状态的页面在AEM Publish实例重新启动后通过CDN间歇性地显示，并且CDN缓存不完整的响应时，问题的解决方案。 |
| 2026 年 10 月 | [在AEM Dynamic Media中隔离非生产和生产环境](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-47157) | 新文章 | 了解在非生产环境中发布或取消发布资产时问题的解决方案，这些解决方案会更改生产环境中的资产状态，因为两个环境共享一个AEM Dynamic Media公司。 |
| 2026 年 10 月 | 由于自定义验证中的HEAD分离，[AEM Cloud Manager生成失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50643) | 新文章 | 了解当AEM as a Cloud Service中的Cloud Manager管道生成在自定义验证步骤期间失败，并出现&#x200B;*java.lang.IllegalStateException：当存储库处于分离的HEAD状态时，无法确定当前Git分支*&#x200B;错误时的问题的解决方案。 |
| 2026 年 10 月 | [Adobe Experience Manager Assets Content Hub中缺少默认排序选项](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43439) | 新文章 | 了解当启用排序后默认排序选项未显示在AEM Assets Content Hub界面的右上角区域时问题的解决方案。 |
| 2026 年 10 月 | [使用CSV导入修复不完整的AEM Assets批量元数据更新](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44028) | 新文章 | 了解当超过100个AEM Assets的批量元数据更新报告所有选定资源更新成功，但只有部分资源收到更新值时问题的解决方案。 |
| 2026 年 10 月 | [无法为AEM Assets中的特定收藏集生成共享链接](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44032) | 新文章 | 了解在AEM Assets中为特定收藏集生成共享链接时出现的问题的解决方案，该问题在因&#x200B;*无法生成链接而产生延迟后失败，请重试*&#x200B;错误。 |
| 2026 年 10 月 | [AEM Assets新UI中的文件夹名称规范化差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44087) | 新文章 | 了解当新的AEM Assets UI处理文件夹名称中的空格的方式不同于经典UI（后者在JCR节点名称中使用连字符替换）时，该问题的解决方案。 |
| 2026 年 10 月 | [对Adobe Experience Manager as a Cloud Service生产管道中增加的部署时间进行故障排除](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43293) | 新文章 | 了解针对在部署步骤滚动更新发布实例期间AEM as a Cloud Service生产管道部署时间比以前的版本长的问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud Manager中自定义域的SSL证书“失败”状态疑难解答](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43487) | 新文章 | 了解当自定义域的SSL证书在AEM Cloud Manager中显示[!UICONTROL 失败]状态并且无法创建或续订时，即使DNS和CAA记录看起来是正确的，该问题的解决方案。 |
| 2026 年 10 月 | 自定义索引作业和 [!DNL Elastic App Search] 错误导致[AEMaaCS部署时间较长](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43670) | 新文章 | 了解当AEM as a Cloud Service部署时间长于预期，并且日志包含与自定义索引作业和[!DNL Elastic App Search]引擎连接相关的重复错误时，该问题的解决方案。 |
| 2026 年 10 月 | [在AEM自适应Forms的翻译词典下拉列表中启用阿拉伯语](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43291) | 新文章 | 了解AEM Forms as a Cloud Service自适应Forms的[!UICONTROL 将字典添加到翻译项目]屏幕中的[!UICONTROL 目标语言]下拉列表未列出阿拉伯语时问题的解决方案。 |
| 2026 年 10 月 | [解决Adobe Experience Manager Forms中的SOAP调用超时问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43464) | 新文章 | 了解当在AEM Forms提交触发SOAP调用外部服务的XML表单（尤其是在高负载或文件较大时）时出现间歇性超时问题的解决方案。 |
| 2026 年 10 月 | [AEM Assets HTTP API （站点）弃用计划和文件夹操作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43879) | 新文章 | 了解当您不确定AEM Assets HTTP API(Sites)（特别是文件夹操作）的弃用计划以及文件夹API的当前支持状态时的问题的解决方案。 |
| 2026 年 10 月 | [已删除带有管道字符的图像alt属性：更新XSS策略](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43934) | 新文章 | 了解在保存并重新打开AEM Sites富文本编辑器对话框后，从`img`标记中删除包含管道字符的图像`alt`属性时问题的解决方案。 |
| 2026 年 10 月 | [在AEM Guides中修复B树索引错误导致的DITA后处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-44077) | 新文章 | 了解当您在DAM中删除并重新上传DITA和DITAMAP文件后，AEM Guides中对这些文件的后处理失败并出现B树引用索引错误时该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Experience Manager as a Cloud Service中[记录保留和删除](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-43643) | 新文章 | 如果您对AEM as a Cloud Service保留日志文件的时间长度以及如何访问和删除日志数据存有任何疑问，请了解此问题的解决方案。 |
| 2026 年 10 月 | [AEM Cloud Manager角色在分配配置文件后未更新](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-42376) | 新文章 | 了解当您在AEM Cloud Manager中分配所需的Cloud Manager产品配置文件后，您的角色未在Adobe Admin Console中更新的问题的解决方案。 |

### [!DNL Adobe Commerce] {#tutorials-commerce}

有关新功能和修复，请参阅[[!DNL Adobe Commerce] as a Cloud Service发行说明](https://experienceleague.adobe.com/zh-hans/docs/commerce/cloud-service/release-notes){target="_blank"}或 [!DNL Adobe Commerce] 和 [!DNL Magento Open Source]&#x200B;[&#128279;](https://experienceleague.adobe.com/zh-hans/docs/commerce-operations/release/notes/adobe-commerce/overview){target="_blank"}的发行说明。

#### [!DNL Commerce] 的新教程

获取 [!DNL Adobe Commerce] 最新教程和知识库支持文章。

* [Adobe [!DNL Commerce] 服务指南](https://experienceleague.adobe.com/zh-hans/docs/commerce/user-guides/home){target="_blank"}
* [产品可用性](https://experienceleague.adobe.com/zh-hans/docs/commerce-operations/release/product-availability){target="_blank"}

Experience League 上的 [!DNL Adobe Commerce] 新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [导览：浏览商店配置和系统菜单](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/admin/store-configuration-and-system-menu){target="_blank"} | 视频 | 浏览Adobe Commerce中的商店配置和系统菜单，其中涵盖产品网格、筛选、保存的视图和商店范围的设置。 |
| 2026 年 10 月 | [演示：管理客户](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/customers/customer-groups){target="_blank"} | 视频 | 了解Adobe Commerce中的客户组如何允许您针对特定类型的客户定制定价、税则、类别可见性和私有销售。 |
| 2026 年 9 月 | [Adobe Commerce Developer Agent概述](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-overview-technical-video){target="_blank"} | 视频 | 了解Adobe Commerce Developer Agent如何在不人工编码的情况下，将纯英语请求转换为已部署、经过测试的店面功能（从创意到实时测试）。 |
| 2026 年 9 月 | [Adobe Commerce开发人员代理Blueprint和开发阶段](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-blueprint-and-develop-stages-technical-video){target="_blank"} | 视频 | 了解开发人员代理如何将纯英文购物车限制规则转换为已批准的Blueprint，然后生成并自验证有效的webhook代码。 |
| 2026 年 9 月 | [Adobe Commerce Developer Agent连接集成](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-connect-integrations-technical-video){target="_blank"} | 视频 | 了解在启用该功能之前，如何将开发人员代理生成的代码连接到App Builder、您的Adobe Commerce实例和GitHub。 |
| 2026 年 9 月 | [Adobe Commerce Developer Agent配置和测试](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-configure-and-test-technical-video){target="_blank"} | 视频 | 了解如何配置购物车限制规则的业务设置，并在店面中测试该设置，而无需更改或重新部署代码。 |
| 2026 年 9 月 | [Adobe Commerce Developer Agent部署、关联和安装](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-deploy-associate-and-install-technical-video){target="_blank"} | 视频 | 了解如何部署开发人员代理的应用程序，然后在Adobe Commerce管理员中关联并安装该应用程序以激活新的webhook功能。 |
| 2026 年 9 月 | [Adobe Commerce Developer Agent迁移现有代码](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-migrate-existing-code-technical-video){target="_blank"} | 视频 | 了解如何使用迁移评估工具扫描旧版模块，然后让开发人员代理将其重建为经过测试的App Builder扩展。 |
| 2026 年 9 月 | [Adobe Commerce开发人员代理结论](https://experienceleague.adobe.com/zh-hans/docs/commerce-learn/tutorials/extensibility/commerce-developer-agent/adobe-commerce-developer-agent-conclusion-technical-video){target="_blank"} | 视频 | Commerce Developer Agent演练的总结，通过要求或旧版扩展来实现无需手动编码且经过测试的有效商店功能。 |

#### 新的 [!DNL Commerce] 支持知识库{#kb-commerce}

Adobe Commerce 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
| --------- | -------- | --------- | --------- |
| 2026 年 10 月 | [[!DNL Quality Patches Tool] （QPT）](https://experienceleague.adobe.com/zh-hans/docs/commerce-operations/tools/quality-patches-tool/patches-available-in-qpt/patches-available-in-qpt-tool-overview) | 新文章 | 已发布有关如何应用QPT 1.1.83、QPT 1.1.84和QPT 1.1.85中提供的修补程序的新文章，这些文章可在各自的章节中找到。 |
| 2026 年 10 月 | [使用 [!DNL SendGrid]](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-40991)对云基础架构上Adobe Commerce中传出电子邮件的DMARC失败进行故障排除 | 新文章 | 了解通过Adobe Commerce在云基础架构上的内置[!DNL SendGrid]集成发送的传出电子邮件未通过DMARC检查、被标记为垃圾邮件或被拒绝时，该问题的解决方案。 |
| 2026 年 10 月 | [Adobe Commerce项目根目录中出现意外的SHA-256命名文件](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50910) | 新文章 | 了解当您在应用2026年10月独立的安全修补程序后在Adobe Commerce项目根目录中创建具有长十六进制SHA-256名称的文件时问题的解决方案。 |
| 2026 年 10 月 | [更新了Adobe Commerce 2.4.8-p5 2026年10月隔离的安全修补程序](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-50927) | 新文章 | 了解当您在应用Adobe Commerce和Magento Open Source 2.4.8-p5的原始2026年10月隔离安全修补程序后，Commerce版本工具将您的隔离修补程序报告为&#x200B;*UNKNOWN*&#x200B;时问题的解决方案。 |
| 2026 年 10 月 | [常规自定义模块疑难解答帮助](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51556) | 新文章 | 了解当Adobe Commerce中的自定义模块中的功能无法按预期发挥作用并且没有明显错误消息指出问题时，问题的解决方案。 |
| 2026 年 10 月 | [在Adobe Commerce上缓存预热和网站不可用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51557) | 新文章 | 了解当部署后阶段末尾的缓存预热脚本以云基础架构实例上的Adobe Commerce无法应对的高速率发送请求，从而导致停滞部署或站点停机时该问题的解决方案。 |

### [!DNL Adobe Target] {#tutorials-target}

有关新功能和修复，请参阅[[!DNL Adobe Target] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/target/using/release-notes/release-notes){target="_blank"}。

#### [!DNL Target] 的新教程

访问 [!DNL Adobe Target] [教程](https://experienceleague.adobe.com/zh-hans/docs/target-learn/tutorials/overview)获取最新内容。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [基于配置文件属性的推荐](https://experienceleague.adobe.com/zh-hans/docs/target-learn/tutorials/recommendations/most-viewed-by-profile-attribute){target="_blank"} | 视频 | 了解如何使用Adobe Target的“查看次数最多”配置文件属性功能来提供本地化的、特定于区段的推荐，而不是一个放之四海而皆准的人气列表。 |

### [!DNL Adobe Campaign] {#tutorials-campaign}

有关新功能和修复，请参阅[[!DNL Campaign] v8](https://experienceleague.adobe.com/zh-hans/docs/campaign/campaign-v8/releases/release-notes){target="_blank"}、[[!DNL Campaign Classic] v7](https://experienceleague.adobe.com/zh-hans/docs/campaign-classic/using/release-notes/latest-release){target="_blank"}、[[!DNL Campaign] Web用户界面](https://experienceleague.adobe.com/zh-hans/docs/campaign-web/v8/release-notes/release-notes){target="_blank"}和[[!DNL Campaign Standard]](https://experienceleague.adobe.com/zh-hans/docs/campaign-standard/using/release-notes/release-notes){target="_blank"}的发行说明。

#### [!DNL Campaign] 的新教程

查看 Adobe Campaign 的最新视频教程和支持文章。

* 要查找教程和文档，请参阅[Campaign文档和视频教程主页](https://experienceleague.adobe.com/zh-hans/docs/campaign)

<!-- 
| Published | Application | Name | Type | Description |
| ---------- | ---------- | ---------- | ---------- | ---------- |
| August 2025 | Campaign v8 Web User Interface |[Enhance a delivery with dynamic content](https://experienceleague.adobe.com/zh-hans/docs/campaign){target="_blank"} | Video tutorial | Learn how to use the generative AI powered Content Generator to create and enhance the email content, optimizing your email deliveries to better resonate with your audience. |
| August 2025 | Campaign v8 Web User Interface |[Configure JavaScript code activity](https://experienceleague.adobe.com/zh-hans/docs/campaign-web-learn/tutorials/workflows/configure-java-script-code-activity){target="_blank"} | Video tutorial | Learn how to use the JavaScript Code activity in Adobe Campaign Web v8 to enhance your workflows. This tutorial covers both simple and advanced scripting modes. It explains execution settings and error handling. View real-world examples, such as targeting VIP profiles, transforming data, and triggering conditional operations. | 
-->

#### 新的 [!DNL Campaign] 支持知识库{#kb-campaign}

[!DNL Campaign] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
| --------- | ---- | ---- | ----------- |
| 2026 年 10 月 | 客户端控制台登录期间缺少[组织](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-51055) | 新文章 | 了解当Adobe Campaign Classic客户端控制台在IMS登录期间不列出所需的组织（即使同一Adobe ID通过Web UI访问实例）时，该问题的解决方案。 |
| 2026 年 10 月 | 在Adobe Campaign中，针对事务性事件类型，[电子邮件投放失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-49447) | 新文章 | 了解当Adobe Campaign中事务性事件类型的电子邮件投放在消息准备期间失败，并且图像出现DLV-490094 *下载时出现*&#x200B;错误时，该问题的解决方案。 |

### [!DNL Adobe Journey Optimizer] {#tutorials-ajo}

有关新功能和修复，请参阅[[!DNL Journey Optimizer] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer/using/whats-new/release-notes){target="_blank"}。

#### [!DNL Journey Optimizer] 的新教程

查看有关Experience League的最新教程和支持文章。

| 发布日期 | 应用程序 | 名称 | 类型 | 描述 |
| ---------- | ---------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [使用渠道优化来联系他们参与的客户](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/tutorials/journeys/use-channel-optimization){target="_blank"} | 视频 | 了解如何使用操作组组合电子邮件、推送和短信，然后通过手动优先级、客户偏好设置或AI参与度分数来优化渠道选择。 |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [使用自然语言创建历程条件](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/tutorials/journeys/create-journey-conditions-using-natural-language){target="_blank"} | 视频 | 了解[!DNL Journey Optimizer] AI如何在不编写表达式语言的情况下将纯英语提示转换为历程条件。 |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [探索忠诚度挑战的配置选项](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/loyalty/set-up-loyality/explore-the-configuration-options-for-loyalty-challenges){target="_blank"} | 视频 | 探索支持忠诚度挑战的配置选项，包括全局设置、报告、奖励、事件映射、产品清单和排除项。 |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [设置Android的实时更新](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/tutorials/channels/live-activities/android-live-updates){target="_blank"} | 视频 | 了解如何在Journey Optimizer中配置Android实时更新渠道，以通过营销活动和API提供实时、永久的客户体验。 |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [设置忠诚度数据摄取：连接并映射忠诚度数据](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/loyalty/set-up-loyality/set-up-loyalty-data-ingestion/connect-and-map-loyalty-data){target="_blank"} | 视频 | 了解如何创建HTTP API连接和数据流，然后将传入的忠诚度用户档案和事件字段映射到您在Journey Optimizer Loyalty中的数据集。 |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [设置忠诚度数据摄取：验证忠诚度数据并配置绩效报表](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/loyalty/set-up-loyality/set-up-loyalty-data-ingestion/verify-loyalty-data-and-configure-performance-reporting){target="_blank"} | 视频 | 了解如何在Experience Platform中验证忠诚度配置文件和事件数据，然后在忠诚度绩效设置中选择数据集并优先处理KPI。 |
| 2026 年 10 月 | [!DNL Journey Optimizer] | [设置会员数据摄取：准备会员数据结构](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/loyalty/set-up-loyality/set-up-loyalty-data-ingestion/prepare-loyalty-data-structures){target="_blank"} | 视频 | 了解如何在Experience Platform中设置接收忠诚度会员和事件数据所需的XDM架构和启用配置文件的数据集。 |

#### 新的 [!DNL Journey Optimizer] 支持知识库{#kb-ajo}

[!DNL Journey Optimizer] 的新文章和现有文章的更新。

| 发布日期 | 名称 | 类型 | 描述 |
| --------- | ---- | ---- | ----------- |
| 2026 年 8 月 | [在Adobe Journey Optimizer中找不到inSegment(null)条件和受众错误](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-41654) | 新文章 | 了解在将受众添加到Adobe Journey Optimizer历程中的条件时，即使受众存在，该条件也会失败，从而导致该条件显示为&#x200B;*inSegment(null)*，并且历程发布失败并出现&#x200B;*ERR_AUTHORING_SEGMENTS_3 — 无法找到受众*。 |


#### [!DNL Journey Optimizer] 的更多资源

* [[!DNL Journey Optimizer] 文档](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer/using/ajo-home){target="_blank"} - [操作方法视频](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/tutorials/overview){target="_blank"}
* [决策管理文档](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning){target="_blank"} - [操作方法视频](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-learn/tutorials/decision-capabilities/decision-management/introduction-to-decision-management){target="_blank"} - [最新文档更新](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer/using/whats-new/documentation-updates){target="_blank"}

### [!DNL Adobe Journey Optimizer B2B Edition] {#tutorials-ajo-b2b}

有关新功能和修复，请参阅[[!DNL Journey Optimizer B2B Edition] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-b2b/user/release-notes){target="_blank"}。

#### [!DNL Journey Optimizer B2B Edition] 的新教程

查找 Journey Optimizer B2B Edition 的学习资源。

* [[!DNL Journey Optimizer B2B Edition]](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-b2b){target="_blank"}（全部自助）
* [!DNL Journey Optimizer B2B Edition] 的[产品文档](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-b2b/user/guide-overview){target="_blank"}
* [!DNL Journey Optimizer B2B Edition] 的[视频概述和教程](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer-b2b-learn/tutorials/overview){target="_blank"}

### [!DNL Adobe Marketo Engage] {#tutorials-marketo}

有关新功能和修复，请参阅[[!DNL Marketo Engage] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/marketo/using/release-notes/current){target="_blank"}。

#### [!DNL Marketo] 的新教程

为 Adobe Marketo 发布的新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [发送电子邮件给Designer概述](https://experienceleague.adobe.com/zh-hans/docs/marketo-learn/tutorials/email-marketing/email-designer-overview){target="_blank"} | 视频 | 进一步了解Marketo Engage中的高级电子邮件Designer。 |
| 2026 年 9 月 | [Sales Qualifier概述](https://experienceleague.adobe.com/zh-hans/docs/sales-qualifier/using/home){target="_blank"} | 视频 | 了解Sales Qualifier产品，包括其特性和功能。 |

* [Marketo Engage教程](https://experienceleague.adobe.com/zh-hans/docs/marketo-learn/tutorials/overview){target="_blank"} — 浏览教程库并充分利用Marketo Engage。

有关最新的产品文档，请参阅 [Marketo 产品文档](https://experienceleague.adobe.com/zh-hans/docs/marketo/using/home){target="_blank"}主页。

<!-- 
#### New [!DNL Marketo] support knowledge base

New articles and updates to existing articles for [!DNL Marketo].

| Published | Name | Type | Description |
| ----------- | ---------- | ---------- | ---------- |
| February 2026 | [Understanding persistent report subscriptions for standard analytics reports](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-29909){target="_blank"} | New article | Learn about the solutions to the issue when Marketo Engage continues sending scheduled subscription emails for standard workspace-level analytics reports even when the report isn't a custom or standalone report. |
-->

### [!DNL Adobe Workfront] {#tutorials-workfront}

有关新功能和修复，请参阅[[!DNL Workfront] 产品版本](https://experienceleague.adobe.com/zh-hans/docs/workfront/using/product-announcements/product-releases/product-releases){target="_blank"}或[[!DNL Workfront Fusion] 版本活动](https://experienceleague.adobe.com/zh-hans/docs/workfront-fusion/using/fusion-release-activity/fusion-release-activity){target="_blank"}。

#### [!DNL Workfront] 的新教程

Experience League 上的新 [!DNL Workfront] 教程和活动。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [路由器演练](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/universal-connectors-and-routing/routers-walkthrough.html?lang=zh-Hans){target="_blank"} | 视频 | 浏览Adobe Workfront Fusion中的路由器。 |

<!--
#### New [!DNL Workfront] support knowledge base

New articles and updates to existing articles for [!DNL Workfront].

| Published | Name | Type | Description |
| ----------- | ---------- | ---------- | ---------- |
| August 2025 | [Calendar appears blank when owner is deactivated in Workfront](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27192){target="_blank"} | New article | Learn about the solutions to the issue when the owner of a calendar is deactivated, the calendar becomes blank, and no tasks or events are visible. |
| August 2025 | [Error appears when assigning resource managers in Workfront](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27251){target="_blank"} | New article | Learn about the solutions to the issue when the error *Only users with a plan license can be added as resource managers* occurs when attaching a project template that includes resource managers without the required license type. |
| August 2025 | [Issue to project conversion grants home group "view" access by default in Workfront](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27261){target="_blank"} | New article | Learn about the solutions to the issue when converting an issue into a project using a template in Adobe Workfront, the creator's home group automatically receives view access to the resulting project. |
| August 2025 | [Duplicate folders auto-created in Workfront via [!DNL Fusion] scenarios](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27287){target="_blank"} | New article | Learn about the solutions to the issue when duplicate folders are automatically created in certain Adobe Workfront projects due to active [!DNL Fusion] connections. |
| August 2025 | [Unable to report on specific approver actions in Adobe Workfront](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27298){target="_blank"} | New article | Learn about the solutions to the issue when Adobe Workfront reports don't natively support isolating actions taken by specific approvers in multi-stage approval workflows. |
| August 2025 | [Unable to attach template to an existing project in Workfront](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27305){target="_blank"} | New article | Learn about the solutions to the issue when an error occurs when attaching a template to an existing project in Adobe Workfront related to system-wide sharing permissions settings. |
-->

有关最新的产品文档，请参阅 [Adobe [!DNL Workfront] 文档主页](https://experienceleague.adobe.com/zh-hans/docs/workfront/using/home){target="_blank"}。

### [!DNL Adobe GenStudio for Performance Marketing] {#tutorials-genstudio-marketing}

有关新功能和修复，请参阅[[!DNL GenStudio for Performance Marketing] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest){target="_blank"}。

#### [!DNL GenStudio] 的新教程

GenStudio for Performance Marketing 视频教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 7 月 | [GenStudio Figma集成演示](https://experienceleague.adobe.com/zh-hans/docs/genstudio-for-performance-marketing/user-guide/integrations/figma-plugin#convert-figma-frames-to-photoshop){target="_blank"} | 视频 | 观看GenStudio for Performance Marketing中Figma集成的演示，包括如何将Figma帧转换为Photoshop。 |

**GenStudio for Performance Marketing 资源**

* [GenStudio for Performance Marketing](https://experienceleague.adobe.com/zh-hans/browse/genstudio-for-performance-marketing){target="_blank"}（全自助）
* GenStudio for Performance Marketing [的产品文档](https://experienceleague.adobe.com/zh-hans/docs/genstudio-for-performance-marketing/user-guide/home){target="_blank"}
* [GenStudio for Performance Marketing](https://business.adobe.com/cn/products/genstudio-for-performance-marketing.html) 产品信息

### [!DNL Adobe Pass] {#tutorials-pass}

[!DNL Adobe Pass] 是一个多屏幕电视平台，可帮助广播公司、有线电视网和服务提供商创造有吸引力的个性化观看体验并从中盈利。 有关新功能和修复，请参阅[[!DNL Adobe Pass] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/pass/authentication/product-releases/2026/auth-rn-370){target="_blank"}。

* [Adobe Pass 文档](https://experienceleague.adobe.com/zh-hans/docs/pass){target="_blank"}，查找版本特有的信息、系统要求、限制、已修复问题和已知问题。

### [!DNL Adobe Document Cloud] {#tutorials-document-cloud}

查看为 [!DNL Document Cloud] 发布的新教程，包括 [!DNL Acrobat Services] 和 [!DNL Acrobat Sign]。

| 发布日期 | 应用程序 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | Acrobat | [创建播客](https://experienceleague.adobe.com/zh-hans/docs/document-cloud-learn/acrobat-learning/get-started/ai/podcast){target="_blank"} | 视频 | 了解如何从Acrobat Studio中的文档创建AI生成的播客，然后随着内容的更改对其进行自定义和更新。 |
| 2026 年 10 月 | Acrobat Analyzer | [构造：查找分包中的利润风险](https://experienceleague.adobe.com/zh-hans/docs/document-cloud-learn/acrobat-learning/analyzer/use-cases/identify-margin-erosion){target="_blank"} | 视频 | 了解建筑和项目团队如何使用Acrobat Studio中的Analyser在影响利润率之前查找未完成的更改单、过期的RFI以及分包合同保护中的漏洞。 |
| 2026 年 10 月 | Acrobat Analyzer | [信息安全审核：识别供应商风险](https://experienceleague.adobe.com/zh-hans/docs/document-cloud-learn/acrobat-learning/analyzer/use-cases/vendor-risk){target="_blank"} | 视频 | 了解Acrobat Studio中的Analyzer如何主动识别供应商合同中的信息安全风险。 |

要浏览 [!DNL Document Cloud] 教程，请参阅：

* [Adobe Acrobat](https://experienceleague.adobe.com/zh-hans/docs/document-cloud-learn/acrobat-learning/overview){target="_blank"}
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/zh-hans/docs/document-cloud-learn/sign-learning-hub/overview){target="_blank"}
* [Adobe Acrobat 服务 API 教程](https://experienceleague.adobe.com/zh-hans/docs/acrobat-services-learn/tutorials/overview){target="_blank"}
* [Document Cloud学习与支持](https://helpx.adobe.com/cn/support/document-cloud.html)

### [!DNL Adobe Creative Cloud] 企业版 {#tutorials-creative-cloud}

浏览 [Creative Cloud 企业版](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview){target="_blank"}教程库，以获取更多内容。

Adobe基于节点的创意自动化工具[!DNL Firefly Graph]的新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [填补剪裁中的空白：B卷、音频和过早结束的剪辑](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/fill-gaps){target="_blank"} | 视频 | 了解如何使用Premiere中的“创成扩展”，从已有的剪辑生成额外的素材，以便能够精确地根据需要进行剪切。 |
| 2026 年 10 月 | [几分钟内即可形成无缝矢量模式，而不是几小时](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/seamless-vector){target="_blank"} | 视频 | 了解如何使用生成模式在Illustrator中构建无缝品牌模式，添加您自己的徽标图标，扩展重复范围，以及使用创新型重新着色来构建三种颜色。 |
| 2026 年 10 月 | [将平面矢量图转换为任意角度而不重新绘制](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/turn-flat-vector-art){target="_blank"} | 视频 | 了解如何使用文本到图案来探索选项、将您自己的品牌图案添加到重复项、为不同应用程序调整图案大小以及从一种可编辑设计构建三种颜色方式。 |
| 2026 年 10 月 | [更快地完成粗略剪辑](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/rough-cut){target="_blank"} | 视频 | 了解如何在Premiere中使用基于文本的编辑和Media Intelligence从访谈和B滚中构建粗略剪辑，而无需翻阅每个剪辑。 |
| 2026 年 10 月 | [生成预设，以便在拍摄过程中保持颜色一致](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/build-presets){target="_blank"} | 视频 | 了解如何在Lightroom中构建颜色预设，然后在Firefly中通过批量操作将该颜色级别应用于一批图像。 |
| 2026 年 10 月 | 午餐前[20条路线，从一则简讯开始](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/one-brief){target="_blank"} | 视频 | 了解如何使用Firefly展示板将创意简报转换为视觉方向共享展示板，然后进一步编辑为两三个值得辩护的展示板。 |
| 2026 年 10 月 | [从简介到情节提要：在生产之前探索视频方向](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/brief-to-storyboard){target="_blank"} | 视频 | 了解如何在Firefly展示板上将简介和几个参考转换为情节提要帧、生成短动画测试并并排比较两个方向。 |
| 2026 年 10 月 | [加快润饰速度并保持原始像素](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/cceaitutorials/retouch-faster){target="_blank"} | 视频 | 了解如何在Photoshop中使用“协调”为产品照片添加自然阴影，同时保持原始像素完好无损。 |

### [!DNL Adobe Brand Concierge] {#tutorials-brand-concierge}

有关新功能和修复，请参阅[[!DNL Brand Concierge] 发行说明](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/release-notes/current){target="_blank"}。

#### [!DNL Brand Concierge] 的新教程

查看[!DNL Adobe Brand Concierge]的新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026年11 | [在Marketo中使用Brand Concierge活动](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/live-chat-and-meeting-booking/use-brand-concierge-activities-in-marketo){target="_blank"} | 教程 | 了解Brand Concierge如何将潜在客户详细信息和参与活动发送到Marketo，以及如何在智能营销活动中使用它们。 |
| 2026年11 | [配置实时聊天和会议的可用性和路由](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/live-chat-and-meeting-booking/configure-availability-and-routing-for-live-chat-and-meetings){target="_blank"} | 教程 | 了解代表如何设置其可用性，以及管理员如何为Brand Concierge Live Chat和Meeting Booking创建路由规则。 |
| 2026 年 10 月 | [Live Chat和会议预订：端到端体验](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/live-chat-and-meeting-booking/live-chat-and-meeting-booking-end-to-end-experience){target="_blank"} | 教程 | 了解Brand Concierge如何通过Live Chat或Meeting Booking将网站访客与代表连接起来。 |
| 2026 年 10 月 | [使用查询服务和终端导出对话](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/getting-started/exporting-conversations-using-query-service-and-terminal){target="_blank"} | 教程 | 了解如何使用Brand Concierge查询服务和终端保存和导出Experience Platform对话。 |
| 2026 年 10 月 | [使用Adobe CX Enterprise Coworker导出对话](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/getting-started/exporting-conversations-using-adobe-cx-enterprise-coworker){target="_blank"} | 教程 | 了解如何使用Brand Concierge查询服务和同事保存和导出Experience Platform对话。 |
| 2026 年 10 月 | [多语言功能](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/getting-started/multilingual-capabilities){target="_blank"} | 教程 | 了解Brand Concierge如何让您为每个礼宾实例选择响应语言，这样即使知识源使用其他语言，对话也会本地化。 |
| 2026 年 10 月 | [测量质量并设置护栏](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/go-live-guide/measuring-quality-and-setting-guardrails){target="_blank"} | 教程 | 了解如何构建一组黄金的示例问题和理想答案，并为敏感主题定义护栏，以在启动之前衡量和验证Brand Concierge的质量。 |
| 2026 年 10 月 | [与Marketo集成](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/getting-started/integration-with-marketo){target="_blank"} | 教程 | 了解Brand Concierge如何与Marketo Engage集成，以便通过Concierge对话捕获的潜在客户作为可在Smart Campaigns中使用的本机活动自动流入Marketo。 |
| 2026 年 10 月 | [技术设置和可选功能](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/go-live-guide/technical-setup-and-optional-features){target="_blank"} | 教程 | 了解部署Brand Concierge所需的技术设置（标签管理、页面定位、AEP沙盒和数据流）以及会议预订、实时聊天和Marketo集成等可选功能。 |
| 2026 年 10 月 | [您的上线前核对清单和转出计划](https://experienceleague.adobe.com/zh-hans/docs/brand-concierge/content/go-live-guide/your-pre-go-live-checklist-and-rollout-plan){target="_blank"} | 教程 | 浏览Brand Concierge的上线前核对清单，了解如何从内部测试到完全流量逐步推出，同时在此过程中监控质量。 |

### [!DNL Adobe Brand Visibility]（以前称为 [!DNL Adobe LLM Optimizer]） {#tutorials-llm-optimizer}

有关新功能和修复，请参阅[[!DNL Brand Visibility] 发行说明](https://abv.adobe.com/articles/release-notes){target="_blank"}。

#### [!DNL Brand Visibility] 的新教程

查看[!DNL Adobe Brand Visibility]的新教程。

| 发布日期 | 名称 | 类型 | 描述 |
| ----------- | ---------- | ---------- | ---------- |
| 2026 年 10 月 | [什么是Google首选源？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/news-and-insights/what-are-google-preferred-sources){target="_blank"} | 视频 | 了解Google的首选源功能的功能、它为什么增长迅速，以及如何通过两行HTML添加它。 |
| 2026 年 10 月 | [什么是WebMCP？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/news-and-insights/what-is-webmcp){target="_blank"} | 视频 | 了解WebMCP如何让网页公开AI代理可以直接调用的工具、它与MCP有何不同以及在何处开始。 |
| 2026 年 10 月 | [Impact Measurement Engine如何工作？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/measurement/how-does-the-impact-measurement-engine-work){target="_blank"} | 视频 | Adobe Brand Visibility中的影响测量引擎可测量优化之前和之后的AI可见性，并自动构建之前和之后报表。 |
| 2026 年 10 月 | [是否必须优化整个网站？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/technical/do-you-have-to-optimize-your-entire-website){target="_blank"} | 视频 | 了解Adobe Brand Visibility如何让您选择要优化的页面、代理其余的页面而不更改，以及随时回滚。 |
| 2026 年 10 月 | 2026年5月从ChatGPT增加[引荐流量](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/measurement/referral-traffic-increase-from-chatgpt-in-may-2026){target="_blank"} | 视频 | 了解ChatGPT现在如何将品牌提及超链接，推动引荐流量增长约60%，并将其从品牌渠道重新转变为流量渠道。 |
| 2026 年 10 月 | [AI助理如何决定何时使用外部源以及什么是引用？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/foundations/how-do-ai-assistants-decide-when-to-use-outside-sources-and-what-are-citations){target="_blank"} | 视频 | 了解AI助理如何在从训练数据中回答和检索实时源之间做出选择，以及引文的真实含义，包括为什么某些引文会出现幻觉。 |
| 2026 年 10 月 | [如何编写提示，为您提供可靠的可重复的GEO分析](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/foundations/how-do-you-write-prompts-that-give-you-reliable-repeatable-geo-insights){target="_blank"} | 视频 | 学习将GEO提示视为现实、具体且可重复的测试案例，并对它们进行版本更改以获取稳定、可靠的AI可见性见解。 |
| 2026 年 10 月 | [在GEO中还无法测量的内容以及测量将如何随着时间的推移而改进](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/measurement/what-we-cant-measure-well-yet-in-geo-and-how-measurement-will-improve-over-time){target="_blank"} | 视频 | GEO测量比较困难，因为AI具有不确定性，并且因地区和个性化而异。 看看今天很难衡量什么，以及它正在如何改进。 |
| 2026 年 10 月 | [哪些技术基础知识可帮助LLM正确抓取和解读您的网站？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/technical/what-technical-basics-help-llms-crawl-and-interpret-your-website-correctly){target="_blank"} | 视频 | 了解可让LLM抓取您的网站的技术基础知识，从robots.txt和CDN机器人规则到客户端渲染，让您的内容保持可见性和可编辑性。 |
| 2026 年 10 月 | [什么是代理流量，它如何为优化决策提供信息？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/measurement/what-is-agentic-traffic-and-how-can-it-inform-optimization-decisions){target="_blank"} | 视频 | 代理流量正在与您的网站进行AI交互。 了解监控点击量、成功率和内容可见度如何指导您的优化决策。 |
| 2026 年 10 月 | [添加AI友好页面摘要隐藏吗？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/technical/is-adding-ai-friendly-page-summaries-cloaking){target="_blank"} | 视频 | 了解为什么为代理添加对AI友好的摘要不会遮蔽，因为Edge中的优化会重新组织页面上已有的内容。 |
| 2026 年 10 月 | [LLM的工作方式：营销人员指南](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/foundations/how-llms-work-a-marketers-guide){target="_blank"} | 视频 | 了解RAG中有多少语言模型可以预测、学习和检索资源，以及为什么引用是GEO新的可见性。 |
| 2026 年 10 月 | [在AI答案中被提及和被引用之间有何区别？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/foundations/what-is-the-difference-between-being-mentioned-and-being-cited-in-an-ai-answer){target="_blank"} | 视频 | 提及内容会在文本中命名您的品牌；引文会将您的页面链接为源。 了解为何引文来自检索并且是更强的可见性信号。 |
| 2026 年 10 月 | [为什么情绪在AI答案中很重要？情绪分析会漏掉哪些内容？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/brand-presence/why-does-sentiment-matter-in-ai-answers-and-what-can-sentiment-analysis-miss){target="_blank"} | 视频 | 情绪决定了AI如何诠释你的品牌，但分析可能会误读讽刺和行业术语。 了解上下文在跟踪它时为什么很重要。 |
| 2026 年 10 月 | [如何监视AI品牌响应中的区域差异](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/brand-presence/how-to-monitor-regional-differences-in-ai-brand-responses){target="_blank"} | 视频 | 人工智能答案因地区而异。 了解为什么将位置写入提示本身会使品牌监控反映客户实际看到的内容。 |
| 2026 年 10 月 | [Bing网站管理员工具人工智能性能报表](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/measurement/bing-webmaster-tools-ai-performance-report){target="_blank"} | 视频 | 探索Microsoft的Bing网站管理员工具AI性能报表 — 它如何跟踪AI答案中的引用以及它对于GEO可见性的含义。 |
| 2026 年 10 月 | [LLMs.txt：它是否相关？ （2026年6月）](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/technical/llmstxt-is-it-relevant-june-2026){target="_blank"} | 视频 | 一项对近5000个AEM网站的审计表明，LLMs.txt的采用率很小，引用率也微不足道，但谷歌现在能读懂它，因此创建这种网站就是廉价保险。 |
| 2026 年 10 月 | [为什么应定期监视AI助理对您的品牌或主题的评价？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/brand-presence/why-should-you-regularly-monitor-what-ai-assistants-say-about-your-brand-or-topic){target="_blank"} | 视频 | AI答案会随着模型和Web更新而快速变化。 定期监控是品牌叙事的质量保证，可及早发现错误和丢失的引用。 |
| 2026 年 10 月 | [大型语言模型如何决定其响应中要包含哪些引文？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/foundations/how-do-large-language-models-llms-decide-which-citations-to-include-in-their-responses){target="_blank"} | 视频 | LLM关注许多子查询并引用在所有子查询中排名靠前的源，因此深入的话题报道和SEO仍然驱动着哪些品牌被引用。 |
| 2026 年 10 月 | [如何改进AI助理对您的产品或服务的评价？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/brand-presence/what-can-you-do-to-improve-what-ai-assistants-say-about-your-products-or-services){target="_blank"} | 视频 | 通过使您的网站成为最清晰、最一致的来源，并调整AI提到的有关您品牌的第三方来源，改进AI对您的评价。 |
| 2026 年 10 月 | [为什么将提示映射到角色，以及如何为不同的受众定制提示？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/foundations/why-map-prompts-to-personas-and-how-do-you-tailor-prompts-to-different-audiences){target="_blank"} | 视频 | 将提示映射到真实角色可显示内容在何处获胜或失败，因为在整个受众中平均可见性会隐藏您在AI答案中的真实立场。 |
| 2026 年 10 月 | [提高低代理流量域的品牌权限](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/brand-presence/increasing-brand-authority-for-low-agentic-traffic-domains){target="_blank"} | 视频 | 构建可提升搜索排名和AI引用次数的链接、提及次数和声誉，然后使用Adobe Brand Visibility对其进行测量，即使在AI流量较低时也是如此。 |
| 2026 年 10 月 | [什么是Edge优化？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/technical/what-is-optimize-at-the-edge){target="_blank"} | 视频 | Edge中的优化位于您的CDN中，并且为人工智能机器人提供预呈现的HTML，以便它们能够看到隐藏在客户端JavaScript后面的内容，而不会对用户产生任何影响。 |
| 2026 年 10 月 | [什么是可见度分数，应该使用什么指标来衡量AI可见性？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/measurement/what-is-visibility-score-and-what-metrics-should-you-use-to-measure-ai-visibility){target="_blank"} | 视频 | 可见度分数汇总提及次数、引用次数、位置和情绪。 了解它衡量的指标以及与其配对的量度，以使AI可见性可操作。 |
| 2026 年 10 月 | [AI机器人遮盖的预呈现内容是否为？](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/technical/is-pre-rendering-content-for-ai-bots-cloaking){target="_blank"} | 视频 | 预渲染不会掩盖。 它只是让AI代理能够查看人类看到的相同内容，从而匹配Google关于JavaScript渲染的指导。 |
| 2026 年 10 月 | [Google现在通过AI概述回答您的品牌名称](https://experienceleague.adobe.com/zh-hans/docs/brand-visibility-learn/tutorials/news-and-insights/google-now-answers-your-brand-name-with-an-ai-overview){target="_blank"} | 视频 | Google现在为大多数品牌名称搜索显示AI概述。 了解您的品牌发生了哪些变化（从引文到搜索控制台展示次数），以及要观看哪些变化。 |

### 客户数据管理 - 意见 {#tutorials-voices}

[客户数据管理意见](https://experienceleague.adobe.com/zh-hans/events#f-el_event_series=Customer%20Data%20Management%20Voices){target="_blank"}是您作为客户数据管理技术和营销实践领导者和专家的目标。 本教程合集是一项综合性学习资源，帮助您聆听同行经验、获取灵感，并了解营销技术（MarTech）领域的最新发展。 无需注册。

### 客户体验编排Blueprint {#tutorials-blueprints}

[客户体验编排Blueprint](https://experienceleague.adobe.com/zh-hans/docs/blueprints-learn/architecture/overview){target="_blank"}是可重复的实施，可让您处理战略并快速解决既定的业务问题。 每个 Blueprint 都提供了一系列构件，这些构件说明了高价值业务问题、体系结构、实施步骤、技术注意事项以及指向相关文档的链接。

[回到顶部](#top)
