# AI 项目月度巡检报告 — 2026 年 5 月

> 巡检日期：2026-05-01  
> 数据来源：GitHub Trending（日榜/周榜/Python 榜）、项目仓库、行业新闻  
> 覆盖项目数：150+  
> 本月搜索引擎（DuckDuckGo）受限，以 GitHub 实时数据和已有跟踪记录为主要依据

---

## 一、本月关键变化摘要

### 🔥 最重大事件

1. **Anthropic 信任危机持续恶化**（第六~第九击）
   - Cache TTL 降级 → 封杀第三方 → 源码泄露 → Pro 移除 Claude Code → 质量事故复盘 → 4/28 全面宕机 → HERMES.md 计费 Bug → OpenClaw 歧视性封杀
   - `free-claude-code` 周增 14,666 stars 达 19,190，成为本周 GitHub 全榜热度最高项目之一
   - 直接催化开发者向 DeepSeek/GPT-5.5/开源方案迁移

2. **DeepSeek V4 发布**（4/25）—— 开源前沿模型新标杆
   - V4-Pro 1.6T/49B active + V4-Flash 284B/13B active，1M 上下文
   - HN 1779 分（本月最高），OpenAI/Anthropic API 兼容

3. **GPT-5.5 发布并开放 API**（4/24~25）
   - Terminal-Bench 2.0 82.7%，FrontierMath Tier 4 35.4%
   - GPT-5.4 降为次旗舰，发布间隔仅约 5 周

4. **Warp 开源**（4/29）—— 终端+Agent 开发环境
   - GitHub 全榜连续三天第一，43,496+ stars
   - OpenAI 赞助，Oz agent 编排平台

5. **SpaceX 600 亿美元收购 Cursor**（4/22 Bloomberg 报道）
   - AI 工具领域史上最大收购
   - 引发中立性争议

6. **Microsoft × OpenAI 结束独家协议**（4/28）
   - OpenAI 可多云分发，Microsoft 加速自研 MAI

7. **PyTorch Lightning 供应链攻击**（5/1）
   - 恶意代码植入 lightning 2.6.2/2.6.3
   - 跨 PyPI/npm 蠕虫传播，影响所有 AI 训练环境

---

## 二、按领域分组项目状态

### 基础模型 / 平台

| 项目 | 状态 | 判断依据 |
|------|------|----------|
| GPT-5.5 | 🟢 活跃 | 发布即开放 API，Terminal-Bench 登顶 |
| GPT-5.4 | 🟡 降温 | 被 5.5 取代为次旗舰 |
| DeepSeek V4 | 🟢 活跃 | HN 最高分，开源 SOTA |
| DeepSeek Engram | 🔴 停止更新 | 最后推送停在 1/14，三个月无代码更新 |
| Kimi K2.6 | 🟢 活跃 | Apache 2.0 开源，编码基准追平闭源 |
| Qwen 3.6-Plus/27B/Max | 🟢 活跃 | 三个变体全线覆盖，持续迭代 |
| Claude Opus 4.7 | 🟢 活跃 | 编码提升 13%，但信任危机影响口碑 |
| GLM-5.1 / GLM-5-Turbo | 🟢 活跃 | 智谱持续发力 agent 场景 |
| Gemma 4 | 🟢 活跃 | MedGemma/ShieldGemma 专业变体 |
| Meta Muse Spark | 🟡 降温 | 概念大于产品，闭源策略与 Meta 开源叙事矛盾 |
| Dify | 🟢 活跃 | Pre-A 融资后稳步推进 |
| Onyx | 🟢 活跃 | v3.0 GitHub Trending，21.8k stars |
| Supermemory | 🟢 活跃 | 20.7k stars，稳步增长 |
| MemPalace | 🟡 不确定 | 9 天 4.3 万星增速异常，需观察假星风险 |
| vLLM-Omni | 🟢 活跃 | 4,061 stars，持续增长 |
| CompactifAI API | 🟡 不确定 | 近一个月无重大公开动态 |
| OpenViking | 🟡 不确定 | 初始热度后缺乏后续报道 |
| Xiaomi Hunter Alpha | 🔴 降温 | 话题性消退后无后续产品动态 |
| Qutwo | 🔴 降温 | 量子+AI 叙事冷却 |
| Ensu (Ente) | 🟢 活跃 | 本地 AI 赛道持续受关注 |
| Apfel | 🟢 活跃 | macOS 本地 LLM 解锁方案 |
| Google TimesFM 2.5 | 🟢 活跃 | BigQuery 集成说明不是实验项目 |
| Voxtral TTS | 🟢 活跃 | Mistral 企业全栈 |
| Microsoft VibeVoice | 🟢 活跃 | 45,659→46,082 stars，GitHub Trending 持续 |
| VoxCPM2 | 🟢 活跃 | 12,279 stars，语音 AI 开源热 |
| NeuTTS | 🟢 活跃 | 端侧 TTS 新玩家 |
| Cohere Transcribe | 🟢 活跃 | HF Leaderboard 第一 |
| NVIDIA PersonaPlex | 🟢 活跃 | 人格可控对话 |
| Microsoft Agent Lightning | 🟢 活跃 | Agent RL 训练基础设施 |
| Kronos | 🟡 不确定 | K 线预测学术有价值但实盘高度存疑 |
| xMemory / TrustGraph | 🟢 活跃 | Agent 记忆/上下文层持续受关注 |
| DeepSeek DeepEP | 🟢 活跃 | V4 次日开源核心通信库 |
| Google TurboQuant | 🟢 活跃 | 理论突破级工作 |
| Thunderbolt (Mozilla) | 🟡 降温 | 1,537 stars，赛道拥挤 |

### AI 编程 / 开发工具

| 项目 | 状态 | 判断依据 |
|------|------|----------|
| Warp Open Source | 🟢 活跃 | 43,496+ stars，GitHub 全榜连续三天第一 |
| Cursor 3.0 | ⚫ 被收购（待完成） | SpaceX 600 亿美元 |
| free-claude-code | 🟢 活跃 | 19,190 stars，周增 14,666，Anthropic 信任危机受益者 |
| Superpowers | 🟢 活跃 | 128k+ stars，GitHub Trending 日榜持续出现 |
| everything-claude-code | 🟢 活跃 | 126,801 stars，跨 harness 生态扩张 |
| Matt Pocock Skills | 🟢 活跃 | 49,494 stars，周增 30,945（本周全榜第二） |
| GitHub Spec-Kit | 🟢 活跃 | 84,135 stars，Spec-Driven Development 被广泛采纳 |
| Claude-Mem | 🟢 活跃 | 63,291 stars，agent 记忆刚需 |
| GitNexus | 🟢 活跃 | 32,602 stars，代码知识图谱 |
| Andrej Karpathy Skills | 🟢 活跃 | 71,863 stars，品类引爆者 |
| learn-claude-code | 🟢 活跃 | 45,161 stars |
| claude-code-best-practice | 🟢 活跃 | 28,642 stars |
| oh-my-claudecode | 🟢 活跃 | 23,109 stars |
| oh-my-codex | 🟢 活跃 | 14,050 stars |
| Strix (安全测试) | 🟢 活跃 | 22,925 stars |
| Claude HUD | 🟢 活跃 | 15,746 stars |
| Context Hub | 🟢 活跃 | 12,383 stars |
| Archon | 🟢 活跃 | 15,563 stars，YAML 工作流 |
| Claude Agent SDK Python | 🟢 活跃 | 6,007 stars，Anthropic 官方 |
| Get Shit Done (GSD) | 🟢 活跃 | 52,066 stars |
| HuggingFace ml-intern | 🟢 活跃 | 7,701 stars，HF 官方，周增 5,665 |
| Zed Parallel Agents | 🟢 活跃 | Zed 1.0 正式版发布 |
| Vercel Skills CLI | 🟢 活跃 | 15,448 stars |
| context-mode | 🟢 活跃 | 9,401 stars |
| Craft Agents OSS | 🟢 活跃 | 5,574 stars，GitHub 日榜 |
| jcode | 🟢 活跃 | 1,886 stars，Rust 极致资源效率 |
| Dirac | 🟢 活跃 | TerminalBench 2.0 登顶 |
| Codex Everything Update | 🟢 活跃 | 后台电脑控制+90+ 插件 |
| Cursor Automations | 🟡 不确定 | 收购影响待评估 |
| Claude Code Review | 🟡 不确定 | 信任危机影响 |
| Coasts | 🔴 降温 | 仅 264 stars，采纳率低 |
| Claude Subconscious | 🟡 降温 | 2,466 stars，面临 Anthropic 内置替代风险 |

### AI Agent / 自动化

| 项目 | 状态 | 判断依据 |
|------|------|----------|
| Hermes Agent | 🟢 活跃 | 108,034 stars，自进化 Agent 工程化 |
| The Agency | 🟢 活跃 | 67,463 stars |
| TradingAgents | 🟢 活跃 | 57,756 stars，GitHub Python 日榜第一 |
| browser-use | 🟢 活跃 | 85,341 stars |
| DeerFlow 2.0 | 🟢 活跃 | 55,257 stars，字节持续投入 |
| Claude Mac Control + Dispatch | 🟢 活跃 | Windows 扩展大幅扩大覆盖 |
| Obsidian Skills | 🟢 活跃 | 18,624 stars |
| n8n-MCP | 🟢 活跃 | 17,216 stars |
| Ruflo | 🟢 活跃 | 28,989 stars |
| GenericAgent | 🟢 活跃 | 8,482 stars，周增 2,350（本周周榜） |
| Multica | 🟢 活跃 | 16,739 stars |
| CUA | 🟢 活跃 | 15,404 stars，周增 1,842 |
| Cloudflare Dynamic Workers | 🟢 活跃 | Agent 基础设施三层布局完成 |
| AgentScope | 🟢 活跃 | 22,625 stars |
| Block Goose | 🟢 活跃 | 37,466 stars |
| Beads | 🟢 活跃 | Steve Yegge 项目 |
| CrabTrap | 🟢 活跃 | Agent 安全代理层 |
| Agent Vault | 🟢 活跃 | 凭证代理基础设施 |
| Memori | 🟢 活跃 | Agent 行为记忆 |
| MiroFish | 🔴 降温 | 最后推送停在 3/20，两月无更新，GitHub 仓库疑似 404 |
| Dexter | 🟡 不确定 | 20,676 stars 但增长放缓 |
| Nyne | 🔴 不确定 | 种子轮后信息断层 |
| OpenSandbox | 🟡 不确定 | 近一个月无重大更新 |
| Moltbook | ⚫ 被收购 | Meta 收购后无独立更新 |
| WorldMonitor | 🟡 不确定 | 50k stars 增速异常，假星风险 |
| RuView WiFi DensePose | 🟡 不确定 | 44,955 stars 但应用场景窄 |

### 企业服务 / SaaS

| 项目 | 状态 | 判断依据 |
|------|------|----------|
| OpenBB | 🟢 活跃 | 64,823 stars，成功转型 AI-native 金融数据平台 |
| Slack AI 30 Features | 🟢 活跃 | 企业 AI 渗透加速标志 |
| Salesforce Headless 360 | 🟢 活跃 | 企业从 GUI→Agent API 不可逆 |
| OpenAI Workspace Agents | 🟢 活跃 | 研究预览 |
| Intuit Intelligence | 🟢 活跃 | 85% 复用率验证 AI-HI 模式 |
| FinceptTerminal | 🟢 活跃 | 18,320 stars，周增 4,505 |
| Cloudflare AI Crawl Control | 🟢 活跃 | AI 数据海关角色 |
| ChatGPT for Excel | 🟢 活跃 | AI 嵌入办公工具 |
| Agent 365 | 🟢 活跃 | 微软 Agent 治理 |
| DiligenceSquared | 🔴 不确定 | 种子轮后无后续公开报道 |
| Forethought | ⚫ 被收购 | Zendesk 完成整合 |
| InterPositive | ⚫ 被收购 | Netflix 收购 |

### 多模态生成 / 创意工具

| 项目 | 状态 | 判断依据 |
|------|------|----------|
| ChatGPT Images 2.0 | 🟢 活跃 | OpenAI 正式推出 |
| Claude Design | 🟢 活跃 | HN 777 分 |
| Pixelle-Video | 🟢 活跃 | 8,429 stars，周增 2,064 |
| Open-Generative-AI | 🟢 活跃 | 10,422 stars，周增 3,799 |
| CorridorKey | 🟢 活跃 | 12,589 stars，影视后期开源工具 |
| Voicebox | 🟢 活跃 | 16,264 stars |
| Sora | ⚫ 已关停 | OpenAI 3 月宣布关停 |
| Runway Builders Fund | 🟡 不确定 | 生态投资非产品 |

### AI 安全

| 项目 | 状态 | 判断依据 |
|------|------|----------|
| Project Glasswing | 🟢 活跃 | 12 家公司联合发起 |
| OpenAI Privacy Filter | 🟢 活跃 | 基础设施级组件 |
| Shannon (渗透测试) | 🟢 活跃 | 36,463 stars |
| Heretic (去审查) | 🟡 争议 | 证明安全对齐脆弱 |
| PyTorch Lightning 供应链攻击 | ⚠️ 事件 | 恶意代码植入 |
| Claude Code OpenClaw 歧视 | ⚠️ 事件 | 今日爆发 |

### 行业动态

| 事件 | 影响 |
|------|------|
| SpaceX $60B 收购 Cursor | AI 工具史上最大收购 |
| Microsoft × OpenAI 结束独家 | 合作六年后最大结构性变化 |
| Google $40B 投资 Anthropic | 史上最大单笔 AI 投资 |
| OpenAI $122B 融资 | 史上最大 AI 融资轮 |
| GitHub 假星经济 | 600 万假星动摇开源信任 |
| SWE-bench Verified 退役 | AI 最重要编码基准正式退役 |
| China 阻止 Meta 收购 Manus | AI 跨国并购地缘合规 |
| GitHub Copilot 按量计费 | 影响数百万开发者预算 |

---

## 三、本月最值得继续跟踪的项目

### 🏆 S 级（行业格局级）

1. **DeepSeek V4** — 开源前沿模型标杆，API 兼容性好，直接影响闭源模型定价策略
2. **Warp Open Source** — AI-native 终端+Agent 环境，OpenAI 赞助，43k+ stars
3. **GPT-5.5** — Terminal-Bench 登顶，API 已开放，模型迭代速度惊人
4. **Anthropic 信任危机** — 九连击持续发酵，free-claude-code 和 ds2api 是直接反映
5. **Microsoft × OpenAI 协议重构** — 多云分发开启新格局

### 🥇 A 级（赛道定义级）

6. **Matt Pocock Skills** — Agent Skills 品类增速最快（周增 30k+）
7. **Superpowers** — 128k stars，Claude Code 生态最大项目
8. **CUA** — 计算机操控 Agent 基建层
9. **GenericAgent** — 自进化 agent 技能树方向
10. **HuggingFace ml-intern** — ML 全链路自动化
11. **Cloudflare Agent 基础设施** — Dynamic Workers + AI Platform + Artifacts + Email Service 四层布局
12. **Zed 1.0** — IDE 内多 Agent 并行编码

### 🥈 B 级（重要跟踪）

13. Kimi K2.6 — 开源编码模型追平闭源
14. Qwen 3.6 系列 — 全线覆盖
15. FinceptTerminal — 开源 Bloomberg 替代
16. OpenBB — 金融数据平台转型成功
17. Dirac — coding agent 上下文管理创新
18. Agent Vault / CrabTrap — Agent 安全基建

---

## 四、已明显掉队或消失的项目

### ❌ 已关停/退场
- **Sora** — OpenAI 宣布关停，算力转向机器人和 AGI
- **SWE-bench Verified** — 正式退役，59.4% 审计样本有缺陷测试

### 📉 明显掉队/停滞
- **MiroFish** — GitHub 仓库疑似已删除（404），最后推送 3/20，典型一次性爆红后消失
- **DeepSeek Engram** — 最后代码推送 1/14，三个月无更新，论文热度完全消退
- **Xiaomi Hunter Alpha** — 初始话题性消退后零后续动态
- **Qutwo** — 量子+AI 叙事冷却，无实质产品进展
- **Coasts** — 仅 264 stars，多 agent 并行隔离环境概念好但无人采纳
- **DiligenceSquared** — 种子轮后完全信息断层
- **Nyne** — 种子轮融资后信息断层

### ⚠️ 假星/增速异常需警惕
- **WorldMonitor** — 50k stars 增速异常
- **MemPalace** — 9 天 4.3 万星，AAAK 压缩层被社区纠正为误导
- 多个 Agent Skills 类仓库增速超出正常范围（CMU 研究发现 600 万假星）

---

## 五、批判性观察

### 1. Agent Skills 品类爆发但护城河近零
本月 GitHub 上 Agent Skills 类仓库爆发（Matt Pocock Skills 周增 30k、Karpathy Skills 72k、Addy Osmani 等），但本质都是 system prompt engineering，技术壁垒极低。这更像是「.claude 目录」文化运动而非持久产品品类。

### 2. Anthropic 信任危机是真实的
从 Cache TTL 降级到 OpenClaw 歧视性封杀，九连击不是偶发事故而是系统性问题。free-claude-code 两周飙到 19k stars、HN「I cancelled Claude」734 分，这是用户用脚投票。Google $40B 投资可能缓解容量问题但无法修复信任。

### 3. 模型迭代速度超出预期
GPT-5.4 → 5.5 间隔约 5 周、DeepSeek V3 → V4 间隔数月、Qwen 3.6 三变体密集发布——模型层正在加速商品化，真正的竞争壁垒在 Agent 运行时和生态锁定。

### 4. GitHub 假星问题严重
CMU ICSE 2026 论文发现 600 万假星、18,617 仓库参与。AI/LLM 是最大非恶意类别。本报告中多个高星项目增速异常（WorldMonitor 50k、MemPalace 4.3 万/9 天），星数不再是可靠的项目质量指标。

### 5. Agent 安全基建加速成型
CrabTrap（Brex）、Agent Vault（Infisical）、OpenAI Privacy Filter、Project Glasswing——生产级 Agent 安全基建从概念走向开源产品。AI Agent 删库事件是最好的催化剂。

---

## 六、数据说明

- 本月 DuckDuckGo 搜索引擎被限流，部分项目依赖上月数据+GitHub 实时 Trending 交叉验证
- 星数增长数据来自 GitHub Trending 日/周榜实际抓取（2026-05-01）
- 未能逐一验证所有 150+ 项目官网，对标记为「不确定」的项目建议下月重点核查

---

*报告生成工具：OpenClaw AI Tracker*  
*下次巡检：2026-06-01*
