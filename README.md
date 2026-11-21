<h1 align="center">Diego Ramírez</h1>

<p align="center">
  <b>Software engineer · Medellín, Colombia</b><br>
  I build systems that handle money, identity and real customers — and I keep them running.
</p>

<p align="center">
  <a href="https://deviego.xyz"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-deviego.xyz-0095f6?style=for-the-badge&logo=safari&logoColor=white"></a>
  <a href="https://linkedin.com/in/diego-andres-ramirez-mejia"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:diegowritescode@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Say_hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Open to work" src="https://img.shields.io/badge/Open_to-Remote_%26_Hybrid-22c55e?style=flat-square">
  <img alt="English" src="https://img.shields.io/badge/English-B2-444?style=flat-square">
  <img alt="Spanish" src="https://img.shields.io/badge/Spanish-Native-444?style=flat-square">
</p>

---

### What I do

Three years across a regulated bank, a marketing agency, and my own company. Today I am the sole engineer on a multi-tenant SaaS in production — architecture, data model, APIs, interface, infrastructure and operations.

I like problems where being almost right is not good enough: money that has to balance, permissions that have to hold, an order that has to reach the right kitchen.

- **AI inside the product** — retrieval over `pgvector`, LLM output validated against a schema before a row is written, tenant isolation enforced in the query rather than the prompt
- **AI inside how I build** — a custom MCP server over my own codebase, plus subagents and hooks carrying generation, review and documentation
- **Shipped like production** — images built once in CI and deployed by commit SHA behind Traefik with TLS, least-privilege database roles, private metrics

---

### Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![DB2](https://img.shields.io/badge/DB2%2FAS400-054ADA?style=flat-square&logo=ibm&logoColor=white)

**AI**

![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-D4A27F?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_servers-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-5A67D8?style=flat-square)

**Infrastructure & quality**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### Selected work

| Project | What it is | Evidence |
|---|---|---|
| **[AccessCore](https://github.com/diegowritescode/accesscore)** | Identity and authorization platform: a hybrid ReBAC + RBAC + ABAC engine with Zanzibar-style consistency | `1.3 ms` p50 check · `~96%` line coverage · `27` decision records · [live console](https://console.deviego.xyz) |
| **[MiniLedger](https://github.com/diegowritescode/miniledger)** | Double-entry ledger API — balanced entries, idempotent transfers, a hash chain per account | `100%` mutation score on the ledger domain · `~99%` coverage · [live dashboard](https://app.ledger.deviego.xyz) |
| **Toque** | Multi-tenant restaurant SaaS with a WhatsApp ordering agent, in production | `2` products on one core · `80+` decision records · `1` engineer, end to end |
| **LDM Campañas** | Advertising SaaS: one message in, live campaigns across Meta, Google Ads and TikTok out | `3` networks behind one contract · `126/128` objectives chosen correctly · `v2.83` shipped |
| **Zyrcle** · [backend](https://github.com/diegowritescode/zyrcle-backend) · [frontend](https://github.com/diegowritescode/zyrcle-frontend) | Tokenized recycling with blockchain and IoT — three role-specific dashboards over one domain, routes drawn on the real map of Medellín | 🏆 **1st place**, Avalanche Hackadev 2025 — plus Best Use of Precompiles and Best Interoperability |
| **AICFES** · [backend](https://github.com/diegowritescode/aicfes-backend) · [frontend](https://github.com/diegowritescode/aicfes-frontend) | Generates Colombian ICFES exam items with an LLM — Zod validation and an audit trail of the model's raw output | [Whitepaper](https://github.com/diegowritescode/aicfes-whitepaper) · the model proposes, the schema decides |

> Toque and LDM Campañas are commercial products, so their source is closed. The screens and the decisions behind them are on [deviego.xyz](https://deviego.xyz).

---

### How I work

**Decisions are written down.** Every significant choice has a record with its context, the alternatives, and the cost accepted. Over 120 of them across the projects.

**Tests prove properties.** Property-based tests state the invariants, mutation testing checks the tests can actually fail, concurrency runs against real PostgreSQL, and Playwright drives the UIs.

**AI proposes, the system decides.** I direct coding agents and review their output with the same rigor as a colleague pull request. In production, model output is validated against the schema before it is persisted.

---

### Away from the keyboard

My way out of the network is long-distance hiking — full-day routes around 45 km, no signal, nothing to refresh. It is the only place where a problem cannot be solved by typing faster, and most of what I have figured out about a stuck system, I figured out somewhere around kilometre thirty.

A long route is not about speed. It is about a pace you can hold and knowing the way back. I build the same way.

---

<p align="center">
  <b>3 years</b> shipping &nbsp;·&nbsp; <b>5 systems</b> in production &nbsp;·&nbsp; <b>120+</b> decision records &nbsp;·&nbsp; <b>1</b> hackathon won
</p>

<p align="center">
  <sub>Currently learning English daily and preparing the AWS Solutions Architect certification.</sub>
</p>
