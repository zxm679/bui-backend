# Change Log

All user visible changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/), as described
for Rust libraries in [RFC #1105](https://github.com/rust-lang/rfcs/blob/master/text/1105-api-evolution.md)

## unreleased

## [0.2.0] - 2017-09-17

### Changed

* Make event URL path configurable and send events whenever prefix used
* Do not use deprecated futures .boxed() methods and BoxFuture type.
* Update to error-chain 0.11

### Fixed

* Remove compiler warnings

## [0.1.1] - 2017-09-16

### Added

* The demo checks if the browser supports EventSource and shows error if not.

### Fixed

* bui-backend permits file path configuration to be specified as an absolute
  path.

## 0.1.0 - 2017-08-13

* Initial release

[0.2.0]: https://github.com/astraw/bui-backend/compare/bui-backend/0.1.1...bui-backend/0.2.0
[0.1.1]: https://github.com/astraw/bui-backend/compare/bui-backend/0.1.0...bui-backend/0.1.1