# Changelog
All notable changes to this project will be documented in this file.  
This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

A list of unreleased changes can be found [here](https://github.com/SAP/ui5-project/compare/v0.2.5...HEAD).

<a name="v0.2.5"></a>
## [v0.2.5] - 2018-12-18
### Bug Fixes
- **npm translator:** Deduplicate subtrees of pending dependencies [`7e55ae3`](https://github.com/SAP/ui5-project/commit/7e55ae3d88280746f5800bffc7bbd13e1495ba07)
- **npm translator:** Fix handling of indirect dependency cycles [`c99d6d3`](https://github.com/SAP/ui5-project/commit/c99d6d3a19fbb6c197b449dfd6cb8acc48837dba)

### Internal Changes
- **npm translator:** Ignore packages that can't be read [`d8c2354`](https://github.com/SAP/ui5-project/commit/d8c23545fd8f1180f988417a9c8cee880b668415)
- **npm translator:** Add silly debug logging [`1ae0d5d`](https://github.com/SAP/ui5-project/commit/1ae0d5dbc9ec9630cd405e108529cab83bc87347)
- **npm translator:** Add addtl. test for cyclic dependencies [`299eb2a`](https://github.com/SAP/ui5-project/commit/299eb2af0472ecf9bf79b96895a2864667b535bf)


<a name="v0.2.4"></a>
## [v0.2.4] - 2018-12-17
### Bug Fixes
- **npm t8r:** Add deduplication of npm dependencies [`2717088`](https://github.com/SAP/ui5-project/commit/2717088532d415b6922f290b58d9227b946a965f)
- **projectPreprocessor:** Ignore deduped modules [`84f7b25`](https://github.com/SAP/ui5-project/commit/84f7b25a9e45df3bc55a7957e4f61db580e68509)

### Internal Changes
- Add tests for cyclic dependency handling [`0378b77`](https://github.com/SAP/ui5-project/commit/0378b77406107294acb3a0103eb6a3464d129be1)
- UA Review README.md [`dd64ff5`](https://github.com/SAP/ui5-project/commit/dd64ff58099d2d21d59a1fe0b05ae7a7e416a5df)
- **npm t8r:** Add includeDeduped option [`eaa2863`](https://github.com/SAP/ui5-project/commit/eaa2863c506f98e011bc0a78776d0f4d61c506d6)
- **static translator and normalizer:** Add tests [`595936d`](https://github.com/SAP/ui5-project/commit/595936d97379bd2ab92967dc7e7e1f568374e4db)


<a name="v0.2.3"></a>
## [v0.2.3] - 2018-11-20
### Bug Fixes
- **npm t8r:** Again, handle npm optionalDependencies correctly [`9fd78dc`](https://github.com/SAP/ui5-project/commit/9fd78dca4d836f9a37036fd151a78e9295b28aa1)

### Internal Changes
- **npm t8r:** Prevent re-throwing own errors [`63f15d3`](https://github.com/SAP/ui5-project/commit/63f15d320b67249c81394d4d4508e83d403e9230)
- **npm t8r:** Handle projects with explicitly zero UI5 dependencies [`7fe6269`](https://github.com/SAP/ui5-project/commit/7fe626943b8a6a4bb53b3e43c93aafbe2b92ef1b)


<a name="v0.2.2"></a>
## [v0.2.2] - 2018-11-17
### Bug Fixes
- **npm t8r:** Handle npm optionalDependencies correctly [`da707d7`](https://github.com/SAP/ui5-project/commit/da707d73b5c75b489e2e499de2b4f54924018844)

### Features
- **projectPreprocessor:** Add handling for task extensions [`0722865`](https://github.com/SAP/ui5-project/commit/072286591ae3b20cca8e418030c3f2bc048352c5)
- **projectPreprocessor:** Allow application project dependency on non-root level [`b8a59d5`](https://github.com/SAP/ui5-project/commit/b8a59d56c8b5cf4c330fe99cb2162c1701aa51ca)

### Internal Changes
- Fix eslint error [`d24eeb2`](https://github.com/SAP/ui5-project/commit/d24eeb2f1c3a6582ce8514e49e9c720a05f8a0f5)
- **ESLint:** prefer-const [`340151f`](https://github.com/SAP/ui5-project/commit/340151f4bd01ed8644d2c6b90bc695b30933cf80)
- **ESLint:** Allow strings to use backticks [`ec81373`](https://github.com/SAP/ui5-project/commit/ec813730b08ae173f5490629a5d074301ca88de3)
- **Git:** Apply lf line-ending to all files [`067b026`](https://github.com/SAP/ui5-project/commit/067b026d74a14d5e3807b7926a9292153ceac13e)
- **GitHub:** Add PULL_REQUEST_TEMPLATE [`7f2366f`](https://github.com/SAP/ui5-project/commit/7f2366f0f727d150b52e23151cd8ce8ecbdcabfd)
- **GitHub ISSUE_TEMPLATE:** Request UI5 module version info [`0936053`](https://github.com/SAP/ui5-project/commit/0936053d2c50837643495760b6b4e46eb36cb87d)
- **Travis:** Activate Windows and Mac builds [`fe46588`](https://github.com/SAP/ui5-project/commit/fe46588218e9c85892486dd9ce120a4828b64c55)
- **npm t8r:** Fix tests on Windows [`f304d7c`](https://github.com/SAP/ui5-project/commit/f304d7c26b14b40cd673bae7cafce8f695ea316e)
- **package.json scripts:** Update verbose logging params [`dd232a3`](https://github.com/SAP/ui5-project/commit/dd232a39bde7c787846b89a5207558f39f3074cb)


<a name="v0.2.1"></a>
## [v0.2.1] - 2018-10-29
### Features
- Add shim extension [`93c9b39`](https://github.com/SAP/ui5-project/commit/93c9b3960ca36f240c5f8453a89f72792a01fe92)
- Add "extension" projects [`476b785`](https://github.com/SAP/ui5-project/commit/476b785810d6993d2a3e21707ffa67e568e67eac)

### Internal Changes
- Add addt'l project-shim extension tests [`e0ecb7f`](https://github.com/SAP/ui5-project/commit/e0ecb7f6a0da334f423a1267c310e687b9854724)
- Add missing cross-env dependency [`0f2bd76`](https://github.com/SAP/ui5-project/commit/0f2bd76fdc03103d4b88b4764d94ebb353340fd5)
- Apply extensions only once [`0488a59`](https://github.com/SAP/ui5-project/commit/0488a5959a0b2b87d1945866da07bc011103c1b2)
- Apply extensions found in root project [`5866cad`](https://github.com/SAP/ui5-project/commit/5866cadc04348c15c2ae7abefe70b934f6cf5b99)
- Add .npmrc to enforce public registry [`78dd5d7`](https://github.com/SAP/ui5-project/commit/78dd5d7fb72a9c51b56b47179dd823f016255cd3)
- **CHANGELOG:** Fix scope detection in commit messages [`955ab92`](https://github.com/SAP/ui5-project/commit/955ab9275b6ee6d0261f9033ed110ac8b684abcf)
- **Coveralls:** Use parallel setting to reduce number of PR comments [`cbcc8ea`](https://github.com/SAP/ui5-project/commit/cbcc8ea8f15d4f8c5ac0124024bf67f29ef14bd9)


<a name="v0.2.0"></a>
## [v0.2.0] - 2018-07-11
### Internal Changes
- Update min Node.js version to >=8.5 [`fc96d87`](https://github.com/SAP/ui5-project/commit/fc96d874c08b54f887cf375eb5028b298c96067f)
- **package.json:** Define files to publish [`01d543c`](https://github.com/SAP/ui5-project/commit/01d543c682f4a0f6fbf15fab0a73b91a5424acee)


<a name="v0.1.0"></a>
## [v0.1.0] - 2018-06-26
### Bug Fixes
- Fix some typos in log messages ([#17](https://github.com/SAP/ui5-project/issues/17)) [`1f2f2fd`](https://github.com/SAP/ui5-project/commit/1f2f2fd164abaf449cc5e7d94ec792f469710207)
- **npm translator:** Fix endless loop in case of dependency cycles ([#15](https://github.com/SAP/ui5-project/issues/15)) [`cf31112`](https://github.com/SAP/ui5-project/commit/cf3111288278e8dd36a09b549bd2b254e86af041)

### Internal Changes
- Update ui5-builder and ui5-logger dependency [`c4aaa81`](https://github.com/SAP/ui5-project/commit/c4aaa81ed813fb96a24a289ceb54bc2537bc70e7)
- Add coveralls and dm-badges [`0fb9132`](https://github.com/SAP/ui5-project/commit/0fb9132ca87e0dd959f1dea4dd3d584f0205baad)
- **CHANGELOG:** Fix GitHub release template [`2ca710b`](https://github.com/SAP/ui5-project/commit/2ca710b04d247e7799266644c1a3099c6621d345)
- **README:** Pre-Alpha -> Alpha [`a988310`](https://github.com/SAP/ui5-project/commit/a988310ae2b810dcff9e8253d32d6474c9ee1da9)


<a name="v0.0.1"></a>
## v0.0.1 - 2018-06-06
### Bug Fixes
- **npm t8r:** Fix collection fallback with missing package.json [`578466f`](https://github.com/SAP/ui5-project/commit/578466fdedf871091874c93d1a9305859e34e3ed)

### Internal Changes
- Prepare npm release [`0467b6a`](https://github.com/SAP/ui5-project/commit/0467b6ac2e87dadd7319fe02901c3b24a3901663)
- Update .editorconfig [`1644a10`](https://github.com/SAP/ui5-project/commit/1644a105337ff83c1f800b99451881f4d8952b8f)
- Add chglog config + npm release scripts [`574f976`](https://github.com/SAP/ui5-project/commit/574f9761debb0cf527e4dfe9d09a73b7abfecc49)
- Update dependencies [`51ddbc8`](https://github.com/SAP/ui5-project/commit/51ddbc854e1e28c6455cbe98fdf517601e560f71)
- Add missing test module dependencies [`0d1d57a`](https://github.com/SAP/ui5-project/commit/0d1d57a0f4643ea171b134d1639404fc51fdb051)
- Add travis CI badge + package.json cleanup [`7769590`](https://github.com/SAP/ui5-project/commit/776959063ab673a92ebfd4cf4c7ba253aae158a8)
- Fix links to CONTRIBUTING.md file [`734a870`](https://github.com/SAP/ui5-project/commit/734a870d6a68f0370626d5a17906afabf1cd27d1)
- **ESLint:** Activate no-var rule [`6916828`](https://github.com/SAP/ui5-project/commit/6916828560c1765bdd64306c8b1c4950a36f0c8b)
- **ESLint:** Activate no-console [`df406da`](https://github.com/SAP/ui5-project/commit/df406dab0888b16b9c66f4fe5a2d7e026ad9f4f4)
- **Travis:** Add node.js 10 to test matrix [`5f26276`](https://github.com/SAP/ui5-project/commit/5f2627668b7faa554b8c3810899828d3be6fd63f)
- **npm t8r:** Improve handling of missing package.json [`4b32134`](https://github.com/SAP/ui5-project/commit/4b321345139058dc821fb08c4556aff88366ea86)


[v0.2.5]: https://github.com/SAP/ui5-project/compare/v0.2.4...v0.2.5
[v0.2.4]: https://github.com/SAP/ui5-project/compare/v0.2.3...v0.2.4
[v0.2.3]: https://github.com/SAP/ui5-project/compare/v0.2.2...v0.2.3
[v0.2.2]: https://github.com/SAP/ui5-project/compare/v0.2.1...v0.2.2
[v0.2.1]: https://github.com/SAP/ui5-project/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/SAP/ui5-project/compare/v0.1.0...v0.2.0
[v0.1.0]: https://github.com/SAP/ui5-project/compare/v0.0.1...v0.1.0
