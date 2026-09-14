# rievs

Marketing site for Rhode Island EV Conversions. Static HTML, no build step.

## Pages

- `/` — homepage
- `/ford-ranger-ev-conversion/` — Ranger build log
- `/electric-truck-conversion/`, `/classic-car-ev-conversion/` — guides
- `/ev-conversion-new-england/` — service area
- `/ev-conversion-registration/` — RI + nearby state registration notes (sources linked; re-check yearly)

All pages share `assets/site.css`. Header, nav, and footer are repeated in each page, so change them everywhere.
When adding a page, add it to `sitemap.xml` and the footer nav.

Images: originals in `img/*.jpg`, served as `img/*-800.webp` / `*-1600.webp`. Social share image is `img/og-ranger.jpg`.

## Local preview

```
python3 -m http.server 8000
# http://localhost:8000
```

## Deploy (GitHub Pages, free)

1. Create a public repo and push this directory to `main`.
2. Repo → Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Live at `https://<user>.github.io/<repo>/` in about a minute.

### Custom domain

Once the domain is confirmed:

```
echo yourdomain.com > CNAME
```

Then at the registrar, point the apex `A` records at GitHub's IPs
(185.199.108–111.153) and `www` as a `CNAME` to `<user>.github.io`.
Settings → Pages → Custom domain, then check **Enforce HTTPS**.

## Before it goes live

- [ ] Replace `REPLACE@EXAMPLE.COM` in `index.html` with the real contact address
- [ ] Swap the Ranger photo placeholder for a real photo
- [ ] Confirm the business name / domain
