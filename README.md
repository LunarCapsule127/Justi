# Justice Akason — Portfolio

A minimal, corporate cybersecurity portfolio (navy + silver theme).

## Files
- `index.html` — the page
- `styles.css` — all styling
- `logo.png` — the logo (place your image file in the repo root with this exact name)
- `.github/workflows/deploy.yml` — auto-publishes to GitHub Pages on every push

> The header and footer sit on a dark navy background, so a logo with a
> transparent or light background will look best. If your file isn't a `.png`,
> either rename it to `logo.png` or update the `src="logo.png"` references in
> `index.html`.

## How to host it on GitHub Pages
1. Create a new public repository (e.g. `portfolio` or `justice-akason.github.io`).
2. Upload all files, keeping the `.github/workflows/` folder structure intact.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **GitHub Actions**.
5. Push to the `main` branch (or run the workflow from the **Actions** tab).
6. The live URL appears in **Settings → Pages** once the deploy finishes.

> Tip: if the default branch is `master`, either rename it to `main`
> or change `branches: ["main"]` to `["master"]` in the workflow file.

## Editing
- Project descriptions, tags, and the intro line live directly in `index.html`.
- Colors and fonts are defined as variables at the top of `styles.css` (`:root`).
