# Changelog

## [0.35.8](https://github.com/GhostNoodl/Nuvio/releases/tag/v0.35.8) — 2026-10-04

- Expanded imported-title cleanup for Windows/itch/platform suffixes, archive extensions and version formats.
- Added **View → Clean up game titles** for visible games or the entire library.
- Added a selectable before/after preview with wrapping names, select all/none, Apply and Cancel.
- Bulk changes preserve game files, saves, artwork and collections, and skip titles edited after the preview opened.
- Validation: 152 automated tests passed, one skipped; build, lint, signing and packaged-runtime checks passed. Device UI acceptance remains unconfirmed.

## [0.35.7](https://github.com/GhostNoodl/Nuvio/releases/tag/v0.35.7) — 2026-10-03

- Reduced Ren'Py return-to-shelf teardown waiting after the engine acknowledges suspend/save work.
- Moved default RPG Maker touch controls inward into a compact cluster and added Escape. Existing custom layouts remain intact.
- Made automatic Windows graphics setup GPU-aware and repaired untouched legacy automatic presets.
- Added GPU/backend details and Wine errors to Windows startup reports.
- Lookouts phone/tablet launch compatibility is not yet confirmed; a possible RPG Maker exit delay remains under investigation.

## [0.35.4](https://github.com/GhostNoodl/Nuvio/releases/tag/v0.35.4) — 2026-10-03

- First public release, with Android APK, dependency source kits, notices and checksums.
- Ren'Py, RPG Maker and experimental Windows/Unity playback in one app.
- Controller and touch support, customizable shelf views, collections, sorting, artwork and import tools.
