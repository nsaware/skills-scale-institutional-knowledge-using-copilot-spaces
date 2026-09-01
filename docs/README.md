# OctoAcme Project Management Processes

**Last Updated:** 2026-09-01  
**Purpose:** Central entry point for all OctoAcme project management process documentation  
**Owner:** OctoAcme Program Management Office

---

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five distinct phases: **Initiation** (validating business need and stakeholder alignment through a lightweight One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and acceptance criteria), **Execution** (daily standups, weekly syncs, and continuous progress tracking on a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done), **Release** (deploying to production with pre-release checklists, smoke tests, and rollback plans), and **Close & Retrospective** (capturing learnings and converting them into actionable improvements). This iterative rhythm keeps stakeholders aligned and reduces the risk of missed requirements or surprises at release time.

The organization defines clear roles and accountabilities: **Project Managers** own schedules, risks, dependencies, and stakeholder communication; **Product Managers** define outcomes, prioritize backlogs, and measure success through data-driven metrics; **Developers** implement features, collaborate on design and testability, and help identify technical risks; and **QA/Testing teams** validate acceptance criteria and quality before release. Regular touchpoints—daily standups (15 min), weekly PM-PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates—ensure transparency and enable rapid escalation when blockers arise.

Quality and testing are embedded at every stage of delivery. The process requires unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI/CD pipelines. Pull requests must be small (≤400 lines where possible), include issue links and acceptance criteria, run automated tests and linting before review, and receive at least one approval before merging. A formal Definition of Done ensures consistency, and acceptance criteria are validated through manual QA when needed. Velocity, burndown, and key success metrics (errors, latency, usage) are tracked on dashboards to inform iterative improvements.

Risk and communication are managed proactively throughout the project lifecycle. A Risk Register captures each risk's description, impact, likelihood, owner, and mitigation plan, reviewed weekly during syncs. Blocker escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Stakeholder updates use a consistent template (progress, next steps, risks & blockers, decisions needed), and incidents trigger blameless retrospectives to extract organizational learning. This focus on transparency, psychological safety, and continuous improvement enables OctoAcme teams to deliver reliable, customer-focused outcomes at scale.

---

## Process Documentation

### Initiation & Planning

| Document | Description |
|---|---|
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate a project idea, align stakeholders, and create a Project One-pager |
| [Project Planning](octoacme-project-planning.md) | Breaking work into shippable increments, building backlogs, and defining acceptance criteria |

### Execution & Delivery

| Document | Description |
|---|---|
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Daily standups, sprint ceremonies, project board management, and progress tracking |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklists, deployment steps, smoke tests, and rollback plans |

### Governance & Improvement

| Document | Description |
|---|---|
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk Register, blocker escalation paths, and stakeholder communication templates |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint and project retrospective formats, action item tracking, and improvement cycles |

### Reference & Roles

| Document | Description |
|---|---|
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities for PM, PdM, Developers, QA, and Stakeholders |
| [Project Management Overview](octoacme-project-management-overview.md) | High-level summary of OctoAcme's end-to-end project management framework |

---

## How to Use These Docs

### New to OctoAcme?
1. Read the [Project Management Overview](octoacme-project-management-overview.md) for the big picture
2. Review [Roles and Personas](octoacme-roles-and-personas.md) to understand your responsibilities
3. Skim the [Execution & Tracking](octoacme-execution-and-tracking.md) guide to learn daily/weekly rhythms

### Starting a New Project?
1. Start with the [Project Initiation Guide](octoacme-project-initiation.md) to create your One-pager
2. Move to [Project Planning](octoacme-project-planning.md) to build your backlog and sprint plan
3. Set up your project board using the guidance in [Execution & Tracking](octoacme-execution-and-tracking.md)

### Managing Risks or Escalating Blockers?
1. Open [Risk Management & Communication](octoacme-risks-and-communication.md)
2. Log the risk or blocker in the Risk Register
3. Follow the three-level escalation path described in that document

### Setting Up a New Team/Project Board?
1. Review [Project Planning](octoacme-project-planning.md) for backlog and sprint setup
2. Follow the board column structure in [Execution & Tracking](octoacme-execution-and-tracking.md)
3. Reference [Roles and Personas](octoacme-roles-and-personas.md) to assign owners

### Preparing for Release?
1. Follow the pre-release checklist in the [Release & Deployment Guide](octoacme-release-and-deployment.md)
2. Confirm acceptance criteria are met per [Project Planning](octoacme-project-planning.md)
3. Schedule the post-release retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

---

## Quick Reference

### Key Artifacts

| Artifact | Created During | Owner | Purpose |
|---|---|---|---|
| Project One-pager | Initiation | PM / PdM | Aligns stakeholders on scope, goals, and success criteria |
| Product Backlog | Planning | PdM | Prioritized list of features and work items |
| Sprint Plan | Planning | PM | Committed scope for the current iteration |
| Risk Register | Planning → Execution | PM | Tracks risks, likelihood, impact, and mitigations |
| Project Board | Execution | PM | Real-time visibility into work status |
| Status Update | Execution | PM | Weekly/monthly stakeholder communication |
| Release Checklist | Release | PM / Dev Lead | Gates production deployment |
| Retrospective Notes | Close | PM / Scrum Master | Captures learnings and improvement actions |

### Communication Cadence

| Meeting | Frequency | Duration | Participants | Purpose |
|---|---|---|---|---|
| Daily Standup | Daily | 15 min | Dev team, PM | Blockers, progress, coordination |
| PM-PdM Sync | Weekly | 30 min | PM, PdM | Backlog, priorities, risks |
| Delivery Standup | Twice-weekly | 30 min | Dev team, PM, PdM | Sprint progress, impediments |
| Stakeholder Update | Monthly | Async or 30 min | PM, Stakeholders | Progress, decisions needed |

### Core Roles

| Role | Key Responsibilities |
|---|---|
| Project Manager (PM) | Schedule, risks, dependencies, stakeholder communication, escalation |
| Product Manager (PdM) | Outcomes, backlog prioritization, success metrics, customer voice |
| Developers | Implementation, technical design, PR reviews, risk identification |
| QA / Testing | Acceptance criteria validation, test coverage, release sign-off |
| Stakeholders | Business requirements, decisions, and executive sponsorship |

---

## Contributing

To propose updates or additions to any process document, open a new issue using the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/process-doc-update.md). Include the document name, the change requested, and the rationale. All updates should be reviewed by the Program Management Office before merging.
