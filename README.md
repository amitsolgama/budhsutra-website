# BudhSutra starter website

A free, static, mobile-responsive landing page for BudhSutra with:
- English, Hindi and Gujarati language selector for the homepage
- Each of the three starter articles has English, Hindi and Gujarati versions
- Article cards and category filters
- Three sample educational articles
- Basic privacy and educational disclaimer pages
- No backend, paid API, database or build process

## Before publishing
1. Replace `hello@budhsutra.example` in `index.html` with an email address you control.
2. Review and fact-check all sample articles. They are starter educational drafts, not investment recommendations.
3. Review `privacy.html` and `disclaimer.html` against your actual practices and applicable Indian requirements.
4. Optional: replace Google Fonts import in `styles.css` with system fonts if you want to avoid external font requests.

## Test locally
Open `index.html` in a browser. For a more reliable local preview, run a simple static server from this folder:
`python -m http.server 8000`
Then open `http://localhost:8000`.

## Deploy free with GitHub + Cloudflare Pages
1. Create a GitHub account at https://github.com/.
2. Create a **public** repository named `budhsutra-website`.
3. Upload the contents of this folder to the repository root. `index.html` must be at the root, not inside another nested folder.
4. Create a Cloudflare account at https://dash.cloudflare.com/.
5. Open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
6. Connect GitHub and select `budhsutra-website`.
7. Use these settings:
   - Framework preset: **None**
   - Build command: leave blank
   - Build output directory: `/` (if the interface requires a directory, use the repository root / `.` as supported)
8. Click **Save and Deploy**.
9. Cloudflare will provide a `*.pages.dev` address. Open it on desktop and mobile to test.
10. Future changes: edit files in GitHub and commit; Cloudflare automatically redeploys.

## Important
- Keep the repository public only if you are comfortable making the website source code public. This static site contains no secrets.
- Do not put passwords, API keys, private customer data or credentials in this repository.
- Free-plan quotas and product interfaces can change; check current Cloudflare and GitHub terms.
- A `pages.dev` address is a platform subdomain, not ownership of a custom domain.
