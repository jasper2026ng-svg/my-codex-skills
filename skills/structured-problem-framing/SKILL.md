---
name: structured-problem-framing
description: Structure messy business, strategy, HRBP, sales, product, or operations questions before solving them. Use when the user asks to define a problem, cut or decompose an issue, build a logic tree, apply MECE-style thinking, generate hypotheses, check reasoning traps, prioritize options, or turn a vague concern into a clear decision and validation plan. Based on a small MVP extraction from the user's WeRead copy of "麦肯锡结构化战略思维".
---

# Structured Problem Framing

Use this skill to turn an unclear business question into a clear problem frame, issue structure, hypotheses, and validation plan. It is an early-stage thinking tool: use it before proposing solutions.

Do not summarize the source book or quote long passages from it. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. Restate the raw question.
   - Identify the decision owner, target outcome, deadline, scope, and current symptom.
   - If these are missing, infer a reasonable default and label it as an assumption.

2. Define the problem before solving it.
   - Convert the raw concern into one decision question.
   - Separate symptom, suspected cause, desired outcome, and constraint.
   - Reject solution-shaped framing such as "How do we implement X?" when the real question may be "What problem should X solve?"

3. Generate multiple ways to cut the problem.
   - Create at least two alternative decomposition angles for ambiguous or high-stakes problems.
   - Common cuts: process steps, stakeholder groups, metric tree, internal vs external, controllable vs uncontrollable, time horizon, customer journey, geography, product line, organization layer.
   - Choose the cut that best exposes action, evidence needs, and tradeoffs.

4. Build the working issue tree.
   - Use 3 to 6 top-level branches unless the problem clearly needs fewer or more.
   - Make branches meaningfully distinct, but do not become rigid about textbook MECE if the real work needs overlap notes.
   - Push each branch one level deeper until it suggests evidence to check or an action to test.

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

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Problem Frame**
- Raw question:
- Better decision question:
- Scope:
- Assumptions:

**Issue Structure**
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
- avoid jumping to actions too early;
- show at least two plausible ways to decompose a messy issue;
- make hypotheses testable;
- name what evidence would change the answer;
- use plain business language rather than consultant theater;
- fit the user's actual operating context, especially HRBP, sales, organization, and emerging-market execution constraints when relevant.

## Source Notes

For source grounding or future expansion, read `references/method-notes.md`. It records the book, WeRead book id, relevant chapters, and the method extraction boundaries for this MVP.
