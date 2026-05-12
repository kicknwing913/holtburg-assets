# holtburg-assets

Public asset CDN for [Holtburg Hollow](https://github.com/kicknwing913/holtburg-hollow) / Caelvars Crest: The Hollow Path, a browser MMO project.

Served via GitHub Pages: https://kicknwing913.github.io/holtburg-assets/

## Structure

- `character/` — player character body + Mixamo animation GLBs (1 body + 15 anims)
- `buildings/` — Quaternius/Kenney architecture GLBs
- `npcs/` — NPC character body GLBs
- `mobs/` — hostile creature GLBs
- `props/` — decorative environment GLBs
- `audio/` — music, SFX, ambience (deferred)
- `test/` — pipeline verification assets

## Source & licensing

- `character/` — generated from Mixamo (Paladin J Nordstrom), subject to Mixamo free-use terms. Build pipeline: `convert.py` (local-only, gitignored) batch-converts the FBX sources in `raw/` (also gitignored) to GLB via Blender.
- Everything else — CC0 or otherwise licensed for use in Caelvars Crest.
