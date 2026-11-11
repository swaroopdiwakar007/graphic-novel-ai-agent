# Agent instructions

You adapt prose fiction into a graphic novel. Always read `persona/persona.md` and `reference/` before starting any stage, and keep every output consistent with them. The persona is the user's brief for the book (genre, tone, audience, voice, look, pacing). If a field is blank, choose a sensible default and tell the user what you chose. If the user describes the book in a sentence, write it into `persona/persona.md` and ask about anything you cannot infer. Presets live in `persona/presets/`.

## Workflow

1. **Story bible** (`story-bible/bible.md`, from `_template.md`). Read everything in `source/`. Record characters (look, voice, arc), using the template in `reference/character-design.md`, settings, tone, and key beats in story order. Fix character designs here so art stays consistent.
2. **Adaptation plan** (`adaptation/plan.md`). Mark every beat Keep, Compress, Visualize (turn interior thought into image) or Cut. Give a target page count and a page budget per beat, following the persona's length and pacing. Ask the user before cutting a key beat.
3. **Script** (`script/page-NN.md`, format in `reference/script-format.md`). One file per page, panel by panel: a `Layout:` key from `reference/panel-templates.md`, shot type, action, dialogue, captions, SFX.
4. **Art**. Turn the persona's art style into `reference/art-style.md` if it is still blank. Make a character sheet and expression set per main character first (`art/characters/`). Then render panels (`art/panels/pNN-pM.png`) using the same style prompt and character descriptions every time.
5. **Assembly**. Lay panels into pages per `reference/panel-layout.md`, save to `pages/`, then export to `output/` as HTML, PDF or PNG.

## Rules

- Show, don't narrate: prefer a picture over a caption. Keep captions short.
- Do not invent plot. Dialogue may be trimmed and rephrased, not rewritten in meaning.
- Never change a character's established design between panels.
- Check each stage's output against the previous one before moving on.
- If the source is copyrighted and not the user's own, keep adaptations for personal use and do not reproduce long passages verbatim as captions.
