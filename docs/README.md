# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management knowledge base. This directory contains standardized processes and guidance for running projects across the organization.

## Quick Start

New to OctoAcme projects? Start with our [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, roles, and key artifacts.

## Project Lifecycle Phases

Our project management follows a structured lifecycle:

### 1. [Project Initiation](octoacme-project-initiation.md)
Validate business need, identify stakeholders, and make the go/no-go decision to proceed with planning.

**Key deliverables:**
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones
- Initial risk list
- Resource needs assessment

### 2. [Project Planning](octoacme-project-planning.md)
Break work into shippable increments, identify dependencies, and create actionable backlogs and release plans.

**Key deliverables:**
- Prioritized backlog with acceptance criteria
- Scope estimates (T-shirt sizing or story points)
- Definition of Done
- Release plan and milestone map
- Initial test plan / QA approach

### 3. [Execution & Tracking](octoacme-execution-and-tracking.md)
Manage day-to-day delivery, track progress, and maintain team rhythm through standups and syncs.

**Key activities:**
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Pull Request workflow with automated testing and code review
- Unit, integration, and end-to-end smoke tests
- Regular demos and stakeholder reviews

### 4. [Release & Deployment](octoacme-release-and-deployment.md)
Standardize how features are released to production with quality gates and rollback plans.

**Release types:**
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

**Pre-release requirements:**
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented

### 5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements for future projects.

**Retrospective structure:**
- What went well
- What could be improved
- Action items (owner, due date)
- Follow-up on previous action items

## Cross-Cutting Processes

### [Risk Management & Communication](octoacme-risks-and-communication.md)
Identify, track, and communicate risks and dependencies across the project lifecycle.

**Key components:**
- Risk Register (ID, Description, Impact, Probability, Owner, Mitigation)
- Risk Lifecycle: Identify → Assess → Mitigate → Monitor
- Stakeholder Communication plans
- Escalation Paths: Team-level → PM → Product Lead → Sponsor

### [Roles & Personas](octoacme-roles-and-personas.md)
Understand the key roles and responsibilities in OctoAcme projects.

**Core Roles:**
- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Using These Docs

- Keep process documentation updated as your team's approach evolves
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Refer to [Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to propose updates or enhancements to these processes
- Use the issue template [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest updates

## Quick Navigation

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach |
| [Project Initiation](octoacme-project-initiation.md) | Validate ideas and authorize work |
| [Project Planning](octoacme-project-planning.md) | Create actionable plans and backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day delivery |
| [Release & Deployment](octoacme-release-and-deployment.md) | Deploy features safely to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and improve processes |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify and manage risks |
| [Roles & Personas](octoacme-roles-and-personas.md) | Understand team roles and responsibilities |
