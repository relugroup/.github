
# Contributing to ReluGroup Repositories

## Development Workflow

1. Create a feature or fix branch from the current development branch.
2. Make and test your changes locally.
3. Push your branch to GitHub.
4. Open a pull request into the relevant `dev/*` branch.
5. At least one approval is required before merging.
6. Address all review comments before merge.
7. Only approved maintainers/owners may merge into protected branches.

## Branch Naming

Use descriptive branch names:

- `feature/<feature-name>`
- `fix/<issue-name>`

Development branches follow:

- `dev/v0.0.1`
- `dev/v0.0.2`

`main` represents production-ready code.

## Pull Requests

Pull requests should:

- clearly explain what changed and why;
- be focused on a single feature, fix, or task;
- include relevant testing information;
- avoid unrelated changes.

Direct pushes to protected `dev/*` and `main` branches are not permitted.

## Code Quality

Before submitting a pull request:

- make sure the application builds/runs successfully;
- run relevant tests;
- remove debugging code;
- review your own changes.

## Commit Messages

Use clear and consistent commit messages following this format:

`type: short description`

Examples:

- `feat: add event filtering`
- `fix: correct margin calculation`
- `docs: update setup instructions`
- `refactor: simplify validation logic`
- `test: add pricing unit tests`
- `chore: update dependencies`

Use the following commit types:

- `feat` — new feature
- `fix` — bug fix
- `docs` — documentation changes
- `refactor` — code restructuring without changing behaviour
- `test` — adding or updating tests
- `chore` — maintenance, configuration, or dependency changes
