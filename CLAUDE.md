---
district: personal-sites
status: stale
capabilities: [netlify]
last_reviewed: 2026-06-23
---

# lutomski-glass — client photo-gallery site for Lutomski Stained Glass (Denver, CO)

**Where work happens:** `index.html` · `style.css` · `main.js` · `photos/` (the gallery images)

**Skills**
- gap: shared `deploy-astro-netlify-site` skill (static deploy, `publish = "."`)

**Depends on / used by:** standalone static client site. No backend.

**Gotchas**
- Client work — confirm with Mike before content/design changes.
- Pure static, single initial build (2026-05-11). Add photos to `photos/` and reference them in the gallery; no build step.
- `netlify.toml` sets security headers (X-Frame-Options DENY etc.) — preserve them.
