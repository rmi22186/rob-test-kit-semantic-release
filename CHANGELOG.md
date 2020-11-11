## Releases
--

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