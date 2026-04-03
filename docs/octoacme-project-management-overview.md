# OctoAcme Project Management Overview

## Table of Contents

- [Purpose](#purpose)
- [Scope](#scope)
- [Principles](#principles)
- [Core Roles](#core-roles)
- [Key Artifacts](#key-artifacts)
- [Lifecycle (high-level)](#lifecycle-high-level)
- [Communication Cadence](#communication-cadence)
- [Role Hand-offs and Dependencies](#role-hand-offs-and-dependencies)
- [How to use these docs](#how-to-use-these-docs)

---

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.
- Inclusive collaboration: all roles have a defined voice and clear hand-off points.

## Core Roles
- **Project Manager (PM):** coordinates delivery, schedules, risk, and communications.
- **Product Manager (PdM):** defines outcomes, prioritizes backlog, and measures success.
- **Developers:** implement features, collaborate on design and testability.
- **QA / Testing Engineers:** validate quality, acceptance criteria, and release readiness.
- **Stakeholders:** provide strategic inputs and approvals.
- **UX Designers:** research user needs, design interfaces, and ensure usability and accessibility. *(See [Roles and Personas](octoacme-roles-and-personas.md#ux-designers))*
- **DevOps Engineers:** build and maintain CI/CD pipelines, environments, and deployment processes. *(See [Roles and Personas](octoacme-roles-and-personas.md#devops-engineers))*
- **Business Analysts:** bridge business and engineering by documenting and validating requirements. *(See [Roles and Personas](octoacme-roles-and-personas.md#business-analysts))*
- **Customer Support Leads:** channel customer feedback and ensure support readiness for releases. *(See [Roles and Personas](octoacme-roles-and-personas.md#customer-support-leads))*

For full role descriptions and interaction maps, see [Roles and Personas](octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- UX Design Specs and Wireframes *(owned by UX Designer)*
- Requirements Documentation and User Stories *(owned by Business Analyst)*
- Deployment Runbooks and Release Notes *(owned by DevOps Engineer)*

## Lifecycle (high-level)
1. **Initiation:** problem statement, stakeholders, high-level timeline. *(See [Project Initiation Guide](octoacme-project-initiation.md))*
2. **Planning:** scope, resources, milestones, dependencies. *(See [Project Planning](octoacme-project-planning.md))*
3. **Execution:** build, test, review, iterate. *(See [Execution & Tracking](octoacme-execution-and-tracking.md))*
4. **Release:** deploy, verify, announce. *(See [Release & Deployment Guide](octoacme-release-and-deployment.md))*
5. **Close & Retrospective:** capture learnings and next steps. *(See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))*

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Pre-release readiness review (PM, DevOps, QA, Customer Support Lead)
- Design review checkpoints (UX Designer, Product Manager, Developer)
- Ad-hoc escalations as needed

## Role Hand-offs and Dependencies

Clear hand-offs between roles reduce delays and miscommunication. Key dependencies across the lifecycle:

| Stage | Hand-off | From | To |
|---|---|---|---|
| Initiation | Business requirements and goals | Business Analyst / Stakeholders | Product Manager |
| Planning | Feature specs and acceptance criteria | Product Manager + Business Analyst | Developers + QA |
| Planning | UX wireframes and design specs | UX Designer | Developers |
| Planning | Environment and pipeline readiness | DevOps Engineer | Developers + QA |
| Execution | Completed feature for QA | Developer | QA / Testing |
| Execution | Design validation request | Developer | UX Designer |
| Release | Deployment execution | DevOps Engineer | Project Manager + Stakeholders |
| Release | Support readiness sign-off | Customer Support Lead | Project Manager |
| Post-Release | Customer feedback and trends | Customer Support Lead | Product Manager |

For a full interaction map, see the [Role Collaboration Matrix](octoacme-role-collaboration-matrix.md).

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Refer to [Roles and Personas](octoacme-roles-and-personas.md) for role-specific responsibilities and interaction guides.
- Use [Risk Management & Communication](octoacme-risks-and-communication.md) for risk tracking and escalation templates.
