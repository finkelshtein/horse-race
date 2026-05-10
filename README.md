# The Horse Race

A Quarto/HTML classroom simulation for two dice and 11 horses numbered 2 to 12.

## Files

- `_quarto.yml` — Quarto website settings
- `index.qmd` — the page with raw HTML and JavaScript
- `horse-race.css` — styling

## Render

```powershell
quarto render
```

The rendered site will appear in the `docs` folder.

For GitHub Pages, use:

- Branch: `main`
- Folder: `/docs`

## Behaviour

- `Roll once` adds one dice throw.
- `Run race (100 rolls)` runs one 100-roll race and keeps the final picture visible.
- `Run 20 races` runs 20 races.
- The right-hand columns show cumulative count and frequency across all rolls since the last Reset.
- Reset clears all race and cumulative statistics.
