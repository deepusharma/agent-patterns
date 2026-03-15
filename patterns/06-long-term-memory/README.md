# 06 — Long-Term Memory

**Pattern:** Persist memory across sessions using a vector store.
**Framework:** LangChain + LanceDB
**Status:** ⏳ Planned

## What This Demonstrates
An agent that stores and retrieves memories from previous sessions using
LanceDB as a local vector store — no external database required.

## When to Use
When an agent needs to recall context from prior interactions — personalised
assistants, ongoing research agents, relationship-aware workflows.

## Tradeoffs
- Local vector store keeps data private and removes cloud dependency
- Memory retrieval quality depends heavily on embedding and chunking strategy
