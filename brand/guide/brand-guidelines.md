# GameDirection Brand Guidelines

For the visual version of this document, open [`index.html`](index.html) in a browser.

## Logo

- Primary mark: `brand/logo/primary/gamedirection-logo.svg` (also `.png`) - full color, blue mark.
- Reverse variants: `brand/logo/reverse/` - white-on-black, black-on-white, and blue-on-transparent, for use on dark or light backgrounds.
- Icon/favicon: `brand/logo/icon/` - icon-only mark plus a full favicon set (16x16 up to 512x512, plus `.ico`).
- Motif: `brand/logo/motif/` - the mark is built from circular/orbiting parts (center dot, exterior circle, directional arrows). This circular language is the source for the rounded-corner rule below - it's not an arbitrary UI choice, it's an extension of the mark itself.

### Clearspace & Minimum Size

- Keep clearspace around the logo equal to at least the height of the circular mark on all sides - don't let text or other graphics enter that zone.
- Don't scale the full logo below ~120px wide for web use; below that, use the icon-only mark instead.

### Color Rules

- The mark appears in brand blue (`#00ACED`), pure white, or pure black only. See `brand/colors/palette.md`.
- On dark/black backgrounds, use the white or blue reverse variant - never place a low-contrast color combination.
- On light/white backgrounds, use the full-color or black mark.

## Don't (Logo)

- Don't recolor the mark to a non-brand color.
- Don't stretch, skew, or rotate the logo.
- Don't add drop shadows, outlines, or gradients beyond what ships in the source files.
- Don't place the mark on busy photographic backgrounds without a solid-color safe area behind it.
- Don't recreate or approximate the mark - always use the provided files.

## Color

See [`../colors/palette.md`](../colors/palette.md) for full light/dark token tables. Short version: brand blue `#00ACED`, black `#000000`, white `#FFFFFF`, neutral grays `#A6A8AB` / `#D1D3D4` for UI chrome.

## Typography

See [`../typography/typography.md`](../typography/typography.md). Typeface is Raleway, all weights included.

## Shape Language: Rounded, Not Sharp

Because the mark itself is built from circles, UI built around the GameDirection brand should favor **rounded corners and circular accents** over sharp, squared-off edges.

Recommended defaults (no official spec exists - these are sensible defaults derived from the logo, adjust as needed):

| Element | Radius |
|---|---|
| Buttons | 999px (fully pill-shaped) or 12px minimum |
| Cards / panels | 16px |
| Input fields | 10px |
| Avatars / profile images | Circular (50%) |
| Images / hero graphics | 12–20px |

### Buttons

- Primary button: filled `--accent` background, white text, pill or 12px+ radius, no hard corners.
- Secondary button: outlined in `--border` or `--accent`, transparent/`--surface` background, same radius as primary.
- Hover/active states: slightly darken/lighten the fill, don't change the shape.

## Don't (UI)

- Don't use sharp, unrounded corners on buttons, cards, or inputs.
- Don't introduce a second accent color - blue is the only accent.
- Don't use a serif or monospace typeface anywhere in the brand surface.
- Don't set brand-blue text at small sizes directly on white (contrast is borderline - see palette notes); use it for large text, icons, or filled buttons instead.

## Photography / Imagery Style

- Project hero art (see `projects/*/hero.png`) is illustrated/stylized, not photographic - favor illustrated game art over generic stock photography when representing GameDirection projects.
- Team photography may be photographic (see `company/team.md`).
