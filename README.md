# Graphic Novel AI Agent

An agent that turns prose fiction into a graphic novel. Give it a story or novel excerpt; it returns finished comic pages.

## Pipeline

1. **Analyze** `source/` → `story-bible/` (characters, settings, tone, key beats)
2. **Adapt** → `adaptation/` (what to keep, compress, or visualize)
3. **Script** → `script/` (page-by-page, panel-by-panel)
4. **Illustrate** → `art/` (character sheets first, then panels, in one consistent style)
5. **Assemble** → `pages/` then `output/` (HTML, PDF or PNG)

## Folders

| Folder | Purpose |
|---|---|
| `reference/` | Art style, panel layout conventions, script format (the rules every stage follows) |
| `source/` | Input story or novel excerpt |
| `story-bible/` | Output of stage 1 |
| `adaptation/` | Output of stage 2 |
| `script/` | Output of stage 3 |
| `art/characters/` | Character reference sheets |
| `art/panels/` | Panel artwork |
| `pages/` | Assembled pages |
| `output/` | Final shareable files |

Start with `CLAUDE.md` for the agent's working instructions.
