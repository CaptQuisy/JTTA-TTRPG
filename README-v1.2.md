# JTTA Character Creator 1.2

Extract the entire ZIP, then open `index.html` in a modern browser. No server, installation, internet connection, or third-party dependencies are required. Keep the folders together. For GitHub Pages, publish the folder unchanged and link to its index.html.

Use the seven tabs to create a Level 1 character. Select Hindrances before Edges to determine the Edge Point budget. The review panel flags incomplete allocations. Save JSON to retain your work; load that file to resume. Print character sheet opens the browser print dialog (choose Save as PDF if desired). Portraits are embedded in saved JSON. No data is transmitted. There is no automatic persistence: save before closing.

## Maintenance
- `data/`: separate classic JavaScript data files, not fetched JSON, so file:// works.
- `js/validation.js`: derived values, budget checks and review.
- `js/creator.js`: state, UI, save/load and sheet rendering.
- `css/`: screen and print styles.

Rules source: supplied JTTA repository revision 63f4aefc07119ed3d180d7f837b132537f01f45c, 25 November 2026. Character chapters 02.0–02.7 and Equipment 03.5–03.6. Data includes 26 Backgrounds, 15 Skills, 37 Edges, 30 Hindrances and 114 equipment listings. Source descriptions are reproduced/adapted for display. See https://captquisy.github.io/JTTA-TTRPG/ for the full rules.

GM decisions: historical availability, signature item selection, issued equipment, reasonable quantities, Wealth/Poverty adjustments and campaign-specific restrictions remain subject to GM approval. The application tracks selections rather than currency. Equipment profiles and situational Edge modifiers are not automatically calculated. Custom equipment is supported; custom Backgrounds/Edges/Hindrances require editing the data files. Advancement, combat tracking and extraordinary powers are not implemented. Random generation allows swaps and rerolls; GM supervises generation. No Archetypes appear in this source's creation procedure.

Rules adapted from Journey Through the Ages by Christopher Hanson, © 2026, licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Changes: application interface, data extraction and validation. No reserved artwork included.

## Version 1.1
Edges and Hindrances are alphabetized. Equipment search supports multiple era checkboxes (OR matching, with Any-era items included); clear all to show every era. Each Serious, Critical and Lethal Wound slot has a separate condition field in the review panel, saved in JSON and displayed on the printable sheet. Older JSON saves remain compatible.

## Version 1.2
Hindrances precede Edges. Equipment cost checkboxes combine with era and text filters; no cost selection shows all costs. Print styling uses compact 9-point text and keeps Attributes, Skills and Injury Tracker together when space permits.
