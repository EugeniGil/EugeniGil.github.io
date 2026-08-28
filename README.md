# eugenigil.github.io

Personal academic website of Eugeni Gil-Ocana — PhD candidate in Economics at the Universitat
Politècnica de València. Live at <https://eugenigil.github.io>.

Built with [academicpages](https://github.com/academicpages/academicpages.github.io), a Jekyll
template forked from Minimal Mistakes. GitHub Pages builds and deploys `master` automatically.

## Where the content lives

| What | Where |
|---|---|
| Site-wide settings, sidebar, social links | `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Home / About, CV, and other standalone pages | `_pages/` |
| Papers | `_publications/` |
| Talks and slides | `_talks/` |
| Code repositories | `_portfolio/` |
| PDFs (slides, papers, CV) | `files/` |
| Images, favicons, social card | `images/` |

`_pages/teaching.md` and `_pages/year-archive.html` are set to `published: false` because there
is nothing behind them yet; flip that flag and re-add the nav entry in `_data/navigation.yml`
when there is.

## Adding a talk

Create `_talks/YYYY-MM-DD-short-name.md` with front matter for `title`, `collection: talks`,
`type`, `permalink`, `venue`, `date` and `location`, then drop the slides in `files/` and link
them from the body.

## Running locally

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open <http://localhost:4000>. Alternatively, `docker compose up` uses the bundled
`Dockerfile` / `docker-compose.yaml`.

## Notes

- Images are kept small on purpose: the sidebar avatar is served at 700 px. Do not commit
  multi-megabyte originals — the avatar loads on every page.
- The theme builds the LinkedIn URL itself, so `author.linkedin` in `_config.yml` must be the
  **username only**, not a full URL.
