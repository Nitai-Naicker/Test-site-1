# Top 10 Anime of 2026 — GitHub Pages Website

A dark, editorial-style website listing the top 10 anime of 2026, built with pure HTML & CSS. Ready to deploy to GitHub Pages in minutes.

---

## Files Included

```
index.html   ← Main page (all content lives here)
style.css    ← Dark dramatic styling
README.md    ← This guide
```

---

## How to Deploy to GitHub Pages

### Step 1 — Create a new GitHub repository

1. Go to [https://github.com/new](https://github.com/new)
2. Name it something like `anime-2026` or `top-anime`
3. Set it to **Public** (required for free GitHub Pages)
4. Do NOT add a README (you already have one)
5. Click **Create repository**

---

### Step 2 — Upload your files

**Option A — Drag and drop (easiest):**
1. On your new repo page, click **"uploading an existing file"**
2. Drag all three files (`index.html`, `style.css`, `README.md`) into the box
3. Scroll down and click **Commit changes**

**Option B — Using Git (command line):**
```bash
git init
git add .
git commit -m "Initial commit: Top 10 Anime 2026 site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

---

### Step 3 — Enable GitHub Pages

1. In your repo, click **Settings** (top tab)
2. In the left sidebar, click **Pages**
3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**

---

### Step 4 — Visit your live site

After 1–2 minutes your site will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

Example: `https://johndoe.github.io/anime-2026/`

GitHub will show the URL at the top of the Pages settings once it's ready.

---

## Customising the Site

### Change the title or intro text
Open `index.html` and edit the `<header>` section near the top.

### Add or edit an anime entry
Each entry is an `<article class="anime-card">` block. Copy an existing one and change:
- The rank number in `<div class="rank-badge">`
- The genre in `<div class="tag">`
- The title in `<h2>`
- The studio/season in `<p class="studio">`
- The description in `<p class="synopsis">`
- The badges in `<div class="meta">`

### Change colours
Open `style.css` and edit the `:root` variables at the top:
```css
--gold: #c9a84c;      /* accent colour */
--bg: #0a0a0f;        /* background */
--text-primary: #f0ece0;  /* main text */
```

---

## Notes

- No frameworks, no dependencies, no build step needed
- Google Fonts are loaded via CDN (internet required to view fonts)
- The site is fully mobile responsive
