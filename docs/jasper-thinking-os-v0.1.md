# Jasper Thinking OS v0.1

一个可跳转、可裁剪、以行动为导向的思考地图。

## 1. 定位

Jasper Thinking OS 不是一个新的知识库，也不是一条所有问题都必须走完的长流程。

它是 Cognitive System 里的“思考流程层”：

- Cognitive System 负责沉淀资产：书籍、想法、案例、Skill、Human Learning Card、CEA 评审、index-db。
- Thinking OS 负责指导使用：面对一个真实问题时，先判断问题处在哪个思考环节，再选择合适的 Skill。

一句话：

> Cognitive System 解决“沉淀什么”；Thinking OS 解决“现在怎么想”。

## 2. 核心原则

1. Thinking OS 是地图，不是流水线。
2. 小问题走最小闭环，大问题才展开完整链路。
3. 能用 1-2 个 Skill 解决的，不要强行走 7 个 Skill。
4. 每次都先保留人的初始判断，再让 Agent 辅助。
5. 每个环节都必须服务行动；不服务行动的分析要删掉。
6. Agent 负责步骤、整理、审查和提醒；Jasper 保留问题定义、方法选择、关键判断和最终取舍。

## 3. 最小实用闭环

大多数真实问题，先用这 5 个问题判断就够了：

| 核心问题 | 思考动作 | 可用 Skill |
|---|---|---|
| 问题到底是什么？ | 发现真问题、识别真需求、定义问题、拆解结构、识别假设 | `real-problem-discovery`, `structured-problem-framing`, `first-principles-reframing` |
| 为什么会这样？ | 诊断原因、检查证据、区分人/角色/系统 | `hrbp-business-diagnosis`, `effective-manager-operating-system`, `critical-questioning` |
| 有哪些选择？ | 生成方案、比较路径、设计小实验 | 当前偏弱，后续补充 |
| 应该怎么做？ | 决策审查、取舍、风险、停止条件 | `decision-quality-review` |
| 怎么说、怎么推进？ | 组织表达、对齐行动、推动执行 | `pyramid-communication`；执行和复盘 Skill 待补 |

## 4. 完整地图

完整地图只在复杂问题、重要决策、跨团队协作或长期项目中展开：

```text
发现真问题
-> 定义问题
-> 拆解问题
-> 提出假设
-> 收集证据
-> 诊断原因
-> 生成方案
-> 做出决策
-> 组织表达
-> 推动执行
-> 复盘学习
```

这不是固定顺序。真实工作中可以回跳：

```text
初步判断
-> 找一点证据
-> 修正问题定义
-> 重新诊断
-> 做小实验
-> 再决定是否扩大行动
```

## 5. 当前 Skill 地图

| Skill | 所在环节 | 上游 | 下游 | 不适合 |
|---|---|---|---|---|
| `real-problem-discovery` | 发现真问题、识别真需求 | 原始抱怨、现象、方案要求、用户反馈 | 问题定义、管理诊断、HRBP 诊断 | 问题已经清楚且只需要执行时 |
| `structured-problem-framing` | 定义问题、拆解问题、提出假设 | 原始现象、模糊问题 | 诊断、证据收集、表达 | 已经有清晰决策时，不必重复拆解 |
| `first-principles-reframing` | 挑战默认假设、重构方案空间 | 当前做法、惯性方案 | 方案生成、决策审查 | 普通执行问题；专业约束很强且不可挑战的问题 |
| `critical-questioning` | 审查论证、假设、证据 | 初步判断、方案、结论 | 决策审查、表达 | 用户只是需要生成想法时；不要把它当成否定工具 |
| `effective-manager-operating-system` | 管理诊断、会议、授权、节奏 | 团队效率现象、管理困境 | HRBP 诊断、决策、表达 | 法务/合规/纯 HR 政策问题 |
| `hrbp-business-diagnosis` | HRBP/组织/人才问题诊断 | HR 症状、业务压力 | 决策审查、业务建议 | 没有业务上下文；只要模板或政策文本 |
| `decision-quality-review` | 方案取舍、偏误审查、行动前检查 | 候选方案、当前倾向 | 决策 memo、行动计划 | 问题还没定义；低风险小选择 |
| `pyramid-communication` | 表达结论、组织汇报、写建议 | 已有判断或方案 | 会议沟通、汇报、推动执行 | 逻辑和证据还没想清楚时，不要先美化表达 |

## 6. 常见调用路径

### 6.1 模糊业务现象

```text
real-problem-discovery
-> structured-problem-framing
-> critical-questioning
-> decision-quality-review
-> pyramid-communication
```

适合：用户/业务/老板提出一个现象、抱怨或方案要求，但你还不确定真正问题是什么。

### 6.2 模糊业务现象

```text
structured-problem-framing
-> critical-questioning
-> decision-quality-review
-> pyramid-communication
```

适合：业绩下降、项目推进慢、组织协作乱、问题原因不清。

### 6.3 HRBP 或组织问题

```text
real-problem-discovery
-> structured-problem-framing
-> hrbp-business-diagnosis
-> critical-questioning
-> decision-quality-review
-> pyramid-communication
```

适合：离职率、士气、绩效、干部、编制、激励、组织能力问题，且问题可能被错误命名。

轻量版：

```text
structured-problem-framing
-> hrbp-business-diagnosis
-> critical-questioning
-> decision-quality-review
-> pyramid-communication
```

适合：问题已经比较清楚，只需要进入 HRBP 诊断。

### 6.4 管理者时间、会议和授权问题

```text
real-problem-discovery
-> structured-problem-framing
-> effective-manager-operating-system
-> decision-quality-review
-> pyramid-communication
```

适合：会议太多、决策慢、下属不主动、管理者被琐事拖住，且你怀疑表面现象不是真问题。

轻量版：

```text
structured-problem-framing
-> effective-manager-operating-system
-> decision-quality-review
-> pyramid-communication
```

适合：问题已经清楚是管理节奏或会议体系问题。

### 6.5 惯性方案需要重想

```text
real-problem-discovery
-> first-principles-reframing
-> structured-problem-framing
-> decision-quality-review
```

适合：大家都默认“只能这样做”，但你怀疑问题本身或解决方案前提错了。

轻量版：

```text
first-principles-reframing
-> structured-problem-framing
-> decision-quality-review
```

适合：问题已知，主要是挑战默认方案。

### 6.6 已有结论，需要表达

```text
critical-questioning
-> pyramid-communication
```

适合：你已经有判断，但需要先审一下逻辑，再写成老板能看懂的表达。

## 7. 每次使用的固定动作

在调用任何 Skill 前，先写 30 秒初始判断：

```text
我认为真正的问题是...
我现在的初步判断是...
我最不确定的是...
我希望 Agent 帮我检查的是...
```

Agent 输出后，再做对照：

```text
Agent 和我哪里一致？
哪里不同？
它补充了什么视角？
它有没有机械套模型？
我最终保留什么判断？
下一步行动是什么？
```

## 8. 何时沉淀回 Cognitive System

不是每次使用都要沉淀。满足以下条件之一时，再考虑进入 Cognitive System：

- 这次问题代表一种反复出现的工作场景。
- 某个 Skill 明显提升了判断质量。
- 某个 Skill 明显误用，需要修正规则。
- 产生了可复用案例、模板、判断标准或反例。
- 你的原始判断和 Agent 审查之间出现了有价值的差异。

沉淀路径：

```text
真实问题
-> Thinking OS 定位
-> 调用 Skill
-> 人机对照
-> 行动或决策
-> 复盘
-> CEA 判断是否入库
-> Cognitive System / Feishu / index-db
```

## 9. 当前缺口

v0.1 先承认缺口，不假装完整：

| 缺口 | 说明 | 后续可能来源 |
|---|---|---|
| 真需求 / 真问题发现 | 现在更多是定义和拆解，缺少从用户、业务、现场中发现真问题的方法 | 用户研究、访谈、产品思维、问题发现类书 |
| 证据收集与访谈 | 现在有审查证据，但缺少如何设计访谈和收集证据 | 咨询访谈、用户研究、调研方法 |
| 因果诊断 | 现在诊断偏业务经验，缺少更强因果推理 | 系统思考、因果推断、问题解决 |
| 方案生成 | 当前对“怎么产生多个好方案”覆盖不足 | 创造性问题解决、设计思维、战略选项 |
| 推动执行 | 当前表达有了，但执行推进、责任闭环、变革管理不足 | 项目管理、变革管理、执行力 |
| 复盘学习 | 当前还没有独立复盘 Skill | 复盘、AAR、学习科学 |

## 10. 使用判断

当你面对一个问题，不要先问“用哪个 Skill”。

先问：

1. 这是问题不清，还是方案不清？
2. 这是证据不足，还是取舍困难？
3. 这是业务诊断，还是表达沟通？
4. 这件事需要完整链路，还是只需要一个最小动作？

然后再选 Skill。

Thinking OS 的目标不是让流程变复杂，而是让你更快知道：

> 现在真正需要思考的是哪一步。
