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
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Stakeholder Liaison coordinates release communications
- [ ] Risk Manager reviews post-deployment risks and updates Risk Register
- [ ] Change Control Coordinator closes related change requests

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

## Cross-Functional Coordination
- **Project Manager:** Coordinates release timeline and checklist execution
- **Stakeholder Liaison:** Communicates release status and impacts to stakeholders (use `octoacme-stakeholder-communication-template.md`)
- **Risk Manager:** Monitors deployment risks and readiness to rollback
- **Change Control Coordinator:** Ensures all approved changes are included and documented

*See `octoacme-roles-and-personas.md` for detailed role descriptions.*
