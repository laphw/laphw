# Contributing to fixhw

Thanks for your interest in contributing to `fixhw`! We welcome contributions of fixes, improvements, and new profiles.

## Workflow

1. Fork the repo or create a new branch if you're a member.
2. Make your changes in a feature branch.
3. Run `pre-commit` to format and lint your changes.
4. Open a pull request against `main`.
5. A maintainer (currently @karlssonkenneth) will review and merge it.

## Commit Guidelines

- Use clear, descriptive commit messages.
- Make separate commits for logically independent changes.
- Keep your pull request focused on one topic.

## Running Pre-Commit

Before pushing, run:

```bash
pre-commit run --all-files

### Notes on pre-commit
- The order of the hooks matter, prettier should run first to catch stylistic issues before running markdownlint.
- prettier and markdownlint can conflict, added the .markdownlint.yaml to disable conflicting rules.
```
