---
name: real-problem-discovery
description: Construct a better provisional problem definition or need behind a vague symptom, complaint, request, proposed solution, stakeholder demand, user feedback, business pain, HR issue, meeting problem, product request, or operational friction. Use before structured-problem-framing when the issue may be misnamed, solution-shaped, owned by the wrong person, based on assumptions, or missing the affected person's real scenario, expected state, and cost. In the first pass, classify the raw signal, identify the stakeholder gap, give at least three provisional definitions, select one working definition, recommend only one evidence check, and stop before solution design. Based on an early, multi-source extraction anchored in "你的灯亮着吗：如何找到真问题".
---

# Real Problem Discovery

## Purpose

Reduce the risk of solving the wrong problem. Produce a better working problem definition based on current evidence; do not claim to have found a single, final, essential, or fully proven "real problem."

Treat a problem as a meaningful gap, for a specific stakeholder, between the current condition they perceive and the condition they expect or need.

## Mandatory First-Pass Contract

In the first response:

1. Stay in discovery. Do not design a full solution, intervention, experiment, action plan, KPI system, meeting redesign, training program, or HR process.
2. Separate observed facts, factual claims needing verification, interpretations, cause guesses, and proposed solutions.
3. State the stakeholder's perceived current condition, desired condition, and meaningful gap.
4. Produce at least three provisional problem definitions.
5. Select one best working definition with a confidence level and say what could change it.
6. Recommend no more than one small evidence check.
7. Stop and hand off to the next Skill. Do not execute the downstream Skill in the same response unless the user explicitly asks.

In coaching mode, first ask the user: "What do you currently think the problem is?" Skip this only when the user explicitly wants direct execution.

## Workflow

1. Classify the raw signal.
   - Preserve the exact complaint, symptom, request, or proposed solution.
   - Label what is directly observed and what still needs verification.
   - Label interpretations, cause guesses, and solution-shaped language.
   - Ask: if the proposed solution were forbidden, what gap would still matter?

2. Identify the stakeholder and perceived gap.
   - Who raised the issue?
   - Who directly experiences the consequence?
   - What current condition do they perceive?
   - What condition do they expect or need?
   - What consequence makes the gap worth attention?

3. Check ownership and willingness.
   - Distinguish requester, affected person, owner, solver, and beneficiary.
   - Ask whether the affected person and decision owner actually want the gap reduced.
   - Ask who benefits if the current condition remains unchanged.
   - Do not take over a problem that another person can and should own.

4. Generate provisional problem definitions.
   - Produce at least three formulations that vary stakeholder, scope, or level.
   - Write each as a gap and consequence, not as an unproven cause or preferred solution.
   - Include one uncomfortable but plausible formulation when relevant.
   - Treat every formulation as provisional.

5. Compare the definitions.
   - Which definition is most directly supported by current evidence?
   - Which matters enough to act on?
   - Which is within the user's legitimate influence?
   - Which avoids hard-to-verify motivation labels?
   - Which proposed solution might create a new problem?

6. Select a working definition.
   - Choose the most useful current formulation, not the deepest-sounding one.
   - State confidence as high, medium, or low.
   - State what missing evidence could materially change it.

7. Route the next step.
   - Use `structured-problem-framing` when the working definition is clear enough to decompose.
   - Use `critical-questioning` when a key claim or causal explanation needs evidence review.
   - Use `hrbp-business-diagnosis` for HRBP or organization diagnosis after the problem is accepted.
   - Use `effective-manager-operating-system` for management rhythm redesign after the problem is accepted.
   - Stop or watch when the gap is not worth solving now.

## Required Output Format

Use this exact structure in the first pass unless the user explicitly asks for another format:

```markdown
**原始信号分类**
- 已观察事实：
- 待核实的事实性陈述：
- 解释或原因猜测：
- 已提出的方案：

**谁的什么差距**
- 提出者：
- 直接承受影响的人：
- 感知到的当前状态：
- 期望状态：
- 差距造成的影响：

**三个暂定问题定义**
1.
2.
3.

**当前工作定义**
- 最值得先处理的定义：
- 选择理由：
- 置信度：
- 什么证据会改变它：

**只做一个最小检查**
- 检查：
- 定义被接受后的下一 Skill：
```

## Quality Bar

A good first-pass output must:

- distinguish the signal from its interpretation and proposed solution;
- identify a specific stakeholder and meaningful gap;
- provide at least three provisional definitions;
- avoid presenting one plausible cause as a diagnosis;
- avoid words such as "root cause," "essence," or "the real problem is" unless unusually strong evidence exists;
- state uncertainty and what could change the working definition;
- propose only one evidence check;
- stop before solution design.

## When Not To Use

Do not use this Skill when:

- the problem is already clearly defined and only needs decomposition;
- the user needs a finished communication draft;
- the task is narrow execution with low ambiguity;
- strong evidence already exists and the user needs decision review rather than discovery;
- legal, medical, financial, or safety-critical issues require current professional standards.

## Source Notes

Read `references/method-notes.md` for source grounding and boundaries. Read `references/source-audit-20260716.md` before making source-fidelity or maturity claims.
