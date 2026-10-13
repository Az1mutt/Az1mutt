# Igor Mego 👋

**Data & Analytics Engineer | Microsoft Fabric · PySpark · SQL · Delta Lake | Agentic AI Systems**

I work in the energy sector, turning ambiguous business and domain problems into reliable analytical datasets and reusable data solutions. My professional work is centered around **Microsoft Fabric, PySpark, Spark SQL, SQL, Delta Lake, data quality, temporal/high-frequency data, and Power BI**.

Outside work, I build end-to-end systems around **agent architecture, guarded automation, databases, APIs, Linux, Docker, and self-hosted infrastructure**. I care a lot about provenance, explicit state, testable boundaries, and making automation earn its permissions rather than hiding them in prompts.

[LinkedIn](https://www.linkedin.com/in/igor-mego-06ab79238/)

## What I bring

- **Data engineering with domain context** — translating messy real-world rules into trustworthy data products, not just moving rows from A to B.
- **Data quality & semantics** — temporal logic, provenance, controlled concepts/relationships, validation, and explainable business rules.
- **Agentic engineering mindset** — agent/tool contracts, approval boundaries, idempotency, auditability, durable state, bounded execution, and human escalation where ambiguity matters.
- **End-to-end ownership** — from data/model design through Python/SQL implementation to Docker/Linux runtime and operational validation.

## Featured projects

### 🧠 [Personal AI Brain](https://github.com/Az1mutt/personal-ai-brain)

A local-first agent platform for coordinating projects, tools, and future autonomous workflows.

The current implementation includes:

- machine-readable durable Project OS state;
- explicit agent contracts, tool permissions, and approval boundaries;
- a deterministic read-only Core Agent;
- a bounded control plane;
- remote work submission with persistent task state;
- duplicate/replay protection, cancellation, interruption handling, and auditability;
- isolated execution with separate identities and credentials;
- automated tests and CI.

The architecture deliberately separates **reasoning capability from execution permission**. LLM planning and broader autonomy are introduced only after the underlying execution and policy boundaries are explicit and testable.

### 🍳 [Recipe Intelligence System](https://github.com/Az1mutt/recipe-intelligence-system)

A PostgreSQL/Supabase data product for structured culinary knowledge, provenance, ingestion, classification, personal preference modeling, and future AI-assisted workflows.

Its guarded-agent design separates:

**Discovery → Resolution → Classification → QA/Review → deterministic Promotion**

The workflow uses evidence-backed claims, explicit escalation rules, idempotency, constrained write authority, and deterministic promotion after approval. A real creator-scale pilot was used to validate the role boundaries before broader automation.

### 🏠 [Homelab Infrastructure](https://github.com/Az1mutt/homelab-infrastructure)

A dedicated Ubuntu Server environment for self-hosting, infrastructure learning, and running personal engineering projects.

The repository documents a real migration from a laptop-hosted stack to a dedicated server, including Docker services, storage migration, rollback strategy, recovery checks, monitoring, and application-level validation.

## Professional stack

**Data:** Microsoft Fabric · PySpark · Spark SQL · SQL · Delta Lake · Power BI · PostgreSQL  
**Engineering:** Python · Git/GitHub · CI · APIs · Docker · Linux · Supabase  
**System design:** data quality · temporal modeling · provenance · domain semantics · agent contracts · approval boundaries · durable state · guarded automation

## Current direction

I'm especially interested in engineering work where **reliable data, domain semantics, and AI/agent systems meet** — building useful systems that can survive contact with real users, messy data, partial failure, and changing requirements.

---

> Build the deterministic parts deterministically. Use AI where judgment adds value. Keep the boundaries explicit.
