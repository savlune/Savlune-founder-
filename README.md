# SAVLUNE — Muhammad Luthfi Yannur

Personal website with responsive typography, scroll-driven book animations, documents, sponsors, and business news.

## Publishing

In repository **Settings → Pages**, set **Source → GitHub Actions**. The `Publish SAVLUNE` workflow builds and deploys on every push to `main`, manual run, and at 08:00 WITA on the 1st, 11th, and 21st each month.

Expected website address after a successful deployment: https://savlune.github.io/Savlune-founder-/

## Development

Node.js 22. Run `npm ci`, then `npm run dev` or `npm run build`. The exported website is in `out/`.

## News

Three dated BBC Business headlines are refreshed at build time. The refresh button reads the latest published edition; GitHub Pages does not provide a live server or streaming prices. Editorial notes are edited in `src/data/insights.json`. An unavailable feed preserves the previously published headlines when available.

## Content

Profile, services, and document data are in `src/data/`. Original images and font licenses are in `public/`. Testimonials must come from actual people; the website provides a WhatsApp submission form.
