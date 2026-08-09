---
doc: SYSTEM_MAP
audience: [human, agent]
status: living
owner: vision
last_reviewed: 2026-08-08
---

# Engineering OS System Map

```
                   Engineering OS
                          │
        ┌─────────────────┼─────────────────┐
     Vision            Roadmap         Engineering
                          │
                      AI Memory
           (Engineering Knowledge Kernel)
                          │
        ┌─────────────────┼─────────────────┐
    AI Review    engineering-mcp    Future Clients
                          │
              Engineering Intelligence
                          │
                Repository Knowledge
                      Evidence
                    Architecture
                  Engineering Rules
                    Documentation
                       Search
                      Retrieval
```

## Principles

### AI Memory

Provides engineering knowledge.

Never performs reasoning.

---

### Consumers

Consumers perform reasoning.

Two exist today, and that is the point: AI Review (a program that
reviews changes) and engineering-mcp (a transport that lets an AI client
ask its own questions). They share no code and no shape. A kernel two
unrelated consumers build on is a platform; a kernel one consumer builds
on is an application with extra steps.

Examples:

- AI Review
- Claude Code
- GitHub
- VS Code
- Cursor

---

### Engineering Intelligence

Engineering intelligence should always be exposed as reusable
capabilities.

Never expose one giant API.

Prefer small reusable capabilities such as:

- `search_memory`
- `collect_evidence`
- `get_architecture_context`
- `find_engineering_rules`
- `find_related_documents`

These capabilities can later be consumed through:

- CLI
- MCP
- HTTP
- gRPC
- IDE integrations

without changing the kernel.
