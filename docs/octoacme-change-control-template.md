# OctoAcme — Change Control Template

## Purpose
Provide a structured process for requesting, evaluating, approving, and implementing changes to project scope, requirements, processes, or deliverables. Ensures all changes are properly vetted, documented, and communicated for accountability and auditability.

## Who uses this
- Change Control Coordinator (primary owner)
- Project Managers (to assess change impacts)
- Product Managers (to evaluate business value)
- Team members (to submit change requests)
- Stakeholders (to review and approve significant changes)

---

## Change Control Process Overview

### Process Flow
1. **Submit:** Team member or stakeholder submits change request
2. **Triage:** Change Control Coordinator reviews and categorizes
3. **Assess:** Impact analysis conducted by relevant parties
4. **Review:** Change Control Board evaluates the request
5. **Decide:** Approve, reject, or defer with clear rationale
6. **Implement:** If approved, change is executed per plan
7. **Verify:** Confirm change is implemented correctly
8. **Close:** Document outcome and lessons learned

### Change Categories

#### By Impact Level
- **Minor:** Low impact on timeline, budget, or scope; can be approved by PM
- **Moderate:** Medium impact; requires Change Control Board approval
- **Major:** High impact; requires sponsor/stakeholder approval

#### By Type
- **Scope Change:** Add, remove, or modify features/requirements
- **Schedule Change:** Adjust timeline or milestones
- **Resource Change:** Change team composition or budget
- **Process Change:** Modify workflows, tools, or standards
- **Technical Change:** Architecture, technology stack, or design decisions

---

## Change Request Form Template

### Change Request: CR-[Number]

**Submitted By:** [Name, Role]
**Date Submitted:** [MM/DD/YYYY]
**Project:** [Project Name]

---

### 1. Change Description
**What needs to change?**
[Clear, detailed description of the proposed change]

**Current State:**
[What exists today]

**Proposed State:**
[What it will be after the change]

---

### 2. Justification
**Why is this change needed?**
[Business reason, customer feedback, risk mitigation, etc.]

**What happens if we don't make this change?**
[Consequences of not implementing the change]

---

### 3. Impact Assessment

#### Timeline Impact
- [ ] No impact
- [ ] Minor delay (<1 week)
- [ ] Moderate delay (1-2 weeks)
- [ ] Major delay (>2 weeks)

**Details:** [Explanation of timeline impact]

#### Budget Impact
- [ ] No impact
- [ ] Minor cost increase (<10%)
- [ ] Moderate cost increase (10-20%)
- [ ] Major cost increase (>20%)

**Details:** [Explanation of budget impact, estimated cost]

#### Scope Impact
- [ ] Addition of features/requirements
- [ ] Removal of features/requirements
- [ ] Modification of existing features/requirements
- [ ] No scope change

**Details:** [What scope elements are affected]

#### Quality Impact
- [ ] Improves quality
- [ ] No impact on quality
- [ ] May reduce quality (explain mitigation)

**Details:** [How quality is affected]

#### Risk Impact
- [ ] Reduces existing risks
- [ ] Introduces new risks
- [ ] No impact on risks

**Details:** [New risks or risk mitigation provided by this change]

---

### 4. Affected Parties

**Roles/Teams Impacted:**
- [ ] Development team
- [ ] QA/Testing team
- [ ] Product Management
- [ ] Stakeholders
- [ ] End users
- [ ] Other: [Specify]

**Communication Required:**
[List who needs to be informed and when]

---

### 5. Implementation Plan

**Proposed Implementation Date:** [MM/DD/YYYY]

**Key Steps:**
1. [Step 1]
2. [Step 2]
3. [Step 3]

**Resources Needed:**
- [People, tools, budget, etc.]

**Testing/Validation Approach:**
[How will we verify the change is implemented correctly?]

**Rollback Plan:**
[What if we need to undo this change?]

---

### 6. Alternatives Considered

**Option 1:** [Alternative approach]
- **Pros:** [Benefits]
- **Cons:** [Drawbacks]

**Option 2:** [Another alternative]
- **Pros:** [Benefits]
- **Cons:** [Drawbacks]

**Why the proposed change is preferred:** [Rationale]

---

### 7. Approvals Required

- [ ] Project Manager
- [ ] Product Manager
- [ ] Technical Lead
- [ ] Change Control Board
- [ ] Executive Sponsor
- [ ] Other: [Specify]

---

## Change Request Triage Checklist

**Performed by:** Change Control Coordinator

- [ ] Change request is complete and clear
- [ ] Impact assessment is thorough
- [ ] Appropriate reviewers identified
- [ ] Change category assigned (Minor/Moderate/Major)
- [ ] Priority assigned (Critical/High/Medium/Low)
- [ ] Target review date set
- [ ] CR number assigned and logged
- [ ] Request routed to Change Control Board (if needed)

**Triage Notes:**
[Any clarifications, questions, or observations]

---

## Change Control Board (CCB) Meeting Template

### Meeting Details
**Date:** [MM/DD/YYYY]
**Time:** [HH:MM]
**Facilitator:** Change Control Coordinator
**Attendees:** [List of CCB members present]

---

### Agenda

#### 1. Review New Change Requests (30 minutes)

| CR ID | Submitted By | Description | Category | Impact | Recommendation |
|-------|--------------|-------------|----------|--------|----------------|
| CR-001 | [Name] | [Brief description] | [Minor/Moderate/Major] | [Timeline/Budget/Scope] | [Approve/Reject/Defer] |
| CR-002 | [Name] | [Brief description] | [Minor/Moderate/Major] | [Timeline/Budget/Scope] | [Approve/Reject/Defer] |

---

#### 2. Discuss High-Impact or Controversial Changes (20 minutes)

**CR-[Number]: [Change Title]**
- **Presenter:** [Requestor name]
- **Discussion points:**
  - [Key consideration 1]
  - [Key consideration 2]
  - [Key consideration 3]
- **Questions for the board:**
  - [Question 1]
  - [Question 2]

---

#### 3. Decision Summary (10 minutes)

| CR ID | Decision | Rationale | Conditions/Notes |
|-------|----------|-----------|------------------|
| CR-001 | Approved | [Why approved] | [Any conditions or modifications] |
| CR-002 | Rejected | [Why rejected] | [Alternative recommendation, if any] |
| CR-003 | Deferred | [Why deferred] | [What information is needed, revisit date] |

---

#### 4. Review Implementation Status of Previously Approved Changes (10 minutes)

| CR ID | Status | Completion Date | Issues/Learnings |
|-------|--------|-----------------|------------------|
| CR-XXX | Complete | [Date] | [Brief note] |
| CR-YYY | In Progress | [Expected date] | [Status update] |

---

#### 5. Action Items & Next Steps (5 minutes)

- [ ] [Action item 1] — Owner: [Name] — Due: [Date]
- [ ] [Action item 2] — Owner: [Name] — Due: [Date]
- [ ] Next CCB meeting scheduled for [Date]

---

## Change Approval Decision Template

### Change Request CR-[Number]: [Change Title]

**Decision:** ✅ Approved | ❌ Rejected | ⏸ Deferred

**Decided By:** [Change Control Board / Project Manager / Sponsor]
**Decision Date:** [MM/DD/YYYY]

---

### Rationale
[Clear explanation of why this decision was made]

### Conditions (for Approved changes)
- [Condition 1, if any]
- [Condition 2, if any]
- *(No conditions)* [if applicable]

### Alternative Recommendations (for Rejected changes)
[Suggested alternative approaches, if any]

### Information Needed (for Deferred changes)
- [What additional information is needed]
- [Who needs to provide it]
- [When it will be revisited]

### Implementation Authorization
**Authorized to proceed:** [Date]
**Implementation owner:** [Name, Role]
**Expected completion:** [Date]

---

## Change Implementation Tracking

| CR ID | Change Title | Approved Date | Implementation Owner | Start Date | Target Completion | Status | Actual Completion | Notes |
|-------|--------------|---------------|----------------------|------------|-------------------|--------|-------------------|-------|
| CR-001 | [Title] | [Date] | [Name] | [Date] | [Date] | In Progress | — | [Updates] |
| CR-002 | [Title] | [Date] | [Name] | [Date] | [Date] | Complete | [Date] | [Lessons] |

### Status Values
- **Not Started:** Approved but implementation hasn't begun
- **In Progress:** Actively being implemented
- **Complete:** Implemented and verified
- **On Hold:** Temporarily paused
- **Cancelled:** Approved but later cancelled

---

## Change Verification Checklist

**CR ID:** CR-[Number]
**Verified By:** [Name, Role]
**Verification Date:** [MM/DD/YYYY]

### Implementation Verification
- [ ] All implementation steps completed as planned
- [ ] Testing/validation performed successfully
- [ ] No unexpected issues or side effects
- [ ] Documentation updated to reflect the change
- [ ] Rollback plan tested (if applicable)

### Communication Verification
- [ ] All affected parties notified of the change
- [ ] Training or guidance provided (if needed)
- [ ] Feedback mechanism in place to monitor impact

### Acceptance Criteria Met
- [ ] [Specific criterion 1]
- [ ] [Specific criterion 2]
- [ ] [Specific criterion 3]

### Issues Encountered
[List any issues that occurred during implementation]

### Lessons Learned
[What went well? What could be improved for future changes?]

**Verified and Closed:** [Date]

---

## Change Log Template

Maintain a comprehensive log of all changes for audit and historical reference.

| CR ID | Date Submitted | Change Title | Requestor | Category | Impact | Decision | Decision Date | Implementation Complete | Closed Date |
|-------|----------------|--------------|-----------|----------|--------|----------|---------------|-------------------------|-------------|
| CR-001 | 2025-01-05 | Add user export feature | Jane Doe | Scope | Moderate | Approved | 2025-01-08 | 2025-01-20 | 2025-01-22 |
| CR-002 | 2025-01-10 | Extend deadline by 1 week | John Smith | Schedule | Minor | Approved | 2025-01-11 | N/A | 2025-01-12 |
| CR-003 | 2025-01-15 | Switch database vendor | Alex Lee | Technical | Major | Rejected | 2025-01-18 | N/A | 2025-01-18 |

---

## Change Control Metrics

Track these metrics to understand change patterns and improve the process:

### Monthly/Quarterly Metrics
- **Total Change Requests:** [Number]
- **Approved:** [Number and %]
- **Rejected:** [Number and %]
- **Deferred:** [Number and %]
- **Average Time to Decision:** [Days]
- **Average Time to Implementation:** [Days]

### Change Categories
- **By Type:** Scope (X%), Schedule (Y%), Resource (Z%), Technical (W%), Process (V%)
- **By Impact:** Minor (X%), Moderate (Y%), Major (Z%)

### Trend Analysis
- Are change requests increasing or decreasing?
- Which types of changes are most common?
- What is the average impact on timeline/budget?
- Are certain teams or areas generating more changes?

### Process Improvements
Based on metrics, identify:
- Bottlenecks in the change control process
- Areas where requirements are frequently changing
- Opportunities for better upfront planning
- Training needs for change management

---

## Emergency Change Process

For critical issues requiring immediate action (e.g., security vulnerabilities, production outages):

### Fast-Track Approval
1. **Immediate Notification:** Change Control Coordinator and Project Manager alerted
2. **Verbal Approval:** CCB chair or sponsor provides verbal approval by phone/video
3. **Implement:** Change implemented immediately
4. **Retrospective Documentation:** Within 24 hours, complete formal change request with:
   - Description of emergency
   - Actions taken
   - Rationale for fast-track
   - Post-implementation verification

### Criteria for Emergency Changes
- [ ] Active security threat
- [ ] Production system down affecting customers
- [ ] Data loss or corruption risk
- [ ] Regulatory compliance violation
- [ ] Safety or legal exposure

**Note:** Emergency process should be used sparingly. Retrospective review ensures proper documentation and identifies prevention opportunities.

---

## Related Documents
- `octoacme-roles-and-personas.md` — Change Control Coordinator role definition
- `octoacme-project-management-overview.md` — Overall PM approach
- `octoacme-project-planning.md` — Initial planning to minimize changes
- `octoacme-risks-and-communication.md` — Risk and communication practices

---

## Best Practices

### Proactive Change Management
- Encourage early identification of potential changes
- Build change buffer into project timelines
- Review change patterns in retrospectives

### Clear Decision Criteria
- Use consistent impact assessment rubrics
- Document decision rationale for future reference
- Be transparent about trade-offs

### Effective Communication
- Notify affected parties promptly
- Explain the "why" behind decisions
- Provide regular change log updates

### Continuous Improvement
- Review change control process effectiveness quarterly
- Solicit feedback from change requestors and CCB members
- Update templates based on lessons learned

### Balance Flexibility and Control
- Don't make change process so rigid that it stifles agility
- Don't be so loose that accountability is lost
- Adjust process rigor based on project complexity and risk
