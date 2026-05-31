# Changelog

All notable changes to CHRONO will be documented in this file.

---

## [β0010-STD.1.38.1 / β0010-ENH.1.40 / β0010.1.36] — All Editions (May 2026)

### Added

- **HISTORY: Add Session to Group** — "＋" button added to group header. Opens a popup to add any ungrouped session to the group without re-creating it.
- **HISTORY: Leave Group** — "↩ Leave Group" button added to each session row inside a group. Removes the session from the group individually without deleting the group.
- **HISTORY: Reorder sessions within group** — ↑↓ buttons added to sessions inside a group for manual reordering.

### Improved

- **HISTORY: CONTINUE button (▽/▼)** — Changed from blinking animation to solid on/off state. ON = filled (▼) in gold, OFF = outlined (▽) in grey. State reflected in print output.
- **HISTORY: Grip icon** — Replaced Unicode braille character (⠿) with inline SVG for consistent rendering across all environments and browsers.
- **HISTORY: Print page breaks** — Print output now breaks pages by group. Sessions within a group that exceed one page continue naturally to the next page.
- **All editions: "グループ化" → "Group"** — Group button label changed to English.

---

## [β0010-STD.1.36.2 / β0010-ENH.1.36.4 / β0010.1.34.3] — All Editions (May 2026)

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

## [β0010.1.0] — LTC EDITION (May 2026)

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

*For Japanese version, see [CHANGELOG_ja.md](CHANGELOG_ja.md)*
