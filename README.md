# fastapi-resume

Bhavika Jangid's portfolio, rendered as an interactive **FastAPI / Swagger UI** docs page.

Your career as an API: experience and projects are modeled as tagged endpoints
you can expand and "try out" (spinner, curl, streaming JSON response), with
Skills, Education, and Certifications as OpenAPI schemas. Includes a scroll-synced
sidebar, deep links, a socials popup (Explore), and light/dark themes.

## Files

- `index.html` — the site served at the root URL (identical to `portfolio.html`).
- `portfolio.html` — the self-contained portfolio site (all CSS/JS inline, no external deps).

## Run locally

It's a single static file, so just open it:

```bash
open index.html
```

Or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Deploy

Static site — deploys as-is on Vercel, Netlify, or GitHub Pages. `index.html`
is served at the root, so no build step or output config is needed.
