# Security Policy

US-SPURS treats security, privacy, resilience, and responsible disclosure as core requirements.

## Reporting a Security Issue

Do not disclose an active vulnerability, exposed credential, private key, sensitive operational detail, or protected personal information in a public GitHub issue.

Use an approved private reporting channel for the repository or organization. Include:

- affected repository, system, or document
- clear description of the issue
- reproduction steps when safe
- potential impact
- evidence such as logs or screenshots with sensitive values removed
- recommended mitigation, when known

## Scope

Security reports may include:

- credential or secret exposure
- authentication or authorization weaknesses
- injection or remote execution risks
- insecure data handling
- dependency vulnerabilities
- configuration weaknesses
- privacy exposure
- unsafe AI or automation behavior
- operational information disclosure

## Response Principles

Security reports should be handled through:

1. acknowledgment and triage
2. impact and scope assessment
3. containment when required
4. remediation and validation
5. coordinated disclosure when appropriate
6. lessons learned and preventive improvement

## Repository Requirements

Contributors must not commit:

- passwords or API tokens
- private keys or certificates
- production secrets
- personal or protected information
- restricted operational plans
- internal network details that create material risk

Use environment variables, approved secret stores, redacted examples, and least-privilege access.

## Supported Material

The default branch and actively maintained documentation are the primary supported versions. Archived or experimental content may receive best-effort review.

## Safe Harbor

Good-faith security research should avoid privacy violations, service disruption, data destruction, social engineering, and access beyond what is necessary to demonstrate the issue.
