# Security

Do not report security vulnerabilities through public issues.

Equipe Suite repositories must never contain production credentials, service-role keys, webhook secrets, private keys or customer secrets.

For a suspected vulnerability, contact the repository owner through the organization's private security reporting channel.

When fixing a security issue:

- preserve evidence needed for investigation;
- avoid exposing sensitive details in commit messages or public issue text;
- verify affected IAM, Billing and Data contracts;
- run repository and production postflight checks.
