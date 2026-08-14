# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization operates across five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. This documentation provides comprehensive guidance for all project phases, roles, and best practices.

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Lifecycle

### Initiation Phase
During initiation, teams validate business need and align stakeholders by producing a lightweight Project One-pager that defines the problem, success metrics, and resource needs. Once approved at a decision gate, the project moves forward with confirmed business value and stakeholder alignment.

### Planning Phase
Work is broken into shippable increments, backlog items are prioritized with acceptance criteria, dependencies are mapped, and a Definition of Done is established. This structured handoff ensures that execution teams inherit a clear, actionable plan rather than ambiguous scope.

### Execution & Tracking Phase
Execution and delivery are coordinated through a defined team rhythm: daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs review milestones and flag risks, and demos occur at sprint or milestone endpoints. Quality assurance is embedded throughout, including unit tests, integration tests, end-to-end smoke tests, and security scanning in CI.

### Release & Deployment Phase
Release and deployment are standardized through pre-release checklists, smoke test execution, rollback playbooks, and comprehensive release notes. This ensures consistent, low-risk deployments to production.

### Close & Retrospective Phase
Retrospectives after each sprint or release capture learnings and convert them into measurable action items tracked alongside the project backlog, driving continuous improvement.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Key Practices

### Communication Strategy
- **Daily standups**: 15-minute team syncs on progress and blockers
- **Weekly delivery syncs**: Show progress, updates, and flagged risks
- **Weekly PM-PdM alignment**: Coordinate strategy and priorities
- **Monthly stakeholder updates**: Communicate status using a single source of truth
- **Ad-hoc escalations**: As needed for urgent issues

### Risk Management
- Maintain a **Risk Register** tracking ID, description, impact, likelihood, owner, and mitigation plan
- Review risks weekly during syncs
- Escalate through three-tier system: team → PM → Product Lead → Sponsor
- Proactive monitoring and mitigation planning

### Quality Assurance
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Pull requests kept small (≤400 lines when possible)
- Require at least one approval before merging

## Documentation Index

Navigate to the specific process documentation you need:

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's project management framework, roles, and key artifacts

### Project Phases
- **[Project Initiation](octoacme-project-initiation.md)** — How to start new projects, validate business need, and get stakeholder alignment
- **[Project Planning](octoacme-project-planning.md)** — Planning and resource allocation, backlog prioritization, and dependency mapping
- **[Execution and Tracking](octoacme-execution-and-tracking.md)** — Day-to-day project execution, team rhythm, quality practices, and blocker escalation
- **[Release and Deployment](octoacme-release-and-deployment.md)** — Release management, deployment processes, and rollback playbooks

### Supporting Practices
- **[Risks and Communication](octoacme-risks-and-communication.md)** — Risk management and stakeholder communication strategies
- **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Post-project reviews and improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Team roles and responsibilities

## Quick Navigation Guide

**I need to...**

- **Start a new project** → [Project Initiation](octoacme-project-initiation.md)
- **Plan my project** → [Project Planning](octoacme-project-planning.md)
- **Understand roles and responsibilities** → [Roles and Personas](octoacme-roles-and-personas.md)
- **Execute and track progress** → [Execution and Tracking](octoacme-execution-and-tracking.md)
- **Manage risks and communicate status** → [Risks and Communication](octoacme-risks-and-communication.md)
- **Release to production** → [Release and Deployment](octoacme-release-and-deployment.md)
- **Run a retrospective** → [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Understand the OctoAcme approach** → [Project Management Overview](octoacme-project-management-overview.md)

## Using These Docs

- **For new team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the framework
- **For project leads**: Review [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md)
- **For developers and contributors**: See [Execution and Tracking](octoacme-execution-and-tracking.md) and [Roles and Personas](octoacme-roles-and-personas.md)
- **For ongoing reference**: Use the Quick Navigation Guide above to find the specific process you need
- **To request updates**: Use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

## Contributing

To suggest updates or additions to this documentation, please use the **[Add Content to Project Management Process Docs]** issue template in `.github/ISSUE_TEMPLATE/`.
