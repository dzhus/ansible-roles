# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [1.0.4] - 2018-06-26
### Removed
- Elasticsearch < 2.0.0 support on debian stretch

## [1.0.3] - 2018-06-05
### Added
- Handle dependency packages to install
- Support version 6

### Changed
- Replace deprecated jinja tests used as filters
- Add curl to pretty in Goss tests to check installed version
- Replace deprecated uses of "include"
- Pass apt module packages list directly to the `name` option

## [1.0.2] - 2017-12-06
### Added
- Debian stretch support

## [1.0.1] - 2017-10-17
### Added
- Handle version (autodetect or fixed)
- Version based configurations
- Version based / distribution release requirements
- Version based tests
- Support version 5

## [1.0.0] - 2017-06-21
### Added
- Handle installation
- Handle config
- Handle services
- Handle plugins
