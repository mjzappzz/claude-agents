# Claude Agents & Skills

Claude Code 的自定义 **Agents** 和 **Skills** 集合。

---

## 目录结构

```
.
├── *.md                    # Agent 定义文件（100+）
├── jarvis.md               # J.A.R.V.I.S. 路由配置
├── banner-design/          # Banner 设计 Skill
├── brand/                  # 品牌管理 Skill
├── design/                 # 综合设计 Skill（Logo/CIP/图标）
├── design-system/          # 设计系统 Skill（Token/Slides）
├── slides/                 # 幻灯片 Skill
├── ui-styling/             # UI 样式 Skill（shadcn/Tailwind）
└── ui-ux-pro-max/          # UI/UX Pro Max 设计智能 Skill
```

---

## Agents

按领域分类的 100+ 个专家代理：

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

每个 Agent 是一个独立的 `.md` 文件，定义了角色、提示词和行为准则。

---

## Skills

Skills 是带参考资源的知识包，通过 `/skill-name` 在当前对话中加载：

| Skill | 用途 |
|-------|------|
| `ui-styling` | shadcn/ui + Tailwind 组件与样式 |
| `ui-ux-pro-max` | 50+ 风格、161 调色板、UX 指南 |
| `design` | Logo 生成、CIP、图标、海报 |
| `banner-design` | 多平台 Banner 设计 |
| `brand` | 品牌识别、色板、排版管理 |
| `design-system` | 设计 Token、幻灯片生成 |
| `slides` | HTML 演示文稿 |

---

## J.A.R.V.I.S. 路由

`jarvis.md` 配置了智能路由规则，通过关键词自动匹配到最合适的 Agent 或 Skill。

示例：
- "帮我看一下这个 UI 问题" → `ui-ux-pro-max` Skill
- "写一个 Solidity 合约" → Solidity Smart Contract Engineer Agent
- "做 SEO 分析" → SEO Specialist Agent

---

## 使用方式

```bash
# 在 Claude Code 中调用 Skill
/ui-ux-pro-max 设计一个登录页面

# 通过 J.A.R.V.I.S. 路由
帮我设计一个品牌 Logo
```

---

## 许可证

MIT
