---
title: Responsible Usage
weight: 40
description: Practical rules for using Codespaces safely and cost-effectively.
last_reviewed_on: 2026-06-18
review_in: 6 months
---

# Responsible Usage

Codespaces is shared cloud infrastructure. Good usage keeps it reliable and affordable.

## Do

- Stop Codespaces you are not using
- Delete old Codespaces after work is merged
- Use the smallest machine size that does the job
- Push changes to GitHub regularly
- Ask for help early if you hit access or environment problems

## Do not

- Leave Codespaces running overnight when idle
- Store secrets directly in source files
- Share forwarded ports publicly unless there is a clear reason and approval
- Use Codespaces as a long-running server

## Handling secrets and data

- Use GitHub Codespaces secrets for credentials: [Managing account-specific secrets](https://docs.github.com/en/codespaces/setting-your-user-preferences/managing-your-account-specific-secrets-for-github-codespaces)
- Use repository or organisation secrets where appropriate: [Encrypted secrets](https://docs.github.com/en/actions/security-for-github-actions/security-guides/using-secrets-in-github-actions)

## Keeping costs down

- Stop at end of day
- Remove stale environments each week
- Prefer one active Codespace per task

## Support

For help, ask in [#octo-github-copilot](https://moj.enterprise.slack.com/archives/C09PXGRDNNT).
