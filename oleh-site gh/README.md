# Personal site

Static, no build step. Deployed by GitHub Actions on every push to main.

## Deploy
1. Create a repo (any name; `YOURUSERNAME.github.io` gives the cleanest URL).
2. Drop these files in the repo root and push to main.
3. One-time: repo Settings > Pages > Source > **GitHub Actions**.

The workflow in `.github/workflows/deploy.yml` publishes the site on every push. Check the Actions tab for the run and the live URL.
