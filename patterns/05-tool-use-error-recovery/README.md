# 05 — Tool Use with Error Recovery

**Pattern:** Agent retries gracefully when tools fail or return bad data.
**Framework:** LangGraph
**Status:** ⏳ Planned

## What This Demonstrates
An agent that calls a tool, handles failures (bad data, timeout, rate limit),
retries with adjusted parameters, and escalates to human after N failures.

## When to Use
Any production agentic system — tool failures are inevitable at scale.
Error recovery is not optional in enterprise workflows.

## Tradeoffs
- Adds complexity but essential for production reliability
- Retry logic must avoid infinite loops — always set max retries
