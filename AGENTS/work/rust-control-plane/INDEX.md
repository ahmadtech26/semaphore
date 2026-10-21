# rust-control-plane — zone index

A new self-hosted control plane inspired by Semaphore and Komodo (not a fork or a fusion): Rust core and
agent, Postgres as system of record, Valkey/Redis for coordination, OpenSearch/Elasticsearch as a derived
search index, an Angular frontend. Covers strategy and licensing, the domain model, the data tier, the
agent, WebAssembly boundaries, security, MVP, roadmap and spikes.

| When you need it | Read |
| --- | --- |
| Deciding whether to build the platform, under which licence, and what may be borrowed from Semaphore (MIT) and Komodo (GPL-3.0) | `architecture-exploration.md` |
| Deciding what Redis/Valkey and Elasticsearch/OpenSearch may and may not hold, or which engines to ship versus accept | `architecture-exploration.md` |
| Designing leases, the command outbox, the log pipeline, search indexing or failover behaviour | `architecture-exploration.md` |
| Choosing the frontend framework and its libraries (Angular vs React, log viewer, Monaco, xterm, DAG editor) | `architecture-exploration.md` |
| Designing the dial-out agent, enrollment, job isolation, cancellation or offline behaviour | `architecture-exploration.md` |
| Reviewing tenant isolation, secrets, plugin sandboxing or agent blast radius | `architecture-exploration.md` |
| Scoping an MVP, roadmap or spikes for the platform | `architecture-exploration.md` |
