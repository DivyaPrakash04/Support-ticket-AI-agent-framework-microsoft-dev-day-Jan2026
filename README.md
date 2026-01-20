# Support-ticket-AI-agent-framework-microsoft-dev-day-Jan2026
Support ticketing automation and my completed labs from Microsoft Agent Framework Dev Day in Jan 2026 — including support ticketing automation, MCP servers/clients, workflow patterns, and Agentic RAG implementations in .NET and Python.
**hosted by Akumina, in association with Microsoft, at the Microsoft office.**  
This gives your repo a polished, authentic provenance without sounding promotional.

Here’s an updated version of the README section that incorporates those details cleanly and professionally.
---

# **Agent Framework Dev Day 2026 — Completed Labs**

This repository contains my completed hands‑on labs from **Agent Framework Dev Day 2026**, a learning workshop **hosted by Akumina in association with Microsoft** at the **Microsoft office**.  
The session explored the Microsoft Agent Framework across both **.NET** and **Python**, with deep dives into **MCP**, **workflow patterns**, **RAG**, and **Agentic RAG**.  
It also includes my implementation of **support ticketing automation** using the Agent Framework.

---

## **Workshop Overview**

The workshop was structured into three major parts:

- **Part 1:** First access, environment setup, and safety fundamentals  
- **Part 2:** Workflow patterns and Model Context Protocol (MCP)  
- **Part 3:** Retrieval‑Augmented Generation (RAG) and Agentic RAG  

Each module included guided exercises, reference solutions, and notebooks for deeper exploration.

---

## **Prerequisites**

### **Core Setup**
- Git + GitHub account  
- Visual Studio Code with recommended extensions (see `VSCode-Extensions.md`)  
- Azure subscription with access to Azure OpenAI and Azure AI Search  
- Stable internet connection  

### **.NET Track**
- .NET 10 SDK  
- C# Dev Kit or C# extension for VS Code  
- Per‑lab debugging notes under `labs/dotnet/`  

### **Python Track**
- Python 3.13  
- `pip` and `venv`  
- Install dependencies:  
  ```
  pip install -r labs/python/requirements.txt
  ```  
- Additional setup notes under `labs/python/`  

---

## **Repository Layout**

```
labs/
  dotnet/
    lab0-hello-world/
    lab1-basic-training/
    lab2-mcp/
    lab2-workflow/
    lab3-agentic-rag/
  python/
    lab0-hello-world/
    lab1-safety/
    lab2-mcp/
    lab2-workflow/
    lab3-agentic-rag/
tools/
VSCode-Extensions.md
```

- **dotnet/** — C# labs covering onboarding, MCP, workflows, and Agentic RAG  
- **python/** — Python equivalents with notebooks and exercises  
- **tools/** — Utility projects used throughout the labs  
- **VSCode-Extensions.md** — Editor setup recommended during the workshop  

---

## **Lab Index**

### **.NET Labs**
| Lab | Focus |
| --- | ------ |
| lab0-hello-world | Validate environment and run the first Agent Framework project |
| lab1-basic-training | Core agent patterns and incremental exercises |
| lab2-mcp | Build MCP servers/clients and explore MCP concepts |
| lab2-workflow | Implement sequential, concurrent, and human‑in‑the‑loop workflows |
| lab3-agentic-rag | Agentic RAG with Azure AI Search and workflow orchestration |

### **Python Labs**
| Lab | Focus |
| --- | ------ |
| lab0-hello-world | Environment smoke test and first Python agent |
| lab1-safety | Exercises reinforcing Agent Framework primitives |
| lab2-mcp | MCP servers/clients and notebook‑based exploration |
| lab2-workflow | Workflow patterns using Python executors |
| lab3-agentic-rag | Agentic RAG using Azure AI Search |

---

## **Support Ticketing Automation**

This repository also includes my implementation of a **support ticketing automation agent**, demonstrating:

- Multi‑step workflow orchestration  
- Tool calling and context management  
- Integration with Azure AI Search  
- Practical use of Agentic RAG patterns  

---

## **Notes**

- A Python‑focused `.gitignore` is included to keep the repo clean.  
- This repository is for learning and demonstration purposes based on the Dev Day workshop hosted by **Akumina + Microsoft**.
- Location | Sponsors |
  | -------- | -------- |
  | Burlington | Microsoft, Akumina |
- Notebooks (`*.ipynb`) are included for MCP, workflows, and RAG concepts and can be run directly in VS Code.

---
