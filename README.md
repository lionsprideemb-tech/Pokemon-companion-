# Journey Companion v2 — Inline Navigation Fix

This finalized GitHub Pages build replaces the floating Back and Home controls with an inline navigation bar that does not cover app content.

## Navigation behavior

- The navigation bar appears inside each page.
- It never floats over forms, tabs, or buttons.
- From an Archetype or other Tools page, **Back** returns to the main Tools page.
- From the main Tools page, **Back** returns Home.
- Pokémon, Pokédex, and Item detail pages return to their parent lists first.
- Professor and Campaign subpages return to their overview pages first.
- The Home button always returns directly to the final dashboard.
- `Alt + Left Arrow` uses the same reliable Back behavior.

## GitHub Pages

Upload `index.html`, `.nojekyll`, and `README.md` to the repository root, then publish from `main` and `/ (root)`.

Export a complete campaign backup before replacing the currently deployed build.
