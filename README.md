# Deception Research in Psychology — Quarto Site

A Quarto website with RevealJS slides embedded on the home page and available standalone.

## Structure

- `index.qmd` — website home with an iframe of the slides
- `slides/slides.qmd` — RevealJS slide deck
- `chapters/*.qmd` — detail pages for each section
- `assets/custom.scss` — professional, subdued styling
- `assets/references.bib` — starter bibliography
- `_quarto.yml` — site configuration; outputs to `docs/` for GitHub Pages
- `.nojekyll` — ensures GitHub Pages does not process files unexpectedly

## Build

```bash
quarto render
```

Then publish the `docs/` directory (GitHub Pages: Settings → Pages → Source: `Deploy from a branch`, folder `docs/`).

