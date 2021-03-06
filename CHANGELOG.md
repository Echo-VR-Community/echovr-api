# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixed
- `Team.Color.by_name` throwing an error when called with an invalid name (now
  returns `None` instead)

## [0.2.0] - 2018-11-18
### Added
- [API Documentation on Read the Docs](https://echovr-api.readthedocs.io/en/latest/index.html)
- Support for new API response properties in Echo VR Combat release patch
- `players` property on `GameSate` for listing all players in the game
- `find_team` and `find_player` methods on `GameState`
- Alias `Player#name` as `Player#username`
- `Team.Color#by_name`

## [0.1.1] - 2018-11-06
### Fixed
- Properly declare dependencies in setup.py

## [0.1.0] - 2018-11-05
### Added
- A changelog
- Shortcut methods for accessing the default API on localhost
- Concept of team colors, with special methods on the GameState and Team objects
- `Team#score` shortcut method for getting a team's score
- More extensive README documentation on how to install and use the package

### Changed
- Fix imports to work when `__init__.py` is not executed directly

## 0.0.1 - 2018-11-01
### Added
- Simple system for fetching JSON from the API
- Simple object model exposing the basic functionality of the API

[Unreleased]: https://github.com/ajedi32/echovr-api/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/ajedi32/echovr-api/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/ajedi32/echovr-api/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/ajedi32/echovr-api/compare/v0.0.1...v0.1.0
