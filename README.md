<div align="center">

# Omer Afzaal

**Senior Software Engineer · Backend & AI Systems · Pakistan 🇵🇰**

*Fast-track promoted ×2 in 18 months · Building production AI infrastructure at scale*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/omerafzaal1)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:omershykh7@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/omer-here)

</div>

---

## About

Backend engineer specializing in distributed systems and LLM-integrated applications. Currently **Senior Software Engineer at [Nayatel](https://nayatel.com)** — Pakistan's leading ISP — where I architect microservices, real-time event pipelines, and AI-powered features serving thousands of concurrent users.

I don't just use AI tools. I build the backend infrastructure that makes AI products work in production: RAG pipelines, agentic runtimes, vector search, streaming APIs, and the observability layer that keeps them reliable.

---

## Featured Projects

### 🧠 [Chronos](https://github.com/omer-here/chronos-mvp) — AI Business Assistant Platform
Multi-tenant RAG SaaS platform combining a PDF knowledge base (via **pgvector**) with dynamic tool calling for real-time attribute retrieval. Streaming chat interface built on the Vercel AI SDK. Resolved production-grade challenges: edge-runtime PDF parsing failures, AI SDK v4 streaming protocol mismatches, and silent Zod schema crashes in LLM tool execution.

`Next.js` `pgvector` `Gemini Embeddings (004)` `Vercel AI SDK` `TypeScript` `Supabase`

---

### 🦞 [Tiny-OpenClaw](https://github.com/omer-here/tiny-openclaw) — Agentic AI Runtime
Production-ready agentic framework implementing the **ReAct (Reasoning + Acting)** loop via the Anthropic Claude API. Hot-loadable skills (web browser automation via Playwright, long-term memory, datetime). Fully async I/O with Python's `asyncio`. Migrated memory/session persistence from JSON to **Redis** to enable concurrent multi-user access and horizontal scalability.

`Python` `Claude API` `Redis` `Playwright` `asyncio` `Docker Compose`

---

### ⚡ [Sportz](https://github.com/omer-here/sportz) — Real-Time WebSocket Architecture
Solved the stateful WebSocket fan-out problem across horizontally scaled Node instances using **Redis Pub/Sub**: mutations publish to a broadcast channel; every instance subscribes and routes to its local connections. Scales to N nodes behind a load balancer with zero dropped broadcasts. Includes heartbeat zombie cleanup, Arcjet rate limiting, Zod validation, and backpressure protection.

`Node.js` `Express` `WebSockets` `Redis Pub/Sub` `PostgreSQL` `Drizzle ORM` `Docker`

---

## Tech Stack

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-%23E0234E.svg?style=flat&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)

**Databases & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)

**AI & LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-D4A017?style=flat&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=google&logoColor=white)

`RAG Pipelines` `Agentic Workflows (ReAct)` `Tool Calling` `pgvector` `MCP` `n8n`

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**DevOps & Observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-008C99?style=flat&logo=newrelic&logoColor=white)

---

## What I'm Working On

- 🔭 **AI Recommendation Engine** — data-driven content personalization for a live-streaming platform
- 🛠️ **NayaTV Backend Modernization** — applying separation-of-concerns refactor to a high-traffic OTT service
- 📖 Deepening knowledge of **LangGraph**, **eval frameworks (RAGAS)**, and **distributed tracing**

---

## Professional Background

```
Nayatel (Pakistan's leading ISP)     Oct 2024 – Present

  Senior Software Engineer           [Promoted ×2 fast-track]
  ↳ Nwatch camera monitoring revamp  NestJS · RabbitMQ · Redis · NewRelic
  ↳ NayaTV backend modernization      Microservices · Separation of Concerns

  Software Engineer
  ↳ Centralized payment platform      Monolith → Microservices · 3+ apps unified
  ↳ Internal CRON scheduling service  Replaced unsafe crontab company-wide

  Assistant Software Engineer
  ↳ NayaTV OTT platform features      40% faster content delivery
  ↳ Internal operational tooling      Log monitoring · Complaint resolution APIs
```

---

<div align="center">

*"Ship it. Observe it. Improve it."*

</div>
