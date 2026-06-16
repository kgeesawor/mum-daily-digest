# Mum Daily Digest Update Guide

Public page:
https://kgeesawor.github.io/mum-daily-digest/

Repo:
https://github.com/kgeesawor/mum-daily-digest

Local path:
`/Users/clawdi-mac-mini/clawd-family/mum-digest`

## Daily Update Shape

Update `index.html` in a calm, Mum-friendly way. Keep the same visual style and tabs unless the family asks for a design change.

Tabs to refresh:
- Mauritius Good News
- Canada & UK
- Checkout & Caribou
- Kushal & Shaadhvi, only if there is safe public information or family-provided context worth adding

Content rules:
- Prefer uplifting, useful, gentle stories.
- Use current and reliable sources. Prefer official sources, company newsroom pages, government pages, reputable newsrooms, or primary organization pages.
- Keep each card simple: title, short body, why Mum might like it, source label, source link.
- Do not add private Kushal or Shaadhvi context.
- Do not invent Shaadhvi role details. Use public or family-provided context only.
- Avoid heavy, frightening, political, or tragic stories unless there is a genuinely constructive, hopeful angle.
- Keep health notes gentle and non-medical.

Verification before publish:
- Run a local browser check with Playwright or equivalent.
- Confirm each tab renders and each refreshed source link exists.
- Commit and push to `main`.
- Wait for GitHub Pages to build.
- Verify the live HTML contains the refreshed content.

Daily cron should update quietly. Do not announce to WhatsApp unless the user explicitly asks for a daily notification or the job is blocked repeatedly.
