---
order: 100
title: Change Log
type: Other
---

NG-ALAIN strictly follows [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/).

#### Release Schedule

* Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
* Monthly release: minor version at the end of every month for new features.
* Major version release is not included in this schedule for breaking change and new features.

---

# [14.0.0](https://github.com/ng-alain/delon/compare/13.5.2...14.0.0) (2022-08-27)

### Bug Fixes

* **abc:se:** fix missing error style ([#1517](https://github.com/ng-alain/delon/issues/1517)) ([c01e3de](https://github.com/ng-alain/delon/commit/c01e3de016a3beaf241c2d94b2e034b71b7b60d9))
* **form:** fix width style ([#1504](https://github.com/ng-alain/delon/issues/1504)) ([8ab8956](https://github.com/ng-alain/delon/commit/8ab89562255b561f2582f85ef9aa81b69e754e88))
* **forum:array:** fix invalid `minItems` ([#1511](https://github.com/ng-alain/delon/issues/1511)) ([923d4f4](https://github.com/ng-alain/delon/commit/923d4f40c4ee43a17e159f95e355478aaeb6cf6b))
* **theme:model** fix missing `xl` style in vertical ([#1506](https://github.com/ng-alain/delon/issues/1506)) ([5e1edee](https://github.com/ng-alain/delon/commit/5e1edeef6c8123b6a730006db337501b086cb874))
* **theme:MenuService** fix hide when all children has hidden ([#1507](https://github.com/ng-alain/delon/issues/1507)) ([50f35a9](https://github.com/ng-alain/delon/commit/50f35a96120c7fca746bf4b4795d93e4ee78535e))

### Features

* **abc:observers:** add `[observeSize]` directive ([#1501](https://github.com/ng-alain/delon/issues/1501)) ([8bebd30](https://github.com/ng-alain/delon/commit/8bebd30e7d32a8a2c5068a787b993a28330fd3f1))
* **abc:pdf:** add `eventBus` property ([#1492](https://github.com/ng-alain/delon/issues/1492)) ([57f340f](https://github.com/ng-alain/delon/commit/57f340f497451e3548893fe6cf2726a349a46735))
* **abc:reuse-tab:** add `canClose` property ([#1497](https://github.com/ng-alain/delon/issues/1497)) ([347745a](https://github.com/ng-alain/delon/commit/347745ae2f7faa0c6a3780b62a422021fa424b7c))
* **abc:reuse-tab:** support status of the last browser closed ([#1493](https://github.com/ng-alain/delon/issues/1493)) ([94f2986](https://github.com/ng-alain/delon/commit/94f2986413a01ab658c861866d77cc529a4c5e0d))
* **abc:st:** add function of `reName` ([#1500](https://github.com/ng-alain/delon/issues/1500)) ([9a0c96e](https://github.com/ng-alain/delon/commit/9a0c96eed22436a566221943fe01dfa520bbbccf))
* **abc:st:** add whether to ignore `null` or `undefined` value ([#1515](https://github.com/ng-alain/delon/issues/1515)) ([4747bcd](https://github.com/ng-alain/delon/commit/4747bcdc476ee819bc229b52823fed1f5349be67))
* **form:select:** add `hide` property ([#1516](https://github.com/ng-alain/delon/issues/1516)) ([6df7c38](https://github.com/ng-alain/delon/commit/6df7c389b505a71667f71b96d05e818676172537))
* **form:** add `visibleIfLogical` logical type ([#1496](https://github.com/ng-alain/delon/issues/1496)) ([7af1397](https://github.com/ng-alain/delon/commit/7af13975d93a856fcbb5195bd9da3d2cf0fddf68))
* **theme:title:** add `selector` property ([#1487](https://github.com/ng-alain/delon/issues/1487)) ([b15f35f](https://github.com/ng-alain/delon/commit/b15f35f6603402595c59ec1b8b38703c4c4da2aa))
* **theme:** add `ALLOW_ANONYMOUS`, `CUSTOM_ERROR`, `IGNORE_BASE_URL`, `RAW_BODY` ([#1486](https://github.com/ng-alain/delon/issues/1486)) ([4a6755e](https://github.com/ng-alain/delon/commit/4a6755ef078275ee3ae4cd996570cd9259ab5aec))
* **util:** add `omit` ([#1519](https://github.com/ng-alain/delon/issues/1519)) ([15bb062](https://github.com/ng-alain/delon/commit/15bb062240d282e7635bea90cdff31d732618d40))
* **theme:MenuService** allow control open via service ([#1507](https://github.com/ng-alain/delon/issues/1507)) ([50f35a9](https://github.com/ng-alain/delon/commit/50f35a96120c7fca746bf4b4795d93e4ee78535e))

### BREAKING CHANGE

* **theme:MenuService** `collapsed` instead of `open` ([#1507](https://github.com/ng-alain/delon/issues/1507)) ([50f35a9](https://github.com/ng-alain/delon/commit/50f35a96120c7fca746bf4b4795d93e4ee78535e))

## Old Versions

All releases notes can be found [here](https://github.com/ng-alain/ng-alain/releases).
