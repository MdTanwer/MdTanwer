<div align="center">

# Hi, I'm Md Tanwir 👋

### Full Stack AI Software Engineer · New Delhi, India

*I build agentic AI systems and the cloud-native infrastructure under them.*

**Core contributor to [OpenHands](https://github.com/OpenHands/software-agent-sdk/pulls/MdTanwer) · [Quarkus (Red Hat)](https://github.com/quarkusio/quarkus/pulls/MdTanwer) · [Keycloak](https://github.com/keycloak/keycloak/pulls/MdTanwer) — 70+ merged PRs across agentic AI and cloud-native Java**


---

## ⭐ Flagship: [PARI](https://pari-cli.in) — Terminal-Native Coding Agent

Architected **PARI**, a terminal-native agentic AI coding assistant built for autonomous, durable code work:

- 🧠 **Multi-step LLM orchestration** — planner–editor routing, reflection-based self-correction, tool/function calling
- 🌳 **AST-aware context routing** with multimodal input across **7 model providers**
- 🛡️ **Fail-closed kernel sandbox** — atomic writes, bounded retries, crash-recoverable state
- ⚙️ Autonomous code search, editing, shell/test execution, and safe failure recovery

> `TypeScript · Node.js · LLM Orchestration · MCP · Sandboxing`

---

## 🤖 AI & Agentic Systems — Open Source

### [OpenHands software-agent-sdk](https://github.com/OpenHands/software-agent-sdk/pulls/MdTanwer) — Core Contributor

| Contribution | Impact |
|---|---|
| [Typed ACP boundary layer](https://github.com/OpenHands/software-agent-sdk/pull/5293) | Replaced 23 fragile runtime attribute probes with a typed dataclass/Protocol boundary — CI violation baseline **98 → 75**, zero regressions across 578 tests |
| [Idle-container suspension](https://github.com/OpenHands/software-agent-sdk/pull/5199) | Concurrency-safe Docker runtime suspension with lock-guarded lease checks + full-history resume — fixed host RAM/disk exhaustion |
| Agent & conversation lifecycle redesign | Typed base-class and Protocol contracts — removed 13 runtime attribute probes across 19 files (local/remote conversations, condensers, events) |

➡️ **Focus areas:** Agentic AI · LangChain · MCP · ACP · RAG · Vector DBs · LiteLLM · LoRA/QLoRA · INT8/INT4 Quantization

---

## ☕ JVM & Cloud-Native — Open Source

### [Quarkus (Red Hat)](https://github.com/quarkusio/quarkus/pulls/MdTanwer) — 40+ merged PRs

- **[`quarkus-cache-kotlin`](https://github.com/quarkusio/quarkus/pull/55542)** — designed and shipped a conditional extension adding Kotlin coroutines support to `@CacheResult`, resolving a **2-year-old issue** where suspend functions never hit cache and blocked the Vert.x event loop
- **[gRPC virtual-thread race fix](https://github.com/quarkusio/quarkus/pull/55041)** — diagnosed and fixed unary calls delivering `onHalfClose` before `onMessage` on virtual threads (`INTERNAL: Half-closed without a request` under load) by deferring half-close until the request message arrives
- More: RESTEasy Reactive `UriInfo` matrix params, `quarkus.http.ssl-host` for independent HTTPS binding, fast-jar packaging for Amazon Lambda JVM containers

### [Keycloak (Red Hat)](https://github.com/keycloak/keycloak/pulls/MdTanwer)

- Fixed a **client-secret entropy flaw** (HS512, ~512 bits), a legacy `KEYCLOAK_SESSION` cookie comparison bug, and hardened the FreeMarker theme layer against path traversal and unsafe engine defaults

### Grafana

- MSSQL connection fix, keyboard accessibility improvements

---

## 💼 Work

**Software Developer @ TechniQue IT Solutions** · New Delhi *(Aug 2023 – Present)*

- 🏗️ **Platform engineering** — RBAC vendor access, compliance-auditing middleware, RabbitMQ async notifications for multi-vendor logistics platforms; partner onboarding < 100ms, endpoints 40% faster
- ☁️ **Backend & microservices** — migrated a legacy billing monolith to 9 Spring Boot microservices on AWS EKS + 8 Quarkus/GraalVM native services; **per-pod memory cut 87%**, releases went from bi-weekly to daily
- 🖥️ **Frontend & API integration** — React dashboards unifying 15+ backend services into one interface for 1,000+ users

---

## 🛠 Tech Stack

| Area | Tools |
|---|---|
| **AI / LLM** | LangChain · MCP · ACP · RAG · LiteLLM · Vector DBs · LoRA/QLoRA · Quantization (INT8/INT4) |
| **Languages** | Python · Java · TypeScript · JavaScript · SQL |
| **Backend** | FastAPI · Quarkus · Spring Boot · Node.js · Kafka · RabbitMQ |
| **Frontend** | React · TypeScript |
| **Cloud & Infra** | AWS (EKS, Lambda, S3) · Docker · Kubernetes · GraalVM · GitHub Actions · CI/CD |
| **Data & Observability** | PostgreSQL · DynamoDB · MongoDB · Redis · OpenTelemetry · Prometheus |

---

