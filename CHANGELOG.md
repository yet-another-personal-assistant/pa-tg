# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.5.1] - 2020-03-29
### Fixed
- Convert stomp heartbeat parameters to integers

## [0.5.0] - 2020-03-29
### Added
- Command-line arguments
- Configuration file
### Removed
- TOKEN_FILE environment variable is ignored
### Changed
- Enable heartbeats on stomp connection
- Removed protocol details from README

## [0.4.0] - 2020-03-23
### Added
- Protocol description
- gitlab-ci compliance scanning
- basic testing
- xtomp connection
### Removed
- Do not respond to messages

## [0.3.0] - 2020-03-11
### Added
- Token file can now be specified in TOKEN_FILE environment variable
### Changed
- Tg-related functionality moved to a separate class

## [0.2.0] - 2020-03-09
### Changed
- The code is no longer tied to heroku
- Token should be provided in a text file
- Fixed changelog urls
### Removed
- Heroku dependencies

## 0.1.0 - 2020-02-23
### Added
- This changelog
- Initial implementation of heroku-hosted telegram bot

[Unreleased]: https://gitlab.com/personal-assistant-bot/infrastructure/pa-tg/compare/v0.5.1...master
[0.5.1]: https://gitlab.com/personal-assistant-bot/infrastructure/pa-tg/compare/v0.5.0...v0.5.1
[0.5.0]: https://gitlab.com/personal-assistant-bot/infrastructure/pa-tg/compare/v0.4.0...v0.5.0
[0.4.0]: https://gitlab.com/personal-assistant-bot/infrastructure/pa-tg/compare/v0.3.0...v0.4.0
[0.3.0]: https://gitlab.com/personal-assistant-bot/infrastructure/pa-tg/compare/v0.2.0...v0.3.0
[0.2.0]: https://gitlab.com/personal-assistant-bot/infrastructure/pa-tg/compare/v0.1.0...v0.2.0
