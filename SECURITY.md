# Security Policy

N9raw takes security reports seriously and asks reporters to keep vulnerability details private while they are being reviewed.

## Reporting a vulnerability

Do **not** disclose a suspected vulnerability in a public GitHub issue, discussion, pull request, social channel, student group, or other public forum.

Use the first available private route:

1. If the affected public repository offers GitHub's **Report a vulnerability** flow, use that private reporting form.
2. Otherwise, email [contact@n9raw.com](mailto:contact@n9raw.com) with a subject beginning with `[Security]`.

Please include only the information needed to understand and reproduce the issue safely:

- the affected N9raw repository, page, service, or component;
- a concise description of the security impact;
- reproducible steps or a minimal proof of concept;
- relevant version, commit, route, or environment details when known; and
- a safe way for us to contact you for follow-up.

## Protect people and data while reporting

N9raw serves students and may involve minors. Do not include real student personal data, credentials, authentication tokens, private messages, database exports, production secrets, or logs containing personal information in a report unless N9raw explicitly requests a narrowly scoped item through a private channel.

Use synthetic or minimized evidence whenever possible. Do not perform destructive testing, degrade service availability, access data that is not yours, retain unnecessary data, use social engineering or phishing, or test third-party/provider infrastructure without separate authorization.

## Scope and repository-specific policies

This file is the default security reporting guidance for N9RAW repositories that do not publish their own `SECURITY.md`. A repository-specific security policy takes precedence when present.

The existence of a public repository or public website does not grant permission to test private N9raw systems, staging environments, student accounts, Nour production systems, third-party services, or infrastructure outside the affected public surface.

## What happens after a report

N9raw will review credible reports and coordinate privately where follow-up is needed. We do not currently publish a guaranteed response time, bug-bounty reward, safe-harbor program, CVE commitment, or general supported-version matrix.

Please keep vulnerability details private until N9raw confirms that coordinated disclosure is appropriate.
