# OctoAcme Roles and Personas

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

## Customer Success / User Adoption Lead

### Role Summary
Customer Success / User Adoption Leads own post-release outcomes and feature adoption in production and clinical environments. They ensure users are prepared, trained, and supported to realize business and clinical value.

### Responsibilities
- Partner with Product Managers to define and track adoption and success metrics
- Coordinate user training, onboarding, and change communication plans
- Gather feedback from end users in production environments
- Escalate usability issues, adoption blockers, and operational surprises
- Support user acceptance testing (UAT) coordination and sign-off
- Own post-release support readiness (support team training, runbooks, FAQ)

### Goals
- Maximize adoption and utilization of new features
- Reduce support tickets and escalations caused by confusion or lack of readiness
- Improve customer satisfaction and clinical outcomes enabled by the product
- Capture early signals of process misalignment or unexpected operational impact

### Typical Communication
- UAT planning and release readiness sessions
- User training and onboarding coordination
- Adoption metric reviews and post-release feedback reports
- Support readiness and escalation handoffs

### Interactions with Existing Roles
- Works with **Product Managers** to validate feature value realization and gather user feedback
- Works with **Project Managers** to coordinate UAT timing and user readiness sign-off before release
- Works with **Clinical SMEs** to ensure training and communication align with workflow realities
- Works with **QA / Testing Leads** to coordinate user acceptance testing
- Works with **Developers** to explain user-reported issues and adoption blockers

---

## Training & Change Management Specialist

### Role Summary
Training & Change Management Specialists design and deliver instructional and organizational change support needed for teams to adopt new features, processes, or tools in live care environments.

### Responsibilities
- Develop training materials, job aids, and e-learning content based on feature scope
- Conduct train-the-trainer sessions and support user training delivery
- Design change communication plans and manage rollout messaging
- Identify and address resistance or change management risks
- Create and maintain training documentation and reference materials
- Coordinate with support teams to prepare FAQ and troubleshooting guides
- Measure training effectiveness and learner competency

### Goals
- Ensure all affected users understand how to use new features safely and effectively
- Reduce learning curve and time-to-proficiency for end users
- Minimize disruption during feature rollout to live care environments
- Improve retention and correct usage of features over time

### Typical Communication
- Training schedule alignment with delivery teams
- Feature walkthroughs and scenario reviews with Clinical SMEs
- Change messaging and rollout updates to affected user groups
- Post-training competency and feedback reviews

### Interactions with Existing Roles
- Works with **Clinical SMEs** to create clinically accurate training scenarios
- Works with **Product Managers** to clarify feature intent, workflows, and success metrics
- Works with **Project Managers** to align training schedules with release timelines and resource availability
- Works with **Customer Success / User Adoption Leads** to coordinate delivery and monitor adoption
- Works with **QA / Testing Leads** to identify common user errors and refine training content

---

## Compliance & Audit Lead

### Role Summary
Compliance & Audit Leads ensure delivery practices maintain audit trails, records retention, and compliance documentation required by healthcare regulations (HIPAA, 21 CFR Part 11, ISO 27001). They provide governance oversight and escalate gaps before they become violations.

### Responsibilities
- Define audit logging requirements and validate implementation
- Review feature scope for compliance and regulatory impact
- Ensure change management and traceability documentation is maintained throughout delivery
- Coordinate compliance testing and sign-off before release
- Maintain records of design decisions, security reviews, and test results for audit purposes
- Identify and escalate compliance gaps or ambiguities
- Support regulatory inspections or audits with evidence of compliant development practices

### Goals
- Maintain continuous compliance with healthcare regulations and industry standards
- Reduce audit findings and remediation effort
- Ensure all changes are traceable and justified
- Support confident audits and regulatory inspections

### Typical Communication
- Compliance impact reviews during planning and design
- Audit logging and traceability checkpoints with engineering teams
- Release sign-off coordination with project and security stakeholders
- Audit evidence preparation for inspections and formal reviews

### Interactions with Existing Roles
- Works with **Security & Compliance Officers** to align regulatory requirements and risk mitigation
- Works with **Developers** to validate audit logging implementation and change traceability
- Works with **Project Managers** to track compliance activities and release sign-off dependencies
- Works with **Technical Architects** to ensure design decisions are documented and justified
- Works with **DevOps / Release Engineers** to ensure deployments include compliance verification steps

---

## Clinical Operations Liaison

### Role Summary
Clinical Operations Liaisons represent the operational and workflow perspective of clinical care environments. They bridge product delivery with day-to-day clinical operations and identify risks to workflow continuity.

### Responsibilities
- Assess how features impact daily clinical workflows and operational efficiency
- Identify resource needs (staffing, training time, equipment, process changes)
- Flag workflow dependencies and sequencing risks that could disrupt care delivery
- Coordinate with operational leadership on readiness and rollout planning
- Validate that features integrate safely into existing care processes
- Support go-live planning and operational readiness reviews
- Gather post-release operational feedback and escalate surprises

### Goals
- Ensure features enhance (not disrupt) clinical workflow and care quality
- Reduce unplanned operational impact or care delivery disruptions
- Enable smooth integration of new features into live care environments
- Improve clinical team confidence and adoption of new capabilities

### Typical Communication
- Workflow impact assessments during planning and release preparation
- Operational readiness reviews with delivery and clinical leaders
- Go-live support coordination and issue escalation updates
- Post-release operational feedback and lessons-learned sessions

### Interactions with Existing Roles
- Works with **Clinical SMEs** to validate workflow impact and identify usability or safety risks
- Works with **Product Managers** to confirm feature scope alignment with operational needs
- Works with **Project Managers** to identify operational dependencies, sequencing risks, and readiness requirements
- Works with **Customer Success / User Adoption Leads** to coordinate readiness and rollout support
- Works with **Training & Change Management Specialists** to ensure training reflects operational realities

---

## How these added personas close documented governance gaps
- **Stakeholder accountability:** Customer Success / User Adoption Leads own value realization and adoption outcomes after release.
- **Operational continuity:** Clinical Operations Liaisons identify workflow disruption risk and readiness dependencies before go-live.
- **Compliance and audit readiness:** Compliance & Audit Leads centralize traceability, documentation, and regulatory sign-off responsibilities.
- **Clinical workflow integration:** Training & Change Management Specialists and Clinical Operations Liaisons align learning and rollout plans to real clinical operations.
- **Cross-functional delivery clarity:** Explicit role interactions reduce ambiguity in handoffs across product, project, clinical, and engineering teams.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
