# 02 — Multi-Agent Handoff

**Pattern:** Agent A delegates to specialist Agent B with context passing.
**Framework:** CrewAI
**Status:** ⏳ Planned

## What This Demonstrates
A manager agent that breaks down a task and routes sub-tasks to specialist
agents, passing context between them cleanly.

## When to Use
When a task has distinct specialist domains that benefit from focused agents
rather than one generalist agent.

## Tradeoffs
- More legible than a single complex agent
- Harder to debug when handoff context is lost between agents
