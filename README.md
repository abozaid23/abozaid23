# Yousef Nasser Abozaid

CS student at Nile University, Cairo. I build operations software and I test it hard: test plans, security reviews, and evaluating what AI tools actually get right.

I grew up in a real-estate development company and still supervise site crews and procurement there, so I keep ending up at the same problem: the work is real, the coordination is on paper, and nobody's built the tool.

---

### Projects

**[SharpMaintain](https://github.com/abozaid23/sharpmaintain)** — multi-tenant fleet maintenance system.
FastAPI + Flutter + React. Offline-first capture for mechanics with no signal, tenant isolation from the first commit, bilingual AR/EN with real RTL. 282 backend tests, including a tenant-isolation audit across every route, and a security audit that found and fixed cross-tenant escalation and CSV formula injection.

**[Fuel Guardian](https://github.com/abozaid23/fuel-guardian)** — fuel anti-theft reconciliation. *(in progress)*
TypeScript monorepo: API, Arabic-first admin console, a Modbus/RS-485 edge poller and a device simulator. Reconciles litres dispensed against distance and tank stock. 435 test cases. Tested against the simulator only, not real pumps yet.

**[Clinic Management System](https://github.com/abozaid23/clinic-management-system)** — Java Swing + PostgreSQL, five-person team (CSCI 217).
Appointments with conflict detection, an interface-based service layer, and every query parameterised.

**[Campus Navigation](https://github.com/abozaid23/campus-navigation-system)** — graph representations and BFS in Python (Discrete Mathematics, two-person team).

Private: **Washly** (Arabic-first car wash booking platform, FastAPI + Next.js, built Jun–Jul 2026, no longer operating) and **Kebda El Prince** (restaurant ordering client demo, deployed on Railway + Vercel).

---

### QA and AI evaluation

Freelance QA for HiSolve (Aug–Sep 2026): I designed a release-assurance test plan of 1,067 controls, assessed 4 web systems with it, and built a 32-defect planted benchmark to measure how well AI testers actually find bugs. That work is client-internal, so it isn't public here.

---

### How I work

I build with AI coding agents (Claude Code, Codex, Cursor) and treat their output as a claim until it's verified: I write the spec, set the test and security gates, and review every change. SharpMaintain's [build log](https://github.com/abozaid23/sharpmaintain/blob/main/STATE.md) is published unedited, including the parts where the process broke and had to be caught on review.

Arabic (native) · English (professional working)

📍 6th of October, Cairo · [LinkedIn](https://www.linkedin.com/in/yousef-abozaid)
