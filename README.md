# pbederke.github.io

My personal website, hosted with GitHub Pages.

**Live site:** https://paulbederke.eu

## Structure

- `index.html` — single-page site (About, Research, Publications, CV, Contact)
- `imprint.html` — imprint / legal notice sub-page
- `styles.css` — editorial-style stylesheet (EB Garamond + Inter, warm off-white palette)
- `me.jpg` — portrait photo shown in the hero section (round)
- `cv.pdf` — (optional) full CV linked from the CV section
- `favicon.svg` / `favicon.ico` — site icon (figure icon, see Attributions)
- `CNAME` — custom domain configuration for GitHub Pages

## Attributions

- `favicon.svg` — "figure" icon by Brandon Lim from [Noun Project](https://thenounproject.com/browse/icons/term/figure/) ([CC BY 3.0](https://creativecommons.org/licenses/by/3.0/))

## Local preview

Just open `index.html` in a browser, or run any static server:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

Because the repo is named `pbederke.github.io`, GitHub Pages serves it automatically from the default branch. The `CNAME` file configures the custom domain, so the site is live at https://paulbederke.eu. No build step required.
