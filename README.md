# 🚀 Learning LangGraph

Welcome to **Learning LangGraph**!

This repository documents my journey of learning **LangGraph** from scratch. I'll be sharing all the notebooks, code examples, and mini-projects I build while exploring LangGraph and agentic AI workflows.

The goal of this repository is to serve as both my personal learning journal and a resource for anyone who wants to get started with LangGraph.

---

## 📚 What You'll Find

This repository will cover topics including:

- Understanding LangGraph
- Defining State using `TypedDict`
- Creating Nodes
- Adding Edges
- Conditional Routing
- Building and Compiling a `StateGraph`
- Multi-Agent Systems
- Agent Communication
- Tool Calling
- Memory and Checkpointing
- Human-in-the-Loop Workflows
- Building Real-World AI Agents
- End-to-End LangGraph Projects

Each topic will include:

- 📓 Jupyter Notebook
- 💻 Well-commented code
- 📝 Explanations
- 🧪 Small experiments to understand concepts

---

## 📂 Repository Structure

```text
learning-langgraph/
│
├── Part-01-StateGraph-Basics/
├── Part-02-Conditional-Routing/
├── Part-03-Multi-Agent-Systems/
├── Part-04-Tool-Calling/
├── Part-05-Memory/
├── Part-06-Projects/
└── README.md
```

---

## ✅ Current Progress

### Part 1 – Understanding StateGraph

Topics covered:

- Defining the State
- Creating Nodes
- Adding Edges
- Conditional Edges
- Router Functions
- Compiling the StateGraph
- Executing the Graph
- Understanding State Updates

---

## 🚀 Mini Projects

### 📧 Email Router Agent

A simple LangGraph-based workflow that:

- Reads customer emails
- Classifies emails into **Sales** or **Billing**
- Routes the email to the appropriate department using conditional edges.

**Concepts Practiced**

- StateGraph
- Conditional Routing
- Router Functions
- Node Communication
- Graph Execution

---

### 📦 Order Status Agent (Tool Calling)

A LangGraph-powered AI agent that uses **tool calling** to inspect customer orders and answer order-related queries.

**Features**

- Accepts natural language order queries from users.
- Uses LangGraph's **ToolNode** to invoke tools.
- Retrieves order details using a custom order lookup tool.
- Returns order information such as:
  - Order Status
  - Product Name
  - Delivery Status
  - Estimated Delivery Date
- Demonstrates the complete **LLM → Tool → LLM** execution cycle.

**Concepts Practiced**

- Tool Calling
- ToolNode
- Conditional Edges
- AIMessage Tool Calls
- LangChain Tools
- State Updates
- Agentic Workflows

---

### 🧠 Chatbot with Short-Term Memory

A conversational AI chatbot built using LangGraph that demonstrates **short-term memory** through checkpointing.

**Features**

- Maintains conversation history across multiple user interactions.
- Stores the graph state after each execution using LangGraph checkpoints.
- Retrieves the latest checkpoint automatically using the same `thread_id`.
- Remembers information shared earlier in the conversation.
- Successfully tested by asking the chatbot to remember a user's name and later answer the question:
  - **"What is my name?"**

**Concepts Practiced**

- Short-Term Memory
- Checkpointing
- SqliteSaver
- Thread-based Conversations
- State Persistence
- Message History
- System Messages
- Conversational AI
- LangGraph Memory

---

## 🛠 Tech Stack

- Python
- LangGraph
- LangChain
- Google Gemini / OpenAI Compatible APIs
- Hugging Face
- SQLite
- Jupyter Notebook

---

## 🎯 Goal

By the end of this repository, I aim to build production-ready AI agents using LangGraph, including:

- Customer Support Agents
- Research Agents
- Multi-Agent Systems
- RAG Pipelines
- Autonomous AI Workflows

---

## ⭐ Contributing

This repository is primarily for learning and experimentation. Suggestions, improvements, and discussions are always welcome!

If you find this repository helpful, consider giving it a ⭐.

---

## 📌 Follow My Journey

I'll continue updating this repository as I learn more about LangGraph and build increasingly advanced agentic AI systems.

Happy Learning! 🚀