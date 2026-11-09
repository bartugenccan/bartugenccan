# Bartu Gençcan

**Backend AI Engineer.** Five years shipping production web, mobile and backend. Now building the layer AI features run on.

- **Now:** Backend at Guester, a hospitality SaaS. Building the platform underneath: a multi-provider ingestion pipeline on BullMQ and Redis, around 30 NestJS modules, MySQL.
- **Building:** `groundtruth`, hybrid RAG with a retrieval eval, so a change is proven with a number, not a hunch.
- **Site:** [bartugenccan.dev](https://bartugenccan.dev)

## AI in production

At Guester I work on **Guester's AI Assistant** for hotel teams (private codebase, so the outline only):

- **Agent flow:** requests are triaged, answered with tool calls over the hotel's own data, and checked before they reach the user.
- **Retrieval:** RAG over product documentation, so answers about the platform come from its docs.
- **Voice:** spoken replies alongside text.
- **MCP server:** read-only, tenant-scoped access to hotel data for outside AI clients, with scoped tokens and redaction.
- **AI features around it:** review analysis and replies, review translation, scheduled briefs and workflows that run on hotel data.

## Building in public

Every project runs the same loop: build → break → debug → measure. Repos go public when they ship with a measurement.

| | Project | What | Status |
|---|---|---|---|
| P1 | groundtruth | Hybrid RAG + retrieval eval | in progress |
| P2 | judge-gate | LLM-as-judge, human calibration, CI regression gate | next |
| P3 | llm-gateway | Rate limits, budgets, circuit breaker, fallback, tracing | planned |
| P4 | casefile | Durable agent: tools, sandbox, budget, replay, human approval | planned |
| P5 | doorman | Prompt-injection defense + red-team harness | planned |
| P6 | warmstart | Semantic cache + cost router | planned |
| P7 | slotfill | Distillation + vLLM serving + break-even analysis | planned |

## Shipped

- [go-crawler](https://github.com/bartugenccan/go-crawler): a web crawler in Go, written to learn systems. 50 pages, 1000 books, and the rules they left behind.

## Stack

Python · TypeScript · Node.js / NestJS · FastAPI · LLM tool calling · RAG · MCP · BullMQ · Redis · MySQL · PostgreSQL · Docker · GitHub Actions

## Contact

[LinkedIn](https://linkedin.com/in/bartugenccan) · [X](https://x.com/bartugenccandev) · bartu@bartugenccan.dev
