# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing

### Test Types
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### QA Stage on the Project Board
The **QA** column on the project board represents stories that are code-complete and awaiting quality sign-off. The following process applies:

1. A Developer moves a story from **In Review** to **QA** once the PR is merged and deployed to the staging environment.
2. The **QA Lead / Test Engineer** picks up the story, executes test cases against the acceptance criteria, and records results.
3. If the story passes all acceptance criteria: QA Lead moves it to **Done** and records sign-off (e.g., a comment or label on the ticket).
4. If defects are found: QA Lead creates bug tickets linked to the story, moves the story back to **In Progress**, and notifies the owning Developer.
5. The QA Lead provides a **QA Summary** at the sprint review, covering: stories tested, defects found, defects resolved, and any deferred items.

For QA Lead responsibilities and communication patterns, see the [Roles & Personas doc](octoacme-roles-and-personas.md#qa-lead--test-engineer).

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] QA column and sign-off process communicated to the team
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

---

## Related docs
- [Roles & Personas](octoacme-roles-and-personas.md) — especially QA Lead and DevOps personas
- [RACI Template](octoacme-raci-template.md)
- [Project Planning](octoacme-project-planning.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
