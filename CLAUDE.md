# CLAUDE.md

This file provides guidance for AI assistants working with this repository.

## Repository Overview

This is a **personal GitHub profile repository** for Jada Bautista. It serves as a public-facing introduction displayed on the GitHub profile page. The repository is not a software project — it contains no source code, build systems, tests, or dependencies.

### Contents

| File | Purpose |
|------|---------|
| `README.md` | GitHub profile introduction, rendered on the profile page |
| `profile.png` | Portrait photo displayed in the README |

## Repository Purpose

The README functions as a professional portfolio introduction highlighting:
- Academic affiliation (Ethics Research Fellow, University of Notre Dame)
- Research and design roles
- Technical skills (Python, design tools)
- External links (LinkedIn, email, Python portfolio)

## Development Workflow

Since this is a documentation-only repository, the typical workflow is:

1. Edit `README.md` directly (no build step required)
2. Preview Markdown rendering locally or on GitHub
3. Commit with a descriptive message
4. Push to `master`

```bash
git add README.md
git commit -m "Update README: <brief description of change>"
git push origin master
```

## Conventions

### Markdown Style
- Uses emoji for visual organization (section headers, contact info)
- Centered heading via raw HTML: `<p align="center">...</p>`
- Horizontal rules (`---`) to separate major sections
- Bold text for emphasis on names, titles, and links
- Sections follow the order: intro → skills → portfolio → contact

### Images
- `profile.png` is a high-resolution RGBA PNG (1130 x 1264 px, ~1.7 MB)
- Referenced in `README.md` implicitly (rendered via GitHub profile mechanics)
- Do not compress or replace without explicit request

### Links
- External links use inline Markdown: `[label](url)`
- Institutional links point to official pages (Notre Dame, LinkedIn, GitHub)
- Email is provided as plain text within a link context

## What AI Assistants Should Know

- **No code to analyze or refactor** — all work is Markdown editing
- **Changes are immediate** — no build, compile, or deploy step exists
- **Audience is public** — content should remain professional and accurate
- **Facts matter** — do not invent or alter affiliations, roles, or dates without explicit instruction from the repository owner
- **Keep formatting consistent** — match existing emoji and section structure when making edits
