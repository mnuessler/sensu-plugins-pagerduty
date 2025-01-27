#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## Unreleased
- nothing

## [0.0.8]
### Changed
- Use pagerduty gem instead of redphone, now also sends description and event details when resolving

## [0.0.7] - 2015-10-29
### Changed
- handler-pagerduty: use json_config for incident key dedup_rules
- adding override from client

## [0.0.6] - 2015-07-31
### Added
- Added support for PagerDuty alert deduping.  See the Readme file for an example.

### Changed
- Updated rubocop to `0.32.1`

### Fixed
- fixed rubocop errors

## [0.0.5] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.4] - 2015-07-11
### Changed
- updated documentation links in the README and CONTRIBUTING
- set deps in gemspec and rakfile to be in alpha order
- removed unused tasks from rakefile

### Fixed
- fix binstubs to only be created for ruby files


## [0.0.3] - 2015-06-26
## Added
- added option for json_config

## [0.0.2] - 2015-06-03

### Fixed
- added binstubs

### Changed
- removed cruft from /lib
- added a new option for specifying the location of the json config file

## 0.0.1 - 2015-04-29

### Added
- initial release
