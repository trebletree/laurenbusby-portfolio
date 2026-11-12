# laurenbusby.com

Lauren Busby's portfolio: a single static page. Scrolling climbs a pixel
Mount Washington from base camp to the summit.

- `index.html` holds the markup, styles, and script. There is no build step.
- `img/` and `fonts/` are loaded by relative path, so the site works at a
  domain root or in a subfolder.
- `404.html` is the not-found page.
- Visitors who prefer reduced motion get a static page.

To preview locally, serve this folder with any static server, for example
`python3 -m http.server`, and open the address it prints.
