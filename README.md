<a href="https://ritishsaini.tech"><img src="https://ritishsaini.tech/og.png" alt="Ritish Saini — Noise goes in. Signal comes out." width="100%"></a>

### AI backend engineer. Python · FastAPI · LLM applications & agent tooling.

I build systems that take input nobody vetted — a repository, a Postgres backup, a bank export, a lab PDF, a git history — and **refuse to guess** about the parts they can't resolve. Anything uncertain goes to a human; everything else gets proven.

Production experience building REST APIs and multi-tenant systems in Python and FastAPI, now focused on AI systems: LLM integration, retrieval and embeddings, evaluation, and tooling that verifies what AI agents actually do.

📍 Fremont, California · Green Card holder, authorized to work in the U.S.

**[ritishsaini.tech](https://ritishsaini.tech)** — the portfolio, one machined instrument that reconfigures per project &nbsp;·&nbsp; [CV](https://ritishsaini.tech/ritish-saini-cv.pdf) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/ritish-saini-2540a5253) &nbsp;·&nbsp; [ritishsaini1995@gmail.com](mailto:ritishsaini1995@gmail.com)

---

#### Nine systems, each with one hard problem

| System | What it does |
|---|---|
| **[carabiner](https://github.com/MaXiMo000/carabiner)** &nbsp;[↗](https://maximo000.github.io/carabiner/) | Make any repo secure by default, keep it that way, and prove the controls actually fire. A ratchet, so only new findings fail the build; also a pre-commit hook. |
| **[firedrill](https://github.com/MaXiMo000/firedrill)** &nbsp;[↗](https://maximo000.github.io/firedrill/) | A backup you haven't restored isn't a backup. Restores Postgres, MySQL and MariaDB backups into a disposable, version-matched container (SQLite needs none) and proves the result is usable. |
| **[recur](https://github.com/MaXiMo000/recur)** &nbsp;[↗](https://recur.onrender.com) | Bank CSV in, recurring charges, price rises and duplicates out. No credentials, ever. A remote MCP server (OAuth 2.1 + PKCE) lets AI assistants query it, isolated per user in the database; a pgvector matcher was measured and cut when it wasn't reliable enough. |
| **[LabLedger](https://github.com/MaXiMo000/LabLedger)** &nbsp;[↗](https://labledger-web.onrender.com/) | Any lab's PDF → each test resolved to a LOINC code, units converted, reference interval resolved, trend charted. An LLM only for the ambiguous rows, which then go to a human. Role-based access, 2FA, audit log. |
| **[QuizNest](https://github.com/MaXiMo000/Quiz-App)** &nbsp;[↗](https://quiz-app-cp2h.onrender.com/) | Full-stack quiz platform — Gemini generates questions on any topic and grades written answers; Google sign-in, role-based access. |
| **[AI Recipe Maker](https://github.com/MaXiMo000/AI-Recipe-Maker)** | Claude-powered recipes from what's in your kitchen, with nutrition analysis and meal plans. |
| **Snazzlebop** &nbsp;[↗](https://snazzlebop.onrender.com) | A party game show where your friends are the contestants: 37 games, one room code, phones as controllers and the TV as the stage. Server-authoritative FastAPI + WebSockets, so each phone only ever sees what its player may. |
| **[AniNest](https://github.com/MaXiMo000/AniNest)** &nbsp;[↗](https://aninest-frontend.onrender.com) | An anime, manga and novels hub: track, review, watch official free episodes, play games. AniList first, Jikan when it fails, and the last good copy when both are down, so a page degrades instead of failing. |
| **[afterglow](https://github.com/MaXiMo000/afterglow)** &nbsp;[↗](https://afterglow.name) | Paste a public GitHub repo and its history grows into a night city: hotspots, bus factor, hidden coupling, in WebGL2. Read by a sandboxed worker that never checks out a file. |

#### Proof tooling — small, tested, each with its own CI &nbsp;[↗ all on one page](https://maximo000.github.io/tools/)

`receipt` what a command, a browser click or an AI coding agent (Claude Code, Codex, Cursor) actually changed &nbsp;·&nbsp; `sourced` per-claim checking of LLM output against its source &nbsp;·&nbsp; `lockstep` installed packages vs. the lockfile, Python and npm &nbsp;·&nbsp; `escrow` a dead man's switch for cron, CI and Kubernetes jobs &nbsp;·&nbsp; `drift` device traffic vs. what it's allowed to contact, from a capture or live &nbsp;·&nbsp; `satchel` a local-first, offline-searchable reading archive with a browser extension &nbsp;·&nbsp; `invariant` declare what must stay true, keep a proof bundle &nbsp;·&nbsp; `playhead` replay AI coding sessions like a timeline &nbsp;·&nbsp; `parity` live API calls vs. their own contract &nbsp;·&nbsp; `portable` does a data export contain what it promises &nbsp;·&nbsp; `witness` holds a site to its own claims

#### Things that render

**[tidewatch](https://github.com/MaXiMo000/tidewatch)** — a scroll-driven 3D live infrastructure world on FastAPI + WebSockets + Three.js.
**[loom](https://github.com/MaXiMo000/loom)** — one dependency tree's vulnerable, drifted and tamper-evident answers as a single explorable 3D graph.

---

#### Work

**Backend Developer — Wizcommerce** · Gurgaon, India · Apr 2025 – Sep 2026
- **30+ REST APIs** on FastAPI — **30% faster data retrieval**
- A multi-tenant backend: each client's data private and isolated, still easy to scale
- Elasticsearch search — **~40% lower response time**
- Celery for long-running work, keeping the API fast and responsive
- PostgreSQL + SQLAlchemy tuning — **25% less database load**; centralized logging with Sentry

**B.Tech Computer Science Engineering**, Chitkara University, 2022–2026 — CGPA **9.02**

#### What I reach for

**Python** · SQL · TypeScript · JavaScript (React, Node.js) · Java &nbsp;|&nbsp; **FastAPI** · REST · JWT · OAuth2 &nbsp;|&nbsp; **GenAI** · RAG · embeddings (pgvector) · LLM evaluation · OpenAI / Gemini / Claude APIs · prompt engineering · MCP &nbsp;|&nbsp; **PostgreSQL** · MongoDB · SQLAlchemy &nbsp;|&nbsp; **Elasticsearch** · Redis &nbsp;|&nbsp; Celery · Docker · Kubernetes · CI/CD · Sentry &nbsp;|&nbsp; Claude Code (hooks) · Cursor · Copilot

<sub>Noise goes in. Signal comes out.</sub>
