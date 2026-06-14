# Atlas Ledger v2.2

## Purpose
Companion to atlas-contract. Auto-invoked by its Final Audit on caught drift; also use after Post Reviews or user requests to record a mistake. Distills drift into WHEN/DON'T/INSTEAD clauses, writes to Atlas.md after confirmation.

## When to Use
# 2. When To Run

Run distillation only when a drift has been **caught**. Triggers, in order of how they usually arrive:

1. **Automatic handoff from atlas-contract (primary path).** When an `atlas-contract` **Final Audit** records one or more hard deviations (a hard Deviation Notice was raised, or an item is Violation / Partial / Unverified that should have been Complete), the contract skill invokes this distillation **immediately and without asking** — the candidate clause is proposed right after the audit, and the flow stops at the write-confirmation. The user should never have to remember to ask for the recording.
2. an `atlas-contract` **Post Review** (the user said the result was wrong / incomplete / downgraded / mocked);
3. a **Phase Check** catches the same class of error recurring;
4. the user explicitly says "record this so it doesn't happen again."

In every path, the confirm-before-write stop (Step 5) is preserved: automatic triggering changes **when distillation starts**, never **whether the user approves the write**.

Do **not** run on: clean completions; optimization requests; ordinary code review; style preferences; general takeaways. There is nothing to enforce in those.

**Honesty boundary:** it can only learn from drift that was *detected*. Drift that slipped through unnoticed leaves no entry. Do not pretend the ledger is complete.

## Expected Output
Task completed successfully.

## Dependencies
None

## Related Skills
None
