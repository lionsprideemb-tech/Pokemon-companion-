# Journey Companion v2 — Final Back Navigation Build

This finalized GitHub Pages build adds universal internal navigation to the complete Journey Companion v2 application.

## Navigation fix

- A visible **Back** button appears on every page.
- A separate **Home** button is always available.
- The app remembers up to 80 internal navigation states.
- Back navigation restores nested pages and tabs, including:
  - Archetype Library
  - Database Center
  - Professor Operations
  - Interactive Kanto World
  - Battle Manager
  - Pokédex entries
  - Item details
  - Pokémon details
- `Alt + Left Arrow` also goes back.
- Mobile controls appear above the bottom navigation bar.

## Publish with GitHub Pages

Upload `index.html`, `.nojekyll`, and `README.md` to your repository root. Then enable GitHub Pages from `main` and `/ (root)`.

Export a complete backup before replacing your current deployed build.
