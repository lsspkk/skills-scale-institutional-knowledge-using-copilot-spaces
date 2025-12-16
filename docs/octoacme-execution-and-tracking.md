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
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

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
- [ ] Regular demos scheduled with stakeholders
- [ ] Risk register updated weekly by Risk Manager
- [ ] Stakeholder updates sent per communication plan
- [ ] Change requests processed through Change Control Coordinator
- [ ] Team onboarding completed using `octoacme-onboarding-checklist.md`

## Execution Role Clarity
- **Project Manager:** Coordinates daily execution, removes blockers, tracks progress
- **Risk Manager:** Monitors risks, updates Risk Register, escalates critical issues
- **Stakeholder Liaison:** Sends regular updates, gathers feedback, manages stakeholder expectations
- **Change Control Coordinator:** Reviews and processes change requests, maintains change log
- **Developers/QA:** Execute backlog items, collaborate on reviews, raise blockers early

*See `octoacme-roles-and-personas.md` for complete role definitions and collaboration points.*
