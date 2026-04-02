# Semantic Operations (SemOps)

**Semantic Operations (SemOps)** is a framework for aligning technology and organization so that data, AI, and agentic systems deliver business value. Semantics is meaning made explicit, validated, and encoded — structures that both humans and machines can work with. The conditions that make AI work well are the same conditions that make organizations work well, and both depend on shared, explicit meaning.

## SemOps Goals

**Focus:** Driving business value through data, AI, and analytics.
**Goal:** Organization-wide improvements for technical and non-technical teams.

1. Understand what AI is actually good at (and what it isn't)
2. Build the conditions AI needs to do what it's good at
3. Recognize that most of these conditions are things you should do anyway
4. Deploy specific solutions that both build the conditions and employ AI for maximum benefit

## What's Here

This is the GitHub home for **Semantic Operations (SemOps)**, maintained by [Tim Mitchell](https://timjmitchell.com). These repos are the open-source implementation — architecture, infrastructure, and working examples built on the framework's principles. For the concepts, theory, and a broader overview of Semantic Operations, see [semops.ai](https://semops.ai).

| Repository | What It Does |
| ---------- | ----------- |
| [semops-orchestrator](https://github.com/semops-ai/semops-orchestrator) | System architecture, cross-repo coordination, and design principles |
| [semops-data](https://github.com/semops-ai/semops-data) | Domain schema, knowledge base, and shared infrastructure services |
| [semops-research](https://github.com/semops-ai/semops-research) | Research pipeline, corpus meta-analysis, and reference catalogs |
| [semops-docs](https://github.com/semops-ai/semops-docs) | Framework theory, concepts, and foundational research |
| [ridgeline-demo](https://github.com/semops-ai/ridgeline-demo) | Reference engagement — full outside-in pipeline for a fictional D2C brand |

**Start here:** [semops-orchestrator](https://github.com/semops-ai/semops-orchestrator) explains how the multi-repo system works and how to navigate across repos.

## The Framework

SemOps is built on one mental model and three pillars:

- **[Semantic Funnel](https://github.com/semops-ai/semops-docs/blob/main/RESEARCH/FOUNDATIONS/semantic-funnel.md)** — A model that reduces any knowledge work process to three entities (objects, agents, rules) transforming through levels of understanding. It gives practitioners a shared vocabulary across technical, organizational, and cognitive contexts.

- **[Strategic Data](https://github.com/semops-ai/semops-docs/blob/main/SEMANTIC_OPERATIONS_FRAMEWORK/STRATEGIC_DATA/README.md)** — Treating data as a first-class strategic asset. Most data failures are organizational, not technical — fragmented ownership, missing literacy, schema treated as afterthought. Strategic Data provides the diagnostic tools and governance methods to fix that.

- **[Explicit Architecture](https://github.com/semops-ai/semops-docs/blob/main/SEMANTIC_OPERATIONS_FRAMEWORK/EXPLICIT_ARCHITECTURE/README.md)** — Encoding strategy into systems so humans and AI operate from shared structure. Clear domain boundaries, simplified systems, and a flywheel where AI accelerates the encoding work and that structure makes AI more effective.

- **[Semantic Optimization](https://github.com/semops-ai/semops-docs/blob/main/SEMANTIC_OPERATIONS_FRAMEWORK/SEMANTIC_OPTIMIZATION/README.md)** — Measuring and improving [semantic coherence](https://github.com/semops-ai/semops-docs/blob/main/SEMANTIC_OPERATIONS_FRAMEWORK/SEMANTIC_OPTIMIZATION/semantic-coherence.md) where decisions are made. This is where AI becomes a partner in growth — converting business systems into measurable improvement through patterns, not features.

Each pillar provides value independent of AI. Together, they create an environment where AI performs better because it has coherent context, and organizations perform better because their meaning is managed.

## The Implementation as Proof

These repos are not just documentation of the framework — they are the framework applied to itself. Every pillar of SemOps is tested in the implementation that produces it.

**Strategic Data in practice.** [semops-data](https://github.com/semops-ai/semops-data) treats the domain model as a first-class data asset: knowledge matures through quality tiers (raw, enriched, curated), every classification decision is tracked with provenance, and three complementary stores (relational, vector, graph) serve the same model through different access patterns. [semops-research](https://github.com/semops-ai/semops-research) builds the measurement infrastructure — coherence scoring experiments that test how well content aligns with its source patterns, using embedding similarity, NLI contradiction detection, and LLM-as-judge approaches.

**Explicit Architecture in practice.** The [orchestrator](https://github.com/semops-ai/semops-orchestrator) encodes Domain-Driven Design into the repo structure itself: each repo is a bounded context with clear ownership, integration patterns (Shared Kernel, Customer-Supplier, Partnership) are formalized rather than implicit, and a Pattern — a semantic unit from the domain model — is the aggregate root that everything traces back to. Architecture drives infrastructure choices, not the reverse.

**Semantic Optimization in practice.** [ridgeline-demo](https://github.com/semops-ai/ridgeline-demo) demonstrates the full outside-in pipeline applied to a fictional D2C brand — from business model decomposition through pattern-scaffolded scoring to agent prescriptions. [semops-research](https://github.com/semops-ai/semops-research) provides the research pipeline that onboards new patterns into the domain model, adapts the framework to new domains, and ingests technical documentation for agentic infrastructure management.

You are welcome to study the architecture, adapt patterns, and learn from the decisions. This is not a library to install or a service to deploy — it is a proving ground that demonstrates the approach at small scale while designing for enterprise applicability.

## Learn More

- **[semops.ai](https://semops.ai)** — Concepts, framework explanations, and the full case for why meaning matters
- **[timjmitchell.com](https://timjmitchell.com)** — Blog, thought leadership, and the story behind SemOps
- **[semops-orchestrator](https://github.com/semops-ai/semops-orchestrator)** — Architecture deep dive and implementation guide
