# PagePace site

Public support + privacy pages for the App Store.

## Setup

1. Replace `REPLACE_WITH_YOUR_EMAIL` in `index.html` and `privacy.html`.
2. Create a **public** GitHub repo (e.g. `pagepace-site`).
3. Push this folder to `main`:

```bash
cd ~/Developer/pagepace-site
git init
git add .
git commit -m "Add PagePace privacy and support pages"
git branch -M main
git remote add origin https://github.com/YOUR_USER/pagepace-site.git
git push -u origin main
```

4. GitHub → **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: **/ (root)**
   - Save

## App Store Connect URLs

After Pages is live (usually 1–2 minutes):

- Support: `https://YOUR_USER.github.io/pagepace-site/`
- Privacy: `https://YOUR_USER.github.io/pagepace-site/privacy.html`
