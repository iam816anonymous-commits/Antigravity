---
name: agent-memory-architecture
description: "A comprehensive hybrid memory system for AI agents, providing persistent, searchable knowledge management. This skill covers the entire architecture of agent memory: short-term (context window), long-term (vector stores/RAG), and persistent cognitive"
risk: safe
source: official
date_added: "2026-06-14"
---
# Agent Memory Architecture

## Purpose
A comprehensive hybrid memory system for AI agents, providing persistent, searchable knowledge management. This skill covers the entire architecture of agent memory: short-term (context window), long-term (vector stores/RAG), and persistent cognitive architectures (Architecture, Patterns, Decisions) that allow agents to remember context across sessions.

## When to Use
- Implementing persistent memory for AI agents using MCP or other systems.
- Designing long-term memory architectures using vector stores or semantic storage.
- Managing agent state and "remembering" user preferences or project decisions across sessions.
- Implementing episodic (events) or semantic (facts) memory retrieval.
- Addressing context window limitations via intelligent retrieval and summarization.

## Architecture Patterns
- **Short-term**: Managed via the immediate context window and session history.
- **Long-term**: Implemented via Vector Databases (Pinecone, Milvus, Chroma) and RAG.
- **MCP Integration**: Using Model Context Protocol for structured tool-based memory access.

## Expected Output
Persistent and searchable memory system integrated successfully into the agent architecture.

## Dependencies
None
