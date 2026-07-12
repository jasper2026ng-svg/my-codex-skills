---
name: hrbp-business-diagnosis
description: Diagnose HRBP, organization, talent, performance, staffing, morale, retention, capability, manager, incentive, and execution issues from the business context. Use when the user asks to translate HR symptoms into business problems, support a sales or operations leader, diagnose organization capability gaps, decide whether an issue is talent/structure/process/incentive/manager behavior, design an HRBP intervention, or prepare business-facing HR recommendations. Based on an MVP extraction from the user's WeRead copies of "业务为本：华为和阿里的HRBP价值创造三层十二式", "人力资源量化管理与数据分析", and related HRBP/organization books.
---

# HRBP Business Diagnosis

Use this skill to diagnose an HR or organization symptom from the business context, then propose a focused HRBP intervention that helps the business win. It should translate between business language and HR levers.

Before using this skill in coaching mode, ask the user for a short initial judgment: "What business problem do you think sits behind this HR symptom?" Then compare the user's judgment with the skill output. Skip this only when the user explicitly wants direct execution.

Use `structured-problem-framing` first if the issue is still vague. Use `critical-questioning` when the diagnosis is based on weak evidence. Use `pyramid-communication` after this skill to write the business-facing recommendation.

Do not summarize the source books or quote long passages from them. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. Translate the symptom into a business question.
   - State the raw HR symptom: turnover, low morale, weak execution, hiring difficulty, manager conflict, capability gap, performance issue, or headcount pressure.
   - Identify the business outcome affected: revenue, growth, productivity, customer experience, compliance, cost, quality, speed, or strategic transition.
   - Convert the symptom into a business-facing diagnosis question.

2. Understand the business context.
   - Clarify business model, market stage, team size, geography, sales/operations rhythm, current target, recent changes, and constraints.
   - Ask what "winning" means in this unit now.
   - Avoid HR solutions before understanding the business pressure.

3. Map the organization capability gap.
   - Diagnose whether the gap is mainly willingness, capability, opportunity, structure, process, incentive, culture, leadership behavior, or resource mismatch.
   - Check the three organization capability questions:
     - Do people want to do it?
     - Can people do it?
     - Does the system allow and reinforce it?

4. Separate people, role, and system issues.
   - People: skill, motivation, values, potential, retention risk.
   - Role: unclear expectations, wrong job design, missing decision rights, overload.
   - System: incentives, process, manager cadence, reporting line, tools, data, hiring pipeline.
   - Do not over-personalize system problems.

5. Test evidence.
   - Identify what evidence exists and what is missing.
   - Useful evidence may include attrition data, performance distribution, productivity metrics, manager interviews, employee feedback, hiring funnel, compensation position, workload, customer or sales data, and execution cycle time.
   - Treat anecdotes as signals, not proof.

6. Choose HRBP leverage.
   - Match the intervention to the diagnosis.
   - Possible levers: role clarity, manager coaching, talent review, hiring profile, onboarding, performance mechanism, incentive adjustment, capability building, communication, org design, succession, retention, or meeting/operating rhythm.
   - Prefer one or two high-leverage interventions over a broad HR program.

7. Design the smallest useful intervention.
   - Define target population, owner, timeline, success signal, risk, and business-facing language.
   - Include what HRBP will do, what business manager must do, and what should not be owned by HR alone.

8. Produce the recommendation.
   - Start with the business problem.
   - Show the organization diagnosis.
   - Recommend focused HRBP action.
   - End with the manager decision or support needed.

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Initial Judgment Check**
- User's initial business diagnosis:
- Skill's working diagnosis:
- Where they agree / differ:

**Business Translation**
- HR symptom:
- Business outcome affected:
- Better diagnosis question:

**Business Context Needed**
- What we know:
- What is missing:
- Assumptions:

**Organization Capability Diagnosis**
| Dimension | Signal | Likely gap | Evidence needed |
|---|---|---|---|
| Willingness | | | |
| Capability | | | |
| System / opportunity | | | |

**People / Role / System Split**
- People issue:
- Role issue:
- System issue:
- Risk of misdiagnosis:

**HRBP Leverage Options**
| Option | Business logic | Owner | Tradeoff |
|---|---|---|---|

**Recommended Intervention**
- Intervention:
- Target group:
- HRBP role:
- Business manager role:
- Timeline:
- Success signal:
- Risk:

**Questions Before Action**
1. 
2. 
3. 
```

## Quality Bar

A good output should:

- translate HR language into business language;
- resist jumping from symptom to HR program;
- separate people problems from system and manager problems;
- name what evidence would change the diagnosis;
- produce a focused intervention with clear business owner and HRBP owner;
- avoid treating HRBP as a service desk when business ownership is required;
- fit sales, operations, emerging-market execution, cross-cultural management, and HRBP contexts when relevant.

## When Not To Use

Do not use this skill when:

- the issue is a legal, compliance, or labor dispute requiring policy-specific handling;
- the user only needs an HR document template;
- the user lacks enough business context to diagnose beyond generic HR advice;
- the problem is purely personal coaching with no organization or business implication;
- the user needs final communication wording before diagnosis is complete.

## Source Notes

For source grounding and skill boundaries, read `references/method-notes.md`. It records the source books, WeRead book ids, reading states, chapter anchors, extraction boundaries, and the Human Learning Card link.
