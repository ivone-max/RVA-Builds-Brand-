# RVA Builds — Media Kit

Media kit for **RVA Builds**, the Richmond Ed Fund's citywide apprenticeship initiative for Richmond Public Schools students.

> **Start here:** open [`media-kit/index.html`](media-kit/index.html) (full scrolling kit) or [`media-kit/slides.html`](media-kit/slides.html) (14-slide presentation deck) in a browser. Downloadable versions: [`media-kit/RVA-Builds-Media-Kit.pdf`](media-kit/RVA-Builds-Media-Kit.pdf) and [`media-kit/RVA-Builds-Media-Kit.pptx`](media-kit/RVA-Builds-Media-Kit.pptx).

## What's inside

```
media-kit/
├── index.html                 ← the full scrolling media kit (open this)
├── slides.html                ← the same content as a click-through slideshow
├── assets/
│   ├── logos/
│   │   ├── horizontal/        ← primary lockup: full color + mono, light + dark backgrounds
│   │   ├── stacked/           ← stacked lockup (built for this kit — no source file existed)
│   │   ├── icon/              ← "VA" cube app icon / avatar mark
│   │   └── partner/           ← Richmond Ed Fund (parent org) endorsement lockup
│   ├── photography/           ← program photography
│   └── people/                ← leadership headshots, for quotes / press
└── docs/
    ├── palette.md              ← color palette reference
    ├── brand-tokens.css        ← drop-in CSS variables
    ├── typography.md           ← type system reference
    ├── tone-and-voice.md       ← voice attributes, writing rules, audience-specific copy
    └── boilerplate.md          ← boilerplate copy, key facts/stats, leadership quotes, media contact
```

## Logos — which file to use

| File | When to use |
|---|---|
| `logos/horizontal/rva-builds-logo-dark-color.png` | **Primary.** Full color on white / light backgrounds |
| `logos/horizontal/rva-builds-logo-light-color.png` | Full color on dark backgrounds or photos |
| `logos/horizontal/rva-builds-logo-dark.png` | Mono (black) on light backgrounds |
| `logos/horizontal/rva-builds-logo-light.png` | Mono (white) on coral / color / busy photos |
| `logos/stacked/*` | Same four variants, stacked footprint — for square/vertical placements (social avatars, signage) |
| `logos/icon/rva-builds-icon.png` | Icon only — favicon, app icon, avatar (900×900, fixed coral tile) |
| `logos/partner/richmond-ed-fund-logo.png` | Parent org endorsement — white, use on dark |

## Colors

- **Coral `#F15C2C`** — primary / action
- **Blue `#329FE6`** — Employer path
- **Purple `#7A35AE`** — Candidate path

Full palette in [`media-kit/docs/palette.md`](media-kit/docs/palette.md). Drop [`media-kit/docs/brand-tokens.css`](media-kit/docs/brand-tokens.css) into any project.

## Typography

- **Space Grotesk** — headings
- **Schibsted Grotesk** — body

Both are free (OFL) via Google Fonts. Details in [`media-kit/docs/typography.md`](media-kit/docs/typography.md).

## Tone & voice

Hopeful, trustworthy, civic, warm, data-informed, editorial — see [`media-kit/docs/tone-and-voice.md`](media-kit/docs/tone-and-voice.md) for writing rules, do/don't guidance, and audience-specific sample copy (candidates, employers, press).

## Boilerplate, key facts & quotes

Program boilerplate (short + long), key stats, sourced leadership quotes, and a media-contact placeholder are in [`media-kit/docs/boilerplate.md`](media-kit/docs/boilerplate.md).

## Still to collect from the client

- [ ] Vector logo files (**SVG**) — current files are high-res PNG only; the stacked lockups in this kit were composited from the existing raster files
- [ ] `.woff2` font files if self-hosting
- [ ] Confirmed media contact (name, title, email, phone)
- [ ] Confirmation that current program figures (students, partners, funding) are still accurate before external distribution

---

**Source of truth:** [rvabuilds.us](https://rvabuilds.us/) and [rps.fund](https://www.rps.fund/) · Assets and copy compiled from the client-provided brandbook and RVA Builds' public launch materials — not invented.
