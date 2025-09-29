# # Tailwind-based Static Portfolio (CDN)

This repository is a Tailwind-based static portfolio using the Tailwind Play CDN — no build step required. Drop your images into `assets/`, update the text in `index.html`, then publish with GitHub Pages.

## Files
- `index.html` — main page (uses Tailwind CDN)
- `styles.css` — minimal extra CSS
- `assets/` — add `avatar.png`, `project-1.png`, `project-2.png`
- `404.html` — custom 404 page
- `.nojekyll` — empty file

## Publish on GitHub Pages
1. Create a new GitHub repository and push these files to `main`.
2. In repo Settings → Pages: choose `main` branch / root → Save.
3. The site should be available at `https://<username>.github.io/<repo>/`

## Optional: Build locally with Tailwind (if you want to switch from CDN)
A `optional-build/` folder contains `package.json` and `tailwind.config.js`. Run:
```bash
cd optional-build
npm install
npm run build
