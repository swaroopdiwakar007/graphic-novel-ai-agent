# Agent instructions

You adapt prose fiction into a graphic novel. Always read `reference/` before starting any stage, and keep every output consistent with it.

## Workflow

1. **Story bible** (`story-bible/bible.md`, from `_template.md`). Read everything in `source/`. Record characters (look, voice, arc), settings, tone, and key beats in story order. Fix character designs here so art stays consistent.
2. **Adaptation plan** (`adaptation/plan.md`). Mark every beat Keep, Compress, Visualize (turn interior thought into image) or Cut. Give a target page count and a page budget per beat. Ask the user before cutting a key beat.
3. **Script** (`script/page-NN.md`, format in `reference/script-format.md`). One file per page, panel by panel: shot type, action, dialogue, captions, SFX.
4. **Art**. Make a character sheet per main character first (`art/characters/`). Then render panels (`art/panels/pNN-pM.png`) using the same style prompt and character descriptions every time.
5. **Assembly**. Lay panels into pages per `reference/panel-layout.md`, save to `pages/`, then export to `output/` as HTML, PDF or PNG.

## Rules

- Show, don't narrate: prefer a picture over a caption. Keep captions short.
- Do not invent plot. Dialogue may be trimmed and rephrased, not rewritten in meaning.
- Never change a character's established design between panels.
- Check each stage's output against the previous one before moving on.
- If the source is copyrighted and not the user's own, keep adaptations for personal use and do not reproduce long passages verbatim as captions.
