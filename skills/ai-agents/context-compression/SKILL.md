---
name: context-compression
description: "When agent sessions generate millions of tokens of conversation history, compression becomes mandatory. The naive approach is aggressive compression to minimize tokens per request."
risk: safe
source: official
date_added: "2026-06-14"
---
# Context Compression Strategies

## Purpose
When agent sessions generate millions of tokens of conversation history, compression becomes mandatory. The naive approach is aggressive compression to minimize tokens per request.

## When to Use
Activate this skill when:
- Agent sessions exceed context window limits
- Codebases exceed context windows (5M+ token systems)
- Designing conversation summarization strategies
- Debugging cases where agents "forget" what files they modified
- Building evaluation frameworks for compression quality

## Expected Output
Task completed successfully.

## Dependencies
None

## Related Skills
None
