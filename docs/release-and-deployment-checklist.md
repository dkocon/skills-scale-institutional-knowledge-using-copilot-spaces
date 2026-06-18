# Release & Deployment Checklist (Project-level)

Purpose: A concise checklist teams can use to confirm release readiness and responsibilities prior to deployment.

- [ ] Release owner (Release/Deployment Engineer) assigned
- [ ] Release window scheduled and communicated to stakeholders and support
- [ ] All PRs merged and acceptance criteria met
- [ ] CI: passing tests, lint, and security scanning
- [ ] Performance and smoke tests run in staging with pass criteria met
- [ ] Rollback plan and runbook updated and validated
- [ ] Release notes drafted and approved
- [ ] Telemetry instrumentation verified (events, dashboards)
- [ ] Security sign-off (if required) completed
- [ ] QA sign-off completed
- [ ] Support/on-call notified and runbooks shared
- [ ] Post-deploy verification checklist defined and owner assigned

Notes:
- If any checkbox is unchecked, the release owner should pause the deployment and escalate per the project's escalation path.
