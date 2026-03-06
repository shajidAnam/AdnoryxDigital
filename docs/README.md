# Adnoryx Digital Website

Single-source static website for **Adnoryx Digital**.

## Source Folder
All website files are in:
- `docs/`

GitHub Pages is configured to publish from:
- Branch: `main`
- Folder: `/docs`

Live URL:
- `https://shajidanam.github.io/AdnoryxDigital/`

## Run Locally
1. Open terminal in VS Code.
2. Run:
   ```powershell
   cd d:\AdNoryxDigital\docs
   py -m http.server 5500
   ```
3. Open: `http://localhost:5500`
4. Stop with `Ctrl + C`.

If `py` does not work:
```powershell
python -m http.server 5500
```

## Edit Website
- Main content: `docs/index.html`
- Meta Ads service page: `docs/meta-ads.html`
- Coming soon service page template: `docs/coming-soon.html`
- Styling/theme: `docs/styles.css`
- Interactions: `docs/script.js`
- SEO files:
  - `docs/robots.txt`
  - `docs/sitemap.xml`
  - `docs/site.webmanifest`
- Assets: `docs/assets/`

## Contact Info (Current)
- Email: `mdanamulshajid@gmail.com`
- Phone: `+8801680861295`
- WhatsApp: `https://wa.me/8801680861295`

## Formspree Setup
1. Create a form at https://formspree.io
2. Replace in `docs/index.html`:
   - `action="https://formspree.io/f/your-form-id"`

## SEO Setup (Important for Google Ranking)
This site is already prepared with:
- Page titles + meta descriptions
- Canonical URLs
- Open Graph + Twitter tags
- Structured data (Schema.org)
- `robots.txt` + `sitemap.xml`

After launch, complete this checklist:
1. Create/verify your property in Google Search Console.
2. Submit sitemap:
   - `https://shajidanam.github.io/AdnoryxDigital/sitemap.xml`
3. Request indexing for:
   - Home page
   - Meta Ads page
   - Privacy Policy page
4. Connect a real domain (recommended for stronger branding/SEO than a github.io subdomain).
5. Replace placeholder social links with real brand profiles.
6. Replace testimonial/case placeholders with real proof and results.
7. Publish 2-4 keyword-focused service/blog pages over time for better long-term ranking.

Note: No one can guarantee instant rank #1. Ranking improves with technical SEO + quality content + backlinks + time.

## Deploy Changes
From repo root:
```powershell
cd d:\AdNoryxDigital
git add .
git commit -m "Update website"
git push origin main
```
GitHub Pages will serve the latest `docs/` content.
