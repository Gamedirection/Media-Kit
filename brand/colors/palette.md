# Color Palette

## Confirmed Brand Colors

Sampled directly from the official logo files (not guessed).

| Token | Hex | RGB | Use |
|---|---|---|---|
| GameDirection Blue | `#00ACED` | `0, 172, 237` | Primary accent — logo mark, links, buttons, highlights |
| Black | `#000000` | `0, 0, 0` | Logo-on-black, dark backgrounds, primary dark-mode text on light |
| White | `#FFFFFF` | `255, 255, 255` | Logo-on-white, light backgrounds, primary text on dark |
| Neutral Gray | `#A6A8AB` | `166, 168, 171` | Secondary/muted gray, sampled from the reverse logo variant |
| Light Gray | `#D1D3D4` | `209, 211, 212` | Border/divider gray, sampled from the official background graphic |

## Light Mode

| Token | Hex | Role |
|---|---|---|
| `--bg` | `#FFFFFF` | Page background |
| `--surface` | `#F5F6F7` | Cards, panels |
| `--text` | `#000000` | Primary text |
| `--text-muted` | `#5B5D60` | Secondary text (derived tint of neutral gray) |
| `--border` | `#D1D3D4` | Dividers, input borders |
| `--accent` | `#00ACED` | Buttons, links, highlights |
| `--accent-contrast` | `#FFFFFF` | Text/icons on top of accent |

## Dark Mode

| Token | Hex | Role |
|---|---|---|
| `--bg` | `#000000` | Page background (matches the official reversed-logo convention) |
| `--surface` | `#141414` | Cards, panels (sampled tone from the WhiteonBlack logo file) |
| `--text` | `#FFFFFF` | Primary text |
| `--text-muted` | `#A6A8AB` | Secondary text |
| `--border` | `#2A2C2F` | Dividers, input borders |
| `--accent` | `#00ACED` | Buttons, links, highlights |
| `--accent-contrast` | `#000000` | Text/icons on top of accent, when higher contrast is needed |

> `--bg`, `--text`, and `--accent` in both modes are confirmed brand colors pulled from real assets. `--surface`, `--border`, and `--text-muted` are derived UI neutrals recommended for building a consistent interface — adjust shade as needed, but keep hue neutral (no tint other than accent blue).

## Contrast Notes

- `#00ACED` on `#FFFFFF`: ~2.6:1 — fine for large text/icons/buttons with a filled background, not for small body text.
- `#00ACED` on `#000000`: ~8.1:1 — passes AA (and AAA) for normal text.
- Always pair small accent-colored text with a solid, high-contrast background rather than placing it directly on busy imagery.
