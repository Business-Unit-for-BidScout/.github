# Business-Unit-for-BidScout

BidScout business unit organization.

## Standard Repositories

- [`requirements`](https://github.com/Business-Unit-for-BidScout/requirements): product/business requirements, scope, workflows, acceptance criteria, and open questions.
- [`deploy`](https://github.com/Business-Unit-for-BidScout/deploy): deployment orchestration, domains, CI/CD release notes, environment mapping, and operations docs.
- [`.github`](https://github.com/Business-Unit-for-BidScout/.github): organization profile and repository map.

## Repository Map

Current repositories should keep this split:

- Business application repositories own source code, tests, builds, and development docs.
- `requirements` owns durable product/business requirements.
- `deploy` owns deployment and operations workflows.
- `.github` owns organization-level profile and repository map.

## Governance

- Keep development and deployment separate.
- Use GitHub Actions/CI for deployment workflows; store credentials in GitHub Actions secrets.
- Do not commit tokens, passwords, SSH keys, customer private data, or server credentials.
