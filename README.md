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

Then open [GEE-O-Spatial Website](https://sujanparajuli-gisp.github.io/GEE-O-Spatial/) in your browser.

## Adding a blog post

Create a Markdown file in `docs/blog/posts/` (e.g. `2026-11-05-my-post.md`):

```markdown
---
date: 2026-11-05
authors:
  - sujan
categories:
  - Tutorials
tags:
  - gee
---

# My Post Title

Short excerpt shown on the blog index.

<!-- more -->

Full article here.
```

Posts with a future `date` stay hidden until that date. Add new authors in `docs/blog/.authors.yml`.

## Training resources

`docs/services/training-resources.md` lists repositories from
<https://github.com/SujanParajuli-GISP?tab=repositories>. To add one, copy an existing card.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site with
MkDocs and publishes it to the `gh-pages` branch via GitHub Pages.

Before going live:

- [ ] Set `site_url` in `mkdocs.yml` to the real GitHub Pages (or custom domain) URL
- [ ] Update contact details in `docs/contact.md` with a company email / LinkedIn page
- [ ] Push this folder to its own GitHub repository
