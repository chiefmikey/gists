# Project CLAUDE.md - Gists

## Project Overview

Archive of GitHub Gists containing reusable shell scripts for macOS system maintenance — app updates and software updates.

## Tech Stack

- **Language:** Shell (Bash scripts), JavaScript (ESM for config only)
- **Runtime:** macOS (target platform for scripts)
- **Linting:** mikey-pro (ESLint 10 flat config)
- **Formatting:** Prettier via `mikey-pro/prettier`, Stylelint via `mikey-pro/stylelint`

## Commands

No npm scripts defined. Run gist scripts directly:
```bash
bash src/mac-apps-update.sh
bash src/mac-software-update.sh
```

## Conventions

- ESM only for JS config (`"type": "module"`)
- Gist scripts live in `src/`
- Static archive — no build or test pipeline
- Conventional commits: `feat:`, `fix:`, `chore:`, etc.
