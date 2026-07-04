# Multi-Agent System Using LangGraph

A modular Multi-Agent AI system built with **LangGraph** and **LangChain** that demonstrates agent orchestration, tool calling, reasoning workflows, and supervisor-based task delegation.

The project includes multiple examples ranging from simple deterministic workflows to advanced multi-agent collaboration using external tools and databases.

---

## ✨ Features

- 🤖 Supervisor-based Multi-Agent architecture
- 🧠 ReAct Agent implementation with tool calling
- 🔎 Web search integration using Tavily
- 🗄️ PostgreSQL integration via MCP Toolbox
- ⚡ LangGraph workflow orchestration
- 🛠️ Custom Python tools
- 📒 Interactive Jupyter notebooks
- 🔄 Standalone LangGraph graph for CLI execution

---

## 📁 Project Structure

```text
.
├── notebook/
│   ├── toto_generator.ipynb
│   ├── langgraph_react_agent.ipynb
│   └── langgraph_mas.ipynb
│
├── graph.py
├── tools.yaml
├── pyproject.toml
├── uv.lock
├── README.md
└── LICENSE
```

### Components

| File | Description |
|------|-------------|
| `graph.py` | Standalone Multi-Agent System graph |
| `tools.yaml` | MCP Toolbox configuration |
| `pyproject.toml` | Project dependencies |
| `notebook/` | Interactive learning examples |

---

# Technologies Used

- Python 3.10+
- LangGraph
- LangChain
- OpenRouter
- Tavily Search
- MCP Toolbox
- PostgreSQL
- uv

---

# Getting Started

## Clone Repository

```bash
git clone https://github.com/yourusername/multi-agent-system-using-langgraph.git
cd multi-agent-system-using-langgraph
```

---

## Create Virtual Environment

```bash
uv venv
```

### macOS / Linux

```bash
source .venv/bin/activate
```

### Windows

```powershell
.venv\Scripts\activate
```

---

## Install Dependencies

```bash
uv sync
```

---

## Configure MCP Toolbox

Download the appropriate Toolbox binary from the official MCP Toolbox releases.

After downloading, start the Toolbox:

```bash
./toolbox
```

The provided `tools.yaml` configuration automatically loads SQL tools and custom database utilities.

---

# Running Examples

The repository contains three notebooks.

## 1. TOTO Generator

A simple deterministic LangGraph workflow.

---

## 2. ReAct Agent

Demonstrates:

- Tool Calling
- Tavily Search
- PostgreSQL Queries
- Custom Python Tools

---

## 3. Multi-Agent System

A Supervisor coordinates multiple specialist agents including:

- SQL Agent
- Amenities Agent
- Web Research Agent

---

# Run with LangGraph

Start the development server:

```bash
langgraph dev
```

Open:

```
http://127.0.0.1:2024
```

This launches LangSmith Studio for graph visualization and debugging.

---

# Requirements

- Python 3.10+
- uv
- PostgreSQL (optional)
- Tavily API Key (optional)
- OpenRouter API Key

---

# Learning Objectives

This project demonstrates:

- Multi-Agent Systems
- Supervisor Pattern
- Agent Collaboration
- Tool Calling
- Graph-based Workflows
- Retrieval & Search
- Database Integration
- LangGraph Architecture

---

# Future Improvements

- Memory Support
- Vector Database Integration
- RAG Pipeline
- Streaming Responses
- FastAPI Backend
- Web Dashboard
- Docker Support

---

# License

This project is licensed under the MIT License.

---

## Acknowledgements

Special thanks to the open-source community and the following technologies:

- LangGraph
- LangChain
- OpenRouter
- Tavily
- MCP Toolbox

---

⭐ If you find this project useful, consider giving it a star.


## Author

Anuman Modi

GitHub: https://github.com/Anuman18

LinkedIn:
https://linkedin.com/in/anumanmodi