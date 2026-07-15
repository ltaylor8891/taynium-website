# Taynium website

Static site (plain HTML/CSS/JS) for Taynium — a founder-led engineering
and technology company.

## Structure
- `index.html`, `about.html`, `contact.html`, `engineering-services.html`,
  `solidworks-automation.html`, `manufacturing-workflows.html`,
  `product-development.html`, `selected-work.html`
- `css/style.css` — shared design system
- `js/main.js` — mobile nav toggle
- `images/` — add photography/diagrams here

## Local preview
Open `index.html` directly in a browser, or run a simple local server:

    python3 -m http.server 8000

Then visit http://localhost:8000

## Deploy
Push this repo to GitHub, connect it to Cloudflare Pages (or Netlify),
set the build command to blank and the output directory to `/`, then
point your IONOS domain's DNS at the host.
