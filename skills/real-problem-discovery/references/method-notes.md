# Method Notes

## Sources

Primary source:

- 《你的灯亮着吗：如何找到真问题（10万册纪念版）》
- Authors: 唐纳德·C.高斯, 杰拉尔德·M.温伯格
- WeRead bookId: `44397308`
- User reading state at extraction: about 14% progress
- User notes available at extraction: 1 highlight

Supporting source:

- 《以用户为中心》
- Author: 陈峻锐
- WeRead bookId: `3300017583`
- User reading state at extraction: about 13% progress
- User notes available at extraction: 6 highlights, 1 personal review

Context source:

- 《好战略，坏战略（畅销版）》
- Author: 理查德·鲁梅尔特
- WeRead bookId: `920922`
- User reading state at extraction: about 30% progress
- User notes available at extraction: 7 highlights

Extraction date: 2026-07-14

This is an MVP skill. The user's personal highlights are sparse for the primary source, so treat this skill as a promising but early asset. Do not overclaim maturity. Do not quote the books at length.

## Why These Sources

Use 《你的灯亮着吗》 as the primary source because the Thinking Map gap is "真问题发现", and the book directly asks:

- What is the problem?
- What is this problem this time?
- What is the problem really?
- Who should solve it?
- Where does the problem come from?
- Do you really want to solve it?

Use 《以用户为中心》 as a supporting source because the gap also includes "真需求识别": user, scenario, feedback, need, and evidence.

Use 《好战略，坏战略》 only as context for the idea that good strategy starts from diagnosing the key challenge, not from slogans or scattered goals.

## Method Anchors

From real-problem thinking:

- Agreement on a solution is useless if people have not agreed on the problem.
- The named problem may not be the real problem.
- Who owns the problem matters.
- Some problems should not be solved by the person who first notices them.
- Some "problems" are created by the way they are framed.

From user-centered thinking:

- Ask who the user is, in what scenario, and what differentiated value is needed.
- Feedback should be gathered from real situations, not abstract opinions alone.
- Insight means seeing patterns behind facts, forming hypotheses, and testing them with facts.
- Exploration has diminishing returns; do enough discovery to guide action, not endless research.

From strategy diagnosis:

- Good action depends on finding the key challenge.
- Avoid hiding from painful details, tradeoffs, and focus.

## Skill Boundary

This skill answers:

- What is the real problem behind this symptom or request?
- Whose problem is it?
- Is the proposed solution hiding the actual problem?
- What real user/scenario/need should be understood first?
- Is the problem worth solving now?
- What should be checked before decomposing or solving?

This skill does not answer:

- Full user research design.
- Full strategy formulation.
- Detailed problem decomposition after the real problem is known. Use `structured-problem-framing`.
- Evidence and argument audit after a claim is formed. Use `critical-questioning`.
- Final business recommendation wording. Use `pyramid-communication`.

## Collaboration With Existing Skills

Typical chain:

```text
real-problem-discovery
-> structured-problem-framing
-> critical-questioning
-> decision-quality-review
-> pyramid-communication
```

Use this when the issue may be misnamed or solution-shaped.

For management issues:

```text
real-problem-discovery
-> effective-manager-operating-system
```

For HRBP or organization issues:

```text
real-problem-discovery
-> hrbp-business-diagnosis
```

## Human Learning Link

Pair this skill with:

```text
human-cards/real-problem-discovery.md
```

The card is for the user's own learning: pausing before solution design, separating observed facts from interpretations, identifying whose problem it is, and choosing observable action cuts.

## Common Failure Modes

- Treating a complaint as the real problem.
- Treating a proposed solution as the problem statement.
- Confusing the requester's problem with the affected user's problem.
- Over-researching when a small check would be enough.
- Turning every issue into a user research project.
- Blaming motivation, attitude, or culture before checking observable system variables.
