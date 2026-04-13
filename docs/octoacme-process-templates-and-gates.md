# OctoAcme — Process Templates, RACI, and Decision Gates

Use this document as the standard repeatability kit across the lifecycle: initiation -> planning -> execution -> release -> retrospective.

## How to use
- Start each project with the **Project One-pager Template**.
- Use the **Lifecycle Decision Gates** to confirm entry/exit readiness for each stage.
- Use the **Weekly Status Update Template** during execution.
- Use the **Release Readiness Checklist** before production deployment.
- Use the **Incident / Rollback Quick Checklist** for high-severity release issues.

## Lightweight RACI by Lifecycle Stage

Legend: **R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed.

| Lifecycle Stage | Developers | Product Managers | Project Managers | UX Designer | Scrum Master / Agile Coach | DevOps / SRE | Data Analyst / Analytics | Security / Compliance | Technical Writer / Docs | Support / Customer Success |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Initiation (one-pager, goals, success metrics) | C | A | R | C | C | I | R | C | I | C |
| Planning (backlog, milestones, DoD, dependencies) | R | A | R | C | C | C | C | C | I | I |
| Execution & Tracking (delivery, status, blockers) | R | C | A | C | R | C | R | C | I | I |
| Release & Deployment (readiness, go/no-go, rollback) | R | A | R | I | C | R | C | C | R | C |
| Retrospective & Improvement (outcomes, actions) | C | A | R | C | R | C | R | C | I | C |

## Artifact Ownership and Definition of Done

| Artifact | Primary Owner | Definition of Done |
| --- | --- | --- |
| Project One-pager | Product Manager (A), Project Manager (R) | Problem, objective, success metrics, stakeholders, risks, timeline, and role coverage are documented and reviewed. |
| Backlog & milestones | Product Manager (A), Developers/PM (R) | Prioritized items include acceptance criteria, estimates, dependencies, and owners. |
| Weekly status update | Project Manager (A/R) | Progress, blockers, risks, decision asks, owner-by-owner actions, and metric snapshot are current. |
| Release readiness checklist | DevOps/SRE + Project Manager (R), Product Manager (A) | CI/security pass, rollback plan, comms plan, support readiness, and go/no-go approvals complete. |
| Retrospective action list | Scrum Master / Agile Coach + Project Manager (R), Product Manager (A) | Top actions have owners, due dates, and measurable success criteria tracked in backlog/issues. |

## Lifecycle Decision Gates

### Gate 1: Initiation -> Planning
- [ ] Project one-pager completed and shared
- [ ] Success metrics and analytics owner identified
- [ ] Sponsor/stakeholder alignment confirmed
- [ ] Core roles staffed (PM, PdM, Developer lead; plus needed specialist roles)
- [ ] Initial risks and dependencies captured
- **Gate owner:** Product Manager (A), Project Manager (R)

### Gate 2: Planning -> Execution
- [ ] Prioritized backlog with acceptance criteria approved
- [ ] Definition of Done documented (code, QA, docs, security, analytics)
- [ ] Timeline/milestones and dependency plan agreed
- [ ] Communication cadence and escalation path documented
- [ ] Dashboards/instrumentation requirements defined
- **Gate owner:** Project Manager (A), Product Manager (R)

### Gate 3: Execution -> Release
- [ ] Scope for release candidate confirmed
- [ ] Quality checks complete (test pass + manual validation as needed)
- [ ] Security/compliance checks complete for in-scope changes
- [ ] Release notes, support brief, and stakeholder comms drafted
- [ ] Rollback and incident ownership confirmed
- **Gate owner:** Product Manager (A), DevOps/SRE + Project Manager (R)

### Gate 4: Release -> Retrospective
- [ ] Deployment complete and post-deploy verification passed
- [ ] Customer/support impact reviewed
- [ ] KPI/metric snapshot completed (adoption, quality, reliability)
- [ ] Incidents or follow-ups logged with owners
- [ ] Retrospective scheduled with required participants
- **Gate owner:** Project Manager (A), Data Analyst + Scrum Master (R)

### Gate 5: Retrospective -> Next Cycle
- [ ] Top 2-3 improvements selected and prioritized
- [ ] Owners, due dates, and success measures assigned
- [ ] Process/document updates captured in `docs/`
- [ ] Carry-over risks and dependencies reviewed for next planning cycle
- **Gate owner:** Product Manager (A), Project Manager (R)

## Project One-pager Template
- Project name:
- Problem statement:
- Objective / Goal (SMART):
- Success metrics (including baseline + target):
- Primary stakeholders:
- Suggested timeline / milestones:
- Risks & dependencies:
- Team roles and owners:
- Decision needed to enter planning:

## Weekly Status Update Template
- Reporting period:
- Overall status (Green / Yellow / Red):
- Progress this week:
- Planned next steps:
- Risks & blockers (owner + mitigation + escalation level):
- Decisions needed (by whom, by when):
- Metrics snapshot (delivery + product outcomes):
- Changes to scope/timeline:

## Release Readiness Checklist
- [ ] All acceptance criteria and DoD checks complete
- [ ] CI, test suite, and security/compliance checks pass
- [ ] Dashboards/alerts validated for release scope
- [ ] Release notes and customer-facing comms reviewed
- [ ] Support handoff complete (known issues, escalation contacts)
- [ ] Rollback plan validated and owner-on-call confirmed
- [ ] Final go/no-go decision recorded

## Incident / Rollback Quick Checklist
- [ ] Confirm incident severity and customer impact
- [ ] Assign incident commander and communications owner
- [ ] Notify key stakeholders (PM, PdM, Support, Security as needed)
- [ ] Trigger rollback to last known-good state if needed
- [ ] Verify service health and customer-facing recovery
- [ ] Publish status update and next update time
- [ ] Capture root cause follow-up and retrospective owner
