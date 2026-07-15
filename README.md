# SiunKim.github.io

Personal website for **Siun Kim** — a single-page static site (plain HTML/CSS), hosted on GitHub Pages.

**Live URL (after deploy):** https://siunkim.github.io

## Structure
```
SiunKim.github.io/
├── index.html      # the whole site (single page)
├── style.css       # styles (light + dark, responsive)
├── assets/
│   ├── profile.jpg # ← ADD your headshot here
│   ├── cv.pdf      # (optional) host your CV here
│   └── favicon.ico # (optional) browser-tab icon
└── README.md
```

## Before you publish — fill these in
Search `index.html` for `TODO` and update:
- [ ] **Email** — replace `YOUR_EMAIL@example.com` with the address you want public.
- [ ] **Profile photo** — save your headshot as `assets/profile.jpg` (shows an "SK" circle until you do).
- [ ] **CV** — currently links to the Selta-hosted PDF. To host it here, drop `assets/cv.pdf` and change the CV link.
- [ ] **Phone** — remove the phone line in the Contact list if you don't want it public.
- [ ] **DiZiNER link** — swap the arXiv URL for the ACL Anthology page once available.
- [ ] **Favicon** — add `assets/favicon.ico` (optional).

## Deploy to GitHub Pages
```bash
cd SiunKim.github.io
git init
git add .
git commit -m "Initial personal site"
git branch -M main
git remote add origin https://github.com/SiunKim/SiunKim.github.io.git
git push -u origin main
```
Then on GitHub: **Settings → Pages** → Source = `Deploy from a branch`, Branch = `main` / `root`.
The site goes live at https://siunkim.github.io within ~1–2 minutes.

## Updating later
Edit `index.html` (e.g. add a publication), then:
```bash
git add . && git commit -m "Update publications" && git push
```
Changes deploy automatically.
