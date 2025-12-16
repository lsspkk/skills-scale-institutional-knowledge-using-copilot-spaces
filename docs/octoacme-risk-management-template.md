# OctoAcme — Risk Management Template

## Purpose
Provide a structured approach and reusable templates for identifying, assessing, tracking, and mitigating project risks.

## Who uses this
- Risk Managers (primary owner)
- Project Managers (for project-level risk tracking)
- Team members (to identify and report risks)
- Stakeholders (to review risk status)

---

## Risk Register Template

Use this table format to maintain your project risk register. Keep it as a living document, updated weekly or as risks emerge.

| Risk ID | Description | Category | Impact | Likelihood | Risk Score | Owner | Mitigation Plan | Status | Last Updated |
|---------|-------------|----------|--------|------------|------------|-------|-----------------|--------|--------------|
| R-001 | Example: Key engineer unavailable during critical phase | Resource | High | Medium | 6 | PM Name | Cross-train backup; document critical knowledge | Active | 2025-01-15 |
| R-002 | Example: Third-party API changes breaking integration | Technical | Medium | Low | 2 | Dev Lead | Monitor API changelog; implement adapter pattern | Monitoring | 2025-01-10 |

---

## Risk Assessment Criteria

### Impact Levels
- **High:** Significant impact on project timeline (>2 weeks), budget (>20%), or scope (major features affected)
- **Medium:** Moderate impact on project timeline (1-2 weeks), budget (10-20%), or scope (minor features affected)
- **Low:** Minimal impact on project timeline (<1 week), budget (<10%), or scope (documentation or cosmetic issues)

### Likelihood Levels
- **High:** Likely to occur (>60% probability)
- **Medium:** May occur (30-60% probability)
- **Low:** Unlikely to occur (<30% probability)

### Risk Score Calculation
- High Impact + High Likelihood = 9 (Critical Priority)
- High Impact + Medium Likelihood = 6 (High Priority)
- High Impact + Low Likelihood = 3 (Medium Priority)
- Medium Impact + High Likelihood = 6 (High Priority)
- Medium Impact + Medium Likelihood = 4 (Medium Priority)
- Medium Impact + Low Likelihood = 2 (Low Priority)
- Low Impact + High Likelihood = 3 (Medium Priority)
- Low Impact + Medium Likelihood = 2 (Low Priority)
- Low Impact + Low Likelihood = 1 (Low Priority)

---

## Risk Categories

Use these categories to classify risks:

- **Technical:** Technology challenges, integration issues, technical debt
- **Resource:** People availability, skill gaps, budget constraints
- **Schedule:** Timeline pressures, dependencies, external deadlines
- **Scope:** Requirements changes, feature creep, unclear acceptance criteria
- **External:** Vendor issues, regulatory changes, market conditions
- **Security:** Vulnerabilities, compliance requirements, data protection
- **Quality:** Testing gaps, defect rates, performance concerns
- **Communication:** Stakeholder misalignment, information gaps, unclear decisions

---

## Risk Identification Worksheet

Use this during planning sessions, retrospectives, or ad-hoc as issues arise:

### Risk Description
What is the risk? Be specific and factual.

**Example:** "Integration with Payment Gateway API may fail if they deprecate v2 endpoints before our migration to v3 is complete."

### Risk Trigger
What event or condition would cause this risk to materialize?

**Example:** "Payment Gateway announces v2 API deprecation with short notice (<2 months)."

### Impact Analysis
What would be the consequences if this risk occurs?

**Example:** "Customers unable to complete purchases; revenue loss; emergency migration required."

### Current Probability
How likely is this risk to occur today?

**Example:** "Medium - They have deprecated APIs before with short notice."

### Mitigation Actions
What can be done to reduce probability or impact?

**Example:** 
- Monitor Payment Gateway announcements weekly
- Begin v3 API migration ahead of schedule
- Implement feature flag to switch between v2 and v3

### Contingency Plan
If mitigation fails, what is Plan B?

**Example:** "Roll back to v2 temporarily; negotiate extension with vendor; switch to alternate payment provider."

### Owner Assignment
Who is responsible for monitoring and executing mitigation?

**Example:** "Tech Lead (primary), Risk Manager (oversight)"

---

## Risk Review Meeting Template

### Frequency
Weekly or bi-weekly, depending on project phase and risk profile.

### Attendees
- Risk Manager (facilitator)
- Project Manager
- Technical Lead
- Product Manager (as needed)
- Other stakeholders for specific high-priority risks

### Agenda

#### 1. Review New Risks (10 minutes)
- Walk through newly identified risks since last meeting
- Assign initial impact, likelihood, and owner
- Decide if immediate action is needed

#### 2. Update Existing Risks (20 minutes)
- Review status of all active risks
- Update impact/likelihood if circumstances changed
- Check progress on mitigation actions
- Escalate risks that need sponsor attention

#### 3. Close Resolved Risks (5 minutes)
- Identify risks that are no longer applicable
- Document lessons learned
- Archive to historical risk log

#### 4. Action Items & Next Steps (5 minutes)
- Confirm owners and deadlines for mitigation actions
- Schedule follow-ups for high-priority risks
- Update risk register and distribute to stakeholders

---

## Risk Communication Template

### Weekly Risk Summary (for Project Status Reports)

**High-Priority Risks (Score ≥6):**
- [Risk ID]: [Brief Description] — [Status] — [Owner]

**New Risks This Week:**
- [Risk ID]: [Brief Description] — [Impact/Likelihood] — [Owner]

**Risks Closed/Resolved:**
- [Risk ID]: [Brief Description] — [How Resolved]

**Top 3 Risks Requiring Attention:**
1. [Risk ID]: [Description] — [Why it matters] — [Next steps]
2. [Risk ID]: [Description] — [Why it matters] — [Next steps]
3. [Risk ID]: [Description] — [Why it matters] — [Next steps]

---

## Risk Escalation Template

Use this format when escalating a critical risk to sponsors or senior leadership:

**Subject:** RISK ESCALATION: [Brief Risk Description]

**Risk ID:** [e.g., R-007]

**Risk Description:**
[Clear, concise description of the risk]

**Current Status:**
[Active | Monitoring | Escalating]

**Impact if Realized:**
[Describe consequences on timeline, budget, scope, quality, or customer experience]

**Probability:**
[High/Medium/Low with brief justification]

**Mitigation Attempted:**
[What has been tried so far]

**Why Escalation is Needed:**
[What decision, resource, or support is needed from leadership]

**Requested Action:**
[Specific ask: budget approval, resource reallocation, scope change, timeline adjustment, etc.]

**Decision Needed By:**
[Date and rationale for urgency]

**Prepared By:**
[Risk Manager Name]

**Date:**
[Date]

---

## Risk Retrospective Template

After project completion or major milestone, review risk management effectiveness:

### What Worked Well?
- Which risks were identified early and mitigated successfully?
- What risk management practices were most effective?

### What Could Be Improved?
- Were there any surprise risks that weren't identified?
- Were mitigation actions effective and timely?
- Was communication about risks clear and actionable?

### Lessons Learned
- What should we do differently on the next project?
- Are there patterns in risks that suggest process improvements?
- Should risk assessment criteria be adjusted?

### Action Items for Next Project
- [ ] Update risk categories or assessment criteria
- [ ] Add new risk identification prompts to planning template
- [ ] Improve risk communication cadence or format
- [ ] Provide risk management training to team

---

## Tools & Resources

### Recommended Tools
- **Risk Register:** Spreadsheet, GitHub Issues with labels, or project management tool
- **Risk Monitoring:** Automated alerts, dashboards, scheduled reminders
- **Communication:** Slack/Teams channels, email templates, status report sections

### Related Documents
- `octoacme-project-management-overview.md` — Overall PM approach
- `octoacme-risks-and-communication.md` — Risk lifecycle and communication guidance
- `octoacme-roles-and-personas.md` — Risk Manager role definition

### Best Practices
- Review risks at every major project gate (initiation, planning, mid-sprint, pre-release)
- Encourage team members to report risks without fear of blame
- Focus on mitigation, not just identification
- Keep risk register visible and accessible to all team members
- Archive closed risks for future reference and lessons learned
