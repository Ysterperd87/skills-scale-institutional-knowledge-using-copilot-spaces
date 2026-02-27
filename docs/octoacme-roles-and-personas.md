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

## Release Manager

### Role Summary
Release Managers coordinate releases, manage deployment planning, and ensure all pre-release requirements are met before changes reach production.

### Responsibilities
- Schedule deployment windows and coordinate release timelines
- Ensure release notes and rollback plans are prepared
- Drive the release checklist and verify all gate criteria are satisfied
- Communicate release status to stakeholders pre- and post-deployment
- Facilitate go/no-go decisions with Project Managers, Developers, and QA

### Goals
- Reduce deployment risk through consistent release practices
- Ensure releases are predictable, auditable, and reversible
- Maintain clear communication across all affected teams during release windows

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment window notifications and post-release announcements
- Coordination via release trackers, Slack/Teams channels, and runbooks

### Interactions with Existing Roles
- **Project Managers**: Aligns on release schedule and milestone readiness; escalates blockers
- **Product Managers**: Confirms scope and acceptance criteria are complete before release
- **Developers**: Coordinates code freeze, deployment steps, smoke test coverage, and rollback procedures
- **Support Lead**: Ensures support is briefed and ready before go-live; coordinates post-deploy incident response

---

## Support Lead

### Role Summary
Support Leads represent the support team in project workflows, validate release readiness from a customer-facing perspective, and manage user-impact communication and incident response post-launch.

### Responsibilities
- Review upcoming changes for support impact and escalation risk
- Ensure support documentation and runbooks are updated before release
- Manage post-deploy incident response alongside the Release Manager
- Gather, prioritize, and relay user feedback to the product and engineering teams
- Own the post-deployment support readiness checklist

### Goals
- Minimize customer impact from releases and incidents
- Close the feedback loop between end users and the development team
- Reduce mean time to resolution (MTTR) through proactive preparation

### Typical Communication
- Release readiness briefings with Release Manager and Project Manager
- Post-deploy incident bridges and status updates
- User feedback summaries shared with Product Managers

### Interactions with Existing Roles
- **Project Managers**: Flags support risks during planning; provides readiness sign-off before release
- **Product Managers**: Channels user feedback and feature adoption signals
- **Developers**: Collaborates on workarounds, fixes, and support tooling
- **Release Manager**: Co-leads incident response; reviews release checklists

---

## Technical Writer

### Role Summary
Technical Writers ensure that documentation—including process docs, release notes, and user guides—is created, maintained, and updated to reflect current features and workflows.

### Responsibilities
- Draft and maintain process docs, release notes, API references, and user guides
- Collaborate with Developers and Product Managers to capture feature intent and usage
- Review documentation for clarity, accuracy, and accessibility
- Advocate for documentation standards and templates across the team
- Update docs as part of the definition of done for new features

### Goals
- Ensure all changes are accompanied by clear, accurate documentation
- Reduce support burden by making self-service content comprehensive and findable
- Maintain a consistent voice and structure across all project documentation

### Typical Communication
- Documentation reviews embedded in PR and sprint workflows
- Periodic doc audits and gap analyses
- Collaboration via shared doc repositories and review comments

### Interactions with Existing Roles
- **Project Managers**: Receives timelines and milestone context to plan doc deliverables
- **Product Managers**: Captures requirements and user-facing language for guides and release notes
- **Developers**: Reviews technical accuracy of implementation docs and API references
- **Support Lead**: Aligns on support documentation needs and known issue tracking

---

## Security Champion

### Role Summary
Security Champions advocate for secure practices throughout the project lifecycle, conduct security reviews at critical milestones, and support incident escalation and remediation.

### Responsibilities
- Conduct security reviews at planning, pre-release, and post-incident milestones
- Identify and recommend mitigations for security risks in design and implementation
- Ensure compliance with applicable security standards and policies
- Support security incident escalation, triage, and remediation efforts
- Promote security awareness and best practices within the team

### Goals
- Reduce security risk through early identification and consistent review
- Ensure secure-by-default patterns are adopted across the codebase and processes
- Minimize impact of security incidents through preparedness and rapid response

### Typical Communication
- Security review sessions at sprint planning and release gates
- Risk register updates and security findings reports
- Incident escalation communications via established runbooks

### Interactions with Existing Roles
- **Project Managers**: Flags security risks in the risk register; advises on compliance milestones
- **Product Managers**: Reviews feature designs for security implications during discovery
- **Developers**: Provides code and architecture security reviews; recommends secure coding patterns
- **Release Manager**: Confirms security gates are met before deployment; co-leads security incident response
- **Support Lead**: Coordinates security incident response and customer communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

