# agent-patterns

A library of enterprise Agentic AI design patterns. Each pattern is a 
standalone, runnable Python example with its own README explaining when 
to use it, the tradeoffs, and how to adapt it for production.

Built from scratch first, then with frameworks — so the code explains 
itself.

---

## Patterns

| # | Pattern | Framework | Status |
|---|---|---|---|
| 01 | [ReAct Loop](patterns/01-react-loop/) | LangChain / LangGraph | 🔧 In Progress |
| 02 | [Multi-Agent Handoff](patterns/02-multi-agent-handoff/) | CrewAI | ⏳ Planned |
| 03 | [Human in the Loop](patterns/03-human-in-loop/) | LangGraph | ⏳ Planned |
| 04 | [Parallel Execution](patterns/04-parallel-execution/) | LangGraph | ⏳ Planned |
| 05 | [Tool Use with Error Recovery](patterns/05-tool-use-error-recovery/) | LangGraph | ⏳ Planned |
| 06 | [Long-Term Memory](patterns/06-long-term-memory/) | LangChain + LanceDB | ⏳ Planned |

---

## Structure

Each pattern folder contains:
- `README.md` — what the pattern is, when to use it, tradeoffs
- `scratch/` — raw implementation without frameworks
- `framework/` — same pattern using the relevant framework
- `requirements.txt` — dependencies

---

## Why Scratch First

Every pattern starts with a raw Python implementation before introducing 
a framework. This makes the framework's abstractions explicit rather than 
assumed — and makes the code easier to debug, adapt, and explain.

---

## Prerequisites

- Python 3.11+
- API key from [Groq](https://console.groq.com) (free tier) 
  or [OpenRouter](https://openrouter.ai) (free models available)
- Recommended models:
  - Groq: `llama-3.3-70b-versatile` (fast, free)
  - OpenRouter: `meta-llama/llama-3.3-70b-instruct` (free tier)
- Each pattern has its own `requirements.txt`

- 

