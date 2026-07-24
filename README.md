# David Eby — Portfolio

Personal portfolio site for David Eby, Creative Director for film and brand campaigns.

Live at [david-eby.com](https://david-eby.com).

## About

A static single-page site built with plain HTML, CSS, and vanilla JavaScript. No framework and no build step. Videos load through a click-to-play facade (poster image plus play button, with the Vimeo or YouTube iframe swapped in only on click) so the page stays light on first load. Images are served in web-optimized sizes.

## Structure

- `index.html` — the site served at the root
- `david-eby-portfolio.html` — identical copy of the site
- `opt/` — web-optimized images and video poster frames

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Deployed on Vercel with Web Analytics enabled. Pushing to the connected project or running `vercel deploy --prod` publishes to david-eby.com.
