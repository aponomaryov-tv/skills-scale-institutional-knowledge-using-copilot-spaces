# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designers

### Role Summary
UX Designers shape the end-to-end user experience and ensure solutions are usable, accessible, and aligned with customer needs.

### Responsibilities
- Translate product goals into user flows, wireframes, and prototypes
- Define UX acceptance criteria and accessibility expectations
- Partner on usability validation and design QA before release
- Document design decisions and known UX trade-offs

### Goals
- Improve user satisfaction and task success
- Reduce rework caused by unclear interaction design
- Ensure experiences are consistent and accessible

### Typical Communication
- Design reviews with Developers and Product Managers
- Prototype walkthroughs during planning and execution
- Usability findings shared in demos and retrospectives

### Interactions with Existing Roles
- **Developers:** clarify interaction details and UI edge cases before implementation.
- **Product Managers:** align design decisions to customer outcomes and roadmap priorities.
- **Project Managers:** flag design dependencies and timeline impacts early.

---

## Scrum Masters / Agile Coaches

### Role Summary
Scrum Masters / Agile Coaches improve team flow, facilitate delivery ceremonies, and remove process bottlenecks.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Track blockers and drive timely escalation
- Coach teams on Definition of Done, work-in-progress limits, and continuous improvement
- Help teams maintain predictable cadence and healthy collaboration

### Goals
- Improve flow efficiency and delivery predictability
- Reduce unresolved blockers and unplanned work
- Strengthen team operating discipline without adding heavy process overhead

### Typical Communication
- Daily and weekly ceremony facilitation
- Blocker and dependency escalation with PM and engineering leads
- Retrospective summaries with agreed action owners

### Interactions with Existing Roles
- **Developers:** help unblock work, protect focus, and improve delivery rhythm.
- **Product Managers:** support backlog readiness and clear acceptance criteria.
- **Project Managers:** align escalation paths, milestones, and delivery risk response.

---

## DevOps / SRE

### Role Summary
DevOps / SRE roles own deployment reliability, operational readiness, and service health guardrails.

### Responsibilities
- Maintain CI/CD reliability and deployment automation
- Define release readiness, monitoring, and rollback requirements
- Partner on incident response and post-incident improvements
- Ensure operational runbooks and alerting are current

### Goals
- Increase release reliability and mean time to recovery (MTTR)
- Reduce deployment risk and operational toil
- Improve observability and production confidence

### Typical Communication
- Release readiness reviews and go/no-go check-ins
- Incident updates with clear status and impact
- Reliability trend reporting in weekly or milestone reviews

### Interactions with Existing Roles
- **Developers:** enforce build/test/deploy quality gates and operability standards.
- **Product Managers:** align release risk decisions with customer impact and timeline.
- **Project Managers:** provide deployment constraints and escalation input for planning.

---

## Data Analysts / Analytics

### Role Summary
Data Analysts define measurement plans and provide analytics that guide prioritization, release decisions, and retrospectives.

### Responsibilities
- Define and maintain project success metrics and dashboards
- Validate telemetry/events needed to measure outcomes
- Produce weekly metric snapshots and trend analysis
- Support experiment/readout design and interpretation

### Goals
- Ensure decisions are evidence-based
- Detect delivery or product risks early through metrics
- Improve outcome measurement from initiation through retrospective

### Typical Communication
- Metric definitions and dashboard walkthroughs in planning
- Weekly performance updates and anomaly alerts
- Outcome readouts after release and in retrospectives

### Interactions with Existing Roles
- **Developers:** confirm event tracking and data quality in delivered features.
- **Product Managers:** translate product goals into measurable KPIs and experiments.
- **Project Managers:** provide objective status signals and escalation indicators.

---

## Security / Compliance

### Role Summary
Security / Compliance roles ensure delivery meets organizational security, privacy, and regulatory requirements.

### Responsibilities
- Advise on threat, compliance, and data-handling requirements
- Define security acceptance criteria and release controls
- Support security incident triage and remediation follow-up
- Review high-risk changes and required approvals

### Goals
- Reduce security and compliance risk exposure
- Shift security validation earlier in the lifecycle
- Enable safe, auditable releases

### Typical Communication
- Security requirement reviews during initiation and planning
- Risk exceptions and mitigation decisions with PM/PdM
- Incident response coordination for security-impacting events

### Interactions with Existing Roles
- **Developers:** provide secure coding guidance and review high-risk implementations.
- **Product Managers:** align security controls with customer and regulatory commitments.
- **Project Managers:** define escalation paths and approvals for security-critical decisions.

---

## Technical Writers / Documentation

### Role Summary
Technical Writers ensure process and product documentation is clear, current, and usable by internal and external audiences.

### Responsibilities
- Create and maintain release notes, runbooks, and user-facing docs
- Define doc Definition of Done criteria for deliverables
- Keep process artifacts versioned and easy to discover
- Coordinate documentation updates as part of release readiness

### Goals
- Reduce onboarding and support friction
- Improve documentation quality and consistency
- Ensure changes are accompanied by accurate guidance

### Typical Communication
- Documentation planning with PM/PdM and engineering
- Release-note reviews before deployment
- Feedback loops with Support and Customer Success

### Interactions with Existing Roles
- **Developers:** capture implementation details and operational caveats accurately.
- **Product Managers:** align docs with customer messaging and feature intent.
- **Project Managers:** track documentation milestones as part of delivery plans.

---

## Support / Customer Success

### Role Summary
Support / Customer Success teams represent customer impact in planning, release readiness, and post-release follow-through.

### Responsibilities
- Share customer pain points and adoption blockers
- Validate support readiness (FAQs, known issues, escalation paths)
- Communicate release changes and expected impact to customers
- Feed support trends into planning and retrospectives

### Goals
- Improve customer adoption and satisfaction
- Reduce time to resolve customer-facing incidents
- Ensure release communications are clear and actionable

### Typical Communication
- Weekly customer-impact updates to PM/PdM
- Release readiness and launch communication reviews
- Incident and escalation updates for customer-facing issues

### Interactions with Existing Roles
- **Developers:** provide reproducible customer issues and urgency/context.
- **Product Managers:** bring customer outcomes into prioritization decisions.
- **Project Managers:** align customer communication timing and escalation workflows.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
