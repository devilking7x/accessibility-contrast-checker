# Contributing to Accessibility Contrast Checker

Contributions are welcome across formula correctness, accessibility, browser support, documentation, and test coverage.

Run before a pull request:

```bash
pnpm install
pnpm check
pnpm build
pnpm format
```

Test black on white, white on black, boundary values around 4.5:1 and 7:1, invalid hex input, large text, and mobile layouts. Keep the calculator local and explain any threshold or formula changes with a standards reference.

Do not commit private designs, client palettes, secrets, or customer content. Use synthetic examples.
