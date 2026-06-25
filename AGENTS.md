# leonard-roepcke.github.io

A single-page static personal portfolio website (German). The entire app lives in `index.html` (inline CSS and vanilla JS). It is hosted via GitHub Pages.

## Cursor Cloud specific instructions

- This is a pure static site with **no dependencies, no build step, and no package manager**. There is nothing to install; the update script is a no-op.
- To run it in development, serve the repo root with any static file server, e.g. `python3 -m http.server 8000` from `/workspace`, then open `http://localhost:8000`. Opening `index.html` directly in a browser also works, but a server is preferred for testing.
- There is no separate lint/test/build tooling configured. "Testing" means loading the page and verifying sections render and the nav links smooth-scroll (Home, Über mich, Skills, Projekte, Kontakt).
