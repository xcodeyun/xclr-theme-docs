# Xclr theme documentation

Public documentation site for the Xclr Shopify theme, published with GitHub Pages.

- Live site: https://xcodeyun.github.io/xclr-theme-docs/
- Theme source code lives in a separate private repository and is not part of this repo.

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Overview, requirements, installation, store setup |
| `settings.html` | Theme settings reference |
| `sections.html` | Section reference |
| `faq.html` | Frequently asked questions |
| `support.html` | Support policy and contact details |
| `changelog.html` | Release notes |
| `404.html` | Not-found page |
| `assets/style.css` | Site styles |
| `.nojekyll` | Serves files as-is, without Jekyll processing |

## Local preview

```bash
python3 -m http.server 8080
# open http://127.0.0.1:8080/
```

## Deploy

The site is served by GitHub Pages from the `main` branch, repository root. Push to `main` and Pages rebuilds automatically. No build step is required.

## Keeping the documentation in sync

Theme settings and sections change over time. When the theme changes:

1. Update the affected page (`settings.html` or `sections.html`).
2. Add an entry to `changelog.html`.
3. Update the version number in the footer of every page and in this README.

The documentation must stay consistent with the theme's setting labels and section names.
