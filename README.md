<div align="center">

# Shaik Inzamam

### I build AI systems that solve real problems — not just demos.

**LLM Engineer · RAG Architect · Agentic AI Developer**

*3rd-year CSE student shipping production-grade GenAI systems with LangChain, LangGraph & FastAPI*

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shaikinzamam333@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shaikinzamam)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikinzamam)

</div>

---

## What I Bring

- 🏗️ **Production mindset** — every project I build has clean API contracts, modular architecture, and real error handling — not just a working notebook
- 🧠 **Deep LLM stack** — hands-on with RAG pipelines, multi-agent orchestration, vector search, and local LLM inference (not just calling the OpenAI API)
- ⚡ **Speed to ship** — built 3 end-to-end AI applications independently, from architecture to deployed REST APIs
- 🎯 **Problem-first thinking** — I start with the user problem, then pick the right AI architecture — not the other way around
- 🔁 **Systems thinker** — I design for statefulness, retrieval accuracy, and latency — the things that matter in production

---

## Featured Projects

### 🃏 [CardSense AI](https://github.com/shaikinzamam/cardsense-ai) — Multi-Agent Credit Card Rewards Optimizer

**Problem:** Indian credit card users leave thousands of rupees in cashback unredeemed — reward policies are complex, card-specific, and change frequently.

**Solution:** Architected a multi-agent AI system using **LangGraph** that routes user transactions through specialized agents, retrieves relevant reward policies via a **FAISS RAG pipeline**, and returns personalized cashback recommendations in real time.

**Impact:**
- Sub-second semantic retrieval over dynamic reward policy documents using local sentence-transformer embeddings
- Stateful multi-turn conversations across sessions via **SQLAlchemy + async SQLite** — agents remember context
- Modular **FastAPI** backend with dedicated agent, RAG, tools, and database layers — Swagger/OpenAPI documented and production-deployable

`Python` `LangChain` `LangGraph` `FAISS` `FastAPI` `SQLAlchemy` `Ollama` `sentence-transformers`

---

### 📄 [DocuMind AI](https://github.com/shaikinzamam/documind-ai) — Offline RAG Document Intelligence System

**Problem:** Enterprise document Q&A tools either cost too much (cloud LLM APIs) or leak sensitive data to third parties — a dealbreaker for legal, medical, and financial use cases.

**Solution:** Built a fully **offline RAG pipeline** using **LangChain + FAISS + Ollama** that enables semantic Q&A over multiple PDFs simultaneously, with zero data leaving the user's machine.

**Impact:**
- Eliminated API cost entirely — 100% local LLM inference with Ollama, enabling use in data-sensitive environments
- Context-aware prompt chains reduce hallucinations across multi-document sessions
- Clean **FastAPI** backend with production-grade error handling — ready for containerized deployment

`Python` `LangChain` `FAISS` `Ollama` `FastAPI` `Prompt Engineering`

---

### 📝 [ATS Resume Analyzer](https://github.com/shaikinzamam/ats-resume-analyzer) — AI-Powered Resume & JD Matching Engine

**Problem:** Job seekers fail ATS filters not because they're unqualified, but because their resumes lack the right keywords — a fixable, systematic problem.

**Solution:** Built a full-stack GenAI app that parses PDF/DOCX resumes, semantically matches them against job descriptions using a locally hosted LLM (**Mistral/Phi3 via Ollama**), and generates specific, actionable rewrites.

**Impact:**
- End-to-end pipeline: resume parsing → LLM inference → structured output → UI — no manual steps
- 4-strategy JSON parser reliably extracts ATS scores, missing skills, and keyword gaps from unstructured LLM output
- Interactive web UI delivers match scores, skill gap analysis, and AI-rewritten bullet points in a single view

`Python` `Flask` `Ollama` `LangChain` `pypdf` `python-docx` `HTML/CSS/JS`

---

## 🔭 Currently Building & Exploring

- **Agentic AI workflows** with tool use, memory, and multi-step planning using LangGraph
- **ChromaDB** as a persistent alternative to FAISS for production vector stores
- **n8n + Make.com** for no-code AI workflow automation pipelines
- **Structured LLM outputs** with reliable JSON extraction for enterprise AI applications

---

## 🛠️ Tech Stack

**AI & LLMs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Vector DBs & Data**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Tools & Cloud**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shaikinzamam&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shaikinzamam&layout=compact&theme=tokyonight&hide_border=true" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shaikinzamam&theme=tokyonight&hide_border=true" width="60%" />
</p>

---

## 🏅 Achievements & Certifications

| Certification | Issuer | Focus |
|---|---|---|
| Generative AI and LLMs: Architecture & Data Preparation | IBM (Coursera) | LLM internals, training pipelines |
| Python for Everybody | Cisco Networking Academy | Core Python, programming fundamentals |
| AWS Solutions Architecture Job Simulation | Forage | Cloud architecture, IAM, EC2, S3 |

- 🎓 **B.Tech CSE** — BESTIU · CGPA: **7.9 / 10.0** · 3rd Year

---

## 📬 Let's Build Something

I'm looking for an **AI / GenAI / Python internship** where I can contribute to real-world intelligent systems — not just learn, but ship.

If your team is building with LLMs, RAG, or agentic AI and needs someone who hits the ground running:

**→ [shaikinzamam333@gmail.com](mailto:shaikinzamam333@gmail.com)**
**→ [linkedin.com/in/shaikinzamam](https://linkedin.com/in/shaikinzamam)**

> *"I don't just use AI tools — I understand what's happening underneath them."*
