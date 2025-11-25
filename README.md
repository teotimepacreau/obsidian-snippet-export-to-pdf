# Features
- Type scale system on Minor Third for h1 to h5
- Classic serif Baskervville for work-compatible documents

# Obsidian & the hidden customization of CSS snippets in order to control PDF export formatting

Obsidian is amazing, not documenting [hidden CSS customization is not](https://forum.obsidian.md/t/pdf-export-font-style-always-glitches/55008/26) [@kepano](https://www.github.com/kepano)

In order to control the font of the exported PDF you have to tweak two CSS vars `--font-print` and `--font-text` and [use the precise name of the font as it appears installed in your OS](https://forum.obsidian.md/t/pdf-export-font-style-always-glitches/55008/32); for example "EB Garamond" won't work, it has to be the name under the font directory of the font as it is registered by your OS. Why ? It's not explained in the docs.

All CSS rules must have `!important` to take effect. It's mandatory in order to override the native Obsidian CSS that applies when exporting to PDF
