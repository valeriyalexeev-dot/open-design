# Narodnyi Front Design System

Design system for the All-Russia People's Front (ONF).

## Colors

| Token | Value | Usage |
|-------|-------|-------|
| `--color-red` | `#C00000` | Primary accent |
| `--color-red-dark` | `#8B0000` | Pressed states |
| `--color-blue` | `#004B92` | Tricolour navy |
| `--color-white` | `#FFFFFF` | Surfaces |
| `--color-black` | `#111111` | Text |

## Typography

Primary: **DIN Pro Condensed** (substitute: Barlow Condensed)
Body: **DIN Pro**

Rules: uppercase headlines, condensed display, numbers as heroes.

## Principles

1. Numbers are heroes - oversized data display
2. Condensed mandatory - DIN Pro Condensed for all headings
3. One accent - red (#C00000) only
4. Square corners - border-radius: 0 default
5. Guillemets - use `« »` never standard quotes

## Files

- `manifest.json` - project metadata
- `DESIGN.md` - full design description (Russian)
- `tokens.css` - CSS custom properties
- `tokens.json` - W3C Design Tokens format

## Usage

```html
<link rel="stylesheet" href="tokens.css">
```

```css
.btn { background: var(--color-red); color: var(--color-white); }
```
