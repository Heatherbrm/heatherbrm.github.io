# heatherbroome.com

Personal academic website for Heather Broome — PhD student in Computer Science at the University of Illinois Urbana-Champaign.

Built with [Jekyll](https://jekyllrb.com/) using the [al-folio](https://github.com/alshedivat/al-folio) theme. The site is deployed automatically to GitHub Pages via the `.github/workflows/deploy.yml` workflow whenever changes are pushed to `main`.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## What lives where

- `_pages/about.md` — landing page bio and contact info
- `_pages/publications.md`, `_bibliography/papers.bib` — publications list
- `_pages/cv.md`, `_data/cv.yml` — CV
- `_pages/news.md`, `_news/` — news / announcements
- `_data/socials.yml` — social links
- `assets/img/prof_pic.jpg` — profile photo
- `_config.yml` — site-wide configuration
