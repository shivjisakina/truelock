# TrueLock - Static Locksmith Website (Orlando)

This repository contains a static HTML/CSS website scaffold for a locksmith business targeting Orlando and the Greater Orlando area. It's designed to be hosted on GitHub Pages and pointed to a GoDaddy domain.

Files included

- `index.html` — Main landing page with SEO-friendly content, meta tags, and JSON-LD.
- `styles.css` — Styling matching the original theme.
- `assets/logo.svg` — Simple logo asset.
- `CNAME` — Put your custom domain (replace `yourdomain.com`) to configure GitHub Pages.

Quick start

1. Open the repo in your terminal and replace placeholders in `index.html` and `CNAME` with your real domain and phone number.
2. Commit and push to GitHub on the `main` branch.
3. In GitHub, go to Settings → Pages and set the source to the `main` branch and root folder.
4. Add your custom domain in the Pages settings or use the `CNAME` file.

GoDaddy DNS setup (summary)

1. Add four A records for the root (`@`) pointing to the GitHub Pages IPs:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
2. Add a CNAME record for `www` that points to `<your-github-username>.github.io`.
3. In GitHub Pages, enter your custom domain and enable HTTPS.

SEO & local business tips

- Replace phone number and exact address in `index.html` and the JSON-LD block to match your business.
- Keep the service-area list up-to-date to target local searches in Orlando and Greater Orlando.
- Create a Google Business Profile (formerly Google My Business) and list consistent NAP (Name, Address, Phone) across directories.

# truelock
