# Chapman Market Group — Website

A single-page marketing site for Chapman Market Group, an AI-powered vending
machine business serving apartment communities, schools, warehouses, and
other high-traffic spaces.

## What's here

- `index.html` — the entire site (HTML, CSS, and JS in one file, logo images
  embedded as base64). No build step, no dependencies — just open it in a
  browser or upload it to any static host.

## Before going live

- **Lead form**: `index.html` contains a Formspree integration. Replace
  `YOUR_FORM_ID` in the `<form action="...">` attribute with a real
  Formspree endpoint (see the comment directly above the form in the HTML).
- **Social preview image**: the `og:image` / `twitter:image` meta tags
  currently point at the embedded logo. Once the site has a real domain,
  swap those for a hosted image URL (see comment in `<head>`).
- **Stats**: double check the numbers in the hero stats bar reflect real
  figures before launch.

## Deploying

This is a static site — no build process required. Drag-and-drop deploy
options:

- **Netlify / Vercel**: drag the folder into their dashboard, or connect
  this repo directly.
- **GitHub Pages**: push to a repo, enable Pages on the `main` branch.
- **Any static host**: upload `index.html` as-is.

## Local preview

Just open `index.html` directly in a browser — no server needed.
