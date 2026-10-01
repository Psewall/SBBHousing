# SBB Housing — sbbhousing.com

Static site for SBB Housing: building and remodeling Idaho homes for resale.

## Structure
- `index.html` — landing page (hero, about, project cards, contact)
- `projects/604-woodlands.html` — McCall new construction ($1.3M, completion April 2027)
- `projects/3917-hillcrest.html` — Boise remodel in progress
- `style.css` — all styles

## Deploy
Push to `main` on GitHub; enable Pages (Settings → Pages → Deploy from branch: `main`, `/ (root)`).
`sbbhousing.com` is set via the `CNAME` file — point DNS at GitHub Pages.

## Adding a project
1. Copy `projects/3917-hillcrest.html` as a starting template.
2. Add a card to the `#projects` grid in `index.html`.
