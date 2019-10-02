# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]

## [1.0.0] - 2019-10-02
- Bump `sensu-plugin` dependency from `~> 1.2` to `~> 4.0` you can read the changelog entries for [4.0](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#400---2018-02-17), [3.0](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#300---2018-12-04), and [2.0](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#v200---2017-03-29)

### Added
- Travis build automation to generate Sensu Asset tarballs that can be used n conjunction with Sensu provided ruby runtime assets and the Bonsai Asset Index
- Require latest sensu-plugin for [Sensu Go support](https://github.com/sensu-plugins/sensu-plugin#sensu-go-enablement)

## [1.0.0] - 2017-07-26
### Breaking Change
- Remove support for Ruby 1.9.3 (@eheydrick)

### Added
- Testing on Ruby 2.4.1 (@Evesy)

### Fixed
- Fix the integration tests (@RoboticCheese)

## [0.1.0] - 2016-01-29
### Added
- Add support to `check-mailq` for inspecting each Postfix queue individually
- Add a `check-mail-delay` script to support alerting by age of queue items

### Fixed
- metrics-mailq.rb: don't output stderr when the mail queue is empty

## [0.0.3] - 2015-07-14
### Changed
- executable tag in gemspec
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-05-30
### Fixed
- executable tag in gemspec

## 0.0.1 - 2015-04-30
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-postfix/compare/1.0.0...HEAD
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-postfix/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/sensu-plugins/sensu-plugins-postfix/compare/0.0.3...0.1.0
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-postfix/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-postfix/compare/0.0.1...0.0.2
