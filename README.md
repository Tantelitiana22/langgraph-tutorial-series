# Agent Framework with LangGraph

A collection of Jupyter notebooks demonstrating agent patterns using LangGraph, from basic agents to multi-agent systems with tools.

## Requirements

To run this project, you need the following:

### Python

- Python 3.9 or higher

### Python packages

Install all dependencies with:

```bash
uv pip install -r requirements.txt
```

Or manually install the main packages:

```bash
uv pip install langchain langchain-core langchain-groq langchain-experimental langgraph tavily-python langchain-tavily python-dotenv requests langsmith
```

### Notebook usage

- Jupyter Notebook or compatible environment (VS Code recommended)

### API Keys

Set the following API keys in a `.env` file at the project root:

```bash
# Required for LLM
GROQ_API_KEY=your_groq_api_key_here

# Required for web search tool
TAVILY_API_KEY=your_tavily_api_key_here

# Optional: LangSmith for tracing and debugging
LANGCHAIN_TRACING_V2=true
LANGCHAIN_API_KEY=your_langsmith_api_key_here
LANGCHAIN_PROJECT=your_project_name
```

### Other

- Internet access for external API calls (weather, currency, search, etc.)

## How to run

1. Install dependencies
2. Add your API keys to `.env`
3. Open and run the notebooks in order for examples and usage
