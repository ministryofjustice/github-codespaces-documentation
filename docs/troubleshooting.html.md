---
title: Troubleshooting
weight: 50
description: Common Codespaces issues and how to resolve them.
last_reviewed_on: 2026-06-18
review_in: 6 months
---

# Troubleshooting

## You cannot create a Codespace

Check the following first:

- You are signed in to the right GitHub account
- You have completed SSO authentication: [MoJ SSO link](https://github.com/orgs/ministryofjustice/sso)
- Your access request has been approved and merged

If all three are true and you still cannot create a Codespace, raise it in [#octo-github-copilot](https://moj.enterprise.slack.com/archives/C09PXGRDNNT).

## A Codespace opens but setup fails

Try:

1. Rebuild the container
2. Restart the Codespace
3. Create a fresh Codespace on the same branch

Reference: [Troubleshooting dev containers and Codespaces](https://docs.github.com/en/codespaces/troubleshooting/troubleshooting-your-connection-to-github-codespaces).

## Ports or local preview are not working

- Check the Ports panel
- Confirm the app is listening on the expected port
- Ensure port visibility is set correctly

Reference: [Forwarding ports](https://docs.github.com/en/codespaces/developing-in-a-codespace/forwarding-ports-in-your-codespace).

## VS Code cannot connect

- Sign out and sign back into GitHub in VS Code
- Confirm the GitHub Codespaces extension is installed and enabled
- Retry with the browser flow to isolate whether the issue is local VS Code or account access

## Getting more help

When you ask for help, include:

- Repository name
- Codespace name
- Approximate time of failure
- Screenshot or exact error text
- Whether browser and VS Code both fail or only one

This usually saves a round of back-and-forth.
