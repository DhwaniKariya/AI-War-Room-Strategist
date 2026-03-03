# AI-War-Room-Strategist

Static simulation dashboard for a fictional election war room.

## Run locally

- Open `Octopus_WarRoom_Live.html` directly in a browser.
- Or open `index.html`, which redirects to `Octopus_WarRoom_Live.html`.

## GitHub Pages deployment

This repo includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

- Trigger: push to `main` (or run manually from Actions tab).
- Deploy target: GitHub Pages.
- Artifact path: repository root (`.`).

### One-time repository settings

In your GitHub repository:

1. Go to `Settings -> Pages`.
2. Under `Build and deployment`, set `Source` to `GitHub Actions`.
3. Push to `main` and wait for workflow `Deploy static site to GitHub Pages` to complete.

Published URL is typically:

`https://<your-username>.github.io/AI-War-Room-Strategist/`
