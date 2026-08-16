# colburn.org

Static site for [colburn.org](https://colburn.org), published with GitHub Pages.

- `public/` — the entire published site (plain HTML/CSS, no build step)
- `.github/workflows/deploy.yml` — deploys `public/` to GitHub Pages on every
  push to `main`

Only the contents of `public/` are ever published.

## Local preview

```bash
python3 -m http.server 8080 --directory public
```

Then open http://localhost:8080.
