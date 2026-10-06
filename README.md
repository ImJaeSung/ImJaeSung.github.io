# Jaesung Lim — Personal Academic Homepage

Static academic homepage for GitHub Pages.

## Pages

- `index.html` — Home / Education / Research interests
- `publication.html` — Selected papers / ongoing work
- `experience.html` — Presentations / research projects / awards
- `assets/css/style.css` — Shared styling
- `.nojekyll` — Serve the site as plain static HTML

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy

This repository should be named exactly:

```text
ImJaeSung.github.io
```

Push to `main`, then configure:

`Settings → Pages → Build and deployment → Deploy from a branch`

- Branch: `main`
- Folder: `/(root)`

The site will be available at:

```text
https://ImJaeSung.github.io/
```

## Typical update

```bash
git add .
git commit -m "Update homepage"
git push origin main
```

## Content updates

- Home: edit `index.html`
- Publications: edit `publication.html`
- Experience: edit `experience.html`
- Design: edit `assets/css/style.css`
