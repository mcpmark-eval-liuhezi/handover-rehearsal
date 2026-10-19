# Maintainer Handover Notes

Welcome aboard! This document is the practical guide for taking over maintenance of this project. It's kept short on purpose — the details below are the things that only get learned by doing the job.

## Quick Orientation

- **Default branch:** `main`. All work lands here via pull request.
- **Contribution flow:** issue → branch → draft pull request → review → merge → issue auto-closes via a `Fixes #N` reference in the pull request description.
- **Branch naming:** `docs/...` for documentation, `feat/...` for features, `fix/...` for patches.

## What You'll Be Doing Weekly

1. Triage new issues. Anything actionable gets a clear title and, where useful, sub-issues under a tracker issue.
2. Review incoming pull requests within a few days — drafts included.
3. Keep the release notes and this handover document current.

## Gotchas Learned the Hard Way

- Always link issues as sub-issues of a tracker when work is related; it keeps the board readable.
- Reference the issue in the pull request body (`Fixes #N`) so merging closes the loop automatically.
- Run the full checklist in a fresh sandbox before changing the live workflow.

## Where Things Live

| Item | Location |
| --- | --- |
| Contribution workflow | Issues + pull requests in this repository |
| Drill / rehearsal log | Gist `handover-log.md` |
| Release process | Documented per release in the repository history |

## Contacts

- Outgoing maintainer: available for questions for 30 days after the handover meeting.
