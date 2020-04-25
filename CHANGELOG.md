# Changelog

The changelog documents all notable changes to this project. The format is based
on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) as defined
by [Cargo](https://doc.rust-lang.org/cargo/reference/manifest.html#the-version-field)
and [Rust](https://github.com/rust-lang/rfcs/blob/master/text/1105-api-evolution.md).

## [Unreleased]

### Changed

- Rewrite workflow in [Rust](https://rust-lang.org)

### Removed

- Remove dependency on `git` executable in path

## [1.1.0] - 2017-11-26

### Fixed

- Update dependency to fix bug in [macOS Sierra and later](https://github.com/deanishe/alfred-workflow/issues/111)

## [1.0.0] - 2015-11-25

### Added

- Release a workflow that can create `.gitignore` files from Alfred

[unreleased]: https://github.com/jdno/alfred-gitignore/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/jdno/alfred-gitignore/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/jdno/alfred-gitignore/releases/tag/1.0.0