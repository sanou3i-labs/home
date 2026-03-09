# Project Template

Copy this structure when creating new repos in Sanou3i Labs.

## Required Repo Elements

### Root-level files
- `README.md` — Clear description, setup instructions, and usage
- `LICENSE` — MIT or appropriate license
- `.gitignore` — Ignore files correctly
- `CONTRIBUTING.md` — How to contribute (if applicable)

### Documentation
- `docs/` folder for extensive docs
- `examples/` folder for usage examples
- Clear inline comments in code

### Metadata in repo description
Format: `<Name> — <One-line description> | tags: category:<category>, status:<status>, lang:<lang>`

Example: `note-cli — Simple command-line notes app | tags: category:tools, status:active, lang:python`

## Category Options

- `tools` — Small utilities, CLIs, scripts
- `webapps` — Full-stack web apps, APIs
- `automation` — Workflows, bots, integrations
- `experiments` — Prototypes, learning projects

## Status Options

- `active` — Currently in development
- `maintained` — Stable, receives updates
- `archived` — No longer maintained

## Commit Message Style

Use conventional commits:
- `feat: add new feature`
- `fix: bug fix`
- `docs: update documentation`
- `refactor: code cleanup`
- `chore: maintenance tasks`

## Branch Strategy

- `main` — Stable releases
- `feature/<name>` — New features
- `fix/<name>` — Bug fixes

## README Template

```markdown
# <Project Name>

**Status:** <active|maintained|archived>
**Category:** <tools|webapps|automation|experiments>
**Language:** <programming-language>

## Description

<What does this do? Why does it exist?>

## Features

- Feature 1
- Feature 2

## Setup

```bash
# Installation steps
<commands here>
```

## Usage

```bash
# Example usage
<commands here>
```

## Contributing

<How others can contribute, if applicable>

## License

MIT

## Project Links

- Organization: https://github.com/sanou3i-labs
- Repo: https://github.com/sanou3i-labs/<repo-name>
```
