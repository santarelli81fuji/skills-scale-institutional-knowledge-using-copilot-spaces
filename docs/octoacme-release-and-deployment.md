# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- **QA Lead sign-off**: QA Lead confirms all in-scope stories passed acceptance testing (no open P1/P2 defects)
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Release Readiness Roles & Sign-offs

Each role below has a specific sign-off responsibility before a release proceeds:

| Role | Sign-off Responsibility |
|---|---|
| **QA Lead / Test Engineer** | Confirms acceptance criteria met; no blocking defects open |
| **Product Manager (PdM)** | Confirms the release delivers agreed scope and meets success metrics |
| **Project Manager (PM)** | Confirms schedule, communications, and stakeholder notifications are ready |
| **DevOps / Platform Engineer** | Confirms deployment pipeline is green, staging smoke tests pass, and rollback plan is ready |
| **Developer(s)** | Confirms no known regressions introduced; documentation updated |
| **Engineering Manager / Tech Lead** (if applicable) | Confirms technical readiness and approves any architectural changes |

> All sign-offs should be recorded on the release ticket or in the release notes document before production deployment begins. See the [RACI Template](octoacme-raci-template.md) for the full responsibility breakdown.

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

---

## Related docs
- [Roles & Personas](octoacme-roles-and-personas.md) — QA Lead and DevOps personas for release sign-off details
- [RACI Template](octoacme-raci-template.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
