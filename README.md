# Hey, I'm Dennis 👋🏽

**Software Engineer · Founder of [Bytes Lab](https://byteslab.io) · Building [Still200](https://still200.com)**

I'm a software engineer based in Nairobi, Kenya 🇰🇪, with 8+ years of experience building backend systems, APIs, and production software.

I specialize in **Python, distributed systems, backend infrastructure, and applied AI**, with a particular interest in designing systems that are reliable, observable, and simple to operate.

I also build and ship my own products — from the first line of code to production infrastructure, billing, monitoring, and everything in between.

I believe great software comes from thoughtful engineering, sensible trade-offs, and knowing when *not* to add complexity.

---

## 🚀 What I'm Building

### 🟢 [Still200](https://still200.com) — Reliability monitoring for developers

**Keep shipping. We'll keep watch.**

Still200 helps developers and small teams catch API downtime, missed cron jobs, and silent background task failures before their users do.

I designed, built, and operate the platform end to end, including its distributed monitoring infrastructure, web application, public status pages, notification delivery, and iOS companion app.

**Engineering highlights:**

- **Distributed monitoring:** Asynchronous Python workers performing HTTP health checks, latency measurements, and incident detection.
- **Custom scheduling:** Redis sorted sets and Lua scripts powering efficient, concurrent monitor scheduling.
- **Event-driven architecture:** NATS JetStream for reliable event processing and notification delivery.
- **Cron monitoring:** Heartbeat-based tracking of scheduled jobs, including start, completion, failure, and missed execution detection.
- **Webhooks:** Event delivery with persisted delivery records, retries, and PostgreSQL-backed background processing.
- **Public status pages:** Customer-facing service health dashboards with configurable monitored components.
- **Developer SDK:** Published `still200-sdk`, a Python package supporting synchronous and asynchronous cron monitoring through decorators.
- **Full-stack ownership:** API design, database architecture, infrastructure, billing, frontend, documentation, and mobile development.

**Stack:** Python · FastAPI · PostgreSQL · Redis · NATS JetStream · React · TypeScript · SwiftUI · Docker

🌐 [Website](https://still200.com) · 📚 [Documentation](https://docs.still200.com) · 📦 [Python SDK](https://pypi.org/project/still200-sdk/) · 📐 [Architecture Deep Dive](https://blog.byteslab.io/posts/still200-system-architecture/) · 📱 [iOS App](https://apps.apple.com/us/app/still200/id6770858177)

### ✉️ [KindlyNote](https://kindlynote.app) — Thoughtful messages, powered by AI

**Every sentiment. Beautifully delivered.**

An AI-powered application that helps people express appreciation, apologies, complaints, and everything in between, with personality and carefully chosen tone.

Built and launched as an independent product, with a focus on simplicity, user experience, and lean production infrastructure.

**Engineering highlights:**

- **Applied AI:** Structured AI generation using OpenAI and Pydantic AI.
- **Lightweight frontend:** Server-rendered interfaces built with Jinja2 and HTMX.
- **Background processing:** PostgreSQL-backed job queue using `SKIP LOCKED`, retries, and worker polling.
- **Abuse prevention:** Rate limiting, recipient protections, and Cloudflare Turnstile.
- **Production observability:** Health checks and monitoring for database connectivity, AI generation, and email delivery.
- **End-to-end delivery:** Product design, backend development, deployment, and production operations.

**Stack:** Python · FastAPI · Pydantic AI · PostgreSQL · HTMX · Jinja2 · Supabase · Railway

🌐 [Try KindlyNote](https://kindlynote.app)

---

## 📱 Other Products I've Shipped

### [Illumity](https://apps.apple.com/us/app/illumity/id6759741620)
An AI-powered image generation app for iOS, combining a native SwiftUI experience with a high-concurrency FastAPI backend.

Built with StoreKit 2 for credit-based purchases and Supabase for authentication and storage.

📐 [Architecture Deep Dive](docs/illumity-architecture.md) · 📱 [App Store](https://apps.apple.com/us/app/illumity/id6759741620)

### [Filmster](https://apps.apple.com/us/app/filmster/id6502289556)
A native iOS entertainment companion for discovering movies and TV shows.

### [Torqy](https://apps.apple.com/us/app/torqy/id6475610114)
An iOS vehicle maintenance tracker designed to make car ownership easier to manage.

---

## 🛠️ Technologies I Work With

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Distributed Systems**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![NATS](https://img.shields.io/badge/NATS-27AAE1?style=flat-square&logo=natsdotio&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

**AI, Web & Mobile**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) ![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=flat-square&logo=htmx&logoColor=white) ![SwiftUI](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## ✍🏽 Engineering Notes

I write about the systems I build, the decisions behind them, and what I learn from running software in production.

A few technical deep dives:

- [Still200: System Architecture](https://blog.byteslab.io/posts/still200-system-architecture/) — Building a distributed monitoring platform.
- [Monitoring with Still200](https://blog.byteslab.io/posts/monitoring-with-still200/) — Instrumenting a real application and monitoring its health.

More writing at **[blog.byteslab.io](https://blog.byteslab.io)**.

---

## 🤝 Let's Build Something

I'm interested in **backend engineering, distributed systems, applied AI, developer infrastructure, and technically ambitious products**.

I'm open to remote engineering roles, consulting engagements, and collaborations with teams building meaningful software.

Whether you need someone to design a reliable backend, take ownership of a complex system, or turn an ambitious idea into a working product, I'd love to connect.

📬 **[Email](mailto:dennis@byteslab.io)** · **[LinkedIn](https://www.linkedin.com/in/dennis-wainaina-359ab388/)** · **[Bytes Lab](https://byteslab.io)**

*Build thoughtfully. Ship consistently. Keep things simple.*