# Security policy

This policy covers every repository in the Opsburg organization: the Opsburg platform, its Helm chart
and container images, the GitHub Action, the Azure DevOps extension, the design system, the templates
and opsburg.dev.

## Supported versions

Security fixes go into the latest release only. If you run an older version, upgrade to the latest
release to get a fix.

## Reporting a vulnerability

**Please do not open a public issue, discussion or pull request for a security problem.**

Report it privately through GitHub:
[github.com/opsburg/.github/security/advisories/new](https://github.com/opsburg/.github/security/advisories/new).
Only the maintainers can see the report, and you can follow it and talk with us there. Use this link
for any Opsburg component, including those whose source repository is not public.

Please include:

- the component and the version affected;
- what an attacker can do and what they need to do it;
- the steps to reproduce it, or a proof of concept;
- any fix or mitigation you have in mind.

## What happens next

- We acknowledge your report within 5 working days.
- We confirm or rule out the issue and tell you how we plan to fix it.
- We fix it, release the fix and then publish a GitHub security advisory. We credit you in it unless
  you ask us not to.

Please give us a reasonable time to release the fix before you disclose the issue publicly.
