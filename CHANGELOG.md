# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security

## [v1.2.4] - 2020-07-18
### Added
- [2020-07-18] Added `make local` support for development builds by [@lflare].

### Fixed
- [2020-07-18] Dropped connections no longer save half-corrupted images to cache by [@lflare].

### Changed
- [2020-07-18] Properly refactored code to fit golangci-lint styles with advisory from @columna1 by [@lflare].

## [v1.2.3] - 2020-07-14
### Added
- [2020-07-14] Added image verification code by [@lflare].

### Fixed
- [2020-07-10] Fixed invalid response code for invalid tokens due to typo by [@lflare].

## [v1.2.2] - 2020-07-09
### Changed
- [2020-07-09] Add client spec version to Server header sent by client by [@lflare].

## [v1.2.1] - 2020-07-09
### Changed
- [2020-07-09] Increased WriteTimeout to 5 minutes to match token expiration timing by [@lflare].
- [2020-07-09] Bumped version number to 16 to match 1.1.5 official build by [@lflare].

## [v1.2.0] - 2020-07-05
### Added
- [2020-07-05] Added rudimentary validation of request tokens by [@lflare].
- [2020-07-05] Automatic update of client settings in the event of new fields by [@lflare].
- [2020-07-05] Added version numbers to build artifacts by [@lflare].

### Changed
- [2020-07-03] Updated README.md with relevant up-to-date information by [@lflare].
- [2020-07-03] Updated client defaults by [@lflare].
- [2020-07-04] Changed graceful shutdown timer from 15 to 30 seconds by [@lflare].
- [2020-07-04] Updated Makefile for single builds to produce static binaries by [@lflare].
- [2020-07-05] Convert `sanitized_url` to `sanitizedUrl` for better cohesion by [@lflare].

### Fixed
- [2020-07-04] Reduced aborted requests due to faulty timer updating by [@lflare].

## [v1.1.0] - 2020-07-03
### Added
- [2020-07-01] Added official CHANGELOG.md file to keep track of changes from v1.0.0 release by [@lflare].
- [2020-07-01] Simple Makefile to batch build for multiple architectures by [@lflare].
- [2020-07-01] Added badge for linking to latest release on GitHub by [@lflare].
- [2020-07-03] Preliminary check for `Cache-Control` header to pull from upstream by [@lflare].
- [2020-07-03] goreleaser for easier publishing of binaries by [@lflare].

### Changed
- [2020-07-01] Updated Makefile for proper Windows executable file extension by [@lflare].
- [2020-07-03] Upgraded lflare/diskcache-golang to v0.2.3 by [@lflare].

## [v1.0.0] - 2020-07-01
### Added
- [2020-07-01] First stable unofficial client public release by [@lflare]

[Unreleased]: https://github.com/lflare/mdathome-golang/compare/v1.2.4...HEAD
[1.2.4]: https://github.com/lflare/mdathome-golang/compare/v1.2.3...v1.2.4
[1.2.3]: https://github.com/lflare/mdathome-golang/compare/v1.2.2...v1.2.3
[1.2.2]: https://github.com/lflare/mdathome-golang/compare/v1.2.1...v1.2.2
[1.2.1]: https://github.com/lflare/mdathome-golang/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/lflare/mdathome-golang/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/lflare/mdathome-golang/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/lflare/mdathome-golang/releases/tag/v1.0.0
