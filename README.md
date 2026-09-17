# CCN Great Debates — website concept

A responsive static redesign of the CCN Generative Adversarial Collaborations website.

## Run locally

From this folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Structure

- `index.html` — app shell
- `styles.css` — responsive editorial design system
- `data.js` — GAC archive data, 2020–2026
- `app.js` — routing, filtering, debate pages, About and Submit pages

No build system is required. This can be deployed directly to GitHub Pages, Netlify, Cloudflare Pages, or any static web host.

## Editorial approach

The original site is chronological and administrative. This version makes the scientific question the primary unit, while preserving an Archive view by year. External recording and official-source links point back to the original GAC resources.
