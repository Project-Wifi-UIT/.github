# Security policy

Project Wifi UIT includes experimental sensing and hospital-software components. We take reports about vulnerabilities, exposed secrets, unsafe data handling, and security-relevant design flaws seriously.

## Reporting a vulnerability

Please do not open a public issue for a suspected vulnerability. Report it privately through the repository's GitHub security reporting mechanism, if enabled, or contact the repository maintainers through a private GitHub channel with:

- the affected repository, component, and commit or release;
- a concise description of the issue and its impact;
- reproducible steps or a minimal proof of concept that does not contain real patient data;
- any relevant logs or configuration details with secrets removed.

If private reporting is unavailable, contact a repository maintainer privately before disclosing details publicly. Do not include passwords, tokens, private keys, patient information, or other sensitive data in a report.

## Scope and boundaries

Security reports may cover the application, firmware, data-processing code, documentation that could cause unsafe use, and repository configuration. The CSI prototype is not a clinical device and must not be treated as a diagnostic or emergency system. A security fix does not establish clinical validity, regulatory compliance, or production readiness.

## Response

Maintainers will acknowledge reports when practical, assess severity and affected versions, and coordinate a fix or mitigation. Please allow time for investigation before public disclosure. We may request additional non-sensitive information to reproduce an issue.
