# langGraph

Hands-on experiments learning [LangGraph](https://github.com/langchain-ai/langgraph) — building agentic AI workflows in Python.

## What's here

`src/langgraph_tutorial/`

- `main.py` — tool-calling agent: GPT-4o-mini bound with tools (Tavily web search + a custom `triple` tool)
- `nodes.py` — graph node definitions
- `react.py` — ReAct-style agent experiments

## Setup

Requires Python 3.12 and [uv](https://docs.astral.sh/uv/).

```bash
uv sync
```

Create a `.env` file with your keys (loaded via `python-dotenv`):

```
OPENAI_API_KEY=...
TAVILY_API_KEY=...
```
