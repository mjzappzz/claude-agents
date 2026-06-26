# Claude Agents

Claude Code 自定义 Agent 集合，当前共 **235** 个 agent 定义文件。

`jarvis.md` 是 J.A.R.V.I.S. 路由入口，其余 `.md` 文件为具体专家代理。

## 快速开始

```bash
git clone git@github.com:mjzappzz/claude-agents.git ~/.claude/agents
find ~/.claude/agents -maxdepth 1 -name '*.md' ! -name README.md | sort
```

## 目录结构

```text
~/.claude/agents/
├── jarvis.md
├── <agent>.md
└── README.md
```

## 分类统计

| 分类 | 前缀 | 数量 |
|------|------|------|
| 学术 | `academic` | 5 |
| 财务/应付 | `accounts` | 1 |
| Agentic 系统 | `agentic` | 1 |
| agents | `agents` | 1 |
| 自动化治理 | `automation` | 1 |
| Blender | `blender` | 1 |
| 商业策略 | `business` | 1 |
| 变更管理 | `change` | 1 |
| CFO | `chief` | 1 |
| 核心与通用 | `core` | 3 |
| 企业培训 | `corporate` | 1 |
| 客户 | `customer` | 2 |
| 数据 | `data` | 2 |
| 设计 | `design` | 9 |
| 工程与开发 | `engineering` | 33 |
| ESG | `esg` | 1 |
| 财务 | `finance` | 5 |
| 游戏 | `game` | 2 |
| GIS | `gis` | 13 |
| Godot | `godot` | 3 |
| 政企售前 | `government` | 1 |
| Grant | `grant` | 1 |
| 医疗 | `healthcare` | 2 |
| 酒店服务 | `hospitality` | 1 |
| HR | `hr` | 1 |
| 身份图谱 | `identity` | 1 |
| 翻译 | `language` | 1 |
| 法务 | `legal` | 3 |
| 关卡设计 | `level` | 1 |
| 贷款 | `loan` | 1 |
| LSP | `lsp` | 1 |
| 并购整合 | `ma` | 1 |
| macOS/Metal | `macos` | 1 |
| 营销 | `marketing` | 36 |
| 医疗账单 | `medical` | 1 |
| 叙事 | `narrative` | 1 |
| 运营 | `operations` | 1 |
| 组织心理 | `organizational` | 1 |
| 付费媒体 | `paid` | 7 |
| 个人成长 | `personal` | 1 |
| 产品 | `product` | 5 |
| 项目管理 | `project` | 7 |
| 地产 | `real` | 1 |
| 招聘 | `recruitment` | 1 |
| 报告 | `report` | 1 |
| 零售 | `retail` | 1 |
| Roblox | `roblox` | 3 |
| 销售 | `sales` | 11 |
| 安全 | `security` | 10 |
| 专家领域 | `specialized` | 13 |
| 留学 | `study` | 1 |
| 供应链 | `supply` | 1 |
| 支持 | `support` | 6 |
| 技术美术 | `technical` | 1 |
| 终端集成 | `terminal` | 1 |
| 测试 | `testing` | 8 |
| Unity | `unity` | 4 |
| Unreal | `unreal` | 4 |
| visionOS | `visionos` | 1 |
| XR | `xr` | 3 |
| ZK | `zk` | 1 |

## Agents 一览

### 学术

| Agent | 说明 |
|-------|------|
| `academic-anthropologist.md` | Expert in cultural systems, rituals, kinship, belief systems, and ethnographic method — builds culturally coherent societies that feel lived-in rather than invented |
| `academic-geographer.md` | Expert in physical and human geography, climate systems, cartography, and spatial analysis — builds geographically coherent worlds where terrain, climate, resources, and settlement patterns make scientific sense |
| `academic-historian.md` | Expert in historical analysis, periodization, material culture, and historiography — validates historical coherence and enriches settings with authentic period detail grounded in primary and secondary sources |
| `academic-narratologist.md` | Expert in narrative theory, story structure, character arcs, and literary analysis — grounds advice in established frameworks from Propp to Campbell to modern narratology |
| `academic-psychologist.md` | Expert in human behavior, personality theory, motivation, and cognitive patterns — builds psychologically credible characters and interactions grounded in clinical and research frameworks |

### 财务/应付

| Agent | 说明 |
|-------|------|
| `accounts-payable-agent.md` | Autonomous payment processing specialist that executes vendor payments, contractor invoices, and recurring bills across any payment rail — crypto, fiat, stablecoins. Integrates with AI agent workflows via tool calls. |

### Agentic 系统

| Agent | 说明 |
|-------|------|
| `agentic-identity-trust.md` | Designs identity, authentication, and trust verification systems for autonomous AI agents operating in multi-agent environments. Ensures agents can prove who they are, what they're authorized to do, and what they actually did. |

### agents

| Agent | 说明 |
|-------|------|
| `agents-orchestrator.md` | Autonomous pipeline manager that orchestrates the entire development workflow. You are the leader of this process. |

### 自动化治理

| Agent | 说明 |
|-------|------|
| `automation-governance-architect.md` | Governance-first architect for business automations (n8n-first) who audits value, risk, and maintainability before implementation. |

### Blender

| Agent | 说明 |
|-------|------|
| `blender-addon-engineer.md` | Blender tooling specialist - Builds Python add-ons, asset validators, exporters, and pipeline automations that turn repetitive DCC work into reliable one-click workflows |

### 商业策略

| Agent | 说明 |
|-------|------|
| `business-strategist.md` | Senior management consulting specialist for competitive analysis, market entry strategy, business model design, growth planning, organizational strategy, and strategic decision-making — translating complex market dynamics into clear, actionable strategies that create sustainable competitive advantage |

### 变更管理

| Agent | 说明 |
|-------|------|
| `change-management-consultant.md` | Expert change management specialist using ADKAR, Kotter, and Prosci frameworks to guide organizations through technology implementations, restructuring, culture transformation, and M&A integration — managing resistance, building adoption, and ensuring changes stick long after go-live |

### CFO

| Agent | 说明 |
|-------|------|
| `chief-financial-officer.md` | Strategic finance executive who governs capital allocation, treasury operations, financial planning, M&A finance, investor relations, and board reporting — translating financial complexity into clear decisions that drive business performance and stakeholder confidence. |

### 核心与通用

| Agent | 说明 |
|-------|------|
| `agent.md` | Your direct line to AI agency expertise |
| `agents.md` | Your direct line to AI agency expertise |
| `jarvis.md` | The intelligent assistant that automatically routes your requests to the right specialist |

### 企业培训

| Agent | 说明 |
|-------|------|
| `corporate-training-designer.md` | Expert in enterprise training system design and curriculum development — proficient in training needs analysis, instructional design methodology, blended learning program design, internal trainer development, leadership programs, and training effectiveness evaluation and continuous optimization. |

### 客户

| Agent | 说明 |
|-------|------|
| `customer-service.md` | Friendly, professional customer service specialist for any industry — handling inquiries, complaints, account support, FAQs, and seamless escalation with warmth, efficiency, and a genuine commitment to customer satisfaction |
| `customer-success-manager.md` | Strategic customer success specialist for onboarding, health scoring, QBR facilitation, churn prevention, expansion identification, and renewal management — driving net revenue retention by turning customers into long-term partners who achieve measurable outcomes |

### 数据

| Agent | 说明 |
|-------|------|
| `data-consolidation-agent.md` | AI agent that consolidates extracted sales data into live reporting dashboards with territory, rep, and pipeline summaries |
| `data-privacy-officer.md` | Corporate data privacy specialist and DPO who builds GDPR, CCPA, and global privacy compliance programs — covering data mapping, privacy impact assessments, consent management, breach response, vendor due diligence, and regulatory engagement. |

### 设计

| Agent | 说明 |
|-------|------|
| `design-brand-guardian.md` | Expert brand strategist and guardian specializing in brand identity development, consistency maintenance, and strategic brand positioning |
| `design-image-prompt-engineer.md` | Expert photography prompt engineer specializing in crafting detailed, evocative prompts for AI image generation. Masters the art of translating visual concepts into precise language that produces stunning, professional-quality photography through generative AI tools. |
| `design-inclusive-visuals-specialist.md` | Representation expert who defeats systemic AI biases to generate culturally accurate, affirming, and non-stereotypical images and video. |
| `design-persona-walkthrough.md` | Simulate cognitive walkthroughs of web pages from a defined persona's psychological perspective — captures emotional reactions and rational thought at each scroll position, then delivers structured CRO reports grounded in LIFT, Cialdini, and Fogg frameworks |
| `design-ui-designer.md` | Expert UI designer specializing in visual design systems, component libraries, and pixel-perfect interface creation. Creates beautiful, consistent, accessible user interfaces that enhance UX and reflect brand identity |
| `design-ux-architect.md` | Technical architecture and UX specialist who provides developers with solid foundations, CSS systems, and clear implementation guidance |
| `design-ux-researcher.md` | Expert user experience researcher specializing in user behavior analysis, usability testing, and data-driven design insights. Provides actionable research findings that improve product usability and user satisfaction |
| `design-visual-storyteller.md` | Expert visual communication specialist focused on creating compelling visual narratives, multimedia content, and brand storytelling through design. Specializes in transforming complex information into engaging visual stories that connect with audiences and drive emotional engagement. |
| `design-whimsy-injector.md` | Expert creative specialist focused on adding personality, delight, and playful elements to brand experiences. Creates memorable, joyful interactions that differentiate brands through unexpected moments of whimsy |

### 工程与开发

| Agent | 说明 |
|-------|------|
| `engineering-ai-data-remediation-engineer.md` | Specialist in self-healing data pipelines — uses air-gapped local SLMs and semantic clustering to automatically detect, classify, and fix data anomalies at scale. Focuses exclusively on the remediation layer: intercepting bad data, generating deterministic fix logic via Ollama, and guaranteeing zero data loss. Not a general data engineer — a surgical specialist for when your data is broken and the pipeline can't stop. |
| `engineering-ai-engineer.md` | Expert AI/ML engineer specializing in machine learning model development, deployment, and integration into production systems. Focused on building intelligent features, data pipelines, and AI-powered applications with emphasis on practical, scalable solutions. |
| `engineering-autonomous-optimization-architect.md` | Intelligent system governor that continuously shadow-tests APIs for performance while enforcing strict financial and security guardrails against runaway costs. |
| `engineering-backend-architect.md` | Senior backend architect specializing in scalable system design, database architecture, API development, and cloud infrastructure. Builds robust, secure, performant server-side applications and microservices |
| `engineering-cms-developer.md` | Drupal and WordPress specialist for theme development, custom plugins/modules, content architecture, and code-first CMS implementation |
| `engineering-code-reviewer.md` | Expert code reviewer who provides constructive, actionable feedback focused on correctness, maintainability, security, and performance — not style preferences. |
| `engineering-codebase-onboarding-engineer.md` | Expert developer onboarding specialist who helps new engineers understand unfamiliar codebases fast by reading source code, tracing code paths, and stating only facts grounded in the code. |
| `engineering-data-engineer.md` | Expert data engineer specializing in building reliable data pipelines, lakehouse architectures, and scalable data infrastructure. Masters ETL/ELT, Apache Spark, dbt, streaming systems, and cloud data platforms to turn raw data into trusted, analytics-ready assets. |
| `engineering-database-optimizer.md` | Expert database specialist focusing on schema design, query optimization, indexing strategies, and performance tuning for PostgreSQL, MySQL, and modern databases like Supabase and PlanetScale. |
| `engineering-devops-automator.md` | Expert DevOps engineer specializing in infrastructure automation, CI/CD pipeline development, and cloud operations |
| `engineering-drupal-shopping-cart.md` | Expert Drupal e-commerce engineer specializing in Drupal Commerce for product catalog management, payment gateway integration, checkout workflow design, order management, tax and promotion configuration, and high-reliability storefront delivery on Drupal 10/11 |
| `engineering-email-intelligence-engineer.md` | Expert in extracting structured, reasoning-ready data from raw email threads for AI agents and automation systems |
| `engineering-embedded-firmware-engineer.md` | Specialist in bare-metal and RTOS firmware - ESP32/ESP-IDF, PlatformIO, Arduino, ARM Cortex-M, STM32 HAL/LL, Nordic nRF5/nRF Connect SDK, FreeRTOS, Zephyr |
| `engineering-feishu-integration-developer.md` | Full-stack integration expert specializing in the Feishu (Lark) Open Platform — proficient in Feishu bots, mini programs, approval workflows, Bitable (multidimensional spreadsheets), interactive message cards, Webhooks, SSO authentication, and workflow automation, building enterprise-grade collaboration and automation solutions within the Feishu ecosystem. |
| `engineering-filament-optimization-specialist.md` | Expert in restructuring and optimizing Filament PHP admin interfaces for maximum usability and efficiency. Focuses on impactful structural changes — not just cosmetic tweaks. |
| `engineering-frontend-developer.md` | Expert frontend developer specializing in modern web technologies, React/Vue/Angular frameworks, UI implementation, and performance optimization |
| `engineering-git-workflow-master.md` | Expert in Git workflows, branching strategies, and version control best practices including conventional commits, rebasing, worktrees, and CI-friendly branch management. |
| `engineering-incident-response-commander.md` | Expert incident commander specializing in production incident management, structured response coordination, post-mortem facilitation, SLO/SLI tracking, and on-call process design for reliable engineering organizations. |
| `engineering-it-service-manager.md` | Expert IT service management specialist using ITIL 4 framework for service catalog design, incident and problem management, change control, SLA governance, CMDB maintenance, and continual service improvement — ensuring IT delivers reliable, measurable business value across any organization size |
| `engineering-minimal-change-engineer.md` | Engineering specialist focused on minimum-viable diffs — fixes only what was asked, refuses scope creep, prefers three similar lines over a premature abstraction. The discipline that prevents bug-fix PRs from becoming refactor avalanches. |
| `engineering-mobile-app-builder.md` | Specialized mobile application developer with expertise in native iOS/Android development and cross-platform frameworks |
| `engineering-multi-agent-systems-architect.md` | Systems architect specializing in the design, coordination, and governance of multi-agent AI pipelines — covering topology selection, context management, inter-agent trust, failure recovery, human-in-the-loop gating, and observability for production-grade agent systems. |
| `engineering-orgscript-engineer.md` | Expert in designing, parsing, and implementing OrgScript grammar, AST validation, and business logic definitions. |
| `engineering-prompt-engineer.md` | Specialist in crafting, testing, and systematically optimizing prompts for LLMs — turning vague instructions into reliable, production-grade AI behaviors. |
| `engineering-rapid-prototyper.md` | Specialized in ultra-fast proof-of-concept development and MVP creation using efficient tools and frameworks |
| `engineering-senior-developer.md` | Premium implementation specialist - Masters Laravel/Livewire/FluxUI, advanced CSS, Three.js integration |
| `engineering-software-architect.md` | Expert software architect specializing in system design, domain-driven design, architectural patterns, and technical decision-making for scalable, maintainable systems. |
| `engineering-solidity-smart-contract-engineer.md` | Expert Solidity developer specializing in EVM smart contract architecture, gas optimization, upgradeable proxy patterns, DeFi protocol development, and security-first contract design across Ethereum and L2 chains. |
| `engineering-sre.md` | Expert site reliability engineer specializing in SLOs, error budgets, observability, chaos engineering, and toil reduction for production systems at scale. |
| `engineering-technical-writer.md` | Expert technical writer specializing in developer documentation, API references, README files, and tutorials. Transforms complex engineering concepts into clear, accurate, and engaging docs that developers actually read and use. |
| `engineering-voice-ai-integration-engineer.md` | Expert in building end-to-end speech transcription pipelines using Whisper-style models and cloud ASR services — from raw audio ingestion through preprocessing, transcript cleanup, subtitle generation, speaker diarization, and structured downstream integration into apps, APIs, and CMS platforms. |
| `engineering-wechat-mini-program-developer.md` | Expert WeChat Mini Program developer specializing in 小程序 development with WXML/WXSS/WXS, WeChat API integration, payment systems, subscription messaging, and the full WeChat ecosystem. |
| `engineering-wordpress-shopping-cart.md` | Expert WordPress e-commerce engineer specializing in WooCommerce for product catalog management, payment gateway integration, checkout customization, order management, tax and coupon configuration, and conversion-optimized storefront delivery on WordPress |

### ESG

| Agent | 说明 |
|-------|------|
| `esg-sustainability-officer.md` | Corporate sustainability strategist and ESG reporting specialist who builds environmental, social, and governance programs, manages disclosures, drives decarbonization initiatives, and aligns business strategy with stakeholder and regulatory expectations. |

### 财务

| Agent | 说明 |
|-------|------|
| `finance-bookkeeper-controller.md` | Expert bookkeeper and controller specializing in day-to-day accounting operations, financial reconciliations, month-end close processes, and internal controls. Ensures the accuracy, completeness, and timeliness of financial records while maintaining GAAP compliance and audit readiness at all times. |
| `finance-financial-analyst.md` | Expert financial analyst specializing in financial modeling, forecasting, scenario analysis, and data-driven decision support. Transforms raw financial data into actionable business intelligence that drives strategic planning, investment decisions, and operational optimization. |
| `finance-fpa-analyst.md` | Expert Financial Planning & Analysis (FP&A) analyst specializing in budgeting, variance analysis, financial planning, rolling forecasts, and strategic decision support. Bridges the gap between the numbers and the business narrative to drive operational performance and strategic resource allocation. |
| `finance-investment-researcher.md` | Expert investment researcher specializing in market research, due diligence, portfolio analysis, and asset valuation. Conducts rigorous fundamental and quantitative analysis to identify investment opportunities, assess risks, and support data-driven portfolio decisions across public equities, private markets, and alternative assets. |
| `finance-tax-strategist.md` | Expert tax strategist specializing in tax optimization, multi-jurisdictional compliance, transfer pricing, and strategic tax planning. Navigates complex tax codes to minimize liability while ensuring full regulatory compliance across local, state, federal, and international tax regimes. |

### 游戏

| Agent | 说明 |
|-------|------|
| `game-audio-engineer.md` | Interactive audio specialist - Masters FMOD/Wwise integration, adaptive music systems, spatial audio, and audio performance budgeting across all game engines |
| `game-designer.md` | Systems and mechanics architect - Masters GDD authorship, player psychology, economy balancing, and gameplay loop design across all engines and genres |

### GIS

| Agent | 说明 |
|-------|------|
| `gis-3d-scene-developer.md` | Web 3D visualization specialist who creates immersive 3D scenes, terrain models, point cloud visualizations, and interactive web experiences using Cesium, ArcGIS Scene Viewer, and modern 3D web frameworks. |
| `gis-analyst.md` | Day-to-day GIS operator who creates maps, manages layers, performs spatial queries, and maintains geospatial data integrity across desktop and web environments. |
| `gis-bim-specialist.md` | Integration specialist who bridges Building Information Modeling and Geographic Information Systems — Revit/IFC data conversion, indoor mapping, digital twin architecture, and facility management data models. |
| `gis-cartography-designer.md` | Map aesthetics specialist who designs beautiful, readable, and effective maps — color theory, typography, label placement, basemap selection, and visual hierarchy for both print and web. |
| `gis-drone-reality-mapping.md` | Photogrammetry and reality capture expert who processes drone imagery into orthomosaics, digital terrain models, point clouds, and 3D meshes — bridging field capture and GIS-ready products. |
| `gis-geoai-ml-engineer.md` | Geospatial machine learning specialist who builds models for feature extraction, object detection, image segmentation, and land cover classification from satellite and aerial imagery. |
| `gis-geoprocessing-specialist.md` | ArcPy and Python toolbox expert who automates spatial workflows — builds .pyt toolboxes, Model Builder processes, batch geoprocessing automation, and custom analysis scripts for ArcGIS Pro. |
| `gis-qa-engineer.md` | Quality assurance specialist who validates geospatial data integrity — topology checks, metadata audits, CRS consistency, accuracy assessment, and compliance verification. |
| `gis-solution-engineer.md` | Hands-on GIS prototype builder who takes strategy from Technical Consultant and turns it into working demos, proof-of-concepts, and technical validations across the full Esri and open-source stack. |
| `gis-spatial-data-engineer.md` | ETL specialist who transforms messy geospatial data from any source into clean, standardized, production-ready datasets — format conversion, CRS reprojection, attribute normalization, and automated pipelines. |
| `gis-spatial-data-scientist.md` | Advanced spatial analytics specialist who applies statistical modeling, spatial econometrics, clustering, and predictive analytics to geospatial data — finding patterns that aren't visible on a map. |
| `gis-technical-consultant.md` | Strategic GIS advisor who translates business problems into geospatial solutions — gap analysis, technology roadmaps, RFP responses, and digital transformation strategy across Esri and open-source ecosystems. |
| `gis-web-gis-developer.md` | Full-stack web GIS engineer who builds interactive mapping applications — MapLibre GL JS, ArcGIS JS API, Leaflet, real-time dashboards, REST API integration, and geospatial web services. |

### Godot

| Agent | 说明 |
|-------|------|
| `godot-gameplay-scripter.md` | Composition and signal integrity specialist - Masters GDScript 2.0, C# integration, node-based architecture, and type-safe signal design for Godot 4 projects |
| `godot-multiplayer-engineer.md` | Godot 4 networking specialist - Masters the MultiplayerAPI, scene replication, ENet/WebRTC transport, RPCs, and authority models for real-time multiplayer games |
| `godot-shader-developer.md` | Godot 4 visual effects specialist - Masters the Godot Shading Language (GLSL-like), VisualShader editor, CanvasItem and Spatial shaders, post-processing, and performance optimization for 2D/3D effects |

### 政企售前

| Agent | 说明 |
|-------|------|
| `government-digital-presales-consultant.md` | Presales expert for China's government digital transformation market (ToG), proficient in policy interpretation, solution design, bid document preparation, POC validation, compliance requirements (classified protection/cryptographic assessment/Xinchuang domestic IT), and stakeholder management — helping technical teams efficiently win government IT projects. |

### Grant

| Agent | 说明 |
|-------|------|
| `grant-writer.md` | Expert grant writing specialist for nonprofits, research institutions, and social enterprises — covering prospect research, letter of inquiry writing, full proposal development, budget narratives, federal and foundation grants, and post-award reporting to maximize funding success |

### 医疗

| Agent | 说明 |
|-------|------|
| `healthcare-customer-service.md` | Empathetic healthcare customer service specialist for patient support, billing inquiries, appointment management, insurance questions, complaint resolution, and seamless escalation to clinical or administrative staff |
| `healthcare-marketing-compliance.md` | Expert in healthcare marketing compliance in China, proficient in the Advertising Law, Medical Advertisement Management Measures, Drug Administration Law, and related regulations — covering pharmaceuticals, medical devices, medical aesthetics, health supplements, and internet healthcare across content review, risk control, platform rule interpretation, and patient privacy protection, helping enterprises conduct effective health marketing within legal boundaries. |

### 酒店服务

| Agent | 说明 |
|-------|------|
| `hospitality-guest-services.md` | Comprehensive hospitality guest services specialist for hotels, resorts, restaurants, and event venues — covering reservations, check-in/check-out, concierge services, guest complaint resolution, loyalty program management, and post-stay follow-up to deliver exceptional guest experiences that drive loyalty and revenue |

### HR

| Agent | 说明 |
|-------|------|
| `hr-onboarding.md` | Comprehensive HR onboarding specialist for employee orientation, documentation management, compliance tracking, benefits enrollment, culture integration, and new hire support — delivering a seamless first-day-to-first-year experience that drives retention and productivity |

### 身份图谱

| Agent | 说明 |
|-------|------|
| `identity-graph-operator.md` | Operates a shared identity graph that multiple AI agents resolve against. Ensures every agent in a multi-agent system gets the same canonical answer for "who is this entity?" - deterministically, even under concurrent writes. |

### 翻译

| Agent | 说明 |
|-------|------|
| `language-translator.md` | Real-time Spanish ↔ English translation specialist with cultural context, regional dialect awareness, travel phrase guidance, and tone-appropriate communication for everyday, business, and emergency situations |

### 法务

| Agent | 说明 |
|-------|------|
| `legal-billing-time-tracking.md` | Comprehensive legal billing and time tracking specialist for accurate time capture, invoice generation, billing narrative writing, collections management, trust account compliance, and billing analysis — maximizing revenue recovery while maintaining client relationships and ethical compliance across any firm size or billing model |
| `legal-client-intake.md` | Comprehensive legal client intake specialist for qualifying prospects, collecting case information, scheduling consultations, managing conflict checks, and delivering attorney-ready intake summaries across any practice area and firm size |
| `legal-document-review.md` | Comprehensive legal document review specialist for contracts, litigation documents, and real estate agreements — summarizing documents, flagging risk clauses, comparing contract versions, and checking compliance across any law firm size or practice area |

### 关卡设计

| Agent | 说明 |
|-------|------|
| `level-designer.md` | Spatial storytelling and flow specialist - Masters layout theory, pacing architecture, encounter design, and environmental narrative across all game engines |

### 贷款

| Agent | 说明 |
|-------|------|
| `loan-officer-assistant.md` | Comprehensive loan officer assistant for mortgage and lending professionals — covering borrower intake, pre-qualification, document collection, pipeline management, compliance tracking, rate quoting, and closing coordination across residential, commercial, and consumer lending |

### LSP

| Agent | 说明 |
|-------|------|
| `lsp-index-engineer.md` | Language Server Protocol specialist building unified code intelligence systems through LSP client orchestration and semantic indexing |

### 并购整合

| Agent | 说明 |
|-------|------|
| `ma-integration-manager.md` | Mergers and acquisitions integration specialist who designs and executes post-merger integration programs — covering Day 1 readiness, 100-day planning, synergy tracking, cultural integration, functional workstream coordination, and transition service agreement management. |

### macOS/Metal

| Agent | 说明 |
|-------|------|
| `macos-spatial-metal-engineer.md` | Native Swift and Metal specialist building high-performance 3D rendering systems and spatial computing experiences for macOS and Vision Pro |

### 营销

| Agent | 说明 |
|-------|------|
| `marketing-aeo-foundations.md` | Expert in AI Engine Optimization infrastructure — implements llms.txt, AI-aware robots.txt, token-budgeted content, structured Markdown availability, and agent discovery files so AI crawlers, citation engines, and browsing agents can find, parse, and act on your site |
| `marketing-agentic-search-optimizer.md` | Expert in WebMCP readiness and agentic task completion — audits whether AI agents can actually accomplish tasks on your site (book, buy, register, subscribe), implements WebMCP declarative and imperative patterns, and measures task completion rates across AI browsing agents |
| `marketing-ai-citation-strategist.md` | Expert in AI recommendation engine optimization (AEO/GEO) — audits brand visibility across ChatGPT, Claude, Gemini, and Perplexity, identifies why competitors get cited instead, and delivers content fixes that improve AI citations |
| `marketing-app-store-optimizer.md` | Expert app store marketing specialist focused on App Store Optimization (ASO), conversion rate optimization, and app discoverability |
| `marketing-baidu-seo-specialist.md` | Expert Baidu search optimization specialist focused on Chinese search engine ranking, Baidu ecosystem integration, ICP compliance, Chinese keyword research, and mobile-first indexing for the China market. |
| `marketing-bilibili-content-strategist.md` | Expert Bilibili marketing specialist focused on UP主 growth, danmaku culture mastery, B站 algorithm optimization, community building, and branded content strategy for China's leading video community platform. |
| `marketing-book-co-author.md` | Strategic thought-leadership book collaborator for founders, experts, and operators turning voice notes, fragments, and positioning into structured first-person chapters. |
| `marketing-carousel-growth-engine.md` | Autonomous TikTok and Instagram carousel generation specialist. Analyzes any website URL with Playwright, generates viral 6-slide carousels via Gemini image generation, publishes directly to feed via Upload-Post API with auto trending music, fetches analytics, and iteratively improves through a data-driven learning loop. |
| `marketing-china-ecommerce-operator.md` | Expert China e-commerce operations specialist covering Taobao, Tmall, Pinduoduo, and JD ecosystems with deep expertise in product listing optimization, live commerce, store operations, 618/Double 11 campaigns, and cross-platform strategy. |
| `marketing-china-market-localization-strategist.md` | Full-stack China market localization expert who transforms real-time trend signals into executable go-to-market strategies across Douyin, Xiaohongshu, WeChat, Bilibili, and beyond |
| `marketing-content-creator.md` | Expert content strategist and creator for multi-platform campaigns. Develops editorial calendars, creates compelling copy, manages brand storytelling, and optimizes content for engagement across all digital channels. |
| `marketing-cross-border-ecommerce.md` | Full-funnel cross-border e-commerce strategist covering Amazon, Shopee, Lazada, AliExpress, Temu, and TikTok Shop operations, international logistics and overseas warehousing, compliance and taxation, multilingual listing optimization, brand globalization, and DTC independent site development. |
| `marketing-douyin-strategist.md` | Short-video marketing expert specializing in the Douyin platform, with deep expertise in recommendation algorithm mechanics, viral video planning, livestream commerce workflows, and full-funnel brand growth through content matrix strategies. |
| `marketing-email-strategist.md` | Expert email marketing strategist for CRM-driven campaigns, lifecycle automation, segmentation architecture, and deliverability. Designs sequences (welcome, nurture, reactivation, win-back, review, referral) grounded in 2025-2026 benchmarks, AI-driven personalization, and post-Apple MPP measurement. |
| `marketing-global-podcast-strategist.md` | Expert podcast growth specialist focused on show positioning, audience development, content strategy, and monetisation. Transforms raw ideas into authoritative audio brands that compound listeners and revenue over time on Spotify, Apple Podcasts, and YouTube. |
| `marketing-growth-hacker.md` | Expert growth strategist specializing in rapid user acquisition through data-driven experimentation. Develops viral loops, optimizes conversion funnels, and finds scalable growth channels for exponential business growth. |
| `marketing-instagram-curator.md` | Expert Instagram marketing specialist focused on visual storytelling, community building, and multi-format content optimization. Masters aesthetic development and drives meaningful engagement. |
| `marketing-kuaishou-strategist.md` | Expert Kuaishou marketing strategist specializing in short-video content for China's lower-tier city markets, live commerce operations, community trust building, and grassroots audience growth on 快手. |
| `marketing-linkedin-content-creator.md` | Expert LinkedIn content strategist focused on thought leadership, personal brand building, and high-engagement professional content. Masters LinkedIn's algorithm and culture to drive inbound opportunities for founders, job seekers, developers, and anyone building a professional presence. |
| `marketing-livestream-commerce-coach.md` | Veteran livestream e-commerce coach specializing in host training and live room operations across Douyin, Kuaishou, Taobao Live, and Channels, covering script design, product sequencing, paid-vs-organic traffic balancing, conversion closing techniques, and real-time data-driven optimization. |
| `marketing-multi-platform-publisher.md` | Expert orchestrator for one-click Chinese blog publishing. Routes a single article to 知乎 / 小红书 / CSDN / B站 / 公众号 / 掘金 via Wechatsync (main channel) with xhs-mcp and biliup as specialized fallbacks. Handles per-platform content adaptation, draft-first publishing, rate control, and risk-avoidance. Does NOT auto-publish — always stops at draft for human review. |
| `marketing-podcast-strategist.md` | Content strategy and operations expert for the Chinese podcast market, with deep expertise in Xiaoyuzhou, Ximalaya, and other major audio platforms, covering show positioning, audio production, audience growth, multi-platform distribution, and monetization to help podcast creators build sticky audio content brands. |
| `marketing-pr-communications-manager.md` | Strategic public relations and communications specialist for media relations, press releases, crisis communications, executive thought leadership, brand reputation management, and integrated communications planning — building and protecting reputations through earned media, storytelling, and proactive narrative control |
| `marketing-private-domain-operator.md` | Expert in building enterprise WeChat (WeCom) private domain ecosystems, with deep expertise in SCRM systems, segmented community operations, Mini Program commerce integration, user lifecycle management, and full-funnel conversion optimization. |
| `marketing-reddit-community-builder.md` | Expert Reddit marketing specialist focused on authentic community engagement, value-driven content creation, and long-term relationship building. Masters Reddit culture navigation. |
| `marketing-seo-specialist.md` | Expert search engine optimization strategist specializing in technical SEO, content optimization, link authority building, and organic search growth. Drives sustainable traffic through data-driven search strategies. |
| `marketing-short-video-editing-coach.md` | Hands-on short-video editing coach covering the full post-production pipeline, with mastery of CapCut Pro, Premiere Pro, DaVinci Resolve, and Final Cut Pro across composition and camera language, color grading, audio engineering, motion graphics and VFX, subtitle design, multi-platform export optimization, editing workflow efficiency, and AI-assisted editing. |
| `marketing-social-media-strategist.md` | Expert social media strategist for LinkedIn, Twitter, and professional platforms. Creates cross-platform campaigns, builds communities, manages real-time engagement, and develops thought leadership strategies. |
| `marketing-tiktok-strategist.md` | Expert TikTok marketing specialist focused on viral content creation, algorithm optimization, and community building. Masters TikTok's unique culture and features for brand growth. |
| `marketing-twitter-engager.md` | Expert Twitter marketing specialist focused on real-time engagement, thought leadership building, and community-driven growth. Builds brand authority through authentic conversation participation and viral thread creation. |
| `marketing-video-optimization-specialist.md` | Video marketing strategist specializing in YouTube algorithm optimization, audience retention, chaptering, thumbnail concepts, and cross-platform video syndication. |
| `marketing-wechat-official-account.md` | Expert WeChat Official Account (OA) strategist specializing in content marketing, subscriber engagement, and conversion optimization. Masters multi-format content and builds loyal communities through consistent value delivery. |
| `marketing-weibo-strategist.md` | Full-spectrum operations expert for Sina Weibo, with deep expertise in trending topic mechanics, Super Topic community management, public sentiment monitoring, fan economy strategies, and Weibo advertising, helping brands achieve viral reach and sustained growth on China's leading public discourse platform. |
| `marketing-x-twitter-intelligence-analyst.md` | Social intelligence specialist for X/Twitter research, trend detection, account monitoring, and evidence-backed audience insights using public signals and structured data workflows. |
| `marketing-xiaohongshu-specialist.md` | Expert Xiaohongshu marketing specialist focused on lifestyle content, trend-driven strategies, and authentic community engagement. Masters micro-content creation and drives viral growth through aesthetic storytelling. |
| `marketing-zhihu-strategist.md` | Expert Zhihu marketing specialist focused on thought leadership, community credibility, and knowledge-driven engagement. Masters question-answering strategy and builds brand authority through authentic expertise sharing. |

### 医疗账单

| Agent | 说明 |
|-------|------|
| `medical-billing-coding-specialist.md` | Expert medical billing and coding specialist for ICD-10-CM/PCS, CPT, and HCPCS coding, claim submission, denial management, revenue cycle optimization, compliance auditing, and payer contract analysis — maximizing clean claim rates and revenue recovery for healthcare providers of all sizes |

### 叙事

| Agent | 说明 |
|-------|------|
| `narrative-designer.md` | Story systems and dialogue architect - Masters GDD-aligned narrative design, branching dialogue, lore architecture, and environmental storytelling across all game engines |

### 运营

| Agent | 说明 |
|-------|------|
| `operations-manager.md` | Business operations specialist who applies Lean, Six Sigma, and systems thinking to process mapping, capacity planning, KPI governance, vendor management, and organizational efficiency — turning operational complexity into repeatable, measurable performance. |

### 组织心理

| Agent | 说明 |
|-------|------|
| `organizational-psychologist.md` | Applied organizational psychologist who diagnoses team dynamics, psychological safety, burnout risk, and culture health — using evidence-based frameworks to help leaders build high-performing, resilient, and psychologically safe organizations. |

### 付费媒体

| Agent | 说明 |
|-------|------|
| `paid-media-auditor.md` | Comprehensive paid media auditor who systematically evaluates Google Ads, Microsoft Ads, and Meta accounts across 200+ checkpoints spanning account structure, tracking, bidding, creative, audiences, and competitive positioning. Produces actionable audit reports with prioritized recommendations and projected impact. |
| `paid-media-creative-strategist.md` | Paid media creative specialist focused on ad copywriting, RSA optimization, asset group design, and creative testing frameworks across Google, Meta, Microsoft, and programmatic platforms. Bridges the gap between performance data and persuasive messaging. |
| `paid-media-paid-social-strategist.md` | Cross-platform paid social advertising specialist covering Meta (Facebook/Instagram), LinkedIn, TikTok, Pinterest, X, and Snapchat. Designs full-funnel social ad programs from prospecting through retargeting with platform-specific creative and audience strategies. |
| `paid-media-ppc-strategist.md` | Senior paid media strategist specializing in large-scale search, shopping, and performance max campaign architecture across Google, Microsoft, and Amazon ad platforms. Designs account structures, budget allocation frameworks, and bidding strategies that scale from $10K to $10M+ monthly spend. |
| `paid-media-programmatic-buyer.md` | Display advertising and programmatic media buying specialist covering managed placements, Google Display Network, DV360, trade desk platforms, partner media (newsletters, sponsored content), and ABM display strategies via platforms like Demandbase and 6Sense. |
| `paid-media-search-query-analyst.md` | Specialist in search term analysis, negative keyword architecture, and query-to-intent mapping. Turns raw search query data into actionable optimizations that eliminate waste and amplify high-intent traffic across paid search accounts. |
| `paid-media-tracking-specialist.md` | Expert in conversion tracking architecture, tag management, and attribution modeling across Google Tag Manager, GA4, Google Ads, Meta CAPI, LinkedIn Insight Tag, and server-side implementations. Ensures every conversion is counted correctly and every dollar of ad spend is measurable. |

### 个人成长

| Agent | 说明 |
|-------|------|
| `personal-growth-mentor.md` | Cross-domain personal development mentor for goal clarity, habit design, strategic decisions, and accountability without motivational fluff. |

### 产品

| Agent | 说明 |
|-------|------|
| `product-behavioral-nudge-engine.md` | Behavioral psychology specialist that adapts software interaction cadences and styles to maximize user motivation and success. |
| `product-feedback-synthesizer.md` | Expert in collecting, analyzing, and synthesizing user feedback from multiple channels to extract actionable product insights. Transforms qualitative feedback into quantitative priorities and strategic recommendations. |
| `product-manager.md` | Holistic product leader who owns the full product lifecycle — from discovery and strategy through roadmap, stakeholder alignment, go-to-market, and outcome measurement. Bridges business goals, user needs, and technical reality to ship the right thing at the right time. |
| `product-sprint-prioritizer.md` | Expert product manager specializing in agile sprint planning, feature prioritization, and resource allocation. Focused on maximizing team velocity and business value delivery through data-driven prioritization frameworks. |
| `product-trend-researcher.md` | Expert market intelligence analyst specializing in identifying emerging trends, competitive analysis, and opportunity assessment. Focused on providing actionable insights that drive product strategy and innovation decisions. |

### 项目管理

| Agent | 说明 |
|-------|------|
| `project-management-experiment-tracker.md` | Expert project manager specializing in experiment design, execution tracking, and data-driven decision making. Focused on managing A/B tests, feature experiments, and hypothesis validation through systematic experimentation and rigorous analysis. |
| `project-management-jira-workflow-steward.md` | Expert delivery operations specialist who enforces Jira-linked Git workflows, traceable commits, structured pull requests, and release-safe branch strategy across software teams. |
| `project-management-meeting-notes-specialist.md` | Extract structured decisions, action items, and open questions from meeting transcripts or rough notes into a clean 4-section summary. |
| `project-management-project-shepherd.md` | Expert project manager specializing in cross-functional project coordination, timeline management, and stakeholder alignment. Focused on shepherding projects from conception to completion while managing resources, risks, and communications across multiple teams and departments. |
| `project-management-studio-operations.md` | Expert operations manager specializing in day-to-day studio efficiency, process optimization, and resource coordination. Focused on ensuring smooth operations, maintaining productivity standards, and supporting all teams with the tools and processes needed for success. |
| `project-management-studio-producer.md` | Senior strategic leader specializing in high-level creative and technical project orchestration, resource allocation, and multi-project portfolio management. Focused on aligning creative vision with business objectives while managing complex cross-functional initiatives and ensuring optimal studio operations. |
| `project-manager-senior.md` | Converts specs to tasks and remembers previous projects. Focused on realistic scope, no background processes, exact spec requirements |

### 地产

| Agent | 说明 |
|-------|------|
| `real-estate-buyer-seller.md` | Comprehensive real estate agent assistant for buyer representation, seller representation, listing management, offer negotiation, transaction coordination, and closing support — delivering a world-class client experience from first showing to final closing across residential and investment real estate |

### 招聘

| Agent | 说明 |
|-------|------|
| `recruitment-specialist.md` | Expert recruitment operations and talent acquisition specialist — skilled in China's major hiring platforms, talent assessment frameworks, and labor law compliance. Helps companies efficiently attract, screen, and retain top talent while building a competitive employer brand. |

### 报告

| Agent | 说明 |
|-------|------|
| `report-distribution-agent.md` | AI agent that automates distribution of consolidated sales reports to representatives based on territorial parameters |

### 零售

| Agent | 说明 |
|-------|------|
| `retail-customer-returns.md` | Comprehensive retail customer returns specialist for processing returns, exchanges, and refunds across in-store, online, and omnichannel retail — handling policy enforcement, fraud prevention, customer retention, vendor returns, and returns analytics to maximize recovery while preserving customer loyalty |

### Roblox

| Agent | 说明 |
|-------|------|
| `roblox-avatar-creator.md` | Roblox UGC and avatar pipeline specialist - Masters Roblox's avatar system, UGC item creation, accessory rigging, texture standards, and the Creator Marketplace submission pipeline |
| `roblox-experience-designer.md` | Roblox platform UX and monetization specialist - Masters engagement loop design, DataStore-driven progression, Roblox monetization systems (Passes, Developer Products, UGC), and player retention for Roblox experiences |
| `roblox-systems-scripter.md` | Roblox platform engineering specialist - Masters Luau, the client-server security model, RemoteEvents/RemoteFunctions, DataStore, and module architecture for scalable Roblox experiences |

### 销售

| Agent | 说明 |
|-------|------|
| `sales-account-strategist.md` | Expert post-sale account strategist specializing in land-and-expand execution, stakeholder mapping, QBR facilitation, and net revenue retention. Turns closed deals into long-term platform relationships through systematic expansion planning and multi-threaded account development. |
| `sales-coach.md` | Expert sales coaching specialist focused on rep development, pipeline review facilitation, call coaching, deal strategy, and forecast accuracy. Makes every rep and every deal better through structured coaching methodology and behavioral feedback. |
| `sales-data-extraction-agent.md` | AI agent specialized in monitoring Excel files and extracting key sales metrics (MTD, YTD, Year End) for internal live reporting |
| `sales-deal-strategist.md` | Senior deal strategist specializing in MEDDPICC qualification, competitive positioning, and win planning for complex B2B sales cycles. Scores opportunities, exposes pipeline risk, and builds deal strategies that survive forecast review. |
| `sales-discovery-coach.md` | Coaches sales teams on elite discovery methodology — question design, current-state mapping, gap quantification, and call structure that surfaces real buying motivation. |
| `sales-engineer.md` | Senior pre-sales engineer specializing in technical discovery, demo engineering, POC scoping, competitive battlecards, and bridging product capabilities to business outcomes. Wins the technical decision so the deal can close. |
| `sales-offer-lead-gen-strategist.md` | Top-of-funnel architect who designs irresistible offers and lead magnets that attract qualified buyers at scale. Specializes in value-equation offer construction, lead magnet typology, multi-channel lead generation, and compounding reach through customers, employees, agencies, and affiliates. |
| `sales-outbound-strategist.md` | Signal-based outbound specialist who designs multi-channel prospecting sequences, defines ICPs, and builds pipeline through research-driven personalization — not volume. |
| `sales-outreach.md` | Consultative B2B sales outreach specialist for cold prospecting, lead follow-up, objection handling, proposal writing, and pipeline management — combining data-driven targeting with genuine relationship-building to open doors and close deals |
| `sales-pipeline-analyst.md` | Revenue operations analyst specializing in pipeline health diagnostics, deal velocity analysis, forecast accuracy, and data-driven sales coaching. Turns CRM data into actionable pipeline intelligence that surfaces risks before they become missed quarters. |
| `sales-proposal-strategist.md` | Strategic proposal architect who transforms RFPs and sales opportunities into compelling win narratives. Specializes in win theme development, competitive positioning, executive summary craft, and building proposals that persuade rather than merely comply. |

### 安全

| Agent | 说明 |
|-------|------|
| `security-appsec-engineer.md` | AppSec specialist who secures the software development lifecycle through threat modeling, secure code review, SAST/DAST integration, and developer security education that makes secure code the default. |
| `security-architect.md` | Expert security architect specializing in threat modeling, secure-by-design architecture, trust-boundary analysis, defense-in-depth, and risk-based security reviews across web, API, cloud-native, and distributed systems. Designs the security model; hands code-level SAST/DAST and SDLC work to the AppSec Engineer. |
| `security-blockchain-security-auditor.md` | Expert smart contract security auditor specializing in vulnerability detection, formal verification, exploit analysis, and comprehensive audit report writing for DeFi protocols and blockchain applications. |
| `security-cloud-security-architect.md` | Cloud-native security specialist designing zero trust architectures, implementing defense-in-depth across AWS, Azure, and GCP, and securing infrastructure-as-code pipelines from day one. |
| `security-compliance-auditor.md` | Expert technical compliance auditor specializing in SOC 2, ISO 27001, HIPAA, and PCI-DSS audits — from readiness assessment through evidence collection to certification. |
| `security-incident-responder.md` | Digital forensics and incident response specialist who leads breach investigations, contains active threats, coordinates crisis response, and writes post-mortems that prevent recurrence. |
| `security-penetration-tester.md` | Offensive security specialist conducting authorized penetration tests, red team operations, and vulnerability assessments across networks, web applications, and cloud infrastructure. |
| `security-senior-secops.md` | Defensive application security specialist who scans every code submission for secrets and sensitive data exposure before anything else, then implements or audits security controls following the organization's security standard — covering authentication, authorization, tokens, cookies, HTTP headers, CORS, rate limiting, CSP, secrets management, input validation, and secure logging. |
| `security-threat-detection-engineer.md` | Expert detection engineer specializing in SIEM rule development, MITRE ATT&CK coverage mapping, threat hunting, alert tuning, and detection-as-code pipelines for security operations teams. |
| `security-threat-intelligence-analyst.md` | Cyber threat intelligence specialist who tracks adversary groups, maps attack campaigns to MITRE ATT&CK, produces actionable intelligence reports, and builds detection rules that catch real threats. |

### 专家领域

| Agent | 说明 |
|-------|------|
| `specialized-chief-of-staff.md` | Master coordinator for founders and executives — filters noise, owns processes, enforces consistency, routes decisions, and positions outputs for impact so the boss can think clearly. |
| `specialized-civil-engineer.md` | Expert civil and structural engineer with global standards coverage — Eurocode, DIN, ACI, AISC, ASCE, AS/NZS, CSA, GB, IS, AIJ, and more. Specializes in structural analysis, geotechnical design, construction documentation, building code compliance, and multi-standard international projects. |
| `specialized-cultural-intelligence-strategist.md` | CQ specialist that detects invisible exclusion, researches global context, and ensures software resonates authentically across intersectional identities. |
| `specialized-developer-advocate.md` | Expert developer advocate specializing in building developer communities, creating compelling technical content, optimizing developer experience (DX), and driving platform adoption through authentic engineering engagement. Bridges product and engineering teams with external developers. |
| `specialized-document-generator.md` | Expert document creation specialist who generates professional PDF, PPTX, DOCX, and XLSX files using code-based approaches with proper formatting, charts, and data visualization. |
| `specialized-french-consulting-market.md` | Navigate the French ESN/SI freelance ecosystem — margin models, platform mechanics (Malt, collective.work), portage salarial, rate positioning, and payment cycle realities |
| `specialized-korean-business-navigator.md` | Korean business culture for foreign professionals — 품의 decision process, nunchi reading, KakaoTalk business etiquette, hierarchy navigation, and relationship-first deal mechanics |
| `specialized-mcp-builder.md` | Expert Model Context Protocol developer who designs, builds, and tests MCP servers that extend AI agent capabilities with custom tools, resources, and prompts. |
| `specialized-model-qa.md` | Independent model QA expert who audits ML and statistical models end-to-end - from documentation review and data reconstruction to replication, calibration testing, interpretability analysis, performance monitoring, and audit-grade reporting. |
| `specialized-pricing-analyst.md` | Specialized pricing analyst who develops optimal pricing models through market research, competitor analysis, cost structure evaluation, and margin optimization — turning pricing from guesswork into a data-driven competitive advantage. |
| `specialized-salesforce-architect.md` | Solution architecture for Salesforce platform — multi-cloud design, integration patterns, governor limits, deployment strategy, and data model governance for enterprise-scale orgs |
| `specialized-strategy-duel-agent.md` | Conducts live strategy duels using game theory and the 36 Chinese stratagems |
| `specialized-workflow-architect.md` | Workflow design specialist who maps complete workflow trees for every system, user journey, and agent interaction — covering happy paths, all branch conditions, failure modes, recovery paths, handoff contracts, and observable states to produce build-ready specs that agents can implement against and QA can test against. |

### 留学

| Agent | 说明 |
|-------|------|
| `study-abroad-advisor.md` | Full-spectrum study abroad planning expert covering the US, UK, Canada, Australia, Europe, Hong Kong, and Singapore — proficient in undergraduate, master's, and PhD application strategy, school selection, essay coaching, profile enhancement, standardized test planning, visa preparation, and overseas life adaptation, helping Chinese students craft personalized end-to-end study abroad plans. |

### 供应链

| Agent | 说明 |
|-------|------|
| `supply-chain-strategist.md` | Expert supply chain management and procurement strategy specialist — skilled in supplier development, strategic sourcing, quality control, and supply chain digitalization. Grounded in China's manufacturing ecosystem, helps companies build efficient, resilient, and sustainable supply chains. |

### 支持

| Agent | 说明 |
|-------|------|
| `support-analytics-reporter.md` | Expert data analyst transforming raw data into actionable business insights. Creates dashboards, performs statistical analysis, tracks KPIs, and provides strategic decision support through data visualization and reporting. |
| `support-executive-summary-generator.md` | Consultant-grade AI specialist trained to think and communicate like a senior strategy consultant. Transforms complex business inputs into concise, actionable executive summaries using McKinsey SCQA, BCG Pyramid Principle, and Bain frameworks for C-suite decision-makers. |
| `support-finance-tracker.md` | Expert financial analyst and controller specializing in financial planning, budget management, and business performance analysis. Maintains financial health, optimizes cash flow, and provides strategic financial insights for business growth. |
| `support-infrastructure-maintainer.md` | Expert infrastructure specialist focused on system reliability, performance optimization, and technical operations management. Maintains robust, scalable infrastructure supporting business operations with security, performance, and cost efficiency. |
| `support-legal-compliance-checker.md` | Expert legal and compliance specialist ensuring business operations, data handling, and content creation comply with relevant laws, regulations, and industry standards across multiple jurisdictions. |
| `support-support-responder.md` | Expert customer support specialist delivering exceptional customer service, issue resolution, and user experience optimization. Specializes in multi-channel support, proactive customer care, and turning support interactions into positive brand experiences. |

### 技术美术

| Agent | 说明 |
|-------|------|
| `technical-artist.md` | Art-to-engine pipeline specialist - Masters shaders, VFX systems, LOD pipelines, performance budgeting, and cross-engine asset optimization |

### 终端集成

| Agent | 说明 |
|-------|------|
| `terminal-integration-specialist.md` | Terminal emulation, text rendering optimization, and SwiftTerm integration for modern Swift applications |

### 测试

| Agent | 说明 |
|-------|------|
| `testing-accessibility-auditor.md` | Expert accessibility specialist who audits interfaces against WCAG standards, tests with assistive technologies, and ensures inclusive design. Defaults to finding barriers — if it's not tested with a screen reader, it's not accessible. |
| `testing-api-tester.md` | Expert API testing specialist focused on comprehensive API validation, performance testing, and quality assurance across all systems and third-party integrations |
| `testing-evidence-collector.md` | Screenshot-obsessed, fantasy-allergic QA specialist - Default to finding 3-5 issues, requires visual proof for everything |
| `testing-performance-benchmarker.md` | Expert performance testing and optimization specialist focused on measuring, analyzing, and improving system performance across all applications and infrastructure |
| `testing-reality-checker.md` | Stops fantasy approvals, evidence-based certification - Default to "NEEDS WORK", requires overwhelming proof for production readiness |
| `testing-test-results-analyzer.md` | Expert test analysis specialist focused on comprehensive test result evaluation, quality metrics analysis, and actionable insight generation from testing activities |
| `testing-tool-evaluator.md` | Expert technology assessment specialist focused on evaluating, testing, and recommending tools, software, and platforms for business use and productivity optimization |
| `testing-workflow-optimizer.md` | Expert process improvement specialist focused on analyzing, optimizing, and automating workflows across all business functions for maximum productivity and efficiency |

### Unity

| Agent | 说明 |
|-------|------|
| `unity-architect.md` | Data-driven modularity specialist - Masters ScriptableObjects, decoupled systems, and single-responsibility component design for scalable Unity projects |
| `unity-editor-tool-developer.md` | Unity editor automation specialist - Masters custom EditorWindows, PropertyDrawers, AssetPostprocessors, ScriptedImporters, and pipeline automation that saves teams hours per week |
| `unity-multiplayer-engineer.md` | Networked gameplay specialist - Masters Netcode for GameObjects, Unity Gaming Services (Relay/Lobby), client-server authority, lag compensation, and state synchronization |
| `unity-shader-graph-artist.md` | Visual effects and material specialist - Masters Unity Shader Graph, HLSL, URP/HDRP rendering pipelines, and custom pass authoring for real-time visual effects |

### Unreal

| Agent | 说明 |
|-------|------|
| `unreal-multiplayer-architect.md` | Unreal Engine networking specialist - Masters Actor replication, GameMode/GameState architecture, server-authoritative gameplay, network prediction, and dedicated server setup for UE5 |
| `unreal-systems-engineer.md` | Performance and hybrid architecture specialist - Masters C++/Blueprint continuum, Nanite geometry, Lumen GI, and Gameplay Ability System for AAA-grade Unreal Engine projects |
| `unreal-technical-artist.md` | Unreal Engine visual pipeline specialist - Masters the Material Editor, Niagara VFX, Procedural Content Generation, and the art-to-engine pipeline for UE5 projects |
| `unreal-world-builder.md` | Open-world and environment specialist - Masters UE5 World Partition, Landscape, procedural foliage, HLOD, and large-scale level streaming for seamless open-world experiences |

### visionOS

| Agent | 说明 |
|-------|------|
| `visionos-spatial-engineer.md` | Native visionOS spatial computing, SwiftUI volumetric interfaces, and Liquid Glass design implementation |

### XR

| Agent | 说明 |
|-------|------|
| `xr-cockpit-interaction-specialist.md` | Specialist in designing and developing immersive cockpit-based control systems for XR environments |
| `xr-immersive-developer.md` | Expert WebXR and immersive technology developer with specialization in browser-based AR/VR/XR applications |
| `xr-interface-architect.md` | Spatial interaction designer and interface strategist for immersive AR/VR/XR environments |

### ZK

| Agent | 说明 |
|-------|------|
| `zk-steward.md` | Knowledge-base steward in the spirit of Niklas Luhmann's Zettelkasten. Default perspective: Luhmann; switches to domain experts (Feynman, Munger, Ogilvy, etc.) by task. Enforces atomic notes, connectivity, and validation loops. Use for knowledge-base building, note linking, complex task breakdown, and cross-domain decision support. |

## 维护

```bash
find . -maxdepth 1 -name '*.md' ! -name README.md | wc -l
git status --short
```

## 许可证

个人配置仓库，按仓库实际授权为准。
