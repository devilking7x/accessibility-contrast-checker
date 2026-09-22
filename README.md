# Accessibility Contrast Checker

[![Live demo](https://devilking7x.github.io/accessibility-contrast-checker/badge.svg)](https://devilking7x.github.io/accessibility-contrast-checker/) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

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

## Who it is for

This project is designed for **designers and developers**. Its narrow first release focuses on helping them check foreground/background pairs against WCAG ratios. The interface uses realistic synthetic fixtures so the value is understandable without connecting a production account.

## Privacy and safety

The default experience is local-first: inputs are processed in the browser or in the user's own development environment, with no required account, API key, payment flow, or remote storage. Fixtures contain synthetic data only. Review a fork's hosting and analytics configuration before using it with sensitive information.

## Validation

The release workflow is intentionally reproducible. Run `pnpm install --frozen-lockfile`, `pnpm check`, and `pnpm build` before submitting a change. Manual review should cover keyboard operation, visible focus, mobile layout, empty states, and both successful and error paths.

## Limitations

This is a focused open-source MVP rather than a hosted replacement for a production system. It does not guarantee business, legal, financial, medical, accessibility, or security compliance by itself. Validate outputs against the context in which you plan to use them.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup, code style, privacy expectations, and pull-request guidance.

## License

Released under the [MIT License](LICENSE).
