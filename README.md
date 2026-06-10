# laurajakli.github.io

Personal academic website for Laura Jakli, Assistant Professor at Harvard Business School (BGIE unit). Built as a static site of plain HTML and CSS and served via GitHub Pages.

## Structure

- `index.html` — Home / bio
- `research.html` — Research
- `cv.html` — CV
- `assets/css/style.css` — Styles
- `assets/images/` — Images (headshot, portrait)

## Test changes locally

The site is static, so any local web server works. From the repo root:

```bash
python3 -m http.server 8080 --directory /Users/ljakli/Playspace/laurajakli.github.io
```

Then open <http://localhost:8080> in your browser. Edit the HTML/CSS files and refresh the page to see your changes.

Press `Ctrl+C` to stop the server.

## Deploying

The site is hosted on GitHub Pages. Pushing to the `main` branch publishes the live site automatically.
