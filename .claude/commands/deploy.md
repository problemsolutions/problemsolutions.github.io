# Deploy to GitHub Pages

## Deployment Process
GitHub Pages auto-deploys from `main` branch.

## Steps
1. Ensure all changes are committed
2. Push to `main` branch (or merge PR)
3. GitHub Actions builds and deploys automatically
4. Live at: https://problemsolutions.github.io

## Pre-deploy Checklist
- [ ] HTML validates
- [ ] Images optimized
- [ ] Links work
- [ ] Mobile responsive
- [ ] Favicon present

## Verify Deployment
```bash
gh run list --limit 3
```

Check https://github.com/problemsolutions/problemsolutions.github.io/actions for build status.