# Operating instructions — Max Arias

## Project

The Unnamed Archive. 42 pieces, 6 weeks, daily Instagram posts.

**Essential reading before every piece:**
- `VISUAL-DNA.md` — The aesthetic specification. All work must align with "Always" qualities and avoid "Never" qualities.
- `projects/AESTHETIC-GUIDE.md` — How to translate visual DNA into Midjourney prompts.
- `projects/PROJECT-BRIEF.md` — Project timeline and series descriptions.
- `projects/collection-v1.md` — Per-series Midjourney prompt frameworks (locked templates).

## Aesthetic Core

The work presents hypothetical artifacts as evidence, maintaining museum/archive register throughout. Every piece must:
- Show sculptural three-dimensionality and tactile surface quality
- Use neutral, clinical lighting (never warm or dramatic)
- Maintain abstraction + biomorphic suggestion (vaguely recognizable but not literal)
- Avoid narrative, decoration, or emotional gesture
- Keep scale ambiguous (no size cues)
- Use monochromatic base (limited, restrained color)

**If a piece reads as art instead of artifact, it's wrong.** Museum documentation, not gallery aesthetics.

## Caption format

Object name. Series number. Nothing else.
Example: `Vessel, fragment / II.04`

## Per-piece process

1. **Concept:** Propose a piece concept tied to its series.
2. **Prompt:** Output a Midjourney prompt using the series framework from `projects/collection-v1.md`. Read it before generating.
3. **Aesthetic validation:** Check against VISUAL-DNA.md:
   - Does it satisfy all "Always" qualities? (Museum register, sculptural form, abstraction, precision, etc.)
   - Does it avoid all "Never" qualities? (No narrative, decoration, hyper-realism, chaos, character, etc.)
   - If it drifts, rewrite the prompt before submission.
4. **Submit:** Wait for Alfred to generate the image manually.
5. **Review:** On Alfred's approval, you propose the caption.
6. **Publish:** On `ship it`, append a line to `log/published.md`: date, series, object name.

## Rejection criteria

- Reads as aesthetic or art instead of documentary → cut.
- Violates VISUAL-DNA "Always" or "Never" qualities → rewrite prompt.
- Adjective-heavy caption → rewrite.
- Visual style drifting from series or aesthetic core → flag and stop.
- Shows narrative, action, or emotional gesture → reject and reframe.
- Scale is obvious or realistic → rewrite.
- Color is saturated or decorative (unless textures series) → rewrite.

## Workflow rules

- One piece per turn unless asked.
- Read VISUAL-DNA.md before every piece. It's not a reference — it's a requirement.
- End of each week: write a short retro to `log/retros/week-NN.md`. What worked, what drifted, what to tighten.
- Track aesthetic drift in retros. If a series is losing precision, address it immediately.
- Never attempt to publish to Instagram. Alfred posts.
- Never commit secrets or session state to git.
