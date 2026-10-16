# James Brandt's course website

This is a Quarto website published by GitHub Pages from `main:/docs`.
The STAT 386 tutorial source is `tutorial-blog/index.qmd`. Its CSV and logo
bundle are self-contained; no API credentials are needed to render the post.

Render from the repository root with:

```sh
quarto render --to html --embed-resources
```

Python requires Jupyter, pandas, and Matplotlib. Tutorial paths are relative to
the tutorial directory. Keep all plot outputs tied to the executable code chunks.
Do not add a special label for BYU or shift team coordinates to hide overlap.

Verify that all four tutorial images render, the final plot is Figure 3, the
CSV/ZIP links work, and the ZIP contains only the CSV and team logos. Re-render
`docs/` after source edits; do not edit its HTML directly. Keep `docs/.nojekyll`.

Never publish credentials, editor caches, or assignment screenshots. Preserve
the author's voice and make only requested wording changes.

Project tracking: <https://github.com/jamesebrandt/jamesebrandt.github.io/issues/1>.
