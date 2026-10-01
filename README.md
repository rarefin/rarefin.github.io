# rarefin.github.io

Personal site, built with Jekyll on GitHub Pages (based on the Minimal Light theme).

## Updating

Everything you'd normally change lives in `_data/` — no HTML edits needed.

| To…                         | Edit                        |
|-----------------------------|-----------------------------|
| Add a news item             | `_data/news.yml` (newest first) |
| Add a paper                 | `_data/publications.yml` (field guide at the top of the file) |
| Feature a paper at the top  | set `selected: true` (keep ~5–6) |
| Swap a local PDF for arXiv  | add `arxiv:` to the entry; the title link switches automatically |
| Internships                 | `_data/experience.yml` |
| Reviewing / awards          | `_data/service.yml` |
| About text                  | `index.md` |
| Sidebar line, SEO text, URL | `_config.yml` |

Pre-arXiv PDFs go in `assets/files/papers/` with stable names. Teaser images go in
`assets/img/` as `.webp`, roughly 900px wide.

## Local preview

```
bundle install
bundle exec jekyll serve
```
