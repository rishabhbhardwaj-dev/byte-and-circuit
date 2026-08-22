# BYTE & CIRCUIT

A visual tech news preview webpage inspired by 1990s print magazine aesthetics.

**🔗 Live Site:** [rishabhbhardwaj-dev.github.io/byte-and-circuit](https://rishabhbhardwaj-dev.github.io/byte-and-circuit/)

---

## Features

- **Typography** — Playfair Display (serif) for headlines, IBM Plex Mono (monospace) for body text
- **Multi-column grid** — Varying column layouts per article (`2fr/1fr`, `1fr/1fr/1fr`, `3fr/2fr`, etc.)
- **Print overflow headline** — Masthead bleeds past the left viewport edge
- **Sepia + noise** — Images filtered with `sepia(0.2)` and SVG fractalNoise overlay
- **Page turn transitions** — CSS 3D perspective animation between sections
- **Magazine TOC** — Numbered `01`–`06` navigation with hover-enlarging digits
- **Colophon footer** — Fake ISSN, editorial staff, subscription rates, copyright boilerplate
- **Paper texture** — Fixed SVG noise layer over the entire page
- **Drop caps** — First-letter styling on article leads
- **Pull quotes** — Accent-bordered italic quotes
- **Responsive** — Adapts to mobile with single-column fallback

## Articles

| # | Title | Section |
|---|-------|---------|
| 01 | The Last Compiler | Feature |
| 02 | Silicon Dust | Investigation |
| 03 | Protocol People | Culture |
| 04 | The 10ms City | Infrastructure |
| 05 | Analog Resistance | Essay |
| 06 | Exit Velocity | Frontier |

## Stack

- Pure HTML + CSS + vanilla JavaScript
- No build tools, no dependencies, no frameworks
- Google Fonts (Playfair Display, IBM Plex Mono)
- Unsplash images (via URL)

## Preview

![Preview](Screenshot%202026-08-22%20153608.png)

## Usage

Just open `index.html` in a browser. That's it.

## License

© 2026 Circuit Press Ltd. — This is a design demo, not a real publication.
