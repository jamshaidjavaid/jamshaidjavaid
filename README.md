<h1 align="center">Jamshaid Javaid</h1>
<h3 align="center">Senior Full Stack Engineer · Fintech Infrastructure · Production Reliability · Agentic AI</h3>

<p align="center">
  <a href="https://jamshaidjavaid.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Visit-blue?style=for-the-badge&logo=internet-explorer" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/jamshaid-javaid" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="https://twitter.com/jamshaidjavaid_" target="_blank">
    <img src="https://img.shields.io/twitter/follow/jamshaidjavaid_?logo=twitter&style=for-the-badge" alt="Twitter / X" />
  </a>
  <a href="mailto:jamshaidjavaid360@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-informational?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</p>

---

## About Me

I'm a **Senior Full Stack Engineer** from **Pakistan (Remote-first)** focused on building **fintech infrastructure, production-reliable systems, and compliance-heavy platforms** where failure is expensive and correctness matters.

At **CreditBook**, I work on the systems behind embedded finance and lending operations — the parts most people never see, but the parts that absolutely cannot break. That includes **partner APIs, loan origination flows, compliance orchestration, disbursement pipelines, auditability layers, and internal operational tooling** that support real financial movement at scale.

A big part of my work is not just writing APIs — it’s designing systems that can survive the messy reality of production:

- third-party services timing out
- webhooks arriving late, duplicated, or out of order
- partner-specific rule variance
- payment providers behaving differently across flows
- compliance vendors returning inconsistent payloads
- humans needing to step into automated flows at critical points
- retries that must be safe because money and state are involved

That’s the kind of engineering I enjoy most: **building systems that stay boring in production, even when everything around them is noisy.**

Before fintech, I built **HIPAA-compliant telehealth platforms** across the **US, Japan, and Australia**, which sharpened my instincts around **secure architecture, auditability, regulated workflows, and operational correctness in sensitive domains**.

---

## What I Actually Specialize In

- **Fintech infrastructure** — loan origination, disbursements, ledgers, compliance-heavy workflows
- **Production reliability** — retries, idempotency, failure recovery, eventual consistency, safe state transitions
- **External systems orchestration** — payment gateways, KYC/KYB, AML/CFT, credit bureaus, banking partners, webhooks
- **Workflow & process automation** — durable multi-step flows with approvals, wait states, branching, and traceability
- **Full-stack product engineering** — building both the infrastructure and the internal/external tools around it
- **AI-native systems** — agentic workflows, RAG pipelines, orchestration, memory-aware automation

---

## What I Build in Practice

I’m strongest when the system has to coordinate **multiple external actors** with different SLAs, different payload shapes, different failure modes, and different business rules — while still preserving a clean internal model and a reliable user/operator experience.

That means building systems around:

- **KYC / KYB providers**
- **AML / CFT screening services**
- **credit bureau integrations**
- **risk and eligibility engines**
- **agreement / document workflows**
- **banking and disbursement rails**
- **multiple payment gateways**
- **partner-specific embedded finance integrations**
- **webhook-driven async state machines**
- **human approval and exception-handling layers**

The hard part isn’t the happy path.

The hard part is:

- when one vendor returns partial success
- when another times out after committing
- when webhooks duplicate
- when a payment gateway confirms asynchronously
- when one partner’s rules differ subtly from another’s
- when you need to retry without double-processing money
- when ops teams need visibility into exactly what happened and why

That’s where I like to work.

---

## Current Role

### Senior Full Stack Engineer — CreditBook (Remote)

`Jan 2026 – Present`

I work on **embedded finance infrastructure** and **loan automation systems** used across multiple partners and financial products.

Key areas of ownership:

- **Fintech workflow orchestration**
  - Architected a **distributed DAG-based execution engine** for complex lending and compliance workflows
  - Supports **conditional branching**, **wait states**, **dynamic parameter resolution**, **safe retries**, **timeouts**, and **fault recovery**
  - Built for flows where automation must coexist with human approvals, operational review, and external dependency variance

- **Production reliability in money-moving systems**
  - Designed flows around **idempotent execution**, **state safety**, and **replay-safe processing**
  - Built systems to handle partial failures, duplicate events, late webhooks, and non-deterministic third-party behavior
  - Focused on keeping critical financial workflows **correct, auditable, and resilient under real production conditions**

- **External systems orchestration**
  - Coordinated multi-step integrations across:
    - KYC / KYB services
    - AML / CFT providers
    - credit bureau systems
    - document / agreement flows
    - banking / disbursement rails
    - partner-specific finance integrations
    - multiple payment gateways
  - Designed abstractions that reduce partner-specific complexity without hiding critical operational differences

- **Operational tooling & auditability**
  - Built a **no-code workflow builder** for ops teams to configure product rules and branching logic without engineering bottlenecks
  - Delivered **regulator-grade auditability** through node-level logs, immutable decision trails, and traceable execution history
  - Enabled failure visibility, manual intervention, and clean recovery paths for operational teams

- **Business impact**
  - Helped automate **1000s of loans every week**
  - Supported **10+ partner integrations**
  - Reduced operational dependence by moving manual financial workflows into safe, controlled automation

---

### Full Stack Engineer — CreditBook (Remote)

`Oct 2024 – Dec 2025`

- Contributed to systems supporting **6B+ PKR** in financial activity and **1M+ SMEs**
- Built internal **KYC/KYB compliance infrastructure** with review, rejection, resubmission, and operator visibility
- Engineered **idempotent bulk disbursement pipelines** processing **100s of loans instantly**
- Reduced Ops workload by **65%** through reliable automation of previously manual processes
- Improved API and webhook performance by **40%** through caching, query optimization, and better async flow design
- Contributed to **double-entry accounting infrastructure** where financial correctness and traceability were critical
- Built E2E automation suites for multi-product lending flows using **Playwright + Python**

---

## Previous Experience

### Software Engineer (Full Stack) — Webwrite Inc.

`May 2023 – Oct 2024`

Built **HIPAA-compliant telehealth systems** for the **US, Japan, and Australia**.

This experience mattered because it forced me to think beyond “features” and into:

- regulated workflows
- access control correctness
- secure auditability
- sensitive data handling
- infrastructure decisions with compliance implications
- product flows where operational mistakes have real downstream consequences

Key work:

- Built **3 production telehealth platforms**
- Led **Twilio Video → Zoom SDK migration**
- Worked on EHR / practice management systems aligned with **FHIR / HL7**
- Implemented secure audit logging and protected clinical workflows
- Integrated **Stripe, Square, PayPal**, and regional payment systems

---

### Associate Software Engineer — Digital Dynamics (Remote, Slovenia)

`June 2022 – Apr 2023`

- Built an event ticketing platform with real-time inventory, QR ticketing, and fraud prevention
- Integrated **Bankart** payment APIs for payment processing, transfers, and merchant payouts
- Worked on transactional flows where timing, correctness, and payment state integrity mattered

---

## Engineering Philosophy

I’m most valuable in systems where:

- the happy path is easy
- the edge cases are expensive
- third parties are inconsistent
- the business logic evolves constantly
- human operations still matter
- and the software has to stay reliable anyway

I like building software that turns **operational chaos into controlled systems**.

Not flashy systems.  
**Trustworthy systems.**

---

## Featured Projects

### 🤖 Mentools — AI-Powered Fitness Platform

**LangChain · Multi-agent orchestration · RAG · Pinecone**

- Built agentic workflows for personalized fitness planning
- Indexed **10K+ protocols / documents**
- Used **RAG pipelines + vector search + memory-aware orchestration**
- Focused on practical, autonomous decision support rather than gimmicky chat UX

### 🎟️ The Muslim Ticket — Event Ticketing SaaS

**Multi-tenant · Real-time inventory · Payments · Operator tooling**

- Built a multi-tenant event platform for independent organizers
- Real-time seat selection and ticket availability
- QR ticket generation, organizer dashboards, and payment integrations
- Operational tooling for organizers and event teams

### 🏥 American Clinic Online — Telehealth Platform

**HIPAA-compliant · Video consultations · Messaging · Scheduling**

- Secure telehealth platform spanning multiple countries
- Video consultations, appointment scheduling, and messaging
- CI/CD via **Docker + GitHub Actions + AWS**

---

## Tech Stack

### Core Languages

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend / Reliability / Infra

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/Nest.js-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-red?style=for-the-badge&logo=redis&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

### Frontend / Product

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

### AI / LLM Stack

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)

### Cloud / DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Open To

- Senior Full Stack / Platform / Product Engineering roles
- Fintech infrastructure and payments-heavy systems
- Reliability-heavy backend and workflow orchestration work
- AI-native product teams building real operational software
- Select consulting opportunities where correctness and production quality matter

---

## Connect

- 🌐 **Portfolio:** [jamshaidjavaid.netlify.app](https://jamshaidjavaid.netlify.app/)
- 💼 **LinkedIn:** [linkedin.com/in/jamshaid-javaid](https://linkedin.com/in/jamshaid-javaid)
- 🐦 **Twitter / X:** [twitter.com/jamshaidjavaid\_](https://twitter.com/jamshaidjavaid_)
- 📧 **Email:** [jamshaidjavaid360@gmail.com](mailto:jamshaidjavaid360@gmail.com)

---

<p align="center"><i>Building serious software where correctness, resilience, and trust matter.</i></p>
