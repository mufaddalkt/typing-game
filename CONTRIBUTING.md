# Contributing to Typing Plane

Thanks for your interest — pull requests and ideas are very welcome!

## Quick start

The entire game is **`index.html`**. There is no build step, no bundler, no dependencies.

1. Fork the repo and create a branch.
2. Open `index.html` in a browser and play.
3. Make your change, keeping it dependency-free and single-file.

## Guidelines

- **Keep it one file.** New features should live in `index.html` (the Google Fonts import is the only external asset).
- **Test the feel.** Play a full flight on each difficulty after your change.
- **Check both themes.** Toggle your OS light/dark mode — the game adapts via `prefers-color-scheme`.
- **Check mobile widths.** The layout collapses under 850px; make sure new HUD elements still fit.
- **Respect reduced motion.** Animations should honor `prefers-reduced-motion` (a global rule already handles this — don't add motion that bypasses it).

## Ideas worth exploring

- New word packs (code keywords, other languages)
- Themes / plane skins
- Daily challenge mode
- Ghost racing against your own best flight

## Opening a PR

Describe what changed and how you tested it. Screenshots or short clips of gameplay changes are appreciated!
