# Jay Burgess

### Founder & Principal Forward Deployed Engineer, Revuity Systems

> _I embed with teams to scope, build, harden, and hand off production AI systems fast — with AI-assisted development (Claude Code)._

15+ years building production data, AI, and software systems across **Fortune 500 enterprises** (Walmart, Adobe), **federally regulated domains**, and **venture-scale startups**. I ship full applications end to end — the data layer, the backend services, the runtime AI components, and the user-facing surface. I don't just architect; I build, ship, and hand off.

Currently: Founder & Principal Forward Deployed Engineer, [Revuity Systems](https://revuitysys.com) · Principal Forward Deployed Engineer at HEAG (concurrent) · Los Angeles, CA

---

## How I Engage

Forward deployed means I work inside your team, not adjacent to it. The loop:

**Scope → Prototype → Harden → Hand off**

- **Scope** — Technical discovery and working sessions with the operators who actually live in the problem. I translate evolving requirements, including federal regulation, into decomposed and shippable build plans.
- **Prototype** — Working software in front of real users fast. AI-assisted development with Claude Code compresses the build cycle; specification decomposition and plan-mode gating keep it controlled.
- **Harden** — Row-level isolation, role-based authorization, audit logging, evaluation checks, and human-in-the-loop review before anything regulated reaches a user.
- **Hand off** — Every build ships with setup docs, an operations runbook, architecture decision records, and a recorded walkthrough, so the receiving team runs the system without me in the room.

---

## Production Work & Outcomes

### ReggieAI — multi-agent compliance in a federally regulated domain

Title IV financial aid administration is unforgiving: the rules change by federal rulemaking, every determination has to be defensible to an auditor, and a confidently wrong answer is a compliance event, not a bug.

I architected ReggieAI as a multi-agent system on Claude, LangGraph, and MCP, built around the constraint that **no generated output reaches a regulated decision without a human in the loop**. Deterministic tool routing keeps policy execution out of the model's discretion — the model interprets and drafts, but the rules themselves run as code. Structured outputs and evaluation checks gate every response, and audit logging captures the full chain so a reviewer can reconstruct why a determination was made. A compliance knowledge pipeline handles email intake, routes through a human QA review interface, and dispatches to the knowledge base only after sign-off.

It runs in production today against real student queries. It produced **$2.7M in new client revenue within three weeks of rollout** and lifted case processing capacity **25% without added headcount**.

### Other delivery outcomes

- **OpsFlow** — replaced Jira with a custom operational execution platform aligned to federal regulation, shipped end to end with Claude Code, FastAPI, and Next.js. Reporting cycle time down 40%.
- **Multi-tenant SaaS platforms** — Next.js, FastAPI, and Supabase with custom MCP servers, role-based authorization, and audit logging. Client onboarding time down 65%.
- **Stateful multi-agent workflows** — persisted checkpoints, async task execution, and deterministic tool routing built for human review and regulatory auditability. Compliance review turnaround down 50%.
- **Adobe** — unified enterprise pipelines orchestrated with Airflow on AWS, tracking $6B in global marketing spend. Executive reporting turnaround down 86%.
- **Walmart** — statistical anomaly detection embedded in the transformation layer to surface production bottlenecks and spend spikes. Project completion rates up 37%.

---

## What I Build

**Core Domains**

- **Agentic AI in Production** — Multi-agent orchestration, deterministic tool routing, structured outputs, evaluation harnesses, guardrails, and human-in-the-loop review
- **Full-Stack Ownership** — Data pipelines and schemas, backend services and APIs, runtime LLM components, and the web front end. One person, every layer.
- **Regulated & Rights-Sensitive Delivery** — Federal Title IV systems, Fortune 500 marketing spend data, multi-tenant platforms with row-level isolation and audit logging
- **AI-Assisted Development** — Claude Code as daily production practice: specification decomposition, plan-mode gating, and review of generated code at velocity
- **Data Platform Engineering** — Lakehouse and warehouse foundations, medallion architecture, governed semantic models

---

## Featured Engineering Repos

### Agentic AI & Forward Deployed Work

- [`eligibility-agent`](https://github.com/jayburgessjr/eligibility-agent) — LangGraph + MCP reference agent for eligibility routing in regulated domains. Sanitized architecture distilled from production compliance work.
- **ReggieAI** _(private — production system)_ — Multi-agent Title IV compliance platform with structured knowledge base, deterministic guardrails, and audit logging
- [`revuity-agentic-os`](https://github.com/jayburgessjr/revuity-agentic-os) — Claude Code plugin packaging my build system: phase routing, prompt surfacing, and structured session retrospectives. How I actually run agent-assisted delivery.
- [`prospecting-agent`](https://github.com/jayburgessjr/prospecting-agent) — Production prospecting agent: lead ingestion and enrichment, a deterministic multi-step cadence, and personalization constrained inside explicit guardrails
- [`ai-revenue-optimization-ltv-churn-uplift`](https://github.com/jayburgessjr/ai-revenue-optimization-ltv-churn-uplift) — Churn + LTV + uplift targeting system; models as execution levers, not decoration

### Data Platform & Architecture

- [`modern-data-platform-template`](https://github.com/jayburgessjr/modern-data-platform-template) — End-to-end lakehouse blueprint: raw → staging → core → marts → tests → governance
- [`Databricks-Lakehouse-Foundation`](https://github.com/jayburgessjr/Databricks-Lakehouse-Foundation) — Medallion architecture on Databricks + Delta Lake with ingestion patterns and platform guardrails
- [`Higher-Ed-Lakehouse-Analytics-on-Databricks`](https://github.com/jayburgessjr/Higher-Ed-Lakehouse-Analytics-on-Databricks) — Governed analytics for regulated higher ed environments: retention, equity, audit-ready reporting
- [`cognos-to-looker-migration-framework-finaid-admissions-registrar`](https://github.com/jayburgessjr/cognos-to-looker-migration-framework-finaid-admissions-registrar) — Migration framework from a real university engagement: inventory, lineage, KPI standardization, validation

---

## Shipping Velocity — Revuity Systems Products

> Revuity Systems is a lean, product-led AI-first software company. These are zero-to-deployed builds, most of them solo. They are the evidence behind the delivery speed.

| Product                                                                 | What It Does                                                                                                                                                                                                              | Stack                         |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| **[Helm](https://helm.revuitysys.com/)**                                | Software-first fractional CIO. Sign up and get an AI-driven system inventory, risk flags, and a draft roadmap without talking to a human first — then escalate any recommendation to a human CIO when it matters.         | React · Supabase · Claude     |
| **[Hired](https://hired.revuitysys.com/)**                              | Interview intelligence for job seekers who want to show up as themselves — not a script. Personalized talking points, authenticity detection, and a readiness score built from your resume and the job description.       | React · Supabase · TypeScript |
| **[Signal](https://signal.revuitysys.com/)**                            | AI social media director for authors, speakers, coaches, and thought leaders. Strategy, drafting, scheduling, and analytics — without making content creation a second job.                                               | React · Supabase · TypeScript |
| **[AI Agentic Engineering Academy](https://aiagenticengineering.pro/)** | Three complete programs for engineers, FDEs, and managers. 122 free chapters, AI tutor grounded in the curriculum, and verifiable credentials employers can look up.                                                      | React · Supabase · TypeScript |
| **[Build Wealth Here](https://wealthos.revuitysys.com/)**               | AI signals, risk controls, 50+ decision tools, and two AI advisors in one decision loop — stocks, crypto, options, and prediction markets, consolidated.                                                                  | React · Supabase · TypeScript |
| **[MenuProfitPro](https://menuiq.revuitysys.com/)**                     | Analyzes recipes, costs, and pricing to show restaurant operators exactly which dishes make money and which drain margin. Food cost made visible, actionable, and automatic.                                              | React · Supabase · TypeScript |
| **[VoltIQ](https://voltiq.revuitysys.com/)**                            | Vertical market intelligence for LA solar contractors operating post-NEM 3.0. Weekly zip-code-level permit velocity, $/W benchmarks, and battery attachment rates, so installers price against data instead of guesswork. | React · Supabase · TypeScript |
| **[GrantEdge](https://meridian.revuitysys.com/)**                       | Competitive intelligence for nonprofits pursuing federal grant funding — who is winning awards, in what programs, and where the open lanes are.                                                                           | React · Supabase · TypeScript |

Also shipped and live: [ProductionOS](https://indieos.revuitysys.com/) (film production pipeline) and [GameNightz](https://gamenightz.online/) (multiplayer party games). [CIOReview](https://cioreview.revuitysys.com/) (technology leadership commentary) is live; CertPath is in development.

---

## Tech Stack

**Languages:** Python · TypeScript · JavaScript · SQL

**Agentic & Production AI:** Claude · Model Context Protocol (MCP) · LangGraph · multi-agent orchestration · RAG · prompt architecture · tool calling · structured outputs · evaluation harnesses · human-in-the-loop review · guardrails

**AI-Assisted Development:** Claude Code · agentic build workflows · plan-mode gating · generated-code review at velocity

**Backend & Full Stack:** FastAPI · asyncio · Node.js · Next.js · React · Vite · Tailwind · shadcn/ui · REST APIs · webhooks

**Data & Storage:** PostgreSQL · pgvector · Supabase · SQL Server · dbt · PySpark · Apache Airflow · Databricks · Microsoft Fabric · Power BI

**Cloud & Infrastructure:** AWS (S3, EMR, Redshift) · Azure · Docker · CI/CD · GitHub Actions · GitLab · Netlify

**Security & Governance:** Row-level security · role-based authorization · audit logging · deterministic policy execution · data quality validation · regulatory auditability

**Engagement Practice:** Technical discovery · stakeholder workshops · solution architecture · production deployment · runbooks and handoff · team coaching

---

## For Recruiters & Hiring Managers

| If you're evaluating me for...         | Start here                                                                                                                                                                                                                                        |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Forward Deployed Engineer (Agentic AI) | [`eligibility-agent`](https://github.com/jayburgessjr/eligibility-agent) → [`revuity-agentic-os`](https://github.com/jayburgessjr/revuity-agentic-os)                                                                                             |
| AI / Agentic Systems                   | [`eligibility-agent`](https://github.com/jayburgessjr/eligibility-agent) → [`ai-revenue-optimization-ltv-churn-uplift`](https://github.com/jayburgessjr/ai-revenue-optimization-ltv-churn-uplift)                                                 |
| Full-Stack / Product Engineering       | [`stratfordsys`](https://github.com/jayburgessjr/stratfordsys) → [`tradeflow`](https://github.com/jayburgessjr/tradeflow)                                                                                                                         |
| Regulated Industry / Higher Ed         | [`eligibility-agent`](https://github.com/jayburgessjr/eligibility-agent) → [`cognos-to-looker-migration-framework-finaid-admissions-registrar`](https://github.com/jayburgessjr/cognos-to-looker-migration-framework-finaid-admissions-registrar) |
| Data Platform / Lakehouse              | [`Databricks-Lakehouse-Foundation`](https://github.com/jayburgessjr/Databricks-Lakehouse-Foundation) → [`modern-data-platform-template`](https://github.com/jayburgessjr/modern-data-platform-template)                                           |

---

## Credentials & Writing

**Certifications:** Certified Forward Deployed Engineer (CFDE) · Certified Agentic Engineer (CAE) · Claude Partner Badge, Claude Code (Anthropic) · Graduate Certificate in Artificial Intelligence, Harvard Business School Executive Education

**Books:** _Agentic Engineering: Building Autonomous AI Systems That Actually Work_ · _The Agentic Builder: Field Notes on Product Development_

---

## Connect

[LinkedIn](https://linkedin.com/in/jayburgessjr) · [jay-burgess.me](https://jay-burgess.me) · [Revuity Systems](https://revuitysys.com) · Email: [jay@revuitysys.com](mailto:jay@revuitysys.com)

---

_Everything here is structured the way I'd harden it for production — observable, governed, and built to run without me in the room._
