# Manar Degachi — Portfolio

Personal portfolio website for Manar Degachi, Full-Stack Web Developer & Final-Year IT Student at ISET Tozeur.

## Contents

- `index.html` — the full single-page portfolio (HTML/CSS/JS, no build step or dependencies required)
- `Manar_Degachi_CV_2026.pdf` — downloadable CV, linked from the site's "Download CV" / "Resume" buttons

## Running locally

No build tools needed. Just open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment (GitHub Pages)

This site is meant to be deployed via **GitHub Pages** directly from this repository:

1. Push this repo to GitHub (see steps in the main chat).
2. Go to the repo on GitHub → **Settings** → **Pages**.
3. Under "Build and deployment" → **Source**, select **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)` → **Save**.
5. Wait 1–2 minutes, then visit the URL GitHub gives you (usually `https://<username>.github.io/<repo-name>/`).

Any future push to `main` updates the live site automatically within a minute or two.

## To-do before going fully live

- [ ] Replace `CERT_PROOF_LINK` placeholder in `index.html` with a real OneDrive/Drive folder link to certificate proofs.
- [ ] Replace `PHOTO_URL` placeholder in `index.html` with a real photo link.
