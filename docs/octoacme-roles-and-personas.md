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

## Engineering Managers / Tech Leads

### Role Summary
Engineering Managers and Tech Leads translate product priorities into executable delivery plans, maintain engineering health, and help teams balance technical quality, velocity, and risk.

### Responsibilities
- Partner with Product Managers and Project Managers on feasibility, sequencing, and trade-offs
- Guide sprint planning, backlog refinement, and technical execution
- Own engineering health, delivery commitments, and support for team dependencies
- Mentor developers on architecture, standards, and technical decision-making
- Help identify blockers and escalate cross-team issues when needed

### Goals
- Improve predictability and delivery quality
- Maintain a sustainable engineering pace
- Reduce technical risk and rework

### Typical Communication
- Engineering planning meetings and sprint reviews
- Architecture and design discussions
- Cross-functional status updates with PM and stakeholder groups

### Interaction with Existing Roles
- Works with Product Managers on scope, sequencing, and trade-offs.
- Coordinates with Project Managers on timelines, team capacity, and dependencies.
- Supports Developers by clarifying technical direction, standards, and delivery priorities.

---

## Security / Compliance Leads

### Role Summary
Security and Compliance Leads protect the project from preventable risk by ensuring controls, standards, and operational safeguards are built into the work from the beginning.

### Responsibilities
- Review project plans for security, privacy, and compliance risks
- Define required controls, access patterns, and approval gates
- Partner with engineering and product teams on secure design and remediation plans
- Support incident triage and communication for security-related issues
- Validate that release and operational readiness requirements meet policy expectations

### Goals
- Reduce security and compliance exposure
- Ensure secure-by-design delivery practices
- Maintain confidence in approved production readiness

### Typical Communication
- Security reviews and design checkpoints
- Compliance risk assessments and governance reporting
- Escalations during release readiness or incident response

### Interaction with Existing Roles
- Provides risk guidance to Product and Project Managers when priorities affect compliance or security posture.
- Works with Engineering Managers and Developers to embed controls into architecture and delivery practices.
- Partners with Release Managers to verify risk mitigation before deployment.

---

## Release Managers / Deployment Leads

### Role Summary
Release Managers and Deployment Leads coordinate the operational readiness of releases so teams can ship changes with reduced risk and clear ownership.

### Responsibilities
- Plan and coordinate deployment windows, rollback strategies, and release readiness checks
- Validate that release criteria, smoke tests, and communications are complete
- Coordinate across engineering, support, and stakeholders for production launches
- Monitor post-deployment health and incident escalation paths
- Capture release learnings for future process improvements

### Goals
- Improve release reliability and predictability
- Reduce deployment-related disruption and uncertainty
- Maintain a clear operational handoff from delivery to production support

### Typical Communication
- Release readiness reviews
- Deployment planning and stakeholder notifications
- Post-release validation and incident coordination

### Interaction with Existing Roles
- Collaborates with Product and Project Managers to align launch timing with business readiness.
- Works closely with Engineering Managers and QA leads to confirm quality gates before deployment.
- Coordinates with Customer Success / Support partners for release communication and user-impact awareness.

---

## Customer Success / Support Partners

### Role Summary
Customer Success and Support partners represent user experience, adoption risk, and service readiness. They connect customer feedback to delivery decisions and help teams prepare for operational impact.

### Responsibilities
- Surface customer feedback, pain points, and support trends relevant to the project
- Help define launch readiness, enablement, and stakeholder communication needs
- Escalate priority issues and service risks to the appropriate project owners
- Align support plans, documentation, and training with new releases
- Contribute to success metrics and adoption-informed decisions

### Goals
- Improve customer satisfaction and adoption
- Reduce service disruption and support burden
- Ensure teams respond to real user needs and operational signals

### Typical Communication
- Customer feedback reviews and advisory meetings
- Support readiness and release communication cycles
- Escalation updates for high-impact issues

### Interaction with Existing Roles
- Provides Product Managers with customer insight and adoption feedback.
- Coordinates with Project Managers and Release Leads on stakeholder readiness and launch timing.
- Helps Engineering teams understand real-world usage patterns and failure points.

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads define how the team measures success, tracks impact, and uses evidence to guide decisions throughout the project.

### Responsibilities
- Define success metrics, instrumentation needs, and reporting expectations
- Measure operational outcomes such as adoption, quality, reliability, and usage trends
- Validate that teams collect the data needed to make informed decisions
- Partner with Product and stakeholders on dashboard and reporting needs
- Surface trends that may require course correction or a change in delivery priorities

### Goals
- Improve decision-making with objective evidence
- Ensure product outcomes are measurable and actionable
- Support learning loops across the project lifecycle

### Typical Communication
- KPI reviews and metric check-ins
- Business and product reporting updates
- Post-launch analysis and continuous improvement discussions

### Interaction with Existing Roles
- Helps Product Managers validate whether initiatives are achieving their stated outcomes.
- Collaborates with Project Managers and Engineering Leads on milestone reporting and health indicators.
- Provides support and insight to Customer Success teams and stakeholder updates.

---

## Architect / Solution Design Leads

### Role Summary
Architects and Solution Design Leads shape the technical direction, integration patterns, and long-term platform decisions needed to keep the project coherent and maintainable.

### Responsibilities
- Define system architecture, dependencies, and design standards
- Guide integration decisions and technology trade-offs across teams
- Identify cross-system risks, scalability constraints, and technical debt
- Ensure the solution aligns with platform standards and project objectives
- Support implementation planning for complex or cross-team work

### Goals
- Improve maintainability and technical consistency
- Reduce architecture-related rework and integration failure
- Enable long-term scalability and operational resilience

### Typical Communication
- Architecture reviews and technical design sessions
- Cross-team dependency planning and integration checkpoints
- Guidance during major design or refactor decisions

### Interaction with Existing Roles
- Works with Product Managers and Engineering Managers to assess feasibility and sequencing.
- Advises Developers and Tech Leads on implementation patterns and risk reduction.
- Collaborates with Security and Release leads to ensure architecture supports compliance and deployment safety.

---

## QA / Test Leads

### Role Summary
QA and Test Leads define quality expectations, validation strategies, and acceptance checks that ensure the solution meets customer and business needs.

### Responsibilities
- Define test strategy, quality gates, and acceptance criteria alignment
- Coordinate testing across unit, integration, end-to-end, and manual validation
- Identify regressions, defects, and quality risks before release
- Partner with Engineering and Product teams on readiness and defect triage
- Help establish a clear definition of done for project work

### Goals
- Reduce escape defects and release risk
- Improve confidence in product quality and user experience
- Align validation to business and technical requirements

### Typical Communication
- Test planning and execution reviews
- Defect triage and release readiness discussions
- Quality signoff with Product Managers and stakeholders

### Interaction with Existing Roles
- Works with Developers and Engineering Managers to validate backlog items against acceptance criteria.
- Collaborates with Release Managers to confirm deployment readiness and post-release quality checks.
- Supports Product Managers in confirming that outcomes are met before launch.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles complement the existing project management framework by clarifying ownership, decision rights, and collaboration patterns across delivery, operations, and stakeholder engagement.

