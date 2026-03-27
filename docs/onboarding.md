# Onboarding — Welcome to the ShopMock QA Team

Hi, and welcome aboard! This document will get you up to speed on how we work.

## Our Tools
- **GitHub Issues** — where all bugs, features, and tasks are tracked
- **GitHub Projects** — our Kanban board (To Do / In Progress / In Review / Done)
- **Pull Requests** — how we review and approve changes to documents and test files
- **Branches** — we never commit directly to `main`; all work goes on a named branch

## Our Branching Convention
| Type | Format | Example |
|------|--------|---------|
| Feature/task | `feat/short-description` | `feat/onboarding-complete` |
| Bug report doc | `bug/issue-number-short-desc` | `bug/42-login-crash` |
| Test plan | `test/feature-name` | `test/login-flow` |

## Our Issue Labels
| Label | Meaning |
|-------|---------|
| `bug` | Something is broken |
| `feature` | New functionality |
| `test-plan` | A test plan document |
| `needs-info` | Waiting on more detail |
| `critical` | Blocks release |
| `major` | Significant issue, workaround exists |
| `minor` | Low impact |
| `cosmetic` | Visual only, no functional impact |
| `duplicate` | Already reported |
| `wontfix` | Acknowledged but won't be fixed |

## How We Communicate
- All discussion happens **on GitHub issues and PRs** — not in chat
- Be specific: vague comments waste everyone's time
- Be respectful: we assume good intent

## Your First Task
1. Read this document fully
2. Go to the issue titled **"[ONBOARDING] Confirm you've read this document"** and leave a comment saying you've read it and have one question (make one up if needed — practise asking a clarifying question!)
3. Add your name to `TEAM.md` on a new branch and open a PR

Good luck — we're glad to have you on the team!
— *Your QA Lead*
