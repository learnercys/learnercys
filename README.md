# Hi, I'm Carlos 👋

**Senior Full Stack Engineer** · 10+ years building backend systems that move money, data, and (lately) LLM tokens reliably.

I design distributed services in **Go** and **Python**: event-driven pipelines, multi-tenant APIs, and payment workflows. I run them on **AWS** and **Kubernetes**. Today I'm building microservices and AI-powered workflows. Before that I built data platforms for higher education, led banking and fintech projects, and worked on payments infrastructure.

---

### 🔧 What I work with

**Languages:** Go · Python · TypeScript
**Backend:** gRPC · REST · FastAPI · PostgreSQL · Redis · SQS · event-driven architecture
**Cloud & Infra:** AWS · Kubernetes · Terraform · Docker · GitHub Actions · OpenTelemetry
**AI:** OpenAI & Anthropic APIs · LLM workflows & evals · MCP · Claude Code / Cursor
**Frontend:** React · Next.js · React Native

---

### 🚀 Featured projects

| Project | What it shows |
|---|---|
| **[event-pipeline](https://github.com/learnercys/event-pipeline)** | Payment-event pipeline in Go + Python: transactional outbox, SNS/SQS fan-out, idempotent consumers, and a chaos test (SIGKILLs, a Postgres restart, injected crashes) that proves every balance stays exact. |
| **[ledger](https://github.com/learnercys/ledger)** | Multi-tenant double-entry ledger in Go: gRPC + HTTP/JSON, Keycloak OIDC, Postgres row-level security, money rules enforced by the database, and property-based tests that prove money is never created, lost or overdrawn. |
| **[llm-gateway](https://github.com/learnercys/llm-gateway)** 🚧 | Provider-agnostic LLM gateway (OpenAI + Anthropic) with fallbacks, caching, per-tenant cost tracking, and an eval suite in CI. |
| **[platform](https://github.com/learnercys/platform)** 🚧 | Terraform + Helm + GitHub Actions deploying all of the above to EKS, with OpenTelemetry tracing and Grafana dashboards. |

<sub>🚧 = in progress. Every project runs locally with one command (`make up`).</sub>

**Fundamentals, for fun:**
[mini-git](https://github.com/learnercys/mini-git) (a Git implementation in Go) · [monkey](https://github.com/learnercys/monkey) (an interpreter in Go)

---

### 💡 Things I care about

- **Correctness under failure.** Retries, duplicates, and partial outages are the normal case, not edge cases.
- **Boring, observable systems.** If it can't be traced, measured, and rolled back, it isn't done.
- **Pragmatic AI.** LLMs are a component like any other: they need evals, budgets, and fallbacks.

---

### 📫 Find me

[Website](https://learnercys.github.io/) · [LinkedIn](https://www.linkedin.com/in/carlos-hernandez-1571b187/)
