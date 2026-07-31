## Pranav Patil

I build production software with AI agents, in Berlin.

Operations and supply-chain background (Mahindra Logistics, Beijer Electronics), now building the systems I used to run manually. Most of what is below was designed, built, reviewed and shipped by me using Claude Code inside a fixed process: scoped tickets with done criteria, a two-part ship gate (zero-context code review plus a QA runner), and merge only on zero blockers.

### Live

| Project | What it is | Live |
| --- | --- | --- |
| **PetraOS** | Showroom OS for natural stone: browse slabs, preview in-room, price, reserve. Next.js, Supabase, Three.js. | [petraos.vercel.app](https://petraos.vercel.app) |
| **Granitopia** | Motion-rich 3D marketing site. React Three Fiber, GSAP, Lenis, internationalized. | [granitopia.vercel.app](https://granitopia.vercel.app) |
| **GraniteOS** | Multi-tenant SaaS ERP for the granite trade: inventory, quotes, GST invoicing, fabrication. Supabase RLS, phone-OTP MFA, RBAC. | [graniteos.vercel.app](https://graniteos.vercel.app) |
| **dashscout** | One dark dashboard to find every agent/AI server on your localhost. Zero deps, runs with npx. | [demo](https://pranav-patil-solutions.github.io/dashscout/) |

### Also public

- **RevenueOS** — finance department in a box: photograph a ledger, AI extracts the rows, posts to double-entry books with P&L, trial balance and GST-prep exports. Local-first Next.js, 353 tests.
- **Scout** — AI job-search command center: source ingestion, application pipeline, analytics, AI-generated application kits.
- **AgentOS** — single-pane dashboard for an AI agent fleet: registry, runs, cost and token analytics.

### How I work

- **Tickets before code.** Every change starts as a scoped ticket with explicit done criteria.
- **A ship gate that is not me.** A code reviewer that sees only the diff, plus a QA runner. Zero blockers or it does not merge.
- **Verify the artifact, not the log.** After deploy I check what actually shipped, not what the build said.
- **Every miss becomes a rule.** Bugs and agent missteps end as a permanent change to the system, logged in each repo's `EVOLUTION.md`.

### Stack

TypeScript, Next.js, React, Node, Python, Postgres/Supabase, SQLite, Drizzle, Tailwind, Three.js, Vercel, Claude Code and the Anthropic SDK.

Berlin, Germany. English C1, German A2 and improving, Hindi and Marathi native.
