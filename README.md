![Ashutosh Gupta, Software Engineer banner](https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=200&section=header&text=Ashutosh%20Gupta&fontSize=50&animation=fadeIn&fontColor=ffffff&desc=Software%20Engineer%20%7C%20Java%20%C2%B7%20Spring%20Boot%20%7C%20Next.js%20%C2%B7%20AWS&descSize=16&descAlignY=75)

<p align="center">
  <a href="mailto:ash.gupta113@gmail.com"><img alt="Get in touch" src="https://img.shields.io/badge/Get%20in%20touch-6366f1?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/ashutoshguptaaz"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="mailto:ash.gupta113@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://leetcode.com/u/user5609iP"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white"/></a>&nbsp;
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/AshuGuptaz?style=flat&logo=github&label=Followers&color=6366f1"/>
</p>

---

### 🧠 About Me

- 🔭 **SWE @ VIAVI Solutions** — Spring Boot APIs for enterprise network monitoring + AI-driven anomaly detection
- ⚙️ Built **[Vex](https://github.com/AshuGuptaz/Vex)**, a vector database implementing HNSW from the original paper (Malkov & Yashunin, 2016) — **0.97 recall@10** on SIFT-1M, mmap persistence + WAL, int8 quantization
- 🍰 Shipped **[The Taste Makerrs](https://tastemakerrs.vercel.app)**, a production e-commerce platform — Next.js 14, dual payment gateways (Razorpay + Stripe), OTP-based accounts, live order tracking
- 🤖 Built a **RAG pipeline** achieving **90%+ answer relevance** using LangChain, ChromaDB & Llama 3.1
- 🎓 B.Tech CSE @ Amity University, Lucknow (2026) · CGPA 7.5

---

### 🚀 Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🧬 [Vex](https://github.com/AshuGuptaz/Vex)
<!-- screenshot: <img src="assets/vex.png" alt="..." width="100%"/> -->
**Vector database · HNSW from the original paper**

![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Implements HNSW end-to-end from the paper — not a wrapper around FAISS.
- **0.97 recall@10** on SIFT-1M (128-dim), sub-millisecond query latency
- mmap-backed persistence + CRC32 write-ahead log, crash-recovery tested
- Hand-rolled filter parser, int8 quantization (4× compression, measured)
- 133 tests · 7 ADRs · CI on every push

**[→ View repo](https://github.com/AshuGuptaz/Vex)**

</td>
<td width="50%" valign="top">

#### 🍰 [The Taste Makerrs](https://github.com/AshuGuptaz/tastemakerrs)
<!-- screenshot: <img src="assets/tastemakerrs.png" alt="..." width="100%"/> -->
**Full-stack e-commerce, live in production**

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

A premium bakery storefront, built and shipped end-to-end.
- Dual payment rails — **Razorpay + Stripe**, webhook-verified & idempotent
- Passwordless **OTP accounts**, live order tracking, verified-buyer reviews
- Server-side price authority, rate-limited APIs, admin ops dashboard

**[→ Live site](https://tastemakerrs.vercel.app)** · **[Source](https://github.com/AshuGuptaz/tastemakerrs)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤖 [RAG-Based Document Q&A](https://github.com/AshuGuptaz/rag-document-qa)
**Retrieval-augmented Q&A over private documents**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

- **90%+ answer relevance**, grounded via ChromaDB vector embeddings
- JWT-secured REST API, **sub-2s response** with concurrent multi-user support
- AWS S3 document storage + dynamic prompt engineering

**[→ View repo](https://github.com/AshuGuptaz/rag-document-qa)**

</td>
<td width="50%" valign="top">

#### ☁️ [CloudVault](https://github.com/AshuGuptaz/cloud-file-management)
**Cloud file management API, enterprise-grade access control**

![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

- **RBAC + JWT** securing 100% of 40+ API endpoints via Spring Security
- AWS S3 integration for scalable PDF/image storage, real-time upload & retrieval
- **40% faster** content retrieval via optimized MySQL schema + full-text search

**[→ View repo](https://github.com/AshuGuptaz/cloud-file-management)**

</td>
</tr>
</table>

---

### 🛠️ Tech Stack

<p align="center">
  <b>Backend</b><br/>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=java,spring,python,fastapi&theme=light">
    <img alt="Backend: java, spring, python, fastapi" src="https://skillicons.dev/icons?i=java,spring,python,fastapi&theme=dark">
  </picture>
</p>

<p align="center">
  <b>Frontend</b><br/>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=typescript,nextjs,react,tailwind&theme=light">
    <img alt="Frontend: typescript, nextjs, react, tailwind" src="https://skillicons.dev/icons?i=typescript,nextjs,react,tailwind&theme=dark">
  </picture>
</p>

<p align="center">
  <b>Data &amp; Cloud</b><br/>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=mongodb,mysql,postgres,aws&theme=light">
    <img alt="Data &amp; Cloud: mongodb, mysql, postgres, aws" src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,aws&theme=dark">
  </picture>
</p>

<p align="center">
  <b>Tools</b><br/>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=docker,git,github,postman,linux,idea&theme=light">
    <img alt="Tools: docker, git, github, postman, linux, idea" src="https://skillicons.dev/icons?i=docker,git,github,postman,linux,idea&theme=dark">
  </picture>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=AshuGuptaz&show_icons=true&include_all_commits=true&hide_border=true&bg_color=ffffff&title_color=4f46e5&text_color=24292f&icon_color=6366f1">
    <img alt="GitHub stats for AshuGuptaz" src="https://github-readme-stats.vercel.app/api?username=AshuGuptaz&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0d1117&title_color=818cf8&text_color=c9d1d9&icon_color=6366f1" height="160"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AshuGuptaz&layout=compact&hide_border=true&bg_color=ffffff&title_color=4f46e5&text_color=24292f&icon_color=6366f1">
    <img alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AshuGuptaz&layout=compact&hide_border=true&bg_color=0d1117&title_color=818cf8&text_color=c9d1d9&icon_color=6366f1" height="160"/>
  </picture>
</p>

### 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AshuGuptaz/AshuGuptaz/main/snake/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AshuGuptaz/AshuGuptaz/main/snake/github-contribution-grid-snake.svg">
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/AshuGuptaz/AshuGuptaz/main/snake/github-contribution-grid-snake.svg">
</picture>

---

### 🏆 Certifications

- Google Cloud Computing Foundations — NPTEL, IIT Kharagpur **(Score: 86%)**
- Java (Basic) — HackerRank

---

![footer](https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=100&section=footer)
