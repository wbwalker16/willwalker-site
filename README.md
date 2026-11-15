# willwalker-site

Personal portfolio for Will Walker. One static HTML file, no build step.

## Edit content
Everything lives in `index.html`. Search for the section ids: `#work`, `#approach`, `#ai`, `#services`, `#contact`.
Case-study write-ups are the `<div class="more" id="case-…">` blocks near the bottom of the work section.

## Deploy
Hosted on Netlify. Every push to `main` redeploys automatically.
Contact form uses Netlify Forms; notifications are configured in the Netlify dashboard (Forms → Notifications).

## Files
- `index.html` — the site
- `William_Walker_Resume.pdf` — résumé download
- `og.png` — LinkedIn / social preview image (1200×630)
- `favicon.svg`, `apple-touch-icon.png`
- `netlify.toml` — headers and publish settings
