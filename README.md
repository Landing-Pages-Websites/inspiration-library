# inspiration-library (data)

Curated best-in-class **design-inspiration** entries + screenshots for the website/landing-page
build pipeline. Consumed by the `inspiration-library` skill in `zleague/mega-clawhub` as a **git
submodule** at `skills/inspiration-library/library/`.

- `index.json` — manifest: `{"entries": [<approved ids>]}`
- `entries/<id>.json` — one curated entry (abstracted patterns + technique notes + tags + screenshot URL). Schema lives in the skill repo.
- `shots/<id>.webp` — full-page screenshots, served via **GitHub Pages**:
  `https://landing-pages-websites.github.io/inspiration-library/shots/<id>.webp`
- `entries/_proposed/`, `shots/_proposed/` — transient harvest staging (gitignored; promoted by `approve_proposed.py`).

Images are committed here on purpose (this is the data repo, not the code repo). Stored as WebP to keep it small.
