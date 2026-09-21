# design.voynich.systems

Voynich Systems web design page. Static, one HTML file, no build step.
Hosted on GitHub Pages. Not connected to Nowt or voynich.systems in any way.

- `index.html`: the page (CSS and JS inline)
- `CNAME`: the custom domain GitHub Pages serves it on
- `og.png`, `favicon.*`, `apple-touch-icon.png`: rebuild with `python _tools/build_images.py`

To change the copy, edit `index.html` and push. Pages redeploys in about a minute.
