# fastapi-resume

Bhavika Jangid's portfolio, rendered as an interactive **FastAPI / Swagger UI** API docs page.

Your career as an API: experience, projects, writing, and status are modeled as
tagged endpoints you can expand and "try out", with skills and education as OpenAPI schemas.

## Files

- `portfolio.html` — the self-contained portfolio site (all CSS/JS inline, no external deps).
- `portfolio-data.md` — the source content (profile, experience, projects, skills) the page is built from.

## Run locally

It's a single static file, so just open it:

```bash
open portfolio.html
```

Or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/portfolio.html
```

## Deploy

Static site — deploys as-is on Vercel, Netlify, or GitHub Pages. On Vercel, set the
output to serve `portfolio.html` (or rename it to `index.html`).
