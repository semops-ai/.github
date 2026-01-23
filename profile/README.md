# SemOps-Ai

> Open source infrastructure for AI-forward organizations built on Semantic Operations.

---

## Why "Semantics"

Why "Semantic Operations" and why do so many other components and concepts contain the word "semantic"?.

"Semantics" is "meaning", and I believe that meaning plays an extra-pivotal role in AI and analytics. Semantics is just meaning that is explicit, validated, and encoded - in other words, meaning structures that machines and humans can work with. When I began working on what would become the Semantic Operations (SemOps), "semantics" wasnt't a goal or focus, but as I continued to understand and build more, it asserted itself as the  central concept.

---

## What is Semantic Operations?

> **Semantic Operations (SemOps)** is a practical, actionable framework for businesses to align their technology and organization to materially benefit from the use of data, AI, and agentic systems.

**Core thesis:** Shared semantic context enables better human+AI collaboration. When meaning is explicit, structured, and maintained, AI agents become reliable collaborators instead of unpredictable tools.

### Problem Space

> What is AI good at? 
> What conditions optimize for its strengths? 
> Which of those conditions also improve non-AI challenges?
> If these conditions exist, what other optimizations for humans and machines are possible?

### Four Pillars

| Pillar | What It Solves |
|--------|----------------|
| **[Symantic Funnel](../../semops-docs/SEMANTIC_OPERATIONS_FRAMEWORK/semantic-funnel.md)** | A mental model to ground solutions in foundational human and organizational space. |
| **Strategic Data** | Data as first-class citizen. Structure enables AI; AI accelerates structure. |
| **Symbiotic Architecture** | Your software = your organization = your product. DDD at enterprise scale. |
| **Semantic Optimization** | Measuring and maintaining *meaning* as operational infrastructure. |

---

## Repository Map

```
semops-dx-orchestrator [PLATFORM / DX]
│
│   Process docs, global architecture, cross-repo coordination
│   The entry point for humans and AI agents
│
└── semops-core [SCHEMA / INFRASTRUCTURE]
    │
    │   Global schema, knowledge graph, shared services
    │   The "semantic operations" hypothesis implemented
    │
    ├── semops-publisher [PUBLISHING]
    │   AI-assisted content workflow
    │
    ├── semops-data [PRODUCT]
    │   Data engineering utilities, research RAG pipeline
    │
    └── semops-sites [FRONTEND]
        Public-facing websites and deployed applications
```

### Repositories

See [Repository Operational Model](../../semops-dx-orchestrator/docs/repository-operational-model.md) for an explanation of how this multi-repo model aligns with sound agentic practices as well as Semantic Operations.

| Repo | Purpose | Status |
|------|---------|--------|
| [semops-dx-orchestrator](https://github.com/semops-ai/semops-dx-orchestrator) | Orchestration layer - process, tooling, global architecture | Active |
| [semops-core](https://github.com/semops-ai/semops-core) | Schema and infrastructure - knowledge graph, shared services | Active |
| [semops-publisher](https://github.com/semops-ai/semops-publisher) | AI-assisted content publishing workflow | Active |
| [semops-data](https://github.com/semops-ai/semops-data) | Data engineering utilities and research RAG pipeline | Active |
| [semops-sites](https://github.com/semops-ai/semops-sites) | Public-facing websites and deployed applications | Active |

---

## Getting Started

### For Exploration

Start with [semops-dx-orchestrator](https://github.com/semops-ai/semops-dx-orchestrator) - it contains the global architecture documentation and entry points.

Review the [Global Architecture](../../semops-docs/SEMANTIC_OPERATIONS_FRAMEWORK/GLOBAL_ARCHITECTURE_PROPOSED.md) being built to support a robust test-bed for SemOps.



### For Data Engineering

Check [semops-data](https://github.com/semops-ai/semops-data) for the research RAG pipeline and data utilities.

### For Infrastructure

See [semops-core](https://github.com/semops-ai/semops-core) for schema definitions, Docker infrastructure, and knowledge graph setup.

---

## Tech Stack

| Layer | Technologies |
|-------|--------------|
| **Database** | PostgreSQL (Supabase), Neo4j (graph) |
| **Vectors** | Qdrant, pgvector |
| **ML/Embeddings** | Ollama (local), OpenAI |
| **Document Processing** | Docling (PDF/DOCX), Crawl4AI (web) |
| **Orchestration** | n8n, Python |
| **Frontend** | Next.js, React, Tailwind, Vercel |
| **AI** | Anthropic Claude, OpenAI |

---

## About

**SemOps.ai Labs** is maintained by [Tim Mitchell](https://timjmitchell.com) - a product leader with 20+ years experience at Microsoft, Amazon, and Roku, now focused on practical AI integration strategies.

**Website:** [semops.ai](https://semops.ai)
**LinkedIn:** [linkedin.com/in/timjmitchell](https://linkedin.com/in/timjmitchell)

---

## License

All repositories in this organization are licensed under [AGPL-3.0](LICENSE) unless otherwise noted.
