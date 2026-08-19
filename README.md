# Shubham Rathod — Portfolio

Personal portfolio site built with plain HTML, CSS, and JavaScript. No build step required.

## Preview locally

Just open `index.html` in a browser, or serve it:

```
npx serve .
```

## Deploy to GitHub Pages (free)

1. Create a new **public** repo on GitHub.
   - Name it `<your-username>.github.io` if you want the site at your root domain (e.g. `https://shubhamrathod.github.io`).
   - Or use any other repo name — the site will be served at `https://<your-username>.github.io/<repo-name>`.
2. Push this project to that repo:
   ```
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
3. On GitHub: repo → **Settings** → **Pages** → under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)` → **Save**.
4. Wait ~1 minute, then visit the URL GitHub shows on that Pages settings page.

## To-do before publishing

- Replace placeholder links (`href="#"`) in `index.html` for:
  - Featured project cards (Biki Games, Sweet Jam Blast, TileBlast, Word Fever)
  - Contact section social links (LinkedIn, GitHub, Google Play)
- Optionally add a profile photo/screenshots under an `assets/` folder and reference them in `index.html`.
