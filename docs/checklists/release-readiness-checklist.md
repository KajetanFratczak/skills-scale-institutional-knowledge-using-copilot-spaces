# Release Readiness Checklist

Purpose: Reduce release friction and ensure rollbacks and post-release verification are possible.

Pre-release
- [ ] Changelog updated
- [ ] Release notes draft prepared
- [ ] All linked PRs merged into release branch
- [ ] Documentation updated (user-facing and internal)
- [ ] QA signoff obtained
- [ ] Migration / DB impact reviewed and tested
- [ ] Rollback plan documented and tested
- [ ] Release owner and communication plan identified

Release window
- [ ] Notify stakeholders before release
- [ ] Run pre-release verification steps
- [ ] Monitor logs & metrics during rollout

Post-release
- [ ] Run post-release verification checklist
- [ ] Confirm no critical alerts
- [ ] Close the release (tag, update milestone, announce)
- [ ] Retrospective / post-mortem if incidents occurred
