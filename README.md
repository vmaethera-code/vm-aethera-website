# V&M AETHERA — Cloudflare-ready website

This is a lightweight, responsive static website built with HTML, CSS and JavaScript. It does not require a build command or framework.

## Preview locally
Open `index.html` in a browser.

## Deploy to Cloudflare Pages (Android-friendly)
1. Create a GitHub account at https://github.com if you do not already have one.
2. Create a **private** repository, for example `vm-aethera-website`.
3. Upload all four project files (`index.html`, `styles.css`, `script.js`, `README.md`) to the repository root.
4. In Cloudflare Dashboard, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
5. Select the GitHub repository.
6. Framework preset: **None** (or **Static HTML** if shown).
7. Build command: leave blank.
8. Build output directory: `/` (repository root; if the form rejects `/`, use `.`).
9. Deploy.

## Connect the domain
After the first successful deployment, open the Pages project → **Custom domains** → **Set up a domain** and add `vm-aethera.com`. Follow the exact DNS instructions Cloudflare displays. Add `www.vm-aethera.com` as a second custom domain or configure it as a redirect to the root domain.

## Important
- Do not delete or replace existing Zoho Mail MX, SPF, DKIM or DMARC records.
- Do not change DNS records until Cloudflare Pages shows the exact records required.
- The photography currently loads from Unsplash URLs and requires an internet connection.
- Replace placeholder imagery with licensed brand photography before commercial launch.
- This is a public-facing informational website, not a booking engine, payment system, guest database or mobile app. Those need a separately designed backend and security review.
- Review all company details and contact information before publishing.
