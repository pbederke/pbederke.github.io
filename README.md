# pbederke.github.io

My personal academic website, hosted with GitHub Pages.

**Live site:** https://pbederke.github.io

## Structure

- `index.html` — single-page site (About, Research, Publications, CV, Contact)
- `imprint.html` — imprint / legal notice sub-page
- `styles.css` — editorial-style stylesheet (EB Garamond + Inter, warm off-white palette)
- `me.jpg` — portrait photo shown in the hero section (round)
- `cv.pdf` — (optional) full CV linked from the CV section

## Editing

All content lives in `index.html`. Search for `[` to find every placeholder
(e.g. `[Your Name]`, `[Institution]`, `[Article Title]`) and replace with your
own details. The design is inspired by [glossaryoftime.com](https://glossaryoftime.com/):
serif typography, narrow measure, lots of whitespace, numbered sections, and
a muted warm palette.

## Local preview

Just open `index.html` in a browser, or run any static server:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

Because the repo is named `pbederke.github.io`, GitHub Pages serves it
automatically from the default branch at https://pbederke.github.io.
No build step required.
