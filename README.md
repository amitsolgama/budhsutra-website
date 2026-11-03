# BudhSutra website — branded update

This version integrates the supplied BudhSutra emblem and the official tagline, **“Unearthing the Roots. Mastering the Formula.”** It retains the existing English, Hindi and Gujarati homepage/article structure.

## What changed
- Added the supplied logo and a compact emblem crop for headers.
- Updated the homepage and article-page brand lockups and tagline.
- Added a PNG favicon based on the emblem.
- Tuned the antique-gold accent to better match the logo.
- Kept the site static: no backend, paid API, database or build step.

## Update your already-deployed website
1. Download and extract this ZIP on your computer.
2. Open the GitHub repository connected to your BudhSutra deployment.
3. Upload/replace the **contents** of the `budhsutra-website` folder at the repository root (so `index.html`, `styles.css`, `script.js`, `assets/` and `articles/` sit directly in the root).
4. Commit the changes. Your connected Cloudflare deployment should publish the update automatically.
5. Open the live site in a private/incognito window or hard-refresh it (`Ctrl + Shift + R`).

If your deployment is a **Cloudflare Worker using a static-assets binding** rather than Pages, upload these same files to the Worker’s assets directory using the deployment method you originally used; the ZIP itself is not deployed automatically.

## Before public promotion
- Replace `hello@budhsutra.example` in `index.html` with an email address you control.
- Review and fact-check all sample articles and their sources.
- Review `privacy.html` and `disclaimer.html` against your actual practices and applicable Indian requirements.
- Check the site on a phone and confirm the three language versions open correctly.

## Local preview
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.
