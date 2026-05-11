# Hi, I'm Lakshyam 👋

**Applied AI Engineer & Solution Architect** based in Toronto, ON 🇨🇦

I build production-grade Agentic AI systems — multi-agent orchestration frameworks, MCP tool layers, RAG pipelines, and LLMOps evaluation infrastructure. MSc Computer Science, Western University (2024) | Mitacs Fellow.

[![Portfolio](https://img.shields.io/badge/Portfolio-lakchchayam.github.io-0969da?style=flat-square&logo=github)](https://lakchchayam.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lakshyamkhare)
[![Email](https://img.shields.io/badge/Email-lakchchayam.khare%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:lakchchayam.khare@gmail.com)

---

## What I Ship

- **Multi-agent orchestration** with LangGraph — Supervisor/Worker graphs, stateful execution, HITL approval gates
- **Model Context Protocol (MCP)** servers — exposing business data to LLMs with security enforcement and read-only access
- **RAG pipelines** — hybrid retrieval (dense + BM25), context-grounded generation, 35% hallucination reduction in production
- **LLMOps** — MLflow experiment tracking, LLM-as-a-Judge evaluation, CI/CD quality gating
- **Semantic routing** — sub-50ms intent classification using local embeddings + BM25, no LLM needed

## Production Metrics

| Metric | Value |
|---|---|
| Monthly transactions orchestrated | **100K+** |
| Production uptime | **99.2%** |
| Hallucination rate reduction | **35%** |
| Domain accuracy improvement via PEFT | **28%** |
| Active production agent workflows | **6** |

---

## Flagship Projects

### 🤖 [enterprise-agentic-orchestrator](https://github.com/lakchchayam/enterprise-agentic-orchestrator)
Production multi-agent engine built on LangGraph. Supervisor delegates to specialized workers through a typed state graph. LLM provider failover (Anthropic → OpenAI → Google). Human-in-the-loop approval gates. Exposed as FastAPI service.

`LangGraph` · `LangChain` · `FastAPI` · `Python` · `Anthropic` · `OpenAI`

---

### 🔌 [mcp-sql-analyst](https://github.com/lakchchayam/mcp-sql-analyst)
Model Context Protocol server for safe LLM-driven database querying. SQL validation via `sqlglot` AST parsing blocks all mutations/DDL before execution. Read-only transactions enforced at DB level. Exposes `schema_discovery`, `run_query`, `explain_query` tools.

`MCP` · `FastMCP` · `SQLAlchemy` · `sqlglot` · `PostgreSQL`

---

### 🔬 [autonomous-researcher](https://github.com/lakchchayam/autonomous-researcher)
Goal-oriented research agent with Planner → Worker → Synthesizer → Critique loop. Scrapes the web with Playwright (JS-rendered pages), stores content in FAISS session memory, and self-corrects based on LLM critique before finalizing the report.

`LangGraph` · `Playwright` · `FAISS` · `BeautifulSoup` · `GPT-4o`

---

### 📊 [rag-eval-harness](https://github.com/lakchchayam/rag-eval-harness)
Enterprise RAG evaluation pipeline. LLM-as-a-Judge metrics — Faithfulness, Context Relevancy, Answer Relevancy — logged per experiment to MLflow. GitHub Action blocks PRs when any metric degrades more than 5% from baseline.

`Ragas` · `DeepEval` · `MLflow` · `Click` · `Pandas`

---

### ⚡ [hybrid-semantic-router](https://github.com/lakchchayam/hybrid-semantic-router)
Sub-50ms query routing using dense embedding cosine similarity (MiniLM) fused with BM25 sparse scoring. No LLM call needed for routing. FastAPI server with single/batch endpoints and dynamic route reconfiguration.

`sentence-transformers` · `BM25` · `FastAPI` · `ONNX` · `NumPy`

---

### 🏋️ [Lushio-AI](https://github.com/lakchchayam/Lushio-AI)
Production AI platform for the fitness industry. LangGraph orchestration, MCP servers for booking and member data, hybrid RAG over SOPs and FAQs, PEFT fine-tuned domain models. 100K+ monthly transactions, 99.2% uptime.

`LangGraph` · `MCP` · `FastMCP` · `Pinecone` · `GCP` · `AWS` · `Docker`

---

## Tech Stack

**AI & Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-orange?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![MCP](https://img.shields.io/badge/MCP%20%2F%20FastMCP-blueviolet?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI%20GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic%20Claude-D97706?style=flat-square)
![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace%20PEFT%20%2F%20LoRA-FFD21E?style=flat-square)

**Data & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-189A00?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**Backend & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

---

## GitHub Stats

![Lakshyam's GitHub stats](https://github-readme-stats.vercel.app/api?username=lakchchayam&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=lakchchayam&layout=compact&theme=github_dark&hide_border=true&langs_count=8&hide=jupyter%20notebook,html,css)

---

*Open to senior Applied AI Engineer and AI Architect roles — Toronto and remote.*
*[lakchchayam.khare@gmail.com](mailto:lakchchayam.khare@gmail.com)*
