# cv.bf.wtf

Ben Follington's CV. Served by GitHub Pages from the `gh-pages` branch (see `CNAME`).

## Editing

Edit the HTML directly. There is no build step.

- `index.html` — the CV itself
- `doublejump.html`, `pck.html`, `runrundie.html`, `umh.html`, `usn.html` — project pages
- `build.css` — styles for every page, hand-edited
- `img/` — project screenshots
- `thesis.pdf` — linked from the CV

Push to `gh-pages` and it's live.

## History

This used to be generated from Pug templates and Sass (`src/`, via `npm run build`).
That pipeline was abandoned years ago — the HTML was edited by hand from then on and
the templates rotted, so regenerating would have silently reverted real content. The
`src/` tree, `package.json` and lockfiles were removed in favour of the files above.

`build.css` keeps its name from that era; it's a normal stylesheet now, not an artifact.
