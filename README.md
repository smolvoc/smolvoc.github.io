# smolvoc.github.io
Smolvoc's cozy website!

A plain static site (no build step) served by GitHub Pages.

- `index.html` – the home page
- `404.html` – shown for missing pages
- `assets/css`, `assets/js`, `assets/img` – styles, script and pictures
- `.nojekyll` – tells GitHub Pages to serve the files as-is

## Preview locally
```
python -m http.server 8765
```
Then open http://localhost:8765.

## Publishing
Push to `main`. In the repo on GitHub, **Settings → Pages → Build and deployment**:
Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
