# OctoAcme Project Management Docs

Overview

OctoAcme runs projects with a clear, outcome-driven lifecycle: Initiation (one‑pagers to validate the problem, stakeholders, and success metrics), Planning (kickoffs, prioritized backlogs, estimates, Definition of Done, and release milestone mapping), Execution (small, tracked increments on a project board with CI and code reviews), Release & Deployment (pre‑release checks, smoke tests, rollback plans, and post‑deploy verification), and Close & Retrospective (capture learnings and convert action items into the backlog). This life cycle is designed to keep work small, measurable, and aligned with customer value.

Roles & Ownership

Responsibility and ownership are explicit: Product Managers define outcomes, success metrics, and prioritize work; Project Managers coordinate delivery, manage risks and communications; Developers implement, test, and document features; QA/Testing validates acceptance criteria and quality. The docs indicate who owns artifacts (one‑pagers, risk register, release notes) and require assignments for risks, decisions, and follow‑ups to prevent ambiguity.

Communication & Quality Assurance

Communication uses a predictable cadence to surface progress and dependencies: daily standups, weekly delivery syncs, milestone demos, and periodic stakeholder updates. Risks are tracked in a risk register with defined escalation paths. Quality assurance is integrated across the workflow: small PRs with linked issues and acceptance criteria, automated CI (tests, linting, security), unit/integration tests, critical flow smoke tests, and manual QA when needed. Releases follow a checklist and include rollback/incident playbooks.

Documentation Index

| Document | Description |
|---|---|
| octoacme-project-management-overview.md | Project lifecycle, principles, roles, and key artifacts |
| octoacme-project-initiation.md | How to start a project, required artifacts, and decision gates |
| octoacme-project-planning.md | Turning initiatives into prioritized backlogs, estimates, and release plans |
| octoacme-execution-and-tracking.md | Team rhythms, PR workflow, QA expectations, and blocker escalation |
| octoacme-risks-and-communication.md | Risk register lifecycle, communication templates, and escalation paths |
| octoacme-release-and-deployment.md | Release types, deployment checklist, and rollback playbook |
| octoacme-retrospective-and-continuous-improvement.md | Running retrospectives and tracking action items |
| octoacme-roles-and-personas.md | Definitions for core roles (PdM, PM, Dev, QA, Stakeholders) |

Notes
- Keep this README as the entrypoint for the docs/ folder and update the index when new process documents are added.
- Reference issue #2 in the PR body (e.g., "Refs #2") to automatically link this change to the request to add this README.
