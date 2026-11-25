# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.1.1] - 2026-11-25

### Fixed
- Every grey now sits on one of the 16 levels of an e-ink panel (multiples of `#111111`). Before, paper and cards fell on the same level, in light and in dark mode.
- Slider tracks and icons of unavailable entities reach 3:1 against the card (were 1.6:1 to 2.3:1).
- Heating and cooling differ on the thermostat ring (ink and light grey); error notices sit on a darker grey than warnings and information.
- Keyboard focus on a reversed tile is drawn in paper colour (with card-mod).

### Changed
- Press ripple switched off on tiles (with card-mod) and wherever the frontend reads the theme value.
- README: corrected the grey-level claim, added a note on full refreshes against ghosting, named the remaining limits, and added images of dark mode without card-mod and of the light dialog.

## [1.1.0] - 2026-11-25

### Changed
- Tiles print in reverse by state instead of by device type (with card-mod): on, open, unlocked, playing, heating or cooling, cleaning, triggered. A paused player or a locked door stays outlined.
- Badges show two inks only (with card-mod): active in full ink, inactive in grey.
- The state line of tiles is as large as the name (14 px), section headings 20 px, 12 px of paper between cards.

### Added
- Tiles of unavailable or unknown entities get a dashed rule (with card-mod).

## [1.0.0] - 2026-11-25

### Added
- First release: one theme with light and dark mode, made for e-paper and e-ink wall displays.
- Strictly monochrome: every state colour, scale, graph and energy colour of Home Assistant is mapped to a grey.
- Paper grey with 2 px ink rules, square corners, no shadows, Home Assistant's own animations switched off. Works without add-ons.
- Book serif from the system for titles and numbers, a plain sans for labels.
- Optional card-mod rules: switched-on devices become solid ink tiles, big numbers and section headings use the serif, coloured lights lose their colour in badges, the selected sidebar entry becomes an ink bar.
