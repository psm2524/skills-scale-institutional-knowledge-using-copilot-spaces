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

## Additional Personas (proposed additions)

To reduce ambiguity and improve accountability across cross-functional delivery, add the following personas. Each persona below includes a short responsibilities list and how they typically interact with existing roles.

- Technical Lead
  - Responsibilities: Owns major technical design decisions and architecture; defines non-trivial technical approaches; ensures codebase health and high-level implementation consistency; reviews major PRs and coordinates cross-team integrations.
  - Interactions: Works closely with Developers, Project Manager, and Product Lead to align technical strategy with product goals; advises PM on technical feasibility and effort; escalates unresolved technical blockers to engineering leadership.

- Delivery Lead
  - Responsibilities: Oversees day-to-day delivery execution for larger initiatives; manages cross-team coordination, release readiness, and delivery cadence; tracks dependencies and mitigations across multiple teams.
  - Interactions: Partners with Project Manager and PM to track timelines and unblock work; coordinates with QA, DevOps, and Release Engineers during releases; reports progress to stakeholders.

- UX Researcher / Designer
  - Responsibilities: Leads user research, usability testing, and creation of design artifacts; translates user insights into requirements and acceptance criteria; ensures accessibility and usability standards are met.
  - Interactions: Collaborates with Product Manager and Developers to refine acceptance criteria and prototype handoffs; participates in planning and sprint reviews for design alignment.

- Security Engineer
  - Responsibilities: Conducts threat modeling, security reviews, and ensures compliance with security requirements; recommends mitigations for identified security risks; participates in code and architecture reviews where applicable.
  - Interactions: Engages during planning and design review stages; raises security-related blockers and coordinates remediation with Developers and Technical Leads; works with Release/DevOps for secure deployments.

- Data Analyst / Data Engineer
  - Responsibilities: Defines measurement strategy and success metrics; validates telemetry and instrumentation; provides data analysis to inform decisions and verify outcomes.
  - Interactions: Works with Product Manager to set measurable success criteria; partners with Developers/QA to ensure data quality and instrumentation; produces dashboards and reports for stakeholders.

- Stakeholder Liaison (Business Owner)
  - Responsibilities: Represents the business or sponsoring group's priorities; approves major scope decisions and trade-offs; clarifies business requirements and acceptance for features with business impact.
  - Interactions: Coordinates with PM and Product Lead for prioritization and escalations; participates in key decision gates and milestone reviews.

---

## Persona Responsibilities & Interaction Mapping

| Persona | Primary Responsibilities | Primary Collaborations / Handoffs |
|---|---:|---|
| Developers | Implement code, tests, docs, fix bugs | Product Manager (requirements), Technical Lead (design), QA (validation) |
| Product Manager | Define outcomes, prioritize backlog | PM, Stakeholder Liaison, UX, Data Analyst |
| Project Manager | Schedule, risk, reporting | PM, Delivery Lead, Stakeholders |
| Technical Lead | Architecture, major technical decisions | Developers, PM, Security Engineer |
| Delivery Lead | Cross-team delivery, release readiness | Project Manager, QA, DevOps |
| UX Researcher / Designer | Research, UX, accessibility | PM, Developers, QA |
| Security Engineer | Threat modeling, reviews, compliance | Technical Lead, Developers, DevOps |
| Data Analyst / Data Engineer | Metrics, telemetry, analysis | PM, Developers, Stakeholders |
| Stakeholder Liaison | Business priorities, approvals | PM, Project Manager, Product Lead |

Notes:
- The table is intentionally concise — link to role sections above for more detail.
- Teams can adapt or rename these personas (e.g., “Tech Lead” vs “Architect”) to fit organizational structure, but the responsibilities should remain explicit.
