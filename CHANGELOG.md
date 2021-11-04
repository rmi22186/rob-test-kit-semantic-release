## [1.2.1](https://github.com/rmi22186/rob-test-kit-semantic-release/compare/v1.2.0...v1.2.1) (2021-11-04)


### Bug Fixes

* Update moduleid ([0fc8842](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/0fc8842361386ec8ae3f68c36521f82189e99b8d))

# [1.2.0](https://github.com/rmi22186/rob-test-kit-semantic-release/compare/v1.1.1...v1.2.0) (2021-11-03)


### Features

* Update module id ([#17](https://github.com/rmi22186/rob-test-kit-semantic-release/issues/17)) ([4c72050](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/4c720509b32fa212aee81c2daa37163913d7aeaf))

## [1.1.1](https://github.com/rmi22186/rob-test-kit-semantic-release/compare/v1.1.0...v1.1.1) (2021-11-02)


### Bug Fixes

* Update moduleid ([#16](https://github.com/rmi22186/rob-test-kit-semantic-release/issues/16)) ([bf38963](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/bf38963c01ddff383e6b1f9709ecffbea492dd25))

# [1.1.0](https://github.com/rmi22186/rob-test-kit-semantic-release/compare/v1.0.0...v1.1.0) (2021-11-02)


### Features

* Update module ([#15](https://github.com/rmi22186/rob-test-kit-semantic-release/issues/15)) ([5fdef93](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/5fdef93b3d83c0677951a6b430c123f4a5dae114))

# 1.0.0 (2021-11-02)


### Bug Fixes

* Update moduleid ([#14](https://github.com/rmi22186/rob-test-kit-semantic-release/issues/14)) ([1d9dd09](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/1d9dd095f0caf914c561852b73a15cc8da28b77d))
* Update package.json ([eb3169b](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/eb3169b268d0ad8542ecd0376a2bc2575842d62c))


### Features

* Implement option to switch between conversion_async and gtag ([#20](https://github.com/rmi22186/rob-test-kit-semantic-release/issues/20)) ([198e232](https://github.com/rmi22186/rob-test-kit-semantic-release/commit/198e23281870a12e09aee4cf31776c582e602352))

## Releases
--

#### 2.1.0 - 2021-10-25
* Implement Google Site Tag (GTAG) support as an opt-in feature

#### 2.0.5 - 2020-11-11
* There are no code changes in this commit. NPM published 2.0.4 but with the dist/ file from 2.0.3. This commit will include the correct dist/ file as we bump to 2.0.5

#### 2.0.4 - 2020-11-10
* Bugfix - Check window for node environments
* Bugfix - rename event --> adWordEvent

#### 2.0.3 - 2020-02-03
* Update package.json

#### 2.0.2 - 2019-10-03
* Bugfix - Remove parseInt(conversionId) which could result in NaN and data not sent to AdWords
* Turn src file into an ESM module
* Remove isObject dependency

#### 2.0.1 - 2019-08-12
* Bugfix - Refactor calculateJSHash
