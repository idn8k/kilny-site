# kilny-site

The static site at https://kilny.app: landing page, privacy policy, terms and support.

Plain HTML and CSS with no build step. GitHub Pages serves the `main` branch from the repo root, and `CNAME` sets the custom domain.

Preview locally with `python3 -m http.server 4173`, then open http://127.0.0.1:4173.

Colours, radii and the font mirror `src/constants/theme.ts` in the app repo. Photos are from Unsplash.
