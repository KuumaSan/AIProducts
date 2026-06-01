# AI 项目月度巡检报告：2026 年 5 月回顾

> 巡检日期：2026-06-01 | 巡检器：kuma | 数据源：tracking/ai-projects.csv
> 覆盖项目总数：500 | 5 月新增项目：~191 | 5 月活跃事件：~29

---

## 一、5 月总览

2026 年 5 月是 AI 行业 **产品化加速+信任危机持续+公众反弹初现** 的月份。

**三大关键趋势：**
1. **基础模型混战白热化**：Claude Opus 4.8、GPT-5.5 系列持续迭代、Gemini 3.5 Flash（Google I/O）、DeepSeek V4 持续领先、Qwen 3.7-Max、Kimi K2.6、Cohere Command A+ 开源旗舰——六大阵营同时推新。
2. **Agent Skills 生态爆发**：从社区自发走向平台标准化（OpenAI Skills、HuggingFace Skills、Flutter 官方 Skills、.NET 官方 Skills、Vercel Skills CLI），品类从编码扩展到安全、营销、学术、设计。
3. **公众反 AI 情绪集中爆发**：HN "Tired of AI" 1961 分、Chrome 静默安装 Gemini Nano 1198 分、DuckDuckGo 搜索量暴涨、VS Code Copilot 强制署名——标志着 AI 从全民欢迎进入选择性抵制阶段。

---

## 二、按领域分组详评

### 🔧 AI 编程 / 开发工具（104 项，本月最活跃领域）

| 项目 | 状态 | 5 月动态 |
|------|------|----------|
| **Claude Opus 4.8** | ✅ 活跃 | 5/28 正式发布，SWE-bench Pro 69.2%，GDPval Elo 1890 超 GPT-5.5，Dynamic Workflows，Fast 模式成本降 1/3 |
| **GPT-5.5** | ✅ 活跃 | DeepSWE 基准 70%，Rosalind 生物安全扩展，Gartner 命名企业编码 Agent 领导者 |
| **Codex Everything Update** | ✅ 活跃 | 300 万周活，后台电脑控制+内置浏览器+90+ 插件+Memory 预览 |
| **Zed 1.0** | ✅ 活跃 | 4/29 发布 1.0 正式版，HN 1421 分，DeltaDB CRDT 同步引擎 |
| **OpenAI Symphony** | ✅ 活跃 | Elixir 实现，对接 Linear 看板自动调度 Codex agent，22.9K stars |
| **Warp 开源** | ✅ 活跃 | 连续三天 GitHub 全榜第一，43.5K+ stars，OpenAI 赞助 |
| **Understand-Anything** | ✅ 活跃 | 47K+ stars，代码理解层品类持续验证 |
| **CodeGraph** | ✅ 活跃 | 35K+ stars，减少 92% 工具调用 |
| **free-claude-code** | ✅ 活跃 | 19K+ stars，Anthropic 信任危机最大受益者 |
| **DeepSeek Reasonix** | ✅ 活跃 | 99.82% 缓存命中率，$12 跑 435M tokens |
| **ECC** | ✅ 活跃 | 200K+ stars，everything-claude-code 演进为跨平台增强系统 |
| **Cursor Plugins** | ✅ 活跃 | SpaceX 收购待完成期间持续推进插件生态 |
| **herdr** | ✅ 活跃 | Rust 编写多 agent 会话管理终端 |
| **oh-my-pi** | ✅ 活跃 | hash-anchored 编辑+LSP 深度集成 |
| **Compound Engineering** | ✅ 活跃 | 17.7K stars，80% 规划 20% 执行方法论插件 |

**编程工具关键判断：**
- Agent Skills 标准化是 5 月最重要的结构性变化，平台方（OpenAI、Google、Microsoft .NET、Flutter）开始主导
- 假星问题严重：ECC 200K+ stars、garrytan/gstack 96K、taste-skill 30K 等项目增速异常
- Anthropic 信任危机催生大量替代工具（free-claude-code、9router、DeepClaude 等）

### 🤖 AI Agent / 自动化（84 项）

| 项目 | 状态 | 5 月动态 |
|------|------|----------|
| **Hermes Agent** | ✅ 活跃 | 108K stars，自进化 Agent 工程化推进 |
| **OpenHuman** | ✅ 活跃（⚠️ 假星风险） | 23.5K stars 周增 17.8K，个人全量上下文管理 |
| **CloakBrowser** | ✅ 活跃（⚠️ 道德灰区） | 连续两周 GitHub 周榜第一，15K+ stars，源码级隐身浏览器 |
| **Gemini Spark** | ✅ 活跃 | Google I/O 发布个人常驻 Agent |
| **Claude MCP Tunnels** | ✅ 活跃 | 企业 Agent 数据不出域方案公测 |
| **Cloudflare × Stripe Agent Projects** | ✅ 活跃 | Agent 成为云平台一等公民客户 |
| **UI-TARS-desktop** | ✅ 活跃 | 字节开源 32K stars，桌面/浏览器操控 Agent |
| **Sim Studio** | ✅ 活跃 | 28K stars，画布式 Agent 编排 |
| **12-factor-agents** | ✅ 活跃 | 22K stars，生产级 Agent 方法论指南 |
| **Anthropic Conway/Orbit/Memory Files** | 🔜 未发布 | 代码泄露暴露常驻 Agent+主动推送+文件式记忆产品矩阵 |

**Agent 关键判断：**
- 企业 Agent 治理成为刚需：Microsoft Agent Governance Toolkit、NVIDIA Verified Agent Skills、RAMPART
- Agent 记忆赛道极度拥挤（9+ 项目上榜），MemPalace/AgentMemory/Memori/YourMemory/Honcho/δ-mem 等互相竞争
- Agent 删库事件（4/27）加速安全基建采纳

### 🧠 基础模型 / 平台（75 项）

| 项目 | 状态 | 5 月动态 |
|------|------|----------|
| **DeepSeek V4** | ✅ 活跃 | V4-Pro 开源 SOTA，V4-Flash $0.14/$0.28，1M 上下文 |
| **GPT-5.5 / 5.5 Instant** | ✅ 活跃 | Terminal-Bench 82.7%，幻觉减 52.5%，已替代 5.3 为默认 |
| **Gemini 3.5 Flash** | ✅ 活跃 | Google I/O Day 1 主角，4x 输出速度，Terminal-Bench 76.2% |
| **Gemini 3.1 Ultra** | ✅ 活跃 | 2M token 上下文旗舰 |
| **Qwen 3.7-Max** | ✅ 活跃 | 非幻觉率 SOTA，Agent 工具调用优化 |
| **Kimi K2.6** | ✅ 活跃 | Apache 2.0 开源，Terminal-Bench/SWE-Bench Pro 全面领先 |
| **Cohere Command A+** | ✅ 活跃 | 首个完全 Apache 2.0 开源旗舰 218B/25B MoE |
| **LFM2.5-8B-A1B** | ✅ 活跃 | 8B/1B active MoE，边缘推理非幻觉率碾压同级 |
| **Onyx v3.0** | ✅ 活跃 | 21.8K stars 企业私有 AI 平台 |

**基础模型关键判断：**
- 开源模型追平闭源旗舰是 5 月最重要信号（DeepSeek V4 Pro、Kimi K2.6、Cohere Command A+）
- 边缘推理成新战场：LFM2.5 系列、Needle 26M、Bonsai Image 4B
- 语音 AI 赛道 5 月极度拥挤：Pocket TTS、Supertonic 3、MOSS-TTS、OpenAI Realtime Voice 同月发布

### 🏢 企业服务 / SaaS（35 项）

| 项目 | 状态 | 5 月动态 |
|------|------|----------|
| **Claude for Small Business** | ✅ 活跃 | 15 个预置 Agent 工作流，免费公益定位 |
| **Anthropic Enterprise AI Services JV** | ✅ 活跃 | 与 Blackstone/GS 成立合资公司估值 15 亿 |
| **IBM watsonx Orchestrate** | ✅ 活跃 | Think 2026 多 Agent 控制平面+IBM Bob GA |
| **Google Managed Agents API** | ✅ 活跃 | 一个 API 部署完整 Agent |
| **Claude Platform on AWS** | ✅ 活跃 | GA，打破 Bedrock 功能滞后限制 |
| **FinceptTerminal** | ✅ 活跃 | 18.3K stars，开源 Bloomberg 替代 |
| **Salesforce Headless 360** | ✅ 活跃 | 100+ 新工具，企业 CRM 转向 Agent API |

### 🎨 多模态生成 / 创意工具（26 项）

| 项目 | 状态 | 5 月动态 |
|------|------|----------|
| **Claude Design** | ✅ 活跃 | HN 777 分，AI 设计工具新赛道 |
| **SANA-WM** | ✅ 活跃 | NVIDIA 开源 2.6B 参数视频世界模型 |
| **MoneyPrinterTurbo** | ✅ 活跃 | 74K+ stars，DeepSeek V4 催化新用户涌入 |
| **CorridorKey** | ✅ 活跃 | 12.5K stars 绿幕抠像 AI |
| **Gemini Omni** | ✅ 活跃 | 对话式视频编辑+物理仿真 |
| **Sora** | ❌ 已关停 | 持续关停，迪士尼合作取消 |

### 🔒 AI 安全 / 事件（合并安全相关 ~30 项）

**5 月安全大事记：**
- **PyTorch Lightning 供应链攻击**（5/1）：跨 PyPI/npm 蠕虫传播，影响所有 AI 训练环境
- **Anthropic 信任危机持续**：Claude Code OpenClaw 歧视（5/1）、HERMES.md bug（4/30）
- **GitHub VSCode 扩展入侵 3800 仓库**（5/21）
- **Microsoft Copilot Cowork 文件外泄**（5/26）：Agent 架构级安全缺陷
- **CTF 竞赛死亡宣告**（5/17）：GPT-5.5 Pro 一键解 Insane 级题目
- **Anthropic NLA 突破**（5/9）：发现模型知道自己在被测试
- **YouTube AI 自动标注上线**（5/29）：视频平台首次大规模部署 AI 内容检测

**新兴安全工具：**
- Microsoft RAMPART（pytest 原生 Agent 安全测试）
- Perplexity Bumblebee（供应链安全扫描）
- Anthropic-Cybersecurity-Skills（754 项安全技能，12.9K stars）

### 📰 行业动态 / 并购

| 事件 | 日期 | 影响 |
|------|------|------|
| Anthropic 首次盈利 | 5/23 | Q2 营收 $10.9B，经营利润 $559M，比预期提前两年 |
| OpenAI 秘密递交 IPO | 5/23 | 目标估值 $1T+，9 亿周活 $25B ARR |
| Karpathy 加入 Anthropic | 5/20 | HN 1104 分，前 Tesla AI 总监/OpenAI 联合创始人 |
| Anthropic 收购 Stainless | 5/19 | Agent 连接层基建自建，MCP 工具链闭环 |
| Mistral 收购 Emmi AI | 5/20 | 进军 Physics AI 工业工程 |
| Anthropic 估值超 OpenAI | 6/1 | 成为全球最有价值 AI 创业公司 |
| OpenRouter $1.13 亿 B 轮 | 6/1 | AI 模型路由中间层获资本验证 |
| SpaceX 收购 Cursor | 4/22→5 月持续 | 600 亿美元，AI 工具史上最大交易 |

### 🗣️ 语音 AI（5 月高密度赛道）

5 月同时活跃的语音 AI 项目超过 10 个：
- **OpenAI Realtime Voice API**：GPT-5 级推理语音 Agent，$32/$64 per M tokens
- **Pocket TTS**（Kyutai Labs）：CPU-only 100M 参数，6 语种
- **Supertonic 3**（HYBE Supertone）：31 语种 ONNX 端侧
- **MOSS-TTS**（复旦 OpenMOSS）：v1.5+SoundEffect v2.0 双版本
- **VoxCPM2**（OpenBMB）：30 语种无 tokenizer TTS

### 🖥️ Google I/O 2026（5/19-20）

5 月最重要的平台级事件：
- **Gemini 3.5 Flash**：Agent 工作流旗舰，4x 速度
- **Gemini Spark**：个人常驻 Agent
- **Googlebook + Magic Pointer**：AI 原生笔记本取代 Chromebook
- **Antigravity 2.0**：Agent 开发平台
- **Managed Agents API**：一键部署
- **Gemini Omni**：多模态视频编辑

---

## 三、5 月掉队或消失的项目

| 项目 | 状态 | 说明 |
|------|------|------|
| **MiroFish** | ❌ 停止更新 | GitHub 仓库 404，典型一次性爆红后消失 |
| **DeepSeek Engram** | ❌ 停止更新 | 4198 stars 但最后推送停在 1/14，三个月无代码更新 |
| **Sora** | ❌ 已关停 | 2026 年最戏剧化的战略撤退 |
| **GPT-5.4** | ⬇️ 降温 | 被 GPT-5.5 取代为次旗舰 |
| **Xiaomi Hunter Alpha** | ⬇️ 降温 | 初始话题性消退后零产品动态 |
| **Qutwo** | ⬇️ 降温 | 量子+AI 叙事冷却 |
| **Coasts** | ⬇️ 降温 | 仅 264 stars，概念好但采纳率极低 |
| **DiligenceSquared** | ❓ 不确定 | 种子轮后无后续公开报道 |
| **Nyne** | ❓ 不确定 | 种子轮融资后信息断层 |

---

## 四、假星风险标记

5 月 GitHub 假星问题进一步恶化（CMU 论文发现 600 万假星）。以下项目增速异常需持续观察：

| 项目 | Stars | 异常信号 |
|------|-------|----------|
| ECC | 200K+ | 单月增长极端 |
| garrytan/gstack | 96K | 个人品牌效应放大 |
| MoneyPrinterTurbo | 74K+ | 5 月底突然回潮 |
| Matt Pocock Skills | 57K | 周增 35K |
| Understand-Anything | 47K+ | 周增 22K |
| taste-skill | 30K+ | 周增 10K+，护城河接近零 |
| OpenHuman | 23.5K | 周增 17.8K |
| Ruflo | 47.7K | 单人核心维护 |
| TradingAgents | 72.5K | 增速异常 |

---

## 五、最值得继续跟踪的项目

### 🏆 S 级（持续证明产品-市场匹配）
1. **DeepSeek V4**——开源 SOTA 持续领先，定价颠覆，1M 上下文标配
2. **Claude Opus 4.8**——信任危机修复关键版本，Dynamic Workflows 是差异化
3. **GPT-5.5**——Terminal-Bench 领先，但定价压力大
4. **Gemini 3.5 Flash**——速度×能力×成本三角最优解
5. **Kimi K2.6**——Apache 2.0 开源编码模型持续霸榜

### 🥇 A 级（赛道领先或方向正确）
6. **Agent Skills 标准化生态**（OpenAI/HuggingFace/Vercel/Flutter/dotnet Skills）
7. **Anthropic Finance Agents**——模板化金融 Agent 交付
8. **Cohere Command A+**——首个完全 Apache 2.0 开源旗舰
9. **CodeGraph**——代码知识图谱实测有效
10. **Warp 开源**——Agent 原生终端
11. **Cloudflare Agent 基建三层**（Dynamic Workers + AI Platform + Email Service）
12. **Microsoft Agent Governance Toolkit**——OWASP Agentic Top 10 全覆盖

### 🥈 B 级（值得观察但需要更多验证）
13. **Anthropic Conway/Orbit/Memory Files**——常驻 Agent 产品矩阵，但尚未发布
14. **Googlebook + Magic Pointer**——AI 原生硬件，秋季出货
15. **OpenAI Realtime Voice API**——语音 Agent 最完整平台，但定价偏高
16. **LiteParser**——LlamaIndex 出品 Rust 文档解析器
17. **GLM-OCR**——0.9B 参数登顶 OmniDocBench

---

## 六、5 月关键数据

| 指标 | 数值 |
|------|------|
| CSV 总项目数 | 500 |
| 5 月新增项目 | ~191 |
| 活跃状态项目 | ~285 |
| 降温/停更/关闭 | ~8 |
| 被收购 | ~6（含 Stainless、Emmi AI、Cursor 待完成） |
| 事件 | ~29 |
| 假星高风险项目 | 9+ |

---

## 七、5 月总结判断

1. **模型竞争格局**：六大阵营（OpenAI/Anthropic/Google/DeepSeek/Qwen/Kimi）同时推新，开源模型首次在多个编码基准追平闭源旗舰。价格战加速，DeepSeek V4 Flash $0.14/M tokens 重新定义底价。

2. **Agent 生态进入治理期**：从"先上 Agent"转向"先治理 Agent"。Microsoft Agent Governance Toolkit、NVIDIA Verified Agent Skills、RAMPART 标志着企业 Agent 安全从边缘走向核心。

3. **信任危机分水岭**：Anthropic 在 4-5 月遭遇 9 次信任打击（cache 降级→封杀第三方→源码泄露→Pro 移除→质量事故→OpenClaw 歧视→HERMES.md→Claude Code 宕机→Copilot 文件外泄），但 Q2 首次盈利+$30B 融资+Karpathy 加入+收购 Stainless 展示了惊人韧性。

4. **公众 AI 反弹**："Tired of AI" HN 1961 分、Chrome 静默安装 1198 分——opt-in 将成为产品信任底线。

5. **SWE-bench 退役**：AI 最重要编码基准正式退役，评测体系面临系统性信任危机。

---

*下次巡检：2026-07-01*
