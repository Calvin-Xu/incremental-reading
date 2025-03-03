# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

## [4.12.0] - 2024-12-30

### Fixed
- Don't switch to deck browser after import (#38).
- Properly handle importing a page when title is missing (#34).
- Missing About menu on OSX (#47).

### Changed
- Various improvements to development process (#43).

### Removed
- Remove `maxWidth` configuration as this should be part of the card's CSS. New
users will have the correct CSS, but existing users might need to manually
update their Card template's CSS to
https://github.com/tvhong/incremental-reading/blob/main/ir/web/model.css


## [4.11.9] - 2023-03-05

### Added
- Add ability to import Epub files (lujun9972@).

### Fixed
- Fix compatibility with 23.10 (lujun9972@, khonkhortisan@, tvhong@).

## [4.11.8]

### Fixed
- Use resolved title from Pocket when import from Pocket (contribution by lujun9972@).

## [4.11.7]

### Fixed
Fix bug for first time user creating IR cards.

## [4.11.6]

### Fixed
- Fix bug in enabling priority queue.

## [4.11.5]

### Fixed
- Fix images and named anchors importing.

## [4.11.4]

### Fixed
- Fix HTTPS imports in MacOS.

## [4.11.3]

### Removed
- Remove deprecated imports from Anki 2.1.54.