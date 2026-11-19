# dmachlanski.com

Personal academic website, built with Jekyll and served by GitHub Pages.

## Editing

| What                 | Where                     |
| -------------------- | ------------------------- |
| Bio, links and news  | `index.md`                |
| Publications         | `_data/publications.yml`  |
| CV                   | `cv.md`                   |
| Navigation, profile links | `_config.yml`        |
| Styles               | `style.css`               |

Publications are listed on both the Publications page and the CV, so add each
paper once in `_data/publications.yml`.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
