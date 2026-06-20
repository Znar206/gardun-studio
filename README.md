# Gardun Studio — Client Sites

This repo hosts:
- `/index.html` → Gardun Studio's own site
- `/_template/` → starter file for every new client build
- `/clients/` → one folder per client, each fully self-contained

Live at: `https://znar206.github.io/gardun-studio/`
(Will become `gardun.net` once the domain is bought — same structure, just repoint DNS.)

---

## Adding a new client

1. Copy `_template/` → rename to `clients/business-name` (lowercase, hyphens only, no spaces)
2. Build their site inside that folder only — never edit shared/root files for a client build
3. Update brand name, tagline, links, colors (the `--accent` CSS variable), and about text
4. Test by opening `clients/business-name/index.html` directly in a browser
5. Commit + push
6. Live at: `https://znar206.github.io/gardun-studio/clients/business-name/`
7. Generate their QR code pointing to that exact URL
8. Log it in the table below

## Editing an existing client's site

1. Find their folder name in the table below
2. Edit only files inside `clients/their-folder-name/`
3. Commit + push — changes go live in 1-2 minutes

## Naming rules (keep these consistent — this is what keeps 160 clients manageable)

- Lowercase only
- Hyphens instead of spaces (`nay-cosmetic`, not `Nay Cosmetic`)
- Business name only, no extra words (`sara-cafe`, not `sara-cafe-website`)

---

## Client tracker

| Folder name | Business | Contact | Built | Last updated |
|---|---|---|---|---|
| _(example)_ `nay-cosmetic` | Nay Cosmetic | 0770 XXX XXXX | 2026-06-22 | 2026-06-22 |

