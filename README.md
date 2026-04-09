# WatchMyMac Landing Page

Public landing page for WatchMyMac, hosted with GitHub Pages.

## Deploy

The landing page is hosted using GitHub Pages and automatically deployed via GitHub Actions.

To deploy a new version after making changes:

1. **Make your changes** to `index.html` or other assets.
2. **Commit your changes**:
   ```bash
   git add .
   git commit -m "your commit message"
   ```
3. **Push to the `main` branch**:
   ```bash
   git push origin main
   ```

Pushing to `main` will automatically trigger the `.github/workflows/deploy-pages.yml` workflow and update the live site within a few minutes.

## Local preview

Open `index.html` in a browser.
