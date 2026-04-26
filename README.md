# The Unnamed Archive

A speculative visual collection presenting material evidence from pre-historic civilizations as artifact, not art. Museum documentation aesthetic. Daily Instagram posts, 42 pieces over 6 weeks.

## Team

- **Alfred** — art editor, historian, curator. Project lead.
- **Max Arias** — cultural curator (OpenClaw agent). Collection structure, curatorial framing, Midjourney prompts.

## Repo layout

- `IDENTITY.md`, `SOUL.md`, `AGENTS.md`, `USER.md` — OpenClaw bootstrap files. Define Max.
- `projects/` — project brief and prompt frameworks.
- `skills/` — OpenClaw skills (if any).
- `log/` — published pieces and weekly retros.
- `learnings/` — notes, post-mortems, what's working / drifting.

## OpenClaw wiring

Set `agents.defaults.workspace` to this directory in `~/.openclaw/openclaw.json`. OpenClaw will inject the four bootstrap files on each session.

Never commit `openclaw.json`, session transcripts, channel state, or API keys. The `.gitignore` handles this — don't disable it.
