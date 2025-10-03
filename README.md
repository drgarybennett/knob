# drgarybennett.org — GitHub Pages (Jekyll) Site

This repository contains a production‑ready GitHub Pages site using the official **minima** theme plus a small custom header and CSS.

## Quick Start

1. **Create a new GitHub repo** (e.g., `drgarybennett.org`).
2. Upload these files to the repo root (or push via git).
3. In **Settings → Pages**, set:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or `master`) / root (`/`)
4. Wait for the build (usually ~1–2 minutes). Your site will be live at:
   - `https://<username>.github.io/<repo>` or at your custom domain once configured.

## Custom Domain

- In **Settings → Pages**, add your custom domain (e.g., `drgarybennett.org`).
- Create a `CNAME` file in the repo root with `drgarybennett.org` (GitHub can do this automatically).
- Point your DNS to GitHub Pages per their docs (A records for apex, CNAME for `www`).

## Where to Put Your Content

- **Headshot:** `assets/img/headshot.jpg` (1600x1600 JPG recommended)
- **Press Kit:** add files under `assets/press/` and update links on `/press-kit/`
- **Media transcripts:** add PDFs under `assets/media/`
- **Videos:** edit `/media/` page and replace the `VIDEO_ID` placeholders with YouTube/Vimeo IDs
- **KPIs:** edit numbers on `index.md`

## Style & Structure

- Navigation is defined in `_config.yml` under the `nav:` key.
- Light custom styles live in `assets/css/custom.css`.
- We override `minima` with `_includes/header.html` and `_includes/head.html` and a custom `_layouts/default.html`.

## Accessibility & Sensitivity

- Provide alt text for images and transcripts for media.
- Use the homepage and leadership pages to emphasize **current commitments** and **stewardship**, avoiding “campaign” tone.
- Keep updates regular but measured (e.g., a quarterly post in **Thoughts**).

## Optional Enhancements

- Add Google Analytics 4 (via `head.html`).
- Add Open Graph images for richer social sharing previews.
- Create a `news/` collection or use posts if you want dated updates.

---

Last updated: 2025-10-03
