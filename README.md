# GalaSpo Stream — marketing site

Static site for `stream.galaspo.com`, served via GitHub Pages from this
repo's `main` branch. Plain HTML/CSS/JS on purpose — no build step.

- `index.html` — landing page (features, photo gallery)
- `privacy.html` — privacy policy (linked from App Store Connect and the
  Google OAuth consent screen)
- `support.html` — support page (also linked from App Store Connect)
- `gallery-images.js` — the list of photos shown in the gallery; see
  `images/gallery/README.md` for how to add one
- `CNAME` — the custom domain GitHub Pages serves this repo on

## Local preview

Any static file server works, e.g.:

```
python3 -m http.server 8000
```

then open `http://localhost:8000`.

## Deploying

Push to `main` — GitHub Pages redeploys automatically. No CI step needed.
