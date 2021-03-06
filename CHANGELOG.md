# CHANGELOG - throttle

## 1.0.2 2020-03-09
### Fixed
* Fixed dependency tree and npm-shrinkwrap to only hold dependencies for production.

## 1.0.1 2020-02-03
### Fixed
* Another fix to 2g to get that right, thank you Matt! [#37](https://github.com/sitespeedio/throttle/pull/37).

## 1.0.0 2020-02-03
### Changed
* 2g speed was updated to become more usable and follow WPT [#36](https://github.com/sitespeedio/throttle/pull/36) - thank you [Matt Hobbs](https://github.com/Nooshu) for the PR.

### Added
* More pre-made profiles: dsl, 3gem, 4g, lte, edge, dial, fois [#36](https://github.com/sitespeedio/throttle/pull/36) - thank you [Matt Hobbs](https://github.com/Nooshu) for the PR.

## 0.5.4 2019-08-26
### Fixed
* Another execa fix, hopefully fixing the last thing + added more tests in Travis.

## 0.5.3 2019-08-26
### Fixed
* Over optimistic Execa upgraded caused Throttle to stop working [#32](https://github.com/sitespeedio/throttle/pull/32).

## 0.5.2 2019-08-26
### Fixed
* Updated dependencies [#31](https://github.com/sitespeedio/throttle/pull/31). 

## 0.5.1 2019-04-23
### Fixed
* Calling stop on Linux throwed error see [#20](https://github.com/sitespeedio/throttle/issues/20) and fixed by [Iñaki Baz Castillo](https://github.com/ibc), thank you!

## 0.5.0 2018-12-07
### Added
* Simplified profile/stop/help. You can now start with: ```throttle $profile``` and stop with ```throttle stop```

## 0.4.3 2018-09-01
### Fixed
* Upload throttling was wrong on Mac OS X, thank you [Paul](https://github.com/paulz) for the [PR](https://github.com/sitespeedio/throttle/pull/16).

## 0.4.2 2018-05-30
### Fixed
* Catching when ifb has already been setup.

## 0.4.1 2018-05-30
### Fixed
* Another go at trying to try/catch failing settings.

## 0.4.0 2018-05-30
### Added
* Rewrite to async/await from promises

## 0.3.0 2018-04-12

### Fixed
* Ensure setup has completed fully before returning when starting throttling with tc.
* Always return Promises from start() and stop(), even in case of errors.
* Typo in the CLI help
* Simpler way to set connectivity with tc

## 0.2.0 2017-10-31

### Added
* You can now see the version with --version
* You can now use pre defined profiles.

## 0.1.0 2017-10-13

### Fixed
* Always remove filters before we try to set them.
