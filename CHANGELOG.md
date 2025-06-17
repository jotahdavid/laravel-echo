# Release Notes

## [Unreleased](https://github.com/laravel/echo/compare/v2.1.6...2.x)

## [v2.1.6](https://github.com/laravel/echo/compare/v2.1.5...v2.1.6) - 2025-06-17

* Fix subscriptions not being restored on reconnect by [@electron93](https://github.com/electron93) in https://github.com/laravel/echo/pull/446

## [v2.1.5](https://github.com/laravel/echo/compare/v2.1.4...v2.1.5) - 2025-06-03

### What's Changed

* Revert CSRF logic by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/442
* Added useEchoNotification hook by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/443

**Full Changelog**: https://github.com/laravel/echo/compare/v2.1.4...v2.1.5

## [v2.1.4](https://github.com/laravel/echo/compare/v2.1.3...v2.1.4) - 2025-05-15

### What's Changed

* `channel` is now immediately available by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/435
* Type fixes in core library by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/434
* Check for import.meta.env before using Vite environment variables by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/436
* Fix channel return type by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/437

**Full Changelog**: https://github.com/laravel/echo/compare/v2.1.3...v2.1.4

## [v2.1.3](https://github.com/laravel/echo/compare/v2.1.1...v2.1.3) - 2025-05-13

### What's Changed

* Fix Reverb app key env name by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/431

**Full Changelog**: https://github.com/laravel/echo/compare/v2.1.2...v2.1.3

## [v2.1.1](https://github.com/laravel/echo/compare/v2.1.0...v2.1.1) - 2025-05-13

### What's Changed

* Fix Ably cluster error by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/429
* Make events and listeners optional by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/430

**Full Changelog**: https://github.com/laravel/echo/compare/v2.1.0...v2.1.1

## [v2.1.0](https://github.com/laravel/echo/compare/v2.0.2...v2.1.0) - 2025-05-07

* fixes: unable to build by [@fxnm](https://github.com/fxnm) in https://github.com/laravel/echo/pull/419
* Update logo by [@iamdavidhill](https://github.com/iamdavidhill) in https://github.com/laravel/echo/pull/421
* CI Improvements by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/echo/pull/424
* React/Vue Typescript Hooks by [@tnylea](https://github.com/tnylea) in https://github.com/laravel/echo/pull/422
* Final hook prep by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/426
* Added listen to `*`, stronger typing by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/echo/pull/427

## [v2.0.2](https://github.com/laravel/echo/compare/v2.0.0...v2.0.2) - 2025-02-18

- [2.x] Fix TS errors with `skipLibCheck: false` by [@SanderMuller](https://github.com/SanderMuller) in https://github.com/laravel/echo/pull/416

## v2.0.0 - 2025-02-11

- Fix TypeScript Error in `isConstructor` by [@SanderMuller](https://github.com/SanderMuller) in https://github.com/laravel/echo/pull/412
- [2.0] Major package upgrades, better TypeScript support, smaller build by [@SanderMuller](https://github.com/SanderMuller) in https://github.com/laravel/echo/pull/413
- [2.x] move tslib to dev deps by [@SanderMuller](https://github.com/SanderMuller) in https://github.com/laravel/echo/pull/414
