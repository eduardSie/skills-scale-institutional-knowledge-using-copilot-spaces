# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation Hub. This directory contains comprehensive guidance for running projects at OctoAcme using our standardized processes, roles, and best practices.

## Overview

OctoAcme uses a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. Our processes are designed to scale institutional knowledge across the organization while maintaining consistency and transparency.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Framework

### Process Overview and Lifecycle

OctoAcme manages projects through a five-phase lifecycle that emphasizes structured planning, transparent communication, and continuous improvement. The project lifecycle spans **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments and defining success criteria), **Execution** (daily build, test, and review cycles), **Release** (standardized deployment with rollback safeguards), and **Close & Retrospective** (capturing learnings and driving continuous improvement). At each stage, teams rely on lightweight artifacts—including a Project One-pager, prioritized backlogs with acceptance criteria, and risk registers—to maintain alignment and transparency. This phased approach ensures that decisions are made with clear success metrics and that dependencies across teams are identified early and monitored throughout delivery.

### Roles, Communication, and Accountability

The framework defines three core delivery roles: **Product Managers** who own the vision and prioritize the backlog; **Project Managers** who coordinate schedules, risks, and stakeholder communications; and **Developers** who implement features while maintaining high quality and testability. Cross-functional collaboration is baked into the cadence: daily standups (15 minutes) focus on progress and blockers, weekly PM-PdM syncs ensure alignment, and twice-weekly team standups maintain momentum. Stakeholders receive monthly updates and can be escalated to when blockers threaten delivery. This clear ownership model, combined with a consistent communication rhythm, reduces single-person dependency risk and gives all team members equal access to decisions and rationale.

### Quality, Risk Management, and Continuous Improvement

Quality is embedded throughout execution via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. Risk management is structured around a simple risk register (tracking ID, description, impact, likelihood, owner, and mitigation), reviewed weekly and escalated through defined levels (team → PM → Product Lead → Sponsor). Teams use a standardized Definition of Done to ensure consistency, small PRs (≤400 lines) to enable faster reviews, and automated CI/CD pipelines to reduce manual error. After each sprint, release, or incident, retrospectives capture what went well and what could improve, with 2–3 prioritized action items fed back into the backlog. This cycle of building incrementally, measuring impact, and iterating based on evidence ensures OctoAcme teams deliver reliably while continuously strengthening their processes.

## Project Management Process Documents

### Project Lifecycle Phases

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need, align stakeholders, and authorize work |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments and define delivery plan |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day delivery and track progress toward milestones |
| **Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize feature releases and deployments to production |
| **Retrospective** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into improvements |

### Cross-Cutting Topics

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to how OctoAcme runs projects, key roles, artifacts, and communication cadence
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks, dependencies, and stakeholder updates
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of key project roles including Developers, Product Managers, and Project Managers

## Quick Links

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Begin with [Project Initiation Guide](./octoacme-project-initiation.md)
- **Need to manage risks?** See [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Releasing to production?** Check [Release & Deployment Guide](./octoacme-release-and-deployment.md)

## Contributing to These Docs

Have feedback, found a gap, or want to improve the processes? Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to:
- Suggest clarifications or updates
- Propose new content or checklists
- Share process improvements based on team feedback

---

*Maintained by: OctoAcme Project Management Team*

_Last updated: 2026-05-16_
