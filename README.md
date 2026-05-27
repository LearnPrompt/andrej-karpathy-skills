<div align="center">

# 🧠 Karpathy-Inspired Skills

#### 从 Andrej Karpathy 三年公开分享中，提炼出 14 个每天能用的 AI 工作方法 + 1 个总控路由

[![License](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge)](./LICENSE)
[![Skills](https://img.shields.io/badge/Skills-14%2BRouter-10B981?style=for-the-badge)](#-skills)
[![Workflows](https://img.shields.io/badge/Workflows-4-F59E0B?style=for-the-badge)](#-workflows)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-8B5CF6?style=for-the-badge)](https://agentskills.io)
![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-Skill-10B981?style=flat-square&logo=openai&logoColor=white)
![Clacky](https://img.shields.io/badge/Clacky-Skill-EC4899?style=flat-square)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-111827?style=flat-square)
![Hermes](https://img.shields.io/badge/Hermes-Skill-7C3AED?style=flat-square)
![OpenCode](https://img.shields.io/badge/OpenCode-Skill-3B82F6?style=flat-square)

</div>

不是语录摘抄，不是人生鸡汤导师。

是 Karpathy 反复在 X 上聊到的那些工作习惯，整理成 Agent 能直接照着执行的指南。

在我的视角，**他一直把复杂的东西拆到人能理解、能复现、能迭代。** 这 14 个方法 + 1 个总控 Skill 就是按这个思路来的，每个都有明确的触发场景、执行流程、验收标准。

和市面上其他项目不同——我常用的 [obra/superpowers](https://github.com/obra/superpowers) 里的 brainstorming 和 [garrytan/gstack](https://github.com/garrytan/gstack) 里的 office-hours，其他 Skills 使用频率基本为零。**这些 Skill 能组成 4 条完整工作流。**

---

## 📋 Skills

| 名字 | 一句话 | 来源 |
|------|--------|------|
| 🎯 **karpathy-methodology** | 不知道用哪个？从这里开始，它帮你选 | 总控路由 |
| ⚙️ **agentic-engineering** | 每轮只交付一个可 review 的增量变更，跑测试后再继续 | [X](https://x.com/karpathy/status/2015883857489522876) |
| 🔀 **vibe-to-agentic** | 先 vibe coding 出原型，再切 agentic 模式收尾上线 | [X](https://x.com/karpathy/status/2026731645169185220) |
| 🔬 **autoresearch** | 假设→实验→分析→下一轮，Agent 替你跑实验 | [X](https://x.com/karpathy/status/2030371219518931079) |
| 🎭 **llm-simulator** | 别问 AI 怎么想，让它模拟 5 个人替你吵架出主意 | [X](https://x.com/karpathy/status/2037921699824607591) |
| 📚 **llm-wiki** | 用 LLM 维护一个越用越值钱的 Markdown wiki | [Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) |
| 🧊 **minimalism** | 每加一个依赖，就多一个出问题的点——能不加就不加 | [X](https://x.com/karpathy/status/2021694437152157847) |
| 🛡️ **supply-chain-hygiene** | 你知道 npm install 的包里有什么吗？大概率不知道 | [X](https://x.com/karpathy/status/2036487306585268612) |
| 🧠 **understanding-first** | AI 帮你写，但出了 bug 你得能读懂它在干嘛 | [X](https://x.com/karpathy/status/2049907410303865030) |
| 📝 **idea-files** | 先把想法写清楚，然后扔给不同 Agent 各自实现、互相对比 | [X](https://x.com/karpathy/status/2049903821095354523) |
| 📈 **output-evolution** | 别只发文字了，让 LLM 给你发 HTML 和幻灯片 | [X](https://x.com/karpathy/status/2053872850101285137) |
| 🎓 **education-first** | 把任何经验压缩成一个 nano project 教会别人 | [X](https://x.com/karpathy/status/1885026028428681698) |
| 🔁 **system-prompt-learning** | 踩坑 → 识别模式 → 写进 system prompt → 永不再犯 | [X](https://x.com/karpathy/status/1921368644069765486) |
| 🏋️ **practice-environments** | 给 Agent 一个能安全试错的沙盒环境 | [X](https://x.com/karpathy/status/1960803117689397543) |
| 🪞 **meta-reflection** | 每月复盘：哪些能力在退化，哪些在提升 | 综合多条 |

---

## 🔗 Workflows（4 条工作流）

建议触发时直接说「用 Karpathy『工作流名』工作流……」。只说「研究到发布」这类通用词，可能会被其他研究或内容 Skill 抢走。

| 工作流 | 链路 | 推荐触发语 | Codex | Hermes | OpenClaw | Claude Code |
|------|------|------------|-------|--------|----------|-------------|
| 🚀 **想法到上线** | idea-files → agentic-engineering → minimalism → supply-chain-hygiene → vibe-to-agentic | `用 Karpathy「想法到上线」工作流，把“AI 产品雷达”这个想法推进到可上线的最小版本。` | 通过 | 通过 | 通过（顺序 fresh session） | 通过（需显式 `/karpathy-*` 链路） |
| 📖 **研究到发布** | autoresearch → llm-wiki → output-evolution → education-first | `用 Karpathy「研究到发布」工作流，把“AI 浏览器 agent 的发展趋势”做成一篇可发布研究内容。` | 通过 | 通过（需 Karpathy 前缀） | 通过（顺序 fresh session） | 通过（需显式 `/karpathy-*` 链路） |
| ⚖️ **反偏见决策** | llm-simulator → understanding-first → system-prompt-learning | `用 Karpathy「反偏见决策」工作流，帮我判断要不要把这个 skill 默认安装到所有 agent。` | 通过 | 通过 | 通过（顺序 fresh session） | 通过（需显式 `/karpathy-*` 链路） |
| 🪞 **月度体检** | meta-reflection → understanding-first → practice-environments → education-first | `用 Karpathy「月度体检」工作流，帮我复盘这个月使用 AI 写代码和写内容的能力变化。` | 部分通过（缺少完整月度任务清单） | 超时 | 通过（含 methodology 路由） | 通过（需显式 `/karpathy-*` 链路） |

测试方式：每条 prompt 都用 `tmux` 新建一次全新会话。Codex 使用 `codex exec`，Hermes 使用 `hermes -z`，OpenClaw 使用 `openclaw agent`，Claude Code 使用 `claude -p --no-session-persistence`。测试时间：2026-05-26。

OpenClaw 安装、Skill 识别、Codex OAuth 登录和最小对话探针已通过：`openclaw agent --local --model openai/gpt-5.5` 能返回 `OK`。四条工作流用 `tmux` 顺序新建 session 重测通过；并发同时跑 4 条会触发 OpenClaw 内部 `CommandLaneTaskTimeoutError`。OpenClaw 会注入较大的 workspace + skill index，单条测试约 63k-86k tokens。

Claude Code 自然语言触发不稳定：只说「用 Karpathy『工作流名』工作流」时，曾出现链路配错和身份串台。显式写出 `/karpathy-idea-files /karpathy-agentic-engineering ...` 这类 Skill 链路后，4 条工作流均可在全新 session 中触发。

---

## ✨ Skills（详细说明）

### 🎯 karpathy-methodology（总控路由）

> *"14 个方法不是都要用。大部分时候你只需要 2-3 个，问题是——选哪几个？"*

不知道该用哪个 Skill？从这里开始。它根据你的任务类型自动路由到对应的 Skill 组合。

**路由逻辑**

| 你在做什么 | 推荐加载 |
|-----------|---------|
| 写代码、做项目 | agentic-engineering + minimalism + supply-chain-hygiene |
| 做研究、写内容 | autoresearch + llm-wiki + output-evolution |
| 做重要决策 | llm-simulator + understanding-first |
| 学新东西 | education-first + practice-environments |
| 月度复盘 | meta-reflection + understanding-first |

**怎么触发**

```
用 karpathy 方法帮我做这件事
不知道用哪个 skill
帮我选方法
```

→ [SKILL.md](./karpathy-methodology/SKILL.md)

### ⚙️ agentic-engineering

> *"The hottest new programming language is English."*

Karpathy 2024 年底加入 Anthropic 前后反复聊的一件事：程序员的工作正在从「写每一行代码」变成「指挥 Agent 写代码」。但这不是甩手掌柜，要先给清楚上下文、定义成功标准、review每一轮 diff、控制变更范围。

**为什么需要这个？**

你大概试过让 Agent 做一个完整功能，结果它一口气改了 20 个文件，你都不知道它干了什么。这个 Skill 的核心就是，

**每轮只交付一个可 review 的增量变更，跑测试后再继续。**

**它怎么工作**

1. 塞入项目上下文：目标、约束
2. 把请求改写成可验证的成功标准
3. Agent 先提方案和取舍，再动手
4. 每轮一个 diff → 跑测试 → 人工 taste review → 下一轮
5. 人类负责方向和判断，Agent 负责执行和验证

**所属工作流**：🚀 想法到上线

**来源**：Karpathy 的 [Claude coding notes](https://x.com/karpathy/status/2015883857489522876)、[programming changed](https://x.com/karpathy/status/2026731645169185220)

→ [SKILL.md](./karpathy-agentic-engineering/SKILL.md)

### 🔀 vibe-to-agentic（从原型到工程）

> *"There's a whole mass of people for whom programming just kinda opened up."*

Vibe coding 很爽，你随口说几句，AI 就给你搓出一个能跑的东西。

但开发之后呢？代码没测试、边界没处理、依赖一团糟。这个 Skill 帮你在「快速出原型」和「能上线的工程」之间搭一座桥。

**两阶段切换**

| 阶段 | 模式 | 你在做什么 |
|------|------|-----------|
| 1 | Vibe mode | 快速摸到原型，验证想法能不能跑 |
| 2 | Agentic mode | 迭代到上线标准，让 Agent 加测试、砍冗余、收紧边界 |

**适合**：你已经有一个「能跑但不敢上线」的原型

**不适合**：你还没开始写，那直接用 agentic-engineering

**所属工作流**：🚀 想法到上线

**来源**：[Programming is changing fast](https://x.com/karpathy/status/2026731645169185220)

→ [SKILL.md](./karpathy-vibe-to-agentic/SKILL.md)

### 🔬 autoresearch（自主研究循环）

> *"The Agent ran 300 experiments while I slept and found 3 things I hadn't considered."*

把研究变成一个可迭代循环，**假设 → 创建分支 → 跑实验 → 分析日志 → 更新假设 → 下一轮。**

Agent 不停转，人类隔段时间回来 review 方向和写提示语。

**它怎么工作**

```
[你] 初始假设 + 评估指标
      ↓
[Agent] 创建 git 分支 → 跑实验 → 分析结果
      ↓
[Agent] 提出下一轮假设 → 等你批准或修正
      ↓
[循环继续]
```

**适合**：ML 训练调参、竞品测试矩阵、prompt 优化实验

**不适合**：没有 baseline 的开放式探索

**所属工作流**：📖 研究到发布

**来源**：[AutoResearch tweet](https://x.com/karpathy/status/2030371219518931079)

→ [SKILL.md](./karpathy-autoresearch/SKILL.md)

### 🎭 llm-simulator（模拟器思维）

> *"Don't ask the model what it thinks. Ask it to simulate people who disagree."*

LLM 最大的问题是讨好你。

你问它「这个方案好不好？」它永远说好。

解法不是追求「客观回答」，而是让它模拟多个有利益冲突的角色互相辩论。

**四种模式**

| 模式 | 适合 |
|------|------|
| Expert Panel | 技术架构决策、产品方向 |
| Red Team | 安全审计、方案压力测试 |
| User Personas | 产品发布前的用户反应预测 |
| Failure Modes | 「如果一切都出错了会怎样」 |

**为什么比普通对话强**

普通对话：你得到一个看起来合理的答案，但不知道它隐藏了什么。

模拟器模式：你看到 5 个角色互相拆台，暴露出你没想到的盲区。

**所属工作流**：⚖️ 反偏见决策

**来源**：[Argue the opposite](https://x.com/karpathy/status/2037921699824607591)

→ [SKILL.md](./karpathy-llm-simulator/SKILL.md)

### 📚 llm-wiki（知识复利）

> *"每条笔记都该是一个会增值的资产，而不是写完就沉底的垃圾。"*

Karpathy 发过一个 Gist 详细描述了他理想中的 LLM Wiki：raw sources 不可变，wiki 页面由 LLM 编译生成，有 index、changelog、lint、去重、矛盾检测。本质上是用 LLM 维护一个越滚越大的知识图谱。

**和普通笔记工具的区别**

| 普通笔记 | LLM Wiki |
|---------|---------|
| 你写，你整理 | 你扔原料进去，LLM 帮你整理 |
| 越多越乱 | 越多越好——LLM 做交叉引用和矛盾检测 |
| 一条一条找 | 跨页面追踪同一个实体的演变 |

**所属工作流**：📖 研究到发布

**来源**：[LLM Wiki Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)、[LLM KB tweet](https://x.com/karpathy/status/2039805659525644595)

→ [SKILL.md](./karpathy-llm-wiki/SKILL.md)

### 🧊 minimalism（极简主义）

> *"I mass delete mass dependencies. mass mass."*

Karpathy 一直在身体力行一件事：用纯 Python 实现 GPT（minGPT、nanoGPT），不用 PyTorch Lightning、不用 Hugging Face Trainer、不用任何包装层。为什么？因为每一层抽象都是一堵理解力的墙。

这个 Skill 帮你做依赖决策：什么时候该引入一个库，什么时候该自己写 50 行代码替代它。

**决策树**

```
需要这个功能？
  └── 能用 50 行以内实现？ → 自己写
  └── 不能？ → 它有多少 transitive dependencies？
       └── < 5 → 可以考虑
       └── > 20 → 红旗。找替代或 yoink 核心代码
```

**所属工作流**：🚀 想法到上线

**来源**：[Pure Python GPT](https://x.com/karpathy/status/2021694437152157847)、[CLI for agents](https://x.com/karpathy/status/2026360908398862478)

→ [SKILL.md](./karpathy-minimalism/SKILL.md)

### 🛡️ supply-chain-hygiene（供应链安全）

> *"Every pip install is an act of mass trust."*

LiteLLM 事件让 Karpathy 公开表态，

依赖不是免费的午餐。每个包都是一个攻击面，每个 postinstall 脚本都是一次权限放弃。这个 Skill 让你在 install 之前先想三秒。

**它做什么**

- 审查新依赖的 transitive tree
- 检查是否有 postinstall hooks
- 推荐 pinned version + lockfile
- 提供「不装也行」的替代方案

**所属工作流**：🚀 想法到上线

**来源**：[Supply chain LiteLLM](https://x.com/karpathy/status/2036487306585268612)、[Memory hygiene](https://x.com/karpathy/status/2036836816654147718)

→ [SKILL.md](./karpathy-supply-chain-hygiene/SKILL.md)

### 🧠 understanding-first（理解不能外包）

> *"You can outsource thinking, but you cannot outsource understanding."*

这句话是整套方法论的哲学内核。

AI 可以帮你写代码、做分析、找答案，但如果你不理解它做了什么，你就在给自己挖坑。

这个 Skill 会强制 Agent 在每次输出后附上，**关键假设、已验证项、未验证项、你必须亲自检查的部分。**

**它在 Agent 输出里加什么**

```
## 你需要理解的部分
- 关键假设：[列出]
- 已通过验证：[列出证据]
- 仍是推测：[列出，附验证方法]
- 建议你亲自看：[具体文件/行/配置]
```

**所属工作流**：⚖️ 反偏见决策 + 🪞 月度体检

**来源**：[Understanding quote](https://x.com/karpathy/status/2049907410303865030)

→ [SKILL.md](./karpathy-understanding-first/SKILL.md)

### 📝 idea-files（想法文件）

> *"Share the idea, not the implementation. Let different agents build different versions."*

灵感来了别急着写代码。先写一个「想法文件」，

背景、目标用户、成功标准、约束条件、实现建议。然后把这个文件丢给不同的 Agent，让它们各自实现。

**想法文件结构**

```markdown
# [想法名称]
## 背景：为什么要做这个
## 目标用户：谁会用
## 成功标准：做成了长什么样
## 约束：绝对不能做什么
## 实现建议：如果让 Agent 做，给它什么提示
```

**所属工作流**：🚀 想法到上线

**来源**：[Agent native MD](https://x.com/karpathy/status/2049903821095354523)

→ [SKILL.md](./karpathy-idea-files/SKILL.md)

### 📈 output-evolution（输出进化）

> *"HTML is the new Markdown."*

2025 年之后，LLM 的输出不该只是一坨文字了。它可以给你一个可交互的 HTML 页面、一份 Marp 幻灯片、一个实时仪表盘、一个可嵌入的图表。这个 Skill 帮 Agent 选择最合适的输出形式。

**输出阶梯**

```
纯文本 → Markdown → Marp 幻灯片 → 独立 HTML
→ 可交互 Dashboard → 带状态的 Web App
```

**适合**：需要分享给别人看的、需要演示的、需要汇报的

**不适合**：只是你自己看个结论

**所属工作流**：📖 研究到发布

**来源**：[HTML output](https://x.com/karpathy/status/2053872850101285137)

→ [SKILL.md](./karpathy-output-evolution/SKILL.md)

### 🎓 education-first（教育优先）

> *"Take LLMs to school."*

Karpathy 做 minGPT 不是为了发论文，是为了让所有人都能理解 Transformer。

他的方法论，任何复杂系统都能压缩成一个 nano project（< 300 行），配上逐步讲解和练习题，让零基础的人从「完全不懂」走到「能改代码」。

**nano project 模板**

1. 一句话说明它是什么
2. 最小可运行版本（< 300 行）
3. 逐步 walkthrough
4. 3-5 个递进式练习
5. 常见误区清单

**所属工作流**：📖 研究到发布+ 🪞 月度体检

**来源**：[Take LLMs to school](https://x.com/karpathy/status/1885026028428681698)

→ [SKILL.md](./karpathy-education-first/SKILL.md)

### 🔁 system-prompt-learning（提示学习）

> *"Learn by writing strategies into system prompts, not by hoping the model remembers."*

Agent 反复犯同一类错误？那就把正确做法写进 system prompt。这个 Skill 帮你把每次踩坑的经验，沉淀成可复用的 prompt 指令块。

**流程**

```
[踩坑] → 识别错误模式 → 写成触发条件+策略+反模式 → 测试 → 写入 skill 或 system prompt
```

**为什么比「记住」更靠谱**

记忆会衰减、会被覆盖、会在新 session 里消失。写进 system prompt 的东西是硬编码的行为规则——每次启动都在。

**所属工作流**：⚖️ 反偏见决策

**来源**：[System prompt learning](https://x.com/karpathy/status/1921368644069765486)

→ [SKILL.md](./karpathy-system-prompt-learning/SKILL.md)

### 🏋️ practice-environments（练习场）

> *"You can't learn tennis by reading about tennis. You need a court."*

给 Agent 一个可以安全试错的环境：有明确的任务、有自动评分、有重试机制。类似 RL 里的 gym environment，但给 LLM 用。

**练习场三要素**

1. **任务定义**：清晰的输入→输出映射
2. **自动评分**：不需要人工判断对错
3. **反馈循环**：错了→看到哪里错了→重试

**适合**：教 Agent 新技能、评估 Agent 能力边界、做 eval

**不适合**：开放式创作任务（没有标准答案的）

**所属工作流**：🪞 月度体检

**来源**：[RL environments](https://x.com/karpathy/status/1960803117689397543)

→ [SKILL.md](./karpathy-practice-environments/SKILL.md)

### 🪞 meta-reflection（元反思）

> *"每隔一段时间问自己：AI 正在悄悄替代我的哪些能力？我还行不行？"*

每月一次的结构化自省。不是焦虑想 AI 要替代我了，而是复盘哪些技能在因为过度依赖AI 退化了，哪些因为 AI 加持而变成了超能力，哪些该刻意练习，哪些该彻底放手。

**审计模板**

- 本月完成的任务清单
- 哪些完全交给了 AI（标记萎缩风险）
- 哪些因 AI 效率翻倍（标记杠杆点）
- 下个月决定刻意练习的 1 件事
- 下个月决定完全交给 AI 的 1 件事

**所属工作流**：🪞 月度体检

**来源**：综合 [Anthropic join](https://x.com/karpathy/status/2056753169888334312)、[Behind programmer](https://x.com/karpathy/status/2004607146781278521) 等多条

→ [SKILL.md](./karpathy-meta-reflection/SKILL.md)


---

### 🚀 想法到上线（开发者）

```
idea-files → agentic-engineering → minimalism → supply-chain-hygiene → vibe-to-agentic
```

| 阶段 | Skill | 产出 |
|------|-------|------|
| 想清楚 | idea-files | 想法文件（背景/目标/约束） |
| 工程化 | agentic-engineering | 增量 diff + 测试 |
| 瘦身 | minimalism | 砍依赖、纯化架构 |
| 安全检查 | supply-chain-hygiene | 依赖审计报告 |
| 收尾 | vibe-to-agentic | 原型→生产 hardening |

### 📖 研究到发布（内容创作者）

```
autoresearch → llm-wiki → output-evolution → education-first
```

| 阶段 | Skill | 产出 |
|------|-------|------|
| 跑实验 | autoresearch | 实验结果 + 迭代日志 |
| 沉淀 | llm-wiki | 结构化知识页面 |
| 包装 | output-evolution | HTML / 幻灯片 / 报告 |
| 教学化 | education-first | nano project + 练习题 |

### ⚖️ 反偏见决策（任何人）

```
llm-simulator → understanding-first → system-prompt-learning
```

| 阶段 | Skill | 产出 |
|------|-------|------|
| 辩论 | llm-simulator | 多角色辩论记录 + 盲区清单 |
| 验证 | understanding-first | 假设分级 + 必须亲自看的部分 |
| 沉淀 | system-prompt-learning | 决策逻辑写成可复用规则 |

### 🪞 月度体检（职场人）

```
meta-reflection → understanding-first → practice-environments → education-first
```

| 阶段 | Skill | 产出 |
|------|-------|------|
| 审计 | meta-reflection | 能力萎缩 / 杠杆 / 练习清单 |
| 定位 | understanding-first | 识别理解力盲区 |
| 练习 | practice-environments | 给自己建练习环境 |
| 输出 | education-first | 把学到的写成教程 |

---

## ⚡ 触发工作流

| 工具 | 触发方式 |
|------|---------|
| **Hermes** | 使用 Bundled 功能，选择工作流入口 Skill，自动加载整条链路 |
| **Claude Code** | 显式写 Skill 链路，例如：`/karpathy-idea-files /karpathy-agentic-engineering /karpathy-minimalism /karpathy-supply-chain-hygiene /karpathy-vibe-to-agentic 用 Karpathy「想法到上线」工作流帮我…` |
| **Codex** | 对话开头说：`用 Karpathy「想法到上线」工作流帮我做这件事` |
| **OpenClaw / OpenCode** | 直接 @ 对应 Skill，或说「用 Karpathy『想法到上线』工作流帮我做这件事」 |

---

## 📦 安装

默认只安装到 Codex / AgentSkills 目录：`~/.agents/skills`。不同 Agent 的 skills 目录不同，建议一个 Agent 一个 target 明确安装。

```bash
git clone https://github.com/LearnPrompt/andrej-karpathy-skills.git
cd andrej-karpathy-skills
bash install.sh
```

安装到指定工具：

```bash
bash install.sh --target codex
bash install.sh --target claude
bash install.sh --target openclaw
bash install.sh --target hermes
bash install.sh --target opencode
```

确实要一次性安装到所有常见目录时，再显式使用：

```bash
bash install.sh --target all
```

先预览会写入哪些目录：

```bash
bash install.sh --dry-run
```

支持的目标目录如下：

| 目标 | 安装目录 |
|------|----------|
| Codex / AgentSkills | `~/.agents/skills` |
| Codex native | `~/.codex/skills` |
| Claude Code | `~/.claude/skills` |
| OpenClaw | `~/.openclaw/skills` |
| Hermes | `~/.hermes/skills` |
| OpenCode | `~/.config/opencode/skills` 和 `~/.opencode/skills` |

安装后如果 Agent 已经在运行，重启或 reload skills 后再测试。

或单独安装某个 Skill：

```
帮我安装这个 skill：https://github.com/LearnPrompt/andrej-karpathy-skills/tree/main/<skill-name>
```

---

## 🌟 关于

灵感来源：[multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)。

我用 Grok 获取了 Karpathy 最近三年与 AI 相关的 X 帖子，又把里面反复出现的方法拆成 14 个可执行 Skill，并补了 1 个 methodology 总控路由。整理时没有只做语录收藏，而是尽量回答三个问题：什么时候该触发、Agent 应该怎么执行、做到什么程度算完成。

这版 README 保留了最初详细版的结构：每个 Skill 都有适用场景、来源推文、使用方式和交付物。它也合并了后续多 Agent 兼容性测试的结果：Codex、Hermes、OpenClaw、Claude Code 都跑过 fresh session；OpenClaw 顺序跑 4 条工作流可用，并发 4 条会 timeout；Claude Code 自然语言触发不稳，建议显式写出 `/karpathy-*` 链路。

做成一组 Skill 而不是一个超长 prompt，是因为这些方法本来就不是同一类动作：有的是工程节奏，有的是研究循环，有的是安全审计，有的是元反思。拆开后可以单独触发，也可以组合成 4 条工作流。

我自己的处理原则是：

1. **先拆成独立 Skill**：让每个 Skill 只解决一种常见任务，不让上下文膨胀成一团。
2. **再组合成工作流**：把经常连续发生的任务串起来，例如从想法文件到工程 hardening，从研究实验到可发布内容。
3. **补上人能读懂的解释**：每个 Skill 都写清楚为什么需要、适合谁、不适合谁，避免看起来像一堆 AI 自动生成的提示词。

核心理念来自 Karpathy 2023-2026 年间的公开 X 帖子和 Gist，不代表 Karpathy 本人立场。

Karpathy 官宣加入 Anthropic 后，AI 教育项目 Eureka Labs 就锁推了。我不知道他后续还会不会继续发新东西，所以想把这段时间的方法论保留下来。

---

<div align="center">

[MIT License](./LICENSE) · 自由使用 / 修改 / 再分发

Inspired by [@karpathy](https://x.com/karpathy) 

</div>
