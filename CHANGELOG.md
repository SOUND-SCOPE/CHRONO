# Changelog

All notable changes to CHRONO will be documented in this file.

---

## [β0010-STD.1.36.2 / β0010-ENH.1.36.4 / β0010.1.34.3] — All Editions

### Added

- **HISTORY: Session Note** — Rich text memo per session with color, font size control
- **HISTORY: GAIN / FADER** — Per-session gain and fader value fields (displayed in HISTORY list and SETLIST right pane)
- **HISTORY: CONTINUE button (▽/▼)** — Toggle flag indicating session continues into the next; filled (▼) when ON, outlined (▽) when OFF. State reflected in print output.
- **HISTORY: Print function** — COLOR / MONO print buttons added to HISTORY toolbar. Prints the session list as a cue sheet.
- **HISTORY: Toolbar restructure** — SORT and DATA rows merged into one line for a cleaner layout.
- **SETLIST: Session info bar** — GAIN, FADER, and session note displayed in the right pane header alongside the session title. (Enhanced / LTC)

### Improved

- HISTORY lap column order: Note (✎) button moved to last column so Sound and CD columns align with headers correctly.
- SETLIST badge (+SL button) now rendered via `updateSlBadges()` for consistent display.

---

## [β0010.1.0] — LTC EDITION

### Added

- LTC (Linear Timecode) Sync — automatic session playback synchronized with Q-LAB and other timecode sources
- SETLIST + LTC Sync integration — automatic session switching driven by LTC timecode
- Keyboard shortcuts for major operations


### Included Editions

- Standard Edition β0010.10.39
- Enhanced Edition β0010.10.39
- LTC Edition β0010.1.0
- LTC Decoder α0000.8.10.17

---

## [β0010.10.39] — Standard / Enhanced Edition

### Added

- REALTIME Mode — overwrite pre-built sessions with live lap times during rehearsal (Enhanced)
- SETLIST Mode — manage and switch between multiple sessions in sequence (Enhanced)
- 2-column layout support
- Custom audio source support for countdown (PRE · 3 · 2 · 1 · GO)
- JSON export / import for session data sharing
- LAP OFFSET setting
- LABEL COLOR per lap
- rtSnapshot feature (Enhanced)


### Improved

- PREVIEW Mode stability
- HISTORY Mode grouping and sorting
- Overall UI refinements

---

## Notes

- This software is currently in **beta**. Unexpected behavior or errors may occur.
- Please verify functionality before use in live productions.
- Bug reports and feature requests are welcome via [GitHub Issues](https://github.com/SOUND-SCOPE/CHRONO/issues).

---

*For Japanese version, see [CHANGELOG_ja.md](https://github.com/SOUND-SCOPE/CHRONO/blob/main/CHANGELOG_ja.md)*
- Please verify functionality before use in live productions.
- Bug reports and feature requests are welcome via [GitHub Issues](../../issues).

---

*For Japanese version, see [CHANGELOG_ja.md](CHANGELOG_ja.md)*
