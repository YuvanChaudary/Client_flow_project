# Client Flow — Agentic Customer Intelligence

![Client Flow](src/assets/hero.png)

Client Flow is an agentic AI project designed to anticipate customer needs and deliver proactive recommendations and actions across CRM, finance, projects, and support workflows. This repository underpins a demo application (React + Vite frontend, Node server and agent logic) that showcases planning, intent extraction, tool integrations (Jira, ServiceNow, CRM), and auditability.

If you'd like to visit the source repo or collaborate, email: yuvanchaudary2004@gmail.com

---

## Highlights

- Agent architecture: intent detection, planner, executor, and validators in server/agents
- Integrations: CRM, Jira, ServiceNow, finance and document tools (server/tools)
- UI: React components for assistant, dashboard, analytics and verification
- Tests: unit & e2e tests for planner, intents and integrations (server/tests)

---

## Project structure (short)

- server/                 — agent logic, tool adapters and tests
- src/                    — React frontend components and client logic
- docs/                   — architecture and supporting docs
- package.json / vite     — frontend build & dev config

---

## Quickstart

Prerequisites: Node 18+, npm

1. Clone the repo

   git clone https://github.com/YuvanChaudary/client_flow.git
   cd client_flow

2. Install and run

   npm install
   npm run dev

3. Run server (if needed)

   # depends on your setup; server.ts is included for demonstration
   node server.ts

---

## Contact

Email: yuvanchaudary2004@gmail.com

---

