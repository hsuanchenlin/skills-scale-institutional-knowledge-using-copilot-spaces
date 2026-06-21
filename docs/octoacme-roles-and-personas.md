# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## QA / Testing

### Role Summary
QA/Testing engineers validate that delivered work meets acceptance criteria, quality standards, and release readiness requirements. They act as the quality gate before features are promoted to production.

### Responsibilities
- Define and maintain test plans, test cases, and acceptance criteria coverage
- Execute functional, regression, and exploratory testing
- Report, triage, and track defects to resolution
- Verify release readiness across environments (staging, pre-production)
- Advocate for testability in design and implementation decisions

### Goals
- Prevent defects from reaching production
- Maintain high confidence in each release through repeatable test coverage
- Reduce the cost of quality by catching issues as early as possible

### Typical Communication
- Sprint reviews and QA sign-off reports
- Bug/defect tracking via project board or issue tracker
- Coordination with Developers on acceptance criteria and test environments
- Release readiness sign-off to Project Manager

### Interaction Points
- **Developers:** Clarify acceptance criteria; share defects and reproduction steps; align on test environment needs
- **Project Manager:** Provide release readiness status; escalate blocking defects
- **Product Manager:** Confirm acceptance criteria are complete and aligned to user intent
- **DevOps/SRE:** Coordinate test environment provisioning and CI test pipeline configuration

---

## Stakeholders

### Role Summary
Stakeholders are business or organizational leaders who have a vested interest in the project outcome. They provide strategic direction, approve key decisions, and review progress against business objectives.

### Responsibilities
- Approve project scope, goals, and key decisions at gate reviews
- Provide business context, constraints, and priority guidance
- Review and accept deliverables at major milestones
- Escalate or unblock organizational dependencies outside the delivery team

### Goals
- Ensure delivered outcomes align with business strategy
- Maintain visibility into project health, risks, and timelines
- Enable the team to move forward by providing timely decisions

### Typical Communication
- Monthly (or milestone-based) status updates from the Project Manager
- Decision requests and approvals via email or structured decision log
- Executive demos at major milestones

### Interaction Points
- **Project Manager:** Receive status updates; provide decisions and approvals
- **Product Manager:** Align on roadmap priorities and business value trade-offs
- **Engineering Manager/Tech Lead:** Review technical feasibility and resource implications of strategic decisions

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

### Interaction Points
- **Project Manager:** Surface blockers and dependencies during standups; provide progress updates
- **Product Manager:** Clarify requirements and acceptance criteria; flag scope or feasibility concerns
- **QA/Testing:** Collaborate on test coverage and defect resolution
- **Engineering Manager/Tech Lead:** Receive technical direction and code review guidance
- **DevOps/SRE:** Coordinate CI/CD pipeline changes and deployment support

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

### Interaction Points
- **Project Manager:** Align on delivery timeline, priorities, and scope changes
- **Developers:** Provide requirements, acceptance criteria, and user-context clarification
- **Stakeholders:** Present roadmap updates and gather strategic input
- **UX/UI Designer:** Define user flows, validate design decisions against product goals
- **Data Analyst:** Review success metrics and usage data to guide backlog priorities

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

### Interaction Points
- **Product Manager:** Align on scope changes, milestone trade-offs, and priority shifts
- **Engineering Manager/Tech Lead:** Coordinate capacity, technical dependencies, and escalation paths
- **QA/Testing:** Track release readiness; receive sign-off signals
- **Stakeholders:** Provide status reports, surface risks, and request decisions
- **All Roles:** Facilitate cross-functional handoffs using the [Handoff Checklist](./octoacme-handoff-checklist.md) and capture key decisions in the [Decision Log](./octoacme-decision-log-template.md)

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads bridge technical execution and team effectiveness. They guide architectural decisions, mentor developers, manage team capacity, and ensure engineering quality standards are maintained.

### Responsibilities
- Set and uphold engineering standards, architecture guidelines, and coding practices
- Mentor and support Developers through code reviews and technical guidance
- Manage team capacity, assignments, and skills growth
- Identify and escalate technical risks and cross-team dependencies
- Participate in project planning to provide accurate effort estimates and feasibility assessments

### Goals
- Maintain high engineering quality and system reliability
- Enable Developers to execute efficiently and grow their skills
- Ensure technical decisions align with project goals and long-term maintainability

### Typical Communication
- Regular 1:1s with Developers and syncs with Project Manager
- Architecture decision records (ADRs) for significant technical choices
- Escalations to Project Manager when capacity or technical constraints affect delivery

### Interaction Points
- **Project Manager:** Communicate capacity constraints, technical dependencies, and escalation needs
- **Developers:** Provide technical direction, code review, and mentorship
- **Product Manager:** Assess technical feasibility of proposed features and timelines
- **DevOps/SRE:** Collaborate on deployment pipelines, reliability standards, and infrastructure decisions
- **Security/Compliance:** Review security requirements and ensure engineering practices meet compliance obligations

---

## UX / UI Designer

### Role Summary
UX/UI Designers create user-centered designs that translate product requirements into clear, usable interfaces. They ensure the product is intuitive and meets user needs.

### Responsibilities
- Conduct user research, create personas, and map user journeys
- Design wireframes, mockups, and interactive prototypes
- Collaborate with Developers and Product Managers to refine designs for implementation
- Maintain design system consistency and accessibility standards
- Review implemented features against design specifications

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce user friction and improve task completion rates
- Ensure designs are technically feasible and delivered on schedule

### Typical Communication
- Design reviews and feedback sessions with Product Manager and Developers
- Prototype walkthroughs with stakeholders
- Design handoff assets and annotations for Developers

### Interaction Points
- **Product Manager:** Translate product requirements and user goals into design direction
- **Developers:** Provide design specifications and review implementation fidelity
- **QA/Testing:** Review UI against design specs during acceptance testing
- **Stakeholders:** Present design concepts and gather feedback at key milestones

---

## DevOps / SRE

### Role Summary
DevOps Engineers and Site Reliability Engineers (SREs) design, build, and operate the CI/CD pipelines, infrastructure, and reliability practices that support rapid, safe delivery.

### Responsibilities
- Build and maintain CI/CD pipelines, deployment automation, and infrastructure-as-code
- Monitor production systems and respond to incidents
- Define and track service-level objectives (SLOs) and error budgets
- Implement and enforce security and compliance controls in deployment pipelines
- Support Developers in debugging production issues and improving observability

### Goals
- Maximize deployment frequency while minimizing deployment risk
- Maintain high system availability and fast incident response
- Reduce manual toil through automation

### Typical Communication
- On-call rotation schedules and incident response channels
- Capacity and reliability reviews with Engineering Manager
- Post-incident review summaries shared with Project Manager and stakeholders

### Interaction Points
- **Engineering Manager/Tech Lead:** Align on infrastructure needs, capacity planning, and reliability targets
- **Developers:** Provide deployment tooling guidance; collaborate on observability and debugging
- **Security/Compliance:** Implement security controls and compliance requirements in pipelines
- **Project Manager:** Communicate deployment readiness and any pipeline blockers affecting the release schedule

---

## Security / Compliance

### Role Summary
Security and Compliance roles ensure that delivered software meets security requirements, regulatory obligations, and organizational risk standards. They act as advisors and reviewers throughout the lifecycle.

### Responsibilities
- Define and communicate security requirements and compliance constraints for projects
- Review architecture and implementation for security vulnerabilities
- Conduct or coordinate security assessments (threat modeling, penetration testing)
- Maintain and update security policies, incident response runbooks, and compliance documentation
- Respond to and lead remediation for security incidents

### Goals
- Minimize organizational security risk
- Ensure regulatory and policy compliance (e.g., GDPR, SOC 2, internal standards)
- Build a security-aware culture across the delivery team

### Typical Communication
- Security review feedback during design and implementation phases
- Compliance status updates to stakeholders and leadership
- Incident notifications and post-incident remediation plans

### Interaction Points
- **Engineering Manager/Tech Lead:** Embed security requirements into engineering standards and review architectural decisions
- **DevOps/SRE:** Enforce security controls in CI/CD pipelines and infrastructure
- **Project Manager:** Flag security risks and compliance blockers that affect project timelines
- **Stakeholders:** Report compliance status and risk posture at key milestones

---

## Customer Support / Success

### Role Summary
Customer Support and Customer Success roles bridge the product team and customers. They gather customer feedback, surface product issues, and help customers achieve their desired outcomes with the product.

### Responsibilities
- Handle customer inquiries, escalations, and defect reports
- Document and communicate recurring customer issues and feedback patterns to Product and Engineering
- Participate in beta programs, early-access releases, and user testing sessions
- Create and maintain customer-facing documentation, FAQs, and help content
- Coordinate with Project Manager for release communications to customers

### Goals
- Resolve customer issues quickly and accurately
- Reduce support volume through proactive documentation and product improvements
- Represent the customer's voice in product and delivery decisions

### Typical Communication
- Regular feedback summaries shared with Product Manager and Project Manager
- Release communication and changelog updates for customers
- Escalation requests to Engineering for critical production defects

### Interaction Points
- **Product Manager:** Provide customer feedback and feature requests to inform roadmap priorities
- **Project Manager:** Align on customer-facing release timelines and communication plans
- **Developers / QA:** Report and verify defects impacting customers
- **Stakeholders:** Present customer health metrics and satisfaction trends

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret product and operational data to support decision-making. They help the team measure outcomes and identify opportunities for improvement.

### Responsibilities
- Define and track key product and project metrics (KPIs, OKRs, success metrics)
- Build dashboards and reports for project health, user behavior, and business outcomes
- Analyze results from experiments, A/B tests, and releases to quantify impact
- Surface data-driven insights to Product Manager and Project Manager
- Maintain data quality and governance standards for project reporting

### Goals
- Enable data-driven decision-making across the team
- Provide timely, accurate metrics that reflect project and product health
- Help the team understand customer behavior and product outcomes

### Typical Communication
- Regular metrics reports and dashboard updates shared with Product Manager and PM
- Ad-hoc analysis for specific decisions or post-release reviews
- Participation in sprint reviews to provide quantitative release impact data

### Interaction Points
- **Product Manager:** Define success metrics; provide data to support roadmap and backlog decisions
- **Project Manager:** Supply project health metrics and burndown data for status reporting
- **Engineering Manager/Tech Lead:** Align on data collection instrumentation needs
- **Stakeholders:** Present outcome metrics and business impact at key reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

