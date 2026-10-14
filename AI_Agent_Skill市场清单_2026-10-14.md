# AI Agent Skill 市场清单（截至 2026-10-14）

Skill 市场是 AI Agent 生态中的能力分发与管理平台，用于集中发布、发现和安装各类 AI 技能模块。当前可分为四类：模型厂商官方生态、国内互联网大厂商店、开源社区仓库、第三方聚合平台。

## 一、市场总览与规模对比

| 类别 | 平台 | 地址 | 规模/统计 | 特点 |
|---|---|---|---|---|
| 官方生态 | Anthropic Skills 仓库 | github.com/anthropics/skills | 16 个核心示例，含 docx/pdf/xlsx 等 | 生产级质量，SKILL.md 标准来源 |
| 官方生态 | OpenAI GPT Store | — | 上线时已超 300 万个 GPTs | 零代码创建，覆盖 7 个垂直领域 |
| 官方生态 | Dify Marketplace | marketplace.dify.ai | — | 插件经审核，解耦架构 |
| 第三方聚合 | skills.sh（Vercel Labs） | skills.sh | 全站累计约 130.9 万次安装记录；第一名 find-skills 约 380 万 8 周活跃 | `npx skills add` 一键安装，支持 11 个 Agent，10 月新增 Skill Packs |
| 第三方聚合 | SkillsMP | skillsmp.com | 60,000+（1 月为 50,000+） | 聚合 GitHub 开源技能，含质量评分与兼容标识 |
| 第三方聚合 | Smithery.ai | smithery.ai/skills | 15,000+ | 显示激活次数与 GitHub Stars |
| 第三方聚合 | Agent Foundry | — | 37,000+ | S/A/B/C 质量评级，一键部署 |
| 第三方聚合 | AI Templates | aitmpl.com/skills | 254+ 精选 | 企业级配置模板 |
| 第三方聚合 | Skill Atlas | ai.skillatlas.cn | — | 中国 AI Agent 技能地图 |
| 开源社区 | ClawHub（OpenClaw 官方） | clawhub.ai | 11,646 个（10 月 10 日）；3 月曾报 13,600+ | 全球首个开源 Skill 共享平台 |
| 开源社区 | ComposioHQ awesome-claude-skills | GitHub | 16.5k+ Star，300+ 精选 | 持续更新的 awesome 列表 |
| 开源社区 | VoltAgent awesome-agent-skills | GitHub | 1000+ 技能 | 强调真实工程团队使用的技能 |
| 开源社区 | obra/superpowers、itgoyo/awesome-agent-skills | GitHub | — | 高星 Coding 技能包 / 热门合集 |
| 国内大厂 | 字节扣子（Coze）技能商店 | coze.cn | 每用户最多启用 30 个第三方技能 | 内置交易机制，可上架收费技能；企业技能商店限团队尊享版/企业旗舰版 |
| 国内大厂 | 腾讯 SkillHub | skillhub.tencent.com | — | ClawHub 本土化镜像 |
| 国内大厂 | 阿里"虾小宝"Skill 市场 | 内置于 JVS Claw | — | 市场免费，调用消耗算力 |
| 国内大厂 | 智谱 AgentMore Skills 广场 | — | — | 官方严选 + Skill Hub + 开源社区三模块，零 Token 安装 |
| 国内大厂 | 美团 xia345 / 觅游 | — | xia345：20+ Agent、7000+ Skill；觅游：3000+ Agent、40,000+ Skill | Agent 生态导航 |

## 二、关键统计数字

- 截至 2026 年 1 月，全球公开可用的 Skills 已超过 6 万个，分布在 GitHub、专用市场和开发者社区。
- skills.sh 排行榜头部以 vercel-labs、mattpocock、heygen-com/hyperframes、anthropics、microsoft/azure-skills 等组织为主，前 20 名 8 周活跃均在 80 万以上。
- 2026-10-10 B 站 UP 主统计：约 370 万人安装过 Skill，第一名"找工具的工具"376.6 万，断层领先第二名 131.8 万。
- ClawHub 下载量前 1000 的 Skill 分为 6 大领域：API 信息打通 35%、研究解析 20%、开发者设施 15%、运维优化 15%、多媒体 10%、垂直场景 5%。

## 三、近期动态与风险

- 碎片化：2026-10-12 OpenClaw 发布 2026.10.1 版本，让 Agent 自行搜索已安装 Skill，缓解技能目录占用上下文的问题。
- 跨工具同步：社区约定 `~/.agents/skills/` 作为通用目录；Skills.sh VS Code 扩展支持扫描 Claude Code、Cursor、Codex、Gemini CLI、Trae 等 11 个 Agent 的技能目录。
- 安全：Koi Security 审计 ClawHub 上 2,857 个技能，发现 341 个恶意技能，其中 335 个借假依赖安装 macOS 窃密程序 Atomic Stealer。

## 四、热门技能示例

| Skill | 来源 | 功能 |
|---|---|---|
| find-skills | vercel-labs/skills | 技能发现工具，约 380 万活跃 |
| agent-browser | vercel-labs | 浏览器自动化，约 110 万 |
| improve-codebase-architecture | mattpocock/skills | 代码架构优化，约 110 万 |
| frontend-design | anthropics/skills | 前端设计，约 98 万 |
| UniversalCodeReviewer | ai-skills-hub | 跨语言代码审查，4.8k Star、28,500+ 激活 |
| skill-creator | Anthropic 官方 | 引导创建新 Skill 的元技能 |

## 五、说明

各平台统计口径不同（GitHub Star、安装量、激活次数、收录数），且部分聚合站含大量 AI 批量生成或重复技能，比较时应以同一口径为准。

## 参考来源

- 腾讯云开发者社区《Skills榜单》2026-01-29
- 实在智能《Skill市场有哪些？一份技术指南》2026-07-28
- 什么值得买《Skill越装越多，AI反而找不着了》2026-10-13
- 新浪财经《我分析了1000个skills，这是最推荐的30个》2026-02-25
- skills.sh 官网排行榜；Skills.sh VS Code 扩展页 2026-10-13
- 新浪《别只让AI聊天了，这10个技能让它学会"干活"和"交接"》2026-10-10
- 扣子官方文档：技能商店、技能概述、使用技能
- The Hacker News：341 Malicious ClawHub Skills
- GitHub VoltAgent/awesome-agent-skills
