# LangGraph Python – Agentic AI Learning Repository

A hands-on Python learning repository focused on **LangGraph, stateful AI workflows, RAG, tool calling, and Agentic AI systems**.

This repository contains practical implementations and experiments exploring how to build, control, and orchestrate LLM-powered workflows using LangGraph.

## 🎯 Learning Objectives

- Understand LangGraph architecture and workflow execution.
- Build stateful applications using StateGraph.
- Understand nodes, edges, and graph compilation.
- Implement sequential, parallel, and conditional workflows.
- Manage shared state and reducers.
- Integrate LLMs and external tools.
- Build RAG applications using LangGraph.
- Implement human-in-the-loop workflows.
- Develop iterative AI agents with feedback loops.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| LangGraph | Stateful AI workflow orchestration |
| LangChain | LLM application framework |
| OpenAI | LLM integration |
| Groq | LLM integration |
| Hugging Face | Embedding models |
| FAISS | Vector database |
| Tavily | Web search integration |
| Streamlit | Interactive application interface |
| PyPDF | PDF document processing |
| Python Dotenv | Environment variable management |

## 📚 Topics Covered

### 1. LangGraph Fundamentals
- Introduction to LangGraph
- LangGraph Architecture
- StateGraph
- Nodes and Edges
- START and END
- Graph Compilation
- Graph Execution
- Graph Invocation

### 2. State Management
- TypedDict
- Pydantic Models
- Python Dataclasses
- MessagesState
- State Updates
- Annotated Types
- Reducers
- add_messages

### 3. Sequential Workflows
- Sequential Graph Execution
- Connecting Multiple Nodes
- Workflow Orchestration
- State Passing Between Nodes
- Multi-Step LLM Workflows

### 4. Conditional Workflows
- Conditional Edges
- Routing Functions
- Dynamic Execution Paths
- Query Classification
- Decision-Based Routing

### 5. Parallel Execution and Reducers
- Parallel Node Execution
- Concurrent Workflow Paths
- Reducers
- State Aggregation
- Combining Parallel Results

### 6. RAG with LangGraph
- Retrieval-Augmented Generation
- PDF Document Loading
- PyPDFLoader
- RecursiveCharacterTextSplitter
- Hugging Face Embeddings
- FAISS Vector Store
- Similarity Search
- Context Retrieval
- Conditional RAG
- Query Classification
- Context-Aware Answer Generation

### 7. Tools and Tool Calling
- Tool Integration
- ToolNode
- Tool Binding
- Tool Execution
- Tavily Search
- LLM Tool Selection
- Tool-Based Workflows

### 8. Human-in-the-Loop
- Human Approval
- Human Feedback
- Interrupt
- Command
- Workflow Pausing
- Workflow Resumption
- Checkpointing
- MemorySaver

### 9. Iterative AI Agents
- Writer Agent
- Reviewer Agent
- Feedback Generation
- Iterative Execution
- Conditional Loops
- Agent Collaboration
- Approval and Rejection Workflows
- Maximum Retry Handling

### 10. Application Development
- Streamlit Integration
- Interactive AI Applications
- LangGraph-Based Chatbots
- Document-Based Question Answering
- LLM-Powered Assistants

## 📁 Repository Structure

```text
langgraph-python/
│
├── states.py
├── sequential_base.py
├── parallel_reducers.py
├── conditional_RAG.py
├── humanintheloop.py
├── iterative_tools.py
├── app.py
│
├── academics_handbook.pdf
├── fee_structure.pdf
│
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

*The structure represents the current learning examples. Update it as you add more implementations.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/langgraph-python.git
cd langgraph-python
```

### 2. Create Virtual Environment

Windows PowerShell:

```powershell
python -m venv .venv
```

Activate:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory.

```env
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Add only the API keys required by the examples you want to execute.

Never upload your actual `.env` file or API keys to GitHub.

### 5. Run Python Examples

Run individual implementations:

```powershell
python states.py
python sequential_base.py
python parallel_reducers.py
python conditional_RAG.py
python humanintheloop.py
python iterative_tools.py
```

For the Streamlit application, install Streamlit if required:

```powershell
pip install streamlit
```

Then run:

```powershell
streamlit run app.py
```

Some examples require additional packages or API keys depending on their imports.

## 🚀 Practical Implementations

| Implementation | Description |
|---|---|
| State Management | Understanding and updating graph state |
| Sequential Workflow | Connecting multiple LLM processing nodes |
| Parallel Workflow | Executing independent workflow branches |
| Conditional RAG | Routing queries to relevant document retrievers |
| Human-in-the-Loop | Pausing execution for human approval and feedback |
| Iterative Agent | Writer and reviewer agents with feedback loops |
| College Assistant | PDF-based academic and fee question-answering application |

## 📈 Learning Progress

- [ ] LangGraph Fundamentals
- [ ] State Management
- [ ] Nodes and Edges
- [ ] Sequential Workflows
- [ ] Conditional Workflows
- [ ] Parallel Execution
- [ ] Reducers
- [ ] RAG with LangGraph
- [ ] Tool Calling
- [ ] Human-in-the-Loop
- [ ] Checkpointing and Persistence
- [ ] Iterative AI Agents
- [ ] Multi-Agent Workflows
- [ ] End-to-End Agentic AI Projects

## 🎓 Learning Approach

Each concept is explored through:

1. Understanding the underlying concept.
2. Implementing the workflow using Python.
3. Building graphs with LangGraph.
4. Running and testing implementations.
5. Understanding practical use cases.

## 🎯 Future Learning Goals

- Advanced Multi-Agent Systems
- Supervisor and Hierarchical Agents
- Agentic RAG
- Long-Term Memory
- Advanced Checkpointing
- MCP Integration
- Production-Ready Agent Workflows
- Agent Evaluation and Observability

## 👨‍💻 Author

**Keshvi Solanki**

GitHub: [keshviSolanki](https://github.com/keshviSolanki)

---

**Repository Focus:** Python | LangGraph | LangChain | RAG | AI Agents | Agentic AI
