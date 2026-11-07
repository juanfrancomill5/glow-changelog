# Glow Changelog

Design → dev changelog for the Phoenix Glow app. Live site: https://juanfrancomill5.github.io/glow-changelog/

- `index.html` — the page (no build step).
- `changes.json` — the rows. Each entry: `id`, `date`, `ts` (ISO UTC), `type` (new | updated | fixed | removed | rule), `product` (Client App iPhone Glow | Client App iPhone Duo | Broker Portal), `area`, `title`, `summary`, `details[]`, `figma`, `file`.

Every design change made in the Phoenix Glow Claude project appends a row here and the site redeploys automatically.
