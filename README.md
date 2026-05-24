## Ilia Malkin

Backend / AI engineer. Python, LLM tooling, Telegram bots, full-stack apps.

**Availability:** remote only. No on-site work in Russia under any circumstances. Open to remote roles worldwide and to on-site roles in Vienna / EU.

**Contact:** [ilyamalkinn@gmail.com](mailto:ilyamalkinn@gmail.com) · [CV PDF (EN)](https://github.com/kudnever/cv/raw/main/kudnever-cv-en.pdf) · [CV PDF (RU)](https://github.com/kudnever/cv/raw/main/kudnever-cv-ru.pdf)

---

### Currently shipping

**[Stager](https://github.com/kudnever/stager)** · multi-tenant project expense tracker.
Telegram bot + FastAPI backend + Next.js admin. LLM router (MiMo to Gemini) with Redis-backed circuit breaker and Pydantic-validated structured output. Full stack: aiogram 3, Celery, async SQLAlchemy 2.0, PostgreSQL 16, MinIO, JWT + RBAC, structlog + Sentry, pytest with testcontainers, GitHub Actions CI, Docker Compose + Caddy on Hetzner.

**[doc-assistant-bot](https://github.com/kudnever/doc-assistant-bot)** · production RAG service.
Telegram RAG over PDF / DOCX / TXT. Bilingual UI in 7 languages, multilingual embeddings via fastembed, OpenRouter-routed LLM with citation enforcement, single-file SQLite + sqlite-vec storage. Live: [@assistantdocumentbot](https://t.me/assistantdocumentbot).

**[windows-claude-code-doctor](https://github.com/kudnever/windows-claude-code-doctor)** · diagnostic skill for AI coding agents on Windows.
Turns vague "Claude Code is broken" reports into shell-aware diagnoses and small, testable fixes. Works with Claude Code, Codex CLI, Cursor, OpenClaw, VS Code agents. PowerShell.

**[Revenue Metrics Console](https://github.com/kudnever/revenue-metrics-console)** · internal revenue analytics tool.
React 18 with TanStack Router + Query, Node.js + Express, PostgreSQL with Drizzle ORM, WebSocket-driven live metrics, JWT auth with RBAC.

### Stack

**AI / LLM:** OpenAI SDK, Google Gemini, xAI Grok (OAuth + Agent Tools), MiMo, OpenRouter, prompt engineering, RAG (sqlite-vec + fastembed), structured output via Pydantic, multi-provider routers with circuit breaker, MCP, function calling

**Languages:** Python, TypeScript, JavaScript, SQL, PowerShell, Bash

**Backend:** FastAPI, Pydantic v2, async SQLAlchemy 2.0, Alembic, aiogram 3, Celery, Node.js, Express, Next.js 14, REST APIs, JWT, RBAC

**Frontend:** React 18, TanStack Router + Query, Next.js 14 (App Router), Tailwind CSS, shadcn-style, recharts

**Data / Infra:** PostgreSQL 16, SQLite, sqlite-vec, Redis, MinIO (S3), Drizzle ORM, Docker, Docker Compose, Caddy, Hetzner, Linux

**Quality:** pytest, testcontainers, respx, ruff, mypy (strict), pre-commit, gitleaks, structlog, Sentry

**CI / Tooling:** GitHub Actions, Git, Playwright, OAuth, WebSocket, OpenAPI

### Education

BSc Data Science, Universität Wien (in progress)
