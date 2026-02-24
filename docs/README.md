# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management process documentation. This README provides a concise overview of our project management approach and direct links to all detailed process guides.

---

## Overview of OctoAcme Project Management Processes

OctoAcme follows a **structured, iterative project lifecycle** grounded in customer-first principles, psychological safety, and data-informed decision-making. Our approach emphasizes delivering small, testable increments with clear ownership and continuous improvement.

### Five Core Phases

1. **Initiation** — Validate business needs, align stakeholders, and create a Project One-pager with success metrics and initial risks.

2. **Planning** — Break work into shippable increments, identify dependencies, define acceptance criteria, and establish milestones and release timelines.

3. **Execution** — Deliver iteratively with daily standups, GitHub Projects boards, small PRs (≤400 lines), rigorous testing (unit, integration, end-to-end smoke tests), and continuous risk monitoring.

4. **Release** — Deploy standardized releases with pre-release checklists, CI/security scans, rollback plans, and clear stakeholder communication.

5. **Retrospective & Continuous Improvement** — Capture learnings through structured reviews, convert action items into backlog issues with clear owners and success criteria, and measure impact of process improvements.

### Key Roles & Communication

**Core Roles:**
- **Project Manager (PM)** — Coordinates schedules, risks, and cross-team communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes the backlog, and measures success
- **Developers** — Implement features, own code quality, and collaborate on design
- **QA/Testing** — Validates acceptance criteria and feature quality

**Communication Cadence:**
- Daily standups (15 min)
- Weekly PM–PdM syncs
- Twice-weekly delivery standups
- Monthly stakeholder updates
- Clear escalation paths: Team → PM → Product Lead → Sponsor

### Quality Assurance & Risk Management

- **Testing:** Unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for acceptance
- **Risk Management:** Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation) reviewed weekly and updated continuously
- **Single Source of Truth:** Project README, risk register, and release documentation maintained for transparency

---

## Quick Links to Process Documentation

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation](./octoacme-project-initiation.md) | Steps to validate business need, align stakeholders, and create a Project One-pager |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into shippable increments, estimating, and managing dependencies |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery: standups, PRs, testing, and blocker escalation |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, stakeholder communication templates, and escalation paths |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback playbook |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |

---

## Getting Started

- **New to OctoAcme projects?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) guide
- **Managing day-to-day work?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Preparing a release?** Use [Release & Deployment](./octoacme-release-and-deployment.md)
- **Running a retrospective?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## How to Use These Docs

- Keep the Project One-pager updated in your project repository
- Add these process docs to your project's `.copilot/` folder if you want Copilot Spaces to use them as context
- Use the templates and checklists in each document to ensure consistency across teams
- Contribute improvements via pull requests—these are living documents