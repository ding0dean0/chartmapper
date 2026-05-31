# chartmapper

## What's in this repo

| File / Folder | Purpose |
|---|---|
| `index.html` | Kworb Weekly Chart Monitor dashboard — Atlantic Records UK Spotify weekly chart tracker |
| `reports/` | Social listening intelligence reports — one per artist, per session |

---

## Social Listening Reports

Reports live in `reports/` as paired files:

- `[artist-slug]-[YYYY-MM-DD].md` — full markdown report (machine-readable, agent-friendly)
- `[artist-slug]-[YYYY-MM-DD].html` — styled HTML preview (open in browser)

### Reports index

| Artist | Date | Markdown | HTML |
|---|---|---|---|
| Maisie Peters | 2026-05-31 | `reports/maisie-peters-2026-05-31.md` | `reports/maisie-peters-2026-05-31.html` |

---

## Generating a new report

When asked to **"run a report for [artist]"**:

1. Follow the **Social Listening Protocol** (defined in your system prompt) — minimum 12 web searches across all four phases
2. Score all dimensions based on searched evidence only — never from training knowledge alone
3. Save the completed report to two files in `reports/`:
   - `reports/[artist-slug]-[YYYY-MM-DD].md`
   - `reports/[artist-slug]-[YYYY-MM-DD].html` — use the existing HTML report as a template; update artist name, date, scores, and all content sections
4. Commit and push both files to the active branch

## HTML report template

Use `reports/maisie-peters-2026-05-31.html` as the base template for all future HTML reports. The structure, CSS, and Atlantic Records UK design system are already defined — only the content needs updating per artist.

---

## Active branch

`claude/social-listening-analyst-Z1dQU`
