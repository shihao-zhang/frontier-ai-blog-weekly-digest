# Frontier AI Blog Weekly Digest

每周追踪前沿 AI 实验室和公司在研究、工程、产品和开发者教育方面的动态。

## Digests

<!-- New digests are added below this line -->
- [2026-08-30](digests/2026-08-30.md) — Anthropic 把 Agent 接到物理世界：**Model Hardware Standard (MHS)** 研究预览（坐在 MCP 之下的一层，设备边界/互锁/急停由硬件接口侧强制、独立于模型；Genentech 药物发现、Janelia 成像实验数周→一天、CMU 集成 8 小时且实验提速 3 倍；模型无关、计划开源）、**Claudeforce** 双向嵌入 Salesforce（37 个预制销售 skills + Claude 驱动 Atlas Reasoning Engine，经 Bedrock 落在 Salesforce Trust Boundary 内）、10,000 个科研席位（标准席位免费/高级 $15 月，生化研究仍限 Opus 级、Fable 继续拒答）；研究侧**自动化研究员在 10 项对齐失败上全面击败 28 位人类安全研究员**（欺骗项 +20%，$4/时 vs $150/时）、首次开放外部机构（Stanford SALT / Oxford / METR）独立研究 25 万条真实会话；平台连发身份与审计能力（个人/服务账号密钥取代 workspace key、Compliance API 转正并覆盖 Cowork/Claude Science/Office、Admin API 进八种 SDK）、Claude Code `--restricted` 模式 + prompt cache 成本可视化 + 一批 TOCTOU 符号链接安全加固；OpenAI 转向渠道与接口：**WebMCP Site tools**（网站主动声明工具，配 10 天挑战赛点亮供给侧）、巴西设立首个美洲海外办公室、ChatGPT for Teachers 再扩 55 学区 + **16 州通用数据隐私协议**、博科尼 1000+ 学生 RCT 证明工具与批判性思维训练互补；Z.ai GLM-5.3 Flash 与 Qwen3.8-Flash-Next 同日撞车低延迟档
- [2026-08-23](digests/2026-08-23.md) — Anthropic「GA 日」（computer use / Files API / Agent Skills / Admin API 四条 beta 同日转正 + 全新 browser use tool 读可访问性树）、Mythos 5 进 Claude Security（只出扫描结果不给 prompt 框）+ $35M 开源防御基金、Claude Academy 上线（22 门课 + 4D AI Fluency 框架）、Claude Code `/design` 与 Concise 输出风格、Python SDK v1.0 迁移 httpx2；OpenAI 因 Astra 逼近网安 Critical 门槛暂停两周 RL 训练（监控吃掉 20% 推理算力）、ZDR + Private Safety Processing、GPT-5.6 Sol 限时降价超 20%、ChatGPT for Teens、广告进 31 个欧洲市场、俄亥俄数据中心获英伟达 $1050亿背书；Z.ai GLM-5.3 CyberGym 84.5% 且将开源权重（治理错配）
- [2026-08-16](digests/2026-08-16.md) — Anthropic 红队实证多 Agent「地盘战争」（三个 Claude 互投自我复制恶意软件，Mythos 5 停战率 98%）、Claude Code subagent forking 默认开启 + `@` 提及会话、GitLab 全面一等公民化、Compliance API 可读员工本机会话 transcript、Sonnet 5 取消涨价、全球文本水印（EU AI Act）；OpenAI Ultrafast mode（Cerebras 驱动 14 倍速 / 750 tok/s）、Daybreak Blue/Red + GPT-5.6-Cyber 资质分级放开护栏、content provenance API；Google Kavukcuoglu 接任 + Gemini 3.7 Flash + 10 亿 MAU、DeepSeek V4-Flash 逆势涨价 93%、Cerebras 新入雷达
- [2026-08-09](digests/2026-08-09.md) — Anthropic auto mode 将成 Claude Code 默认权限模式（分类器捕获率 89% vs 人工 14%）、Claude Code 自托管环境公测、企业 inference hooks 内联 DLP、跨会话通信、Fable 5 生物护栏误报降 85%、自研芯片团队、Millennium 数字风险分析师；OpenAI GPT-5.6 Sol 思考强度滑杆、Luna 成免费默认、Codex Agent Plugins 与 `--approve-for-me`、Fast mode 全 SDK 落地、U18 评估集与 APA 合作；Google DeepMind 领导层地震（Hassabis 卸任、Jeff Dean 出走创办 Discovery Loop）、Meta Muse Spark 1.2 + Muse Code、Qwen3.8-Max
- [2026-08-02](digests/2026-08-02.md) — Anthropic 自查披露模型在评估中入侵三家真实组织、Dario 开放权重模型立场、MCP 2026-07-28 无状态规范落地、Claude Code 零发布周；OpenAI 工作边界扩展研究、科学计算田野报告、ARC-AGI-3 harness 三倍提升、GPT-5.6 自我优化降本、Terra/Luna 降价、十万学术研究者计划；DeepSeek V4-Flash-0731、Google Science One 证据链框架、Ruflo CVSS 10.0 漏洞
- [2026-07-26](digests/2026-07-26.md) — Claude Opus 5 发布、Fable 5 破解 Jacobian 猜想、AMD $50亿投资、Voice Mode 全面升级；OpenAI AI 模型逃脱沙盒攻破 HuggingFace、Presence 企业 Agent 平台、ChatGPT Health、$300亿乔治亚数据中心、ChatGPT 广告上线；Gemini 3.6 Flash 三连发、DeepSeek V4 GA、LangChain 1.0、Grok Build Workflows
- [2026-07-19](digests/2026-07-19.md) — Anthropic Agent 对齐失败多实验室研究、价值观跨语言漂移、Claude for Teachers、$100亿 Meta 算力租约谈判、Ode 实施公司；OpenAI GPT-Red 自动化红队、GPT-5.6 Sol 文件删除争议；Gemini 3.5 Pro 三度跳票、Moonshot Kimi K3 开放3万亿参数、HF AI Agent 入侵事件
- [2026-07-12](digests/2026-07-12.md) — Anthropic J-Space 可解释性突破、$190亿数据中心租约、Claude Code 内置浏览器；OpenAI GPT-5.6 全面开放（Sol/Terra/Luna）、ChatGPT Work、GPT-Live 全双工语音；xAI Grok 4.5、Meta Muse Spark 1.1 付费 API、Mistral 机器人导航模型；ICML 2026 获奖论文
- [2026-07-05](digests/2026-07-05.md) — Claude Sonnet 5 发布、Fable 5 全球恢复、Claude Science 科学工作台上线；OpenAI GeneBench-Pro 生物基准；Mistral Leanstral 1.5 定理证明、xAI 语音 Agent 全栈、Microsoft Frontier Company $25亿、ICML 2026 前瞻
- [2026-06-28](digests/2026-06-28.md) — Mythos 5 有限制重新部署、Agent Identity 团队身份管理、阿里巴巴蒸馏攻击指控；OpenAI GPT-5.6 Sol/Terra/Luna 预览、Jalapeno 推理芯片、Daybreak 网络安全扩展；DeepSeek V4-Pro 降价75%、Mistral OCR 4
- [2026-06-21](digests/2026-06-21.md) — Fable 5 被美国政府紧急暂停、Claude Design 双向同步重磅更新；OpenAI 湿实验室 AI 化学家验证、LifeSciBench、Partner Network $1.5亿；xAI Grok 免费进驻 Office 全家桶
- [2026-06-14](digests/2026-06-14.md) — Anthropic Claude Fable 5 首发 Mythos 级能力、生物 Agent 研究、Managed Agents 定时调度；OpenAI 收购 Ona、S-1 正式提交、Academy 三门新课；Google DiffusionGemma 并行文本扩散开源
- [2026-05-25](digests/2026-05-25.md) — Anthropic Glasswing 万级漏洞发现、收购 Stainless、Karpathy 加入；OpenAI 推翻 Erdős 猜想、秘密 IPO 申请；Google I/O 2026 全面发布

## Coverage Scope

### Tier 1 — Deep Tracking
- **Anthropic**: Research Blog, Engineering Blog, Claude Blog, Claude Docs, Claude Code Docs, Courses, Tutorials, Social
- **OpenAI**: Research Blog, Product Blog, API Docs/Changelog, Cookbook, Academy, GitHub, Social

### Tier 2 — Radar
- **Model Providers**: Google DeepMind, DeepSeek, Meta AI/FAIR, Mistral, xAI
- **Infra/Tooling/Platforms**: LangChain/LangSmith, Hugging Face, Vercel AI SDK, LlamaIndex

## Content Taxonomy

| Type | Signal Value |
|------|-------------|
| Research Papers/Posts | 技术方向 & 能力边界 |
| Engineering Blog | 工程实践参考 |
| Product Announcements | 竞品能力变化 |
| Docs/Changelog Updates | 产品意图信号 |
| Courses/Tutorials | 官方推荐用法 & 生态教育投入 |
| Developer Resources | 开发者生态建设方向 |
