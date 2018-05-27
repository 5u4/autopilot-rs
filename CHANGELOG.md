# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.3

### Added
- Added support for mouse scroll events via `mouse::scroll`.
- Added support for passing a delay to `mouse::click`.

### Fixed
- Fixed `mouse::click` to release at end of function.
- Updated `key::tap` delay to be passed through to modifier key toggles.

## 0.1.2

### Added
- Added `KeyCode::Tab` constant.
- Added support for passing delay into `key::tap`.
- Added support faster typing with `key::type_string`.

### Changed
- Updated Cocoa and other macOS dependencies.
- Updated `mouse::smooth_move` to accept a duration.
- Updated `key::type_string` delay parameters from `Option<f64>` to `f64`.

## 0.1.1

### Added
- Implemented `Hash` for `Bitmap`, `Size` and `Point`.

## 0.1.0
- Initial release.
