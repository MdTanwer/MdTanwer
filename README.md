<div align="left">

# Hi, I'm Md Tanwir 👋

### Java Software Engineer · Distributed Systems & Cloud-Native JVM

New Delhi, India (Open to Relocation) · [LinkedIn](https://www.linkedin.com/in/md-tanwer/) · [Email](mailto:tanw9004167@gmail.com)

*Java Software Engineer with 3+ years of experience building concurrent, distributed, and cloud-native Java systems — spanning gRPC, Virtual Threads, reactive caching, Kafka & RabbitMQ pipelines, Spring Boot, Quarkus, GraalVM Native Image, and Kubernetes / AWS EKS.*

**Active Open-Source Contributor to [Quarkus (Red Hat)](https://github.com/quarkusio/quarkus/pulls/MdTanwer) · [Keycloak (Red Hat)](https://github.com/keycloak/keycloak/pulls/MdTanwer) · [SmallRye GraphQL](https://github.com/smallrye/smallrye-graphql/pulls/MdTanwer) · [OpenSearch](contributions/opensearch.md) · [Kestra](https://github.com/kestra-io/kestra/pulls/MdTanwer) —70+ merged Java/JVM PRs (36 merged in Quarkus core)**

</div>

---

## ⭐ Selected JVM & Cloud-Native Highlights

- **Quarkus Kotlin Coroutines Cache (`quarkus-cache-kotlin`)** — Designed and shipped a conditional extension adding Kotlin `suspend` support to `@CacheResult`, resolving a 2-year-old bug where suspend functions never hit cache and blocked the Vert.x event loop ([#55542](https://github.com/quarkusio/quarkus/pull/55542)).
- **gRPC & Virtual Threads Concurrency Fix** — Diagnosed and fixed a high-load race where unary gRPC calls on `@RunOnVirtualThread` delivered `onHalfClose` before `onMessage` (`INTERNAL: Half-closed without a request`) by deferring half-close until the request arrives ([#55041](https://github.com/quarkusio/quarkus/pull/55041)).
- **Unified IPv6 Dev Services Networking** — Introduced a shared `DevServicesHostUtil` across Quarkus Dev Services (JDBC, MongoDB, Kafka, Redis, Elasticsearch, Keycloak), fixing broken connection URLs and falling back from unreachable IPv6 gateways to IPv4/localhost on Docker and Podman ([#54718](https://github.com/quarkusio/quarkus/pull/54718)).
- **Keycloak Security Hardening** — Fixed an HS512 client-secret entropy flaw (~512 bits) ([#50083](https://github.com/keycloak/keycloak/pull/50083)), an inverted legacy `KEYCLOAK_SESSION` cookie check ([#50147](https://github.com/keycloak/keycloak/pull/50147)), path-traversal containment in `FolderTheme.getTemplate()` ([#50098](https://github.com/keycloak/keycloak/pull/50098)), and unsafe FreeMarker defaults ([#50099](https://github.com/keycloak/keycloak/pull/50099)).
- **SmallRye GraphQL Schema Nullability** — Fixed Kotlin nullability loss for Mutiny-wrapped generic lists (`Uni<List<String>>` → `[String!]!` instead of `[String]!`) by recursively applying Kotlin metadata across the wrapper chain ([#2563](https://github.com/smallrye/smallrye-graphql/pull/2563)).

---

## ☕ Open Source Contributions

### <a href="https://quarkus.io">Quarkus (Red Hat)</a>&nbsp;&nbsp;&nbsp;<a href="contributions/quarkus.md"><img src="https://img.shields.io/badge/View_all_PRs-0366d6?style=for-the-badge" alt="View all PRs" align="middle"></a>

36 merged PRs (+ 15 under review) in Red Hat's Kubernetes-native Java framework across caching, gRPC, Virtual Threads, Vert.x HTTP, RESTEasy Reactive, Hibernate/Panache, GraalVM Native Image, AWS Lambda, Kubernetes/OpenShift, and Dev Services.

> `Java · Kotlin · Vert.x · gRPC · Mutiny · Hibernate/Panache · RESTEasy Reactive · GraalVM · Kubernetes`

### <a href="https://www.keycloak.org">Keycloak (Red Hat)</a>&nbsp;&nbsp;&nbsp;<a href="contributions/keycloak.md"><img src="https://img.shields.io/badge/View_all_PRs-0366d6?style=for-the-badge" alt="View all PRs" align="middle"></a>

4 merged security PRs in Red Hat's identity and access management server covering client-secret entropy, session cookie comparison, and FreeMarker theme hardening.

> `Java · Quarkus · OAuth 2.0 / OIDC · FreeMarker · Security`

### <a href="https://smallrye.io/smallrye-graphql">SmallRye GraphQL</a>&nbsp;&nbsp;&nbsp;<a href="contributions/smallrye-graphql.md"><img src="https://img.shields.io/badge/View_all_PRs-0366d6?style=for-the-badge" alt="View all PRs" align="middle"></a>

MicroProfile GraphQL implementation powering Quarkus GraphQL; fixed recursive Kotlin nullability preservation in schema generation for Mutiny reactive types.

> `Java · Kotlin · MicroProfile GraphQL · Mutiny · Schema Generation`

### <a href="https://opensearch.org">OpenSearch (Security & Neural Search)</a>&nbsp;&nbsp;&nbsp;<a href="contributions/opensearch.md"><img src="https://img.shields.io/badge/View_all_PRs-0366d6?style=for-the-badge" alt="View all PRs" align="middle"></a>

3 merged Java PRs across `opensearch-project/security` (RBAC role permissions and startup compliance logging) and `opensearch-project/neural-search` (configurable rerank score fields).

> `Java · OpenSearch · RBAC Security · Distributed Search · Gradle`

### <a href="https://kestra.io">Kestra</a>&nbsp;&nbsp;&nbsp;<a href="contributions/kestra.md"><img src="https://img.shields.io/badge/View_all_PRs-0366d6?style=for-the-badge" alt="View all PRs" align="middle"></a>

Java/Micronaut event-driven workflow orchestration platform; fixed core runtime `fileURI` namespace file version resolution consistency.

> `Java · Micronaut · Pebble · Distributed Workflows · Docker`

---

## 💼 Professional Experience

**Software Developer @ TechUniqueIIT Solutions** · New Delhi, India *(Jun 2023 – Sep 2026)*

- **High-Performance Reactive Microservices** — Built **8 Quarkus 3 + GraalVM Native Image** microservices running at **45MB RSS per pod** (vs. 350MB JVM), achieving an **87% memory reduction**.
- **Monolith → Microservices Migration** — Architected legacy billing monolith decomposition into **9 Spring Boot microservices** on **AWS EKS**, improving release cadence from **bi-weekly to multiple daily releases**.
- **Enterprise Access & Security Platform** — Built multi-vendor RBAC Vendor Access Management with automated permission cleanup across logistics platforms, securing partner onboarding at **<100ms latency**.
- **Event-Driven & Async Messaging** — Shipped high-throughput **Kafka** pipelines and **RabbitMQ**-based async email/SMS notification queues, unblocking request threads for **40% faster endpoint response times**.
- **Global Data Auditing Middleware** — Standardized enterprise entity auditing via a reusable pre-save hook with dynamic user-context extraction (`created_by` / `last_modified_by` compliance metadata).

---

## 🛠 Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | Java (Virtual Threads, Concurrency) · Kotlin (Coroutines) · SQL |
| **Frameworks & APIs** | Quarkus · Spring Boot · Spring Data JPA · Vert.x · Mutiny (Reactive) · Hibernate / Panache · gRPC · GraphQL · RESTEasy Reactive · Micronaut |
| **Messaging & Streaming** | Apache Kafka · RabbitMQ |
| **Cloud & Infrastructure** | AWS (EKS, Lambda, S3, Redshift) · Google Cloud · Kubernetes · OpenShift · Docker · Podman · GraalVM Native Image · GitHub Actions |
| **Data & Storage** | PostgreSQL · DynamoDB · Redis · MongoDB · MySQL · Amazon Redshift · Amazon S3 |
| **Observability & Build** | Micrometer · OpenTelemetry · Prometheus · Maven · Gradle · Testcontainers |
