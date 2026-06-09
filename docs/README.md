# OctoAcme Project Management Docs

Welcome! This README provides a quick overview of OctoAcme's project management approach and navigation links to core process documentation.

## Project Management Approach (Summary)

OctoAcme follows a comprehensive, lifecycle-based project management approach centered on five core phases: **Initiation, Planning, Execution, Release, and Retrospective**. The process prioritizes customer value, iterative delivery, clear ownership, and data-informed decisions.

### Key Principles
- **Iterative Delivery:** Work is broken into increments and delivered in cycles for feedback and improvement
- **Clear Roles & Ownership:** Each project has a named Project Manager who coordinates delivery and a Product Manager who defines outcomes and measures success
- **Risk & Communication Focus:** Risks, milestones, and communications are tracked with clear escalation paths
- **Quality & Velocity:** Continuous integration, testing, and sprint-style reviews are built into the process
- **Psychological Safety:** Teams are encouraged to provide feedback and learn from experiences

### The OctoAcme Lifecycle

**Initiation:** Projects begin with a lightweight one-pager that validates business need, aligns stakeholders, and establishes success metrics before moving to planning. This ensures all projects have clear objectives and stakeholder buy-in.

**Planning:** Approved work is broken into a prioritized backlog with acceptance criteria, dependencies and risks are identified, and a release timeline is defined. This phase transforms the vision into an actionable plan.

**Execution:** Teams operate on a predictable rhythm of daily standups, weekly delivery syncs, and sprint-based iterations using GitHub Projects. Pull requests follow tight conventions with automated CI testing, linting, and required approvals. Quality assurance is embedded throughout with unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA for feature acceptance.

**Release:** Features are deployed to production following a standardized process that includes pre-release verification, deployment checklists, smoke tests, and documented rollback contingencies. This reduces risk and ensures observability.

**Retrospective:** After each sprint, release, or milestone, teams hold a retrospective to capture learnings and convert them into actionable improvements, ensuring continuous organizational learning and process refinement.

### Core Roles & Communication

Three primary personas drive OctoAcme projects:
- **Developers** implement features and fixes to meet acceptance criteria while managing technical risk
- **Product Managers** define what should be built to deliver customer and business value
- **Project Managers** coordinate delivery activities, manage schedules, risks, and communications

Communication happens through weekly PM–PdM syncs, twice-weekly standups for delivery teams, and monthly stakeholder updates, with ad-hoc escalations for blockers and critical issues. A tiered escalation system (team → PM → Product Lead → Sponsor) ensures risks are surfaced early and resolved transparently.

## Docs Index

Navigate to the process documents below for detailed guidance on each phase:

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need, align stakeholders, confirm success metrics |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments, identify dependencies, establish timelines |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress, escalate blockers |
| **Risks** | [Risks & Communication](./octoacme-risks-and-communication.md) | Identify, assess, and communicate risks and dependencies |
| **Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize how features are released to production safely |
| **Closing** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into improvements |

### Additional Resources

- [Project Management Overview](./octoacme-project-management-overview.md) — Comprehensive introduction to OctoAcme PM approach, roles, and artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of typical roles, responsibilities, and communication patterns

## Quick Start

**New to OctoAcme?**
1. Start with [Project Management Overview](./octoacme-project-management-overview.md) for a full introduction
2. Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand team structure
3. Navigate to the phase-specific docs based on your current work

**Onboarding a new project?**
1. Follow [Project Initiation Guide](./octoacme-project-initiation.md)
2. Move to [Project Planning](./octoacme-project-planning.md) once approved
3. Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) during delivery

**Managing risks or communications?**
→ See [Risks & Communication](./octoacme-risks-and-communication.md)

**Preparing for release?**
→ See [Release & Deployment Guide](./octoacme-release-and-deployment.md)

**Running a retrospective?**
→ See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Using These Docs

- **Keep process docs updated:** As your team learns and evolves, update these docs to reflect current practices
- **Link from project repos:** Reference these docs in your project README or charter
- **Use with Copilot Spaces:** Add process docs to your Copilot Space context to get role-specific guidance aligned with OctoAcme practices
- **Contribute improvements:** Found a gap or have a suggestion? Open an issue to propose updates

---

*Last updated: June 2026*
