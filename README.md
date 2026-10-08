# Kyrylo Kalashnyk

AI Automation Engineer. I build LLM agents and automations that people use every day, and take
them from a vague request to a system running in production.

Most of my client work is private, so the repositories below are reference implementations of
systems I built for clients, rebuilt on synthetic data. Each one has tests, CI and a README that
says plainly what is verified and what is not.

| Repository | What it shows |
|---|---|
| [sprint-analytics](https://github.com/kotiniiqq/sprint-analytics) | Jira sprint metrics computed by code and reported by an LLM, with a guard that rejects invented numbers. MCP server, evals, tracing. Python, 89 tests. |
| [support-agent](https://github.com/kotiniiqq/support-agent) | A support agent that answers only from its knowledge base and hands sensitive tickets to a person. RAG (BM25 / Qdrant), PII pre-gate, golden-set and adversarial evals. Python, 130 tests. |
| [n8n-workflow-kit](https://github.com/kotiniiqq/n8n-workflow-kit) | n8n workflows as TypeScript: tested Code-node modules, deterministic builds, deploy with drift detection and rollback, verified end to end on a live n8n 2.40. 70 tests. |
| [bmf-messenger](https://github.com/kotiniiqq/bmf-messenger) | My own product: a desktop messenger with end-to-end encrypted chats (libsignal), calls and a mail client. TypeScript monorepo (Fastify, Electron, React, PostgreSQL), ~28k lines, 363 tests. |

**Stack:** Python, TypeScript, Go · n8n, LLM APIs, RAG, MCP · PostgreSQL, Redis, BigQuery ·
Docker, Linux, GitHub Actions

**Contact:** kotiniiqq@protonmail.com · Telegram [@kotiniiqq](https://t.me/kotiniiqq) ·
Antalya, Turkey, remote · English B1
