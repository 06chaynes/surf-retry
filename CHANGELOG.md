# Changelog

## [0.3.2] - 2023-10-06

### Changed

- Fixed an issue cloning the request body causing the request body to be empty.

## [0.3.1] - 2023-08-01

### Changed

- Some dependency updates were not committed in the previous release. This release includes those updates.

- Updated the minimum versions of the following dependencies:
  - retry-policies [0.2.0]
  - chrono [0.4.26]
  - url [2.4.0]
  - wiremock [0.5.19]

## [0.3.0] - 2023-07-14

### Changed

- Set `default-features` to `false` for `surf` dependency.
- Updated the minimum versions of the following dependencies:
  - chrono [0.4.26]
  - surf-governor [0.2.0]
  - url [2.4.0]
  - wiremock [0.5.19]

## [0.2.1] - 2022-11-16

### Changed

- Updated the minimum versions of the following dependencies:
  - chrono [0.4.23]
  - retry-policies [0.1.2]
  - surf-governor [0.1.2]
  - url [2.3.1]
  - wiremock [0.5.15]

## [0.2.0] - 2022-08-04

### Changed

- Updated the minimum versions of the following dependencies:
  - async-std [1.12.0]
  - wiremock [0.5.14]

### Added

- `Default` implementation for `RetryMiddleware<ExponentialBackoff>`, with a max retries of 3 attempts, ExponentialBackoff policy of 3 attempts, and a failback interval of 1 second.

- This changelog to keep a record of notable changes to the project.
