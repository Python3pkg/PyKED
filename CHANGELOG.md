# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- Schema can now be split into multiple files via `!include` directive

### Fixed
- Remove Python 2.7 classifier from `setup.py`
- DataFrame output for datapoints lists with multiple compositions (i.e., a species not in all compositions)

### Changed
- Improved tests with no internet
- Improved tests with no warning

## [0.1.4] - 2017-04-21
### Added
- Add `skip_validation` keyword argument to the `ChemKED` initializer

### Removed
- Python 2.7 support is removed again

## [0.1.3] - 2017-04-13
### Added
- Add back Python 2.7 support
- Add Appveyor builds for Windows conda packages

## [0.1.2] - 2017-04-13
### Added
- Tests of the composition uncertainty in the DataPoint
- Tests of the values in the references
- Packaging for conda and PyPI
- Add Anaconda-Server badge to README

### Changed
- All fixed DOIs in CITATION.md are now specified with placeholders

## [0.1.1] - 2017-04-02
### Added
- Added Zenodo DOI badge to README
- Added CITATION file, and mention of license to README

### Fixed
- Fixed chemked-version bug in schema introduced in 0.1.0

## [0.1.0] - 2017-04-02
### Added
- First minor release of PyKED, supporting autoignition experiments.
- Basic API documentation is available via https://pr-omethe-us.github.io/PyKED/

[Unreleased]: https://github.com/pr-omethe-us/PyKED/compare/v0.1.4...HEAD
[0.1.4]: https://github.com/pr-omethe-us/PyKED/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/pr-omethe-us/PyKED/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/pr-omethe-us/PyKED/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/pr-omethe-us/PyKED/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/pr-omethe-us/PyKED/compare/75ecf67766a0be2a80e2377391fd9eca420f152c...v0.1.0
