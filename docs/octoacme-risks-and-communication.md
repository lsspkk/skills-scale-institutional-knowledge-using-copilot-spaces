# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies across cross-functional teams.

## Key Roles
- **Risk Manager:** Primary owner of risk identification, assessment, and mitigation (see `octoacme-roles-and-personas.md`)
- **Project Manager:** Coordinates risk management activities with overall project execution
- **Stakeholder Liaison:** Ensures risks are appropriately communicated to stakeholders
- **Team Members:** Identify and report risks proactively

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- Risk Manager can escalate critical risks directly to sponsor with PM awareness

## Related Templates & Resources
- **Risk Management Template:** See `octoacme-risk-management-template.md` for detailed risk register formats, assessment criteria, and tracking tools
- **Stakeholder Communication:** See `octoacme-stakeholder-communication-template.md` for templates on communicating risks and status to stakeholders
- **Roles & Personas:** See `octoacme-roles-and-personas.md` for detailed descriptions of Risk Manager and Stakeholder Liaison roles

## Process Integration
- **Risk identification** should occur during project initiation (see `octoacme-project-initiation.md`)
- **Risk tracking** continues through execution (see `octoacme-execution-and-tracking.md`)
- **Risk reviews** are part of regular retrospectives (see `octoacme-retrospective-and-continuous-improvement.md`)
