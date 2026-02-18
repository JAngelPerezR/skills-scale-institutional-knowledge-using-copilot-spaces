# Release Readiness Checklist

Purpose: A concise checklist for Release Managers, Project Managers, QA Lead, and Developers to confirm readiness before a production deployment.

Owner: Release Manager (primary), Project Manager (secondary)

Pre-release checks
- [ ] Release branch / tag created and CI pipeline is green
- [ ] All PRs merged for the release and linked to issues
- [ ] Acceptance criteria are met for items in release (per issue/PR)
- [ ] Regression and smoke test plan executed and passed (QA Lead signoff)
- [ ] Security scans completed and no critical findings
- [ ] Migration/DB changes planned with rollback steps
- [ ] Rollback and mitigation plan documented and tested (if applicable)
- [ ] Release notes drafted and reviewed (Product Manager / Release Manager)
- [ ] Stakeholders & Support notified of release window and expected impact
- [ ] Monitoring and alerting configured for new/changed functionality
- [ ] On-call / Support Engineer informed and ready

Deployment
- [ ] Backup or snapshot (if applicable)
- [ ] Deployment steps executed (automated pipeline preferred)
- [ ] Post-deploy smoke tests run and passed
- [ ] Production monitoring checks OK
- [ ] Announce release to stakeholders and relevant channels

Post-release
- [ ] Monitor for at least the agreed observation window
- [ ] Capture any incidents and create follow-up action items
- [ ] Update retrospective/action tracker for process improvements
