# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [1.0.3] - 2018-06-05
### Added
- Handle dependency packages to install

### Changed
- Replace deprecated jinja tests used as filters
- Replace deprecated uses of "include"
- Pass apt module packages list directly to the `name` option

## [1.0.2] - 2017-12-06
### Added
- Debian stretch support

## [1.0.1] - 2017-12-01
### Fixed
- Ensure latest config changes are applied before playing roles, databases and privileges tasks (#123)

## [1.0.0] - 2017-07-17
### Added
- Handle install
- Handle config
- Handle services
- Handle roles
- Handle databases
- Handle privileges
