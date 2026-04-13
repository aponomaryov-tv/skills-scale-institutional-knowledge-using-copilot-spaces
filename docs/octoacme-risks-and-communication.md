# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

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
- Assign communication and escalation owners using the [lifecycle RACI matrix](./octoacme-process-templates-and-gates.md#lightweight-raci-by-lifecycle-stage)

## Communication Templates
- Use the [Weekly Status Update Template](./octoacme-process-templates-and-gates.md#weekly-status-update-template) to keep updates consistent and decision-ready.

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled
- If rollback is needed, use the [Incident / Rollback Quick Checklist](./octoacme-process-templates-and-gates.md#incident--rollback-quick-checklist)

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
