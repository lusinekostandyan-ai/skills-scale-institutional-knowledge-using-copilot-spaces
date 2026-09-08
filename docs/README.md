# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management framework documentation. This directory contains comprehensive guidance for managing projects from initiation through retrospective, including workflows, roles, communication strategies, and quality assurance practices.

## Project Management Process Overview

OctoAcme follows a structured, iterative project lifecycle designed to balance speed with risk management across five core phases: Initiation, Planning, Execution, Release, and Retrospective. The framework is built on principles of customer-first delivery, clear ownership, data-informed decisions, and psychological safety. Each project is anchored by a **Project One-pager** that defines the problem statement, measurable success metrics, and stakeholder alignment before any significant work begins. Once approved by leadership, the team moves into planning—breaking work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done.

OctoAcme operates with clear role definitions that distribute accountability: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** own the vision, prioritize the backlog, and measure outcomes; **Developers** implement features and contribute to estimation and technical risk identification; and **QA/Testing** validates acceptance criteria and quality gates. Communication happens through a structured cadence: daily 15-minute standups focused on progress and blockers, weekly delivery syncs to review progress and flag risks, and monthly stakeholder updates to maintain alignment.

During execution, teams work within GitHub Projects using a standardized workflow and maintain small pull requests with clear acceptance criteria. Quality is enforced through multiple gates: unit tests, integration and end-to-end smoke tests, security scanning in CI, and manual QA. Every PR requires at least one approval before merging. Releases are standardized by type (Patch, Minor, Major) with pre-release requirements and post-deployment verification. After each sprint or milestone, the team conducts a retrospective to capture learnings and drive continuous improvement—creating a closed loop that enables consistent delivery while building institutional knowledge.

## Documentation Index

Navigate to the process document that fits your current project phase or role:

### Core Process Documents

| Document | Purpose | Best For |
|----------|---------|----------|
| **[Project Management Overview](./octoacme-project-management-overview.md)** | Concise introduction to OctoAcme's approach, roles, and key artifacts | New team members, quick reference |
| **[Project Initiation](./octoacme-project-initiation.md)** | Validate business need, align stakeholders, and create a lightweight plan | Starting a new project or feature proposal |
| **[Project Planning](./octoacme-project-planning.md)** | Turn an approved initiative into an actionable plan and backlog for delivery | Planning phase, scope definition |
| **[Execution and Tracking](./octoacme-execution-and-tracking.md)** | Manage day-to-day execution and track progress toward project milestones | Active delivery teams, daily standups |
| **[Risks and Communication](./octoacme-risks-and-communication.md)** | Identify, manage, and communicate risks and dependencies | Risk management, stakeholder updates |
| **[Release and Deployment](./octoacme-release-and-deployment.md)** | Standardize how OctoAcme releases features to production | Release planning, deployment procedures |
| **[Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** | Capture learnings and convert them into actionable improvements | Sprint/milestone retrospectives, process improvement |
| **[Roles and Personas](./octoacme-roles-and-personas.md)** | Define typical roles and responsibilities in OctoAcme projects | Understanding team structure, role-specific guidance |

## Quick Reference: Project Lifecycle at a Glance

```
INITIATION → PLANNING → EXECUTION → RELEASE → RETROSPECTIVE
     ↓           ↓           ↓         ↓            ↓
 One-pager   Backlog &   Daily      Deploy &     Learnings &
 Alignment   Milestones  Standups   Verification  Improvements
```

### Key Artifacts by Phase

- **Initiation**: Project One-pager, Stakeholder list, Initial risk list
- **Planning**: Prioritized backlog, Definition of Done, Risk Register, Release plan
- **Execution**: Sprint backlog, PR descriptions, Acceptance criteria, Risk updates
- **Release**: Release notes, Deployment checklist, Rollback plan, Post-deploy verification
- **Retrospective**: Retrospective notes, Action items, Impact measurement

## Communication Cadence

- **Daily**: 15-minute standups (progress, blockers, dependencies)
- **Weekly**: Delivery sync with PM + PdM; Risk register updates
- **Monthly**: Stakeholder updates and status reports
- **Ad-hoc**: Escalations via defined escalation path (Team → PM → Product Lead → Sponsor)

## Core Principles

1. **Customer-first**: Prioritize customer value and usability
2. **Iterative delivery**: Deliver small, testable increments
3. **Clear ownership**: Each project has a named PM and Product Lead
4. **Data-informed decisions**: Measure impact and iterate based on evidence
5. **Psychological safety**: Encourage feedback and learning

## Getting Started

**New to OctoAcme?**
- Start with [Project Management Overview](./octoacme-project-management-overview.md)
- Review [Roles and Personas](./octoacme-roles-and-personas.md) to understand your role

**Starting a new project?**
- Follow [Project Initiation](./octoacme-project-initiation.md) to validate your idea
- Then move to [Project Planning](./octoacme-project-planning.md) to create your plan

**In active delivery?**
- Refer to [Execution and Tracking](./octoacme-execution-and-tracking.md) for workflows
- Use [Risks and Communication](./octoacme-risks-and-communication.md) for risk management
- Check [Release and Deployment](./octoacme-release-and-deployment.md) when approaching release

**Wrapping up?**
- Use [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Review and update these documents regularly as processes evolve
- Share feedback and suggested improvements via issues or pull requests

---

**Questions or feedback?** Open an issue or reach out to your Product Manager or Project Manager.
