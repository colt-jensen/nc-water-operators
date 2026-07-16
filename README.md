# NC Water Operator Recruitment Study — Landing Page

Public "learn more" page for the NCRWA / UNC School of Government water operator
recruitment study. Built with [Quarto](https://quarto.org); bilingual (English / Español).

## Local preview
```bash
quarto preview
```

## Deploy (GitHub Pages)
```bash
quarto publish gh-pages
```
Rendered output goes to `/_site` (git-ignored); deployment pushes it to the `gh-pages` branch.

## Source files
- `_quarto.yml` — site config, navbar language toggle, footer
- `custom.scss` — brand theme (navy/steel) and Apply button
- `index.qmd` — English page
- `es.qmd` — Spanish page
