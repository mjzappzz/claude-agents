# Claude Agents

Claude Code 的自定义 **Agent** 集合 — 100+ 领域专家代理。

---

## 目录结构

```
.
├── *.md                    # Agent 定义文件（100+）
├── jarvis.md               # J.A.R.V.I.S. 路由配置
└── README.md               # 本文件
```

---

## Agents

按领域分类的 100+ 个专家代理，每个是一个独立 `.md` 文件：

| 领域 | 数量 | 示例 |
|------|------|------|
| 🎓 学术 | 5 | Anthropologist, Historian, Geographer |
| 💰 财务 | 7 | CFO, Financial Analyst, Tax Strategist |
| 🎨 设计 | 9 | UI Designer, UX Architect, Brand Guardian |
| 🛠 工程 | 35+ | Frontend, Backend, DevOps, SRE, Security |
| 🎮 游戏 | 20+ | Unity, Unreal, Godot, Roblox, Blender |
| 🌐 GIS | 12 | Web GIS, Cartography, BIM/GIS |
| 📱 营销 | 35+ | SEO, TikTok, WeChat, Xiaohongshu... |
| 💼 销售 | 12 | Deal Strategist, Sales Coach, Pipeline Analyst |
| 🔒 安全 | 10 | AppSec, Penetration Tester, Threat Intel |

每个 Agent 包含 YAML 前置元数据（名称、描述、可用工具、模型、最大轮数）和系统提示词。

---

## J.A.R.V.I.S. 路由

`jarvis.md` 配置了智能路由规则，通过关键词自动匹配到最合适的 Agent 或 Skill。

---

## 使用方式

```bash
# 直接调用 Agent
帮我写一个 Solidity 合约

# 通过 J.A.R.V.I.S. 路由（需提及"贾维斯"或"路由"关键词）
贾维斯，帮我做 SEO 分析
```

---

## 许可证

MIT
