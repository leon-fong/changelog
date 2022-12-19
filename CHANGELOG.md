# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## v0.5.0

[compare changes](https://github.com/unjs/changelogen/compare/...v0.5.0)


### Features

  - Generate breaking changes section ([cc0b427](https://github.com/unjs/changelogen/commit/cc0b427))
  - Add missing commitlint types ([#6](https://github.com/unjs/changelogen/pull/6))
  - GetGitDiff ignores from ([#17](https://github.com/unjs/changelogen/pull/17))
  - Add gitmoji support ([#22](https://github.com/unjs/changelogen/pull/22))
  - Auto-update changelog files ([#24](https://github.com/unjs/changelogen/pull/24))
  - Support `--bump` to update version while generating changelog ([9bf9aff](https://github.com/unjs/changelogen/commit/9bf9aff))
  - Basic `--release` support ([934c487](https://github.com/unjs/changelogen/commit/934c487))
  - Generate markdown links when github is provided ([ffe1d08](https://github.com/unjs/changelogen/commit/ffe1d08))
  - **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/unjs/changelogen/commit/d348943))
  - Handle new version before generating changelog ([fd56f6b](https://github.com/unjs/changelogen/commit/fd56f6b))
  - Expose `determineSemverChange` and `bumpVersion` ([5451f18](https://github.com/unjs/changelogen/commit/5451f18))
  - Infer github config from package.json ([#37](https://github.com/unjs/changelogen/pull/37))
  - ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/unjs/changelogen/pull/46))

### Fixes

  - Avoid `.exec` for multi matches ([7c612fc](https://github.com/unjs/changelogen/commit/7c612fc))
  - Format names for case matching ([ece2d90](https://github.com/unjs/changelogen/commit/ece2d90))
  - **cli:** Use `/usr/bin/env` ([#5](https://github.com/unjs/changelogen/pull/5))
  - Remove `general` in entries without scope ([31a0861](https://github.com/unjs/changelogen/commit/31a0861))
  - Expose `./config` ([#10](https://github.com/unjs/changelogen/pull/10))
  - Use `getCurrentGitRef` ([#15](https://github.com/unjs/changelogen/pull/15))
  - **parse:** ⚠️  `references` with type ([#27](https://github.com/unjs/changelogen/pull/27))
  - Convertminor to patch for 0.x versions ([011b6a1](https://github.com/unjs/changelogen/commit/011b6a1))
  - Run release step last ([b052f55](https://github.com/unjs/changelogen/commit/b052f55))
  - Handle breaking change commits for bumping ([f7ffaa4](https://github.com/unjs/changelogen/commit/f7ffaa4))
  - Show original semver type without 0.x changes in log ([ddd818a](https://github.com/unjs/changelogen/commit/ddd818a))
  - Use `v` prefix for git tag and annotate ([bf6b5da](https://github.com/unjs/changelogen/commit/bf6b5da))
  - Add missing annotate message ([157b0c5](https://github.com/unjs/changelogen/commit/157b0c5))
  - Use last commit for changelog diff ([6ac4b4b](https://github.com/unjs/changelogen/commit/6ac4b4b))
  - Use h2 for title ([fc0967c](https://github.com/unjs/changelogen/commit/fc0967c))
  - Import semver as default import ([3bd0b61](https://github.com/unjs/changelogen/commit/3bd0b61))
  - Use `creatordate` to find last tag ([#39](https://github.com/unjs/changelogen/pull/39))
  - Use release version in changelog title ([04671a6](https://github.com/unjs/changelogen/commit/04671a6))
  - Let `--output` work without value ([#43](https://github.com/unjs/changelogen/pull/43))
  - Consider docs and refactor as semver patch for bump ([648ccf1](https://github.com/unjs/changelogen/commit/648ccf1))
  - Only skip non breaking `chre(deps)` ([20e622e](https://github.com/unjs/changelogen/commit/20e622e))
  - **markdown:** Avoid rendering `noreply.github.com` emails ([4871721](https://github.com/unjs/changelogen/commit/4871721))
  - Avoid rendering authors with `[bot]` in their name ([4f3f644](https://github.com/unjs/changelogen/commit/4f3f644))
  - Format name to avoid duplicates ([f74a988](https://github.com/unjs/changelogen/commit/f74a988))
  - Remove emoji ([d71e49e](https://github.com/unjs/changelogen/commit/d71e49e))

### Refactors

  - Update emojies ([3c4fbac](https://github.com/unjs/changelogen/commit/3c4fbac))
  - Update types ([6f19cb3](https://github.com/unjs/changelogen/commit/6f19cb3))
  - ⚠️  Use flat scopes ([8e33e93](https://github.com/unjs/changelogen/commit/8e33e93))
  - Use lines array for constructing markdown ([#16](https://github.com/unjs/changelogen/pull/16))
  - Only return contributor's name ([04073bc](https://github.com/unjs/changelogen/commit/04073bc))

### Documentation

  - Small improvement ([#4](https://github.com/unjs/changelogen/pull/4))
  - Use `npx changelogen@latest` to ensure using latest version ([8ec40b5](https://github.com/unjs/changelogen/commit/8ec40b5))
  - Fix from format ([4373a86](https://github.com/unjs/changelogen/commit/4373a86))
  - Update README ([ca1f935](https://github.com/unjs/changelogen/commit/ca1f935))

### Build

  - Use dynamic import for execa for cjs support ([a794cf1](https://github.com/unjs/changelogen/commit/a794cf1))

### Chore

  - Disable starter test ([9edd62d](https://github.com/unjs/changelogen/commit/9edd62d))
  - **release:** 0.0.2 ([38d7ba1](https://github.com/unjs/changelogen/commit/38d7ba1))
  - **release:** 0.0.3 ([1c0dcb7](https://github.com/unjs/changelogen/commit/1c0dcb7))
  - **release:** 0.0.4 ([125fc28](https://github.com/unjs/changelogen/commit/125fc28))
  - **release:** 0.0.5 ([0fb47ec](https://github.com/unjs/changelogen/commit/0fb47ec))
  - **release:** 0.0.6 ([ce317f8](https://github.com/unjs/changelogen/commit/ce317f8))
  - Comment unused fn ([9735e2e](https://github.com/unjs/changelogen/commit/9735e2e))
  - **release:** 0.1.0 ([79d6a90](https://github.com/unjs/changelogen/commit/79d6a90))
  - **release:** 0.1.1 ([37c407c](https://github.com/unjs/changelogen/commit/37c407c))
  - Update lockfile and vitest config ([48f609b](https://github.com/unjs/changelogen/commit/48f609b))
  - Use changelogen release flow ([2a8bb4f](https://github.com/unjs/changelogen/commit/2a8bb4f))
  - **release:** 0.2.0 ([0ee9ecf](https://github.com/unjs/changelogen/commit/0ee9ecf))
  - **release:** 0.2.1 ([99c4e6e](https://github.com/unjs/changelogen/commit/99c4e6e))
  - **release:** 0.2.2 ([d0ef976](https://github.com/unjs/changelogen/commit/d0ef976))
  - **release:** 0.2.3 ([8487e91](https://github.com/unjs/changelogen/commit/8487e91))
  - **release:** 0.3.0 ([cdc7dd4](https://github.com/unjs/changelogen/commit/cdc7dd4))
  - **release:** V0.3.1 ([25d8acc](https://github.com/unjs/changelogen/commit/25d8acc))
  - **release:** V0.3.2 ([5c2babc](https://github.com/unjs/changelogen/commit/5c2babc))
  - Manually update old changelog entries ([c3ff561](https://github.com/unjs/changelogen/commit/c3ff561))
  - Update dependencies ([c210976](https://github.com/unjs/changelogen/commit/c210976))
  - Fix typecheck ([8796cf1](https://github.com/unjs/changelogen/commit/8796cf1))
  - **release:** V0.3.3 ([f4f42a3](https://github.com/unjs/changelogen/commit/f4f42a3))
  - **release:** V0.3.4 ([6fc5087](https://github.com/unjs/changelogen/commit/6fc5087))
  - **release:** V0.3.5 ([3828bda](https://github.com/unjs/changelogen/commit/3828bda))
  - **release:** V0.4.0 ([a3cafa9](https://github.com/unjs/changelogen/commit/a3cafa9))
  - Update renovate config ([#54](https://github.com/unjs/changelogen/pull/54))

### Tests

  - Update snapshot ([102aa98](https://github.com/unjs/changelogen/commit/102aa98))
  - Update snapshot ([b264c80](https://github.com/unjs/changelogen/commit/b264c80))

#### ⚠️  Breaking Changes

  - **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/unjs/changelogen/commit/d348943))
  - ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/unjs/changelogen/pull/46))
  - **parse:** ⚠️  `references` with type ([#27](https://github.com/unjs/changelogen/pull/27))
  - ⚠️  Use flat scopes ([8e33e93](https://github.com/unjs/changelogen/commit/8e33e93))

### Contributors

- Fanglm
- Nozomu Ikuta
- Pooya Parsa
- Lvjiaxuan
- Ahad Birang
- Conner
- Anthony Fu
- 三咲智子
- Julien Ripouteau
- Sébastien Chopin

## v0.4.0

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.5...v0.4.0)


### 🚀 Enhancements

  - ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/unjs/changelogen/pull/46))

### 🩹 Fixes

  - **markdown:** Avoid rendering `noreply.github.com` emails ([4871721](https://github.com/unjs/changelogen/commit/4871721))
  - Avoid rendering authors with `[bot]` in their name ([4f3f644](https://github.com/unjs/changelogen/commit/4f3f644))
  - Format name to avoid duplicates ([f74a988](https://github.com/unjs/changelogen/commit/f74a988))

#### ⚠️  Breaking Changes

  - ⚠️  Resolve github usernames using `ungh/ungh` ([#46](https://github.com/unjs/changelogen/pull/46))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))

## v0.3.5

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.4...v0.3.5)


### 🩹 Fixes

  - Only skip non breaking `chre(deps)` ([20e622e](https://github.com/unjs/changelogen/commit/20e622e))

### ❤️  Contributors

- Pooya Parsa

## v0.3.4

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.3...v0.3.4)


### 🚀 Enhancements

  - Infer github config from package.json ([#37](https://github.com/unjs/changelogen/pull/37))

### ❤️  Contributors

- Pooya Parsa

## v0.3.3

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.2...v0.3.3)


### 🚀 Enhancements

  - Expose `determineSemverChange` and `bumpVersion` ([5451f18](https://github.com/unjs/changelogen/commit/5451f18))

### 🩹 Fixes

  - Let `--output` work without value ([#43](https://github.com/unjs/changelogen/pull/43))
  - Consider docs and refactor as semver patch for bump ([648ccf1](https://github.com/unjs/changelogen/commit/648ccf1))

### 🏡 Chore

  - Manually update old changelog entries ([c3ff561](https://github.com/unjs/changelogen/commit/c3ff561))
  - Update dependencies ([c210976](https://github.com/unjs/changelogen/commit/c210976))
  - Fix typecheck ([8796cf1](https://github.com/unjs/changelogen/commit/8796cf1))

### ❤️  Contributors

- Lvjiaxuan
- Pooya Parsa

## v0.3.2

[compare changes](https://github.com/unjs/changelogen/compare/v0.3.1...v0.3.2)


### 🩹 Fixes

  - Use release version in changelog title ([04671a6](https://github.com/unjs/changelogen/commit/04671a6))

### ❤️  Contributors

- Pooya Parsa

## 0.3.1


### 🚀 Enhancements

  - Handle new version before generating changelog ([fd56f6b](https://github.com/unjs/changelogen/commit/fd56f6b))

### 🩹 Fixes

  - Use `creatordate` to find last tag ([#39](https://github.com/unjs/changelogen/pull/39))

### ❤️  Contributors

- Ahad Birang
- Pooya Parsa

## 0.3.0


### 🚀 Enhancements

  - **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/unjs/changelogen/commit/d348943))

#### ⚠️  Breaking Changes

  - **cli:** ⚠️  Show changelog in CLI unless bumping or releasing ([d348943](https://github.com/unjs/changelogen/commit/d348943))

### ❤️  Contributors

- Pooya Parsa

## 0.2.3


### 🩹 Fixes

  - Import semver as default import ([3bd0b61](https://github.com/unjs/changelogen/commit/3bd0b61))

### ❤️  Contributors

- Pooya Parsa

## 0.2.2


### 🚀 Enhancements

  - Generate markdown links when github is provided ([ffe1d08](https://github.com/unjs/changelogen/commit/ffe1d08))

### ✅ Tests

  - Update snapshot ([b264c80](https://github.com/unjs/changelogen/commit/b264c80))

### ❤️  Contributors

- Pooya Parsa

## 0.2.1


### 🩹 Fixes

  - Use last commit for changelog diff (6ac4b4b)
  - Use h2 for title (fc0967c)

### ✅ Tests

  - Update snapshot (102aa98)

### ❤️  Contributors

- Pooya Parsa

## 0.2.0


### 🚀 Enhancements

  - GetGitDiff ignores from (#17)
  - Add gitmoji support (#22)
  - Auto-update changelog files (#24)
  - Support `--bump` to update version while generating changelog (9bf9aff)
  - Basic `--release` support (934c487)

### 🩹 Fixes

  - Expose `./config` (#10)
  - Use `getCurrentGitRef` (#15)
  - **parse:** ⚠️  `references` with type (#27)
  - Convertminor to patch for 0.x versions (011b6a1)
  - Run release step last (b052f55)
  - Handle breaking change commits for bumping (f7ffaa4)
  - Show original semver type without 0.x changes in log (ddd818a)
  - Use `v` prefix for git tag and annotate (bf6b5da)
  - Add missing annotate message (157b0c5)

### 💅 Refactors

  - Use lines array for constructing markdown (#16)

### 🏡 Chore

  - Update lockfile and vitest config (48f609b)
  - Use changelogen release flow (2a8bb4f)

#### ⚠️  Breaking Changes

  - **parse:** ⚠️  `references` with type (#27)

### ❤️  Contributors

- Anthony Fu
- Conner
- Pooya Parsa
- 三咲智子

### 0.1.1


### Bug Fixes

* remove `general` in entries without scope ([31a0861](https://github.com/unjs/changelogen/commit/31a08615bb7da611dcaefe33b510d23aa7d2cc29))

## 0.1.0


### ⚠ BREAKING CHANGES

* use flat scopes

* use flat scopes ([8e33e93](https://github.com/unjs/changelogen/commit/8e33e93e6c4aa4b0b727d351fd73590626d1d6ce))

### 0.0.6

### 0.0.5


### Features

* add missing commitlint types ([#6](https://github.com/unjs/changelogen/issues/6)) ([0a6deef](https://github.com/unjs/changelogen/commit/0a6deefae9a433bbb2136ac8675976ac455dd159))

### 0.0.4


### Bug Fixes

* **cli:** use `/usr/bin/env` (resolves [#5](https://github.com/unjs/changelogen/issues/5)) ([e4218cc](https://github.com/unjs/changelogen/commit/e4218cc08d07b597137469396ba83ec709d7f174))

### 0.0.3


### Features

* generate breaking changes section ([cc0b427](https://github.com/unjs/changelogen/commit/cc0b4272543ffc012d15f038ffa62cdcaca35a44))


### Bug Fixes

* avoid `.exec` for multi matches ([7c612fc](https://github.com/unjs/changelogen/commit/7c612fc4e698e9f8fa1554405efb19b51d7c412f))
* format names for case matching ([ece2d90](https://github.com/unjs/changelogen/commit/ece2d9067171e2b34f45f3d86c28912e90106a6c))

### 0.0.2 (2022-05-02)
