# omarboulaid.com

Personal portfolio of **Omar Boulaid** — Senior Product Designer.
Currently an "under construction" landing page; the full portfolio is in progress.

## What's here
- `index.html` — the site (single, self-contained file; fonts loaded from Google Fonts)
- `CNAME` — custom domain for GitHub Pages (`omarboulaid.com`)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy (GitHub Pages — free)
1. Push this repo to GitHub (see commands below).
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **/(root)** → Save.
3. Under **Custom domain**, enter `omarboulaid.com` (the `CNAME` file already sets this).
4. At your domain registrar, point DNS at GitHub Pages:
   - Four `A` records for the apex `omarboulaid.com` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - One `CNAME` record for `www` → `omar-bld.github.io`
5. Back in Pages, tick **Enforce HTTPS** once the certificate is issued.

## Deploy (Cloudflare Pages — also free, alternative)
Connect this repo in the Cloudflare dashboard, framework preset **None**, build command empty, output dir `/`. Add `omarboulaid.com` as a custom domain.

## Local preview
Open `index.html` in a browser, or run `python3 -m http.server` and visit `http://localhost:8000`.
