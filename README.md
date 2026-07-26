# Sewing the Archive

A quilt-block web page for the "Sewing the Small Archive" workshop.

## How to put this on GitHub Pages

1. Create a new repository on GitHub (e.g. `sewing-the-archive`).
2. Upload `index.html` from this folder to the root of that repo.
3. In the repo, go to **Settings > Pages**.
4. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a live URL (usually `https://<your-username>.github.io/<repo-name>/`) within a minute or two.

## Notes

- Everything (fonts, patterns, PDF export) is self-contained in `index.html` — no other files needed.
- The PDF download button loads a small library from a CDN, so it needs an internet connection to work.
- Fonts used: ByteBounce and Hyper Oxide are personal-use-only licenses — fine for a class page, not for commercial use.
- The "facilitator only" lock control at the bottom freezes editing once the workshop is done — use it once, right before publishing the final page.
