---
title: Prerequisites and Access
weight: 20
description: What you need before requesting Codespaces access, and how requests are handled.
last_reviewed_on: 2026-06-18
review_in: 6 months
---

# Prerequisites and Access

## Prerequisites

Before you request Codespaces access, make sure the following are in place.

### 1. GitHub account

You need a GitHub account.

- Create one here: [github.com/signup](https://github.com/signup)
- GitHub account settings: [Manage your profile and account](https://docs.github.com/en/account-and-profile)

### 2. Ministry of Justice organisation membership

You must be part of the Ministry of Justice GitHub organisation.

- Join/authenticate via SSO: [github.com/orgs/ministryofjustice/sso](https://github.com/orgs/ministryofjustice/sso)
- GitHub guidance on SAML SSO: [About authentication with SAML single sign-on](https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-single-sign-on/about-authentication-with-single-sign-on)

### 3. Slack access

You need access to Justice Digital Slack and your member ID for the request form.

- How to find your Slack member ID: [Where to find your member ID](https://slack.com/help/articles/360003868612-View-and-copy-a-members-id-in-Slack)
- OCTO support channel: [#octo-github-copilot](https://moj.enterprise.slack.com/archives/C09PXGRDNNT)

### 4. Editor choice

You can use Codespaces either in a browser or in VS Code.

- Browser option: no install required
- VS Code download: [code.visualstudio.com/download](https://code.visualstudio.com/download)
- VS Code onboarding: [Getting started with VS Code](https://code.visualstudio.com/docs/getstarted/getting-started)

## How access requests work

1. Open the request form: [octo-access issue chooser](https://github.com/ministryofjustice/octo-access/issues/new/choose)
2. Select GitHub Codespaces Access Request.
3. Complete all required fields.
4. Submit.

The request flow is automated through this repository. A pull request is created to add your membership to the Codespaces users team. After review and merge, access is applied.

## What to include in your request

- Full name
- Work email
- Slack ID
- Team
- Whether you have a developer device
- Short use case summary

Reviewers use the use case to confirm the request, so a sentence or two about what you plan to do is enough.
