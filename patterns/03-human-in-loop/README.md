# 03 — Human in the Loop

**Pattern:** Pause workflow, get human approval, resume.
**Framework:** LangGraph
**Status:** ⏳ Planned

## What This Demonstrates
An agent that pauses at a checkpoint, surfaces its proposed action to a
human for approval, and resumes or adjusts based on the response.

## When to Use
When agent actions have real-world consequences that require human oversight
before execution — approvals, financial transactions, communications.

## Tradeoffs
- Adds latency but dramatically reduces risk in high-stakes workflows
- LangGraph's interrupt_before/after makes this clean to implement
