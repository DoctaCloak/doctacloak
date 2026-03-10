# Christopher Taylor (doctacloak)

Senior Software Engineer focused on **distributed systems, platform engineering, and cloud-native infrastructure**.
I build systems where **cost, latency, reliability, and failure modes** are first-class design constraints—not afterthoughts.

My work sits at the intersection of **application development**, **platform architecture**, and **real-world operational constraints**, spanning enterprise cloud environments, resource-constrained edge systems, and AI-powered knowledge platforms.

---

## What I Work With

- **Cloud & Platform:** Azure, Kubernetes (AKS), GitOps, Infrastructure as Code
- **Distributed Systems:** multi-tenant architectures, caching strategies, failure-mode design
- **Edge & Hybrid:** Raspberry Pi 5 edge nodes paired with Azure control planes
- **AI/ML:** LLMs, RAG pipelines, hybrid retrieval, agent orchestration, MCP/Skills architecture, voice synthesis
- **Observability & Reliability:** Prometheus, Grafana, OpenTelemetry
- **Application Engineering:** React, Next.js, TypeScript, Python, FastAPI, WebSockets

---

## Things I'm Building

### Cortex — Personal Knowledge Platform
**"Dropbox for your mind."** One app that replaces Obsidian, ChatGPT, Anki, and Trello.

Knowledge graph, AI assistant with voice synthesis, flashcards with spaced repetition, kanban boards with task sharing, video ingestion, and semantic recall under 50ms — all connected.

**Key architecture:**
- **Skills/Gateway** — sandboxed Kubernetes pods with scoped permission manifests and multi-channel routing (web, WhatsApp, Slack, Discord, voice). Extensibility without exposing user data.
- **Hybrid Retrieval** — semantic embeddings, keyword search, graph-derived importance, and recency scoring fused into one query.
- **Zettelkasten Graph** — 900+ notes, 1,000+ links, with consistency-on-retrieval checking.
- **RUMAD** — multi-perspective debate protocol for architecture decisions with content-agnostic topology control.
- **Sentinel** — arXiv monitoring pipeline scanning 20+ subject categories, scoring relevance against the knowledge graph.
- **Observatory** — benchmarking system comparing static vs. dynamic context performance (+20% task success vs. no-context baselines).
- **Storage Monetization** — free 50MB (students), Pro 5GB ($12/mo), Agent 20GB ($39/mo) with add-on storage packs.

Tech: Next.js 15, TypeScript, Redux, FastAPI, Python, ChromaDB, Memgraph, ElevenLabs, Tailwind CSS, Kubernetes

> **Live:** https://cortex-nine-bice.vercel.app

---

### Hybrid Cloud / Edge Lab
A hybrid platform pairing **Raspberry Pi 5 edge nodes** with **Azure-based cloud services**, intentionally designed to surface real-world challenges such as:

- intermittent connectivity
- constrained compute
- partial failure
- latency variability

This lab mirrors failure patterns I've seen in production systems and serves as a proving ground for platform, reliability, and recovery decisions.

> https://github.com/doctacloak/homelab *(update with actual repo)*

---

### Crow Platform
A multi-tenant civic intelligence platform focused on **cost-efficient data access**, **strict tenant isolation**, and **scalable ingestion**.

Key outcomes:
- Order-of-magnitude API cost reduction through architectural caching and request optimization
- Sub-millisecond response paths where latency matters
- Clear blast-radius boundaries and zero data leakage across tenants

---

## Areas I'm Going Deeper (2026)

### Platform & Cloud Engineering
- Kubernetes operations and troubleshooting
- GitOps workflows (Argo CD)
- Infrastructure automation and policy enforcement
- Observability-driven reliability engineering
- Hybrid cloud failure-mode testing

### AI Knowledge Infrastructure
- Sandboxed skill execution on Kubernetes with scoped permissions
- Multi-channel AI access (messaging platforms, voice, API)
- Knowledge graph architectures for persistent agent memory
- Voice-enabled AI assistants with graph-grounded retrieval

### Unreal Engine 5 (C++)
This year I'm going deep into **Unreal Engine 5** from the ground up, with a deliberate focus on:

- **C++ systems programming** inside a large-scale engine
- Engine architecture, memory ownership, and performance tradeoffs
- Real-time simulation constraints (latency, determinism, resource budgets)
- Bridging engine-level systems thinking with distributed and platform concepts
- **MCP integration** — building custom tool servers that connect AI agents to the Unreal Editor

The goal is not game "content," but a deeper understanding of **real-time systems, performance-critical C++ codebases, and engine-level architecture**.

Progress, experiments, and notes will live here as they mature.

---

## Learning in Public

I document what I build and learn—especially the parts that break—so others can learn from **real constraints instead of idealized diagrams**.

Common themes:
- Hybrid cloud & edge architecture
- Platform reliability and observability
- Kubernetes operations at scale
- AI knowledge infrastructure and agent memory
- Real-time systems and performance tradeoffs

---

## Philosophy

### A quote from the Master
"Once you decide on your occupation, you must immerse yourself in your work. You have to fall in love with your work. Never complain about your job. You must dedicate your life to mastering your skill. That's the secret of success and is the key to being regarded honorably."

**Jiro**


I care deeply about craftsmanship and long-term systems health.

> Build boring systems that fail predictably.
> Optimize for clarity, blast radius, and recovery—not novelty.

If you're working on **mission-critical systems**, **platform engineering**, **distributed infrastructure**, **AI knowledge systems**, or **real-time systems**, we'll probably have good conversations.

---

📫 **Connect**
- LinkedIn: https://www.linkedin.com/in/doctacloak/
- GitHub: https://github.com/doctacloak
