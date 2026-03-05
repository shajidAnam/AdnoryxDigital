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

## Deploy Changes
From repo root:
```powershell
cd d:\AdNoryxDigital
git add .
git commit -m "Update website"
git push origin main
```
GitHub Pages will serve the latest `docs/` content.
