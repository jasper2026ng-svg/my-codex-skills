# Method Notes

## Source

- Primary source: 《学会提问（原书第11版）》
- Authors: 尼尔·布朗, 斯图尔特·基利
- WeRead bookId: `25614397`
- User reading state at extraction: about 35% progress
- User notes available at extraction: 19 highlights, 0 personal reviews
- Extraction date: 2026-07-12

This is an MVP skill. Treat the book as a source of method structure, not as a fully validated personal operating method. Do not quote the book at length.

## Relevant Chapter Anchors

The skill is grounded in the book's critical-questioning sequence:

- benefits and method of asking better questions
- obstacles to critical thinking
- identifying issue and conclusion
- identifying reasons
- clarifying ambiguous words
- surfacing value assumptions and descriptive assumptions
- detecting reasoning fallacies
- evaluating evidence quality
- evaluating observation, research, and analogy
- checking alternative causes
- checking whether data may mislead
- identifying omitted information
- deciding what conclusions are reasonable

## Skill Boundary

This skill answers:

- Is this claim or proposal well supported?
- What assumptions does it depend on?
- What evidence is strong or weak?
- What alternative explanations exist?
- What questions should be asked before acting?

This skill does not answer:

- What is the best decomposition of a vague problem? Use `structured-problem-framing`.
- How would we redesign the system from basic facts? Use `first-principles-reframing`.
- How should a final executive presentation be written? Use a communication skill such as a future `pyramid-communication`.

## Collaboration With Existing Skills

### Before `critical-questioning`

Use `structured-problem-framing` first when the user provides only a messy symptom, such as:

- "Meetings are inefficient."
- "Sales performance is bad."
- "The team lacks ownership."

The output of framing should produce the issue, decision question, hypotheses, and evidence needs. Then use this skill to stress-test the hypotheses and reasoning.

### After `critical-questioning`

Use `first-principles-reframing` after this skill when the audit shows that the current solution is trapped by habit, inherited process, or untested constraints.

Example chain:

```text
structured-problem-framing
-> critical-questioning
-> first-principles-reframing
```

### Standalone Use

Use this skill directly when the user already has a concrete argument, proposal, or conclusion:

- "Review this proposal before I send it."
- "What questions should I ask in this meeting?"
- "Does this diagnosis make sense?"
- "Is this KPI conclusion supported by the data?"

## Output Discipline

Keep the review practical:

- Do not produce a long classroom explanation of fallacies.
- Do not nitpick every possible wording problem.
- Prioritize questions that could change a decision.
- For workplace contexts, phrase challenges so the user can ask them without embarrassing others.
- Use confidence levels: high, medium, low, or not enough evidence.

## Common Failure Modes

- Becoming adversarial instead of curious.
- Treating every weak argument as false.
- Confusing "missing evidence" with "wrong conclusion."
- Over-focusing on abstract logic while ignoring incentives, politics, culture, and execution.
- Asking too many questions without ranking which ones matter most.
- Failing to distinguish value disagreements from factual disagreements.
