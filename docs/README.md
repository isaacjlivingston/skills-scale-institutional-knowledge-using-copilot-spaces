# OctoAcme Project Management Processes

This folder hosts OctoAcme's end-to-end project management process documentation. It provides structured guidance for every phase of a project — from initiation through retrospective — as well as team roles and communication standards. Use this README as your entry point to discover and navigate the full documentation set.

## Project Management Framework Summary

OctoAcme follows a **five-phase lifecycle** — Initiation → Planning → Execution → Release → Retrospective — anchored by five core principles: customer-first prioritization, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

Three primary roles drive delivery:

- **Project Manager (PM):** coordinates schedules, risks, and communications across the team and stakeholders.
- **Product Manager (PdM):** defines outcomes, owns the backlog, and measures success against agreed metrics.
- **Developers:** implement and test features, participate in design and code review, and help identify technical risks.

Key recurring practices across all process documents include:

- **Checklists and templates** at every phase (initiation, planning, deployment, status updates, action items, release notes) to enforce consistency.
- **Risk Register** maintained from initiation through release — the single most cross-referenced artifact — capturing impact, likelihood, owner, and mitigation for each risk.
- **Structured communication cadence:** twice-weekly standups, weekly PM–PdM syncs, monthly stakeholder updates, and a standardized Weekly Status Template (progress / next steps / risks & blockers / decisions needed).
- **Tiered escalation:** team standup → PM to Product Lead → sponsor-level for business-impacting issues, with a separate security incident runbook.
- **Quality built in:** unit, integration, and end-to-end smoke tests; security scanning in CI; small PRs (≤ 400 lines); and at least one review approval required before merge.
- **Continuous improvement:** timeboxed retrospectives (45–75 min) after every sprint, release, or incident, with 2–3 prioritized action items tracked in the backlog and reviewed weekly.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, key artifacts, lifecycle, and communication cadence. |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize work: one-pager template, stakeholder alignment, and go/no-go decision gate. |
| [Project Planning](octoacme-project-planning.md) | Converting an approved initiative into an actionable backlog, release plan, Definition of Done, and risk register. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythm, PR workflow, quality & testing standards, metrics, and blocker escalation. |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk lifecycle, stakeholder communication templates, weekly status format, and escalation paths. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running guidelines, action item tracking, and continuous improvement culture. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and typical communication patterns for Developers, Product Managers, Project Managers, Project Sponsors, Change Managers, Technical Leads, QA Analysts, and Subject Matter Experts (SMEs). See also the [RACI Matrix](octoacme-raci-matrix.md). |
| [RACI Matrix](octoacme-raci-matrix.md) | Role-by-activity accountability matrix covering all OctoAcme roles across the full project lifecycle. |
