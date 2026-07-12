---
name: decision-quality-review
description: Review decision quality before committing to an important business, HR, strategy, product, hiring, investment, negotiation, or personal choice. Use when the user has a proposed decision, multiple options, a favored option, a stuck tradeoff, pressure to follow the group, sunk-cost concerns, framing concerns, confirmation bias risk, or wants a pre-mortem, option comparison, evidence check, bias audit, or decision memo. Based on an MVP extraction from the user's WeRead copy of "好的决策" by 夏栋.
---

# Decision Quality Review

Use this skill to audit a decision before action. It helps separate the quality of the decision process from the eventual outcome, especially when intuition, emotion, group pressure, sunk cost, or framing may be distorting judgment.

Before using this skill in coaching mode, ask the user for a short initial judgment: "What decision would you make right now, and why?" Then compare that judgment with the audit. Skip this only when the user explicitly wants direct execution.

Use `structured-problem-framing` first if the decision question is unclear. Use `critical-questioning` when the main task is to challenge a claim or argument. Use `first-principles-reframing` when inherited assumptions may be blocking new options. Use `pyramid-communication` after this skill to write a decision memo.

Do not summarize the source book or quote long passages from it. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. Define the decision.
   - State the exact choice being made.
   - Identify the decision owner, deadline, reversibility, stakes, and affected people.
   - Separate the decision from the surrounding complaint, emotion, or narrative.

2. Capture the current leaning.
   - Ask what the user would choose now.
   - Ask for the main reason, strongest evidence, and biggest fear.
   - Treat this as a baseline for comparison, not as a final answer.

3. Clarify the decision frame.
   - Identify how the options are being presented.
   - Check whether the frame hides alternatives, forces a false binary, or makes one option emotionally easier.
   - Reframe the decision in at least two neutral ways.

4. Expand and compare options.
   - List viable options, including "do nothing", "delay", "small experiment", and "hybrid" when relevant.
   - Compare options on objective, upside, downside, reversibility, evidence required, opportunity cost, and implementation burden.
   - Avoid evaluating only the favored option.

5. Audit common bias risks.
   - Confirmation bias: Is the user mainly collecting support for the current belief?
   - Sunk cost / endowment: Is the user protecting past investment, identity, or ownership?
   - Survivorship bias: Is the user learning only from visible winners?
   - Fundamental attribution error: Is the user over-blaming character or attitude instead of context?
   - Group pressure: Is consensus replacing independent judgment?
   - Framing effect: Would a different wording change the decision?
   - Overconfidence: What might the user not know that matters?

6. Test the evidence.
   - Separate facts, interpretations, assumptions, anecdotes, and missing evidence.
   - Identify disconfirming evidence that would change the decision.
   - Ask what base rate, comparison group, or failed case is missing.

7. Run a pre-mortem.
   - Imagine the decision failed after implementation.
   - Name the most likely failure causes.
   - Decide which risks can be reduced before commitment.

8. Recommend a decision posture.
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
- Owner:
- Deadline:
- Stakes:
- Reversibility:

**Frame Check**
- Current frame:
- Hidden assumption:
- Possible false binary:
- Neutral reframe:

**Option Comparison**
| Option | Upside | Downside | Reversibility | Evidence needed | Opportunity cost |
|---|---|---|---|---|---|

**Bias Audit**
| Bias risk | Signal | How to test it |
|---|---|---|
| Confirmation bias | | |
| Sunk cost / endowment | | |
| Survivorship bias | | |
| Attribution error | | |
| Group pressure | | |
| Framing effect | | |

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

**Decision Posture**
- Recommended posture:
- Why:
- Smallest next step:
- Stop / revisit condition:
```

## Quality Bar

A good output should:

- make the actual decision explicit;
- compare more than one option;
- reveal how wording or framing may be shaping the choice;
- name at least three relevant bias risks;
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

For source grounding and skill boundaries, read `references/method-notes.md`. It records the source book, WeRead book id, reading state, chapter anchors, extraction boundaries, and the Human Learning Card link.
