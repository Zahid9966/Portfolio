# Portfolio

Personal portfolio website of Zahid Shaikh, a data analyst. It is a single-page, football-themed site: the sections are laid out with match vocabulary (home, profile, formation, transfers, highlights and more) and scroll smoothly from one to the next.

**Live site:** https://zahid9966.github.io/Portfolio/

## What is inside

- `index.html`: the whole site in one file (HTML, CSS and a little JavaScript, no build step)
- Smooth scrolling with [Lenis](https://github.com/darkroomengineering/lenis), loaded from the jsDelivr CDN
- Fonts from Google Fonts

Because of the CDN and font links, the page needs an internet connection to look exactly as intended.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is published with GitHub Pages from the `main` branch. Every push to `main` updates it.
