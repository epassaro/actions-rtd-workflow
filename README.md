# actions-rtd-workflow
A RTD-like documentation pipeline for GitHub Actions

### Features
1. Support of `pip` and `conda` dependency files.
2. Build and deploy branches under `/branches/<branch>`.
3. Build and deploy tags under `/tags/<tag>`.
4. Secure build and preview of pull requests under `/pull/<number>` via labels.
5. Manual trigger for branches.
6. Select branch to deploy the site (default: `gh-pages`).
7. Redirect the main domain to `/latest` or `/stable` (default: `/latest`).
8. Redirect the `/stable` subdomain to the latest SemVer tag, or the stable branch (if exists).
9. Automatic removal of pages from closed/merged pull requests, and deleted branches or tags.

### Not supported
Multi-language builds.

### Live demo
- https://epassaro.github.io/actions-rtd-workflow
- https://epassaro.github.io/actions-rtd-workflow/latest
- https://epassaro.github.io/actions-rtd-workflow/stable
- https://epassaro.github.io/actions-rtd-workflow/pull/1
- https://epassaro.github.io/actions-rtd-workflow/tag/v0.1.0

This page has been created from a pull request
