# Nishan Chandika | Portfolio

Personal portfolio website for Nishan Chandika. This is a static site with no build step or runtime dependencies.

## Run locally

Open `index.html` with the VS Code Live Server extension, or start Python's built-in web server from this folder:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Customise
- Credly badge images: save into `assets/badges/` (file names are in the `BADGES` list near the bottom of `index.html`) and paste each badge's Credly URL there.
- Company logos are stored in `assets/logos/`.
- Hero and About photos are stored in `assets/hero/` and `assets/about/`.
- The downloadable CV is stored in `assets/cv/`.

## Deploy to Vercel
Import this repository at [Vercel](https://vercel.com/new); no build settings are needed. The static site can also be hosted with GitHub Pages.

## Search indexing

The site publishes `robots.txt` and `sitemap.xml` at the domain root. To request search indexing, verify the domain in [Google Search Console](https://search.google.com/search-console/), submit `https://nishan-chandika-portfolio.vercel.app/sitemap.xml`, and request indexing for the homepage. Search engines determine when and where pages appear; metadata and sitemap submission cannot guarantee rankings or inclusion.
