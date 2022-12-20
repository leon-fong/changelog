# changelogens

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]

Forked from [changelogen](https://github.com/unjs/changelogen)

Changes in this fork:
 - Disable emoji before the title
 - Add the current date after the version
 - Show only the name of the contributor in markdown

## Quick Start

Generate changelog in markdown format and show in console:

```sh
npx changelogens@latest
```

Generate changelog, bump version in `package.json` automatically and update `CHANGELOG.md` (without commit)

```sh
npx changelogens@latest --bump
```

Bump version, update `CHANGELOG.md` and make a git commit and tag:

```sh
npx changelogens@latest --release
```

## CLI Usage

```sh
npx changelogens@latest [...args] [<rootDir>]
```

**Arguments:**

- `--from`: Start commit reference. When not provided, **latest git tag** will be used as default.
- `--to`: End commit reference. When not provided, **latest commit in HEAD** will be used as default.
- `--rootDir`: Path to git repository. When not provided, **current working directory** will be used as as default.
- `--output`: Changelog file name to create or update. Defaults to `CHANGELOG.md` and resolved relative to rootDir. Use `--no-output` to write to console only.
- `--bump`: Determine semver change and update version in `package.json`.
- `--release`. Bumps version in `package.json` and creates commit and git tags using local `git`. You can disable commit using `--no-commit` and tag using `--no-tag`.
- `-r`: Release as specific version.

## Configuration

Configuration is loaded by [unjs/c12](https://github.com/unjs/c12) from cwd. You can use either `changelog.json`, `changelog.{ts,js,mjs,cjs}`, `.changelogrc` or use the `changelog` field in `package.json`.

See [./src/config.ts](./src/config.ts) for available options and defaults.


<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/changelogens?style=flat-square
[npm-version-href]: https://www.npmjs.com/package/changelogens

[npm-downloads-src]: https://img.shields.io/npm/dm/changelogens?style=flat-square
[npm-downloads-href]: https://www.npmjs.com/package/changelogens
