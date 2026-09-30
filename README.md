# home base

The public site behind the posts: one page per build. Served by GitHub Pages from the root of
this repo (`devakmmm.github.io`).

- `index.html` — the front page, a list of builds with their state.
- `sentence-snake/` — the Sentence Snake replay page (built from the decision lab's `snake.html`).
- `.nojekyll` — serve files as-is.

Static HTML only. No build step, no analytics, no external scripts. The Snake page loads its
typefaces from Google Fonts; everything else is inline.
