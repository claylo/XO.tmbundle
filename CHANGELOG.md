# Change Log
All notable changes to this bundle will be documented in this file. XO.tmbundle adheres to [Semantic Versioning](http://semver.org/).

## [1.1.0] - 2015-11-25
### Added
- Support for `TM_XO` and `TM_XO_OPTIONS` environment variables to control XO's execution.
- A change log, like a civilized human being.

### Changed
- Always run with `--compact` option to make messages easier to manage.
- Switch to `TM_PROJECT_DIRECTORY` prior to running XO, so that `package.json` configuration will be recognized.
- Cursor will now move to line _and_ column of the first error found.
- Updated screenshot.png to show line-and-column-hotness.

### Fixed
- Wrap file path in quotes to avoid occasional oddities causing TextMate to open (or try to open) far more files than intended.

## 1.0.0 - 2015-10-03
- Initial release. Whee!

[Unreleased]: https://github.com/claylo/XO.tmbundle/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/claylo/XO.tmbundle/compare/v1.0.0...v1.1.0