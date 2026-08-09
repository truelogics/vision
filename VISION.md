---
doc: VISION
audience: [human, agent]
status: placeholder
owner: vision
last_reviewed: 2026-08-08
---

# Vision

> **Status:** placeholder — write the north star here.

## Problem

_What pain exists in the world that we exist to fix?_

## Who we serve

_Primary users and what success looks like for them._

## North star

_One or two sentences: the future state we're building toward._

## What we are not

_Explicit non-goals so priorities stay sharp._

## System Architecture

The AI Engineering OS is composed of multiple independent projects with
clearly defined responsibilities.

```
Vision
  │
  ▼
Roadmap
  │
  ▼
Engineering Standards
  │
  ▼
AI Memory (Kernel)
  │
  ▼
Consumers
  ├── AI Review
  ├── engineering-mcp (Claude Code, and any MCP client)
  ├── GitHub (future)
  ├── VS Code (future)
  ├── Cursor (future)
  └── Other Engineering Tools
```

### Responsibilities

#### Vision

Defines the long-term direction of the AI Engineering OS.

#### Roadmap

Tracks what we are building now, next, and later.

#### Engineering

Defines development process, RFCs, architecture standards, and
engineering principles.

#### AI Memory

The engineering knowledge kernel.

Responsible for:

- engineering memory
- indexing
- retrieval
- evidence
- repository knowledge

AI Memory never performs reasoning.

#### Consumers

Consumers use AI Memory to perform engineering tasks.

Current:

- AI Review
- engineering-mcp — MCP transport; Claude Code reaches the kernel
  through it

Future:

- GitHub App
- VS Code
- Cursor
- CI
- Future AI Engineering applications

Each consumer owns its own reasoning.

AI Memory provides engineering knowledge.
