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
- [ ] Deploy to staging and run smoke tests (QA Specialist validates)
- [ ] UAT completed and signed off by External Stakeholders
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (QA Specialist and Developers)
- [ ] Announce release to stakeholders and support
- [ ] Brief Account Executive/Customer Success team on new features and customer impact
- [ ] Update customer-facing documentation and training materials
- [ ] Schedule post-launch review with External Stakeholders to gather feedback

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Post-Launch Activities

### Account Executive / Customer Success Responsibilities
- Monitor customer adoption metrics and usage patterns
- Collect customer feedback on new features
- Coordinate training sessions or webinars if needed
- Track customer satisfaction scores
- Escalate issues or feature requests to Product Manager
- Report on customer success metrics in post-launch reviews

### External Stakeholder Engagement
- Schedule follow-up sessions to gather real-world usage feedback
- Validate that features are meeting intended goals
- Identify any gaps or opportunities for improvement
- Participate in release retrospectives

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Customer impact (prepared by Account Executive/Customer Success)
- Support readiness checklist
