# lotingo-app.github.io

The public site of the Lotingo app: home, privacy policy and support, in English (`/`) and Vietnamese (`/vi/`). Served by GitHub Pages from `main`, root folder.

- `.nojekyll` must stay: without it Pages drops `/.well-known/`, which will hold `assetlinks.json` and `apple-app-site-association` for the app links.
- The app claims only links under `/l/`. Never put a page there, and never add a custom domain to this site: the domain is fixed in released builds.
- Plain HTML, no build step. Keep the English and Vietnamese pages in step.
