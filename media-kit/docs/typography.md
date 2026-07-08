# RVA Builds — Typography

Both faces are open-source (SIL OFL) and free to self-host. Already used on the brand site.

## Typefaces

| Role | Font | Where to get it | Weights |
|---|---|---|---|
| Display / Headings | **Space Grotesk** | https://fonts.google.com/specimen/Space+Grotesk | 500, 600, 700 |
| Body / UI | **Schibsted Grotesk** | https://fonts.google.com/specimen/Schibsted+Grotesk | 400, 700 |

Fallback stack: `"Helvetica Neue", Helvetica, Arial, sans-serif`

```css
--font-display: "Space Grotesk", "Helvetica Neue", Arial, sans-serif;
--font-body:    "Schibsted Grotesk", "Helvetica Neue", Arial, sans-serif;
```

Self-host via `@fontsource/space-grotesk` and `@fontsource/schibsted-grotesk`.
To download the `.woff2` files, place them in an `04-fonts/` folder next to this one (see checklist in the root README).

## Type scale (1.250 major-third, 16px base)

| Role | Size | Font | Weight |
|---|---|---|---|
| Display / Hero | 48–64px (clamp) | Space Grotesk | 700 |
| H1 | 40px | Space Grotesk | 700 |
| H2 | 32px | Space Grotesk | 600 |
| H3 | 24px | Space Grotesk | 600 |
| Body large | 20px | Schibsted Grotesk | 400 |
| Body | 16px | Schibsted Grotesk | 400 |
| Caption / meta | 14px | Schibsted Grotesk | 400 |

## Rules

- Headings in Space Grotesk; running text and UI in Schibsted Grotesk. Don't mix.
- Line-height ~1.15 for display/headings, ~1.5 for body.
- Sentence case for headings (civic, warm — not shouty all-caps).
