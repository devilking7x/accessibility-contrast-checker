# Accessibility Contrast Checker

> Make readable color choices before they ship.

Accessibility Contrast Checker compares foreground and background colors, calculates their contrast ratio, and shows WCAG AA and AAA results beside a live preview.

## Features

- Foreground and background color pickers.
- Hex input support.
- WCAG AA and AAA checks for normal text.
- Live text and button preview.
- Local-only calculations.
- No account, upload, or tracking.

## Demo

Try the live app: https://devilking7x.github.io/accessibility-contrast-checker/

## Getting started

```bash
git clone https://github.com/devilking7x/accessibility-contrast-checker.git
cd accessibility-contrast-checker
pnpm install
pnpm dev
```

```bash
pnpm check
pnpm build
```

## Notes

The checker uses the WCAG relative-luminance formula and 4.5:1 / 7:1 thresholds for normal text. Test large text, UI components, focus states, and real content separately when reviewing a product.

## License

MIT — see [LICENSE](LICENSE).
