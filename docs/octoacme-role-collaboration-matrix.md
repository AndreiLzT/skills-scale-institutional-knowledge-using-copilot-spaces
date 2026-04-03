# OctoAcme — Role Collaboration Matrix

> **Related to:** [Issue #4 — Adding more personas and roles to the project management processes](https://github.com/AndreiLzT/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

This document maps the hand-offs, dependencies, and key collaboration touchpoints between all OctoAcme project roles across each lifecycle stage.

For full role descriptions, see [Roles and Personas](octoacme-roles-and-personas.md).

---

## Table of Contents

- [How to Use This Matrix](#how-to-use-this-matrix)
- [Lifecycle Stage: Initiation](#lifecycle-stage-initiation)
- [Lifecycle Stage: Planning](#lifecycle-stage-planning)
- [Lifecycle Stage: Execution](#lifecycle-stage-execution)
- [Lifecycle Stage: Release](#lifecycle-stage-release)
- [Lifecycle Stage: Retrospective](#lifecycle-stage-retrospective)
- [Cross-Role Dependency Checklist](#cross-role-dependency-checklist)

---

## How to Use This Matrix

- Use this document during **project kickoff** to identify which roles need to be involved at each stage.
- Reference the **hand-off checkpoints** before moving between lifecycle stages.
- Use the **dependency checklist** at the bottom to confirm all role inputs are complete before proceeding.

---

## Lifecycle Stage: Initiation

**Goal:** Validate the project concept, align stakeholders, and authorize planning.

| Hand-off | From | To | Artifact / Output |
|---|---|---|---|
| Business need and strategic context | Stakeholders | Product Manager | Initial goals and constraints |
| Requirements elicitation | Business Analyst | Product Manager | Initial requirements doc |
| Customer pain points | Customer Support Lead | Product Manager | Feedback summary |
| Infrastructure feasibility | DevOps Engineer | Project Manager | Environment and timeline constraints |
| User research needs | UX Designer | Product Manager | Research plan outline |
| Project one-pager | Product Manager + Project Manager | Stakeholders | Project One-pager for approval |

**Gate:** Stakeholder sign-off on the project one-pager. See [Project Initiation Guide](octoacme-project-initiation.md#decision-gate).

---

## Lifecycle Stage: Planning

**Goal:** Convert the approved initiative into an actionable backlog, release plan, and team commitments.

| Hand-off | From | To | Artifact / Output |
|---|---|---|---|
| Prioritized requirements | Business Analyst | Product Manager | User stories with acceptance criteria |
| UX wireframes and design specs | UX Designer | Developers + QA | Design handoff package |
| Backlog with acceptance criteria | Product Manager | Developers + QA | Sprint-ready backlog |
| Test strategy | QA / Testing | Product Manager + Developers | Test plan |
| Pipeline and environment plan | DevOps Engineer | Developers + QA | CI/CD setup guide |
| Support readiness input | Customer Support Lead | Project Manager | Known risks from customer perspective |
| Risk register | Project Manager | All roles | Initial risk register |
| Release plan | Project Manager + DevOps | All roles | Release milestone map |

**Gate:** Planning checklist complete. See [Project Planning](octoacme-project-planning.md#planning-checklist).

---

## Lifecycle Stage: Execution

**Goal:** Build, test, and iterate on features within sprint cycles.

| Hand-off | From | To | Artifact / Output |
|---|---|---|---|
| Feature implementation | Developers | QA / Testing | Feature branch / PR ready for QA |
| Design review request | Developers | UX Designer | UI implemented — needs design validation |
| QA sign-off | QA / Testing | Project Manager | Test results and defect report |
| Defect report | QA / Testing | Developers | Defect tickets with reproduction steps |
| Design validation feedback | UX Designer | Developers | Design gap notes and revision requests |
| Risk and blocker updates | Project Manager | All roles (weekly sync) | Updated risk register |
| CI/CD status | DevOps Engineer | Developers + Project Manager | Pipeline health and environment updates |
| Sprint status report | Project Manager | Stakeholders | Bi-weekly progress update |

**Gate:** All acceptance criteria met; QA sign-off obtained. See [Execution & Tracking](octoacme-execution-and-tracking.md#execution-checklist).

---

## Lifecycle Stage: Release

**Goal:** Deploy the release safely, verify correctness, and communicate to stakeholders.

| Hand-off | From | To | Artifact / Output |
|---|---|---|---|
| Release readiness confirmation | QA / Testing | Project Manager | Final QA sign-off |
| Support readiness review | Customer Support Lead | Project Manager | Support team readiness sign-off |
| Deployment execution | DevOps Engineer | Project Manager + Stakeholders | Deployment status and post-deploy verification |
| Release notes | Product Manager + DevOps | Stakeholders + Customer Support | Published release notes |
| Customer communication | Customer Support Lead | Customers | Release announcement or FAQ update |
| Rollback plan | DevOps Engineer | Project Manager | Rollback runbook |

**Gate:** All deployment checklist items complete. See [Release & Deployment Guide](octoacme-release-and-deployment.md#deployment-checklist).

---

## Lifecycle Stage: Retrospective

**Goal:** Capture learnings and translate them into improvements for the next cycle.

| Hand-off | From | To | Artifact / Output |
|---|---|---|---|
| Post-release customer feedback | Customer Support Lead | Product Manager + UX Designer | Feedback summary and support ticket trends |
| Process improvement observations | All roles | Project Manager | Retrospective action items |
| Resolved action items | Project Manager | All roles | Updated process docs or backlog items |
| UX improvement recommendations | UX Designer | Product Manager | Usability findings report |
| Pipeline improvement needs | DevOps Engineer | Project Manager | Infrastructure action items |

**Gate:** Action items assigned with owners and due dates. See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

---

## Cross-Role Dependency Checklist

Use this checklist when transitioning between project stages to confirm all role contributions are in place.

### Initiation → Planning
- [ ] Product Manager has documented the problem statement and success metrics
- [ ] Business Analyst has completed initial requirements gathering
- [ ] Stakeholders have approved the project one-pager
- [ ] UX Designer has scoped user research needs
- [ ] DevOps Engineer has provided infrastructure feasibility input
- [ ] Customer Support Lead has shared relevant customer pain points

### Planning → Execution
- [ ] Backlog is prioritized with acceptance criteria for at least the first sprint
- [ ] UX Designer has delivered wireframes and design specs
- [ ] QA / Testing has drafted the test plan
- [ ] DevOps Engineer has CI/CD environment ready
- [ ] Risk register is populated and reviewed
- [ ] Definition of Done is agreed and documented

### Execution → Release
- [ ] All sprint acceptance criteria are met and QA has signed off
- [ ] Release notes are drafted
- [ ] DevOps Engineer has prepared the deployment plan and rollback runbook
- [ ] Customer Support Lead has confirmed support readiness
- [ ] Stakeholders have been briefed on release scope

### Release → Retrospective
- [ ] Deployment completed and post-deploy verification passed
- [ ] Release announced to stakeholders and support team
- [ ] Any incidents triaged and documented
- [ ] Retrospective scheduled with all key roles invited

---

*For role descriptions, see [Roles and Personas](octoacme-roles-and-personas.md).*
*For risk management, see [Risk Management & Communication](octoacme-risks-and-communication.md).*
