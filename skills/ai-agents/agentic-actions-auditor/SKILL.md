---
name: agentic-actions-auditor
description: "Audits GitHub Actions workflows for security vulnerabilities in AI agent integrations including Claude Code Action, Gemini CLI, OpenAI Codex, and GitHub AI Inference. Detects attack vectors where attacker-controlled input reaches. AI agents running i"
risk: safe
source: official
date_added: "2026-06-14"
---
# Agentic Actions Auditor

## Purpose
Audits GitHub Actions workflows for security vulnerabilities in AI agent integrations  including Claude Code Action,  Gemini CLI, OpenAI Codex, and GitHub AI  Inference.  Detects attack vectors where attacker-controlled  input reaches. AI agents running in CI/CD pipelines.


## When to Use
- Auditing a repository's GitHub Actions workflows for AI agent security
- Reviewing CI/CD configurations that invoke Claude Code Action, Gemini CLI, or OpenAI Codex
- Checking whether attacker-controlled input can reach AI agent prompts
- Evaluating agentic action configurations (sandbox settings, tool permissions, user allowlists)
- Assessing trigger events that expose workflows to external input (`pull_request_target`, `issue_comment`, etc.)
- Investigating data flow from GitHub event context through `env:` blocks to AI prompt fields

## Expected Output
Task completed successfully.

## Dependencies
None

## Related Skills
None
