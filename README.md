# GitHub Pages Deployment

A simple GitHub Actions workflow that deploys a static website to GitHub Pages whenever `index.html` changes on the `main` branch.

Project URL: https://roadmap.sh/projects/github-actions-deployment-workflow

## Live Site

https://reneilwembuy.github.io/gh.deployment.workflow/

## How it works

- The workflow lives in `.github/workflows/deploy.yml`
- Every push to `main` that changes `index.html` triggers a deployment
- The site is published to GitHub Pages automatically
