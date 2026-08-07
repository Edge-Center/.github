# Security policy

## Reporting a vulnerability

**Do not open a public issue for a security problem.** A public report exposes
every user of the affected component before a fix exists.

Report it privately instead. Go to the affected repository, open the **Security**
tab, and choose **Report a vulnerability**. That creates a thread visible only to
the maintainers, and it is the channel we watch.

Include as much as you can:

- Which repository and which version or commit is affected.
- What an attacker can do with it, and what access they need to start.
- Steps to reproduce, ideally a minimal configuration or a short program.
- Any patch or mitigation you already have in mind.

## What happens next

- We acknowledge the report and tell you whether we can reproduce it.
- We agree a disclosure date with you. Please keep the details private until a
  fixed release is out.
- We credit you in the advisory and the release notes unless you prefer otherwise.

## Scope

In scope: the code in this organization - the Terraform provider, the Go SDKs,
the Kubernetes components and the integration plugins. Credential handling, token
leakage into state or logs, TLS verification, and privilege escalation through a
managed resource are all worth reporting.

Out of scope here: the EdgeCenter platform and its public API. Report those
through the EdgeCenter support channels instead, not through this repository.

## Supported versions

Fixes go into the latest released minor version of a component. Older lines are
not backported unless the issue is critical and the upgrade path is genuinely
blocked.

## Handling credentials

If you are reporting a problem that involves a token, rotate that token first and
never paste a live credential into an issue, a pull request or a log excerpt.
