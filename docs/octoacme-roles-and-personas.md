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

## QA / Testing Lead

### Role Summary
QA/Testing leads define quality standards, design test strategies, and validate that deliverables meet acceptance criteria and quality gates before release.

### Responsibilities
- Design and maintain test plans (unit, integration, e2e, smoke tests)
- Establish quality acceptance criteria and Definition of Done standards
- Execute manual and automated testing
- Identify and track quality issues and regressions
- Participate in release readiness reviews
- Collaborate with developers on testability of features
- Validate that security scanning and quality gates pass pre-release

### Goals
- Ensure customer-facing features meet quality standards
- Catch defects early and reduce production incidents
- Enable fast, confident releases
- Maintain high product quality and customer trust

### Typical Communication
- Sprint planning and daily standups
- Test plan reviews and QA status updates
- Pre-release readiness sign-offs
- Quality metrics and regression reporting

### Interaction with Other Roles
- Works closely with **Developers** to review design for testability and define acceptance criteria
- Collaborates with **Release Managers** to coordinate pre-release validation
- Reports quality status to **Product Managers** and **Project Managers**

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and sponsors provide business context, funding, and executive alignment. They approve gates, resolve trade-offs, and ensure project outcomes align with organizational strategy.

### Responsibilities
- Approve project charter and success metrics
- Resolve scope/timeline/resource trade-offs
- Escalate blockers at the business level
- Review and provide feedback on milestone updates
- Authorize go/no-go decisions at release gates
- Ensure alignment with organizational priorities and strategy

### Goals
- Ensure project delivers measurable business value
- Maintain executive visibility and risk awareness
- Align work with organizational priorities
- Minimize business risk and maximize ROI

### Typical Communication
- Monthly stakeholder briefings and updates
- Decision gates and approval meetings
- Escalation and risk communications
- Milestone reviews and release announcements

### Interaction with Other Roles
- Works with **Project Managers** for status updates and escalations
- Provides direction to **Product Managers** on strategic priorities
- Approves resource decisions affecting **Developers** and other team members

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, ensure pre-release checklists are complete, manage rollback procedures, and drive communication during releases.

### Responsibilities
- Coordinate release schedule and deployment windows
- Verify pre-release checklist completion (testing, documentation, approvals)
- Manage release notes and stakeholder communication
- Execute or oversee deployment process
- Lead incident response and rollback procedures if needed
- Conduct post-release verification and validation
- Announce releases to stakeholders and support teams
- Document release retrospectives and lessons learned

### Goals
- Execute reliable, predictable releases
- Minimize release risk and downtime
- Maintain clear communication during releases
- Enable rapid, safe deployments

### Typical Communication
- Release planning meetings with delivery teams
- Pre-release readiness reviews and sign-offs
- Release day deployment calls and status updates
- Post-release retrospectives and incident reviews

### Interaction with Other Roles
- Coordinates with **QA/Testing Lead** to verify all quality gates are met
- Works with **Developers** on deployment procedures and rollback plans
- Reports to **Project Managers** and **Stakeholders** on release status
- Collaborates with **Security/Compliance Officer** on security readiness

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate team processes, remove impediments, and coach teams on continuous improvement and agile practices.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Help identify and remove blockers and impediments
- Coach team on agile practices and sprint cadence
- Maintain sprint board and burndown health
- Support retrospective action item tracking and follow-up
- Escalate systemic impediments that block team velocity
- Foster psychological safety and encourage open communication

### Goals
- Enable consistent team velocity and predictability
- Foster psychological safety and continuous improvement
- Reduce process friction and unplanned work
- Support team self-organization and empowerment

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- One-on-ones to understand and help remove blockers
- Coaching on agile practices and team dynamics

### Interaction with Other Roles
- Removes impediments affecting **Developers**, **QA/Testing**, and other team members
- Escalates systemic blockers to **Project Managers**
- Works with **Product Managers** on backlog clarity and sprint planning
- Supports **Release Managers** during release sprints

---

## Security / Compliance Officer

### Role Summary
Security and Compliance roles ensure solutions meet security standards, regulatory requirements, and organizational policies. They integrate security practices into the SDLC and respond to security incidents.

### Responsibilities
- Define security requirements and acceptance criteria
- Review designs and code for security risks
- Conduct or coordinate security scanning and assessments
- Support incident response for security events
- Ensure compliance with regulatory and organizational standards
- Advise on secure SDLC practices and risk mitigation
- Participate in risk registers and threat modeling
- Verify security gates before release

### Goals
- Minimize security and compliance risk
- Build customer trust through secure practices
- Enable fast, secure delivery
- Maintain regulatory compliance and reduce audit risk

### Typical Communication
- Design review participation (especially for data handling, authentication, APIs)
- Security incident escalations and response coordination
- Compliance audit updates and attestations
- Security training and guidance to development teams

### Interaction with Other Roles
- Collaborates with **Developers** on secure coding practices and code reviews
- Works with **QA/Testing Lead** to include security testing in test plans
- Participates in **Release Manager** pre-release security readiness reviews
- Advises **Project Managers** and **Stakeholders** on security risks
- Escalates critical security findings to leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning work or defining escalation paths, refer to the persona responsibilities and communication patterns to ensure clarity.
- Use the "Interaction with Other Roles" sections to understand cross-functional dependencies and communication needs.
