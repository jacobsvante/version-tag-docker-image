# Changelog

## [0.6.1](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.6.0...v0.6.1) (2024-05-30)


### Bug Fixes

* Upgrade dependencies to fix deprecation warnings ([866f4ce](https://github.com/jacobsvante/version-tag-docker-image/commit/866f4ce41a01b1a525b2068d274e1d990e2215c4))

## [0.6.0](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.5.1...v0.6.0) (2023-01-06)


### ⚠ BREAKING CHANGES

* Push `latest` tag to repo

### Features

* Push `latest` tag to repo ([29821d9](https://github.com/jacobsvante/version-tag-docker-image/commit/29821d9d970ff4a1c54bea027efa995b21cadee2))

## [0.5.1](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.5.0...v0.5.1) (2023-01-05)


### Bug Fixes

* Update to akhilerm/tag-push-action@v2.1.0 ([107803f](https://github.com/jacobsvante/version-tag-docker-image/commit/107803fcbfac5f58e5d48c53411c485b36aa4c07))

## [0.5.0](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.4.0...v0.5.0) (2023-01-05)


### Features

* Default to using docker.io as registry ([6b44813](https://github.com/jacobsvante/version-tag-docker-image/commit/6b4481395f155c1b8b179e7f7a5c01f9116582b1))


### Bug Fixes

* Deprecated use of setting output variables ([02459f8](https://github.com/jacobsvante/version-tag-docker-image/commit/02459f861df4f3e426f1671133741423a06b3537))
* Use jacobsvante/github-semver-parse ([70daaff](https://github.com/jacobsvante/version-tag-docker-image/commit/70daaffa500546c3e70e3c92e8f12faef27cb524))
* Use latest docker/login-action ([65820cd](https://github.com/jacobsvante/version-tag-docker-image/commit/65820cd2415b18b587c48c8fdbf79010d5f1c95c))

## [0.4.0](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.3.0...v0.4.0) (2022-08-24)


### ⚠ BREAKING CHANGES

* Use dashed output variables to follow input naming convention

### Features

* Ability to override GITHUB_TOKEN ([79aaf9c](https://github.com/jacobsvante/version-tag-docker-image/commit/79aaf9c275333a60cf128e8f52f63cc51817f30b))


### Bug Fixes

* Use dashed output variables to follow input naming convention ([8247264](https://github.com/jacobsvante/version-tag-docker-image/commit/8247264158f432f3639b21433fc5c7d46fa38825))

## [0.3.0](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.2.2...v0.3.0) (2022-08-14)


### Features

* Add pr_number to outputs ([be518f6](https://github.com/jacobsvante/version-tag-docker-image/commit/be518f66916a88eb58215aad2c9b47561b9201be))

## [0.2.2](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.2.1...v0.2.2) (2022-08-14)


### Bug Fixes

* Separate errors for missing PR number and missing SHA ([b591adf](https://github.com/jacobsvante/version-tag-docker-image/commit/b591adf6fd1c97eade4aca003d726b891186da8e))

## [0.2.1](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.2.0...v0.2.1) (2022-08-12)


### Bug Fixes

* Check that commit sha can be retrieved ([47568e7](https://github.com/jacobsvante/version-tag-docker-image/commit/47568e76adf917cdefb91d39c568cb8f0e432d71))

## [0.2.0](https://github.com/jacobsvante/version-tag-docker-image/compare/v0.1.0...v0.2.0) (2022-08-12)


### ⚠ BREAKING CHANGES

* Use shorter input keys

### Features

* Use shorter input keys ([592abb9](https://github.com/jacobsvante/version-tag-docker-image/commit/592abb9c0907f2aeac7d0bf7402adf6046b61f31))

## 0.1.0 (2022-08-12)


### Miscellaneous Chores

* Initial commit ([10fdeaa](https://github.com/jacobsvante/version-tag-docker-image/commit/10fdeaa79a5407cfa39a0356f08401e7f883ac0b))
