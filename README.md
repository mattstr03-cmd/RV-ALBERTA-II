# RV Alberta II — OMUA

An award-style landing page for the RV Alberta II, a hydrofoil research vessel
concept for the Oceanic Marine Underwater Agency (OMUA), built in
Stormworks: Build and Rescue.

## What's here

- `index.html` — the whole site (HTML, CSS and JS in one file)
- `images/` — 50 render and diagram images
- `.nojekyll` — tells GitHub Pages to serve the folder as-is

## Publishing with GitHub Pages

1. Create a new repository on GitHub (e.g. `rv-alberta-ii`).
2. Upload everything in this folder to the repo root — `index.html`,
   the `images/` folder, `.nojekyll` and this README.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
5. Choose the `main` branch and the `/ (root)` folder, then **Save**.
6. Wait a minute, then visit `https://<your-username>.github.io/<repo-name>/`.

That's it — the site is live. Every push to the branch updates it automatically.

## Local preview

Open `index.html` directly in a browser, or from this folder run:

    python3 -m http.server 8000

then visit `http://localhost:8000`.
