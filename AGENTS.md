# Agent Guidelines

Varshini Elangovan's personal site (varshini-e.github.io), built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme. This is a personal fork, not the upstream template — there's no external contributor workflow to worry about.

## Local Development (Docker)

```bash
# Initial setup & start dev server
docker compose pull && docker compose up
# Site runs at http://localhost:8080

# Rebuild after changing dependencies or Dockerfile
docker compose up --build

# Stop containers and free port 8080
docker compose down
```

## Pre-Commit Checklist

1. **Format code:**
   ```bash
   npx prettier . --write
   ```
2. **Build locally & verify:**
   ```bash
   docker compose up --build
   # Visit http://localhost:8080 — check navigation, pages, images, and dark mode.
   ```

## Key personal-content files

- `_pages/about.md` — homepage bio
- `_pages/resume.md` — resume/CV page (self-contained HTML/CSS, not the theme's `cv.liquid`/rendercv pipeline, which is unused)
- `_data/socials.yml`, `_data/citations.yml` — contact info and Google Scholar citation counts (`_data/citations.yml` is auto-updated by `bin/update_scholar_citations.py` via `.github/workflows/update-citations.yml`)
- `assets/pdf/Varshini_Elangovan_Resume.pdf` — the downloadable resume linked from the resume page

## Critical Configuration

When modifying `_config.yml`:

- `url` + `baseurl` must stay consistent with the deploy target (`url: https://varshini-e.github.io`, `baseurl:` empty, since this is a personal site not a project site)
- Quote YAML strings with special characters: `title: "My: Cool Site"`
