# Cyrus Jalili Khiabani

Technical Project Manager moving into software/AI engineering. I build MCP servers and AI tools
that run in production — for construction field operations and for a personal health-data stack.

### What I've shipped

| Project | What it does | Stack | Status |
|---|---|---|---|
| [TSheets MCP](https://github.com/cykj40/Tsheets-MCP) | Lets Claude pull timesheet hours, notes, and photo attachments, run note-quality audits, and export to Sage 100 Contractor format. Handles the API's 200-record page cap | TypeScript, MCP SDK, OAuth2, SQLite | Weekly production use |
| [Dexcom MCP](https://github.com/cykj40/dexcom-mcp-server) | Connects Claude to CGM data: trend analysis, event logging, AGP charts, parameter-drift detection. Human-in-the-loop by design | TypeScript, MCP SDK, Fly.io | Production |
| [Peloton MCP](https://github.com/cykj40/Peloton-MCP-Server) | Workout history with exact timestamps for glucose correlation, plus muscle-group and training-balance analysis | TypeScript, MCP SDK, Fly.io | Production |
| [T1Copilot](https://github.com/cykj40/t1copilot) | AI copilot over CGM, labs, Apple Health, and fitness data, with HITL approval on every recommendation | Next.js 15, Vercel AI SDK, Drizzle, Turso, Neon + PGVector | Active development |
| [Field Notes PWA](https://github.com/cykj40/Field-notes-assistant) | English/Spanish voice-dictation notes app for construction supervisors | Next.js, Whisper, Redis, Playwright E2E | Live |
| [Health Journal AI](https://github.com/cykj40/health-journal-ai) | Extracts 40+ health signals from free-form journal entries, with Whisper voice input | Next.js 15, Claude API, Neon, Drizzle | Live |

**An architecture call I'd defend:** T1Copilot started on LangGraph. I replaced it with plain
AI SDK tool calls to ship faster and kept the graph implementation at the `langgraph-reference` tag.

### Stack
**Languages:** TypeScript · Go · Python · C

**Frameworks & tools:** Next.js · React · Fastify · Zod · MCP SDK · Claude API · OpenAI API · Vercel AI SDK

**Infra:** Fly.io · Vercel · Neon · Turso

### Background
Self-taught. Rutgers Web Dev Bootcamp, IBM Web Development Professional Certificate,
675+ hours on Frontend Masters. I found gaps inside a non-technical industry and shipped the tools myself.

[cyruskhiabani.com](https://cyruskhiabani.com)
