# Site change log (read before editing index.html)

This site can be edited from more than one place at the same time. To keep each other's work:

1. **Always `git pull` / fetch the latest `index.html` from this repo before editing.** Never upload `index.html` from an old local copy; it silently undoes the other edit's changes. Edit the repo's current file in place.
2. Make small, targeted edits, then fetch and rebase right before pushing.
3. Do not bring back anything listed under "Removed on purpose".

## Removed on purpose (Nathan's request, Nov 13, 2026)
- **Build** section (parts table, process steps) and its nav link.
- **References** section and its nav link. Its content now lives in the click-a-part panels: each part has a "From the references" note (e.g. the thick padding and high cushioned ankle come from the Melo 0.1).

## Added on purpose
- **Next test** is its own section (`id="tests"`) with a full-size title and a nav link.
- "From the references" note in the part panels (`took:` field in `FEATURES`).
- Embedded business simulator in "Could it sell?" (`business-sim.html`).
- **Applied physics** section (`id="physics"`, before "Could it sell?") with a nav link: embedded physics simulator (`physics-sim.html`), same iframe pattern as the business simulator. Added Nov 17, 2026.
- "Could it sell?" relabeled as a what-if model (not real sales data); simulator page is now "business model". Embed version bumped to v=5. Nov 18, 2026.
