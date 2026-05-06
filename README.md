# Arko — Landing Page

Single-file landing page for [arko.ge](https://arko.ge) (or your GitHub Pages URL).

## Deploy to GitHub Pages in 3 steps

### 1. Create a GitHub repo
Go to github.com → New repository → name it `arko` (or `arko-landing`)
Make it **Public**. Don't add README (we have one).

### 2. Push this file
```bash
git init
git add .
git commit -m "initial landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/arko.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: `main` / `/ (root)`
- Save

Your site will be live at:
`https://YOUR_USERNAME.github.io/arko/`

---

## Custom Domain (optional, free)
1. Buy a `.ge` domain (e.g. `arko.ge`) from any registrar
2. In repo Settings → Pages → Custom domain: enter `arko.ge`
3. Add a CNAME DNS record at your registrar pointing to `YOUR_USERNAME.github.io`
4. Check "Enforce HTTPS" after DNS propagates (~24h)

---

## To update the page
Just edit `index.html` and push:
```bash
git add index.html
git commit -m "update landing"
git push
```
GitHub Pages redeploys automatically in ~1 minute.
