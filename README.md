# EuroSTEMPeers2025_workshop

Welcome to the **EuroSTEMPeers 2025** hands-on beginner-level workshop on **Agentic AI**!  
This session aims to **demystify language model agents** by walking participants through how to build **simple, modular agents** using **LangGraph** — an open-source Python framework for creating multi-agent workflows.

## 🧠 LangGraph Agentic AI Workshop

**Hosted by TeamVPE at BioMed X Institute**

![TeamVPE Logo](https://avatars.githubusercontent.com/u/144795768?s=200&v=4)

Welcome to the hands-on workshop on **Agentic AI with LangGraph**!
This session is hosted by [TeamVPE](https://bmedx.com/research-teams/artificial-intelligence/team-vpe/) at the [BioMed X Institute](https://bmedx.com), proudly supported by [Sanofi](https://www.sanofi.com/en/).

---

## 🎯 Workshop Goals

By the end of this workshop, you'll be able to:

- Understand the **LangGraph** framework for building stateful LLM agents
- Create and manage **agent state** and **tool-calling workflows**
- Use **OpenAI** or **NVIDIA NIMs** as your LLM backend
- Build a **ReAct-style reasoning loop** with tools
- Visualize LangGraph agent flows
- Extend agents with tools for:
  - 🧮 Math calculation
  - 📊 Matplotlib plotting
  - 🌍 Language translation
  - 📄 PDF Q\&A pipeline
  - 🎨 DALL·E image generation

---

## 🧱 What You'll Build

You will implement several progressively advanced agents:

1. **Echo agent** using LangGraph
2. **LLM-powered assistant** (OpenAI or NVIDIA NIM)
3. **ReAct agent** with intermediate memory and reasoning
4. **Multi-tool agent** with tool routing and control flow
5. **PDF reasoning agent** that can download, extract, and answer questions from papers
6. **Image generation agent** using DALL·E 3

---

## 🧰 Prerequisites

- Python 3.12+
- Jupyter Notebook environment (e.g. Anaconda, VS Code, Colab)
- One of the following API keys:
  - [OpenAI API Key](https://platform.openai.com/account/api-keys)
  - [NVIDIA NIM API Key](https://build.nvidia.com/)

---

## 🚀 Installation

Install required libraries with:

```bash
pip install langgraph langchain openai matplotlib pymupdf graphviz pydot requests
```

You’ll also need to install:

- `langchain_nvidia_ai_endpoints` (if using NVIDIA NIMs)
- `IPython` (if not included in your environment)

---

## 🔐 API Key Setup

You can either:

- Set environment variables (`OPENAI_API_KEY` or `NVIDIA_API_KEY`)
- Or paste the key directly into the notebook (demo-friendly)

---

## 📚 Topics Covered

| Section          | Highlights                             |
| ---------------- | -------------------------------------- |
| ✅ Basics        | LangGraph setup, Echo agent            |
| 🧠 LLMs          | OpenAI/NVIDIA NIM integration          |
| 🔁 ReAct         | Reasoning + tool invocation            |
| 🔧 Tools         | Calculator, plot generator, translator |
| 📄 PDFs          | Download, extract, and answer          |
| 🎨 Vision        | Image generation with DALL·E           |
| 📊 Visualization | Flowchart of LangGraph workflows       |

---

## 🧑‍🔬 About the Project

This workshop is part of the **AIAgents4Pharma** initiative — an open-source toolkit for enabling biomedical researchers and pharma professionals to interact with complex data through intelligent, language-powered agents.

👉 Explore more: [VirtualPatientEngine/AIAgents4Pharma](https://github.com/VirtualPatientEngine/AIAgents4Pharma)

---

## 📎 Attribution

Developed by **TeamVPE**, AI research team at [BioMed X Institute](https://bmedx.com). Sponsored by **Sanofi**.

---

## 🧑‍💻 Get Started

Launch the Jupyter Notebook and start from:

```python
!pip install -q langgraph langchain openai
```

Then follow the steps to build your first intelligent agent!
