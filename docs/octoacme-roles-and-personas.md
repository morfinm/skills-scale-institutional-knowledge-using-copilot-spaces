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
Release Managers coordinate release readiness, deployment sequencing, and communication so teams can ship changes with minimal disruption and clear operational ownership.

### Responsibilities
- Define release windows, deployment plans, and rollback readiness
- Coordinate pre-release validation, smoke tests, and stakeholder notifications
- Track release blockers, dependencies, and launch risks
- Maintain release notes and post-deployment follow-up
- Partner with engineering, PM, and support teams to align on launch timing

### Goals
- Reduce release risk and production surprises
- Improve predictability of deployments and operational readiness
- Keep stakeholders informed before, during, and after releases

### Typical Communication
- Release planning and deployment check-ins
- Status updates during launch windows
- Post-release summaries and issue follow-up

### Interaction with Existing Roles
- Works closely with Project Managers to align release timing with milestones and dependencies
- Collaborates with Developers and Technical Leads to confirm readiness and rollback plans
- Supports Product Managers by communicating changes, customer impact, and release goals
- Coordinates with Operations and Support teams to ensure post-deployment monitoring is ready

---

## Technical Lead / Architecture Owner

### Role Summary
Technical Leads guide technical direction, system design, and implementation standards so product and delivery goals can be achieved without unnecessary risk or rework.

### Responsibilities
- Review technical architecture, trade-offs, and integration decisions
- Define standards for maintainability, scalability, and operational health
- Support estimation, implementation planning, and technical dependency management
- Help resolve design conflicts and unblock delivery teams
- Partner with Developers and Product Managers on feasibility and sequencing

### Goals
- Align engineering decisions with long-term product goals
- Reduce technical debt and avoid avoidable delivery risk
- Improve delivery confidence and implementation quality

### Typical Communication
- Architecture reviews and technical design discussions
- Planning sessions with PM and engineering leads
- Escalation points for design blockers or cross-team dependencies

### Interaction with Existing Roles
- Works with Developers to guide design decisions and implementation quality
- Provides Product Managers with feasibility and sequencing input for roadmap trade-offs
- Supports Project Managers by clarifying technical dependencies, risks, and delivery constraints
- Coordinates with Security and Compliance partners on architecture-level controls and risk treatment

---

## Quality / QA Lead

### Role Summary
Quality / QA Leads define validation strategies and quality gates to help ensure products meet acceptance criteria, customer expectations, and operational standards.

### Responsibilities
- Define test strategy, quality gates, and acceptance validation approach
- Review user stories and requirements for testability and completeness
- Coordinate test planning, signoff, and defect triage
- Validate release readiness and regression risk
- Partner with development and product teams to improve quality outcomes

### Goals
- Deliver reliable, user-acceptable features
- Catch defects earlier and reduce rework
- Establish consistent quality standards across delivery teams

### Typical Communication
- QA planning and review meetings
- Defect triage and release signoff discussions
- Acceptance criteria validation with Product and PM stakeholders

### Interaction with Existing Roles
- Works with Developers to align on testability, coverage, and defect resolution
- Partners with Product Managers to validate acceptance criteria and customer-facing quality expectations
- Supports Project Managers by surfacing risks that could affect schedule, scope, or go-live quality
- Coordinates with Release Managers on launch readiness and rollback triggers

---

## Customer Success / Stakeholder Liaison

### Role Summary
Customer Success and Stakeholder Liaisons translate customer feedback, stakeholder needs, and operational realities into actionable project priorities and communication plans.

### Responsibilities
- Gather and synthesize customer feedback, adoption signals, and support trends
- Communicate stakeholder concerns, expectations, and roadmap implications
- Help prioritize user experience and operational readiness needs
- Support customer-facing messaging and issue escalation
- Provide input during planning and retrospective reviews

### Goals
- Improve customer outcomes and stakeholder confidence
- Ensure product decisions reflect real-world needs and feedback
- Build stronger alignment between delivery teams and customer-facing teams

### Typical Communication
- Stakeholder check-ins and customer feedback reviews
- Weekly or milestone updates with PM and Product teams
- Support and escalation discussions with operational teams

### Interaction with Existing Roles
- Feeds Product Managers with customer insights and evidence to inform prioritization
- Coordinates with Project Managers on stakeholder reporting and milestone updates
- Works with Developers on usability, quality issues, and support impact
- Supports Release Managers by helping frame rollout communications and expected customer impact

---

## Security / Compliance Partner

### Role Summary
Security and Compliance Partners help teams identify and manage security, privacy, and regulatory risks throughout planning, implementation, and release.

### Responsibilities
- Review project designs and implementations for security and compliance risks
- Define required controls, review checkpoints, and risk treatment actions
- Support secure coding, data handling, and incident readiness practices
- Partner with delivery teams on access, privacy, and operational risk decisions
- Help escalate and track remediation for high-risk issues

### Goals
- Reduce security and compliance exposure
- Enable delivery without unnecessary risk or policy violations
- Build trust in project decisions and operational practices

### Typical Communication
- Security reviews and compliance checkpoints
- Risk and remediation discussions during planning and release readiness
- Incident escalation and coordination for urgent issues

### Interaction with Existing Roles
- Advises Technical Leads and Developers on secure architecture and implementation patterns
- Works with Project Managers on risk tracking and mitigation planning
- Provides Product Managers input on customer and business risk trade-offs
- Supports Release Managers by ensuring launch readiness includes security and legal review as needed

---

## Operations / Enablement Owner

### Role Summary
Operations and Enablement Owners ensure teams, systems, and support processes are ready for delivery, adoption, and ongoing stewardship after launch.

### Responsibilities
- Prepare support readiness, runbooks, and handoff processes for new features or services
- Coordinate operational monitoring, alerts, onboarding, and training needs
- Support post-deployment verification and issue escalation
- Help teams transition new work into steady-state operations
- Identify operational dependencies and service readiness gaps

### Goals
- Improve service reliability and adoption readiness
- Reduce operational friction during release and post-launch support
- Create clear ownership for ongoing service health

### Typical Communication
- Operational readiness reviews and launch check-ins
- Support handoff and on-call readiness discussions
- Post-release retrospectives and service health reviews

### Interaction with Existing Roles
- Partners with Release Managers on deployment readiness and post-launch monitoring
- Works with Developers and Technical Leads to validate supportability and observability
- Supports Product Managers by surfacing adoption and customer operational concerns
- Helps Project Managers track dependencies that affect launch success or steady-state operations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For larger projects, multiple personas may collaborate at the same time to provide clearer accountability across delivery, quality, customer impact, and operational readiness.

