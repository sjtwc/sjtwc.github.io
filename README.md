# sjtwc.github.io

Personal site and blog, built with [Jekyll](https://jekyllrb.com) and the
[Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme.
Published at **<https://sjtwc.github.io>** via GitHub Actions.

## Writing

- Posts: `_posts/YYYY-MM-DD-slug.md` (front matter: `title`, `date`, `categories`, `tags`)
- Drafts: `_drafts/`, preview with `bundle exec jekyll s --drafts`

## Local preview

Requires Ruby 3.4 (pinned in `.ruby-version`).

    bundle install
    bundle exec jekyll s

## Deploy

Push to `main`; `.github/workflows/pages-deploy.yml` builds, runs html-proofer,
and publishes to GitHub Pages (Settings → Pages → Source: GitHub Actions).

## Credits

Theme: Chirpy © Cotes Chung, MIT. Do not fork this repo for your own site —
use [chirpy-starter](https://github.com/cotes2020/chirpy-starter) instead.
Content © Richard Tsang.
