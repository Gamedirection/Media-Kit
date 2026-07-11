# Typography

## Typeface: Raleway

The only typeface found across all GameDirection brand/press-kit source material. Use it for all brand-facing surfaces (site headings, buttons, logotype-adjacent text).

Files included in `fonts/`:

- `Raleway-Regular.ttf` - body text
- `Raleway-Medium.ttf` - emphasis, nav labels
- `Raleway-SemiBold.ttf` - subheadings, buttons
- `Raleway-Bold.ttf` - headings
- `Raleway-Italic.ttf`, `Raleway-SemiBoldItalic.ttf`, `Raleway-BoldItalic.ttf` - emphasis/quotes

Raleway is licensed under the SIL Open Font License - free to embed and redistribute. ([source](https://fonts.google.com/specimen/Raleway))

## Web Usage

```css
@font-face {
  font-family: "Raleway";
  src: url("./fonts/Raleway-Regular.ttf") format("truetype");
  font-weight: 400;
}
@font-face {
  font-family: "Raleway";
  src: url("./fonts/Raleway-Medium.ttf") format("truetype");
  font-weight: 500;
}
@font-face {
  font-family: "Raleway";
  src: url("./fonts/Raleway-SemiBold.ttf") format("truetype");
  font-weight: 600;
}
@font-face {
  font-family: "Raleway";
  src: url("./fonts/Raleway-Bold.ttf") format("truetype");
  font-weight: 700;
}

body { font-family: "Raleway", sans-serif; }
```

(For production, consider loading Raleway from Google Fonts CDN instead of shipping the .ttf files, unless the site must work fully offline/self-hosted.)

## Scale (recommended)

No official type scale exists in source material - this is a recommended default, adjust to taste:

| Role | Size | Weight |
|---|---|---|
| H1 | 48px / 3rem | Bold (700) |
| H2 | 32px / 2rem | Bold (700) |
| H3 | 24px / 1.5rem | SemiBold (600) |
| Body | 16px / 1rem | Regular (400) |
| Small / caption | 13px / 0.8125rem | Medium (500) |
| Button label | 15px / 0.9375rem | SemiBold (600), uppercase or title case |

## Don't

- Don't use a serif or monospace font for headings/buttons
- Don't mix in a second display font
- Don't set body copy below 14px
