# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Proposed Additional Personas (New)

The following personas clarify ownership across release, quality, design, support, and business analysis. Adding these roles reduces ambiguity, clarifies handoffs, and improves cross-team coordination.

### Release Manager

#### Role Summary
Coordinates and owns release planning, readiness, and deployment execution across teams.

#### Responsibilities
- Maintain the release schedule and coordinate release windows
- Verify pre-release conditions (CI, test coverage, release notes, rollback plan)
- Coordinate cross-team release readiness checks and runbooks
- Communicate release timing and scope to stakeholders and support
- Drive post-release retrospectives for release processes

#### Goals
- Reduce release-related incidents and rollbacks
- Make release cadence predictable and transparent

#### Typical Communication & Interactions
- Works closely with Project Manager, Product Manager, QA Lead, Developers, and Support Engineer
- Sends release readiness summaries to stakeholders and on-call/support channels

---

### QA Lead

#### Role Summary
Leads the testing strategy and ensures work meets defined quality standards prior to release.

#### Responsibilities
- Define test strategy for features and releases (manual & automated)
- Coordinate QA resources, test plans, and acceptance verification
- Maintain test automation coverage priorities and failure triage
- Escalate unresolved quality risks to PM/Release Manager

#### Goals
- Ensure acceptance criteria are validated before release
- Reduce production defects and regressions

#### Typical Communication & Interactions
- Partners with Developers, Product Manager, and Release Manager to validate readiness
- Provides test summary and known issues to Release Manager and Support

---

### UX Designer

#### Role Summary
Owns user experience design and validation to ensure delivered features meet usability and accessibility goals.

#### Responsibilities
- Create user flows, wireframes, and high-fidelity designs as needed
- Run usability testing and incorporate feedback into acceptance criteria
- Define UX acceptance criteria and accessibility checks
- Advise on design trade-offs during planning

#### Goals
- Improve user satisfaction and reduce usability-related rework

#### Typical Communication & Interactions
- Collaborates with Product Manager on requirements and success criteria
- Works with Developers and QA Lead to ensure designs are implemented and tested

---

### Support Engineer

#### Role Summary
First line for customer-facing incidents and support; converts operational feedback into actionable issues.

#### Responsibilities
- Triage production issues and provide timely incident updates
- Document reproducible steps and collect logs/metrics for engineers
- Coordinate with Release Manager and PM for rollouts and mitigations
- Maintain the incident / postmortem artifacts and communicate customer impact

#### Goals
- Reduce time-to-detect and time-to-resolve production problems
- Provide actionable feedback to engineering and product teams

#### Typical Communication & Interactions
- Communicates incidents to PM and Release Manager
- Feeds prioritized issues into the backlog and risk register

---

### Business Analyst

#### Role Summary
Bridges business stakeholders and delivery teams by formalizing requirements and acceptance criteria.

#### Responsibilities
- Elicit and document business rules, constraints, and non-functional requirements
- Produce clear user stories and acceptance criteria aligned to business outcomes
- Validate delivered features against business needs and data

#### Goals
- Reduce rework due to ambiguous requirements
- Ensure delivered functionality meets stakeholder expectations

#### Typical Communication & Interactions
- Works with Product Manager, PM, Developers, and Stakeholders to clarify scope
- Participates in acceptance testing and sign-offs

---

## Role Interaction Guidelines & Suggested Artifacts

- Add an immediate “Role Owner” field on backlog items (Owner = Developer, QA Lead, UX Designer, etc.) to make handoffs explicit.
- Use a simple RACI mapping for major deliverables (e.g., release plan, build, test, deploy):
  - Responsible: Release Manager / Developer
  - Accountable: Project Manager / Product Manager
  - Consulted: QA Lead / UX Designer / Business Analyst
  - Informed: Stakeholders, Support
- Suggested artifact additions per project:
  - Role contact list in project README (names & responsibilities)
  - Release readiness checklist (see docs/checklists/release-readiness-checklist.md)
  - Role Responsibility template (docs/templates/role-responsibility-template.md)

---
