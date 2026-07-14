# RVA Builds — Typography

Both faces are standard Google Workspace fonts — no self-hosting or menu-hunting required.

## Typefaces

| Role | Font | Where to get it | Weights |
|---|---|---|---|
| Display / Headings | **Montserrat** | https://fonts.google.com/specimen/Montserrat | 500, 600, 700 |
| Body / UI | **Lato** | https://fonts.google.com/specimen/Lato | 400, 700 |

Fallback stack: `"Helvetica Neue", Helvetica, Arial, sans-serif`

```css
--font-display: "Montserrat", "Helvetica Neue", Arial, sans-serif;
--font-body:    "Lato", "Helvetica Neue", Arial, sans-serif;
```

Both are available directly in Google Docs, Slides, and Sheets font menus. To self-host instead, use `@fontsource/montserrat` and `@fontsource/lato`, placing the `.woff2` files in an `04-fonts/` folder next to this one (see checklist in the root README).

## Type scale (1.250 major-third, 16px base)

| Role | Size | Font | Weight |
|---|---|---|---|
| Display / Hero | 48–64px (clamp) | Montserrat | 700 |
| H1 | 40px | Montserrat | 700 |
| H2 | 32px | Montserrat | 600 |
| H3 | 24px | Montserrat | 600 |
| Body large | 20px | Lato | 400 |
| Body | 16px | Lato | 400 |
| Caption / meta | 14px | Lato | 400 |

## Rules

- Headings in Montserrat; running text and UI in Lato. Don't mix.
- Line-height ~1.15 for display/headings, ~1.5 for body.
- Sentence case for headings (civic, warm — not shouty all-caps).
