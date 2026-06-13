# Claude Agents

Claude Code 的自定义 **Agent** 集合 — 100+ 领域专家代理，覆盖工程、设计、营销、安全、财务、游戏开发等全领域。

通过 J.A.R.V.I.S. 智能路由系统，你只需要用自然语言描述需求，就能自动匹配合适的专家代理来处理。

---

## 目录

- [简介](#简介)
- [安装与配置](#安装与配置)
- [快速开始](#快速开始)
- [目录结构](#目录结构)
- [Agents 一览](#agents-一览)
- [使用方式](#使用方式)
  - [方式一：直接对话](#方式一直接对话)
  - [方式二：J.A.R.V.I.S. 智能路由](#方式二jarvis-智能路由)
  - [方式三：多 Agent 协作](#方式三多-agent-协作)
- [J.A.R.V.I.S. 路由详解](#jarvis-路由详解)
- [创建你自己的 Agent](#创建你自己的-agent)
- [最佳实践](#最佳实践)
- [许可证](#许可证)

---

## 简介

Claude Code 是 Anthropic 推出的 AI 编程助手 CLI 工具。它支持自定义 **Agent** 机制：

- **Agent** 是一个 `.md` 文件，定义了专家的角色、系统提示词、可用工具和模型配置
- 对话中通过自然语言或 J.A.R.V.I.S. 自动路由来激活对应的 Agent
- Agent 会在独立子会话中执行任务，完成后返回结果

本仓库是您的个人 AI 专家团队配置文件，拿来即用。

---

## 安装与配置

### 前置条件

- 安装 [Claude Code](https://claude.ai/code)
- 有效的 Claude 订阅

### 安装步骤

```bash
# 1. 克隆本仓库到 Claude Agents 目录
git clone git@github.com:mjzappzz/claude-agents.git ~/.claude/agents

# 2. 克隆 Skills（配套知识包，可选）
# 如果你也需要 Skills，从 Skills 仓库同样操作

# 3. 验证安装
ls ~/.claude/agents/*.md  # 应该看到 100+ agent 文件
```

### 配置 Claude Code

在 `~/.claude/settings.json` 中设置：

```json
{
  "permissions": {
    "allow": {
      "agent": true
    }
  }
}
```

更多配置请参考 [Claude Code 官方文档](https://docs.anthropic.com/en/docs/claude-code)。

---

## 快速开始

```bash
# 直接对话 — Claude 会自动识别需求并响应当前 Agent 的能力
帮我修复这个 SQL 注入漏洞

# 调用 J.A.R.V.I.S. 路由 — 自动匹配合适的专家
贾维斯，帮我做一份市场竞品分析

# 多 Agent 协作
贾维斯，帮我分析这个网站的性能问题并给出优化方案
```

---

## 目录结构

```
~/.claude/agents/
├── *.md                     # Agent 定义文件（100+）
├── jarvis.md                # J.A.R.V.I.S. 智能路由配置
└── README.md                # 本文件
```

每个 Agent 是一个独立的 Markdown 文件，包含：

```yaml
---
name: Agent Name           # Agent 名称
description: 一句话描述     # 用于路由匹配
color: blue                # 显示颜色
emoji: 🤖                  # 显示图标
tools:                     # 可用工具列表（可选）
  - Skill                  # 允许加载 Skill
  - Bash                   # 允许执行命令
  - Read                   # 允许读取文件
model:                     # 模型配置（可选）
  - claude-sonnet-4-6
maxTurns: 30               # 最大对话轮次（可选）
---
```

---

## Agents 一览

按领域分类的 100+ 专家代理：

| 领域 | 数量 | 覆盖范围 |
|------|------|---------|
| 🛠 **工程与开发** | 35+ | 前端、后端、全栈、移动端、DevOps、SRE、嵌入式、区块链、AI/ML、数据库、代码审查、技术写作等 |
| 🎨 **设计** | 9 | UI 设计、UX 架构、品牌管理、视觉叙事、图像生成、包容性设计 |
| 🎮 **游戏开发** | 20+ | Unity、Unreal、Godot、Roblox 各子领域（架构/多人/着色器/技术美术） |
| 📱 **中国市场营销** | 15+ | 抖音、小红书、B站、微信、微博、知乎、百度 SEO、跨境电商、私域运营 |
| 🌍 **全球营销** | 20+ | SEO、TikTok、Instagram、Twitter、LinkedIn、Reddit、播客、邮件营销、视频优化 |
| 💰 **销售与商业** | 14+ | 销售拓展、售前、客户策略、交易策略、提案、管道分析 |
| 📊 **付费媒体** | 7 | PPC、社媒广告、广告审计、程序化广告、转化跟踪 |
| 🔒 **安全** | 10 | 安全架构、应用安全、渗透测试、应急响应、威胁情报、云安全 |
| 💵 **财务与法务** | 11 | 财务分析、FP&A、税务、合同审查、应付账款、法律合规 |
| 👥 **人力资源与运营** | 15+ | 招聘、培训、组织心理、客服、客户成功、供应链 |
| 📋 **产品与项目管理** | 12 | 产品管理、Sprint 排期、趋势研究、项目管理、会议记录 |
| 🧪 **测试与质量** | 8 | API 测试、性能基准、无障碍审计、工具评估 |
| 🗺️ **GIS 与地理空间** | 13+ | 3D 场景、无人机、空间数据科学、Web GIS |
| 🥽 **XR 与空间计算** | 7 | WebXR、visionOS、macOS Metal、终端集成 |
| 🧠 **专家领域** | 15+ | 土木工程、MCP 构建、定价分析、Salesforce、工作流架构 |
| 🎓 **学术** | 5 | 人类学、地理学、历史学、叙事学、心理学 |
| ✅ **其他通用** | 12+ | 数据分析、执行摘要、翻译、个人成长、留学顾问 |

> 每个 Agent 文件以 `domain-specialty.md` 命名，便于查找和管理。

---

## 使用方式

### 方式一：直接对话

直接在 Claude Code 中描述需求，不需要提及任何 Agent 名称：

```bash
帮我写一个 React 自定义 Hook，用于处理表单验证
分析这段代码的性能瓶颈在哪里
设计一个微服务架构的电商系统
```

Claude Code 会根据任务内容自动选择最合适的 Agent。

### 方式二：J.A.R.V.I.S. 智能路由

提及"贾维斯"或"路由"等关键词，触发自动路由：

```bash
# 工程类
贾维斯，帮我搭建一个 CI/CD 流水线

# 设计类（会自动加载对应 Skill）
贾维斯，帮我设计一个品牌 Logo

# 营销类
贾维斯，帮我分析这个网站的 SEO 问题

# 安全类
贾维斯，审查这段代码的安全漏洞

# 游戏类
贾维斯，帮我优化 Unity 游戏的渲染性能

# 财务类
贾维斯，帮我做一个财务预测模型

# GIS 类
贾维斯，帮我生成一份 WebGIS 地图可视化

# 多 Agent 协作
贾维斯，我要开发一个电商系统，帮我安排前端、后端和数据库的专家一起工作
```

**路由规则示例（部分）：**

| 你的需求关键词 | 命中 Agent | 说明 |
|---------------|-----------|------|
| React / 前端 / Web界面 | Frontend Developer | 前端开发 |
| 后端 / API / 微服务 | Backend Architect | 后端架构 |
| SQL / 查询优化 / 数据库 | Database Optimizer | 数据库优化 |
| DevOps / Docker / K8s | DevOps Automator | 基础设施 |
| 渗透 / 安全审计 | Penetration Tester | 安全测试 |
| 抖音 / 快手 / 短视频 | Douyin Strategist | 中国短视频 |
| 小红书 / 种草 | Xiaohongshu Specialist | 小红书营销 |
| SEO / 关键词排名 | SEO Specialist | SEO 优化 |
| Solidity / 智能合约 | Solidity Engineer | 区块链开发 |
| Unity / 游戏性能 | Unity Architect | Unity 开发 |

完整路由表请查看 `jarvis.md`。

### 方式三：多 Agent 协作

J.A.R.V.I.S. 能同时调度多个 Agent 协同工作：

```bash
贾维斯，帮我完成一个全栈项目：
1. 设计后端 API 架构
2. 开发前端界面
3. 配置 CI/CD 部署
4. 编写项目文档
```

J.A.R.V.I.S. 会自动拆分任务、分派给对应专家、汇总结果后给你统一答复。

---

## J.A.R.V.I.S. 路由详解

`jarvis.md` 是本系统的核心路由引擎。它的工作流程：

```
用户需求
    ↓
分析阶段
    ├─ 识别任务类型（开发/设计/营销/安全/...）
    ├─ 确定所需专业领域
    └─ 判断是否需要多 Agent 协作
    ↓
选择阶段
    ├─ 匹配关键词路由表
    ├─ 确定主 Agent（和副 Agent）
    └─ 确定是否需加载 Skill
    ↓
执行阶段
    ├─ 调 Agent → @AgentName 派活
    ├─ 调 Skill → Skill 工具加载知识包
    └─ 自行处理 → 简单任务直接完成
    ↓
整合阶段
    ├─ 收集各 Agent 结果
    ├─ 合并去重
    └─ 统一格式
    ↓
交付阶段
    └─ 呈现最终结果给用户
```

**Skill 自动加载：** J.A.R.V.I.S. 检测到设计类需求时（如"设计 Logo"、"做个 Banner"、"调整 UI 样式"），会自动调用 `Skill` 工具将对应 Skill 加载到当前对话，然后利用 Skill 的知识完成设计任务。

---

## 创建你自己的 Agent

在 `~/.claude/agents/` 下新建一个 `.md` 文件：

```markdown
---
name: Python Code Reviewer
description: Expert Python code reviewer specializing in performance and best practices
color: green
emoji: 🐍
tools:
  - Read
  - Write
  - Bash
  - WebSearch
model:
  - claude-sonnet-4-6
maxTurns: 20
---

# Python Code Review Specialist

You are a senior Python code reviewer with deep expertise in ...

## Your Expertise

- Python 3.12+ features and idioms
- Performance optimization (CPython internals, profiling)
- Type hints and static analysis (mypy, pyright)
- Async/await patterns (asyncio, trio, anyio)

## Review Checklist

Always check for:
1. **Performance** — unnecessary allocations, slow patterns
2. **Type Safety** — missing type hints, Any usage
3. **Error Handling** — bare excepts, swallowed exceptions
4. **Security** — eval usage, shell injection, path traversal
5. **Best Practices** — PEP 8, PEP 484, design patterns

## Communication Style

- Be direct and specific
- Show before/after code for each issue
- Prioritize findings by severity
```

然后在 `jarvis.md` 的路由表中添加对应规则，这样 J.A.R.V.I.S. 就能路由到这个新 Agent。

---

## 最佳实践

### 日常使用

- **简单问题直接问** — 不需要每次都叫"贾维斯"，Claude Code 会自动处理
- **复杂任务叫贾维斯** — 涉及多步骤或需要专家协作的，让贾维斯来调度
- **设计类任务不需要指定 skill** — 贾维斯会自动加载对应的 Skill 知识包

### Agent 管理

- **按领域分组** — 文件名格式 `domain-specific.md`，方便查找
- **定期更新路由表** — 添加新 Agent 后同步更新 jarvis.md 的关键词映射
- **保持 Agent 专注** — 每个 Agent 做一件事，不要堆砌多个领域到一个文件

### 与 Skills 配合使用

本系统配套了 7 个 Skills（位于 `~/.claude/skills/`）：

| Skill | 用途 | 自动加载条件 |
|-------|------|-------------|
| `ui-ux-pro-max` | UI/UX 设计（50+ 风格、161 调色板） | 提到 UI/UX 设计、风格等 |
| `ui-styling` | shadcn/ui + Tailwind CSS | 提到 UI 样式、组件库 |
| `banner-design` | 多平台 Banner 设计 | 提到 Banner、广告图 |
| `brand` | 品牌识别与色板管理 | 提到品牌、色板 |
| `design-system` | 设计 Token 与规范 | 提到设计系统 |
| `slides` | HTML 演示文稿 | 提到幻灯片、PPT |
| `design` | Logo/CIP/图标生成 | 提到 Logo、图标 |

---

## 许可证

MIT

---

**相关资源：**
- [Claude Code 官方文档](https://docs.anthropic.com/en/docs/claude-code)
- [Skills 仓库](https://github.com/mjzappzz/claude-skills)（如果已分开托管）
- [Anthropic 官方](https://anthropic.com)
