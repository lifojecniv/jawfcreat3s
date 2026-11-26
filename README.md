# JAWF Creats — Portfolio

A responsive, single-page portfolio. Plain HTML, CSS and JavaScript, so there is no build step.

## Files
- `index.html` — the whole site (styles and scripts included)
- `favicon.svg` — browser tab icon
- `robots.txt`, `.nojekyll` — hosting helpers
- `netlify.toml`, `vercel.json`, `.github/workflows/pages.yml` — deploy configs

## Before you deploy
Edit `index.html` and replace:
- `hello@example.com` with your real email
- the placeholder bio, projects (`Project One` to `Project Four`) and links (`href="#"`)
- skill percentages if you want different numbers

## Deploy

### GitHub Pages
1. Create a repo (for a user site, name it `<username>.github.io`) and upload all files, including the hidden `.github` and `.nojekyll`.
2. In the repo go to **Settings > Pages** and set **Source** to **GitHub Actions**.
3. Push to `main`. The site appears at `https://<username>.github.io/`.

### Netlify
Drag and drop this folder at https://app.netlify.com/drop, or connect the repo. No build command is needed.

### Vercel
Import the repo at https://vercel.com/new. Leave the framework as **Other** and the build command empty.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.
