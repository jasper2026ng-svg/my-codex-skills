---
name: decision-quality-review
description: Run a structured review before an important business, HR, strategy, product, hiring, negotiation, or personal choice. Use when the decision type, boundary conditions, objectives, options, tradeoffs, reversibility, consequence ownership, evidence, action commitments, feedback, or relevant bias risks need clarification. Preserve the user's ownership of the final choice. The process backbone comes from the effective-decision chapters of "卓有成效的管理者"; "非对称风险" calibrates consequence and accountability, while "思考，快与慢" and "好的决策" support only bias checks.
---

# Decision Quality Review

Use this skill to audit a decision before action. It helps separate the quality of the decision process from the eventual outcome, especially when intuition, emotion, group pressure, sunk cost, or framing may be distorting judgment.

Before using this skill in coaching mode, ask the user for a short initial judgment: "What decision would you make right now, and why?" Then compare that judgment with the audit. Skip this only when the user explicitly wants direct execution.

Use `structured-problem-framing` first if the decision question is unclear. Use `critical-questioning` when the main task is to challenge a claim or argument. Use `first-principles-reframing` when inherited assumptions may be blocking new options. Use `pyramid-communication` after this skill to write a decision memo.

Do not summarize the source book or quote long passages from it. Treat the book-derived material as method inspiration, and write in your own words.

## Source Contract

Treat this as a practical decision review, not a universal decision-science protocol. Drucker supports deciding whether a decision is needed, distinguishing recurring from exceptional issues, defining boundary conditions, seeking disagreement, deciding the right answer before compromise, converting decisions into action, and checking results through feedback. Risk asymmetry, option comparison, pre-mortem, and the integrated output remain a multi-source synthesis requiring real-case validation.

## Workflow

1. Decide whether a decision is needed.
   - State the exact choice being made.
   - Identify the decision owner, deadline, reversibility, stakes, and affected people.
   - Separate the decision from the surrounding complaint, emotion, or narrative.
   - Ask whether action is necessary now, whether continued inaction will worsen the situation, or whether a significant opportunity will be lost.
   - Classify the issue as recurring/generic, recurring in a new form, or genuinely exceptional. Recurring issues usually need a rule or principle, not repeated case-by-case judgment.

2. Define boundary conditions, objectives, and criteria.
   - State what a good outcome must achieve.
   - Separate must-have boundary conditions from preferences.
   - Name the 3 to 5 criteria that should drive the choice before scoring options.
   - State which condition would make an otherwise attractive option unacceptable.

3. Capture the current leaning.
   - Ask what the user would choose now.
   - Ask for the main reason, strongest evidence, and biggest fear.
   - Treat this as a baseline for comparison, not as a final answer.

4. Clarify the decision frame.
   - Identify how the options are being presented.
   - Check whether the frame hides alternatives, forces a false binary, or makes one option emotionally easier.
   - Reframe the decision in at least two neutral ways.

5. Find the right answer before acceptable compromise.
   - List viable options, including "do nothing", "delay", "small experiment", and "hybrid" when relevant.
   - Compare options on objective, upside, downside, reversibility, evidence required, opportunity cost, and implementation burden.
   - Avoid evaluating only the favored option.
   - First state what the best answer would be if acceptance politics were temporarily set aside.
   - Then distinguish necessary compromise from a compromise that violates a boundary condition.

6. Check consequence asymmetry and accountability.
   - Who has decision authority?
   - Who receives the upside and who bears the downside?
   - Does the recommender or decision maker have meaningful exposure to failure consequences?
   - Is a small error recoverable, or can downside compound or become irreversible?
   - Prefer reversible experiments when uncertainty is high and downside can be contained.

7. Audit relevant bias risks.
   - Select only the 2 to 4 bias risks that have observable signals in this decision; do not diagnose every bias by default.
   - Confirmation bias: Is the user mainly collecting support for the current belief?
   - Sunk cost / endowment: Is the user protecting past investment, identity, or ownership?
   - Survivorship bias: Is the user learning only from visible winners?
   - Fundamental attribution error: Is the user over-blaming character or attitude instead of context?
   - Group pressure: Is consensus replacing independent judgment?
   - Framing effect: Would a different wording change the decision?
   - Overconfidence: What might the user not know that matters?

8. Test evidence and disagreement.
   - Separate facts, interpretations, assumptions, anecdotes, and missing evidence.
   - Identify disconfirming evidence that would change the decision.
   - Ask what base rate, comparison group, or failed case is missing.
   - Seek a serious alternative interpretation or dissenting view before commitment.

9. Run a pre-mortem and action check.
   - Imagine the decision failed after implementation.
   - Name the most likely failure causes.
   - Decide which risks can be reduced before commitment.
   - Convert the decision into named actions, owners, deadlines, and communication.
   - Define feedback that will show whether the assumptions and boundary conditions remain valid.

10. Recommend a decision posture.
   - If evidence is strong and stakes are manageable, recommend acting.
   - If uncertainty is high but the decision is reversible, recommend a small experiment.
   - If uncertainty is high and the decision is hard to reverse, recommend delaying for specific evidence or redesigning options.
   - If the decision is mostly driven by bias, recommend reframing before choosing.

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Initial Judgment Check**
- Current leaning:
- Main reason:
- Biggest fear:
- What changed after audit:

**Decision Definition**
- Decision:
- Decision needed now:
- Recurring / new-form / exceptional:
- Owner:
- Deadline:
- Stakes:
- Reversibility:

**Objectives And Criteria**
- Must achieve:
- Boundary conditions:
- Decision criteria:

**Frame Check**
- Current frame:
- Hidden assumption:
- Possible false binary:
- Neutral reframe:

**Option Comparison**
| Option | Upside | Downside | Reversibility | Evidence needed | Opportunity cost |
|---|---|---|---|---|---|

**Consequence And Accountability**
- Decision authority:
- Who benefits:
- Who bears downside:
- Reversibility / ruin risk:
- Accountability gap:

**Relevant Bias Audit**
| Bias risk | Observable signal | How to test it |
|---|---|---|

**Evidence Quality**
- Facts:
- Interpretations:
- Assumptions:
- Missing evidence:
- Disconfirming evidence:

**Pre-Mortem**
- If this fails, likely causes:
- Early warning signals:
- Risk reduction steps:

**Action And Feedback**
- Action owner:
- First action and deadline:
- Who must understand the decision:
- Feedback signal:
- Revisit condition:

**Decision Posture**
- Recommended posture:
- Why:
- Smallest next step:
- Stop / revisit condition:
```

## Quality Bar

A good output should:

- make the actual decision explicit;
- determine whether a new decision is needed and whether the issue calls for a general rule;
- compare more than one option;
- define boundary conditions, objectives, and decision criteria before comparing options;
- distinguish the right answer from an acceptable compromise;
- check whether authority, upside, and downside are misaligned;
- reveal how wording or framing may be shaping the choice;
- audit only the 2 to 4 bias risks with observable signals;
- distinguish facts from assumptions and interpretations;
- include evidence that could change the recommendation;
- identify whether to act, experiment, delay, or reframe;
- preserve the user's responsibility for final judgment instead of pretending the agent can decide for them.

## When Not To Use

Do not use this skill when:

- the user only needs a generic pros-and-cons list for a low-stakes choice;
- the decision is already legally, ethically, or policy constrained and requires expert review;
- the user needs emotional support more than decision analysis;
- the problem is not yet a decision and should first be framed with `structured-problem-framing`;
- the user wants to challenge a written argument rather than audit a choice, where `critical-questioning` is better.

## Source Notes

For source grounding and skill boundaries, read `references/method-notes.md` and `references/source-audit-20260716.md`. The audit explains the new source hierarchy and which workflow elements remain Agent synthesis.
