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
- Identify stakeholder groups and communication needs:
  - **Sponsor**: Monthly executive summaries, milestone approvals, escalated decisions
  - **External Stakeholders (Key Users)**: Sprint demos, UAT invitations, feature announcements
  - **Account Executive / Customer Success**: Release notes, customer impact assessments, post-launch metrics
  - **Engineering teams**: Technical updates, dependency coordination
  - **Sales and Support**: Feature capabilities, known issues, training materials
- Provide regular updates (weekly or milestone-based) tailored to each audience
- Use a single source of truth (project README or release doc) for status

## Communication Matrix Example

| Role | Frequency | Method | Content Focus |
|------|-----------|--------|---------------|
| Sponsor | Monthly or at milestones | Executive summary, meetings | Strategic alignment, ROI, major decisions |
| External Stakeholders | Sprint demos (bi-weekly) | Demo sessions, UAT invites | Usability, feature validation, feedback |
| Account Executive/Customer Success | At releases | Release notes, briefings | Customer impact, support readiness, adoption plan |
| Delivery Team | Daily/Weekly | Standups, syncs | Progress, blockers, technical details |
| Broader Organization | Major milestones | Email updates, announcements | High-level progress, launch dates |

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
- **Technical blockers**: Developer/QA Specialist -> Scrum Master -> PM -> Technical Lead
- **Product/scope decisions**: PM -> Product Manager -> Sponsor
- **Resource constraints**: PM -> Product Manager -> Sponsor
- **Customer satisfaction issues**: External Stakeholder -> Account Executive/Customer Success -> Product Manager -> Sponsor
- **Security incidents**: Follow the security incident runbook and notify Security on-call immediately

## Role-Specific Communication Responsibilities

### Scrum Master
- Facilitates team communication in ceremonies
- Escalates organizational blockers
- Shares velocity and flow metrics with PM

### Sponsor
- Receives executive summaries and milestone reports
- Provides strategic guidance and decision-making
- Communicates project value to executive leadership

### External Stakeholders
- Provide feedback during demos and UAT
- Escalate usability concerns to Product Manager
- Validate that communication about features is clear and accurate

### Account Executive / Customer Success
- Shares customer feedback and satisfaction metrics
- Coordinates post-launch communication with customers
- Escalates customer concerns that impact product decisions
