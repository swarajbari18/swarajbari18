<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6E40C9&center=true&vCenter=true&width=600&lines=AI+Engineer+%7C+2.5%2B+Years+in+Production;Multi-Agent+Systems+%26+LLM+Orchestration;Making+AI+Reliable%2C+Not+Just+Impressive;RAG+Pipelines+%7C+Evaluation+%7C+LLMOps" alt="Typing SVG" /></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-swarajbari18-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/swarajbari18)
[![Email](https://img.shields.io/badge/Email-swarajbari18%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:swarajbari18@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-swarajbari18-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@swarajbari18)

</div>

---

## About

I build LLM systems that actually work in production.

Most of my work is in multi-agent systems, RAG pipelines, and orchestration. Not just calling an API, but making these systems reliable, deterministic, and usable in real workflows. I designed a planning framework that pushed success rates from **43% to 81%** on a mid-tier model by removing the LLM from execution entirely. Intelligent architecture outperforms brute-force token spending.

I focus on the things teams usually skip: evaluation frameworks, tracing, prompt reliability, guardrails, and failure handling. That is where the real problems live.

---

## Results That Shipped

| Problem | Before | After | How |
|---|---|---|---|
| Agentic system success rate | 43% | **81%** | Replaced AutoGen with custom LLM-independent orchestration |
| RAG retrieval accuracy | 40% | **83.5%** | Hybrid search + semantic chunking + structured extraction |
| LLM inference cost | Baseline | **−90%** | Multi-agent architecture on GPT-3.5 matching GPT-4 output |
| Internal workflow processing | 2 hours | **15 min** | Agentic automation pipeline |
| ML model accuracy | 20% | **80%** | Diagnosed and fixed data leakage in production pipeline |

---

## Projects

### [Creator Joy](https://github.com/swarajbari18/Creator-joy) — Video analysis chatbot for content creators

Paste any social video url. The system generates rich multimodal transcriptions of every 10-second segment covering shot types, camera angles, editing style, on-screen text, and audio. Indexes everything into a vector store with 3-vector hybrid search and lets you ask questions about visual style, not just the words.

Built a skill-based multi-agent system: single orchestrator delegates to specialized sub-agents depending on query type. Three-vector search fusion (dense embeddings via Qwen3, sparse via miniCOIL, cross-encoder reranking) on Qdrant.

`LangGraph` `Gemini 2.5 Flash` `Qdrant` `FastAPI` `React` `Python`

---

### [Genie / Tend](https://github.com/swarajbari18/genie-poc) — Contract workflow automation in production

Contracts sent, signed, and tracked over email. Built this on my own because I saw the product gap. The interesting engineering decision: used Postmark inbound webhooks instead of Gmail API to capture replies without ever reading the user's inbox. BoldSign for e-signatures. Live at genie-app.usetend.in.

[Demo video](https://youtu.be/CmXNSKUTZeY) · [How I built email capture without inbox access](https://medium.com/@swarajbari18/building-contract-email-without-asking-to-read-a-users-inbox-a727e9ce1c3b)

`React` `Node.js` `Postmark` `BoldSign` `PostgreSQL`

---

### [3D Model Generation Pipeline](https://github.com/swarajbari18/Image-to-3d-model) — POC: composite images to 3D models

Generates 3D models from composite images. Gemini handles understanding the composition with a self-correcting bounding box loop that keeps iterating until the output meets a quality threshold. Tested across Hunyuan 2MV, Tripo v1, and Only One v3.1.

[Demo video](https://youtu.be/voCHwnfvTM8)

`Python` `Gemini` `Hunyuan 2MV` `Tripo` `Only One`

---

## Work Experience

```
Jul 2025 – Present   AI Engineer         Fere AI (Web3)         Remote
Aug 2024 – Jun 2025  AI Developer        Yoonify Inc            San Diego, CA (Remote)
Jan 2024 – Jul 2024  AI Engineer         Artus AI               Boston, MA (Remote)
Oct 2023 – Dec 2023  ML Engineer         Freelance              Tokyo, JP (Remote)
```

---

## What I Work On

```
Multi-Agent Systems        — Custom orchestration frameworks, planning + execution pipelines,
                             LLM-independent code-based execution layers

Agentic RAG               — Hybrid search (BM25 + semantic), semantic chunking, structured
                             extraction, query routing, evaluation-driven iteration

Evaluation & Observability — Custom success-rate frameworks, LangSmith tracing, guardrails
                             (prompt injection, PII, toxicity), hallucination detection

LLM Cost Engineering       — Architecture-first cost reduction, model selection, prompt
                             optimization that matches frontier quality at mid-tier price
```

---

## Tech Stack

**LLM & Agentic AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-121212?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=flat-square&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-6E40C9?style=flat-square&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Infra & Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Vector DBs & Storage**

![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-FF5A5F?style=flat-square&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)
![Chroma](https://img.shields.io/badge/ChromaDB-F5A623?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0064BD?style=flat-square&logo=meta&logoColor=white)

**Evaluation & Observability**

![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=swarajbari18&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&count_private=true" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=swarajbari18&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=swarajbari18&theme=tokyonight&hide_border=true" />

</div>

---

## Education

**B.Tech (Hons.) — National Institute of Technology, Jamshedpur** · 2017–2021

---

<div align="center">

*Building AI systems that work, not just ones that demo well.*

</div>
