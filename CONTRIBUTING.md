# Contributing

Thank you for helping improve Project Wifi UIT. Contributions may include code, firmware, experiments, tests, documentation, or careful reports about reproducibility and limitations.

## Before you start

- Read the repository README and the relevant project documentation.
- Check existing issues and pull requests before opening a new one.
- Use synthetic, simulated, or explicitly de-identified data only. Never commit patient information.
- Do not include secrets, credentials, private keys, or local machine paths in commits or examples.
- Keep claims proportional to the evidence. Prototype observations are not clinical conclusions.

## Issues

Use the issue templates for reproducible bugs and focused feature requests. Include the repository, version or commit, environment, steps to reproduce, and relevant logs or screenshots after removing sensitive information.

For security vulnerabilities, do not open a public issue. Follow [SECURITY.md](SECURITY.md).

## Pull requests

1. Create a focused branch from the repository's default branch.
2. Explain the problem, the approach, and any safety or data-handling implications.
3. Keep changes small enough to review and update relevant documentation.
4. Run the repository's documented checks and include the results in the pull request.
5. Confirm that examples and test fixtures contain no patient data or secrets.
6. Request review from maintainers and respond to feedback constructively.

Pull requests are reviewed for correctness, clarity, maintainability, security, and respect for the project's prototype boundaries. Passing checks does not imply clinical validity or production readiness.

## Commit and documentation guidance

Use clear commit messages and avoid unrelated changes. When documenting sensing results, include the setup, assumptions, limitations, and enough context for another contributor to reproduce the experiment without exposing sensitive data.

By contributing, you agree that your contributions are provided under the terms applicable to the repository receiving the contribution.
