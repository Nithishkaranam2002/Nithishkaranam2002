<h1 align="center">Hi, I'm Nithish Karanam 👋</h1>
<h3 align="center">AI/ML Engineer — Agentic Systems, RAG Architectures & Production LLM Platforms</h3>

<p align="center">
I design and ship production AI systems — not prototypes. My work spans multi-agent LangGraph pipelines,
hybrid retrieval architectures indexing tens of thousands of documents, and privacy-preserving healthcare
tools deployed on real infrastructure. Domains: legal tech, fintech, logistics, and healthcare.
</p>

<p align="center">
MS in Artificial Intelligence, University of North Texas (2026) · NVIDIA-Certified in Agentic AI & Generative AI LLMs
</p>

---

## 🚀 Flagship Projects

### 🏛️ ImmigraAssist
Full-stack RAG platform for immigration legal research, deployed on DigitalOcean. Indexes 6,500+ vectors across USCIS and BIA/AAO case documents using hybrid retrieval (Milvus + BM25 + Reciprocal Rank Fusion), achieving a RAGAS score of 0.840. Includes GLiNER-based PII redaction, 4-tier RBAC, and a Celery + Playwright ingestion pipeline across a 9-service Docker Compose stack, with a React/TypeScript/Tailwind frontend featuring streaming chat and cited-law badges.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square)
![BM25+RRF](https://img.shields.io/badge/Hybrid%20Retrieval-BM25%20%2B%20RRF-555555?style=flat-square)
![GLiNER](https://img.shields.io/badge/GLiNER-PII%20Redaction-orange?style=flat-square)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)

**🔗 [Live Demo](#) &nbsp;•&nbsp; 📦 [Repository](#)** <sub>*(replace # with your links)*</sub>

---

### 💸 FinFlow
Agentic invoice-to-reconciliation platform built on a five-agent LangGraph pipeline, with multi-tenant RBAC, Langfuse observability, and DeepEval-driven CI evaluation. Deployed on DigitalOcean.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-Observability-8A2BE2?style=flat-square)
![DeepEval](https://img.shields.io/badge/DeepEval-CI%20Evals-FF6F61?style=flat-square)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)

**🔗 [Live Demo](#) &nbsp;•&nbsp; 📦 [Repository](#)** <sub>*(replace # with your links)*</sub>

---

### 🚛 DeadMile AI
Trucking load optimization SaaS built on a 19-container architecture. Started as a Buildathon 2026 project, now an active SaaS build.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB0028?style=flat-square)
![Deck.gl](https://img.shields.io/badge/Deck.gl-Geospatial%20Viz-4B8BBE?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Mem0](https://img.shields.io/badge/Mem0-Agent%20Memory-6C5CE7?style=flat-square)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js%2015-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**🔗 [Live Demo](#) &nbsp;•&nbsp; 📦 [Repository](#)** <sub>*(replace # with your links)*</sub>

---

## 🧩 Other Projects

| Project | What it does | Tech |
|---|---|---|
| **MedAssist-AI** | Privacy-preserving healthcare assistant. PHI redaction before every LLM call, JWT-based RBAC (3 roles), HIPAA/GDPR-aligned design, EHR summarization, microservice architecture. | FastAPI, JWT, LLM, Microservices |
| **ShopVoice** | Voice-first AI shopping assistant for blind and visually impaired users (UNT Research Assistant project). Voice in, voice out shopping over a real storefront. | LangGraph, GPT-4o, FastAPI, Streamlit, Docker, Whisper STT, ElevenLabs TTS, Shopify Storefront API, PostgreSQL |
| **Clinical Trial Intelligence Assistant** | Six-module clinical research assistant including CTCAE v5.0 adverse event grading and live ClinicalTrials.gov data. | FastAPI, Streamlit, GPT-4o-mini, ChromaDB, Docker, ClinicalTrials.gov API v2 |
| **Knowledge Gap Finder** | Research discovery tool that surfaces under-explored areas in the literature via semantic clustering and a custom Gap Score (UNT Information Retrieval course). | Semantic Scholar API, ArXiv API, SentenceTransformers, FAISS, BM25, RRF, KMeans, FastAPI |

---

## 🛠️ Tech Stack

**🧠 LLM / Agentic AI**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG%20Architectures-4B8BBE?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-333333?style=flat-square)
![Multi--Agent](https://img.shields.io/badge/Multi--Agent%20Systems-FF6F00?style=flat-square)
![GPT--4o](https://img.shields.io/badge/GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-8A2BE2?style=flat-square)
![DeepEval](https://img.shields.io/badge/DeepEval-FF6F61?style=flat-square)
![GLiNER](https://img.shields.io/badge/GLiNER-orange?style=flat-square)

**⚙️ Backend / Infra**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**🗄️ Data / Vector DBs**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-purple?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-4267B2?style=flat-square)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![Mem0](https://img.shields.io/badge/Mem0-6C5CE7?style=flat-square)

**🎨 Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**🐳 DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Nithishkaranam2002&show_icons=true&theme=radical" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Nithishkaranam2002&theme=radical" alt="GitHub Streak" />
</p>

---

## 🏅 Certifications

- **NVIDIA-Certified Professional: Agentic AI (NCP-AAI)**
- **NVIDIA-Certified: Generative AI LLMs**

---

## 🤝 Let's Connect

📍 Looking for **AI Engineer / ML Engineer** roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](#)

<sub>*(replace # with your LinkedIn, email, and portfolio links)*</sub>
