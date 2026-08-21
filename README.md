# Agentic-Ai
A collection of Agentic AI projects built using LangChain, LangGraph, LLMs, RAG, vector databases, and tool-using AI agents. Includes experiments and practical implementations of autonomous agents, multi-agent workflows, retrieval-augmented generation, memory, and LLM-powered applications.
# 🤖 Agentic AI Projects

A collection of **Agentic AI and Generative AI projects** built to explore and implement modern LLM-based architectures using **LangChain, LangGraph, RAG, LLMs, Vector Databases, Tool Calling, Memory, and AI Agents**.

This repository contains multiple practical projects, experiments, and implementations focused on building intelligent systems that can **reason, retrieve information, use tools, maintain context, and execute multi-step workflows**.

---

## 🚀 What This Repository Covers

The projects in this repository cover a wide range of Agentic AI concepts:

* 🤖 AI Agents
* 🧠 Large Language Models (LLMs)
* 🔗 LangChain
* 🔄 LangGraph
* 📚 Retrieval-Augmented Generation (RAG)
* 🗃️ Vector Databases
* 🔍 Semantic Search
* 🛠️ Tool Calling
* 🧩 Multi-Agent Systems
* 💾 AI Memory
* 🔄 Agent Workflows
* 📄 Document Question Answering
* 🧠 Context-Aware AI Applications
* ⚡ LLM-powered applications

---

## 🏗️ Repository Structure

```text
Agentic-AI-Projects/
│
├── LangChain/
│   ├── project-1/
│   ├── project-2/
│   └── ...
│
├── LangGraph/
│   ├── project-1/
│   ├── project-2/
│   └── ...
│
├── RAG/
│   ├── project-1/
│   ├── project-2/
│   └── ...
│
├── AI-Agents/
│   ├── project-1/
│   ├── project-2/
│   └── ...
│
├── LLM-Applications/
│   ├── project-1/
│   ├── project-2/
│   └── ...
│
└── README.md
```

> The structure may evolve as new projects and experiments are added.

---

# 🧠 Technologies & Tools

### LLM & Generative AI

* OpenAI
* Groq
* Ollama
* Hugging Face
* Mistral
* Claude
* Other LLM APIs

### Agentic AI

* AI Agents
* Tool Calling
* Function Calling
* Agent Workflows
* Multi-Agent Systems
* Planning & Reasoning
* Agent Memory

### Frameworks

* LangChain
* LangGraph
* LangSmith

### RAG

* Document Loaders
* Text Splitting
* Embeddings
* Semantic Search
* Retrieval
* Context Injection
* RAG Pipelines

### Vector Databases

* FAISS
* Chroma
* Pinecone
* Other vector stores

### Development

* Python
* FastAPI
* Streamlit
* REST APIs
* Git & GitHub

---

# 🔗 LangChain Projects

Projects in this section focus on building applications using **LangChain components and abstractions**.

Typical concepts include:

* LLM integration
* Prompt templates
* Chains
* LCEL
* Output parsers
* Document loaders
* Retrievers
* Embeddings
* Agents
* Tools
* Memory
* Structured outputs

---

# 🔄 LangGraph Projects

LangGraph projects focus on **stateful and controllable agent workflows**.

Concepts explored include:

* Graph-based workflows
* Nodes & edges
* State management
* Conditional routing
* Agent loops
* Tool execution
* Human-in-the-loop workflows
* Multi-agent architectures
* Persistent state
* Complex decision-making workflows

Example architecture:

```text
            ┌──────────────┐
            │    User      │
            └──────┬───────┘
                   │
                   ▼
            ┌──────────────┐
            │   Agent      │
            └──────┬───────┘
                   │
             ┌─────┴─────┐
             ▼           ▼
        ┌─────────┐  ┌─────────┐
        │  Tool   │  │  RAG    │
        └────┬────┘  └────┬────┘
             │            │
             └─────┬──────┘
                   ▼
            ┌──────────────┐
            │   Response   │
            └──────────────┘
```

---

# 📚 RAG Projects

The RAG projects focus on connecting LLMs with external knowledge sources.

Typical pipeline:

```text
Documents
    │
    ▼
Document Loader
    │
    ▼
Text Splitting
    │
    ▼
Embeddings
    │
    ▼
Vector Database
    │
    ▼
Retriever
    │
    ▼
Relevant Context
    │
    ▼
LLM
    │
    ▼
Final Answer
```

These projects explore:

* PDF RAG
* Document Q&A
* Semantic search
* YouTube/content-based RAG
* Vector similarity search
* Embedding models
* Retrieval strategies
* Context-aware generation

---

# 🤖 AI Agent Projects

Agent projects focus on creating systems that can **decide what action to take instead of simply generating a response**.

An agent can:

```text
User Query
     │
     ▼
   LLM
     │
     ▼
Decide Action
     │
 ┌───┴────────┐
 ▼            ▼
Tool         RAG
 │            │
 └─────┬──────┘
       ▼
   Observation
       │
       ▼
     LLM
       │
       ▼
Final Response
```

Concepts include:

* Tool-using agents
* ReAct-style reasoning
* Function calling
* Web/search tools
* Custom tools
* Agent memory
* Autonomous workflows
* Multi-agent collaboration

---

# 🧩 Multi-Agent Systems

Some projects explore architectures where multiple specialized agents work together.

Example:

```text
                 User
                  │
                  ▼
            ┌───────────┐
            │ Supervisor│
            └─────┬─────┘
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
   Researcher   Coder    Analyst
        │         │         │
        └─────────┼─────────┘
                  ▼
            Final Response
```

Each agent can have a specific role, tools, instructions, and responsibilities.

---

# 💾 AI Memory

The repository also explores ways to make AI applications more context-aware by maintaining information across interactions.

Possible approaches include:

* Conversation memory
* Short-term memory
* Long-term memory
* Vector-based memory
* User-specific context
* Persistent agent state

---

# 🛠️ Example Agent Architecture

A typical project in this repository may follow an architecture like:

```text
                    User
                     │
                     ▼
              ┌─────────────┐
              │   Frontend  │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   Backend   │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │    Agent    │
              └──────┬──────┘
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
       LLM        Tools        RAG
          │          │          │
          └──────────┼──────────┘
                     ▼
              ┌─────────────┐
              │   Memory    │
              └──────┬──────┘
                     │
                     ▼
              Final Response
```

---

# 🎯 Goals of This Repository

The main goal of this repository is to understand and implement **real-world Agentic AI architectures** rather than only building simple chatbot applications.

The projects focus on:

* Understanding how LLM applications work internally
* Building autonomous AI agents
* Designing stateful workflows
* Connecting LLMs with external tools
* Implementing RAG systems
* Working with vector databases
* Building multi-agent workflows
* Exploring AI memory
* Experimenting with different LLM providers
* Developing production-oriented AI applications

---

# 📈 Learning Progression

The projects generally follow this progression:

```text
LLM
 │
 ▼
Prompt Engineering
 │
 ▼
LangChain
 │
 ▼
RAG
 │
 ▼
Tools & Function Calling
 │
 ▼
AI Agents
 │
 ▼
LangGraph
 │
 ▼
Memory
 │
 ▼
Multi-Agent Systems
 │
 ▼
Advanced Agentic AI
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/Agentic-AI-Projects.git
```

Navigate into the project:

```bash
cd Agentic-AI-Projects
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies for the required project:

```bash
pip install -r requirements.txt
```

---

# 🔐 Environment Variables

Some projects require API keys.

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key
GROQ_API_KEY=your_api_key
LANGCHAIN_API_KEY=your_api_key
HUGGINGFACE_API_KEY=your_api_key
```

Never commit API keys, passwords, tokens, or other secrets to GitHub.

---

# ▶️ Running Projects

Each project may have its own setup instructions.

For example:

```bash
cd RAG/project-name
pip install -r requirements.txt
streamlit run app.py
```

or:

```bash
python main.py
```

Refer to the individual project's README for project-specific instructions.

---

# 📂 Projects

| Project   | Category       | Technologies          |
| --------- | -------------- | --------------------- |
| Project 1 | RAG            | LangChain, LLM, FAISS |
| Project 2 | Agent          | LangChain, Tools, LLM |
| Project 3 | Agent Workflow | LangGraph, LLM        |
| Project 4 | RAG            | Embeddings, Vector DB |
| Project 5 | Multi-Agent    | LangGraph, LLM        |
| Project 6 | LLM App        | LangChain, Streamlit  |

> This table will be updated as more projects are added.

---

# 🔬 Concepts Explored

```text
LLMs
├── Prompt Engineering
├── Structured Output
├── Function Calling
└── Model Integration

LangChain
├── Chains
├── Agents
├── Tools
├── Retrievers
└── Memory

RAG
├── Embeddings
├── Vector Stores
├── Retrieval
├── Context
└── Generation

LangGraph
├── State
├── Nodes
├── Edges
├── Conditional Routing
├── Loops
└── Multi-Agent Workflows
```

---

# 🚀 Future Improvements

Planned additions include:

* Advanced multi-agent systems
* Long-term agent memory
* More complex LangGraph workflows
* MCP-based tool integration
* Production-ready RAG pipelines
* Agent evaluation
* LLM observability
* Advanced retrieval techniques
* Agent deployment
* More autonomous AI systems

---

# 📚 Purpose

This repository serves as a **learning, experimentation, and portfolio collection** for modern Agentic AI development.

The focus is on understanding how individual components such as **LLMs, RAG, tools, memory, LangChain, and LangGraph** can be combined to build intelligent and autonomous AI systems.

---

## 👨‍💻 Author

**Tanish Rajput**

Exploring **AI/ML, Generative AI, Agentic AI, LLMs, RAG, LangChain, and LangGraph**.

---

## ⭐ Support

If you find this repository useful, consider giving it a ⭐ on GitHub.

More Agentic AI projects will be added as the repository evolves.
