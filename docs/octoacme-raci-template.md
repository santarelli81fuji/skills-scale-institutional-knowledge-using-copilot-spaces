# OctoAcme — RACI Template

A **RACI matrix** clarifies who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for each major activity in a project. Fill this in during kickoff and update it as the project evolves.

## RACI Key

| Code | Meaning |
|---|---|
| **R** — Responsible | Does the work. There can be multiple R's for one activity. |
| **A** — Accountable | Owns the outcome; approves or signs off. There should be exactly **one** A per activity. |
| **C** — Consulted | Provides input before or during; two-way communication. |
| **I** — Informed | Kept up to date; one-way communication after the fact. |

---

## Project Details

| Field | Value |
|---|---|
| Project name | |
| Date | |
| Author | |
| Version | |

---

## RACI Matrix

Replace the column headers with the actual role names or individuals for your project. Add or remove rows as needed.

| Activity | PM | PdM | Dev | QA Lead | Scrum Master | UX Designer | DevOps | EM / Tech Lead | Stakeholder |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | | |
| Define problem statement & success metrics | C | A/R | C | I | I | C | I | C | C |
| Confirm required roles & ownership (RACI) | A/R | C | I | I | I | I | I | C | I |
| Stakeholder alignment / project sign-off | R | R | I | I | I | I | I | I | A |
| **Planning** | | | | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | R | C | I | C | I |
| Estimation (story points / T-shirt sizing) | I | C | A/R | C | R | C | C | C | I |
| Definition of Done (DoD) agreement | C | C | R | A/R | R | C | C | C | I |
| Test strategy / QA plan | I | C | C | A/R | I | I | C | C | I |
| Release plan & milestone map | A/R | C | C | C | C | I | C | C | I |
| **Execution** | | | | | | | | | |
| Feature implementation | I | I | A/R | I | I | C | I | C | I |
| UX design & prototype handoff | I | C | C | I | I | A/R | I | I | I |
| CI/CD pipeline maintenance | I | I | C | C | I | I | A/R | C | I |
| Code review & merge | I | I | A/R | C | I | I | I | C | I |
| QA testing & defect management | I | C | C | A/R | I | C | I | I | I |
| Risk register updates | A/R | C | C | C | C | I | C | C | I |
| **Release** | | | | | | | | | |
| Release readiness sign-off (QA) | I | I | I | A/R | I | I | I | I | I |
| Deployment to staging & smoke tests | C | I | C | R | I | I | A/R | C | I |
| Deployment to production | C | I | C | R | I | I | A/R | C | I |
| Post-deploy verification | I | I | C | R | I | I | A/R | C | I |
| Release notes & stakeholder announcement | A/R | C | C | I | I | I | I | C | I |
| **Close & Retrospective** | | | | | | | | | |
| Retrospective facilitation | I | I | I | I | A/R | I | I | I | I |
| Action item tracking | A/R | C | C | C | R | C | C | C | I |
| Lessons learned documentation | R | C | C | C | R | C | C | C | I |

> **Tip:** Each row should have exactly one **A**. If you find a row with no A or multiple A's, clarify ownership before the project begins.

---

## Customizing this template

1. Copy this file into your project's `docs/` folder.
2. Replace generic role names with the actual names of team members where helpful.
3. Add project-specific activities as additional rows.
4. Review and update the RACI at the start of each phase or when the team changes.

---

## Related docs
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Roles & Ownership Checklist](octoacme-roles-and-ownership-checklist.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
