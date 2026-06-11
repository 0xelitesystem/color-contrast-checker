# Color Contrast Checker

A single-file browser tool that takes a text color and a background color and reports the contrast ratio between them, checked against the WCAG 2.1 thresholds for normal and large text at AA and AAA, with a live preview of the two colors together.

**Live demo:** https://0xelitesystem.github.io/color-contrast-checker/

It runs entirely in the browser. Nothing is uploaded, stored, or tracked.

## What it shows

- The contrast ratio, from 1 to 21
- Pass or fail for AA normal, AA large, AAA normal, and AAA large text
- A live swatch showing the text color on the background color
- A plain-language note on where the pair is safe to use

## How to use

Open `index.html` in any browser, or visit the GitHub Pages URL. Pick each color with the swatch or type a hex value, and the ratio and the pass or fail chips update live. Use the swap button to flip text and background. Large text means roughly 24px and up, or 18.66px and up if bold.

## Notes

The ratio uses the standard WCAG relative-luminance formula. AA requires at least 4.5 for normal text and 3 for large; AAA requires at least 7 for normal text and 4.5 for large.

## License

MIT. Copyright (c) 2026 0xelitesystem.
