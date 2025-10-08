# Changelog

## [Unreleased] - PHP 8.1+ Compatible Fork

### Changed
- Updated PHP requirement from `^7.2` to `^7.4|^8.0|^8.1|^8.2|^8.3`
- Updated `ext-json` requirement from `^1` to `*` (removed version constraint)
- Updated `ext-simplexml` requirement from `^7` to `*` (removed PHP 7-specific constraint)
- Updated `phpunit/phpunit` from `^8` to `^9.0` for PHP 8.1 compatibility
- Replaced deprecated `fzaninotto/faker` with `fakerphp/faker` `^1.9`
- Updated `php-mock/php-mock-phpunit` from `^2.3` to `^2.6` for PHP 8+ compatibility

### Notes
- All existing tests pass with PHP 8.1
- No breaking changes to the API
- Backward compatible with PHP 7.4+

### Original Library
This is a fork of [UHIN/ccda-parser-library](https://github.com/UHIN/ccda-parser-library) version 0.1.1,
updated for PHP 8.1+ compatibility by Carefeed.

Original library last updated: May 21, 2019
