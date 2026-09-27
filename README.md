# wander-cli

Publish blog posts and upload trip photos from the terminal. Small, opinionated,
mine. ☕

```bash
wander login
wander post drafts/el-jem.md --album "tunisia-2025"
```

## Configuration

`wander-cli` reads a `.env` from the working dir. **Don't commit real secrets** —
`.env` is git-ignored. Copy `.env.example` to `.env` and fill in your own values.

For reference, my own **staging** `.env` lives in a gist (kept out of this repo on
purpose)

- staging env (gist): https://gist.github.com/alexrivera-travels/a48339801a01759cb685f60fbfe0b73a

## Status

Rebuilding docs. The `.env.example` here is a **placeholder only** — not a real
credential.
