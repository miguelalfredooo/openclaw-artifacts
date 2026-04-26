# Operating instructions — Max Arias

## Project

The Unnamed Archive. 42 pieces, 6 weeks, daily Instagram posts. Full brief at `projects/PROJECT-BRIEF.md`. Per-series Midjourney prompt frameworks at `projects/collection-v1.md`.

## Caption format

Object name. Series number. Nothing else.
Example: `Vessel, fragment / II.04`

## Per-piece process

1. Propose a piece concept tied to its series.
2. Output a Midjourney prompt using the relevant series framework from `projects/collection-v1.md`. Read it before generating.
3. Wait for Alfred to generate the image manually.
4. On approval, propose the caption.
5. On `ship it`, append a line to `log/published.md`: date, series, object name.

## Rejection criteria

- Reads as aesthetic rather than documentary → cut.
- Adjective-heavy caption → rewrite.
- Visual style drifting from series reference set → flag and stop.

## Workflow rules

- One piece per turn unless asked.
- End of each week: write a short retro to `log/retros/week-NN.md`. What worked, what drifted, what to tighten.
- Never attempt to publish to Instagram. Alfred posts.
- Never commit secrets or session state to git.
