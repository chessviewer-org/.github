# Security Policy

This is the organization-wide security policy for **chessvision-org**. A
repository may publish its own `SECURITY.md` with project-specific details; where
it does, that file applies to that project.

## Reporting a vulnerability

**Please do not open a public issue for a security vulnerability.**

Report it privately through GitHub's
[private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability):
go to the affected repository's **Security** tab and choose **Report a
vulnerability**. If that isn't available, email **contact@chessvision.org**.

Please include:

- A description of the vulnerability and its impact
- Steps to reproduce, or a proof of concept
- The affected repository, version, or URL
- Any suggested fix, if you have one

## What to expect

- We aim to acknowledge a report within a few days.
- We'll confirm the issue, work on a fix, and keep you updated on progress.
- Once a fix ships, we're happy to credit you in the advisory — let us know if
  you'd prefer to stay anonymous.

## Scope

Our projects are privacy-first and run primarily in the browser. We're
especially interested in:

- Cross-site scripting (XSS) or other injection
- Authentication or authorization flaws, or anything that lets one account reach
  another account's data
- Exposure of secrets or sensitive data
- Content Security Policy bypasses

Out of scope: reports from automated scanners with no demonstrated impact,
issues that require a compromised device or browser, and social-engineering
attacks.

## Safe harbor

We will not pursue or support legal action against anyone who reports a
vulnerability in good faith, follows this policy, and avoids privacy violations
and service disruption while testing.
