# Change Log

All notable changes to the "language-alta" extension will be documented in this file.

## [0.0.2] - 2019-08-27
### Added
- Syntax highlighting for some Docca annotations
- Syntax highlighting for constants (based on letter case)
### Fixed
- Function definitions and declarations can now span multiple lines
- Multiline function calls will now have their accessors correctly highlighted (as functions)
- The `any` primitive type is now correctly highlighted like other primitive types
### Changed
- Scope names for attributes have changed to make them stand out more
  - The old scope (`variable.annotation`) isn't highlighted distinctly from `variable` in most themes

## [0.0.1] - 2019-08-27
- Initial release
### Added
- Syntax highlighting for all current (as of [5fde2c7](https://github.com/alta-lang/alta/commit/5fde2c7a1bb383037142f5c7a9e306cc08890143)) Alta syntax
