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

## QA Lead / Test Engineer

### Role Summary
The QA Lead owns the overall quality strategy for a project. They design and execute test plans, define acceptance criteria with PdM and Developers, and act as the final quality gate before release.

### Responsibilities
- Define and maintain the test strategy (unit, integration, end-to-end, regression)
- Review acceptance criteria and translate them into test cases
- Execute and coordinate manual and automated testing
- Manage the "QA" column on the project board — triage, reproduce, and track defects
- Sign off on quality readiness before deployments
- Champion a "shift-left" testing mindset by involving QA early in the sprint

### Goals
- Prevent defects from reaching production
- Reduce rework by catching issues early in the development cycle
- Build confidence in each release through repeatable test coverage

### Typical Communication
- Sprint planning and backlog grooming (ensuring testability of stories)
- Daily standup to surface QA blockers
- Bug reports and test summary reports shared with PM and PdM
- Release sign-off confirmation to PM and DevOps

### How they interact with other roles
- **Developers**: Collaborates on testability, code coverage, and defect resolution
- **Product Managers (PdM)**: Reviews acceptance criteria to ensure completeness and measurability
- **Project Managers (PM)**: Reports QA status, defect counts, and risks to the PM; escalates blocking issues
- **DevOps**: Coordinates with DevOps to integrate automated tests into CI/CD pipelines
- **Scrum Master**: Works within sprint ceremonies facilitated by the Scrum Master

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches the team on agile practices. They shield the team from external distractions and continuously improve team process.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that hinder team progress
- Track and communicate team velocity and sprint health
- Coach the team on agile values, principles, and practices
- Protect team capacity from unplanned scope additions

### Goals
- Maintain a sustainable team cadence with high predictability
- Foster continuous improvement through actionable retrospective outcomes
- Reduce friction and waste in team processes

### Typical Communication
- Daily standups and agile ceremony facilitation
- Retrospective action item tracking and follow-up
- Team health and impediment log shared with PM

### How they interact with other roles
- **Project Managers (PM)**: Partners closely on scheduling, risk management, and stakeholder communication; the PM focuses on external delivery while the Scrum Master focuses on internal team health
- **Developers**: Coaches on engineering practices and removes day-to-day blockers
- **Product Managers (PdM)**: Coordinates backlog refinement sessions and helps maintain a healthy, ready-to-pull backlog
- **QA Lead**: Incorporates QA work and sign-off into sprint ceremonies and the Definition of Done

---

## UX Designer / Researcher

### Role Summary
The UX Designer / Researcher is responsible for the end-user experience. They conduct user research, create wireframes and prototypes, and validate that features are usable and valuable before and after implementation.

### Responsibilities
- Conduct user research (interviews, surveys, usability testing)
- Create wireframes, mockups, and interactive prototypes
- Define user journeys and interaction flows
- Contribute to and review acceptance criteria for user-facing features
- Perform usability reviews before stories are marked Done

### Goals
- Ensure features solve real user problems effectively
- Reduce user friction and support request volume
- Bring the user's voice into every planning and review session

### Typical Communication
- Design critiques and prototype reviews with Developers and PdM
- Research readouts to stakeholders and PdM
- Handoff specs (e.g., Figma links, annotated mockups) to Developers

### How they interact with other roles
- **Product Managers (PdM)**: Collaborates closely on problem definition, user research, and acceptance criteria; UX provides the "how it looks/feels" to PdM's "what to build"
- **Developers**: Provides detailed design specs and participates in implementation reviews to ensure fidelity
- **Project Managers (PM)**: Keeps PM informed of design dependencies and any timeline impacts
- **QA Lead**: Reviews designs together to ensure testability of UX requirements

---

## DevOps / Platform Engineer

### Role Summary
The DevOps / Platform Engineer owns the CI/CD pipelines, infrastructure, and operational tooling that enable the team to build, test, and release software reliably and safely.

### Responsibilities
- Build and maintain CI/CD pipelines (build, test, lint, security scan, deploy)
- Manage cloud or on-premise infrastructure and environments (dev, staging, production)
- Implement monitoring, alerting, and observability tooling
- Coordinate deployment windows and execute or automate production deployments
- Maintain runbooks, rollback procedures, and incident response playbooks
- Enforce infrastructure security and compliance standards

### Goals
- Maximize deployment frequency with minimal risk
- Ensure high availability and fast recovery from incidents
- Reduce manual toil through automation

### Typical Communication
- Deployment readiness confirmations to PM and QA Lead
- Infrastructure status and incident updates in shared channels
- Runbooks and deployment guides maintained in the project repo

### How they interact with other roles
- **Project Managers (PM)**: Coordinates release windows, communicates deployment risks and infrastructure needs
- **Developers**: Partners on CI/CD setup, environment access, and build tooling
- **QA Lead**: Integrates automated test suites into pipelines; coordinates staging environment availability
- **Product Managers (PdM)**: Provides operational metrics (uptime, latency, error rates) that inform PdM's success metrics

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager (EM) or Tech Lead provides technical leadership and people management for the engineering team. They own technical direction, developer growth, and team capacity planning.

### Responsibilities
- Define and communicate technical standards and architecture guidelines
- Lead technical design reviews and ADR (Architecture Decision Record) creation
- Manage engineering headcount, hiring, and performance
- Partner with PM and PdM to scope and de-risk technical work
- Identify and mitigate long-term technical debt and platform risks

### Goals
- Grow a high-performing, sustainable engineering team
- Ensure technical decisions are well-reasoned, documented, and understood by the team
- Balance delivery velocity with long-term code health

### Typical Communication
- Technical design docs and ADRs
- 1:1s with engineers and cross-functional leads
- Capacity and staffing updates to PM and program leadership

### How they interact with other roles
- **Project Managers (PM)**: Co-owns delivery planning; PM manages schedule and process while EM manages technical risk and team capacity
- **Product Managers (PdM)**: Aligns on technical feasibility and trade-offs during roadmap planning
- **Developers**: Provides technical mentorship, code review guidance, and career growth support
- **DevOps**: Collaborates on infrastructure strategy and platform roadmap
- **Scrum Master**: Partners on team health and process improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Related docs
- [Roles & Ownership Checklist](octoacme-roles-and-ownership-checklist.md) — use at project kickoff to confirm required roles
- [RACI Template](octoacme-raci-template.md) — assign ownership across roles for each project
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)

