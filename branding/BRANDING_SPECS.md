# BRANDING SPECS — RY STEWART
**Last Updated:** 2026-08-04
**Source:** https://www.rystewart.com/elite-trainer-blueprint (pulled directly from live page computed styles)

---

## COLOR PALETTE

| Swatch | Name | Hex | RGB | Usage |
|--------|------|-----|-----|-------|
| ⬛ | Black | `#000000` | rgb(0, 0, 0) | Primary background (hero, video section) |
| ⬜ | White | `#FFFFFF` | rgb(255, 255, 255) | Primary text on dark backgrounds |
| 🟨 | Gold | `#FBB227` | rgb(251, 178, 39) | Primary CTA button fill |
| 🟧 | Amber/Orange | `#FFAA00` | rgb(255, 170, 0) | Secondary accent, hover/highlight states |
| 🟦 | Brand Blue | `#0E8FC5` | rgb(14, 143, 197) | Section headers, footer background, links |
| 🔷 | Navy | `#0F1A24` | rgb(15, 26, 36) | Secondary dark section background |
| ⬛ | Charcoal | `#2F2F2F` | rgb(47, 47, 47) | Body copy text |
| 🟩 | Teal | `#00C0BE` | rgb(0, 192, 190) | Minor accent (rare use) |

---

## FONTS

Extracted by parsing the embedded font files' binary `name` tables (actual font names, not the page builder's randomized asset IDs).

| Font | Weight(s) seen | Used For |
|------|----------------|----------|
| **Barlow** | 400, 700 (also 100 thin variant) | Main headline ("Turn your Instagram audience into a predictable appointment setting machine"), CTA buttons, banner text |
| **Neue Helvetica** | 700, 950 (black) | Body copy, small labels ("Trusted By Companies Such As:") |
| **Varsity Team** | 400 | Section headers (e.g. "ABOUT RY STEWART") — bold athletic/collegiate display font |
| Ridley Grotesk | — | Loaded on the page as a font asset; exact on-page usage not confirmed in this scan |

---

## USAGE PATTERN

- **Backgrounds:** Black is the dominant page background; Navy (`#0F1A24`) used for secondary dark sections; Blue (`#0E8FC5`) used as a solid section/footer background.
- **CTAs:** Buttons use the Gold (`#FBB227`) fill with black/dark bold uppercase text — this is the primary conversion color across the page.
- **Headers:** Section headings ("ABOUT RY STEWART") rendered in Brand Blue (`#0E8FC5`), bold, uppercase.
- **Body text:** White on dark backgrounds; Charcoal (`#2F2F2F`) on light backgrounds.
- **Typography feel:** Bold, condensed, all-caps headlines (Barlow / Varsity Team) paired with a clean utility body face (Neue Helvetica) — high-contrast, direct-response style.

---

## NOTES

- Colors extracted via computed-style scan of live DOM (`getComputedStyle` across all elements), cross-checked visually against page screenshots (hero section + footer).
- Fonts extracted by fetching the page's embedded font files and parsing the TTF/OTF `name` table directly (the page builder renames the asset files/CSS font-family to random IDs, so this was the only way to get the real font names).
- No official brand guideline doc existed prior to this; this is the first canonical record of the palette + fonts for reuse across decks, proposals, and specialist outputs (Canva, Google Docs, PoppyAI, etc.).
