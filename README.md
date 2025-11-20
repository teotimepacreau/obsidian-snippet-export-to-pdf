# Obsidian & the hidden customization of CSS snippets in order to control PDF export formatting

Obsidian is great, not documenting [hidden CSS customization is not](https://forum.obsidian.md/t/pdf-export-font-style-always-glitches/55008/26)

In order to control the font of the exported PDF you have to tweak two CSS vars `--font-print` and `--font-text` and use the precise name of the font as it appears installed in your OS; for example "EB Garamond" won't work, it has to be the name under the font directory of your OS. Why ? It's not explained in the docs.
