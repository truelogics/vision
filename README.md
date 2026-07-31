---
doc: README
audience: [human, agent]
status: living
owner: vision
last_reviewed: 2026-08-01
---

# Vision

## What is TrueLogics?

TrueLogics is the company building the AI Engineering OS. This repo is its
north star: why we exist, what we believe, which projects we pursue, and how
that maps to a long-term roadmap.

## What is the AI Engineering OS?

We're not designing a finished product top-down. We're building it the way
Linux was built: start with a kernel, let everything else emerge around it.

```
                 Engineering OS
                      ▲
        ┌─────────────┼─────────────┐
        │             │             │
     Workflows     Intelligence   Runtime
        ▲             ▲             ▲
        │             │             │
   Skills         Context       Memory   ← kernel
```

**Memory is the kernel.** Everything — review, planning, agents, standards
enforcement — depends on it. [`ai-memory/`](../ai-memory/) starts as
*Engineering Memory*: store, organize, retrieve, and connect engineering
knowledge (code, ADRs, PRs, standards, roadmap, incidents, runbooks). Version
1 has no AI in it — it's a search and indexing problem before it's an LLM
problem. Context, intelligence, and workflow layers get added on top only
once the kernel earns them. The OS emerges; it isn't decreed.

## Why does it exist?

Agents start every session with no memory, and humans lose context to
scattered docs and tribal knowledge. The AI Engineering OS exists so intent
(why, from `vision/`), priority (what's now, from `roadmap/`), standards (how,
from `engineering/`), and memory (what's been decided, from `ai-memory/`) live
in one place both people and agents can read and trust — so every repo and
agent decision can point back to a shared purpose instead of re-litigating
it. Product priorities and engineering standards should follow from vision —
not the other way around.

## Who is it for?

- Founders and leads setting direction
- Engineers choosing what to build next
- Agents that need intent, not just tasks

## Current status

**Planning** — files are placeholders. Fill `VISION.md` and `PHILOSOPHY.md` first.

## Roadmap

1. Write [`VISION.md`](VISION.md) — problem, audience, north star
2. Write [`PHILOSOPHY.md`](PHILOSOPHY.md) — principles we won't compromise
3. List active bets in [`PROJECTS.md`](PROJECTS.md)
4. Align long-term phases in [`ROADMAP.md`](ROADMAP.md) with [`roadmap/`](../roadmap/)

## Contributing

Open a PR against the relevant file. Vision changes are high-impact — keep them
short, explicit, and linked from company `roadmap/` when priorities move.

## Repositories

| Repo | Role |
|------|------|
| [`vision/`](.) | Company north star — this repo |
| [`roadmap/`](../roadmap/) | Company-wide priorities: now / next / backlog |
| [`engineering/`](../engineering/) | Coding standards, architecture, RFCs, ADRs, rules |
| [`ai-memory/`](../ai-memory/) | Engineering Memory — the kernel the OS is built outward from |

## Map

```
vision/
├── README.md       ← you are here
├── VISION.md       ← what we're building toward
├── PHILOSOPHY.md   ← beliefs and constraints
├── PROJECTS.md     ← product / initiative index
└── ROADMAP.md      ← long-horizon company roadmap
```
