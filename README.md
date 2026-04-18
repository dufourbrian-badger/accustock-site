# accustock-site

Marketing website for **AccuStock** — smart inventory tracking for Shopify bundles, multipacks, and kits.

Live at: https://accustockapp.com

## Structure

Static HTML, no build step.

- `index.html` — landing page
- `privacy.html` — privacy policy
- `terms.html` — terms of service

## Deployment

Auto-deploys to Cloudflare Pages on push to `main`.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
