# Terra Impact website

Static one-page site for Terra Impact (terraimpact.net), built with plain HTML/CSS/JS — no build step, no framework. Hosted on GitHub Pages.

## Structure

- `index.html` — all page content and sections
- `style.css` — all styling
- `script.js` — mobile nav toggle + footer year
- `assets/` — logo, favicons, hero photos
- `CNAME` — tells GitHub Pages to serve this repo at `terraimpact.net`

## Local preview

Open `index.html` directly in a browser, or run a tiny local server from this folder:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deploying

See the setup guide provided alongside this project for connecting GitHub Pages to the `terraimpact.net` domain on Namecheap.
