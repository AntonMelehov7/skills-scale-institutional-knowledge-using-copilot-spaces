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

### Interaction with Other Roles
- Work closely with Product Managers to translate priorities into implementation
- Coordinate with Project Managers on scheduling, dependencies, and delivery risks
- Partner with QA/Testing to ensure defect triage and acceptance coverage
- Support Technical Leads/Architects on design trade-offs and engineering standards

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

### Interaction with Other Roles
- Align with Project Managers on scope, milestones, and stakeholder communication
- Partner with Developers and Technical Leads to confirm feasibility and prioritization
- Work with QA/Testing on acceptance criteria and release readiness
- Coordinate with Executive Sponsors and Business Stakeholders to confirm strategic fit

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

### Interaction with Other Roles
- Coordinate with Product Managers on milestones, risks, and communication cadence
- Work with Developers and Technical Leads to surface delivery dependencies and blockers
- Partner with QA/Testing and DevOps/SRE on release readiness and operational dependencies
- Escalate issues to Executive Sponsors when scope, resourcing, or strategic decisions require intervention

---

## QA Engineers / Test Leads

### Role Summary
QA Engineers and Test Leads ensure that features meet acceptance criteria, quality standards, and operational readiness before release. They validate whether the solution works for the intended user and business scenario.

### Responsibilities
- Define test strategy and quality gates for features and releases
- Validate acceptance criteria and regression coverage
- Coordinate defect triage, severity assessment, and issue prioritization
- Partner with Developers on testability and automation opportunities
- Support release-readiness decisions with evidence and risk-based testing

### Goals
- Reduce risk of shipping defects or failed workflows
- Improve release confidence and user trust
- Maintain consistent quality standards across milestones

### Typical Communication
- Test plans, defect reports, and release sign-off discussions
- Daily standups and QA triage sessions
- Review of acceptance criteria with Product Managers and Developers

### Interaction with Other Roles
- Work with Developers to review testability, edge cases, and bug fixes
- Partner with Product Managers to confirm acceptance criteria and release quality
- Coordinate with Project Managers on delivery risks, test timelines, and launch readiness
- Support DevOps/SRE in validating pre-release and post-deployment checks

---

## UX/UI Designers and Researchers

### Role Summary
UX/UI Designers and Researchers translate customer needs into usable, accessible, and measurable product experiences. They help teams design around real user behaviors and business goals.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Define user flows, interaction patterns, and accessibility needs
- Align product experience with customer value and usability goals
- Partner with Product Managers to validate solutions against user outcomes
- Help Developers and QA understand design intent and edge cases

### Goals
- Improve usability, clarity, and engagement
- Reduce rework caused by unclear requirements or poor design fit
- Ensure accessibility and inclusive product experiences

### Typical Communication
- Design reviews, research summaries, and usability findings
- Product discovery sessions and feature planning
- Collaboration with engineering and QA during implementation and validation

### Interaction with Other Roles
- Support Product Managers by shaping customer-informed requirements
- Work with Developers and Technical Leads on implementation feasibility and design constraints
- Partner with QA to validate that the final experience meets intended user outcomes
- Inform Project Managers on design-driven risks, dependencies, or stakeholder review needs

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide system design, technical quality, and engineering trade-offs. They help teams balance delivery speed, maintainability, and platform constraints.

### Responsibilities
- Define technical direction, system boundaries, and design standards
- Evaluate architecture decisions, scalability, and integration risks
- Guide implementation quality and technical debt management
- Support estimation, dependency planning, and technical sequencing
- Coordinate with Product and Project teams on feasibility and trade-offs

### Goals
- Maintain a robust, scalable, and maintainable architecture
- Reduce technical ambiguity and delivery risk
- Enable predictable implementation across dependencies

### Typical Communication
- Architecture reviews, technical design docs, and planning discussions
- Dependency and sequencing conversations with engineering and project leadership
- Risk and trade-off discussions with Product Managers and stakeholders

### Interaction with Other Roles
- Partner with Developers on engineering standards, design reviews, and implementation decisions
- Work with Project Managers on risk, sequencing, and cross-team dependencies
- Help Product Managers assess feasibility, trade-offs, and delivery implications
- Coordinate with DevOps/SRE and Security/Privacy Leads on infrastructure, reliability, and compliance concerns

---

## DevOps / Site Reliability Engineers (SRE)

### Role Summary
DevOps and SRE roles ensure that systems are deployable, observable, reliable, and resilient in production. They support smooth delivery and operational stability across the project lifecycle.

### Responsibilities
- Maintain deployment pipelines, environment configuration, and automation
- Support monitoring, alerting, observability, and incident response readiness
- Help teams reduce operational risk during release and post-deploy validation
- Define reliability and performance standards for critical systems
- Support recovery planning and rollback readiness

### Goals
- Improve release safety and operational stability
- Reduce downtime, incident impact, and mean time to recovery
- Enable continuous delivery with confidence

### Typical Communication
- Release readiness reviews, deployment checklists, and incident updates
- Operational dashboards and reliability reporting
- Coordination with engineering on production issues and rollback decisions

### Interaction with Other Roles
- Work with Developers to support deployability, monitoring, and environment health
- Partner with QA/Testing on smoke tests, release validation, and release gates
- Coordinate with Project Managers on deployment windows, operational dependencies, and risk communication
- Support Technical Leads and Security/Privacy Leads on infrastructure controls and resilience design

---

## Security / Privacy Leads

### Role Summary
Security and Privacy Leads protect the project from risk by helping the team identify, control, and validate security and compliance obligations.

### Responsibilities
- Review security and privacy requirements for features and systems
- Guide risk assessments, threat analysis, and mitigation plans
- Validate secure implementation patterns and access controls
- Support compliance checks and policy alignment
- Help triage and escalate critical security or privacy issues

### Goals
- Reduce security and privacy risk
- Ensure compliance with organizational policies and stakeholder expectations
- Build trust through secure, resilient delivery

### Typical Communication
- Security reviews, risk assessments, and compliance updates
- Escalation paths for incidents or high-risk findings
- Collaboration with engineering and project leadership during planning and release

### Interaction with Other Roles
- Work with Developers and Technical Leads on secure architecture and implementation
- Partner with Product Managers to align security requirements with business needs
- Support QA/Testing on validating controls, edge cases, and release readiness
- Coordinate with Project Managers and Executive Sponsors on material risk and escalation decisions

---

## Business / Domain Stakeholders

### Role Summary
Business and Domain Stakeholders provide subject-matter expertise, strategic context, and decision-making support. They help ensure the solution addresses real operational needs and business constraints.

### Responsibilities
- Provide domain knowledge, workflow context, and success criteria
- Review business impact, trade-offs, and priority decisions
- Validate whether a solution addresses the actual problem
- Supply timely decisions, approvals, and feedback when needed
- Help identify dependencies or constraints affecting delivery

### Goals
- Improve alignment between business needs and delivery
- Reduce ambiguity and rework through early validation
- Ensure the final solution is useful, relevant, and adoptable

### Typical Communication
- Planning workshops, stakeholder reviews, and milestone check-ins
- Decision-making on deliverables, trade-offs, or scope adjustments
- Feedback loops on usability, fit, and operational impact

### Interaction with Other Roles
- Partner with Product Managers to refine priorities and outcomes
- Support Project Managers with business context, approvals, and communication needs
- Work with Developers and QA on examples, edge cases, and acceptance validation
- Provide input to sponsors and leadership when priority or strategic alignment changes

---

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic sponsorship, priority alignment, and escalation support for high-impact initiatives. They help ensure the project remains aligned with organizational goals and resourcing constraints.

### Responsibilities
- Sponsor the initiative and confirm strategic importance
- Resolve major escalations, trade-offs, and decision bottlenecks
- Support cross-functional alignment and organizational prioritization
- Confirm continued business sponsorship through milestones and release
- Help unblock dependencies requiring leadership visibility

### Goals
- Ensure strategic alignment and executive visibility
- Support successful delivery of high-value outcomes
- Reduce barriers to execution caused by organizational friction

### Typical Communication
- Steering reviews, milestone check-ins, and status updates
- Escalation of high-risk issues or business-impacting blockers
- Strategic alignment conversations with Product Leads and PMs

### Interaction with Other Roles
- Partner with Product Managers on outcome prioritization and strategic fit
- Work with Project Managers on risk escalation, governance, and major dependency decisions
- Support Security/Privacy and DevOps/SRE when issues affect business continuity or compliance
- Provide decision support for scope trade-offs and strategic changes

---

## Role Selection and Adaptation

Not every project requires every role in equal measure. Teams may combine responsibilities, assign a single person to multiple roles, or add temporary specialists based on project size, risk, and complexity. The goal is to make ownership explicit, reduce ambiguity, and improve handoffs across planning, execution, release, and review.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
