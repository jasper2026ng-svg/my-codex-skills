---
name: first-principles-reframing
description: Reframe problems from basic facts instead of inherited assumptions. Use when the user wants to challenge conventional practice, rethink a stale solution, escape "everyone does it this way" reasoning, redesign a process from scratch, separate facts from assumptions, identify physical/economic/human constraints, or generate non-obvious alternatives before choosing a solution. Based on a narrow MVP extraction from the user's WeRead copy of "半小时讲透第一性原理（轻思维）".
---

# First Principles Reframing

Use this skill to break a problem down to basic facts, expose hidden assumptions, and rebuild a solution space from the real constraints. It is a redesign tool, not a generic explanation of "first principles."

If the raw problem is still vague, use `structured-problem-framing` first. Use this skill after there is a clear target but the current approach may be trapped by habit, analogy, inherited process, or industry convention.

Do not summarize the source book or quote long passages from it. Treat the book-derived material as method inspiration, and write in your own words.

## Workflow

1. State the current frame.
   - Name the user's current goal, current solution, and assumed constraint.
   - Separate "what we want" from "how we currently try to get it."

2. Strip away inherited assumptions.
   - List the rules, habits, benchmarks, org norms, and analogies the current approach relies on.
   - Mark each item as fact, assumption, preference, constraint, or unresolved claim.
   - Be especially skeptical of claims phrased as "this is how it is done," "people will not accept it," "we have to," or "there is no other way."

3. Identify basic facts.
   - Ask what must be true physically, economically, legally, socially, psychologically, or operationally.
   - Keep facts concrete and falsifiable.
   - If a "fact" depends on culture, incentives, data quality, or current tooling, treat it as conditional rather than universal.

4. Define the true constraints.
   - Separate hard constraints from soft constraints.
   - Hard constraints: legal rules, safety, budget ceiling, time window, required outcome, minimum human capacity.
   - Soft constraints: habits, status expectations, legacy process, fear, preference, current org design.

5. Rebuild from the facts.
   - Generate 3 to 5 alternative designs that satisfy the hard constraints.
   - Include at least one conservative redesign, one low-cost experiment, and one uncomfortable but plausible redesign.
   - Avoid novelty for its own sake; prefer designs that remove unnecessary assumptions.

6. Compare with the current approach.
   - Show what the current approach protects.
   - Show what it unnecessarily preserves.
   - Name the tradeoff of each new option.

7. Convert to a test.
   - Pick the smallest experiment that could falsify the key assumption.
   - Define success, failure, and the decision after the test.

## Output Format

Use this structure unless the user asks for another format:

```markdown
**Current Frame**
- Goal:
- Current approach:
- Stated constraint:
- Suspected inherited assumption:

**Assumption Strip-Down**
| Claim | Type | Keep / challenge | Why |
|---|---|---|---|

**Basic Facts**
1. Fact:
2. Fact:
3. Fact:

**True Constraints**
- Hard constraints:
- Soft constraints:
- Unknowns:

**Rebuilt Options**
| Option | What it changes | Constraint it satisfies | Tradeoff |
|---|---|---|---|

**Smallest Test**
- Assumption to test:
- Test:
- Success signal:
- Failure signal:
- Decision after test:

**One-Sentence Reframe**
```

## Quality Bar

A good output should:

- challenge assumptions without becoming contrarian theater;
- distinguish facts, constraints, preferences, and inherited habits;
- avoid treating "from scratch" as permission to ignore people, culture, or execution limits;
- generate alternatives that could realistically be tested;
- state what evidence would change the recommendation;
- fit the user's real context, especially HRBP, sales management, organization, team meetings, learning systems, and emerging-market execution constraints when relevant.

## When Not To Use

Do not use this skill when:

- the user only needs quick execution;
- the problem is already well-defined and the solution is obvious;
- safety, legal, or compliance rules should not be challenged;
- the team needs alignment on known choices rather than fundamental redesign;
- there is not enough time to test a new frame.

## Source Notes

For source grounding or future expansion, read `references/method-notes.md`. It records the source book, WeRead book id, relevant chapter anchors, and extraction boundaries for this MVP.
