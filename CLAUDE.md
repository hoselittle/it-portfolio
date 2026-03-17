# CLAUDE.md

## Project Overview

This is a personal IT portfolio and professional profile for Joselito Augustinus, hosted on GitHub. It showcases cybersecurity skills, certifications, and career objectives, targeting a Security Operations Center (SOC) Tier 1 Analyst role.

This is **not** an application project — it is a static, Markdown-based portfolio with no build system, dependencies, or runtime.

## Repository Structure

```
it-portfolio/
├── README.md       # Main portfolio content (profile, skills, certifications)
└── CLAUDE.md       # This file — guidance for AI assistants
```

## Technology & Format

- **Content format**: Markdown (`.md`) with inline HTML for badges and layout
- **Badge service**: [img.shields.io](https://img.shields.io) for certification and LinkedIn badges
- **No build tools, package managers, or CI/CD pipelines**
- **No tests** — pure documentation project

## Key Conventions

- Use GitHub-flavored Markdown for all content
- Inline HTML (`<div>`, `<a>`, `<img>`) is used sparingly for badge rendering and layout
- Certification badges use the `for-the-badge` style from shields.io
- Keep the README concise and professionally focused on cybersecurity

## Branching

- `master` — primary branch with portfolio content
- `main` — remote default branch (maps to `master` locally)

## Current State / TODOs

- The **Skills** table in README.md is a placeholder — needs real skills and hyperlinked project references
- The portfolio could be expanded with project descriptions, tools used, and links to lab/demo repositories

## Development Workflow

1. Create a feature branch from `master`
2. Edit Markdown files directly
3. Commit with clear, descriptive messages
4. Push and open a pull request

## Guidelines for AI Assistants

- This is a documentation-only repo. Do not introduce build tooling, scripts, or dependencies unless explicitly requested.
- Preserve the existing badge style (`for-the-badge`) and shields.io URL patterns when adding new badges.
- When editing README.md, maintain the current section order: Introduction, Objective, Skills, Certifications.
- Do not remove or alter the LinkedIn badge link.
- Keep language professional and concise — this serves as a public-facing portfolio.
