# OctoAcme Project Management — Documentation Hub

> This README is the entry point for OctoAcme's project management process documentation.
> Use the links below to navigate to the relevant guide for each phase of delivery.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle with clear artifacts and decision gates. Work moves through five phases: **Initiation → Planning → Execution → Release → Close & Retrospective**. In initiation, the team validates the business need and success metrics using a short **Project One-pager**, identifies stakeholders, drafts a high-level timeline and initial risk list, and makes a go/no-go decision to proceed. Planning then translates the approved initiative into an actionable backlog with acceptance criteria, estimates, a Definition of Done, and a milestone/release map — ensuring work is broken into shippable increments and dependencies are identified early.

Roles and ownership are explicit to keep delivery predictable. A **Project Manager (PM)** coordinates schedules, delivery rituals, risk management, and stakeholder communications; a **Product Manager (PdM)** owns outcomes, prioritization, and measurement; **Developers** implement and test changes while supporting estimation and technical risk mitigation; **QA/Testing** validates acceptance criteria and quality; and **Stakeholders** provide inputs and approvals. These roles are used consistently across the process docs to clarify responsibilities and reduce ambiguity in handoffs and decision-making.

Execution is managed with a visible work system — typically a project board (e.g., GitHub Projects) using columns such as **Backlog, Ready, In Progress, In Review, QA, Done** — and a PR workflow that emphasizes small, reviewable changes. The team rhythm includes short **daily standups** to surface blockers and dependencies, plus a **weekly delivery sync** for progress updates and risk review. Risk management is handled via a simple **Risk Register** (impact, likelihood, owner, mitigation, status) and escalated through defined levels — from team triage to PM-led cross-team escalation, up to sponsor-level escalation for business-impacting issues. Stakeholder communication follows a regular cadence of weekly status updates, monthly briefings, and ad-hoc escalations as needed.

Quality assurance is built into both development and release practices. New logic is covered with **unit tests**, supplemented by **integration tests** where applicable, and **end-to-end smoke tests** for critical flows before release. Pull requests are expected to pass **CI checks** (including linting, tests, and security scanning) before review, and releases require completed acceptance criteria, release notes, and a rollback/mitigation plan. After each sprint, release, or incident, OctoAcme runs **retrospectives** to capture what worked, what didn't, and a small set of owned action items that feed back into the backlog — creating a continuous improvement loop.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle, and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | Validating the business need, aligning stakeholders, and getting to go/no-go |
| [Project Planning](octoacme-project-planning.md) | Building the backlog, estimating, defining DoD, and creating a release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day board management, PR workflow, quality gates, and metrics |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, communication templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release checklist, deployment steps, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement culture |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each role |
| [Roles & Ownership Checklist](octoacme-roles-and-ownership-checklist.md) | Kickoff checklist to confirm required roles and responsibilities |
| [RACI Template](octoacme-raci-template.md) | Ownership matrix template for assigning R/A/C/I across all project activities |
