# SemOps.ai Labs

> Open source infrastructure for AI-forward organizations built on semantic operations principles.

---

## What is Semantic Operations?

**Semantic Operations (SemOps)** is a framework for aligning technology and organization to materially benefit from AI. It addresses the fundamental problem: AI amplifies organizational gaps, it doesn't fix them.

**Core thesis:** Shared semantic context enables better human+AI collaboration. When meaning is explicit, structured, and maintained, AI agents become reliable collaborators instead of unpredictable tools.

**Three Pillars:**

| Pillar | What It Solves |
|--------|----------------|
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

| Repo | Purpose | Status |
|------|---------|--------|
| [semops-dx-orchestrator](https://github.com/semops-ai/semops-dx-orchestrator) | Orchestration layer - process, tooling, global architecture | Active |
| [semops-core](https://github.com/semops-ai/semops-core) | Schema and infrastructure - knowledge graph, shared services | Active |
| [semops-publisher](https://github.com/semops-ai/semops-publisher) | AI-assisted content publishing workflow | Active |
| [semops-data](https://github.com/semops-ai/semops-data) | Data engineering utilities and research RAG pipeline | Active |
| [semops-sites](https://github.com/semops-ai/semops-sites) | Public-facing websites and deployed applications | Active |

---

## Key Concepts

### Pattern as Aggregate Root

SemOps implements Domain-Driven Design with **Pattern as the aggregate root** - a reusable unit of meaning with a business purpose. Patterns are:

- **Measured** for semantic coherence (stability, availability, consistency)
- **Versioned** with explicit provenance (1P innovation vs 3P adoption)
- **Connected** via typed edges in a knowledge graph

### The Semantic Flywheel

AI needs structure to operate well. AI is also good at creating structure. This creates a virtuous cycle:

1. Human-defined structure enables AI to produce better outputs
2. Better outputs feed back as structured artifacts
3. More structure enables better AI
4. Each turn improves semantic coherence

### Stable Core, Flexible Edge

Growth happens at the edge (new patterns, experiments, drafts). Stability lives in the core (approved patterns, schemas, production). The lifecycle:

```
Orphan → Classified → Approved → Core
  │          │           │         │
  │          │           │         └─ Stable, measured
  │          │           └─ Production-ready
  │          └─ Typed, validated
  └─ New, unstructured
```

---

## Getting Started

### For Exploration

Start with [semops-dx-orchestrator](https://github.com/semops-ai/semops-dx-orchestrator) - it contains the global architecture documentation and entry points.

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
