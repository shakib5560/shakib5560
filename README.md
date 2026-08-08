<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=190&section=header&text=Shamiul%20Shakib&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Backend-Leaning%20Software%20Engineer%20%E2%80%94%20Systems%2C%20Scale%2C%20AI%20Pipelines&descAlignY=60&descSize=16&animation=twinkling" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1400&color=A78BFA&center=true&vCenter=true&width=680&lines=Architecting+backend+systems+that+don't+fall+over;Correctness-first%2C+then+speed%2C+then+features;NestJS+%C2%B7+FastAPI+%C2%B7+Django+%C2%B7+PostgreSQL+%C2%B7+Redis;Shipping+for+startups+with+international+clients" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-https://shamiulshakib.me/-0f0c29?style=for-the-badge&logo=firefox&logoColor=A78BFA)](https://shamiulshakib.me/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0f0c29?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/sheikh-shamiul-834878206/)
[![Email](https://img.shields.io/badge/Email-dev.shakib%40outlook.com-0f0c29?style=for-the-badge&logo=microsoftoutlook&logoColor=EA4335)](mailto:dev.shakib@outlook.com)
[![Resume](https://img.shields.io/badge/Resume-Download-0f0c29?style=for-the-badge&logo=googledrive&logoColor=22c55e)](https://drive.google.com/file/d/1qow0jClmescT-xLhqZjltETDIVulw0Ka/view?usp=sharing)

</div>

<br/>

## `01` Positioning

Software Engineer with **~2 years of production experience** shipping AI-powered, full-stack systems for startups and international product teams. Background bridges a **B.Sc. in Computer Science & Engineering** with a **Diploma in Graphic Design & Software Technology** — engineering rigor with product/design intuition baked in.

The throughline across the projects below isn't the framework — it's the same question asked every time: *what breaks first at scale, and how do I design so it doesn't?* Money-handling paths get correctness before features. Chat systems get failure-tolerant state before real-time polish. Specs get a single source of truth before code gets written.

<br/>

## `02` Experience

<table>
<tr><td width="180"><b>Jan 2026 – Present</b><br/><sub>Dhaka, Bangladesh</sub></td>
<td>

**Backend Software Engineer** · RajTech BD
Leading backend for an enterprise-grade AI-powered SaaS platform — modular services, workflow orchestration, and extensible LLM integration pipelines. Built production REST APIs and FastAPI microservices (JWT auth, RBAC, rate limiting, caching, async processing) and scaled the core system on NestJS + TypeScript + PostgreSQL + Prisma, tuning query performance through indexing and caching. Sits directly with international clients translating business requirements into architecture, owning API contracts, CI/CD, and Docker-based deployment.

</td></tr>
<tr><td><b>Feb – Dec 2025</b><br/><sub>Karachi, PK (Remote)</sub></td>
<td>

**Full-Stack Software Engineer** (Project-Based) · DevNext
Built high-traffic production applications serving thousands of daily users, including retail platforms like **ToyGalaxy Australia**. Designed backend architecture and data models for scalability and fault tolerance, optimized database access and caching to hold response times steady under growing load, and owned delivery end-to-end with international clients — requirements through post-release optimization.

</td></tr>
<tr><td><b>Apr – Sep 2024</b><br/><sub>Dhaka, Bangladesh</sub></td>
<td>

**Web Developer Intern** · Techonfy IT LTD
Shipped features and resolved bugs across client production applications in an Agile workflow — backend, frontend, database design, API integration, and auth, with early exposure to code review and deployment practice under senior engineers.

</td></tr>
</table>

<br/>

## `03` Systems I've Built

Each of these solves one hard problem, not a checklist of features.

<table>
<tr>
<td width="50%" valign="top">

### 🧬 Idea2System
`NestJS` `Docker` `PostgreSQL` `Redis` `Prisma`

A multi-stage LLM orchestration pipeline that decomposes ambiguous product briefs into requirements, ERDs, architecture, and API contracts — while preserving semantic intent so downstream artifacts never drift from the original ask. Ships with a centralized artifact registry that cross-validates specs against endpoints and docs, packaged into reproducible multi-stage Docker builds.

[`Source`](https://github.com/shakib5560) · [`Registry`](https://github.com/shakib5560)

</td>
<td width="50%" valign="top">

### 💬 GitRabbit
`NestJS` `Socket.IO` `PostgreSQL` `Redis` `Prisma`

A horizontally scalable WebSocket chat system on Socket.IO + Redis Pub/Sub, deliberately splitting ephemeral presence state (Upstash Redis) from durable message history (Postgres) so any node can die without dropping a conversation. Auth layer combines GitHub OAuth 2.0, JWT hybrid sessions, and RBAC with an auto-provisioned Super Admin on bootstrap — closing a privilege-escalation gap common to self-hosted deployments.

[`Live`](https://github.com/shakib5560) · [`Source`](https://github.com/shakib5560)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💳 AINOS
`NestJS` `React` `PostgreSQL` `Prisma`

An AI-powered premium platform with authentication and payment processing, where money-handling paths were designed for correctness and auditability *first*, features second. Backend uses a decoupled data-access layer so horizontal scaling later never means touching business logic.

[`Live`](https://ainos-premium.netlify.app/) · [`Frontend`](https://github.com/shakib5560/AINOS) · [`API`](https://github.com/shakib5560/AINOS_API)

</td>
<td width="50%" valign="top">

### 🛒 Rinors
`Next.js` `T3 Stack` `TypeScript` `Prisma`

A type-safe, end-to-end multi-vendor marketplace serving 10,000+ monthly users, treating the database schema as the single source of truth all the way to the UI. The T3 standardization call traded a little short-term velocity for long-term maintainability — one that kept integration bugs low as both vendor base and codebase scaled.

[`Live`](https://www.rinors.com/) · [`Source`](https://github.com/shakib5560)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 GyaanBD
`Next.js` `NestJS` `TypeScript` `i18n` `JWT`

A multi-language knowledge-sharing platform built for reach from day one — internationalization and auth architected in, not bolted on.

[`Live`](https://gyaanbd.vercel.app) · [`Source`](https://github.com/shakib5560/gyaanbd.com)

</td>
<td width="50%" valign="top">

### 🧸 ToyGalaxy
`Django` `JavaScript` `Tailwind CSS`

Backend and performance owner for a Django e-commerce platform in production for **1,500+ daily active users** — tuning query plans and asset delivery to hold load times steady as traffic grew, and hardening validation against real-world traffic edge cases to cut production incidents.

[`Live`](https://www.toygalaxy.com.au/) · [`Source`](https://github.com/shakib5560)

</td>
</tr>
</table>

<details>
<summary><b>🛠️ In progress & experiments</b></summary>
<br/>

| Project | Stack | What it is |
|---|---|---|
| [`tubeX`](https://github.com/shakib5560/tubeX) | Node.js · MongoDB | Scalable REST API backend for a video-sharing platform |
| `ServicoBD` | Full-stack · AI | AI-powered service finder |
| `List-Live` | React · Node.js | Real-estate listing platform |
| `FoodSvaly` | React | Food delivery app, full UI & business logic |
| `career_z` | C++ · LLM | CLI career-recommendation engine with LLM integration |

</details>

<br/>

## `04` Stack

<div align="center">

<sub><b>Languages</b></sub>
<br/><img src="https://skillicons.dev/icons?i=python,javascript,typescript,c,cpp,dart&theme=dark" />

<sub><b>Backend & APIs</b></sub>
<br/><img src="https://skillicons.dev/icons?i=nestjs,fastapi,django,nodejs,express&theme=dark" />

<sub><b>Frontend</b></sub>
<br/><img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind&theme=dark" />

<sub><b>Data & Infra</b></sub>
<br/><img src="https://skillicons.dev/icons?i=postgresql,mysql,mongodb,redis,docker,git,linux&theme=dark" />

</div>

**Core concepts:** API design & integration · System design · Database design · Caching strategies · Data structures & algorithms · AI-assisted development

<br/>

## `05` GitHub

<div align="center">
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=shakib5560&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&icon_color=7c3aed&text_color=c4b5fd" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=shakib5560&theme=midnight-purple&hide_border=true&background=0d0d1a&stroke=7c3aed&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa" />

<img width="60%" src="https://github-readme-activity-graph.vercel.app/graph?username=shakib5560&bg_color=0d0d1a&color=a78bfa&line=7c3aed&point=f59e0b&area=true&hide_border=true" />
</div>

<br/>

## `06` Education & Recognition

<table>
<tr><td width="55%" valign="top">

**Bangladesh University of Business & Technology (BUBT)**
B.Sc. Computer Science & Engineering · CGPA 3.43/4.00 · 2023–Present
*DSA · System Design · DBMS · OS · Networking · OOP · Software Engineering*

**Graphic Arts Institute (GAI)**
Diploma in Engineering, Graphic Design & Software Technology · CGPA 3.60/4.00 · 2020–2023
*Product Design · UI/UX · Figma · Web Dev (React, Node.js, Django)*

</td><td width="45%" valign="top">

🏆 **Regional Programming Contest** — 1st place
🎓 **Three Minute Thesis (3MT)** — presented *FacePass*, a facial-authentication model for secure web login
🥇 **HackerRank** — Gold Badge, Problem Solving; Certified in Python

</td></tr>
</table>

<br/>

<div align="center">

*"Write code that scales, reads well, and solves real-world problems."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=110&section=footer&animation=twinkling" width="100%" />

</div>
