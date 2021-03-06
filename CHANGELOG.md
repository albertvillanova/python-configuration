# Changelog
All notable changes to this project will be documented in this file.

## [0.7.0] - 2020-05-06
### Added
- New string interpolation feature

## [0.6.1] - 2020-04-24
### Changed
- Added a `separator` argument to `config` function

## [0.6.0] - 2020-01-22
### Added
- Added missing `dict` methods so a `Configuration` instance acts like a dictionary for most use cases
- Added a `reload` method to refresh a `Configuration` instance (can be used to reload a configuration from a file that may have changed).
- Added a `configs` method to expose the underlying instances of a `ConfigurationSet`

## [0.5.0] - 2020-01-08
### Added
- Support for Azure Key Vault credentials (in `config.contrib`)
- Support for AWS Secrets Manager credentials (in `config.contrib`)
- Tox support
### Changed
- Changed the `__repr__` and `__str__` methods so possibly sensitive values are not printed by default.

## [0.4.0] - 2019-10-11
### Added
- Allow path-based failures using the `config` function. 
- Added a levels option to the dict-like objects.

## [0.3.1] - 2019-08-20
### Added
- Project now builds fine on ReadTheDocs
- TravisCI support
- Codecov

## [0.3.0] - 2019-08-16
### Changed
- Changed the old behavior in which every key was converted to lower case.

## [0.2.0] - 2019-07-16
### Added
- Added Sphinx documentation
- Added a `remove_levels` parameter to the config function

## [0.1.0] - 2019-01-16
### Added
- Initial version

[Unreleased]: https://github.com/tr11/python-configuration/compare/0.7.0...HEAD
[0.7.0]: https://github.com/tr11/python-configuration/compare/0.6.1...0.7.0
[0.6.1]: https://github.com/tr11/python-configuration/compare/0.6.0...0.6.1
[0.6.0]: https://github.com/tr11/python-configuration/compare/0.5.0...0.6.0
[0.5.0]: https://github.com/tr11/python-configuration/compare/0.4.0...0.5.0
[0.4.0]: https://github.com/tr11/python-configuration/compare/0.3.1...0.4.0
[0.3.1]: https://github.com/tr11/python-configuration/compare/0.3.0...0.3.1
[0.3.0]: https://github.com/tr11/python-configuration/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/tr11/python-configuration/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/tr11/python-configuration/releases/tag/0.1.0
