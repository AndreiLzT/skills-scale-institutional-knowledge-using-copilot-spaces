# OctoAcme Personas

> **Related to:** [Issue #4 — Adding more personas and roles to the project management processes](https://github.com/AndreiLzT/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Table of Contents

- [Developers](#developers)
- [Product Managers](#product-managers)
- [Project Managers](#project-managers)
- [QA / Testing Engineers](#qa--testing-engineers)
- [Stakeholders](#stakeholders)
- [UX Designers](#ux-designers) *(new)*
- [DevOps Engineers](#devops-engineers) *(new)*
- [Business Analysts](#business-analysts) *(new)*
- [Customer Support Leads](#customer-support-leads) *(new)*
- [Role Interaction Overview](#role-interaction-overview)
- [How these personas are used in the exercise](#how-these-personas-are-used-in-the-exercise)

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

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Product Manager | Receives feature specs and acceptance criteria; raises technical feasibility concerns |
| Project Manager | Reports progress and blockers; flags technical risks |
| QA / Testing | Hands off completed features for validation; collaborates on test coverage |
| UX Designer | Implements UI/UX designs; raises implementation constraints early |
| DevOps Engineer | Coordinates pipeline integrations and deployment readiness |

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

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Project Manager | Aligns on timelines, scope, and priorities; makes trade-off decisions |
| Developers | Provides feature specs; validates built features against success metrics |
| QA / Testing | Reviews test coverage against acceptance criteria |
| UX Designer | Collaborates on user research, wireframe reviews, and usability outcomes |
| Business Analyst | Refines backlog and business requirements; validates user stories |
| Customer Support Lead | Receives user feedback and support escalations to inform prioritization |
| Stakeholders | Presents roadmap updates; collects strategic guidance and approvals |

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

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Product Manager | Weekly PM sync; scope and priority alignment |
| Developers | Sprint planning, daily standups, blocker resolution |
| QA / Testing | Milestone sign-off; tracks quality gates before release |
| UX Designer | Ensures design tasks are tracked and unblocked |
| DevOps Engineer | Coordinates deployment windows and release readiness |
| Business Analyst | Manages dependency tracking; leverages BA requirement documentation |
| Customer Support Lead | Aligns on support readiness before major releases |
| Stakeholders | Delivers status reports; escalates blockers as needed |

---

## QA / Testing Engineers

### Role Summary
QA / Testing Engineers validate that delivered features meet acceptance criteria and quality standards. They design and execute test plans, identify defects early, and act as a quality gate before releases.

### Responsibilities
- Design and execute test plans (unit, integration, end-to-end)
- Validate features against acceptance criteria and Definition of Done
- Log, track, and verify resolution of defects
- Participate in sprint reviews and release sign-off
- Maintain automated test suites and CI quality gates

### Goals
- Ensure high product quality and user experience
- Detect and prevent regressions before they reach production
- Continuously improve test coverage and automation

### Typical Communication
- Sprint reviews and QA sign-off meetings
- Defect reports and test result summaries
- Collaboration on acceptance criteria during planning

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Developers | Receives features for testing; aligns on testability and defect fixes |
| Product Manager | Clarifies acceptance criteria; provides quality sign-off |
| Project Manager | Reports test status and risks ahead of milestones |
| DevOps Engineer | Coordinates environment readiness and CI pipeline integration |
| UX Designer | Validates UI/UX implementations against design specifications |

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups who have an interest in the project outcome. They provide strategic guidance, approvals, and domain expertise at key project phases.

### Responsibilities
- Provide input on business requirements and priorities
- Review and approve key project deliverables (charter, roadmap, releases)
- Escalate blockers or decisions at the executive level when needed
- Offer domain expertise to inform trade-off decisions

### Goals
- Ensure the project aligns with business and strategic objectives
- Stay informed and provide timely decisions to avoid delays
- See measurable business outcomes delivered on time

### Typical Communication
- Monthly or milestone-based stakeholder updates
- Executive briefings and roadmap reviews
- Ad-hoc decision requests via PM escalation

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Project Manager | Receives status reports; provides approvals and decisions |
| Product Manager | Reviews roadmap priorities; provides strategic input |
| Customer Support Lead | Receives insights on customer satisfaction and support trends |

---

## UX Designers

### Role Summary
UX Designers research user needs, design interfaces and workflows, and ensure the product is usable, accessible, and aligned with business goals. They act as the advocate for the end user throughout the project lifecycle.

### Responsibilities
- Conduct user research, interviews, and usability studies
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers to translate user needs into feature designs
- Work with Developers to ensure accurate and faithful implementation
- Conduct usability testing and iterate based on feedback
- Define and maintain design standards and accessibility guidelines

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce friction in user workflows and support product adoption
- Ensure design decisions are grounded in user research and data

### Typical Communication
- Design reviews and prototype walkthroughs with Product Managers and Developers
- Usability testing reports and user research summaries
- Design handoff notes and annotated specs in design tools

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Product Manager | Co-leads ideation and feature design; validates designs against business goals |
| Developer | Hands off design specs; answers implementation questions; reviews final UI |
| QA / Testing | Reviews implemented UI against design specs to surface discrepancies |
| Project Manager | Provides design task estimates; flags design blockers |
| Business Analyst | Collaborates on user journey maps and workflow requirements |
| Customer Support Lead | Uses support insights to identify usability pain points |

---

## DevOps Engineers

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and operational tooling that enable reliable, frequent, and safe software delivery. They bridge development and operations to ensure system health and deployment confidence.

### Responsibilities
- Design and maintain CI/CD pipelines for automated build, test, and deploy
- Manage cloud infrastructure, environments (dev, staging, production), and monitoring
- Implement security scanning and compliance checks in the pipeline
- Coordinate deployment windows and production releases
- Monitor system health and respond to infrastructure incidents
- Document runbooks, deployment procedures, and environment setup guides

### Goals
- Enable fast, reliable, and repeatable software delivery
- Minimize downtime and mean time to recovery (MTTR)
- Ensure infrastructure is secure, scalable, and cost-effective

### Typical Communication
- Release coordination meetings with Project Managers and Developers
- Incident and on-call reports shared with Project Managers and Stakeholders
- Pipeline and environment status updates in project channels

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Developer | Provides pipeline tooling; collaborates on environment setup and deployment scripts |
| QA / Testing | Ensures CI test environments are available and correctly configured |
| Project Manager | Confirms deployment readiness; communicates deployment windows and incidents |
| Product Manager | Informs on system reliability and release feasibility |
| Stakeholders | Reports incident status and uptime impacts when relevant |

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They gather, document, and analyze business requirements to ensure the project delivers the right outcomes.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Write user stories, use cases, and process flows with clear acceptance criteria
- Facilitate requirements workshops and backlog refinement sessions
- Identify process inefficiencies and propose improvements
- Support change management by documenting impacts on existing workflows
- Act as a communication bridge between technical and non-technical stakeholders

### Goals
- Ensure all project requirements are well-understood, documented, and traceable
- Reduce ambiguity and rework by delivering clear, actionable specifications
- Align business objectives with technical solutions

### Typical Communication
- Requirements workshops and backlog refinement sessions
- User story documentation and process flow diagrams
- Bi-weekly check-ins with Product Managers and Project Managers

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Product Manager | Collaborates on backlog refinement; validates requirements against business goals |
| Developer | Clarifies requirements; answers questions during implementation |
| QA / Testing | Shares acceptance criteria and use cases to inform test plans |
| Project Manager | Helps identify dependencies and impacts; provides requirements documentation |
| Stakeholders | Facilitates requirements workshops; validates output with domain experts |
| UX Designer | Collaborates on user journey mapping and workflow documentation |

---

## Customer Support Leads

### Role Summary
Customer Support Leads manage the support team, channel user feedback to product and engineering, and ensure customers receive timely, accurate help. They act as the voice of the customer within the project team.

### Responsibilities
- Manage customer support operations and escalation workflows
- Document known issues, FAQs, and workarounds for the support team
- Aggregate and synthesize user feedback and support trends for Product Managers
- Collaborate with Product Managers on feature prioritization based on customer pain points
- Assess and communicate support readiness before major releases
- Coordinate customer communications during incidents or service disruptions

### Goals
- Ensure customers receive fast, accurate, and empathetic support
- Reduce support volume by surfacing product and documentation improvements
- Represent the customer's voice in product and project decisions

### Typical Communication
- Regular syncs with Product Managers to share support insights and feedback trends
- Pre-release readiness reviews with Project Managers
- Incident communications and customer-facing announcements

### Interactions with Other Roles
| Interacts With | Nature of Interaction |
|---|---|
| Product Manager | Shares feedback trends; influences prioritization of bugs and UX improvements |
| Project Manager | Advises on support readiness before releases; flags post-release issues |
| Developer | Reports reproducible bugs; validates fixes from a user impact perspective |
| Stakeholders | Communicates customer satisfaction metrics and escalated issues |
| UX Designer | Shares common user pain points to inform usability improvements |

---

## Role Interaction Overview

The table below summarizes the key hand-off and collaboration points between all roles. See the [Role Collaboration Matrix](octoacme-role-collaboration-matrix.md) for a full mapping of touchpoints across the project lifecycle.

| From \ To | Product Manager | Project Manager | Developer | QA/Testing | UX Designer | DevOps | Business Analyst | Customer Support |
|---|---|---|---|---|---|---|---|---|
| **Product Manager** | — | Scope & priority | Feature specs | Acceptance criteria | Design direction | Release feasibility | Requirement validation | Feedback intake |
| **Project Manager** | Timeline & risks | — | Sprint planning | Quality gates | Task tracking | Deployment windows | Dependency management | Release readiness |
| **Developer** | Feasibility input | Blocker reporting | — | Feature handoff | Design queries | Pipeline needs | Requirement clarification | Bug reports |
| **QA / Testing** | Sign-off | Test status | Defect reports | — | Design validation | Env readiness | Test case review | Known issues |
| **UX Designer** | Design approval | Design blockers | Design specs | UI/UX review | — | — | Journey mapping | Pain point insights |
| **DevOps** | Reliability updates | Incident reports | Pipeline support | CI environment | — | — | — | Incident comms |
| **Business Analyst** | Requirements | Dependency docs | User stories | Acceptance criteria | Journey maps | — | — | Support process flows |
| **Customer Support** | Feedback trends | Post-release issues | Bug reports | — | UX pain points | Incident comms | — | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Role Collaboration Matrix](octoacme-role-collaboration-matrix.md) for cross-role interaction templates.
- See the [Project Management Overview](octoacme-project-management-overview.md) for how these roles fit into the broader lifecycle.

