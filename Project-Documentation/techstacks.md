# Tech Stack

This document lists the primary technologies chosen to build Project-Y with a design and feature set similar to n8n.

**Core Stack**
- **Foundation:** `Next.js` + `TypeScript` : Server-rendered React framework with strong typing for building the web app and visual editor.
- **Database:** `Prisma` + `Neon` : Prisma for a type-safe ORM and Neon for serverless Postgres hosting.
- **Authentication:** `Better Out` : Authentication and session management (as requested).
- **Payment & Subscription:** `Polar` : Managed billing, subscriptions, and recurring payments.
- **Workflow Engine / Ingestion:** `Ingest` : Handles ingestion and orchestration of workflow tasks and connectors.
- **Visual Canvas:** `React Flow` : Node-based visual editor for building and wiring workflows.
- **AI Integration:** `Gemini` : LLM integrations for AI-assisted actions and generation.
- **GitHub Workflow / CI:** `CodeRabbit` : GitHub workflow automation and CI pipelines.
- **Production Ready / Monitoring:** `Sentry` : Error reporting, performance monitoring, and release tracking.

**Rationale (short)**
- **Next.js + TypeScript:** Fast startup, good SEO/SSR, and excellent DX with types.
- **Prisma + Neon:** Type-safe DB access and serverless Postgres fits scalable, cloud-first deployments.
- **React Flow:** Proven library for building visual workflow canvases like n8n.
- **Sentry & Polar:** Production observability and payments are critical for SaaS readiness.

**Next steps**
- Create a minimal starter scaffold (Next.js + TS) wired to Prisma schema and Neon connection.
- Add authentication flow (Better Out) and a sample React Flow canvas page.
- Add CI using CodeRabbit and Sentry integration for error tracking.

If you want, I can scaffold a starter repo (Next.js + Prisma + React Flow) next.
