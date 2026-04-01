# AI 项目月度巡检报告 — 2026 年 4 月

> 巡检日期：2026-04-01  
> 数据来源：GitHub API、GitHub Trending（周榜/日榜）、Hacker News Front Page、VentureBeat、TechCrunch  
> 注：本月 DuckDuckGo 搜索 API 受限，部分非 GitHub 项目依赖已有新闻快照和缓存信息判断。

---

## 总览

本期跟踪 **93 个项目**（含新增 4 月 1 日条目）。

| 状态 | 数量 | 趋势 |
|------|------|------|
| 🟢 活跃 | 79 | 绝大多数保持更新 |
| 🔴 已关停 | 1 | Sora App/API |
| 🟣 被收购 | 4 | InterPositive、Moltbook、Forethought、Promptfoo |
| 🟡 降温 | 5 | 详见下文 |
| ⚪ 事件 | 1 | Claude Code Source Leak |
| 🔵 不确定 | 3 | 信息不足 |

---

## 按领域分组详情

### 一、基础模型 / 平台

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **GPT-5.4** | 🟢 活跃 | OpenAI 完成 $1220 亿融资、估值 $8520 亿（HN 304 分）；产品线收缩（Sora 关停）但核心模型持续迭代 |
| **Dify** | 🟢 活跃 | 3000 万 Pre-A 后无重大新闻，但企业用量和开源社区持续活跃 |
| **OpenViking** | 🟢 活跃 | 上月热度后进入平稳期，需下月再验证留存 |
| **Qutwo** | 🟡 降温 | 量子+AI 叙事冷却，近一个月无重大进展报道 |
| **Xiaomi Hunter Alpha** | 🟡 降温 | 初始话题性消退后缺乏后续产品动态 |
| **Autoresearch** | 🟢 活跃 | 62,741 stars，Karpathy 持续维护，最后推送 3/26 |
| **Unsloth Studio** | 🟢 活跃 | 本地 AI 工作流持续吸引开发者 |
| **GLM-5-Turbo** | 🟢 活跃 | Z.ai 持续迭代 agent-oriented Turbo 系列 |
| **CompactifAI API** | 🟢 活跃 | 模型压缩赛道热度稳定 |
| **Ensu (Ente)** | 🟢 活跃 | 本地 LLM App，HN 320 分后关注度稳定 |
| **ARC-AGI-3** | 🟢 活跃 | 新基准已发布，研究社区持续讨论 |
| **vLLM-Omni** | 🟢 活跃 | 4,061 stars（+561 vs 上月），GitHub Trending Python 周榜 |
| **DeepSeek Engram** | 🟡 降温 | 4,198 stars 但最后推送停在 1/14，论文热度消退，代码无实质更新 |
| **Google TurboQuant** | 🟢 活跃 | 学术论文持续被引用 |
| **Microsoft VibeVoice** | 🟢 活跃 ⭐ | **本月最亮眼**：33,128 stars，本周 +8,327，日增 3,863；GitHub Trending 全榜+Python 榜双第一；五天突破 3.3 万 |
| **Voxtral TTS** | 🟢 活跃 | Mistral 开源 TTS 持续受关注 |
| **Supermemory** | 🟢 活跃 | 20,764 stars（+2,914），稳步增长 |
| **xMemory** | 🟢 活跃 | 学术阶段，方向正确 |
| **OpenAI $852B Funding** | 🟢 活跃 | 史上最大 AI 融资轮关闭，HN 304 分 |
| **Cohere Transcribe** | 🟢 活跃 | HN 153 分，Open ASR 榜首 |

### 二、AI 编程 / 开发工具

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **Cursor Automations** | 🟢 活跃 | Cursor 持续迭代，但无 3 月以来的重大新闻 |
| **Codex Security** | 🟢 活跃 | OpenAI 安全审计功能研究预览阶段 |
| **Claude Code Remote Control** | 🟢 活跃 | Anthropic 持续推进桌面/手机远程 |
| **Promptfoo** | 🟣 被收购 | 已被 OpenAI 收购，整合进行中 |
| **Claude Code Review** | 🟢 活跃 | PR 级审查功能扩展中 |
| **CLI-Anything** | 🟢 活跃 | 25,634 stars（从 ~10k 翻倍+），最后推送 3/30 |
| **Crawler.sh** | 🟢 活跃 | 桌面版持续迭代 |
| **Lightpanda** | 🟢 活跃 | headless browser 赛道稳定 |
| **GitNexus** | 🟢 活跃 | 代码图谱工具继续维护 |
| **InsForge** | 🟢 活跃 | 后端语义层工具 |
| **Claude-Mem** | 🟢 活跃 ⭐ | 44,082 stars（从 ~3.67 万增到 4.4 万），跨会话记忆需求爆发 |
| **Claude HUD** | 🟢 活跃 | 15,746 stars（从 ~454/天到稳定增长） |
| **Superpowers** | 🟢 活跃 ⭐ | **128,161 stars**，GitHub Trending 日榜持续出现；已成为 Claude Code 生态最大项目之一 |
| **everything-claude-code** | 🟢 活跃 ⭐ | **126,801 stars**（从 ~9.8 万增到 12.7 万），本周 +19,869；GitHub Trending 全榜 |
| **Open SWE** | 🟢 活跃 | LangChain 异步 coding agent 脚手架 |
| **Deep Agents** | 🟢 活跃 | 18,406 stars（从 ~1.28 万增到 1.84 万），LangChain 持续推进 |
| **Microsoft APM** | 🟢 活跃 | Agent 依赖管理方向 |
| **Context Hub** | 🟢 活跃 | 12,383 stars，Andrew Ng 背书稳定 |
| **Claude Plugins Official** | 🟢 活跃 | 插件生态扩展中 |
| **GitHub Spec-Kit** | 🟢 活跃 ⭐ | **84,135 stars**（从 ~初始到 8.4 万），Spec-Driven Development 被广泛采纳 |
| **Strix** | 🟢 活跃 | 22,925 stars（从初始快速增长），AI 渗透测试 |
| **oh-my-claudecode** | 🟢 活跃 ⭐ | 19,038 stars（从 ~14.6k 增到 19k），本周 +6,933，日增 1,126；多 agent 编排 Claude Code |
| **Claude Agent SDK Python** | 🟢 活跃 | 6,007 stars，Anthropic 官方 |
| **learn-claude-code** | 🟢 活跃 | 45,161 stars（从 ~42.6k 增），教程项目持续热度罕见 |
| **json-render** | 🟢 活跃 | 13,799 stars，Vercel Labs |
| **Agentation** | 🟢 活跃 | 3,251 stars，视觉反馈工具 |
| **claude-skills** | 🟢 活跃 | 8,399 stars，220+ 技能插件 |
| **claude-howto** | 🟢 活跃 ⭐ | **13,010 stars**（从 ~6.5k 翻倍），日增 2,390，GitHub Trending 日榜第一 |
| **OpenSpec** | 🟢 活跃 | 36,061 stars，规格驱动开发 |
| **claude-code-best-practice** | 🟢 活跃 | 28,642 stars，实践指南 |
| **Claude Subconscious** | 🟢 活跃 | 2,466 stars（+1,258/周），Letta 开源 |
| **Coasts** | 🟡 降温 | 仅 264 stars，多 agent 并行开发隔离环境，概念好但采纳率低 |
| **Claude Code Source Leak** | ⚪ 事件 | HN 1,881 分 + 921 评论；npm .map 文件泄露完整源码，揭示反蒸馏/undercover 模式 |

### 三、AI Agent / 自动化

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **Always On Memory Agent** | 🟢 活跃 | Google 开源记忆层 |
| **MiroFish** | 🟡 降温 | 47,017 stars 但最后推送停在 3/20，两周无更新 |
| **PageAgent** | 🟢 活跃 | 阿里 DOM agent |
| **Hermes Agent** | 🟢 活跃 ⭐ | 20,365 stars（突破 2 万），本周 +7,539，日增 1,907；NousResearch 社区活跃 |
| **Moltbook** | 🟣 被收购 | Meta 收购后无公开进展 |
| **DeerFlow 2.0** | 🟢 活跃 ⭐ | **55,257 stars**（从 ~54k 增），本周 +13,560；GitHub Trending 周榜第四；字节持续投入 |
| **The Agency** | 🟢 活跃 | 67,463 stars，多角色 agent 团队模板 |
| **Hindsight** | 🟢 活跃 | Agent 长期记忆 |
| **Deep Agents** | 🟢 活跃 | 同上 AI 编程分类 |
| **AgentMail** | 🟢 活跃 | Agent 邮箱身份基础设施 |
| **Nyne** | 🔵 不确定 | 种子轮后无后续报道 |
| **TradingAgents** | 🟢 活跃 | 45,194 stars（从 ~4 万增到 4.5 万），本周 +4,848 |
| **browser-use** | 🟢 活跃 | 85,341 stars，稳步增长 |
| **n8n-MCP** | 🟢 活跃 | 17,216 stars（从 ~1.6 万增到 1.72 万） |
| **Ruflo** | 🟢 活跃 | 28,989 stars（从 ~2.5 万增到 2.9 万） |
| **Crucix** | 🟢 活跃 | 8,084 stars，OSINT 工具 |
| **Project NOMAD** | 🟢 活跃 | 20,702 stars（从 ~1.52 万增到 2.07 万），本周 +6,272 |
| **Obsidian Skills** | 🟢 活跃 | 18,624 stars，kepano 开源 |
| **ClawBot (WeChat × OpenClaw)** | 🟢 活跃 | 腾讯微信 agent 接入 |
| **World AgentKit** | 🟢 活跃 | 真人授权验证 |
| **Dexter** | 🟢 活跃 | 20,676 stars（从 ~19.6k 增），金融研究 agent |
| **Cloudflare Dynamic Workers** | 🟢 活跃 | Agent 沙箱基础设施 |
| **RuView WiFi DensePose** | 🟢 活跃 | 44,955 stars（从初始爆发式增长），WiFi 人体检测 |
| **AgentScope** | 🟢 活跃 | 22,625 stars，阿里 agent 框架 |
| **Claude Mac Control + Dispatch** | 🟢 活跃 | Anthropic 桌面+手机控制 |
| **OpenSandbox** | 🟢 活跃 | 阿里 agent 沙箱 |

### 四、企业服务 / SaaS

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **DiligenceSquared** | 🔵 不确定 | 种子轮后无新报道 |
| **Agent 365** | 🟢 活跃 | 微软 agent 治理平台 GA |
| **Perplexity Computer for Enterprise** | 🟢 活跃 | 企业 agent 工作台 |
| **Claude Marketplace** | 🟢 活跃 | Anthropic 应用分发 |
| **Armadin** | 🟢 活跃 | $1.899 亿融资，自动化安全 agent |
| **Forethought** | 🟣 被收购 | Zendesk 收购后整合中 |
| **Legora** | 🟢 活跃 | $55 亿估值，法律 AI 平台 |
| **Wonderful** | 🟢 活跃 | $20 亿估值，多语言客服 agent |
| **Alibaba Qwen Enterprise Agent** | 🟢 活跃 | 阿里企业 agent 平台持续落地 |
| **MaxKB** | 🟢 活跃 | 企业知识库 agent |
| **Nvidia Agent Toolkit** | 🟢 活跃 | GTC 2026 发布后持续推进 |
| **Baidu DuClaw** | 🟢 活跃 | 百度多端 agent 生态 |
| **Rebar** | 🟢 活跃 | HVAC AI 估价 |
| **ElevenLabs × IBM** | 🟢 活跃 | 企业语音 AI 合作 |
| **OpenBB** | 🟢 活跃 ⭐ | **64,823 stars**（从 ~4.5 万飙升到 6.5 万），金融数据平台转型成功 |
| **Slack AI 30 Features** | 🟢 活跃 | Slackbot 30 个 AI 功能发布 |
| **TaxHacker** | 🟢 活跃 | 3,734 stars，自托管 AI 记账 |

### 五、多模态生成 / 创意工具

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **Luma Agents** | 🟢 活跃 | 多模态创意生成 |
| **InterPositive** | 🟣 被收购 | Netflix 收购后整合中 |
| **Picsart Agents** | 🟢 活跃 | AI agent marketplace |
| **Sora** | 🔴 已关停 | **2026 年最戏剧化的战略撤退**；OpenAI 关停 App/API，取消迪士尼合作 |
| **Runway Builders Fund** | 🟢 活跃 | Sora 退场后反向加注，$10M 基金 |
| **webnovel-writer** | 🟢 活跃 | 2,170 stars，网文 agent |

### 六、搜索 / 研究工具

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **OpenDataLoader PDF** | 🟢 活跃 | PDF 解析工具 |
| **Chandra OCR 2** | 🟢 活跃 | 8,103 stars（从 ~4k 翻倍），连续在 Trending |
| **last30days-skill** | 🟢 活跃 ⭐ | **16,890 stars**（从 ~5k 到 1.69 万），本周 +11,933；GitHub Trending Python 周榜第一 |
| **notebooklm-py** | 🟢 活跃 | NotebookLM Python API |

### 七、其他

| 项目 | 状态 | 变化摘要 |
|------|------|----------|
| **MiniMind 3** | 🟢 活跃 | 45,121 stars，教育项目持续增长 |
| **Rox AI** | 🟢 活跃 | 销售 agent，$12 亿估值 |

---

## 🔥 本月最值得继续跟踪的项目（Top 10）

1. **Microsoft VibeVoice** — 五天 3.3 万星，语音 AI 开源标杆，生态影响力巨大
2. **Superpowers** — 12.8 万星，已成 Claude Code 生态核心
3. **everything-claude-code** — 12.7 万星，agent harness 优化系统
4. **GitHub Spec-Kit** — 8.4 万星，Spec-Driven Development 正在被采纳
5. **DeerFlow 2.0** — 5.5 万星，字节 SuperAgent 持续吸引开发者
6. **OpenBB** — 6.5 万星，从终端工具成功转型为 AI-native 金融数据平台
7. **last30days-skill** — 1.69 万星/周增 1.2 万，agent skill 概念红利的代表
8. **Hermes Agent** — 突破 2 万星，NousResearch 长运行 agent 方向
9. **Claude-Mem** — 4.4 万星，跨会话记忆是 agent 刚需
10. **oh-my-claudecode** — 1.9 万星，多 agent 编排 Claude Code

## ⚠️ 掉队、消失或需警惕的项目

1. **Sora (OpenAI)** — 已关停。从发布到关停不到 6 个月，迪士尼合作从签约到取消不到 4 个月。AI 视频生成赛道的警示。
2. **DeepSeek Engram** — 代码最后推送停在 1/14，近三个月无更新。论文热度消退。
3. **MiroFish** — 47k stars 但最后推送停在 3/20，两周无更新。典型「一次性爆红后沉寂」。
4. **Coasts** — 仅 264 stars，概念超前但采纳率极低。
5. **Qutwo** — 量子+AI 叙事冷却，缺乏后续产品验证。
6. **Xiaomi Hunter Alpha** — 话题性消退后无实质产品动态。
7. **Nyne / DiligenceSquared** — 种子轮融资后信息断层，无法确认运营状态。

## 📊 关键趋势判断

### Claude Code 生态爆发
本月最显著的信号是围绕 Claude Code 的项目群爆发：
- Superpowers (128k)、everything-claude-code (127k)、learn-claude-code (45k)、Claude-Mem (44k)、claude-code-best-practice (29k)、oh-my-claudecode (19k)、claude-howto (13k)、claude-skills (8.4k)、Claude Agent SDK (6k)
- Claude Code 源码泄露（HN 1881 分）反而加速了社区理解和二次开发
- **判断**：Claude Code 正在成为 AI 编程的事实标准之一，生态锁定效应正在形成

### Agent 基础设施层开始分化
- 沙箱层：Cloudflare Dynamic Workers、OpenSandbox
- 记忆层：Supermemory、xMemory、Claude-Mem、Hindsight
- 编排层：DeerFlow、Ruflo、AgentScope、oh-my-claudecode
- 身份层：World AgentKit、AgentMail
- 治理层：Agent 365、Armadin
- **判断**：Agent 生态从「谁的 agent 最聪明」转向「谁的基础设施最可靠」

### 语音 AI 三方激战
- Microsoft VibeVoice（开源，3.3 万星）
- Mistral Voxtral TTS（开源权重，正面挑战 ElevenLabs）
- Cohere Transcribe（Open ASR 榜首）
- ElevenLabs × IBM（企业合作）
- **判断**：语音 AI 已从「demo 好不好听」进入「谁能进入生产部署」

### OpenAI 战略收缩
- 关停 Sora（$10 亿迪士尼合作也放弃）
- 完成 $1220 亿融资（估值 $8520 亿）
- IPO 压力下聚焦核心：模型、API、安全
- **判断**：OpenAI 正在从「什么都做」收缩为「只做平台层」

---

*报告由 kuma 自动生成 | 2026-04-01 09:00 CST*
