<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,100:4169E1&height=180&section=header&text=Nicola%20Palo&fontSize=45&fontColor=ffffff&desc=AI%20Engineer&descSize=20&descAlignY=64&animation=fadeIn" width="100%" alt="header"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=8B5CF6&center=true&vCenter=true&width=680&lines=AI+Engineer;From+prompt+engineering+to+RAG+to+fine-tuning;Building+Hybrid+RAG+on+a+single+PostgreSQL+store;Shipping+LLM+systems%2C+not+notebooks)](https://github.com/nicola-palo)

</div>

## 🔭 About me

AI Engineer working through the full LLM engineering ladder — **prompt engineering in production first, retrieval-augmented generation now, fine-tuning next**.
Whatever the layer, I build the complete path: data model, retrieval, serving API, observability, deploy.
Backend foundations in **Java/Spring and Python**, so the systems I build are boring where they must be, and smart where it counts.

- ✅ **Shipped:** LLM-powered support microservice on the ATM platform — Google Gemini, system-prompt design, session & context handling
- 🔨 **Now building:** [HybridRAG](https://github.com/nicola-palo/HybridRAG) — hybrid retrieval (dense + lexical + RRF) on a single PostgreSQL store
- 🔜 **Next:** first fine-tuning project, starting as soon as HybridRAG ships
- 📫 **Reach me:** [LinkedIn](https://linkedin.com/in/nicolapieropalo) · nicolapiero.palo@gmail.com

## 🚀 The LLM engineering arc

One platform (ATM), one ladder: each project climbs a step of LLM engineering.

| Step | Status | Project | What it proves |
|------|--------|---------|----------------|
| **Prompt engineering** | ✅ shipped | [ATM chat-support](https://github.com/nicola-palo/be.chatBancomat.python) | System-prompt design (`config.py`), context & session handling, Gemini 2.0 Flash inside a production microservice |
| **RAG** | 🔨 in progress | [HybridRAG](https://github.com/nicola-palo/HybridRAG) | Dense + lexical retrieval fused with RRF on one PostgreSQL store — CI included |
| **Fine-tuning** | 🔜 next | — | Launching right after HybridRAG — watch this space |

### 🔨 Current chapter: HybridRAG

**Hybrid retrieval-augmented generation (dense + lexical + RRF fusion) on a single PostgreSQL store.**
One database does it all: embeddings, full-text, metadata — no extra vector DB to operate.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-3E668F?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-0A7CFF?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

```mermaid
graph LR
    A["Docs / corpus"] --> B["Ingestion<br/>and chunking"]
    B --> C[("PostgreSQL<br/>pgvector + tsvector")]
    C --> D["Dense<br/>retrieval"]
    C --> E["Lexical<br/>retrieval"]
    D --> F["RRF<br/>fusion"]
    E --> F
    F --> G["Answer<br/>generation"]
    F -.-> H["Langfuse<br/>traces & evals"]
    G -.-> H
```

➡️ **[github.com/nicola-palo/HybridRAG](https://github.com/nicola-palo/HybridRAG)** — work in progress

## 🧩 Featured work

| | Project | What it is |
|---|---------|------------|
| 🏧 | [**ATM microservices system**](https://github.com/nicola-palo/be.bancomat.java) | Full ATM platform across three services: [React front end](https://github.com/nicola-palo/fe.bancomat.react) + [Java/Spring core](https://github.com/nicola-palo/be.bancomat.java) + [FastAPI chat-support with Gemini AI](https://github.com/nicola-palo/be.chatBancomat.python), each with its own database, deployed on Render |
| 🧠 | [**atm-node**](https://github.com/nicola-palo/atm-node) | Python service node of the ATM platform |
| 🧩 | [**antigravityVSplug-in**](https://github.com/nicola-palo/antigravityVSplug-in) | VS Code extension integrating Antigravity directly into the IDE |

## 🛠 Stack

**AI & RAG**
[![AI stack](https://skillicons.dev/icons?i=py,fastapi,pytorch,postgres,docker&theme=dark)](https://github.com/nicola-palo)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-886FBF?style=flat-square&logo=googlegemini&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A7CFF?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-3E668F?style=flat-square)

**Engineering foundations**
[![Infra stack](https://skillicons.dev/icons?i=java,spring,ts,react,git&theme=dark)](https://github.com/nicola-palo)

## 📊 GitHub stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=nicola-palo&show_icons=true&rank_icon=github&hide_border=true&theme=radical" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nicola-palo&layout=compact&hide_border=true&theme=radical&langs_count=8" alt="Top languages"/>
</div>

<!-- 🐍 SNAKE — attiva questa sezione SOLO dopo il primo run dell'action (vedi ISTRUZIONI.md, passo 4):
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nicola-palo/nicola-palo/output/github-contribution-grid-snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/nicola-palo/nicola-palo/output/github-contribution-grid-snake.svg" width="100%" alt="contribution snake"/>
</picture>
-->

## 📫 Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nicolapieropalo)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nicolapiero.palo@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4169E1,100:8A2BE2&height=110&section=footer" width="100%" alt="footer"/>
