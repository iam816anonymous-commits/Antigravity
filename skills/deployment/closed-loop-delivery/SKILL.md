---
name: closed-loop-delivery
description: "Use when a coding task must be completed against explicit acceptance criteria with minimal user re-intervention across implementation, review feedback, deployment, and runtime verification."
risk: safe
source: official
date_added: "2026-06-14"
---
# Closed-Loop Delivery

## Purpose
Use when a coding task must be completed against explicit acceptance criteria with minimal user re-intervention across implementation, review feedback, deployment, and runtime verification.

## When to Use
Use this skill when:
- user gives a coding/fix task and expects end-to-end completion
- task spans code + tests + PR comments + dev deploy + runtime checks
- repeated manual prompts like "now test", "now deploy", "now re-check PR" should be avoided

Do not use this skill for:
- pure Q&A/explanations
- prod deploy requests without explicit human approval
- tasks blocked by missing secrets/account access that cannot be inferred

## Expected Output
Task completed successfully.

## Dependencies
None

## Related Skills
None
