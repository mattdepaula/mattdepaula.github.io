# mattdepaula.github.io

Personal site of Matheus de Paula (Matt), Software Engineer.

Built with [Jekyll](https://jekyllrb.com/) and the
[al-folio](https://github.com/alshedivat/al-folio) theme, deployed to GitHub
Pages via GitHub Actions.

## Local development

Requires Ruby (3.3.x), Node, and ImageMagick.

```bash
bundle install
bundle exec jekyll serve
# http://127.0.0.1:4000
```

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site
and publishes the result to the `gh-pages` branch. GitHub Pages must be set to
**Settings → Pages → Source: Deploy from a branch → `gh-pages` / root**.

## Editing content

- `_config.yml` — site settings, identity, features
- `_pages/about.md` — landing/bio (placeholder)
- `_projects/` — project cards (placeholder)
- `_posts/` — blog posts (placeholder)
- `_news/` — news/announcements (placeholder)
- `assets/json/resume.json` — CV data (placeholder)
- `_data/socials.yml` — social links
