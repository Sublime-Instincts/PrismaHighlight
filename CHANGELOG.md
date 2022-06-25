# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2022-03-14
### Added
- Syntax highlighting for `.prisma` files.
- Quickly navigate through models, enums, types etc. defined in your schema files using `Goto Symbol`.
- Ability to comment using the standard key bindings.

## [1.0.1] - 2022-03-16
### Fixed
- Fix modifiers not being highlighted for data types in composite types.
- Fix references of other composite types not being highlighted in composite types.

## [1.1.0] - 2022-06-25
### Fixed
- Fix newlines in comments not being scoped.
- Exclude prototype from string contexts.
- Highlight `fulltext` attribute correctly.
- General syntax cleanups.

### Added
- Configure scope based code folding.
- Added some basic symbol tests for models.
