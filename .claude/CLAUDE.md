# Problem Solutions GitHub Pages

Static landing page — https://problemsolutions.github.io (auto-deploys on merge to main).

## Quick Start

**Local preview:** `python3 -m http.server 8000`

**Deploy:** Create PR against `main` (protected). Merging auto-deploys to GitHub Pages.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page + tagline rotation + copy-to-clipboard contact |
| `styles.css` | All styling (gradient bg, animations, responsive) |
| `logo.svg` | Company logo |
| `logo-badge.svg` | Browser favicon (SVG, icon-only badge) |
| `404.html` | Custom 404 page |
| `robots.txt` | SEO — allow all, point sitemap |
| `sitemap.xml` | Single entry for github.io URL |

## Taglines

Rotating in JS (~line 117 in index.html):
- "Enabling the Augmented Enterprise"
- "We Make AI Usable"
- "Software Excellence Since 2004"

## Quality Baseline

- HTML5 valid: `npx html-validate index.html`
- Lighthouse 90+ (Chrome DevTools)
- WCAG AA accessibility (contrast, alt text, semantic markup)
- Respects `prefers-reduced-motion` in JS

## SEO & Metadata

- Open Graph + Twitter Card meta tags
- Schema.org Organization structured data
- Canonical URL: https://problemsolutions.github.io/
- Contact: 888.343.0569 | contact@problemsolutions.net
