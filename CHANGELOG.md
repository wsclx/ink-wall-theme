# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

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
