# Process Improvements

This PR/branch introduces process improvements, templates, and checklists to address gaps identified in the project management documentation. The goal is to reduce context loss, speed onboarding, and make decisions and releases more repeatable.

Why these changes

- Problem: Meeting notes are inconsistent or missing action owners and due dates, resulting in untracked work.
- Problem: Decisions and rationale are not captured centrally; context is lost over time.
- Problem: Retros and releases lack standard checklists which leads to missed follow-ups and release friction.

What’s included

- templates/meeting-notes-template.md — standard meeting notes format
- templates/decision-log-template.md — decision/ADR-style log
- checklists/retro-checklist.md — retro facilitation & follow-up checklist
- checklists/release-readiness-checklist.md — pre-release & post-release checklist

How to use

1. Use the meeting notes template for all recurring and important meetings. Add the meeting notes to docs/meetings/ or link them from the relevant issue/PR.
2. When making architectural or process decisions, create a decision-log entry and link related PRs/issues.
3. Use the retro checklist to plan, run, and capture outcomes from retros. Track action items in issues.
4. Use the release readiness checklist before major releases and for deployment signoff.

Rollout

- Add these templates to your normal meeting and PR workflows.
- Encourage team to use decision-log for any change that affects cross-team behavior.
- Review usage after 1 month and iterate based on feedback.
