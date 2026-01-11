<div align="center">

# Usman Bukhari

**Senior AI Engineer** · RAG Systems · Healthcare AI

[![Website](https://img.shields.io/badge/Website-usmanbukhari.co.uk-0A66C2?style=for-the-badge&logo=safari&logoColor=white)](https://usmanbukhari.co.uk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/usmanbukhari)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:usmanbukhari541@gmail.com)

</div>

---

Building production AI systems that serve real users. Currently at **NHS South Yorkshire ICB**, where I architect RAG infrastructure serving **1.4M residents**.

I focus on the hard parts: making AI reliable in healthcare, handling compliance, and building systems that work at scale without breaking the budget.

---

## 🏗️ What I Build

| Domain | Focus |
|--------|-------|
| **Healthcare AI** | Document intelligence, clinical data pipelines, IG-compliant systems |
| **RAG at Scale** | Azure AI Search, vector embeddings, hybrid retrieval strategies |
| **Production ML** | End-to-end pipelines with monitoring, evaluation, and cost optimization |

---

## 🚀 Featured Projects

### NHS Health Services Finder
> RAG-powered chatbot helping 1.4M South Yorkshire residents find health services

`Azure AI Search` `LangChain` `FastAPI` `React`

- Hybrid retrieval combining semantic search with keyword matching
- Real-time data sync from 30+ regional health service sources
- Built for NHS compliance and accessibility standards

```mermaid
flowchart LR
    subgraph sources [Data Sources]
        S1[NHS APIs]
        S2[Regional Health Sites]
        S3[Service Directories]
    end
    
    subgraph ingestion [Ingestion Pipeline]
        C[Crawl4AI]
        P[LLM Parser]
    end
    
    subgraph storage [Storage and Index]
        PG[(PostgreSQL)]
        AZ[Azure AI Search]
    end
    
    subgraph retrieval [RAG Engine]
        E[Embeddings]
        H[Hybrid Search]
        L[LangChain]
        LLM[GPT-4]
    end
    
    subgraph app [Application]
        API[FastAPI]
        UI[React Frontend]
    end
    
    sources --> ingestion --> storage
    storage --> retrieval --> app
```

### Enterprise Data Pipeline
> Automated ingestion system for regional healthcare data

`Crawl4AI` `Azure Functions` `PostgreSQL`

- Processes 30+ data sources on automated schedules
- Intelligent content extraction with LLM-assisted parsing
- Feeds multiple downstream AI applications

---

## 🛠️ Tech Stack

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,typescript,react,fastapi,nodejs,postgres,redis,docker,azure,git,github,githubactions,linux,vscode&theme=dark&perline=7)](https://skillicons.dev)

**AI/ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Azure AI](https://img.shields.io/badge/Azure_AI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Azure Functions](https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## 📊 GitHub Activity

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=UsmanBuk&theme=github_dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=UsmanBuk&theme=github_dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=UsmanBuk&theme=github_dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/UsmanBuk/UsmanBuk/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/UsmanBuk/UsmanBuk/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/UsmanBuk/UsmanBuk/output/github-contribution-grid-snake.svg" />
</picture>

[![](https://visitcount.itsvg.in/api?id=UsmanBuk&icon=0&color=0)](https://visitcount.itsvg.in)

</div>

---

<div align="center">

📍 **UK-based** · Open to contracts & consulting

*Specializing in RAG systems, healthcare AI, and production ML infrastructure*

</div>
