# PSL Bootstrap Working Group

This is an independent, opt-in working group for operators whose legitimate multi-tenant namespace or hosting products encounter the Public Suffix List bootstrap problem: browser-enforced isolation is needed before safely onboarding unrelated users, while inclusion may require thousands of already-active users.

The group's purpose is to document real cases and develop a concise, security-focused proposal for transparent alternative eligibility criteria. It is not affiliated with the Public Suffix List project.

## Principles

- Focus on browser security, verifiable architecture, accountable operation, and evidence.
- Treat PSL maintainers and browser stakeholders respectfully.
- Do not coordinate pressure, repetitive comments, reactions, or personal criticism.
- Do not misrepresent adoption, user counts, or production readiness.
- Participation is voluntary and does not imply endorsement of any proposal.

## The bootstrap problem

A new service may issue subdomains to mutually untrusting parties and therefore need browser-enforced registrable-domain boundaries before safely onboarding those parties. Requiring thousands of active users first can leave an operator choosing between delaying a legitimate service and exposing early users to the very cross-tenant risks that PSL recognition is intended to prevent.

The working group will collect independently verifiable cases and explore an architecture-based eligibility path using evidence such as domain control, durable registration, an accountable operator, published abuse and security contacts, a clear mutually-untrusted tenancy model, and a technically correct PSL rule.

Relevant upstream discussion: [publicsuffix/list#2805](https://github.com/publicsuffix/list/issues/2805).

## Participate

Open an issue describing your service, proposed suffix boundary, tenant trust model, present user count, security dependency, and the outcome of any PSL submission. Please do not include credentials, private customer information, or unverifiable claims.
