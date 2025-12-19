# Problem Solutions GitHub Pages

## Project Overview
Static landing page for Problem Solutions company. GitHub Pages deployment.

**Live URL:** https://problemsolutions.github.io
**Main Site:** https://www.problemsolutions.net

## Tech Stack
- Static HTML5/CSS3/JS (vanilla)
- No build tools - edit and push
- GitHub Pages deployment (auto on push to main)

## File Structure
```
index.html    # Main landing page
styles.css    # All styles
logo.svg      # Company logo
favicon.png   # Browser icon
```

## Development Workflow

### Local Preview
```bash
python3 -m http.server 8000
# or
npx serve .
```

### Deploy
NOT ALLOWED: Push to `main` branch - will trigger GitHub Pages deploy automatically.
MUST create PR against `main` for review.

## Content Guidelines

### Taglines (rotating in JS)
Located in `index.html` ~line 117:
- "Enabling the Augmented Enterprise"
- "We Make AI Usable"
- "Software Excellence Since 2004"

### Contact Info
- Phone: 888.343.0569
- Email: contact@problemsolutions.net

### Social Links
- LinkedIn, Twitter/X, Facebook, YouTube

## Quality Checks

### Validate HTML
```bash
npx html-validate index.html
```

### Lighthouse Audit
Run in Chrome DevTools > Lighthouse

### Accessibility
- All images have alt text
- Semantic HTML structure
- ARIA labels on interactive elements
- Color contrast meets WCAG AA

## SEO
- Open Graph meta tags configured
- Twitter Card meta tags configured
- Schema.org structured data (Organization)
- Canonical URL set

## Git Workflow
- Branch: `main` (protected)
- PR required for changes
- Auto-deploy on merge
