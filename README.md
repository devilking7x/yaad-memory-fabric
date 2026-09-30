# Yaad Memory Fabric

**Open Agent Hackathon 2026 — Tinkerer Track entry.**

Yaad Memory Fabric is a new knowledge/memory layer that extends
[Yaad](https://github.com/devilking7x/yaad) — Om's memory-based personal AI
assistant — turning it from a chat assistant into a connected, autonomous
knowledge agent, powered by NVIDIA sponsor technology.

> 🚧 Building in the open. Implementation lands during the official build
> window, **Oct 15–20, 2026** (judged work must be created during the window
> per the Tinkerer Track rules). This README tracks what exists vs. what is
> new — see `docs/NEW-WORK.md`.

## What it adds to Yaad

| Module | What it does | Sponsor tech |
|---|---|---|
| Document ingestion | Upload PDF/MD/CSV/TXT → extract → chunk → embed → local vector store | NVIDIA NIM embeddings |
| Hybrid knowledge search | Vector + keyword retrieval with **citations** (doc + chunk) | NVIDIA NIM |
| Deep research v2 | planner → parallel investigators → critic → synthesizer, evidence-backed reports | NVIDIA NIM + Tavily |
| Watch goals | Standing goals → scheduled autonomous briefings | NVIDIA NIM |

## Status

- [x] Repo scaffolded (README, LICENSE, .gitignore)
- [ ] Implementation (build window Oct 15–20, 2026)
- [ ] Live demo deployment
- [ ] Demo video

## Tinkerer story

Yaad already exists (agent loop, persistent memory, skills, web search). Memory
Fabric is the **new work**: every file outside this seed commit is written
during the build window and integrates NVIDIA NIM for embeddings, chat, and
multi-agent reasoning over the user's own documents.

## License

MIT — see [LICENSE](LICENSE).
