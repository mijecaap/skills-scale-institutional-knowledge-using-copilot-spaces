# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks (PM, PdM, key stakeholders)
- Demo/Review at the end of each sprint or milestone — include External Stakeholders for feedback
- Sprint retrospectives — facilitated by Scrum Master, all team members participate
- QA sync — dedicated time for QA Specialist to review test results and quality metrics

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
The QA Specialist leads quality assurance activities in collaboration with Developers:
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers and QA Specialist)
- End-to-end smoke tests for critical flows before release (QA Specialist)
- Security scanning in CI (automated)
- Manual QA for feature acceptance when needed (QA Specialist)
- User acceptance testing (UAT) with External Stakeholders (coordinated by QA Specialist and Product Manager)
- Regression testing for each release (QA Specialist)
- Test automation development and maintenance (QA Specialist with Developer support)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates resolution)
- Level 2: PM escalates to Product Lead and dependent teams (Scrum Master supports removal of organizational blockers)
- Level 3: Sponsor-level escalation for business-impacting issues or resource constraints

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with External Stakeholders invited
- [ ] Risk register updated weekly by PM
- [ ] QA Specialist integrated into sprint workflow
- [ ] Scrum Master facilitating ceremonies and removing blockers
- [ ] Quality metrics dashboard established and monitored
- [ ] UAT sessions scheduled for major features

## Role-Specific Execution Activities

### Scrum Master
- Facilitate daily standups, sprint planning, and retrospectives
- Track and resolve blockers
- Monitor team velocity and flow metrics
- Coach team on agile practices
- Protect team from interruptions

### QA Specialist
- Execute test plans for each sprint
- Report quality metrics and test coverage
- Coordinate UAT with External Stakeholders
- Identify and document defects
- Verify acceptance criteria are met before marking work as done

### External Stakeholders
- Attend sprint demos and provide feedback
- Participate in UAT for major features
- Validate that solutions meet real-world needs
- Escalate usability concerns early
