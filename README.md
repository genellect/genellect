<div align="center">

# Yuto Matsui

### AI-native full-stack developer building production systems across education, AI, and science.

I turn domain problems into working products—from problem definition and system architecture to implementation, testing, deployment, and operations.

**[Live Product](https://compass-interactive.pages.dev/demo)** · **[COMPASS Platform](https://compass-official.pages.dev/)** · **[Developer Case Study](https://compass-official.pages.dev/INTRO_Interactive/developers/)**

</div>

---

## Selected Systems

<sub>PRODUCTION WORK ACROSS EDUCATION, AI, AND SCIENCE</sub>

Two connected systems spanning live classroom interaction, public product experience, identity, registration, permissions, and operations.

### 01 / COMPASS Interactive

**Learning infrastructure for the complete lecture lifecycle.**

Founder · Product Owner · Lead Developer

Connects students, instructors, classroom displays, and post-lecture archives through one shared system.

#### Engineering Highlights

- **Secure multi-role architecture** — Designed Student, Admin, Display, and Archive experiences with Supabase Auth, PostgreSQL, Row Level Security, and RPC-based ownership controls.
- **Resilient live state** — Built versioned synchronization with visibility-aware polling, retry control, and failure backoff while separating browser-facing state, protected server operations, and private document delivery.
- **Governed AI execution** — Structured authorization, concurrency limits, budget control, usage accounting, validation, and human review across end-to-end lecture workflows.

<p align="center">
  <strong><a href="https://compass-interactive.pages.dev/demo">Explore the Live Demo →</a></strong>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://compass-official.pages.dev/INTRO_Interactive/">Product Overview</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://compass-official.pages.dev/INTRO_Interactive/developers/">Developer Case Study</a>
</p>

**Stack**<br>
`React` · `TypeScript` · `Supabase` · `PostgreSQL` · `Edge Functions` · `OpenAI API` · `Cloudflare` · `Playwright` · `pgTAP`

> The production repository is private; its architecture and key engineering decisions are documented in the public case study.

---

### 02 / COMPASS Platform

**Public product, registration, and operational infrastructure for COMPASS.**

Founder · Product Owner · Full-Stack Developer

Turns public discovery, registration, identity, permissions, operations, and audit history into one production platform.

#### Engineering Highlights

- **Product and identity** — Built the Next.js interface and FastAPI registration services with Google authentication, server-side ID-token verification, and eligibility evaluation.
- **Reliable operations** — Established PostgreSQL as the source of truth and implemented asynchronous Google Drive permissions with transactional outbox processing, idempotency, leases, retries, and recovery states.
- **Production infrastructure** — Separated Public API, Admin API, Worker, Migration, and Database responsibilities; defined Cloud Run, IAM, secrets, monitoring, and deployment with Terraform; and automated validation across the full system.

<p align="center">
  <strong><a href="https://compass-official.pages.dev/">Visit the Production Platform →</a></strong>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/my270yuto0413-cmyk/COMPASS">View Source Code</a>
</p>

**Stack**<br>
`Next.js` · `TypeScript` · `FastAPI` · `PostgreSQL` · `Google Cloud Run` · `Cloudflare` · `Terraform` · `Docker` · `Playwright` · `Pytest`

---

## Research × Engineering

I am also a molecular biology researcher studying the molecular mechanisms of ALS/FTD, with a focus on C9orf72-associated neurodegeneration.

I apply software engineering, automation, image analysis, and AI to research and education workflows.

---

<div align="center">

**Education · AI · Science · Production Systems**

[Portfolio](https://compass-official.pages.dev/INTRO_Interactive/developers/) · [GitHub](https://github.com/my270yuto0413-cmyk) · [Live Product](https://compass-interactive.pages.dev/demo)

</div>
