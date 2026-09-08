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

## Additional operational personas

To improve clarity and accountability across delivery, release, security, design, and support activities, add the following operational and liaison personas.

- Release Manager
  - Responsibilities: Owns release scheduling, deployment coordination, rollback planning, and post-release verification (smoke checks). Prepares release notes and runbooks.
  - Interactions: Works with Project Manager for scheduling, Developers and Engineering Leads for deployment tasks and rollback plans, QA for pre-release verification, and Support for post-release monitoring and incident readiness.

- Delivery Lead
  - Responsibilities: Focuses on sprint-level execution—ensures backlog readiness, refines scope for upcoming iterations, coordinates cross-team dependencies, and clears execution blockers.
  - Interactions: Collaborates with Project Manager and Product Manager on priorities, coordinates with Tech/Engineering Leads on technical dependencies, and aligns with QA to ensure acceptance criteria are testable.

- Engineering Lead / Tech Lead
  - Responsibilities: Serves as the technical owner for architecture, design decisions, and implementation trade-offs. Mentors developers and enforces engineering standards.
  - Interactions: Partners with Product Manager on technical feasibility and scope, works with Developers on implementation, and coordinates with QA on testability and observable requirements.

- UX / Research Liaison
  - Responsibilities: Ensures research and design considerations are introduced early, coordinates user testing and validation, and translates UX findings into actionable requirements.
  - Interactions: Engages with Product Managers to align user needs, works with Developers to integrate designs, and shares findings with Project Managers to influence scheduling and scope.

- Security Liaison
  - Responsibilities: Coordinates security reviews, threat modeling, and triage of security findings; tracks remediation and ensures security gates are met prior to release.
  - Interactions: Interfaces with Engineering Leads and Developers to implement fixes, notifies Project Managers about security-related schedule impacts, and escalates to Security on-call when needed.

- Support Liaison (Customer Ops)
  - Responsibilities: Brings customer-impact insights, triages incoming incidents, maintains runbooks, and coordinates communications and handoffs during incidents and releases.
  - Interactions: Works with Release Manager for rollout communications, with Project Manager for prioritization of customer-impacting fixes, and with Developers for reproducing and resolving customer issues.

Suggested next steps
- Add this "Additional operational personas" section to docs/octoacme-roles-and-personas.md.
- Keep entries concise and include one-line interactions as shown.
- Review these additions with PM, Product Lead, Security, and Support stakeholders before merging.
