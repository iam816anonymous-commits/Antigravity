# Atlas Contract v6.2

## Purpose
Goal-integrity skill. Use for backend/API/persistence, preserve/do-not-change, tests/validation, mocks, rework, multi-part requests. Emits Goal Contracts, Deviation Notices, Phase Checks, Final Audits. Skip for Q&A or trivial edits.

## When to Use
# 2. When To Use Atlas, and How Much

First decide **whether** Atlas applies, then **how heavily**.

Do not use Atlas at all for: simple factual answers; pure explanation; isolated typo or formatting fixes; trivial one-line edits with no behavior/scope/preservation/test/data risk; analysis-only requests with no execution.

Otherwise, classify the task by counting how many of these **risk signals** are present:

1. **Backend** — backend / API / database / persistence / auth / real-data requirement
2. **Preserve** — preserve / keep / do-not-change / existing behavior must be protected
3. **Data** — data integrity / schema / enum / shared state / dashboard statistics
4. **Tests** — tests / validation / acceptance criteria / test-weakening risk
5. **Fidelity** — reference image / screenshot / layout / structure must be matched

(A mock/stub risk is implied whenever Backend or Data is present.)

## Expected Output
Task completed successfully.

## Dependencies
None

## Related Skills
None
