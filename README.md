# anfra Discourse theme

Paper and ink with one violet, after `DESIGN.md` in this repo.

## Install

Admin → Customize → Themes → Install → "From your device": zip this folder
(`zip -r anfra-discourse.zip .`) and upload it, or push it to its own git repo
and install "From a git repository".

The theme brings two color schemes. Set them under the theme's settings:

- Light: **anfra Paper**
- Dark: **anfra Ink** (from the OG dark palette, DESIGN.md D3)

## Site settings (Admin → Settings → Branding)

| Setting | Value |
| --- | --- |
| logo | `https://media.holistics.io/anfra/logo/anfra-logo-default.svg` |
| logo dark | `https://media.holistics.io/anfra/logo/anfra-logo-gradient.svg` |
| logo small | `https://media.holistics.io/anfra/logo/anfra-logomark-default.svg` |
| favicon / mobile logo | `https://media.holistics.io/anfra/logo/anfra-logomark-default-tile-light.svg` (export a PNG if Discourse asks for one) |

Discourse may need the SVGs uploaded rather than linked; download them from the CDN, don't redraw them.

## What it does

- Geist and Geist Mono (`ss01` on), headings 600 with tight tracking
- Paper ground, sheet surfaces, hairline rules; the header has a hairline, no shadow
- One violet: primary buttons, unread counts, likes, active sidebar link, focus ring
- Radii: 6px chips and tags, 10px controls, 14px cards, menus and modals
- Topic list as a ruled list with mono column labels
- Menus, cards and modals: sheet, one strong edge, `e2` shadow in light, border only in dark
- Welcome banner on graph paper
- Press feedback `scale(0.97)`, hover only on fine pointers, reduced motion respected
