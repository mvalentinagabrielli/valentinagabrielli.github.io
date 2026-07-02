# valentina-gabrielli.github.io

A minimal academic personal site — plain HTML/CSS, no build step.

## Files
- `index.html` — all page content
- `style.css` — all styling
- `assets/CV_Gabrielli.pdf` — your CV, linked from the "Download CV" button

## Publish it on GitHub Pages

**Option A — user site (recommended, gives you `yourusername.github.io`)**
1. On GitHub, create a new repository named exactly `yourusername.github.io` (replace with your actual GitHub username).
2. On your computer, open a terminal in this folder and run:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```
3. Go to the repo → **Settings → Pages** → under "Build and deployment", set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Your site will be live at `https://yourusername.github.io` within a minute or two.

**Option B — project site (any repo name, gives you `yourusername.github.io/repo-name`)**
Same steps, but name the repo whatever you like (e.g. `personal-site`). GitHub Pages will serve it at `https://yourusername.github.io/repo-name`.

## Before you publish — a few things to fill in
- In `index.html`, the **Google Scholar** and **GitHub** links in the hero currently point to `#`. Replace `href="#"` with your real profile URLs (search for `title="Add your`).
- Double check `valentina.gabrielli@psemail.eu` is the email you want public — it's used both as a mailto link and in the footer.
- The CV download button points to `assets/CV_Gabrielli.pdf`. Swap in a fresh export any time by replacing that file (keep the same filename, or update the link in `index.html` and `footer`).

## Editing later
No build tools required — just edit `index.html` for content and `style.css` for design, then commit and push. GitHub Pages redeploys automatically on every push to `main`.
