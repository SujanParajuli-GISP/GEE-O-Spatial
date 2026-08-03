# GEE-O-Spatial Solutions Company Inc.

This is the repository for the GEE-O-Spatial Solutions company website — geospatial
consulting, professional training, and SaaS solutions.

This website is built using:

* MkDocs (Material theme)
* GitHub Pages
* GitHub Actions

## Local development

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000 in your browser.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site with
MkDocs and publishes it to the `gh-pages` branch via GitHub Pages.

Before going live:

- [ ] Set `site_url` in `mkdocs.yml` to the real GitHub Pages (or custom domain) URL
- [ ] Update contact details in `docs/contact.md` with a company email / LinkedIn page
- [ ] Push this folder to its own GitHub repository
