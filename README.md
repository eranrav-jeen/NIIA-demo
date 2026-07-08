# NIIA OS · שרשרת המתודולוגיה

A static, single-page implementation of the NIIA OS methodology pipeline UI, built from a Claude Design handoff.

- **Project route view** — 6-stage pipeline rail (Challenge → Focus → Life Problem → AI Fit → Project Card → Gate) with a detail panel per stage.
- **Portfolio view** — kanban-style board of all initiatives grouped by pipeline stage.
- **Mobile view** — vertical, collapsible stepper mockup inside a phone frame.

No build step or dependencies — it's a single `index.html` with vanilla CSS/JS.

## Running locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploying

A GitHub Actions workflow (`.github/workflows/deploy-pages.yml`) publishes this site to GitHub Pages automatically on every push to the default branch. Once the first run completes, the site is available under the repository's Pages URL (Settings → Pages).
