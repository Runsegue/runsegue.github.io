# Runsegue website

Jekyll site for [runsegue.github.io](https://runsegue.github.io).

## GitHub Pages setup (once)

1. Repo **Settings → Pages → Build and deployment**
2. **Source:** GitHub Actions (not “Deploy from branch”)
3. Push to `main` — workflow `.github/workflows/pages.yml` builds and deploys

## Local preview

```bash
bundle install
bundle exec jekyll serve
```
