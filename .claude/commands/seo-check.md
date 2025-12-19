# SEO Check

Validate SEO elements for the site.

## Checklist

### Meta Tags
- [ ] `<title>` present and descriptive (50-60 chars)
- [ ] `<meta name="description">` present (150-160 chars)
- [ ] `<meta name="viewport">` set
- [ ] `<link rel="canonical">` set

### Open Graph
- [ ] `og:title`
- [ ] `og:description`
- [ ] `og:type`
- [ ] `og:url`
- [ ] `og:image`
- [ ] `og:site_name`

### Twitter Cards
- [ ] `twitter:card`
- [ ] `twitter:site`
- [ ] `twitter:title`
- [ ] `twitter:description`
- [ ] `twitter:image`

### Structured Data
- [ ] Schema.org JSON-LD present
- [ ] Valid Organization schema
- [ ] Test at: https://validator.schema.org/

### Technical SEO
- [ ] `<html lang="en">` set
- [ ] Semantic heading hierarchy (h1 > h2 > h3)
- [ ] All images have `alt` attributes
- [ ] favicon.png present
- [ ] robots.txt (optional for GitHub Pages)
- [ ] sitemap.xml (optional for single page)

## Validation Tools
- Google Rich Results: https://search.google.com/test/rich-results
- Schema Validator: https://validator.schema.org/
- Meta Tags Preview: https://metatags.io/
- Twitter Card Validator: https://cards-dev.twitter.com/validator

## Current Status
Run this command to have Claude analyze index.html and report SEO compliance.
