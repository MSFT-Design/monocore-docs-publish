# Monocore Docs

Static documentation site for the Monocore design system.

Single-file SPA with seven pages:

- Cold Start Pipeline
- Card — Component Spec
- Card — Design Spec
- Semantic Surface System
- Nested Elements
- Spec Completeness
- Source Libraries

## Local viewing

Open `index.html` directly in a browser, or serve the folder:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## GitHub Pages

After pushing this repo to GitHub, enable Pages under **Settings → Pages → Build and deployment**, source: `Deploy from a branch`, branch: `main` / `/ (root)`. The site will be served at `https://<user>.github.io/<repo>/`.
