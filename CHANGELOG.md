# Changelog

All notable changes to the "language-alta" extension will be documented in this file.

## [0.1.0] - 2019-12-17
### Added
#### Syntax Highlighting
- Bitfield definitions
- Enumeration definitions
- Capture class definitions (i.e. class definitions inside a function)
- Export statements for local items
- Iterators in ranged-for loops
- Yield expressions
- Generator functions
- `protected` class item modifier
### Fixed
#### Syntax Highlighting
- Highlight aliases in `import` and `export` statements
- Highlight `this` and `super` in method calls
- Correct righthand-`this` operator-overload component highlighting

## [0.0.3] - 2019-08-28
### Added
- Syntax highlighting for the simple assignment operator (`=`) overload
- Syntax highlighting for Docca sections
### Fixed
- Lambda expressions do not require parentheses at their ends
- Compound assignment operator overloads can only appear in left-hand overloads

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
