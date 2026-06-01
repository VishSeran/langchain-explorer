# 🚀 Introduction to LangChain

> Build intelligent, context-aware AI applications using the LangChain ecosystem.
>
> This hands-on Jupyter Notebook explores the essential components of LangChain, guiding you from basic LLM interactions to Retrieval-Augmented Generation (RAG), multi-step chains, conversational memory, and autonomous AI agents capable of reasoning and executing code.

---

## 🌟 Why LangChain?

Large Language Models (LLMs) are powerful, but real-world AI applications require much more than sending prompts to a model.

Modern AI systems need to:

- Retrieve information from external knowledge sources
- Maintain conversational context
- Process and transform documents
- Chain multiple reasoning steps together
- Interact with tools and external systems
- Perform autonomous decision-making

**LangChain** provides a flexible framework that connects these capabilities into production-ready AI workflows.

This repository serves as a practical introduction to the LangChain ecosystem, demonstrating how its modular components can be combined to create intelligent and scalable applications.

---

## 🎯 Learning Objectives

By completing this lab, you will learn how to:

✅ Interact with Large Language Models using LangChain

✅ Create structured and reusable prompt templates

✅ Build chat-based applications with role-aware messaging

✅ Parse and structure model outputs

✅ Load and process data from PDFs and websites

✅ Split, embed, and index documents for semantic search

✅ Implement Retrieval-Augmented Generation (RAG)

✅ Maintain conversational memory across interactions

✅ Design sequential and summarization workflows

✅ Create autonomous ReAct agents capable of reasoning and tool usage

---

## 🏗️ What You'll Build

Throughout this notebook, you'll progressively construct a complete LangChain-powered AI ecosystem:

### 🤖 Chat Model

Learn how LangChain abstracts LLM interactions and enables conversational AI through structured message handling.

### ✨ Prompt Engineering Workflows

Design dynamic prompts using:

- PromptTemplate
- ChatPromptTemplate
- FewShotPromptTemplate
- Example Selectors

to create adaptable and reusable prompting systems.

### 📚 Retrieval-Augmented Generation (RAG)

Build an end-to-end RAG pipeline that can:

- Load documents from PDFs and websites
- Split documents into semantic chunks
- Generate embeddings
- Store vectors in ChromaDB
- Retrieve relevant context using similarity search
- Produce grounded, context-aware responses

### 🔗 Multi-Step Chains

Create workflows where the output of one LLM operation becomes the input of another, enabling more sophisticated reasoning processes.

### 🧠 Conversational Memory

Implement persistent conversation history so applications can maintain context across multiple interactions.

### 🤖 ReAct Agent

Build an autonomous agent that can:

- Analyze user questions
- Decide which tools to use
- Generate Python code
- Execute calculations
- Return intelligent responses

using the ReAct (Reason + Act) framework.

---

## 📖 Topics Covered

| Module | Topic | Description |
|----------|----------|-------------|
| 01 | 🤖 Model | Understanding LLM wrappers and model integration |
| 02 | 💬 Chat Model | Working with System, Human, and AI messages |
| 03 | ✨ Prompt Templates | Building reusable and dynamic prompts |
| 04 | 📤 Output Parsers | Converting raw LLM responses into structured outputs |
| 05 | 📄 Documents & Loaders | Loading and preprocessing PDFs and web content |
| 06 | 🧠 Memory | Managing conversation history and context |
| 07 | 🔗 Chains | Building multi-step AI workflows |
| 08 | 📚 Retrieval-Augmented Generation (RAG) | Semantic search and context retrieval |
| 09 | 🤖 Agents | Autonomous reasoning and tool execution |

---

## 🛠️ Technologies Used

This lab leverages a collection of modern AI and data-processing tools:

| Technology | Purpose |
|------------|----------|
| LangChain | AI application orchestration |
| IBM Watsonx | Foundation model integration |
| ChromaDB | Vector database for semantic search |
| PyPDF | PDF document processing |
| Python REPL Tool | Agent-based code execution |
| LangChain Community | Document loaders and integrations |
| LangChain Experimental | Advanced agent capabilities |

---

## 📂 Repository Structure

```text
introduction-to-langchain/
│
├── Introduction_to_LangChain.ipynb
├── README.md
├── sample_documents/
│   ├── pdfs/
│   └── web_content/
│
└── assets/
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/introduction-to-langchain.git

cd introduction-to-langchain
```

### 2️⃣ Install Dependencies

The notebook was developed and tested using the following package versions:

```bash
pip install tenacity \
  "langchain-ibm==0.1.7" \
  "langchain-community==0.2.1" \
  "langchain-experimental==0.0.59" \
  "langchainhub==0.1.17" \
  "langchain==0.2.1" \
  "pypdf==4.2.0" \
  "chromadb==0.4.24"
```

---

## 🔄 LangChain Workflow Covered in this Lab

```text
User Query
     │
     ▼
Prompt Template
     │
     ▼
Large Language Model
     │
     ▼
Output Parser
     │
     ▼
Chains / Memory
     │
     ▼
RAG Retrieval
     │
     ▼
Agent Reasoning
     │
     ▼
Final Response
```

---

## 🎓 Who Is This For?

This notebook is ideal for:

- Computer Science students
- AI/ML enthusiasts
- Generative AI developers
- Prompt engineers
- Data scientists
- Software engineers exploring LLM applications
- Anyone interested in building intelligent AI systems

Basic familiarity with Python is recommended, but no prior LangChain experience is required.

---

## 🚀 Expected Outcome

After completing this lab, you'll have a strong foundation in:

- LangChain architecture
- Prompt engineering
- Retrieval-Augmented Generation (RAG)
- Conversational AI
- LLM orchestration
- Autonomous agents
- Production-oriented AI workflow design

These concepts form the backbone of many modern AI applications, including chatbots, knowledge assistants, AI copilots, document intelligence systems, and agentic AI solutions.

---

## 📚 References

- 🌐 https://www.langchain.com/
- 📖 https://python.langchain.com/
- 📦 https://github.com/langchain-ai/langchain
- 🔍 https://www.trychroma.com/

---

## ⭐ Support

If you found this repository helpful:

- Star ⭐ the repository
- Fork 🍴 the project
- Share 📢 with fellow AI developers

Happy Building with LangChain! 🚀
