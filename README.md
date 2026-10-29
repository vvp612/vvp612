# vvp612

Automation & internal-tools developer. I build small, well-tested tools that remove manual work:
browser automation, backend services, AI-assisted reporting and intake pipelines.

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [playwright-flow-kit](https://github.com/vvp612/playwright-flow-kit) | JSON-driven browser automation with CDP attach, per-step retries and screenshot evidence, plus a site-health auditor (uptime, broken links, visual diff) | Node · Playwright · CDP |
| [internal-tool-scaffold](https://github.com/vvp612/internal-tool-scaffold) | Production-shaped starter for small-business web tools — auth, audit trail, CSV exports, validated uploads. Demo: equipment inventory with loans & overdue tracking | FastAPI · SQLite · htmx |
| [ai-report-generator](https://github.com/vvp612/ai-report-generator) | Digest Studio — turns raw team notes into a branded `.pptx` weekly digest via Claude; runs fully offline with a deterministic MockLLM | Streamlit · Claude API · python-pptx |
| [lead-qual-agent](https://github.com/vvp612/lead-qual-agent) | Lead & support intake pipeline: webhook → LLM triage grounded in an FTS5 knowledge base → Sheets/CSV CRM → weekly digest; ships an importable n8n workflow | FastAPI · SQLite FTS5 · n8n |

## Toolkit

- **Automation** — Playwright (incl. CDP), n8n, webhooks, scheduled jobs
- **Backend** — Python (FastAPI), SQLite, REST APIs, CSV/spreadsheet integrations
- **AI integration** — Claude API with validated JSON contracts, offline-safe MockLLM for tests, lightweight RAG
- **Frontend** — Jinja2 + htmx, Streamlit, token-based plain-CSS design systems

## Working style

- Tests ship with the code (pytest / `node --test`) — every demo runs offline
- Small logical commits and readable history
- READMEs reproduce the demo from a clean clone

Open to automation & AI-tool projects — open an issue on any repo or message me here.
