# Problem Solutions

Professional software engineering and enterprise AI solutions since 2004.

- **Live Site:** https://problemsolutions.github.io
- **Main Website:** https://www.problemsolutions.net
- **Contact:** contact@problemsolutions.net | 888.343.0569

## Quick Start

### Local Preview

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Deploy

Push to a PR against `main` branch (protected). Merging auto-deploys to GitHub Pages.

```bash
git checkout -b feature/your-change
# ... make changes ...
git commit -m "description"
git push -u origin feature/your-change
# Open PR on GitHub
```

## What's Here

- `index.html` — Landing page
- `styles.css` — All styling
- `logo.svg` — Company logo
- `favicon.png` — Browser icon
- `.well-known/` — Standards & verification files

## Tech Stack

Static HTML5/CSS3/JavaScript — no build tools, no dependencies.

## Quality Standards

- HTML5 valid (run `npx html-validate index.html`)
- Lighthouse score 90+ (Chrome DevTools)
- WCAG AA accessibility
- Semantic markup

See `.claude/CLAUDE.md` for full development guidelines.

---

**License:** All Rights Reserved — see LICENSE file
