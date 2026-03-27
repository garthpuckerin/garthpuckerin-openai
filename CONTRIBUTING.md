# Contributing to this project

First off, thank you for considering contributing to this repository. It's people like you that make the project such a great tool.

## Commit Guidelines

This project uses **Conventional Commits** (`@commitlint/config-conventional`). All commits must be formatted accurately.

Format:
`<type>[optional scope]: <description>`

Examples:

- `chore: update dependencies`
- `feat(ui): add new adaptive learning component`
- `fix: resolve hydration error`

The `pre-commit` and `commit-msg` Husky hooks will automatically format your code with Prettier and validate your commit message. If validation fails, your commit will be rejected.

## Development Setup

1. Clone the repository and install dependencies with `npm install`.
2. Run standard local dev server with `npm run dev`.
3. Test your changes locally to ensure the system compiles correctly using `npm run build`.

## Making Changes

- Ensure your code adheres to standard formatting (run `npm run format` locally if needed).
- Write descriptive commit messages.
- Submitting a Pull Request to `main` will automatically trigger our CI pipeline, including CodeQL validation and deploy builds.

We enforce semantic versioning strictly via `standard-version`. Do not bump versions manually in `package.json`.
