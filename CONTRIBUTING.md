# Contributing

## Before Starting

- Read the project overview and relevant documentation.
- For substantial changes, discuss the proposed scope before implementation.
- Check existing issues and avoid duplicating active work.

## Changes

- Keep each change focused and explain its purpose.
- Add or update tests and documentation when behavior changes.
- Run the checks relevant to the changed area.
- Do not include secrets, credentials, generated clutter, or unrelated changes.

## Commits

Use one commit per concern with a subject in the form `type(scope): outcome`.
Type is one of `feat`, `fix`, `refactor`, `docs`, `test`, `chore`, `perf`, or
`ci`; scope names the package or area and is omitted for cross-cutting changes.
Write the subject in present tense, lower case, without a trailing period, and
explain what changed and why in the body.

Enable the repository commit template with:

```sh
git config commit.template .gitmessage
```

A behavior change also adds a `CHANGELOG.md` entry.

## Pull Requests

Describe the problem, the change, verification performed, and known limitations.

Project-specific commands and review requirements: <add or link them here>.
