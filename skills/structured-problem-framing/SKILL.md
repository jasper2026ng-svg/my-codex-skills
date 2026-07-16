---
name: structured-problem-framing
description: Turn an accepted working problem into a structured definition, decision question, suitable problem representation, hypotheses, and evidence plan before solution design. Use after real-problem-discovery when the stakeholder gap is clear enough but scope, target state, constraints, structure, or validation logic remain messy. Choose among an issue tree, process map, stakeholder map, metric tree, or causal/system map instead of forcing every problem into one format. Do not claim a unique root problem or produce the final solution in the first pass. Anchored in "麦肯锡结构化战略思维", calibrated by "系统之美" and "好战略，坏战略".
---

# Structured Problem Framing

Use this skill to turn an accepted but still messy working problem into a clear problem frame, issue structure, hypotheses, and validation plan. It is an early-stage thinking tool: use it before proposing solutions.

This Skill starts after a provisional working problem exists. If the input is still only a complaint, motivation label, or proposed solution and the affected stakeholder gap is unclear, use `real-problem-discovery` first. Use `critical-questioning` after framing when a key claim needs a deeper evidence audit.

Do not summarize the source book or quote long passages from it. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. Restate the raw question.
   - Identify the decision owner, current state, target state, meaningful gap, deadline, scope, constraints, and current symptom.
   - If these are missing, infer a reasonable default and label it as an assumption.

2. Define the problem before solving it.
   - Convert the raw concern into one decision question.
   - Separate symptom, suspected cause, desired outcome, and constraint.
   - Reject solution-shaped framing such as "How do we implement X?" when the real question may be "What problem should X solve?"

3. Choose the right problem representation.
   - Create at least two plausible representations for ambiguous or high-stakes problems.
   - Use an issue tree when the task needs categories or exhaustive coverage.
   - Use a process map when timing, handoffs, rework, queues, or ownership transitions matter.
   - Use a stakeholder map when different actors perceive different needs, incentives, or consequences.
   - Use a metric tree when the outcome can be decomposed quantitatively.
   - Use a causal or system map when feedback, delays, adaptation, circular causality, or local optimization may reproduce the problem.
   - Choose the representation that best exposes evidence needs, controllable levers, and tradeoffs.

4. Build the working structure.
   - For an issue tree, use 3 to 6 top-level branches unless the problem clearly needs fewer or more.
   - For other representations, define the minimum set of stages, actors, variables, flows, or feedback relationships needed to guide investigation.
   - Make distinctions useful rather than cosmetically MECE. Record important overlaps instead of hiding them.
   - Push the structure one level deeper until it suggests evidence to check or a decision to make.

5. Form hypotheses.
   - Generate 2 to 5 hypotheses that could explain the issue or guide action.
   - For each hypothesis, name the supporting logic, the evidence needed, and what would disprove it.
   - Prefer testable hypotheses over broad opinions.

6. Audit logic traps.
   - Check for false causality, overgeneralizing from a few examples, false dichotomy, circular reasoning, missing comparison group, base-rate neglect, survivorship bias, stakeholder blind spot, and metric substitution.
   - If the user's proposed conclusion is plausible but weakly supported, preserve it as a hypothesis rather than treating it as fact.

7. Produce the answer-first output.
   - Give the recommended problem frame first.
   - Then show decomposition, hypotheses, risks, and first validation actions.
   - End with the smallest next step that would reduce uncertainty.
   - Stop before a full solution or implementation plan unless the user explicitly asks to continue.

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Problem Frame**
- Raw question:
- Better decision question:
- Current state:
- Target state:
- Meaningful gap:
- Scope:
- Constraints:
- Assumptions:

**Chosen Problem Representation**
- Recommended representation:
- Why it fits:
- Alternative considered:
- What this representation may miss:

**Issue Structure / Map**
1. Branch:
2. Branch:
3. Branch:

**Alternative Cuts Considered**
- Cut A:
- Cut B:

**Working Hypotheses**
| Hypothesis | Why it might be true | Evidence to check | Disconfirming signal |
|---|---|---|---|

**Logic Trap Audit**
- Strongest risk:
- Weakest assumption:
- Missing comparison:
- Stakeholder blind spot:

**Next Validation**
1. First check:
2. Second check:
3. Decision after checking:

**One-Sentence Storyline**
```

## Quality Bar

A good output should:

- make the real decision sharper;
- preserve the accepted stakeholder gap instead of silently inventing a new root problem;
- avoid jumping to actions too early;
- show at least two plausible ways to represent a messy issue;
- avoid forcing a dynamic system, handoff problem, or stakeholder conflict into a static issue tree;
- make hypotheses testable;
- name what evidence would change the answer;
- use plain business language rather than consultant theater;
- fit the user's actual operating context, especially HRBP, sales, organization, and emerging-market execution constraints when relevant.

## Source Notes

For source grounding or future expansion, read `references/method-notes.md` and `references/source-audit-20260716.md`. The audit records book quality, Skill-convertibility, provenance, and current maturity limits. The representation-selection layer is a multi-source synthesis.
