## 7.2.1 (2026-01-15)

### 🚀 Features

- **ci-context:** revert to commonjs ([d5e5ded](https://github.com/abeljim8am/nx-tools/commit/d5e5ded))
- **ci-context:** migrate to ESM package ([82eb04f](https://github.com/abeljim8am/nx-tools/commit/82eb04f))
- **core:** migrate from @action/exec to tinyexec ([#1284](https://github.com/abeljim8am/nx-tools/pull/1284))
- **ci-context:** migrate to std-env package ([2354f5f](https://github.com/abeljim8am/nx-tools/commit/2354f5f))
- **ci-context:** updated config files to align with new library generators ([#1232](https://github.com/abeljim8am/nx-tools/pull/1232))
- added provenance support ([732184f](https://github.com/abeljim8am/nx-tools/commit/732184f))
- move workspace to use typescript solution ([#1168](https://github.com/abeljim8am/nx-tools/pull/1168))
- **container-metadata:** align with container-metadata-action 5.5.1 ([1c8187e](https://github.com/abeljim8am/nx-tools/commit/1c8187e))
- **ci-context:** improve context for github, gitlab and drone ([5909b45](https://github.com/abeljim8am/nx-tools/commit/5909b45))
- **ci-context:** migrating contexts from functions to classes ([3bf3ec3](https://github.com/abeljim8am/nx-tools/commit/3bf3ec3))
- adding login group support for github ([5d18af6](https://github.com/abeljim8am/nx-tools/commit/5d18af6))
- **ci-context:** update logging methods ([a78dacf](https://github.com/abeljim8am/nx-tools/commit/a78dacf))
- **ci-context:** support teamcity ([#670](https://github.com/abeljim8am/nx-tools/issues/670))
- **ci-context:** added Semaphore provider ([e0b7e93](https://github.com/abeljim8am/nx-tools/commit/e0b7e93))
- **ci-context:** added Drone CI provider ([11e84ce](https://github.com/abeljim8am/nx-tools/commit/11e84ce))
- **ci-context:** added Travis CI provider ([fc61b53](https://github.com/abeljim8am/nx-tools/commit/fc61b53))
- release 4.0.0 ([#644](https://github.com/abeljim8am/nx-tools/pull/644))
- **nx-container:** added init generator ([#639](https://github.com/abeljim8am/nx-tools/pull/639))
- **ci-context:** move to esbuild bundler ([39dd577](https://github.com/abeljim8am/nx-tools/commit/39dd577))
- several updates and nx bump ([e0ad550](https://github.com/abeljim8am/nx-tools/commit/e0ad550))
- ⚠️  **ci-context:** move to swc ([a183cac](https://github.com/abeljim8am/nx-tools/commit/a183cac))
- **ci-context:** switch from swc to tsc again ([aa98db4](https://github.com/abeljim8am/nx-tools/commit/aa98db4))
- **docker-metadata:** migrate to swc compiler ([655bf20](https://github.com/abeljim8am/nx-tools/commit/655bf20))
- **ci-context:** migrate to swc compiler ([8b3727e](https://github.com/abeljim8am/nx-tools/commit/8b3727e))
- **docker-metadata:** base_ref global expression and trim tags and flavor inputs ([2f125cb](https://github.com/abeljim8am/nx-tools/commit/2f125cb))
- **ci-context:** added option to fallback to local environment ([4124f2d](https://github.com/abeljim8am/nx-tools/commit/4124f2d))
- azure devops pipeline support ([cfe1a59](https://github.com/abeljim8am/nx-tools/commit/cfe1a59))
- update nx to 13 and minor packages ([5689f10](https://github.com/abeljim8am/nx-tools/commit/5689f10))
- **ci-context:** add bitbucket support ([73c9b2a](https://github.com/abeljim8am/nx-tools/commit/73c9b2a))
- update nx stack to 12.9.0 ([e077d50](https://github.com/abeljim8am/nx-tools/commit/e077d50))
- general improvements and versions bumps ([04f2c10](https://github.com/abeljim8am/nx-tools/commit/04f2c10))
- **nx-docker:** bx docker improvements ([800147f](https://github.com/abeljim8am/nx-tools/commit/800147f))
- **ci-context:** bump version ([8cc60e4](https://github.com/abeljim8am/nx-tools/commit/8cc60e4))
- **ci-context:** jenkins context ([23da98e](https://github.com/abeljim8am/nx-tools/commit/23da98e))
- **ci-context:** improvements in ci-context package ([31a90e6](https://github.com/abeljim8am/nx-tools/commit/31a90e6))
- update length of docker sha tags to 8 ([12ad233](https://github.com/abeljim8am/nx-tools/commit/12ad233))
- nx-docker improvements and version bumps ([148d62e](https://github.com/abeljim8am/nx-tools/commit/148d62e))

### 🩹 Fixes

- **deps:** bump std-env from 3.9.0 to v3.10.0 ([43ff89f](https://github.com/abeljim8am/nx-tools/commit/43ff89f))
- **ci-context:** fix jenkins context resolution ([#1363](https://github.com/abeljim8am/nx-tools/issues/1363))
- fix ci ([#1201](https://github.com/abeljim8am/nx-tools/pull/1201))
- **ci-context:** improved fallback context detection for detached ref ([1e18dc2](https://github.com/abeljim8am/nx-tools/commit/1e18dc2))
- **deps:** bump @octokit/openapi-types to v22.1.0 ([55438af](https://github.com/abeljim8am/nx-tools/commit/55438af))
- **ci-context:** relaxed dependencies ranges ([40a55fe](https://github.com/abeljim8am/nx-tools/commit/40a55fe))
- **deps:** bump ci-info from 3.9.0 to v4 ([958e958](https://github.com/abeljim8am/nx-tools/commit/958e958))
- **deps:** bump properties-file from 3.3.5 to v3.5.4 ([85d4cfb](https://github.com/abeljim8am/nx-tools/commit/85d4cfb))
- **deps:** bump @octokit/openapi-types from 19.0.0 to v19.1.0 ([c26ad58](https://github.com/abeljim8am/nx-tools/commit/c26ad58))
- **deps:** bump properties-file from 3.3.4 to v3.3.5 ([2e17d20](https://github.com/abeljim8am/nx-tools/commit/2e17d20))
- **deps:** bump @actions/github from 5.1.1 to v6 ([918397f](https://github.com/abeljim8am/nx-tools/commit/918397f))
- **deps:** bump properties-file from 3.3.3 to v3.3.4 ([67e5d91](https://github.com/abeljim8am/nx-tools/commit/67e5d91))
- **deps:** bump properties-file from 3.2.17 to v3.3.3 ([d4cade6](https://github.com/abeljim8am/nx-tools/commit/d4cade6))
- **deps:** bump ci-info from 3.8.0 to v3.9.0 ([80a6c5a](https://github.com/abeljim8am/nx-tools/commit/80a6c5a))
- **ci-context:** fix package.json ([be32489](https://github.com/abeljim8am/nx-tools/commit/be32489))
- **deps:** bump nrwl monorepo from 16.5.5 to v16.7.0 ([745c4fd](https://github.com/abeljim8am/nx-tools/commit/745c4fd))
- **ci-context:** fix missing drone, travis and semaphore initialization in repo factory ([52f7e1b](https://github.com/abeljim8am/nx-tools/commit/52f7e1b))
- **ci-context:** fix missing drone and semaphore in context factory ([1bf0a34](https://github.com/abeljim8am/nx-tools/commit/1bf0a34))
- **nx-container:** fix missing dotenv dependency ([64a835e](https://github.com/abeljim8am/nx-tools/commit/64a835e))
- **core:** fix getPosixName on Nx 15.0.4 ([508b5a6](https://github.com/abeljim8am/nx-tools/commit/508b5a6))
- **ci-context:** fix core version ([72d436d](https://github.com/abeljim8am/nx-tools/commit/72d436d))
- use env var interpolation to handle env variables in tags ([f25d30c](https://github.com/abeljim8am/nx-tools/commit/f25d30c))

### 🏡 Chore

- **release:** publish 7.2.0 ([5073c41](https://github.com/abeljim8am/nx-tools/commit/5073c41))
- **release:** publish 7.1.1-0 ([a6bc84a](https://github.com/abeljim8am/nx-tools/commit/a6bc84a))
- **release:** publish 7.1.0 ([958029a](https://github.com/abeljim8am/nx-tools/commit/958029a))
- **release:** publish 7.0.2 ([b900199](https://github.com/abeljim8am/nx-tools/commit/b900199))
- **release:** publish 7.0.2-beta.0 ([636778c](https://github.com/abeljim8am/nx-tools/commit/636778c))
- **release:** publish 7.0.1 ([2427901](https://github.com/abeljim8am/nx-tools/commit/2427901))
- **release:** publish 7.0.0 ([2e5b88e](https://github.com/abeljim8am/nx-tools/commit/2e5b88e))
- **release:** publish 7.0.0-alpha.3 ([565ae01](https://github.com/abeljim8am/nx-tools/commit/565ae01))
- pin some deps ([be36376](https://github.com/abeljim8am/nx-tools/commit/be36376))
- added node 24 support ([7a348f9](https://github.com/abeljim8am/nx-tools/commit/7a348f9))
- fix customConditions ([5082c66](https://github.com/abeljim8am/nx-tools/commit/5082c66))
- **release:** publish 7.0.0-alpha.2 ([d247cfa](https://github.com/abeljim8am/nx-tools/commit/d247cfa))
- **release:** publish 7.0.0-alpha.1 ([e889155](https://github.com/abeljim8am/nx-tools/commit/e889155))
- ⚠️  bump min Node.js version to 20.19 ([c8412d2](https://github.com/abeljim8am/nx-tools/commit/c8412d2))
- ⚠️  bump required tslib version ranges ([dc121be](https://github.com/abeljim8am/nx-tools/commit/dc121be))
- **release:** publish 6.8.0 ([ab91b2e](https://github.com/abeljim8am/nx-tools/commit/ab91b2e))
- move to pnpm as package manager ([#1242](https://github.com/abeljim8am/nx-tools/pull/1242))
- update eslint configuration to ESM files ([#1228](https://github.com/abeljim8am/nx-tools/pull/1228))
- **release:** publish 6.7.1 ([ed6ef61](https://github.com/abeljim8am/nx-tools/commit/ed6ef61))
- **release:** publish 6.7.0 ([3d2526b](https://github.com/abeljim8am/nx-tools/commit/3d2526b))
- **release:** publish ([60b68de](https://github.com/abeljim8am/nx-tools/commit/60b68de))
- update readme files ([9b6b74c](https://github.com/abeljim8am/nx-tools/commit/9b6b74c))
- **release:** publish ([0b01e27](https://github.com/abeljim8am/nx-tools/commit/0b01e27))
- **release:** publish ([d216104](https://github.com/abeljim8am/nx-tools/commit/d216104))
- **release:** publish ([d5b842e](https://github.com/abeljim8am/nx-tools/commit/d5b842e))
- move to eslint flat rules ([b6229aa](https://github.com/abeljim8am/nx-tools/commit/b6229aa))
- **release:** publish ([5acb2aa](https://github.com/abeljim8am/nx-tools/commit/5acb2aa))
- **release:** publish ([b5baec3](https://github.com/abeljim8am/nx-tools/commit/b5baec3))
- **release:** publish ([c1fb374](https://github.com/abeljim8am/nx-tools/commit/c1fb374))
- update projects configurations to prepare for nx-release ([d68c141](https://github.com/abeljim8am/nx-tools/commit/d68c141))
- migrate to nx 18 ([5ed4b8a](https://github.com/abeljim8am/nx-tools/commit/5ed4b8a))
- bump to 6.0.0-alpha.2 ([69f7acf](https://github.com/abeljim8am/nx-tools/commit/69f7acf))
- **deps:** bump nrwl monorepo from ^16.0.0 to v17 (major) ([e83682b](https://github.com/abeljim8am/nx-tools/commit/e83682b))
- **ci-context:** bump properties-file from 2.2.4 to v3 ([fdc99b1](https://github.com/abeljim8am/nx-tools/commit/fdc99b1))
- version release 5.0.3 ([8a60401](https://github.com/abeljim8am/nx-tools/commit/8a60401))
- release 5.0.2 ([33a2caf](https://github.com/abeljim8am/nx-tools/commit/33a2caf))
- bump package versions ([7ab0d64](https://github.com/abeljim8am/nx-tools/commit/7ab0d64))
- release 5.0.0 ([1dab552](https://github.com/abeljim8am/nx-tools/commit/1dab552))
- bump versions and nx update ([10c75cd](https://github.com/abeljim8am/nx-tools/commit/10c75cd))
- bump packages to 5.0.0-beta.1 ([1c4e7f2](https://github.com/abeljim8am/nx-tools/commit/1c4e7f2))
- ⚠️  update to Nx 16 ([a0bccfb](https://github.com/abeljim8am/nx-tools/commit/a0bccfb))
- ⚠️  prepare release 5.0.0-alpha.1 ([5f7a64d](https://github.com/abeljim8am/nx-tools/commit/5f7a64d))
- bump version to 4.0.1 ([2639d3e](https://github.com/abeljim8am/nx-tools/commit/2639d3e))
- release rc.1 ([01b4405](https://github.com/abeljim8am/nx-tools/commit/01b4405))
- update to nx 15 ([5ca59bc](https://github.com/abeljim8am/nx-tools/commit/5ca59bc))
- release version 3.0.1 ([7beb6d0](https://github.com/abeljim8am/nx-tools/commit/7beb6d0))
- **ci-context:** update deps ([e9cc70f](https://github.com/abeljim8am/nx-tools/commit/e9cc70f))
- release version 3.0.0 ([6338e09](https://github.com/abeljim8am/nx-tools/commit/6338e09))
- release version 3.0.0-alpha.3 ([b5e0dbe](https://github.com/abeljim8am/nx-tools/commit/b5e0dbe))
- update nx ([109a26c](https://github.com/abeljim8am/nx-tools/commit/109a26c))
- set engines to node >= 14 ([0e85106](https://github.com/abeljim8am/nx-tools/commit/0e85106))
- update nx stack ([e052965](https://github.com/abeljim8am/nx-tools/commit/e052965))
- new alpha release ([d962265](https://github.com/abeljim8am/nx-tools/commit/d962265))
- bump nx to 14.0.5 ([37f4190](https://github.com/abeljim8am/nx-tools/commit/37f4190))
- release version 3.0.0-alpha.1 ([5e8b6e0](https://github.com/abeljim8am/nx-tools/commit/5e8b6e0))
- **release:** 2.2.0 ([83ddcc3](https://github.com/abeljim8am/nx-tools/commit/83ddcc3))
- **release:** 2.1.1 ([50f5ada](https://github.com/abeljim8am/nx-tools/commit/50f5ada))
- **release:** 2.1.0 ([2adf74e](https://github.com/abeljim8am/nx-tools/commit/2adf74e))
- **release:** 2.0.1 ([4fb33d5](https://github.com/abeljim8am/nx-tools/commit/4fb33d5))
- **release:** 2.0.0 ([756aefe](https://github.com/abeljim8am/nx-tools/commit/756aefe))
- **release:** 2.0.0-alpha.4 ([f40772d](https://github.com/abeljim8am/nx-tools/commit/f40772d))
- **release:** 2.0.0-alpha.3 ([44fb29e](https://github.com/abeljim8am/nx-tools/commit/44fb29e))
- **release:** 2.0.0-alpha.2 ([9fb1f9e](https://github.com/abeljim8am/nx-tools/commit/9fb1f9e))
- **release:** 2.0.0-alpha.1 ([789f90a](https://github.com/abeljim8am/nx-tools/commit/789f90a))
- setup semver plugin ([f945223](https://github.com/abeljim8am/nx-tools/commit/f945223))
- update nx stack to 12.8 ([7c3359f](https://github.com/abeljim8am/nx-tools/commit/7c3359f))
- convert to standalone config ([aa2679c](https://github.com/abeljim8am/nx-tools/commit/aa2679c))
- bump versions ([6696ed9](https://github.com/abeljim8am/nx-tools/commit/6696ed9))
- update deps ([eb7deb8](https://github.com/abeljim8am/nx-tools/commit/eb7deb8))

### ⚠️  Breaking Changes

- bump min Node.js version to 20.19  ([c8412d2](https://github.com/abeljim8am/nx-tools/commit/c8412d2))
  update supported Node.js versions to 20.19.x and later
- bump required tslib version ranges  ([dc121be](https://github.com/abeljim8am/nx-tools/commit/dc121be))
  update supported tslib versions to 2.6.x and later
- update to Nx 16  ([a0bccfb](https://github.com/abeljim8am/nx-tools/commit/a0bccfb))
  Nx ^16.0.0 is required
- prepare release 5.0.0-alpha.1  ([5f7a64d](https://github.com/abeljim8am/nx-tools/commit/5f7a64d))
  drop support for Nx 12 and 13
- **ci-context:** move to swc  ([a183cac](https://github.com/abeljim8am/nx-tools/commit/a183cac))
  Dropped support for Node 12

### ❤️ Thank You

- Daniel Schuba @DaSchTour
- Gustavo Perdomo
- Ian Serpa
- Leonardo Chaia

## 7.2.0 (2025-11-22)

### 🩹 Fixes

- **deps:** bump std-env from 3.9.0 to v3.10.0 ([43ff89f5](https://github.com/gperdomor/nx-tools/commit/43ff89f5))

### 🏡 Chore

- **release:** publish 7.1.1-0 ([a6bc84a5](https://github.com/gperdomor/nx-tools/commit/a6bc84a5))

### ❤️ Thank You

- Gustavo Perdomo

## 7.1.1-0 (2025-11-21)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 7.1.0 (2025-11-20)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 7.0.2 (2025-11-17)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 7.0.2-beta.0 (2025-11-11)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 7.0.1 (2025-10-31)

### 🩹 Fixes

- **ci-context:** fix jenkins context resolution ([#1363](https://github.com/gperdomor/nx-tools/issues/1363))

### ❤️ Thank You

- Gustavo Perdomo

# 7.0.0 (2025-10-23)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 7.0.0-alpha.3 (2025-10-14)

### 🚀 Features

- **ci-context:** revert to commonjs ([d5e5ded](https://github.com/gperdomor/nx-tools/commit/d5e5ded))

### 🏡 Chore

- pin some deps ([be36376](https://github.com/gperdomor/nx-tools/commit/be36376))
- added node 24 support ([7a348f9](https://github.com/gperdomor/nx-tools/commit/7a348f9))
- fix customConditions ([5082c66](https://github.com/gperdomor/nx-tools/commit/5082c66))

### ❤️ Thank You

- Gustavo Perdomo

## 7.0.0-alpha.2 (2025-08-05)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 7.0.0-alpha.1 (2025-08-05)

### 🚀 Features

- **ci-context:** migrate to ESM package ([82eb04f](https://github.com/gperdomor/nx-tools/commit/82eb04f))
- **core:** migrate from @action/exec to tinyexec ([#1284](https://github.com/gperdomor/nx-tools/pull/1284))
- **ci-context:** migrate to std-env package ([2354f5f](https://github.com/gperdomor/nx-tools/commit/2354f5f))

### 🏡 Chore

- ⚠️ bump min Node.js version to 20.19 ([c8412d2](https://github.com/gperdomor/nx-tools/commit/c8412d2))
- ⚠️ bump required tslib version ranges ([dc121be](https://github.com/gperdomor/nx-tools/commit/dc121be))

### ⚠️ Breaking Changes

- update supported Node.js versions to 20.19.x and later
- update supported tslib versions to 2.6.x and later

### ❤️ Thank You

- Gustavo Perdomo

## 6.8.0 (2025-06-17)

### 🚀 Features

- **ci-context:** updated config files to align with new library generators ([#1232](https://github.com/gperdomor/nx-tools/pull/1232))

### 🏡 Chore

- move to pnpm as package manager ([#1242](https://github.com/gperdomor/nx-tools/pull/1242))
- update eslint configuration to ESM files ([#1228](https://github.com/gperdomor/nx-tools/pull/1228))

### ❤️ Thank You

- Gustavo Perdomo

## 6.7.1 (2025-05-17)

This was a version bump only for ci-context to align it with other projects, there were no code changes.

## 6.7.0 (2025-05-17)

### 🚀 Features

- added provenance support ([732184f](https://github.com/gperdomor/nx-tools/commit/732184f))

### ❤️ Thank You

- Gustavo Perdomo

## 6.2.0 (2025-05-15)

### 🏡 Chore

- update readme files ([9b6b74c](https://github.com/gperdomor/nx-tools/commit/9b6b74c))

### 🧱 Updated Dependencies

- Updated core to 6.2.0

### ❤️ Thank You

- Gustavo Perdomo

## 6.2.0-beta.0 (2025-05-15)

### 🚀 Features

- move workspace to use typescript solution ([#1168](https://github.com/gperdomor/nx-tools/pull/1168))

### 🩹 Fixes

- fix ci ([#1201](https://github.com/gperdomor/nx-tools/pull/1201))

### 🧱 Updated Dependencies

- Updated core to 6.2.0-beta.0

### ❤️ Thank You

- Gustavo Perdomo

## 6.1.1 (2024-11-08)

### 🧱 Updated Dependencies

- Updated core to 6.1.1

## 6.1.0 (2024-10-16)

### 🧱 Updated Dependencies

- Updated core to 6.1.0

## 6.0.1 (2024-05-22)

### 🩹 Fixes

- **ci-context:** improved fallback context detection for detached ref ([1e18dc2](https://github.com/gperdomor/nx-tools/commit/1e18dc2))

### ❤️ Thank You

- Gustavo Perdomo
- Kaden Wilkinson @kdawgwilk
- meehawk @meehawk

# 6.0.0 (2024-05-07)

### 🩹 Fixes

- **ci-context:** improved fallback context detection for detached ref ([1e18dc2](https://github.com/gperdomor/nx-tools/commit/1e18dc2))

### ❤️ Thank You

- Gustavo Perdomo
- Kaden Wilkinson @kdawgwilk
- meehawk @meehawk

## 6.0.0-alpha.3 (2024-04-24)

### 🚀 Features

- **ci-context:** migrating contexts from functions to classes ([3bf3ec3](https://github.com/gperdomor/nx-tools/commit/3bf3ec3))

- **ci-context:** improve context for github, gitlab and drone ([5909b45](https://github.com/gperdomor/nx-tools/commit/5909b45))

- **container-metadata:** align with container-metadata-action 5.5.1 ([1c8187e](https://github.com/gperdomor/nx-tools/commit/1c8187e))

### 🩹 Fixes

- **ci-context:** fix package.json ([be32489](https://github.com/gperdomor/nx-tools/commit/be32489))

- **deps:** bump ci-info from 3.8.0 to v3.9.0 ([80a6c5a](https://github.com/gperdomor/nx-tools/commit/80a6c5a))

- **deps:** bump properties-file from 3.2.17 to v3.3.3 ([d4cade6](https://github.com/gperdomor/nx-tools/commit/d4cade6))

- **deps:** bump properties-file from 3.3.3 to v3.3.4 ([67e5d91](https://github.com/gperdomor/nx-tools/commit/67e5d91))

- **deps:** bump @actions/github from 5.1.1 to v6 ([918397f](https://github.com/gperdomor/nx-tools/commit/918397f))

- **deps:** bump properties-file from 3.3.4 to v3.3.5 ([2e17d20](https://github.com/gperdomor/nx-tools/commit/2e17d20))

- **deps:** bump @octokit/openapi-types from 19.0.0 to v19.1.0 ([c26ad58](https://github.com/gperdomor/nx-tools/commit/c26ad58))

- **deps:** bump properties-file from 3.3.5 to v3.5.4 ([85d4cfb](https://github.com/gperdomor/nx-tools/commit/85d4cfb))

- **deps:** bump ci-info from 3.9.0 to v4 ([958e958](https://github.com/gperdomor/nx-tools/commit/958e958))

- **ci-context:** relaxed dependencies ranges ([40a55fe](https://github.com/gperdomor/nx-tools/commit/40a55fe))

- **deps:** bump @octokit/openapi-types to v22.1.0 ([55438af](https://github.com/gperdomor/nx-tools/commit/55438af))

### ❤️ Thank You

- Dan Iosif
- Gustavo Perdomo
- Lehoczky Zoltán @Lehoczky
- Nicolas Dubois
- Rene Bonilla

# Changelog

This file was generated using [@jscutlery/semver](https://github.com/jscutlery/semver).

## [3.0.1](https://github.com/gperdomor/nx-tools/compare/ci-context@3.0.0...ci-context@3.0.1) (2022-07-11)

## [3.0.0](https://github.com/gperdomor/nx-tools/compare/ci-context@3.0.0-alpha.3...ci-context@3.0.0) (2022-06-14)

## [3.0.0-alpha.3](https://github.com/gperdomor/nx-tools/compare/ci-context@3.0.0-alpha.2...ci-context@3.0.0-alpha.3) (2022-06-14)

### Features

- several updates and nx bump ([e0ad550](https://github.com/gperdomor/nx-tools/commit/e0ad550db010d1710b6729911aae9d432aaf5ffb))

## [3.0.0-alpha.2](https://github.com/gperdomor/nx-tools/compare/ci-context@3.0.0-alpha.1...ci-context@3.0.0-alpha.2) (2022-04-29)

### Features

- chore: bump nx to 14.0.5
- other deps updates

## [3.0.0-alpha.1](https://github.com/nx-tools/nx-tools/compare/ci-context@2.2.0...ci-context@3.0.0-alpha.1) (2022-04-09)

### ⚠ BREAKING CHANGES

- **ci-context:** Dropped support for Node 12

### Features

- **ci-context:** move to swc ([a183cac](https://github.com/nx-tools/nx-tools/commit/a183cac4cda9888d3345989908dbf4ef0cc99971))

# [2.2.0](https://github.com/gperdomor/nx-tools/compare/ci-context@2.1.1...ci-context@2.2.0) (2022-01-02)

### Features

- **ci-context:** switch from swc to tsc again ([aa98db4](https://github.com/gperdomor/nx-tools/commit/aa98db4180218da5cd2f8c949bd8582d86a4db32))

## [2.1.1](https://github.com/gperdomor/nx-tools/compare/ci-context@2.1.0...ci-context@2.1.1) (2022-01-02)

### Bug Fixes

- **ci-context:** fix core version ([72d436d](https://github.com/gperdomor/nx-tools/commit/72d436d387f33e85d80fc03b01e33dc7e44582e5))

# [2.1.0](https://github.com/gperdomor/nx-tools/compare/ci-context@2.0.1...ci-context@2.1.0) (2021-12-27)

### Features

- **ci-context:** migrate to swc compiler ([8b3727e](https://github.com/gperdomor/nx-tools/commit/8b3727ef295cefdf15f69042ab03c19001075d84))
- **docker-metadata:** migrate to swc compiler ([655bf20](https://github.com/gperdomor/nx-tools/commit/655bf202cc0661588b34f54357253fd290c4cabb))

# [2.0.1](https://github.com/gperdomor/nx-tools/compare/ci-context@2.0.0...ci-context@2.0.1) (2021-11-25)

- Set tslib@^2.1.0 as peerDependencies

# [2.0.0](https://github.com/gperdomor/nx-tools/compare/ci-context@2.0.0-alpha.4...ci-context@2.0.0) (2021-11-23)

- No changes from alpha.4

# [2.0.0-alpha.4](https://github.com/gperdomor/nx-tools/compare/ci-context@2.0.0-alpha.3...ci-context@2.0.0-alpha.4) (2021-11-10)

### Features

- **ci-context:** added option to fallback to local environment ([4124f2d](https://github.com/gperdomor/nx-tools/commit/4124f2d4f4117cdab064756410fd992394c7b261))

# [2.0.0-alpha.3](https://github.com/gperdomor/nx-tools/compare/ci-context@2.0.0-alpha.2...ci-context@2.0.0-alpha.3) (2021-11-08)

### Features

- azure devops pipeline support ([cfe1a59](https://github.com/gperdomor/nx-tools/commit/cfe1a59265873d6d1c95bf1aa1a72e4b75e27a79))

# [2.0.0-alpha.2](https://github.com/gperdomor/nx-tools/compare/ci-context@2.0.0-alpha.1...ci-context@2.0.0-alpha.2) (2021-11-05)

### Features

- update nx to 13 and minor packages ([5689f10](https://github.com/gperdomor/nx-tools/commit/5689f10271777520294a6958f65b8004726412ec))
- bump @nx-tools/core to 2.0.0-alpha.2

## 2.0.0-alpha.1 (2021-10-06)

### Features

- **ci-context:** add bitbucket support
- **ci-context:** releasing using @jscutlery/semver
- **ci-context:** updated to nx 12.9.0
- **ci-context:** updated dependencies

## 1.0.0 (2021-06-14)

- Initial release
