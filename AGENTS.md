# AGENTS.md — .github

> This file provides universal AI agent guidance for any coding assistant working in this repository.
> It serves as the Anthropic key-man DR layer — if Claude is unavailable, any AI agent can use this to operate the repo.

## Repository Purpose

Organization-level GitHub configuration for the AltsPassport GitHub org. Contains the public organization profile (README) and shared templates. This is the ONLY public repository in the AltsPassport org — all content here is visible to the internet.

## Tech Stack

- **Languages:** Markdown, YAML
- **No executable code** — GitHub org config only

## Architecture

```
profile/
  README.md              # Public org profile (displayed on github.com/AltsPassport)
README.md                # Repo-level readme
```

## Development Rules

- Branch strategy: feature branches → squash merge to main → auto-delete branch
- This is a PUBLIC repo — every character is visible to the internet
- Profile README is the org's public face on GitHub — maintain professional quality
- Keep content minimal and polished — this is a storefront, not documentation
- Do not reference internal repo names, infrastructure details, or tooling

## Security

> **CRITICAL: This is a PUBLIC repository. Everything committed here is visible to the entire internet.**

- NEVER commit credentials, API keys, tokens, internal URLs, or infrastructure details
- NEVER reference private repo names, internal systems, or security configurations
- NEVER include employee/founder personal information beyond what's already public
- Keep the profile README professional and minimal
- Review every change for accidental information disclosure before committing

## Key Files

| File | Purpose |
|------|---------|
| `profile/README.md` | Public GitHub org profile |
| `README.md` | Repo readme |

## AltsPassport Context

- This repo is part of the AltsPassport AI Operating System
- Company: 2 co-founders (Marcel Dawson, President/COO + Jeff Ramseyer, CEO) + AI workforce
- All development follows SVPPB doctrine (Si Vis Pacem, Para Bellum)
- Primary AI tool: Claude Code, but this file ensures any AI agent can contribute
- Git discipline: branches for changes, squash merge, auto-delete branches
- Timestamps: US Eastern Time (ET) only
