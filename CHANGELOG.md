# Changelog

## [3.4.0] - 2021-05-06
### Added
- #45 suport for country codes & languages

## [3.3.0] - 2021-04-07
### Added
- #48 useCaching configuration for fetching the json translation files

### Fixed
- #46 default path variables (asset dir, local asset dir, output dir)

## [3.2.1] - 2021-03-30
### Fixed
- #43 Newline documentation issue

## [3.2.0] - 2021-03-30
### Added
- #42 Migrated strict mode code
- #42 Generate strict mode code
- #36 Added support generating documentation so you can see translations in your IDE
- #37 Added config option to configure which languages should be used for generating documentation code

## [3.1.0] - 2021-03-25
### Added
- #34 Support for skipping a locale at runtime. example: only use dutch in alpha but not in beta & production

## [3.0.0] - 2021-03-07
### Added
- #32 Nullsafety implementation. Support for flutter 2.0 & dart 2.12.0
### Removed
- #32 nullsafe flag is removed because from this version we are targeting 2.12 which will use nullsafety by default

## [2.1.0] - 2021-02-09
###
- Added option to generate null safety compatible code 

## [2.0.5] - 2020-10-06
### Fixed
- #24: error when using locale_asset_path in combination with the icapps_translations package

## [2.0.4] - 2020-10-03
### Fixed
- Version bump packages

## [2.0.3] - 2020-10-03
### Added to repo
- Added travis ci integration

## [2.0.2] - 2020-10-03
### Fixed
- Android embedding v2

## [2.0.1] - 2020-10-03
### Updated
- Documentation updated 

## [2.0.0] - 2020-10-03
### Refactor
- Added support for the usage of this package in other once. Mainly because of icapps_translations
### Added
- Strict mode
- Support for a multi module architecture 

## [1.0.0] - 2020-03-28
### Added
- Localization keys support (better support for testing)
### Breaking
- isInTest => showLocalizationKeys
  Behaviour is still the same.
 
## [0.2.0] - 2019-10-13
### Added
- Test support
### Fixed
- Removed the unneeded log

## [0.1.1] - 2019-08-19
### Fixed
- Fixed documentation about arguments

## [0.1.0] - 2019-06-22
### Added
- Support for arguments

### Fixed
- Dart formatting

## [0.0.2] - 2019-06-12
### Added
- Updated README.md

## [0.0.1] - 2019-06-12
### Added
- Initial release
