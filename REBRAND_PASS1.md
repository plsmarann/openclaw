# Rebrand Pass 1

This repository has been rebranded at the identity layer while keeping runtime compatibility.

## Completed

- Project metadata renamed to `maranclaw` in `package.json`.
- Added CLI alias `maranclaw` (existing `openclaw` command remains supported).
- README branding updated from OpenClaw to MaranClaw.
- README repository/badge/clone links updated to `plsmarann/openclaw`.
- `.env.example` header updated with compatibility note.
- Local git remotes changed:
  - `origin` -> `https://github.com/plsmarann/openclaw.git`
  - `upstream` -> `https://github.com/openclaw/openclaw.git`

## Intentionally deferred (Pass 2+)

- Internal package scope renames (for example `openclaw/*` paths and imports).
- Config/state path migration from `~/.openclaw` to a new home.
- Mobile bundle IDs and app display names.
- Docker image/env key renames (`OPENCLAW_*`).
- Docs domain replacement from upstream docs hosting.

