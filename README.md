# Journey Companion v2 — Universal Content Pack Edition

This GitHub Pages build adds the universal Journey Companion content-pack system.

## Content Pack Center

Open **Tools → Content Packs** to create, preview, export, and import portable packs.

Supported content includes:

- Delta Pokémon
- Custom species
- Moves
- Abilities
- Items
- Trainer archetypes
- Trainer classes
- Status conditions
- Weather
- Terrain
- Rooms and field effects
- Badges
- House rules
- Tea recipes
- Pokémon foods
- NPCs
- Trainers
- Quests
- Encounters
- Gyms
- Locations
- Routes
- Factions
- Sessions
- Timeline entries

## File format

The standard extension is:

`*.jccpack`

The file contains JSON and can also be imported with a `.json` extension.

The pack format identifier is:

`journey-companion-content-pack`

## ChatGPT workflow

1. Design custom content with ChatGPT.
2. Download the generated `.jccpack` file.
3. Open **Tools → Content Packs → Import**.
4. Choose the file.
5. Imported records become available in the corresponding app tools.

## Backward compatibility

Earlier Delta Pokémon packs using the `journey-companion-delta-pokemon` format are automatically converted during import.

## GitHub Pages

Upload `index.html`, `.nojekyll`, and `README.md` to the repository root, then publish from `main` and `/ (root)`.

Export a complete campaign backup before replacing the deployed build.
