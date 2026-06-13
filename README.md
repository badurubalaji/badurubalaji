<h1 align="center">Hi, I'm Balaji Baduru 👋</h1>

<p align="center">
  <b>Founder & Full-Stack Engineer · Distributed Systems · AI-Native SaaS</b><br>
  14+ years building enterprise platforms — Java · Go · Rust · Angular · cloud-native.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/badurubalaji"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/badurubalaji"><img src="https://img.shields.io/badge/X-@badurubalaji-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="mailto:balaji4b@gmail.com"><img src="https://img.shields.io/badge/Email-balaji4b@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### 🚀 About

I'm a **technical founder and full-stack engineer** in Bengaluru, India, currently building a portfolio of **AI-native SaaS platforms** across healthcare, data protection, communication, and education.

I design systems end-to-end: **modular backends, event-driven services, multi-tenant data layers, and cloud-native deployment** — backed by **14+ years** shipping enterprise web platforms and leading teams of up to **15 engineers** through the full SDLC. Comfortable going deep across the stack: **Java / Spring Boot, Go, Rust, TypeScript / Angular**, PostgreSQL, and Kubernetes.

---

### 🧱 Engineering I care about

Things I've designed and built across my recent projects — the decisions, not just the labels:

- **Modular monoliths & bounded contexts** — Spring Modulith with 10 isolated domains in [Healthplex](#-featured-projects); enforced module boundaries over a distributed-by-default reflex.
- **Multi-tenancy with hard isolation** — tenant data separation via **PostgreSQL Row-Level Security** (MSLS) and per-tenant orchestration (MDP), not app-layer filtering you can forget.
- **Event-driven, polyglot systems** — a **Go control plane** issuing work over **NATS JetStream** to **Rust data-plane agents** (MDP) — the right language at each layer.
- **AI-native architecture** — provider-agnostic **BYOK LLM gateways** (Anthropic / OpenAI / Bedrock / Ollama), **pgvector** retrieval, and tool-calling orchestration with human-in-the-loop approval.
- **Security by construction** — **AES-256-GCM** at rest, **JWT / OIDC SSO** across role-based apps, BCrypt, server-side secret handling.
- **Operable from day one** — **Flyway** schema-first migrations, **OpenTelemetry** tracing, structured logging, Helm/Terraform infra, GitHub Actions CI/CD.

---

### 🏗️ Featured Projects

Self-built platforms — the architecture is the point.

| Project | Engineering notes | Stack |
|---------|------------------|-------|
| 🏥 **Healthplex** | AI-native EHR as a **modular monolith** — 10 Spring Modulith bounded contexts, multi-region, OIDC SSO across 4 role-based apps, BYOK LLM gateway + pgvector | Java 25 · Spring Boot 4 · Spring Modulith · Angular · PostgreSQL/pgvector · K8s · Terraform |
| 🛡️ **MDP — Meta Development Platform** | Multi-tenant **data-protection control plane**: Go orchestrator dispatching jobs over **NATS JetStream** to **Rust agents** moving bytes on customer infra | Go · Rust · React · NATS JetStream · PostgreSQL · object storage |
| 🎓 **MSLS** | Multi-tenant school SaaS with **hard data isolation via PostgreSQL Row-Level Security**; RBAC across admin/teacher/student/parent | Spring Boot · Angular · PostgreSQL RLS |
| 🔐 **SecureVault** | Credential vault — **AES-GCM** encryption, JWT auth, app/environment-scoped secret storage | Java 21 · Spring Boot 3.5 · Angular 20 · JWT |
| 🎥 **MeetSpace** | Self-hosted **WebRTC** meetings + real-time messaging; single-command deploy, white-label ready | WebRTC · real-time messaging · full-stack |
| 💼 **Payroll** | Enterprise self-hosted payroll — **Gradle multi-module**, schema-first, Flyway migrations, iText PDF reporting, OpenAPI | Java 21 · Spring Boot 3.5 · PostgreSQL · Gradle |

<sub>🤖 Also building an embeddable, page-context-aware AI copilot library, an AI gateway (NeuralGate), and more. Repos open-sourced progressively.</sub>

---

### 🛠️ Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Architecture**
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Modulith](https://img.shields.io/badge/Spring%20Modulith-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Microservices](https://img.shields.io/badge/Event--Driven-FF6F00?style=flat-square&logo=apachekafka&logoColor=white)
![NATS](https://img.shields.io/badge/NATS%20JetStream-27AAE1?style=flat-square&logo=natsdotio&logoColor=white)
![REST](https://img.shields.io/badge/REST%20%2F%20gRPC-02569B?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)

**Data, Cloud & Ops**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

---

### ⚙️ How I engineer

- **Boundaries first** — model the domain and its module/tenant boundaries before reaching for distribution. Most "microservices" problems are missing module boundaries.
- **Schema-first & migration-driven** — the database is a contract; Flyway migrations, explicit constraints, no implicit drift.
- **Right tool per layer** — Java for rich domains, Go for control planes, Rust where bytes and latency matter.
- **Observable or it didn't ship** — tracing, structured logs, and runbooks are part of the feature, not a follow-up.
- **Reviews & readability** — I review rigorously and optimize for the next engineer reading the code.

---

### 🧭 Experience

| Role | Organization | Focus |
|------|--------------|-------|
| Senior Software Engineer | **EPAM Systems** (2021–Present) | Large-scale enterprise platform engineering — Java, Angular & cloud |
| Technical Lead | **HCL Technologies** (2017–2021) | Led delivery, design & code reviews for enterprise client engagements |
| Senior Software Engineer | **KMG Infotech** (2015–2017) | RESTful/SOAP services & full product features for US healthcare |
| Software Engineer | **Sreeven InfoCom / Indecomm** (2011–2015) | GWT/Java products with multiple third-party integrations |

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=badurubalaji&show_icons=true&count_private=true&hide_border=true&theme=tokyonight">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=badurubalaji&layout=compact&hide_border=true&theme=tokyonight">
</p>

---

### 🤝 Let's build something

Founder validating an MVP · investor doing technical diligence · a company that needs a senior hand on architecture — I'd like to hear what you're building.

📧 **balaji4b@gmail.com**  ·  💼 **[LinkedIn](https://www.linkedin.com/in/badurubalaji)**

---

<sub>💬 Side projects and opinions here are my own and do not represent my employer or its clients. Work history is summarized at a high level; no confidential or proprietary information is shared.</sub>
