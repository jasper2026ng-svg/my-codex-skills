# Method Notes

## Sources

Source quality and provenance were re-audited on 2026-07-16. Read `source-audit-20260716.md` for the uneven quality and reading coverage across the source set.

Primary source:

- 《业务为本：华为和阿里的HRBP价值创造三层十二式》
- Author: 襄阳郭丹
- WeRead bookId: `44027161`
- User reading state at extraction: about 25% progress
- User notes available at extraction: 18 highlights

Supporting sources:

- 《人力资源量化管理与数据分析》
- Author: 任康磊
- WeRead bookId: `25916823`
- User reading state at extraction: about 99% progress
- User notes available at extraction: 11 highlights

- 《人力资源管理新逻辑：人人都是HR》
- Author: 谢山
- WeRead bookId: `27011392`
- User reading state at extraction: about 90% progress
- User notes available at extraction: 5 highlights

Organization capability source:

- 《组织能力的杨三角：企业持续成功的秘诀 第3版》, bookId `3300161461`, reading state about 3%, 0 highlights

Light structural reference:

- 《HRBP是这样炼成的之中级修炼》, bookId `25081273`, reading state 0%

Model and evidence reference:

- 《组织诊断：企业健康的衡量方法、模型与实践》, bookId `3300019623`, reading state about 99%, 44 highlights
- The book has high personal relevance but weak public quality signals: 24 ratings with more poor than good ratings, and repeated complaints about model compilation and shallow logic. Use it as a catalog and checklist, not as a final authority.

Extraction date: 2026-07-12

This is an MVP skill. Treat the sources as method anchors, not a complete HRBP doctrine. Do not quote the books at length.

## Method Anchors

From business-first HRBP:

- HRBP should come from the business and return to the business.
- Business understanding is the premise of HR solutions.
- Business translation is the key step between business pain and HR work.
- HR should help improve human capital competitiveness and business success.

From HR data analysis:

- HR evidence should support diagnosis, but HR data alone rarely "saves" the business.
- Staffing, attrition, performance, talent pipeline, training, compensation, and employee relations can be quantified.
- Data should be used to test hypotheses, not decorate HR opinions.

From HR as shared management responsibility:

- Line managers own much of people management.
- HRBP should not replace managers' responsibilities.
- Capabilities are inferred from observable behavior, not abstract claims.

From organization capability thinking:

- Derive the required organization capability from the business strategy or operating priority.
- Diagnose employee ability, employee mindset/motivation, and governance/environment.
- Translate each dimension into observable behavior and mechanisms.
- Organization issues often sit across talent, structure, process, incentive, culture, and leadership behavior.

From organization diagnosis references:

- Choose a model based on the question; do not stack multiple models by default.
- Use business, organization-mechanism, and people evidence together.
- Treat surveys and model scores as signals requiring interpretation, not as diagnoses by themselves.

## Skill Boundary

This skill answers:

- What business problem sits behind an HR symptom?
- Is this mainly a people, role, system, manager, or incentive issue?
- What evidence should HRBP check before recommending action?
- Which HRBP intervention is likely to create business value?
- What should HRBP own, and what must the business manager own?

This skill does not answer:

- Legal or labor dispute handling.
- Policy-specific employee relations procedure.
- Full compensation design.
- Detailed statistical modeling.
- Final executive communication wording. Use `pyramid-communication`.

## Collaboration With Existing Skills

Typical chain:

```text
structured-problem-framing
-> hrbp-business-diagnosis
-> critical-questioning
-> pyramid-communication
```

Use this when an HRBP issue needs to become a business-facing recommendation.

For management rhythm issues:

```text
effective-manager-operating-system
-> hrbp-business-diagnosis
```

Use this when the HR symptom may be caused by manager cadence, meeting design, decision rights, or delegation.

## Human Learning Link

Pair this skill with:

```text
human-cards/hrbp-business-diagnosis.md
```

The card is for the user's own learning: translating HR symptoms into business diagnosis, separating people/role/system causes, and preserving business ownership.

## Common Failure Modes

- Jumping from HR symptom to HR program.
- Treating business managers as clients only, instead of co-owners.
- Blaming attitude, culture, or capability before checking system design.
- Using HR data without a business hypothesis.
- Designing broad initiatives when one focused intervention would do.
- Producing HR language that business leaders cannot act on.
