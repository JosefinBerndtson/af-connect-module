# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2-beta]

### Fixed

- AF-Connect button now disabled while fetching session and polling for envelope. Button is re-activated upon successful envelope response, received error code or timeout.

### Added

- New configuration property "data-poll_retry" to set how many poll retry attempts to perform before exiting with error code, by default 10 retries.

### Changed

- Changed the default api-key to be "dummykey".

## [1.0.1]

### Added

- Codelist for error messages.
- Second argument `error` to `onResponse` callback invocations.
