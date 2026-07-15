---
name: real-problem-discovery
description: Discover the real problem or true need behind a vague symptom, complaint, request, proposed solution, stakeholder demand, user feedback, business pain, HR issue, meeting problem, product request, or operational friction. Use before structured-problem-framing when the issue may be misnamed, solution-shaped, owned by the wrong person, based on assumptions, or missing the user's real scenario and need. Based on an MVP extraction from the user's WeRead copies of "你的灯亮着吗：如何找到真问题" and "以用户为中心".
---

# Real Problem Discovery

Use this skill before solving, decomposing, or designing a solution. Its job is to prevent the agent and user from solving the wrong problem.

Before using this skill in coaching mode, ask the user for a short initial judgment: "What do you currently think the real problem is?" Then compare that judgment with the discovery output. Skip this only when the user explicitly wants direct execution.

Use `structured-problem-framing` after this skill once the real problem is clear enough to decompose. Use `critical-questioning` when the suspected problem rests on weak evidence. Use `hrbp-business-diagnosis` or `effective-manager-operating-system` when the discovered problem sits in HRBP, organization, or management rhythm.

Do not summarize the source books or quote long passages from them. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. Capture the raw signal.
   - State the exact symptom, complaint, request, or proposed solution.
   - Separate what was observed from what was interpreted.
   - Identify who raised it and who feels the pain.

2. Strip solution-shaped framing.
   - Detect when the input already assumes a solution, such as "we need a dashboard", "we need training", "we need a meeting system", or "people need to change".
   - Convert it back into a problem question.
   - Ask: If this solution were forbidden, what problem would still need attention?

3. Identify problem owners and affected users.
   - Name the person or group experiencing the problem.
   - Name the person or group responsible for solving or owning it.
   - Check whether the requester, user, owner, and beneficiary are different people.
   - Ask whether this is the user's problem, the manager's problem, the organization's problem, or the agent's inferred problem.

4. Locate the scenario and job.
   - Ask who is trying to do what, in what context, under what constraint.
   - Identify current workaround, friction, delay, risk, emotional cost, and business cost.
   - Avoid abstract needs without a real situation.

5. Generate alternative problem statements.
   - Produce at least 3 possible versions of the real problem.
   - Vary the level: individual behavior, role clarity, process, incentive, information flow, capability, system, business priority, or customer need.
   - Include one uncomfortable but plausible interpretation.

6. Test whether the problem is real.
   - Ask what would happen if nothing changed.
   - Ask who would notice and what metric, behavior, or decision would be affected.
   - Check whether there is enough pain, frequency, cost, or strategic relevance to justify action.
   - If the problem is interesting but not worth solving now, say so.

7. Test whether the problem is actionable.
   - Check whether the user has influence over any variable.
   - Separate hard-to-verify human motivation claims from observable system variables.
   - Prefer action cuts that are observable, changeable, and reviewable.

8. Decide the next thinking step.
   - If the real problem is clear, hand off to `structured-problem-framing`.
   - If evidence is weak, hand off to `critical-questioning`.
   - If it is a management rhythm issue, hand off to `effective-manager-operating-system`.
   - If it is an HRBP/organization issue, hand off to `hrbp-business-diagnosis`.
   - If it is not worth solving now, recommend stopping or watching.

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Initial Judgment Check**
- User's current real-problem guess:
- Skill's working view:
- What changed:

**Raw Signal**
- Symptom / request / proposed solution:
- Observed facts:
- Interpretations:
- Who raised it:
- Who feels the pain:

**Problem Owner And User**
- Requester:
- Affected user:
- Owner:
- Beneficiary:
- Possible mismatch:

**Scenario And Need**
- Who:
- Situation:
- Job to be done:
- Current workaround:
- Friction / cost:
- Constraint:

**Alternative Problem Statements**
1. 
2. 
3. 

**Reality Test**
- What happens if nothing changes:
- Evidence that pain is real:
- Evidence missing:
- Is it worth solving now:

**Actionability Test**
- Hard-to-verify human explanation:
- Observable system variable:
- What the user can influence:
- First small check:

**Recommended Next Step**
- Best current problem statement:
- Confidence:
- Next skill / action:
```

## Quality Bar

A good output should:

- prevent premature solution design;
- distinguish symptom, interpretation, request, and real problem;
- identify whose problem it is;
- anchor needs in real scenarios and constraints;
- generate multiple plausible problem statements;
- prefer observable and changeable variables over hard-to-verify motivation claims;
- say when a problem is not worth solving now;
- hand off cleanly to the next Thinking Map step.

## When Not To Use

Do not use this skill when:

- the problem is already clearly defined and only needs decomposition;
- the user needs a finished communication draft;
- the task is a narrow execution request with low ambiguity;
- the user already has strong evidence and needs decision review, not discovery;
- legal, medical, financial, or safety-critical issues require professional standards or current external sources.

## Source Notes

For source grounding and skill boundaries, read `references/method-notes.md`. It records the source books, WeRead book ids, reading states, chapter anchors, extraction boundaries, and the Human Learning Card link.
