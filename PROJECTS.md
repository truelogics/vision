---
doc: PROJECTS
audience: [human, agent]
status: living
owner: vision
last_reviewed: 2026-08-03
---

# Projects

> Index of initiatives and which repo owns them.

| Project | Repo | Status | Notes |
|---------|------|--------|-------|
| Engineering Kernel | [`engineering-kernel/`](../engineering-kernel/) | v0.1.0-alpha, architecture frozen | The OS kernel — index, search, graph, hybrid ranking, context assembly, and a public Go SDK (`pkg/memory`) all working end-to-end. Governed by `engineering/KERNEL_POLICY.md`: no new feature without a real consumer requirement, an RFC, and an API-impact review |
| Engineering Review | [`engineering-review/`](../engineering-review/) | Sprint 4 in progress | The Engineering Review Engine — the first product built on the kernel. `review .` runs end-to-end against a real Provider (Claude) or a deterministic `FakeProvider`; RFC-0001/0002/0003 define its contracts and runtime behavior |
| review-benchmarks | [`review-benchmarks/`](../review-benchmarks/) | Data only, by design | Objective evaluation cases for Engineering Review — fixed diffs with a known-good expected review, so quality is judged against a number instead of an anecdote. No eval harness yet |
| Engineering brain | [`engineering/`](../engineering/) | Living | Coding standards, RFC/ADR process, `KERNEL_POLICY.md`, `PRODUCT_DEVELOPMENT.md` |
| Company roadmap | [`roadmap/`](../roadmap/) | Living | NOW / NEXT / BACKLOG |
