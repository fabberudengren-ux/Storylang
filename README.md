# Storylang website

- `site/` – the public website at **https://storylangapp.com** (landing page, support and privacy policy).
  Cloudflare Pages builds it from this repository: production branch `main`, no build command,
  output directory `site`. Every push to `main` that changes `site/` goes live.
- `index.md`, `support.md` – the older GitHub Pages pages at
  https://fabberudengren-ux.github.io/Storylang/ (Storylang 1.4 links to `/support` there). Keep them until
  1.4.1 has replaced 1.4 for most users.

The source of the website is `website/` in the app repository (ReaderApp); `privacy.html` is generated there from
`docs/PRIVACY_POLICY.md`. Copy changes here with `website/scripts/sync-to-site-repo.sh` in that repository.
Keep the App Store download link (https://apps.apple.com/app/id6808269111) on the landing page – the site is also
used in applications (for example the Claude startup program).
