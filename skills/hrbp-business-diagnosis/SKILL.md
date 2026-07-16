---
name: hrbp-business-diagnosis
description: Translate an accepted HR or organization problem into the business outcome, strategic requirement, required organization capability, competing capability-mindset-governance hypotheses, and evidence needs before designing an intervention. Use for talent, performance, staffing, morale, retention, manager, incentive, and execution issues when enough business context exists. In the first pass, diagnose and stop; design an HRBP intervention only after the user accepts the working diagnosis. Anchored in "业务为本" and "组织能力的杨三角", with "组织诊断" used only as a model and evidence reference.
---

# HRBP Business Diagnosis

Use this skill first to diagnose an HR or organization symptom from the business context. Propose a focused HRBP intervention only in a second pass after the user accepts or revises the working diagnosis.

## Two-Pass Contract

1. **Diagnosis pass:** complete business translation, context, competing organization hypotheses, evidence gaps, and one minimum check. Do not design a full HR program.
2. **Intervention pass:** continue only after the user accepts or revises the working diagnosis. Then choose one or two focused levers, owners, success signals, and risks.

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

3. Derive the required organization capability.
   - State the strategic or operating priority the business must deliver.
   - Ask what the organization must be consistently good at to deliver it: speed, customer intimacy, channel execution, innovation, cost discipline, cross-functional coordination, local adaptation, talent replication, or another specific capability.
   - Describe the observable behaviors and operating outcomes that would demonstrate this capability.
   - Do not start with an HR module or a generic list of competencies.

4. Diagnose the capability gap with one primary model.
   - Ability: do we have and develop the required skills, experience, and talent density?
   - Mindset and motivation: do people want to behave in the required way, and do incentives, consequences, identity, and leadership signals reinforce it?
   - Governance and environment: do structure, roles, decision rights, process, information, tools, resources, and manager cadence allow it?
   - Use people / role / system only as a practical sub-check within these three dimensions.
   - Do not stack the Yang triangle, six boxes, 7S, BLM, and other models in one diagnosis. Choose one primary lens and use another only if a specific blind spot remains.

5. Test evidence.
   - Identify what evidence exists and what is missing.
   - Check three evidence layers: business outcomes, organization mechanisms, and people signals.
   - Useful evidence may include revenue or productivity movement, execution cycle time, customer impact, decision delays, workflow and role data, manager interviews, employee behavior, performance distribution, hiring funnel, workload, incentives, and attrition.
   - Treat anecdotes as signals, not proof.

6. Stop and confirm the working diagnosis.
   - State the best current diagnosis and confidence.
   - State what evidence could change it.
   - Recommend only one minimum check.

7. Choose HRBP leverage after confirmation.
   - Match the intervention to the diagnosis.
   - Possible levers: role clarity, manager coaching, talent review, hiring profile, onboarding, performance mechanism, incentive adjustment, capability building, communication, org design, succession, retention, or meeting/operating rhythm.
   - Prefer one or two high-leverage interventions over a broad HR program.

8. Design the smallest useful intervention.
   - Define target population, owner, timeline, success signal, risk, and business-facing language.
   - Include what HRBP will do, what business manager must do, and what should not be owned by HR alone.

9. Produce the recommendation.
   - Start with the business problem.
   - Show the organization diagnosis.
   - Recommend focused HRBP action.
   - End with the manager decision or support needed.

## First-Pass Output Format

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

**Strategy And Required Capability**
- Strategic / operating priority:
- Required organization capability:
- Observable behavior and operating result:

**Competing Diagnosis Hypotheses**
| Hypothesis | Current signal | Evidence needed | What would weaken it |
|---|---|---|---|

**Capability Gap Split**
- Ability:
- Mindset / motivation:
- Governance / environment:
- People / role / system sub-check:
- Risk of misdiagnosis:

**Current Working Diagnosis**
- Diagnosis:
- Confidence:
- What could change it:

**One Minimum Check**
- Check:
- Continue to intervention design only after:
```

For the second pass, add focused leverage options, the selected intervention, HRBP role, business manager role, timeline, success signal, and risk.

## Quality Bar

A good output should:

- translate HR language into business language;
- derive organization capability from a specific business priority;
- resist jumping from symptom to HR program;
- distinguish ability, mindset, and governance while preserving people-role-system detail;
- use one primary diagnostic model instead of stacking frameworks;
- name what evidence would change the diagnosis;
- stop after diagnosis in the first pass;
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

For source grounding and skill boundaries, read `references/method-notes.md` and `references/source-audit-20260716.md`. The audit records the source hierarchy, the limited role of the organization-diagnosis model catalog, and which parts of the workflow remain Agent synthesis.
