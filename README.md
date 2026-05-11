<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Lakshyam%20Khare&fontSize=52&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=Applied%20AI%20Engineer%20%26%20Solution%20Architect&descAlignY=58&descColor=8b949e&descSize=20" width="100%"/>

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-lakchchayam.github.io-58a6ff?style=for-the-badge&logo=github&logoColor=white)](https://lakchchayam.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lakshyamkhare)
[![Email](https://img.shields.io/badge/Email-lakchchayam.khare%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakchchayam.khare@gmail.com)

</div>

---

## About

I build **production-grade Agentic AI systems** — multi-agent orchestration frameworks, MCP tool layers, RAG pipelines, and LLMOps evaluation infrastructure. 

Currently based in **Toronto, ON 🇨🇦** | MSc Computer Science, Western University (2024) | Mitacs Fellow

**What I actually ship:**

- 🤖 Multi-agent systems using **LangGraph** that coordinate Supervisor, Researcher, Writer, and Review agents through stateful execution graphs
- 🔌 **Model Context Protocol (MCP)** servers that expose business data sources to LLMs with security enforcement and read-only access controls
- 🔍 **RAG pipelines** with hybrid retrieval (dense + BM25), context-grounded generation, and LLM-as-a-Judge evaluation — tracking Faithfulness, Context Relevancy, and Answer Relevancy
- ⚡ High-throughput **semantic routing** layers at sub-50ms latency for intent classification and agent dispatch
- 📊 **LLMOps pipelines** with MLflow experiment tracking, drift detection, and CI/CD gating on model quality metrics

---

## Production Impact

<div align="center">

| Metric | Value |
|---|---|
| Monthly transactions orchestrated | **100K+** |
| Production uptime | **99.2%** |
| Hallucination rate reduction (RAG) | **35%** |
| Domain accuracy improvement (PEFT) | **28%** |
| Active production agent workflows | **6** |
| Open-source projects shipped | **5** |

</div>

---

## Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Enterprise Agentic Orchestrator](https://github.com/lakchchayam/enterprise-agentic-orchestrator)
Multi-agent execution engine built on LangGraph. Supervisor delegates to specialized workers (Researcher, Analyst, Writer) through a typed state graph with automatic LLM failover (Anthropic → OpenAI) and human-in-the-loop approval gates.

`LangGraph` `LangChain` `FastAPI` `Python`

</td>
<td width="50%" valign="top">

### 🔌 [MCP SQL Analyst](https://github.com/lakchchayam/mcp-sql-analyst)
Model Context Protocol server for safe LLM-driven database querying. AST-based SQL validation via `sqlglot` blocks all mutations/DDL. Read-only transactions enforced at the database level. Exposes `schema_discovery`, `run_query`, `explain_query` tools.

`MCP` `SQLAlchemy` `sqlglot` `PostgreSQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [Autonomous Researcher](https://github.com/lakchchayam/autonomous-researcher)
Goal-oriented research agent with a Planner → Worker → Synthesizer → Critique loop. Scrapes the web with Playwright, stores content in a FAISS session memory, and self-corrects based on LLM critique before finalizing reports.

`LangGraph` `Playwright` `FAISS` `GPT-4o`

</td>
<td width="50%" valign="top">

### 📊 [RAG Eval Harness](https://github.com/lakchchayam/rag-eval-harness)
Enterprise evaluation pipeline for RAG systems. LLM-as-a-Judge metrics (Faithfulness, Context Relevancy, Answer Relevancy) logged to MLflow. CI/CD GitHub Action blocks PRs when metrics degrade > 5%.

`MLflow` `DeepEval` `Ragas` `Click`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ [Hybrid Semantic Router](https://github.com/lakchchayam/hybrid-semantic-router)
Sub-50ms query routing using dense embedding cosine similarity (MiniLM) fused with BM25 sparse scoring. Routes queries to the correct agent or prompt template without an expensive LLM call. FastAPI server with dynamic route management.

`sentence-transformers` `BM25` `FastAPI` `ONNX`

</td>
<td width="50%" valign="top">

### 🏋️ [Lushio AI](https://github.com/lakchchayam/Lushio-AI)
Production AI platform for the fitness industry. LangGraph orchestration layer, MCP tool servers for booking and member data, hybrid RAG over SOPs and FAQs, and PEFT fine-tuned domain models. Processes 100K+ monthly transactions.

`LangGraph` `MCP` `FastMCP` `GCP` `AWS`

</td>
</tr>
</table>

---

## Tech Stack

**Agentic AI & LLMs**

![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-FastMCP-blueviolet?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-Claude-D97706?style=flat-square)
![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=flat-square&logo=google&logoColor=white)

**ML & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189A00?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)

**Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=lakchchayam&show_icons=true&theme=github_dark&hide_border=true&count_private=true&rank_icon=github&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lakchchayam&layout=compact&theme=github_dark&hide_border=true&langs_count=8&hide=jupyter%20notebook,html,css" />

</div>

---

<div align="center">

*Open to senior Applied AI Engineer and AI Architect roles in Toronto and remote.*
*Let's build something that actually ships.*

[![Email](https://img.shields.io/badge/Get%20In%20Touch-lakchchayam.khare%40gmail.com-58a6ff?style=for-the-badge)](mailto:lakchchayam.khare@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/>

</div>
