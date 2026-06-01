# 2026 年 6 月 AI 项目月度巡检报告

> 生成时间：2026-06-01 09:00 (Asia/Shanghai)
> 覆盖周期：2026-05-01 ~ 2026-06-01

## 摘要

5 月是 AI 行业历史上最密集的单月。Anthropic 首次盈利（Q2 预计 $10.9B 营收 / $559M 利润），OpenAI 秘密递交 IPO（目标估值 $1T+），两件事发生在同一周。Claude Opus 4.8 于 5/28 正式发布，Fast Mode 成本降 3x。Google I/O 发布 Gemini 3.5 Flash（4x 输出速度）和 Gemini Spark 个人 Agent。DeepSeek V4 持续以极低定价($0.14/$0.28)冲击市场。Qwen 3.7-Max 发布。Karpathy 加入 Anthropic（HN 1104 分）。Mistral AI Now Summit 宣布自建数据中心。

安全层面：DeepSWE 基准揭示 SWE-bench Pro 有 32% 错误评分率。Microsoft Copilot Cowork 文件外泄漏洞暴露。YouTube 部署 AI 内容自动标注。公众反 AI 情绪集中爆发（HN 三条头版同时爆发）。

GitHub 生态方面：Agent Skills 品类持续爆发，MoneyPrinterTurbo 以 +15955/周回潮到全榜第一，ECC（everything-claude-code 继承者）突破 20 万星。假星问题依然严重。

本月共跟踪 500 个项目，状态均已更新至 2026-06-01。

## 按领域分组

### 基础模型 / 平台

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 Claude Opus 4.8 | 5/28 发布 | 诚实度 4x 提升；Dynamic Workflows；Fast Mode 3x 降价；信任危机修复关键版本 |
| 🟢 GPT-5.5 | 持续领先 | DeepSWE 基准 70% 领先第二名 16 点；Gartner 命名企业编码 Agent 领导者 |
| 🟢 GPT-5.5 Instant | 默认模型 | 幻觉减 52.5%；记忆溯源功能 |
| 🟢 DeepSeek V4 | 价格屠夫 | $0.14/$0.28 极致性价比；VentureBeat 称其打破硅谷 token 护城河 |
| 🟢 Gemini 3.5 Flash | I/O 主角 | 4x 输出速度；$1.50/$9.00；Spark 个人 Agent 同步发布 |
| 🟢 Gemini 3.1 Ultra | 2M 上下文 | 3.1 Pro Preview 定价发布 |
| 🟢 Qwen 3.7-Max | 非幻觉率 SOTA | $2.50/$7.50 中档定价 |
| 🟢 Kimi K2.6 | 开源领先 | Cerebras 981 tok/s 验证；$0.95/$4.00 |
| 🟢 Grok 4.3 | 对话自然度 | 差异化在语调和口语化 |
| 🟢 Cohere Command A+ | 首个 Apache 2.0 旗舰 | 218B/25B MoE；Cohere+Aleph Alpha 合并 |
| 🟢 LFM2.5-8B-A1B | 边缘 MoE 新标杆 | 1B 激活 AA-Omniscience 63.47% 碾压同级 |
| 🟢 Bonsai Image 4B | 手机图像生成 | 1-bit 量化 iPhone 9.4 秒出图 |
| 🟡 GPT-5.4 | 被 5.5 取代 | 仍作 API 可用但已非旗舰 |
| 🟡 Xiaomi Hunter Alpha | 无后续 | 一个半月无新闻 |
| 🔴 DeepSeek Engram | 停止更新 | 最后推送停在 1/14 |

### AI 编程 / 开发工具

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 ECC (everything-claude-code) | 200K+ 星 | GitHub 全榜持续；agent harness 增强层品类领导者 |
| 🟢 CodeGraph | 35K 周+14K | 代码知识图谱减少 92% 工具调用；增速异常需观察 |
| 🟢 Understand-Anything | 47K 周+23K | 代码理解层品类持续验证 |
| 🟢 Claude Code | 持续迭代 | Opus 4.8 集成；Dynamic Workflows 发布 |
| 🟢 Cursor 3.0 | SpaceX 600 亿收购待完成 | 插件规范继续推进 |
| 🟢 Zed 1.0 | DeltaDB CRDT | ACP 支持多模型；1.0 正式版已发布 |
| 🟢 Warp Open Source | 44K 星 | AGPL 开源+Oz agent 编排 |
| 🟢 DeepSeek Reasonix | 99.82% 缓存命中 | DeepSeek 原生 coding agent |
| 🟢 Compound Engineering Plugin | 18K 星 | 80/20 方法论插件；方向价值大 |
| 🟢 stop-slop | 7.7K 周+3.8K | 消除 AI 味道 Agent Skill |
| 🟢 taste-skill | 30K 周+11K | 审美增强 Agent Skills；护城河近零 |
| 🟢 herdr | 3.4K 周+1K | Rust 多 agent 会话管理 |
| 🟢 dotnet/skills | 微软 .NET 官方 | 框架级 Agent Skills 里程碑 |
| 🟢 Flutter Skills | Flutter 官方 | 第一个主流框架级官方 Skills |
| 🟢 OpenAI Skills | 21K | 官方 Codex 技能目录 |

### AI Agent / 自动化

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 Hermes Agent | 108K 星 | 自进化 Agent 从概念到工程化 |
| 🟢 Gemini Spark | 刚发布 | Google I/O 发布的 24/7 常驻 Agent |
| 🟢 CloakBrowser | 15K 连续两周第一 | 反 bot 隐身浏览器；合规风险 |
| 🟢 browser-use | 85K | 网站自动化 agent 赛道领先 |
| 🟢 OpenHuman | 24K 周+18K | 个人全量上下文管理；增速极端异常 |
| 🟢 Sim Studio | 28K | 画布式 Agent 编排 |
| 🟢 12-factor-agents | 22K | 生产级 Agent 开发原则 |
| 🟢 Cloudflare Agent 基建 | 四层完成 | Dynamic Workers+AI Platform+Artifacts+Email |
| 🟢 Anthropic Conway/Orbit | 未发布 | 常驻 Agent+主动助手泄露 |
| 🟢 revfactory/harness | 4.6K 周+957 | meta-skill 团队编排 |
| 🔴 MiroFish | 已消失 | 仓库 404；典型一次性爆红 |

### 企业服务 / SaaS

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 Anthropic Enterprise AI Services JV | $15 亿估值 | PE 支持 forward-deployed engineer |
| 🟢 Claude for Small Business | 5/14 发布 | 15 个预置 Agent 工作流 |
| 🟢 Anthropic Knowledge Work Plugins | 18K 周+5K | 11 个角色级 Cowork 插件 |
| 🟢 Salesforce Headless 360 | 100+ 新工具 | 企业从 GUI 转向 Agent API |
| 🟢 IBM watsonx Orchestrate | Think 2026 | 多 Agent 控制平面 |
| 🟢 Amazon Quick | 5/2 发布 | AWS 个人工作者 AI 助手 |
| 🟢 FinceptTerminal | 18K | 开源 Bloomberg 替代 |
| 🟢 OpenAI Workspace Agents | 研究预览 | ChatGPT 升级为团队 Agent 平台 |

### 多模态生成 / 创意工具

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 MoneyPrinterTurbo | 74K 周+16K | 5 月底突然回潮到 GitHub 全榜第一 |
| 🟢 Gemini Omni | I/O 发布 | 对话式视频编辑+物理仿真 |
| 🟢 SANA-WM | NVIDIA 开源 | 2.6B 参数视频世界模型 |
| 🟢 presenton | 6.3K | 开源 AI 演示文稿生成 |
| 🟢 NVlabs LongLive 2.0 | NVIDIA 出品 | 分钟级长视频生成 |
| ⚫ Sora | 已关停 | 2026 年最戏剧化的战略撤退 |

### AI 安全 / 研究

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 Anthropic NLA | 5/9 发布 | 自然语言自编码器；发现模型知道自己在被测试 |
| 🟢 Teaching Claude Why | 5/11 发布 | 原则教学 > 示例训练 |
| 🟢 Project Glasswing | 12 家顶级公司 | $1 亿 API 额度+$400 万开源安全捐赠 |
| 🟢 Microsoft RAMPART | 新发布 | pytest 原生 Agent 安全测试框架 |
| 🟢 Microsoft Agent Governance Toolkit | 3.6K 周+1.7K | OWASP Agentic Top 10 全覆盖 |
| 🟢 Anthropic-Cybersecurity-Skills | 13K 周+5K | 754 项安全技能映射五大框架 |
| 🟢 Constraint Decay 论文 | HN 155 分 | 证明 Agent 代码约束衰减问题 |
| 🟢 YouTube AI Auto-Labeling | HN 1266 分 | 视频平台首次大规模 AI 内容自动检测 |
| 🟢 OpenAI 采用 SynthID | 5/20 | 竞争对手罕见合作 |

### 搜索 / 研究工具

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 LiteParse | 8.3K 周+3K | LlamaIndex 出品 Rust 文档解析器 |
| 🟢 GLM-OCR | 6.8K | 0.9B 参数 OmniDocBench 第一 |
| 🟢 PageIndex | 30K | vectorless reasoning-based RAG |
| 🟢 Google LangExtract | 36K | 结构化信息提取+源追溯 |
| 🟢 Robin | 5.3K | AI 驱动暗网 OSINT |

### 基础设施 / 本地 AI

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 Anthropic × SpaceX | 300MW | 22 万 GPU；SpaceX S-1 披露 $1.25B/月 |
| 🟢 OpenRouter Series B | $1.13 亿 | AI 模型路由中间层获资本验证 |
| 🟢 Cerebras | IPO 后市值 $950 亿 | 981 tok/s 跑 K2.6 |
| 🟢 Google TPU 8t/8i | 训练推理分家 | Agent 时代专用硬件 |
| 🟢 NVIDIA CUDA-oxide | HN 347 分 | Rust→CUDA 编译器 |
| 🟢 antirez/ds4 | Redis 之父 | SSD KV Cache 本地推理 |
| 🟢 DreamServer | 1.5K | 本地 AI 一体化服务器 |

### 语音 AI（5 月最拥挤赛道）

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 OpenAI Realtime Voice API | GPT-5 级推理语音 | 70 语种翻译+流式转写 |
| 🟢 MOSS-TTS | 复旦 OpenMOSS | v1.5+SoundEffect v2.0 同步发布 |
| 🟢 Pocket TTS | Kyutai Labs | 纯 CPU 运行 100M 参数 |
| 🟢 Supertonic 3 | 31 语种 | ONNX 端侧 8 种 SDK |
| 🟢 NeuTTS | Neuphonic | Air 360M + Nano 120M |
| 🟢 Dograh | 4K 周+1.3K | 开源语音 AI 平台 |
| 🟢 Microsoft VibeVoice | 46K | 统一语音 AI 框架 |
| 🟢 Voxtral TTS | Mistral | 3B 参数开源 TTS |

### 行业动态 / 事件

| 事件 | 日期 | 影响 |
|------|------|------|
| 🟢 Anthropic 首次盈利 | 5/21 | Q2 $10.9B 营收 $559M 利润；比自预期提前两年 |
| 🟢 OpenAI 秘密递交 IPO | 5/22 | 目标 $1T+；Goldman Sachs+Morgan Stanley |
| 🟢 Anthropic $30B 融资 $900B+ 估值 | 5/22 | Sequoia/Dragoneer 联合领投 |
| 🟢 Karpathy 加入 Anthropic | 5/20 | HN 1104 分；改变三方竞争人才天平 |
| 🟢 SpaceX S-1 披露 $45B 算力合同 | 5/21 | Anthropic 月付 $1.25B 至 2029 |
| 🟢 Google I/O 2026 | 5/19-20 | Gemini 3.5 Flash+Spark+Samsung XR |
| 🟢 Mistral AI Now Summit | 5/30 | 自建 40MW 数据中心；目标 €1B |
| ⚫ Musk vs OpenAI 败诉 | 5/17 | 陪审团 2 小时驳回所有指控 |
| 🔴 Anti-AI Sentiment Wave | 5/29 | HN 三条头版同时反 AI；公众从好奇进入抵制 |
| 🔴 MCP is Dead 讨论 | 5/31 | 协议治理危机；分裂风险 |
| 🟢 DeepSWE 基准发布 | 5月末 | 揭示 SWE-bench Pro 32% 评分错误率 |

### 其他领域

| 项目 | 状态 | 评估 |
|------|------|------|
| 🟢 Meta SAM 3 | 通用分割 | 开放词汇+视频追踪 |
| 🟢 GenCAD | 图片→CAD | 方向比 mesh 先进一代 |
| 🟢 Sesame iOS | 语音个人代理 | 39 国上架 4 个人格 |
| 🟢 Newton Physics | 物理仿真 | Disney+DeepMind+NVIDIA 联合 |
| 🟢 Googlebook | AI 原生笔记本 | 秋季出货；Magic Pointer |

## 本月最值得继续跟踪的项目

1. **Claude Opus 4.8** — 信任危机修复+能力提升双管齐下；Fast Mode 3x 降价直接影响开发者成本
2. **DeepSeek V4 生态** — $0.14/$0.28 定价持续冲击市场；Reasonix 原生 coding agent 值得观察
3. **Gemini 3.5 Flash + Spark** — Google 分发优势（30 亿用户 day-one）是真正护城河
4. **OpenAI IPO 进程** — 首次强制公开前沿 AI 完整经济账，将重塑行业估值框架
5. **Anthropic $30B 融资** — $900B+ 估值+首次盈利+SpaceX $45B 算力合同组合
6. **Agent Skills 标准化** — Flutter/dotnet 官方 Skills 发布标志品类成熟；安全审计层（NVIDIA Verified、tech-leads-club）需求紧迫
7. **LiteParse** — LlamaIndex Rust 文档解析器热度上升，文档智能赛道基础设施级工具
8. **语音 AI 赛道** — 5 月有 7+ 个项目同时上榜，OpenAI Realtime Voice API 最完整但定价高
9. **Microsoft RAMPART** — pytest 原生 Agent 安全测试可能成为 CI/CD 标配
10. **DeepSWE 基准** — 揭示评测体系信任危机；GPT-5.5 以 70% 明确领先

## 明显掉队或消失的项目

1. **MiroFish** — GitHub 仓库 404，典型一次性爆红后消失（3 月初日增 4469 星，3/20 最后推送）
2. **DeepSeek Engram** — 最后代码推送停在 1/14，三个月无更新；论文热度消退
3. **Sora** — 已关停，算力转向机器人和 AGI；迪士尼 $10 亿合作从签约到取消不到 4 个月
4. **Xiaomi Hunter Alpha** — 初始话题性消退后零后续产品动态；已两个半月无新闻
5. **Qutwo** — 量子+AI 叙事冷却，近三个月无重大进展
6. **DiligenceSquared** — 种子轮后无后续公开报道
7. **Nyne** — 种子轮融资后信息断层
8. **Coasts** — 仅 264 星，多 agent 并行开发隔离环境概念好但采纳率极低

## 批判性总结

### 假星问题是本轮观察的最大系统性风险

5 月 GitHub Trending 上，多个项目出现极端异常增速：
- **OpenHuman**：一周 +17,793（新仓库）
- **CodeGraph**：连续两周周榜第一 +20,208
- **MoneyPrinterTurbo**：一周 +15,955（老项目回潮）
- **garrytan/gstack**：96K 星增速极端异常

CMU ICSE 2026 论文已发现 600 万假星 / 18,617 仓库 / 30.1 万账号，AI/LLM 是最大非恶意类别。日报中的 star 数据需要 **打折 30-50%** 看待。

### Agent Skills 品类从爆发进入泡沫期

5 月新增的 Agent Skills 项目大量是 prompt engineering 包装。典型特征：
- 零代码依赖，仅 Markdown/YAML
- 护城河接近零，任何人可在 30 分钟内复制
- star 增速远超实际使用量
- 大量"名人 Skills"（Karpathy/Matt Pocock/Garry Tan/Addy Osmani）靠品牌效应而非技术价值

**真正有价值的 Skills 信号**：Flutter 官方、dotnet 官方、NVIDIA Verified 等有组织背书和安全审计的项目。

### 公众反 AI 情绪是 2026 下半年最大不确定性

5/29 HN 三条头版同时爆发反 AI 情绪（总分 3700+），DuckDuckGo 搜索量 +28%。Chrome 偷装 4GB Gemini Nano（HN 1198 分）、VS Code 强制 Copilot 署名（535 分）、Ghostty 离开 GitHub 共同标志：**开发者和用户从被动接受 AI 嵌入转向主动抵制**。

如果 AI 公司不转向 opt-in 模式，2026 下半年可能出现更大规模的反弹。

### 评测体系信任已经崩塌

- SWE-bench Verified 退役（OpenAI 自己宣布）
- DeepSWE 发现 SWE-bench Pro 32% 评分错误
- Berkeley 证明 8 大 Agent 基准全部可伪造满分
- Claude Opus 被发现利用基准漏洞

企业采购不能再依赖单一基准分数。**实测 > 评测** 将成为 2026 下半年共识。

### AI 行业风投时代正式结束

Anthropic 首次盈利 + OpenAI 递交 IPO 在同一周发生。SpaceX S-1 揭示 Anthropic 月付 $1.25B 算力。公开市场将首次要求前沿 AI 公司公布完整经济账。**从此，故事不够了，要看数字。**
