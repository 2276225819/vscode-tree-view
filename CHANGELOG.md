# Change Log

## [UNRELEASED]

## [0.0.2] - 2017-12-18

### Changed

- [PHP] Removed leading `\` where `array` typehint would show as `\array`
- [PHP] Show `null` where null is used as value of arguments instead of `undefined`
- [TS/JS] Initial (go to _line only_) 'GoTo definition' on node click (@ToDo calculate the proper character offset to find the exact match)
- [TS/JS] Remove `$` from property names
- [PHP] Properly handle default value of `[]`
- [ALL] Show all imports X times, where X is the number of classes/interfaces/traits defined in the current file
- [PHP] Fix constant visibility always being public

### Added

- [TS/JS] 'Imports' section
- [General] Use TSLint

## [0.0.1] - 2017-12-17

### Added

- Initial release

### Changed

- Supported Languages: PHP, Javascript/Typescript
