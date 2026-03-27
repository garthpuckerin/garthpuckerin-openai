# Garth Puckerin · OpenAI Application

[![Build & Deploy](https://github.com/GarthPuckerin/openai-application/actions/workflows/deploy.yml/badge.svg)](https://github.com/GarthPuckerin/openai-application/actions/workflows/deploy.yml)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Enterprise-grade repository holding my application for the Learning Systems Engineer role at OpenAI's Education Team.

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Architecture](#architecture)
- [Contributing](#contributing)
- [License](#license)

## Background

This project represents my perspective on building AI-native, production-grade learning systems. It serves both as an interactive curriculum vitae and as a statement on how educational logic must be treated as robust infrastructure.

## Install

This project uses modern web standards and Vite for bundling.

1. Clone the repository
2. Install dependencies:

```sh
npm install
```

## Usage

**Development Server:**

```sh
npm run dev
```

**Production Build:**

```sh
npm run build
```

**Code Formatting & Linting:**
This project utilizes Prettier and ESLint. Formatting is automatically enforced via Husky and lint-staged prior to committing.

```sh
npm run format
```

## Architecture

- **Vite:** Next-generation frontend tooling.
- **Prettier:** Code formatting standards.
- **Commitlint:** Enforces Conventional Commits.
- **Standard Version:** Automates changelogs and version bumping.

Please refer to `CONTRIBUTING.md` for guidelines on how to contribute or maintain the project.

## Contributing

See [the contributing file](CONTRIBUTING.md) for detailed guidelines.

## Security

Please refer to [SECURITY.md](SECURITY.md) for vulnerability reporting procedures.

## License

ISC © Garth Puckerin
