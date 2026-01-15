## 7.2.1 (2026-01-15)

### 🚀 Features

- **nx-container:** bump tmp from 0.2.4 to v0.2.5 ([3568e7a](https://github.com/abeljim8am/nx-tools/commit/3568e7a))
- added initial support for Nx 22 ([942cc11](https://github.com/abeljim8am/nx-tools/commit/942cc11))
- ⚠️  **nx-container:** remove kaniko suport ([e6bceca](https://github.com/abeljim8am/nx-tools/commit/e6bceca))
- **nx-container:** support for sbom attestations ([0782daf](https://github.com/abeljim8am/nx-tools/commit/0782daf))
- **core:** migrate from @action/exec to tinyexec ([#1284](https://github.com/abeljim8am/nx-tools/pull/1284))
- **nx-container:** move project to plugins directory ([e76e956](https://github.com/abeljim8am/nx-tools/commit/e76e956))
- nx 19 support ([3922496](https://github.com/abeljim8am/nx-tools/commit/3922496))
- add option to configure provenance ([914b361](https://github.com/abeljim8am/nx-tools/commit/914b361))
- **nx-container:** fix generator ([27a1267](https://github.com/abeljim8am/nx-tools/commit/27a1267))
- **nx-container:** fix generator ([15eaea1](https://github.com/abeljim8am/nx-tools/commit/15eaea1))
- **nx-container:** improved configuration generator ([eb88944](https://github.com/abeljim8am/nx-tools/commit/eb88944))
- **nx-container:** revamped configuration generator ([#881](https://github.com/abeljim8am/nx-tools/issues/881))
- **ci-context:** migrating contexts from functions to classes ([3bf3ec3](https://github.com/abeljim8am/nx-tools/commit/3bf3ec3))
- expanding vars on secrets if they are not files ([9f8aff4](https://github.com/abeljim8am/nx-tools/commit/9f8aff4))
- adding login group support for github ([5d18af6](https://github.com/abeljim8am/nx-tools/commit/5d18af6))
- **nx-container:** update logging methods ([5c50f9d](https://github.com/abeljim8am/nx-tools/commit/5c50f9d))
- **nx-container:** migrate to csv-parse 5 ([8225335](https://github.com/abeljim8am/nx-tools/commit/8225335))
- **nx-container:** move .nx-container output folder to node_modules/.cache/nx-container ([1c1edf5](https://github.com/abeljim8am/nx-tools/commit/1c1edf5))
- release 4.0.0 ([#644](https://github.com/abeljim8am/nx-tools/pull/644))
- **nx-container:** added init generator ([#639](https://github.com/abeljim8am/nx-tools/pull/639))
- **nx-container:** added quiet option ([533d1cc](https://github.com/abeljim8am/nx-tools/commit/533d1cc))
- **nx-container:** update jest timeouts ([17f3be4](https://github.com/abeljim8am/nx-tools/commit/17f3be4))
- **nx-prisma:** simplify executors ([f805629](https://github.com/abeljim8am/nx-tools/commit/f805629))
- **nx-prisma:** new commands and refactor + prisma 4 support ([1a30bf0](https://github.com/abeljim8am/nx-tools/commit/1a30bf0))
- **nx-container:** introduce nx-container (replacement for nx-docker) ([6b2b690](https://github.com/abeljim8am/nx-tools/commit/6b2b690))

### 🩹 Fixes

- **nx-container:** fix provenance ([#1314](https://github.com/abeljim8am/nx-tools/issues/1314))
- fix tests ([708bd38](https://github.com/abeljim8am/nx-tools/commit/708bd38))
- **nx-container:** relaxed dependencies ranges ([6f24d36](https://github.com/abeljim8am/nx-tools/commit/6f24d36))
- **nx-container:** provenance 'false' ignored ([6868733](https://github.com/abeljim8am/nx-tools/commit/6868733))
- **deps:** bump tmp from 0.2.1 to v0.2.3 ([e9b5b95](https://github.com/abeljim8am/nx-tools/commit/e9b5b95))
- **deps:** bump csv-parse from 5.5.2 to v5.5.5 ([db61460](https://github.com/abeljim8am/nx-tools/commit/db61460))
- **deps:** bump semver from 7.5.4 to v7.6.0 ([8a9a0cd](https://github.com/abeljim8am/nx-tools/commit/8a9a0cd))
- **deps:** bump handlebars from 4.7.7 to v4.7.8 ([d56bf1a](https://github.com/abeljim8am/nx-tools/commit/d56bf1a))
- **deps:** bump csv-parse from 5.4.0 to v5.5.2 ([1bae187](https://github.com/abeljim8am/nx-tools/commit/1bae187))
- **deps:** bump nrwl monorepo from 16.5.5 to v16.7.0 ([745c4fd](https://github.com/abeljim8am/nx-tools/commit/745c4fd))
- cache-to and from splitting single values on comma ([b59e26b](https://github.com/abeljim8am/nx-tools/commit/b59e26b))
- **nx-container:** fix missing dotenv dependency ([64a835e](https://github.com/abeljim8am/nx-tools/commit/64a835e))
- **nx-container:** fix command evn variable interpolation ([#652](https://github.com/abeljim8am/nx-tools/issues/652))
- **core:** fix getPosixName on Nx 15.0.4 ([508b5a6](https://github.com/abeljim8am/nx-tools/commit/508b5a6))

### 📖 Documentation

- fix nx-container and nx-prisma setup docs ([ac160a5](https://github.com/abeljim8am/nx-tools/commit/ac160a5))
- added example for env var expansion ([7aee4a1](https://github.com/abeljim8am/nx-tools/commit/7aee4a1))
- fix container-metadata references ([ab45a04](https://github.com/abeljim8am/nx-tools/commit/ab45a04))

### 🏡 Chore

- **release:** publish 7.2.0 ([5073c41](https://github.com/abeljim8am/nx-tools/commit/5073c41))
- **release:** publish 7.1.1-0 ([a6bc84a](https://github.com/abeljim8am/nx-tools/commit/a6bc84a))
- **release:** publish 7.1.0 ([958029a](https://github.com/abeljim8am/nx-tools/commit/958029a))
- **release:** publish 7.0.2 ([b900199](https://github.com/abeljim8am/nx-tools/commit/b900199))
- **release:** publish 7.0.2-beta.0 ([636778c](https://github.com/abeljim8am/nx-tools/commit/636778c))
- **release:** publish 7.0.1 ([2427901](https://github.com/abeljim8am/nx-tools/commit/2427901))
- fix dependency range to actually support Nx version 22 ([738f6a1](https://github.com/abeljim8am/nx-tools/commit/738f6a1))
- **release:** publish 7.0.0 ([2e5b88e](https://github.com/abeljim8am/nx-tools/commit/2e5b88e))
- **release:** publish 7.0.0-alpha.3 ([565ae01](https://github.com/abeljim8am/nx-tools/commit/565ae01))
- **deps:** bump tmp from 0.2.3 to 0.2.4 ([010fbc0](https://github.com/abeljim8am/nx-tools/commit/010fbc0))
- pin some deps ([aca6e31](https://github.com/abeljim8am/nx-tools/commit/aca6e31))
- added node 24 support ([7a348f9](https://github.com/abeljim8am/nx-tools/commit/7a348f9))
- fix customConditions ([5082c66](https://github.com/abeljim8am/nx-tools/commit/5082c66))
- **release:** publish 7.0.0-alpha.2 ([d247cfa](https://github.com/abeljim8am/nx-tools/commit/d247cfa))
- **release:** publish 7.0.0-alpha.1 ([e889155](https://github.com/abeljim8am/nx-tools/commit/e889155))
- ⚠️  bump min Node.js version to 20.19 ([c8412d2](https://github.com/abeljim8am/nx-tools/commit/c8412d2))
- ⚠️  bump required tslib version ranges ([dc121be](https://github.com/abeljim8am/nx-tools/commit/dc121be))
- ⚠️  bump required nx version ranges ([7d0dbea](https://github.com/abeljim8am/nx-tools/commit/7d0dbea))
- bump nx and tslib version requirements ([#1280](https://github.com/abeljim8am/nx-tools/pull/1280))
- **release:** publish ([5acb2aa](https://github.com/abeljim8am/nx-tools/commit/5acb2aa))
- **release:** publish ([b5baec3](https://github.com/abeljim8am/nx-tools/commit/b5baec3))
- **release:** publish ([c1fb374](https://github.com/abeljim8am/nx-tools/commit/c1fb374))
- update projects configurations to prepare for nx-release ([d68c141](https://github.com/abeljim8am/nx-tools/commit/d68c141))
- fix lint issues ([b834fcb](https://github.com/abeljim8am/nx-tools/commit/b834fcb))
- migrate to nx 18 ([5ed4b8a](https://github.com/abeljim8am/nx-tools/commit/5ed4b8a))
- **deps:** bump nrwl monorepo from ^16.0.0 to v17 (major) ([e83682b](https://github.com/abeljim8am/nx-tools/commit/e83682b))
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

### ⚠️  Breaking Changes

- **nx-container:** remove kaniko suport  ([e6bceca](https://github.com/abeljim8am/nx-tools/commit/e6bceca))
  kaniko engine is no longer supported
- bump min Node.js version to 20.19  ([c8412d2](https://github.com/abeljim8am/nx-tools/commit/c8412d2))
  update supported Node.js versions to 20.19.x and later
- bump required tslib version ranges  ([dc121be](https://github.com/abeljim8am/nx-tools/commit/dc121be))
  update supported tslib versions to 2.6.x and later
- bump required nx version ranges  ([7d0dbea](https://github.com/abeljim8am/nx-tools/commit/7d0dbea))
  removed support of Nx 16.x and 17.x
- update to Nx 16  ([a0bccfb](https://github.com/abeljim8am/nx-tools/commit/a0bccfb))
  Nx ^16.0.0 is required
- prepare release 5.0.0-alpha.1  ([5f7a64d](https://github.com/abeljim8am/nx-tools/commit/5f7a64d))
  drop support for Nx 12 and 13

### ❤️ Thank You

- Dan Iosif
- Gustavo Perdomo
- Jorge Rodriguez
- Karl-E. Kiel @kekielst
- Nicolas Dubois
- René @jahusa02

## 7.2.0 (2025-11-22)

### 🏡 Chore

- **release:** publish 7.1.1-0 ([a6bc84a5](https://github.com/gperdomor/nx-tools/commit/a6bc84a5))

### ❤️ Thank You

- Gustavo Perdomo

## 7.1.1-0 (2025-11-21)

This was a version bump only for nx-container to align it with other projects, there were no code changes.

## 7.1.0 (2025-11-20)

This was a version bump only for nx-container to align it with other projects, there were no code changes.

## 7.0.2 (2025-11-17)

This was a version bump only for nx-container to align it with other projects, there were no code changes.

## 7.0.2-beta.0 (2025-11-11)

This was a version bump only for nx-container to align it with other projects, there were no code changes.

## 7.0.1 (2025-10-31)

### 🏡 Chore

- fix dependency range to actually support Nx version 22 ([738f6a1](https://github.com/gperdomor/nx-tools/commit/738f6a1))

### ❤️ Thank You

- René @jahusa02

# 7.0.0 (2025-10-23)

### 🚀 Features

- **nx-container:** bump tmp from 0.2.4 to v0.2.5 ([3568e7a](https://github.com/gperdomor/nx-tools/commit/3568e7a))

### ❤️ Thank You

- Gustavo Perdomo

## 7.0.0-alpha.3 (2025-10-14)

### 🚀 Features

- added initial support for Nx 22 ([942cc11](https://github.com/gperdomor/nx-tools/commit/942cc11))

### 🩹 Fixes

- **nx-container:** fix provenance ([#1314](https://github.com/gperdomor/nx-tools/issues/1314))
- fix tests ([708bd38](https://github.com/gperdomor/nx-tools/commit/708bd38))

### 🏡 Chore

- **deps:** bump tmp from 0.2.3 to 0.2.4 ([010fbc0](https://github.com/gperdomor/nx-tools/commit/010fbc0))
- pin some deps ([aca6e31](https://github.com/gperdomor/nx-tools/commit/aca6e31))
- added node 24 support ([7a348f9](https://github.com/gperdomor/nx-tools/commit/7a348f9))
- fix customConditions ([5082c66](https://github.com/gperdomor/nx-tools/commit/5082c66))

### ❤️ Thank You

- Gustavo Perdomo

## 7.0.0-alpha.2 (2025-08-05)

This was a version bump only for nx-container to align it with other projects, there were no code changes.

## 7.0.0-alpha.1 (2025-08-05)

### 🚀 Features

- ⚠️ **nx-container:** remove kaniko suport ([e6bceca](https://github.com/gperdomor/nx-tools/commit/e6bceca))
- **nx-container:** support for sbom attestations ([0782daf](https://github.com/gperdomor/nx-tools/commit/0782daf))
- **core:** migrate from @action/exec to tinyexec ([#1284](https://github.com/gperdomor/nx-tools/pull/1284))

### 🏡 Chore

- ⚠️ bump min Node.js version to 20.19 ([c8412d2](https://github.com/gperdomor/nx-tools/commit/c8412d2))
- ⚠️ bump required tslib version ranges ([dc121be](https://github.com/gperdomor/nx-tools/commit/dc121be))
- ⚠️ bump required nx version ranges ([7d0dbea](https://github.com/gperdomor/nx-tools/commit/7d0dbea))
- bump nx and tslib version requirements ([#1280](https://github.com/gperdomor/nx-tools/pull/1280))

### ⚠️ Breaking Changes

- **nx-container:** kaniko engine is no longer supported
- update supported Node.js versions to 20.19.x and later
- update supported tslib versions to 2.6.x and later
- removed support of Nx 16.x and 17.x

### ❤️ Thank You

- Gustavo Perdomo
- Karl-E. Kiel @kekielst

## 6.8.0 (2025-06-17)

### 🚀 Features

- **website:** improve nx-container docs ([#1252](https://github.com/gperdomor/nx-tools/pull/1252))
- **website:** added initial app for docs ([#1250](https://github.com/gperdomor/nx-tools/pull/1250))
- **nx-container:** updated config files to align with new plugin generators ([#1235](https://github.com/gperdomor/nx-tools/pull/1235))

### 🏡 Chore

- move to pnpm as package manager ([#1242](https://github.com/gperdomor/nx-tools/pull/1242))
- update eslint configuration to ESM files ([#1228](https://github.com/gperdomor/nx-tools/pull/1228))

### ❤️ Thank You

- Gustavo Perdomo

## 6.7.1 (2025-05-17)

This was a version bump only for nx-container to align it with other projects, there were no code changes.

## 6.7.0 (2025-05-17)

### 🚀 Features

- added provenance support ([732184f](https://github.com/gperdomor/nx-tools/commit/732184f))

### ❤️ Thank You

- Gustavo Perdomo

## 6.3.0 (2025-05-15)

### 🏡 Chore

- update readme files ([9b6b74c](https://github.com/gperdomor/nx-tools/commit/9b6b74c))

### 🧱 Updated Dependencies

- Updated container-metadata to 6.2.0
- Updated ci-context to 6.2.0
- Updated core to 6.2.0

### ❤️ Thank You

- Gustavo Perdomo

## 6.3.0-beta.0 (2025-05-15)

### 🚀 Features

- added Nx 21 support ([#1197](https://github.com/gperdomor/nx-tools/pull/1197))
- move workspace to use typescript solution ([#1168](https://github.com/gperdomor/nx-tools/pull/1168))

### 🩹 Fixes

- fix ci ([#1201](https://github.com/gperdomor/nx-tools/pull/1201))
- **nx-container:** fix nx-container packaging info ([efb34d2](https://github.com/gperdomor/nx-tools/commit/efb34d2))

### 🧱 Updated Dependencies

- Updated container-metadata to 6.2.0-beta.0
- Updated ci-context to 6.2.0-beta.0
- Updated core to 6.2.0-beta.0

### ❤️ Thank You

- Gustavo Perdomo

## 6.2.0 (2024-12-08)

### 🚀 Features

- **nx-container:** add init generator ([150024b](https://github.com/gperdomor/nx-tools/commit/150024b))

- **nx-container:** add inferred targets ([6d53fa5](https://github.com/gperdomor/nx-tools/commit/6d53fa5))

- **nx-container:** improvements in inferred task ([#1164](https://github.com/gperdomor/nx-tools/pull/1164))

### 🩹 Fixes

- **nx-container:** fix lint errors ([09b4517](https://github.com/gperdomor/nx-tools/commit/09b4517))

### ❤️ Thank You

- Badeau, Jose
- Gustavo Perdomo

## 6.1.1 (2024-11-08)

### 🧱 Updated Dependencies

- Updated container-metadata to 6.1.1
- Updated core to 6.1.1

## 6.1.0 (2024-10-16)

### 🧱 Updated Dependencies

- Updated container-metadata to 6.1.0
- Updated core to 6.1.0

## 6.0.4 (2024-10-06)

### 🩹 Fixes

- **nx-container:** fix secret-files interpolation ([08b8f10](https://github.com/gperdomor/nx-tools/commit/08b8f10))

### ❤️ Thank You

- Gustavo Perdomo

## 6.0.3 (2024-10-03)

### 🩹 Fixes

- **docs:** update doc links to point to correct plugin doc location ([40ea7ba](https://github.com/gperdomor/nx-tools/commit/40ea7ba))

### ❤️ Thank You

- WTPascoe @WTPascoe

## 6.0.2 (2024-08-19)

### 🚀 Features

- **nx-container:** move project to plugins directory ([e76e956](https://github.com/gperdomor/nx-tools/commit/e76e956))

- **nx-container:** compiled using swc ([462f575](https://github.com/gperdomor/nx-tools/commit/462f575))

- **nx-container:** compiled using swc ([aeac6aa](https://github.com/gperdomor/nx-tools/commit/aeac6aa))

- **nx-container:** improvements in docker templates ([2a5b1ac](https://github.com/gperdomor/nx-tools/commit/2a5b1ac))

- **nx-container:** forward quiet option to metadata generation for quiet logs ([12acea1](https://github.com/gperdomor/nx-tools/commit/12acea1))

- **nx-container:** update package versions ([7ec6b6f](https://github.com/gperdomor/nx-tools/commit/7ec6b6f))

### 🧱 Updated Dependencies

- Updated container-metadata to 6.0.2

### ❤️ Thank You

- Gustavo Perdomo

## 6.0.1 (2024-05-22)

### 🚀 Features

- nx 19 support ([3922496](https://github.com/gperdomor/nx-tools/commit/3922496))

### ❤️ Thank You

- Gustavo Perdomo
- Kaden Wilkinson @kdawgwilk
- meehawk @meehawk

# 6.0.0 (2024-05-07)

### 🚀 Features

- nx 19 support ([3922496](https://github.com/gperdomor/nx-tools/commit/3922496))

### ❤️ Thank You

- Gustavo Perdomo
- Kaden Wilkinson @kdawgwilk
- meehawk @meehawk

## 6.0.0-alpha.3 (2024-04-24)

### 🚀 Features

- add option to configure provenance ([914b361](https://github.com/gperdomor/nx-tools/commit/914b361))

- **ci-context:** migrating contexts from functions to classes ([3bf3ec3](https://github.com/gperdomor/nx-tools/commit/3bf3ec3))

- **nx-container:** revamped configuration generator ([7c98412](https://github.com/gperdomor/nx-tools/commit/7c98412))

- **nx-container:** improved configuration generator ([eb88944](https://github.com/gperdomor/nx-tools/commit/eb88944))

- **nx-container:** fix generator ([15eaea1](https://github.com/gperdomor/nx-tools/commit/15eaea1))

- **nx-container:** fix generator ([27a1267](https://github.com/gperdomor/nx-tools/commit/27a1267))

### 🩹 Fixes

- **deps:** bump csv-parse from 5.4.0 to v5.5.2 ([1bae187](https://github.com/gperdomor/nx-tools/commit/1bae187))

- **deps:** bump handlebars from 4.7.7 to v4.7.8 ([d56bf1a](https://github.com/gperdomor/nx-tools/commit/d56bf1a))

- **deps:** bump semver from 7.5.4 to v7.6.0 ([8a9a0cd](https://github.com/gperdomor/nx-tools/commit/8a9a0cd))

- **deps:** bump csv-parse from 5.5.2 to v5.5.5 ([db61460](https://github.com/gperdomor/nx-tools/commit/db61460))

- **deps:** bump tmp from 0.2.1 to v0.2.3 ([e9b5b95](https://github.com/gperdomor/nx-tools/commit/e9b5b95))

- **nx-container:** provenance 'false' ignored ([6868733](https://github.com/gperdomor/nx-tools/commit/6868733))

- **nx-container:** relaxed dependencies ranges ([6f24d36](https://github.com/gperdomor/nx-tools/commit/6f24d36))

### ❤️ Thank You

- Dan Iosif
- Gustavo Perdomo
- Lehoczky Zoltán @Lehoczky
- Nicolas Dubois
- Rene Bonilla

# Changelog

This file was generated using [@jscutlery/semver](https://github.com/jscutlery/semver).

## [3.0.3](https://github.com/gperdomor/nx-tools/compare/nx-docker@3.0.1...nx-docker@3.0.3) (2022-08-03)

### Features

- **nx-docker:** A new INPUT_CREATE_BUILDER env variable is handled, when is true, a new builder context is created for each app and removed after build execution. This is neccesary to run `npx nx affected --base=$NX_BASE --head=$NX_HEAD --target=docker` inside GitLab Runner to avoid errors related to the build context

## [3.0.1](https://github.com/gperdomor/nx-tools/compare/nx-docker@3.0.0...nx-docker@3.0.1) (2022-07-11)

### Bug Fixes

- **nx-docker:** write metadata to folder .nx-docker on CI environments ([12d56c3](https://github.com/gperdomor/nx-tools/commit/12d56c36d4f578b2a92d9e87126479959c371c13))

## [3.0.0](https://github.com/gperdomor/nx-tools/compare/nx-docker@3.0.0-alpha.3...nx-docker@3.0.0) (2022-06-14)

## [3.0.0-alpha.3](https://github.com/gperdomor/nx-tools/compare/nx-docker@3.0.0-alpha.2...nx-docker@3.0.0-alpha.3) (2022-06-14)

### Features

- several updates and nx bump ([e0ad550](https://github.com/gperdomor/nx-tools/commit/e0ad550db010d1710b6729911aae9d432aaf5ffb))

## [3.0.0-alpha.2](https://github.com/gperdomor/nx-tools/compare/nx-docker@3.0.0-alpha.1...nx-docker@3.0.0-alpha.2) (2022-04-29)

### Features

- chore: bump nx to 14.0.5
- other deps updates

## [3.0.0-alpha.1](https://github.com/nx-tools/nx-tools/compare/nx-docker@2.3.0...nx-docker@3.0.0-alpha.1) (2022-04-09)

### ⚠ BREAKING CHANGES

- **nx-docker:** Dropped support for Node 12

### Features

- **nx-docker:** move to swc ([dc1fd5d](https://github.com/nx-tools/nx-tools/commit/dc1fd5daa57e0ad2f57f62d9aba2cb7822c2f95d))

# [2.3.0](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.2.0...nx-docker@2.3.0) (2022-02-04)

### Features

- **nx-docker:** add add-hosts, cgroup-parent, shm-size, ulimit inputs ([59a0dd2](https://github.com/gperdomor/nx-tools/commit/59a0dd295e3c0e6c709df53dc3f47995d4549a51))

# [2.2.0](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.1.0...nx-docker@2.2.0) (2022-01-02)

### Features

- update versions ([950dc36](https://github.com/gperdomor/nx-tools/commit/950dc36612a94df3f5d87422ee7e38a25c806eec))

## [2.1.0](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.0.2...nx-docker@2.1.0) (2022-01-02)

### Bug Fixes

- **nx-docker:** fix core version ([6a8f96b](https://github.com/gperdomor/nx-tools/commit/6a8f96b1060c1affd1f7e5532009b27c84fa2f5d))

# [2.0.2](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.0.1...nx-docker@2.0.2) (2021-11-25)

- Set tslib@^2.1.0 as peerDependencies

# [2.0.1](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.0.0...nx-docker@2.0.1) (2021-11-25)

- Removed tslib from peerDependencies

# [2.0.0](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.0.0-alpha.3...nx-docker@2.0.0) (2021-11-23)

- No changes from alpha.3

# [2.0.0-alpha.3](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.0.0-alpha.2...nx-docker@2.0.0-alpha.3) (2021-11-08)

- bump @nx-tools/docker-metadata to 2.0.0-alpha.3

# [2.0.0-alpha.2](https://github.com/gperdomor/nx-tools/compare/nx-docker@2.0.0-alpha.1...nx-docker@2.0.0-alpha.2) (2021-11-05)

### Features

- **nx-docker:** added support for prefixed env variable names ([cc32071](https://github.com/gperdomor/nx-tools/commit/cc32071fecb796d2801652dd8d711463871805a9))
- bump @nx-tools/core to 2.0.0-alpha.2
- bump @nx-tools/docker-metadata to 2.0.0-alpha.2

## 2.0.0-alpha.1 (2021-10-06)

### Bug Fixes

- **nx-docker:** handle not POSIX compilant names

### Features

- **nx-docker:** general improvements
- **nx-docker:** releasing using @jscutlery/semver
- **nx-docker:** updated to nx 12.9.0
- **nx-docker:** updated dependencies

### BREAKING CHANGES

- **nx-docker:** Changes in configuration schema
- **@nx-tools/docker-metadata:** is now an optional dependency

## 1.0.0 (2021-06-14)

- Initial release
