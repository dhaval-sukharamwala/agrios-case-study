# AgriOS — Product Design Case Study

A self-initiated concept: an AI copilot for farm management that leads with a **decision**, not a dashboard.

It's a single, self-contained `index.html` — all CSS, JavaScript, images and fonts are embedded, so there's **no build step and no other files to upload**. Host the one file and you're done.

---

## Put it live on GitHub Pages

### Option A — add it to your existing portfolio repo (recommended)
If you already have a portfolio repo (e.g. `your-username.github.io`):

1. Create a folder named `agrios` in the repo.
2. Drop `index.html` inside it.
3. Commit & push.
4. It's live at **`https://your-username.github.io/agrios/`** — link to it from your portfolio's projects list.

### Option B — as its own repo (no command line needed)
1. Create a new **public** repo, e.g. `agrios-case-study`.
2. On the repo page: **Add file → Upload files**, drag in `index.html`, and commit.
3. Go to **Settings → Pages → Build and deployment → Source: "Deploy from a branch" → Branch: `main` / `/ (root)` → Save**.
4. Wait ~1 minute. It's live at **`https://your-username.github.io/agrios-case-study/`**.

### With git (if you prefer the terminal)
```bash
git init
git add index.html README.md
git commit -m "AgriOS case study"
git branch -M main
git remote add origin https://github.com/your-username/agrios-case-study.git
git push -u origin main
# then enable Pages in the repo Settings (step 3 above)
```

---

## Good to know
- **Fonts** load from Google Fonts (needs internet — fine for any visitor; falls back to system fonts offline).
- **To edit your contact details:** open `index.html`, search for `mailto:` and `linkedin.com` near the bottom, and swap in your links.
- **File size** is ~850 KB because the screenshots and the persona photo are embedded. That's well within GitHub Pages limits and loads fast.
- Works on any static host — Netlify Drop, Vercel, Cloudflare Pages — if you'd rather not use GitHub Pages.
