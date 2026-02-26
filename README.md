# RAG to Multi-agent Evolution
Exploring the evolution of LLM system design: from simple retrieval chains to adaptive, orchestrated multi-agent workflows using LangChain, CrewAI and LangGraph.
This repository demonstrates the evolution of LLM application design, from linear retrieval pipelines to adaptive, orchestrated multi-agent systems.
The goal is to understand how AI architectures mature as complexity, reliability and production requirements increase.

## Architecture Levels
### 1️⃣ Linear RAG (LangChain)
A standard Retrieval-Augmented Generation pipeline:
- Document chunking
- Embedding generation
- Vector database storage
- Context retrieval
- LLM response generation
Workflow is fixed and linear.
Folder: `/01_linear_rag`
---

### 2️⃣ Agentic RAG
Enhances traditional RAG with decision-making agents that:
- Decompose user queries
- Decide whether/where to retrieve
- Select tools dynamically
- Evaluate and refine outputs
Workflow becomes adaptive and iterative.
Folder: `/02_agentic_rag`
---

### 3️⃣ Role-Based Multi-Agent System (CrewAI)
Implements collaborative agents with defined roles:
- Research agent
- Writer agent
- Reviewer agent
Tasks are divided and executed by specialized agents.
Folder: `/03_crewai_multi_agent`
---

### 4️⃣ Graph-Based Orchestration (LangGraph)
Models applications as a graph of nodes (agents/tools) and edges (control/data flow).
Supports:
- Branching workflows
- Conditional execution
- Stateful orchestration
- Deterministic control flow
Folder: `/04_langgraph_orchestration`
---

## Why This Matters
Modern AI systems require more than prompt engineering.
As applications scale, systems must support:
- Adaptive control flow
- Tool selection
- State management
- Multi-agent collaboration
- Structured orchestration
This repository explores that architectural progression.
---

## Technologies Used
- LangChain
- LangGraph
- CrewAI
- Vector databases
- OpenAI / LLM APIs
---

## Author
Gargi Tarania  
AI Product Leader | Agentic Systems | LLM Orchestration
