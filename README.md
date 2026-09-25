# Naresh Nandigama — portfolio

A lightweight, responsive, single-page portfolio. The deployable website is in `dist/index.html`; it requires no build step.

## Add your portrait

Save your portrait as `dist/portrait-natural.jpg`. The opening section will display it automatically. A square or vertical image of at least 1000 pixels wide works best. Without it, the monogram remains visible.

## Run locally

From the project root, run `python3 -m http.server 8000 --directory dist` and open `http://localhost:8000`.

## Host elsewhere

Upload the contents of `dist/` to a static host such as GitHub Pages, Netlify, Cloudflare Pages, or Vercel. For a custom domain, connect the domain in your chosen host's settings and update its DNS records as directed there.

Edit the content and links directly in `dist/index.html`.
