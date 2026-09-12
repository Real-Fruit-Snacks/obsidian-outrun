# Changelog

## [1.5.0] - 2026-09-12

### Fixed
- Dropdowns in Settings: Obsidian's chevron was landing on top of the text.

### Changed
- Angled tabs, tags and property pills are drawn with gradients instead of `clip-path`, so they render on every Obsidian version.
- Dropped the Rajdhani 500 weight to trim the embedded fonts.

## [1.1.1] - 2026-09-12

### Changed
- Removed the last `!important` rules (settings navigation) in favour of selector specificity.

## [1.1.0] - 2026-09-11

### Added
- Day mode. Pale lavender sky, the same striped sun, deepened pink / teal / purple accents that hold contrast on light, code blocks stay as dark CRT screens. Switch with Obsidian's base colour scheme.

### Changed
- Every component now reads from mode-level variables; night and day share the whole stylesheet apart from the palette block.

## [1.0.6] - 2026-09-11

### Fixed
- Tab titles are vertically centred in the tab.

## [1.0.5] - 2026-09-11

### Fixed
- Callouts were invisible in Reading view when Obsidian's base colour scheme is Light (Obsidian multiply-blends callouts in that mode). The theme now forces normal blending.

## [1.0.4] - 2026-09-11

### Changed
- Callouts use Obsidian's stock layout with a neon skin (border, glow, tint, mono title). Removes the custom border trick that broke rendering in Live Preview.

## [1.0.3] - 2026-09-11

### Fixed
- Callouts render in Live Preview again (they get a corner-tag variant there; Reading view keeps the label-on-border style).
- Live Preview bullets no longer double up.

## [1.0.2] - 2026-09-11

### Fixed
- Tags: no seam after the `#` in Live Preview, and more padding so the text clears the angled edge.
- Bullets are drawn as pink diamonds rather than relying on a glyph.

## [1.0.1] - 2026-09-11

### Fixed
- Settings toggles: knob is now cyan so it reads in the on state, and sized with Obsidian's toggle variables so nothing overflows the track.

## [1.0.0] - 2026-09-11

### Added
- First release: deep-purple night with pink and cyan neon, striped sun and horizon grid behind notes, glowing Audiowide headings, clip-path tabs and tags, diamond checkboxes, neon callouts with corner name-tags, CRT-black code blocks, animated equaliser in the file explorer, styled settings, modals, menus, command palette, properties, graph and mobile bars. Fonts embedded (Audiowide, Rajdhani, Share Tech Mono).

[1.5.0]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.5.0
[1.1.1]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.1.1
[1.1.0]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.1.0
[1.0.6]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.6
[1.0.5]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.5
[1.0.4]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.4
[1.0.3]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.3
[1.0.2]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.2
[1.0.1]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.1
[1.0.0]: https://github.com/Real-Fruit-Snacks/obsidian-outrun/releases/tag/1.0.0
