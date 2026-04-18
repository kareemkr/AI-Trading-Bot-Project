# Security Policy

## Supported Versions

This is an individual research project, so only the latest code on the `main` branch is actively supported with security fixes.

| Version | Supported |
| --- | --- |
| Latest `main` branch | Yes |
| Older commits | No |
| Experimental branches | No |
| Archived versions | No |

## Reporting a Vulnerability

If you discover a security issue, please report it privately instead of opening a public GitHub issue.

Email: [kareemradwan09@gmail.com](mailto:kareemradwan09@gmail.com)

Please include:

- A clear description of the issue
- Steps to reproduce it
- Affected files, functions, or workflows
- Potential impact or severity, if known
- Any suggested fix or mitigation, if available

## Response Expectations

I will try to review valid security reports within 48 hours.

Fix timing depends on severity and project scope, but critical issues involving credentials, unsafe execution, or exposed secrets will be prioritized.

## Sensitive Data

Never share real API keys, exchange credentials, private tokens, JWT secrets, database passwords, or wallet-related secrets in public issues, pull requests, screenshots, logs, or chat messages.

If you accidentally expose a secret:

1. Revoke or rotate the secret immediately.
2. Remove the secret from the affected environment.
3. Avoid relying only on deleting a commit, because Git history may still expose the value.

## Trading and Exchange Safety

This project is for educational and research purposes only. If live exchange integrations are used, API keys should be configured with the minimum required permissions.

Recommended exchange-key rules:

- Disable withdrawals.
- Use IP restrictions when supported.
- Use separate keys for testing and production.
- Start with paper trading or small controlled tests.
- Monitor balances, open positions, and order history carefully.

## Disclosure

Please do not publicly disclose a vulnerability until it has been reviewed and, when needed, fixed. Credit can be given for valid reports if the reporter wants attribution.
