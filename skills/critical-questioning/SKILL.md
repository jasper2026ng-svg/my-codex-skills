---
name: critical-questioning
description: Audit arguments, claims, proposals, diagnoses, meeting conclusions, HRBP recommendations, strategy choices, and business narratives by testing the issue, conclusion, reasons, assumptions, ambiguous terms, evidence quality, causal logic, missing information, alternative explanations, and reasonable confidence level. Use when the user wants to challenge an argument or turn an opinion into a better-tested judgment. By default, prioritize the 3 to 5 questions most likely to change the decision. Based on an audited, high-fit extraction from "学会提问（原书第11版）".
---

# Critical Questioning

Use this skill to test whether a claim, diagnosis, proposal, or conclusion is well supported. It is a reasoning quality-control tool, not a debate tool. Keep the tone curious and constructive.

## Default Practical Mode

Do not mechanically run the full textbook checklist. Unless the user asks for a comprehensive audit, prioritize the 3 to 5 questions most likely to change an important decision. State what is supported, what remains a hypothesis, and the smallest useful evidence check.

If the problem itself is still vague, use `structured-problem-framing` first. If the user wants to redesign from basic constraints after the argument is challenged, use `first-principles-reframing` after this skill.

Do not summarize the source book or quote long passages from it. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. Identify the argument.
   - State the issue being discussed.
   - Extract the main conclusion.
   - List the explicit reasons or evidence offered.
   - If the user provides only a symptom or opinion, turn it into a testable claim first.

2. Clarify ambiguous terms.
   - Flag abstract or emotionally loaded terms such as "efficient," "high potential," "poor attitude," "strategic," "low performance," "alignment," "ownership," or "culture."
   - Ask what observable behavior, metric, threshold, or example would make each term concrete.

3. Expose assumptions.
   - Separate value assumptions from descriptive assumptions.
   - Value assumptions: what the argument treats as important or desirable.
   - Descriptive assumptions: what the argument assumes is true about people, markets, incentives, processes, data, or cause and effect.

4. Test evidence quality.
   - Classify evidence as data, observation, example, expert opinion, analogy, survey, experiment, benchmark, or personal experience.
   - Check sample size, source reliability, comparison group, recency, selection bias, and whether the evidence actually supports the conclusion.
   - Treat vivid stories as useful signals, not proof.

5. Check logic and causality.
   - Look for false cause, correlation treated as causation, false dichotomy, circular reasoning, slippery slope, straw man, overgeneralization, survivorship bias, base-rate neglect, and metric substitution.
   - If a conclusion is plausible but under-supported, keep it as a hypothesis.

6. Generate alternative explanations.
   - Name at least 2 to 4 other causes or interpretations that could explain the same facts.
   - Include one uncomfortable explanation if relevant, such as incentive mismatch, leadership behavior, unclear ownership, data quality, or hidden tradeoffs.

7. Identify missing information.
   - Ask what information would most change the judgment.
   - Distinguish critical missing information from nice-to-have information.
   - Prefer checks that can be completed quickly in the user's real operating context.

8. Give a confidence-rated judgment.
   - Do not simply say "right" or "wrong."
   - State what is well supported, what is weak, what remains unknown, and what should be tested next.
   - End with the best questions to ask before acting.

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Argument Map**
- Issue:
- Main conclusion:
- Stated reasons:
- Implied recommendation:

**Term Clarity**
| Term | Why it is unclear | Concrete definition needed |
|---|---|---|

**Assumptions**
| Assumption | Type | Risk if false | How to test |
|---|---|---|---|

**Evidence Check**
| Evidence | Strength | Weakness | What it can / cannot prove |
|---|---|---|---|

**Logic Trap Audit**
- Strongest logic risk:
- Causal risk:
- Missing comparison:
- Possible bias:

**Alternative Explanations**
1. 
2. 
3. 

**Missing Information**
- Must know before deciding:
- Useful but not required:

**Confidence-Rated Judgment**
- What is well supported:
- What is still only a hypothesis:
- Confidence level:
- Next questions to ask:
```

For a practical first pass, compress the same logic into:

```markdown
**当前判断**
- 结论：
- 置信度：
- 最薄弱的依据：

**最重要的三个问题**
1.
2.
3.

**一个最小检查**
```

## Quality Bar

A good output should:

- separate conclusion, reasons, evidence, and assumptions;
- turn vague language into observable criteria;
- challenge reasoning without sounding combative;
- preserve useful ideas as hypotheses instead of dismissing them;
- avoid overclaiming from anecdotes, authority, or isolated metrics;
- identify alternative explanations before recommending action;
- fit the user's real context, especially HRBP, sales, management meetings, organization diagnosis, and emerging-market execution constraints when relevant.

## When Not To Use

Do not use this skill when:

- the user needs quick execution rather than reasoning review;
- the claim is already low stakes and obvious;
- the user mainly needs creative ideation;
- the problem frame is missing and should first be clarified;
- legal, medical, financial, or safety-critical claims require current external sources and professional standards before judgment.

## Source Notes

For source grounding and skill boundaries, read `references/method-notes.md` and `references/source-audit-20260716.md`. The audit records the strong book-to-task fit and the remaining risk of checklist overload.
