# Hebatullah Abdulazeem — Personal Website

Personal academic portfolio website for Hebatullah Abdulazeem, MD, MSc.

Built as a static single-page site. Deployed via Cloudflare Pages.

## Structure

- `index.html` — main site (all content, styles, and scripts in one file)
- `_redirects` — Cloudflare Pages redirect rules
- `CNAME` — custom domain (optional)

## Local Development

Open `index.html` directly in a browser, or serve locally:

```bash
npx serve .
```

## Deployment

Push to the `main` branch of the GitHub repo. Cloudflare Pages auto-deploys from the connected repository.

## Updating Publications

Publications are fetched live from ORCID when the page loads, with a static fallback list. To update the fallback list, edit the `fallbackPubs` array in `index.html`.
