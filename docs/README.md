# OctoAcme Project Management Processes

## Overview

OctoAcme employs a customer-first, iterative approach to project delivery grounded in five core principles: customer value prioritization, iterative delivery of testable increments, clear ownership through designated Project Managers and Product Leads, data-informed decision-making, and psychological safety to encourage feedback. The project lifecycle follows a structured five-phase approach: Initiation (problem definition and stakeholder alignment), Planning (scope definition and backlog creation), Execution (build, test, and iterate), Release (deployment and verification), and Close & Retrospective (capturing learnings). Key artifacts maintained throughout the lifecycle include a Project Charter, roadmap and release plan, sprint backlogs with acceptance criteria, a Definition of Done, a risk register, and retrospective action items, ensuring transparency and alignment across teams.

## Roles and Personas

OctoAcme defines three primary personas with distinct responsibilities:

- **Project Managers** coordinate delivery activities, manage risks and dependencies, and facilitate communications across stakeholders
- **Product Managers** define the vision, prioritize the backlog, validate solutions through research and metrics, and own success criteria
- **Developers** implement features, write tests, participate in reviews, and help identify technical risks

This clear role separation enables efficient collaboration while maintaining accountability. Communication cadence is structured through weekly syncs between PM and Product Manager, twice-weekly delivery standups, monthly stakeholder updates, and ad-hoc escalations as needed.

## Execution and Quality Assurance

Execution and quality assurance are tightly integrated through a disciplined workflow combining daily 15-minute standups, weekly delivery syncs, and sprint-based demos. Teams use GitHub Projects with defined columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforce small pull requests (≤400 lines) with automated CI testing, linting, and mandatory approvals before merge.

Quality gates include:
- Unit tests
- Integration tests
- End-to-end smoke tests
- Security scanning
- Manual QA for feature acceptance

Risk management is active throughout the project, with a formal Risk Register tracking impact, likelihood, ownership, and mitigation plans, reviewed weekly and escalated through defined levels (team → PM → Product Lead → Sponsor).

## Release and Continuous Improvement

Deployment follows a controlled release strategy with defined patch, minor, and major release types, supported by comprehensive pre-release requirements including passing CI scans, drafted release notes, and tested rollback plans. Post-release, the team conducts structured retrospectives after each sprint, milestone, or incident to capture what went well, identify improvements, and define actionable items with clear owners and timelines. This continuous improvement culture is reinforced by measuring the impact of action items and celebrating incremental progress, ensuring that OctoAcme learns and evolves with each project cycle.

---

## Documentation

For detailed process documentation, see:
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
