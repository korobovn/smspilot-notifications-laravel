# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][keepachangelog] and this project adheres to [Semantic Versioning][semver].

## v2.1.0

### Changed

- Maximal `illuminate/*` packages version now is `6.*`

### Added

- GitHub actions for a tests running

## v2.0.0

### Changed

- Minimal `PHP` version now is `^7.1.3`
- Maximal `Laravel` version now is `5.8.x`
- Dependency `laravel/framework` changed to `illuminate/*`
- Composer scripts

### Added

- Docker-based environment for development
- Type-hinting
- Interface `SmsPilotExceptionInterface`
- Project `Makefile`

### Removed

- PHPUnit bootstrapper class

## v1.1.0

### Changed

- Maximal PHP version now is undefined
- Maximal Laravel version now is `5.7.*`
- CI changed to [Travis CI][travis]
- [CodeCov][codecov] integrated
- Issue templates updated

[travis]:https://travis-ci.org/
[codecov]:https://codecov.io/

## v1.0.3

### Changed

- CI config updated
- Required minimal PHPUnit version now `5.7.10`
- Disabled HTML coverage report (CI errors)
- Unimportant PHPDoc blocks removed
- Code a little bit refactored

[keepachangelog]:https://keepachangelog.com/en/1.0.0/
[semver]:https://semver.org/spec/v2.0.0.html
