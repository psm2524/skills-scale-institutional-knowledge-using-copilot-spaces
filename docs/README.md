# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management framework. This documentation provides comprehensive guidance for running projects with clear ownership, iterative delivery, and data-driven decision-making.

## Quick Start

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction to our principles, roles, and artifacts.

## Core Principles

- 🎯 **Customer-first**: Prioritize customer value and usability
- 📦 **Iterative delivery**: Deliver small, testable increments
- 👤 **Clear ownership**: Named Project Manager and Product Lead per project
- 📊 **Data-informed**: Measure impact and iterate based on evidence
- 🤝 **Psychological safety**: Encourage feedback and learning

## Overview: How OctoAcme Manages Projects

OctoAcme follows a structured five-phase project lifecycle designed around iterative delivery and clear ownership. Each project is guided by a dedicated Project Manager (coordinating delivery, timelines, and communications) and a Product Manager (defining outcomes, prioritizing the backlog, and measuring success). This dual-role structure ensures clear separation between what gets built and how it gets built.

Throughout execution, teams maintain a predictable rhythm of daily standups, weekly delivery syncs, and sprint-based planning. Work flows through a project board, and pull requests are kept small with clear acceptance criteria and at least one approval before merging. Quality is embedded throughout the process via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA when needed. Release management is standardized with comprehensive checklists, staged deployments, and documented rollback plans.

Risk management is central to planning and execution. Teams capture risks in a simple register and review them during weekly syncs, with a three-level escalation path (team triage → PM escalation → sponsor-level) ensuring blockers are surfaced quickly. Retrospectives occur after each sprint or milestone, examining what went well and what could improve, with prioritized action items feeding back into the project backlog. By coupling clear processes with lightweight artifacts and regular feedback loops, OctoAcme reduces single-person dependency risk, accelerates onboarding, and enables consistent, repeatable execution across projects.

## Documentation Hub

### Project Lifecycle Phases

1. [**Initiation**](./octoacme-project-initiation.md) — Validate need, align stakeholders, create lightweight plan
2. [**Planning**](./octoacme-project-planning.md) — Break work into shippable increments, identify risks and dependencies
3. [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery, measure progress
4. [**Release & Deployment**](./octoacme-release-and-deployment.md) — Deploy to production safely with rollback plans
5. [**Retrospective & Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive continuous improvement

### Cross-cutting Guides

- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks throughout the lifecycle
- [**OctoAcme Personas**](./octoacme-roles-and-personas.md) — Role definitions for Developers, Product Managers, and Project Managers

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Roles at a Glance

- **Project Manager**: Coordinates delivery, schedules, risks, and communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria

For detailed role descriptions, see [OctoAcme Personas](./octoacme-roles-and-personas.md).

## Tips for Success

- Keep your Project Charter and One-pager updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to reference them
- Review the relevant phase guide at the start of each project phase
- Use the checklists provided in each guide to ensure completeness
