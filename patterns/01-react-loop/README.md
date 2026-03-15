# 01 — ReAct Loop

**Pattern:** Think → Act → Observe cycle with tool use.
**Framework:** LangChain / LangGraph
**Status:** 🔧 In Progress

## What This Demonstrates
An agent that reasons about a problem, selects a tool, observes the result,
and loops until it reaches an answer — built from scratch first, then in LangGraph.

## When to Use
When you need an agent that can use tools iteratively to solve a problem
that requires multiple steps.

## Tradeoffs
- Simple to reason about but can loop indefinitely without exit conditions
- Framework version adds memory and streaming with minimal extra code
