---
title: Monthly updates (February 2024)
description: 60 releases this month! What's new in the UnJS ecosystem?
authors:
  - name:
    picture:
    twitter:
category:
  - releases
packages:
  - automd
  - c12
  - citty
  - confbox
  - crossws
  - db0
  - destr
  - h3
  - ipx
  - listhen
  - mlly
  - node-fetch-native
  - scule
  - ufo
  - undocs
  - webpackbar
publishedAt: 2024-02-28T00:56:03.083Z
modifiedAt: 2024-02-28T00:56:03.083Z
---

## automd

This month, we release 13 new releases (0 major release, 2 minor releases and 11 patch releases):

- [v0.3.6](https://github.com/unjs/automd/releases/tag/v0.3.6)
- [v0.3.5](https://github.com/unjs/automd/releases/tag/v0.3.5)
- [v0.3.4](https://github.com/unjs/automd/releases/tag/v0.3.4)
- [v0.3.3](https://github.com/unjs/automd/releases/tag/v0.3.3)
- [v0.3.2](https://github.com/unjs/automd/releases/tag/v0.3.2)
- [v0.3.1](https://github.com/unjs/automd/releases/tag/v0.3.1)
- [v0.3.0](https://github.com/unjs/automd/releases/tag/v0.3.0)
- [v0.2.0](https://github.com/unjs/automd/releases/tag/v0.2.0)
- [v0.1.5](https://github.com/unjs/automd/releases/tag/v0.1.5)
- [v0.1.4](https://github.com/unjs/automd/releases/tag/v0.1.4)
- [v0.1.3](https://github.com/unjs/automd/releases/tag/v0.1.3)
- [v0.1.2](https://github.com/unjs/automd/releases/tag/v0.1.2)
- [v0.1.1](https://github.com/unjs/automd/releases/tag/v0.1.1)

### enhancements

- **file:** Allow rendering in code block ([fbb4003](https://github.com/unjs/automd/commit/fbb4003))

### fixes

- **pm-x:** Make version optional ([ffada82](https://github.com/unjs/automd/commit/ffada82))
- **parser:** Support unicode ([21ed0e1](https://github.com/unjs/automd/commit/21ed0e1))
- **parser:** Support unicode ([7ed127a](https://github.com/unjs/automd/commit/7ed127a))
- **watcher:** Debounce event handling ([0ad9c81](https://github.com/unjs/automd/commit/0ad9c81))
- **pm-i:** Don't modify global array! ([977c2c3](https://github.com/unjs/automd/commit/977c2c3))
- Respect multiline description ([#39](https://github.com/unjs/automd/pull/39))

### refactors

- Switch to mdbox ([5698d0d](https://github.com/unjs/automd/commit/5698d0d))

### documentation

- Use `field-group` & `field` component in args section ([#34](https://github.com/unjs/automd/pull/34))
- Update `file` to `input` for cli usage ([#38](https://github.com/unjs/automd/pull/38))
- Update undocs ([f3c90e3](https://github.com/unjs/automd/commit/f3c90e3))
- Update `src` values to use relative path ([bbe3c12](https://github.com/unjs/automd/commit/bbe3c12))

### 🔥 performance

- Resolve config once ([62a757a](https://github.com/unjs/automd/commit/62a757a))
### fixes
- Graceful issue handling ([c02dc1b](https://github.com/unjs/automd/commit/c02dc1b))
- Return original content if no changes ([49421d3](https://github.com/unjs/automd/commit/49421d3))
- **parser:** Check `<!-- /automd -->` to be start of a line ([03a71a5](https://github.com/unjs/automd/commit/03a71a5))
### refactors
- Improve badges ([db2fb78](https://github.com/unjs/automd/commit/db2fb78))
- ⚠️  Split transform utils ([014838b](https://github.com/unjs/automd/commit/014838b))
- Avoid `node:` static imports ([2ffa57b](https://github.com/unjs/automd/commit/2ffa57b))
- Simplify `node:` usage for now ([40e49d9](https://github.com/unjs/automd/commit/40e49d9))
- Improve cli impl ([9c6e747](https://github.com/unjs/automd/commit/9c6e747))
### documentation
- Various fixes ([#16](https://github.com/unjs/automd/pull/16))
- Use unjs badge colors ([#17](https://github.com/unjs/automd/pull/17))
- Fix syntax example ([#18](https://github.com/unjs/automd/pull/18))
- Update with auto generated examples! ([375367a](https://github.com/unjs/automd/commit/375367a))

### ⚠️ breaking changes

- ⚠️  Allow to specify `input` and `output` ([92baec6](https://github.com/unjs/automd/commit/92baec6))
- ⚠️  Split transform utils ([014838b](https://github.com/unjs/automd/commit/014838b))

## c12

This month, we release 3 new releases (0 major release, 3 minor releases and 0 patch release):

- [v1.9.0](https://github.com/unjs/c12/releases/tag/v1.9.0)
- [v1.8.0](https://github.com/unjs/c12/releases/tag/v1.8.0)
- [v1.7.0](https://github.com/unjs/c12/releases/tag/v1.7.0)

### enhancements

- Use confbox (adds `.toml`, `.yaml`, `.yml` new extensions!) ([#140](https://github.com/unjs/c12/pull/140))

### 🔥 performance

- Lazy load `chokidar` ([a8b3a1d](https://github.com/unjs/c12/commit/a8b3a1d))

### fixes

- Deep merge rc sources with defu ([#139](https://github.com/unjs/c12/pull/139))
- **watcher:** Watch `.config` and all supported extensions ([94c8181](https://github.com/unjs/c12/commit/94c8181))

## citty

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v0.1.6](https://github.com/unjs/citty/releases/tag/v0.1.6)

### fixes

- **usage:** Render valueHint for positional args ([dbd1d92](https://github.com/unjs/citty/commit/dbd1d92))

## confbox

This month, we release 2 new releases (0 major release, 0 minor release and 2 patch releases):

- [v0.1.2](https://github.com/unjs/confbox/releases/tag/v0.1.2)
- [v0.1.1](https://github.com/unjs/confbox/releases/tag/v0.1.1)

### enhancements

- Switch to smol-toml for toml parsing ([#2](https://github.com/unjs/confbox/pull/2))

## crossws

This month, we release 7 new releases (0 major release, 1 minor release and 6 patch releases):

- [v0.2.4](https://github.com/unjs/crossws/releases/tag/v0.2.4)
- [v0.2.3](https://github.com/unjs/crossws/releases/tag/v0.2.3)
- [v0.2.2](https://github.com/unjs/crossws/releases/tag/v0.2.2)
- [v0.2.1](https://github.com/unjs/crossws/releases/tag/v0.2.1)
- [v0.2.0](https://github.com/unjs/crossws/releases/tag/v0.2.0)
- [v0.1.3](https://github.com/unjs/crossws/releases/tag/v0.1.3)
- [v0.1.2](https://github.com/unjs/crossws/releases/tag/v0.1.2)

### enhancements

- Auto generated peer id ([a3b61f5](https://github.com/unjs/crossws/commit/a3b61f5))
- Basic pubsub support for node ([4bd61ca](https://github.com/unjs/crossws/commit/4bd61ca))

### refactors

- Improve peer inspect message ([9f7e1f0](https://github.com/unjs/crossws/commit/9f7e1f0))

### documentation

- Update content ([6d78e12](https://github.com/unjs/crossws/commit/6d78e12))

### fixes

- **node:** Respect `x-forwarded` for client id ([3f8bd0c](https://github.com/unjs/crossws/commit/3f8bd0c))

### ⚠️ breaking changes

- ⚠️  Improve types and api ([2ebacd3](https://github.com/unjs/crossws/commit/2ebacd3))

## db0

This month, we release 2 new releases (0 major release, 0 minor release and 2 patch releases):

- [v0.1.3](https://github.com/unjs/db0/releases/tag/v0.1.3)
- [v0.1.2](https://github.com/unjs/db0/releases/tag/v0.1.2)

### enhancements

- Add bun sqlite support ([d6de297](https://github.com/unjs/db0/commit/d6de297))

### refactors

- Use `createDatabase` ([84c52d8](https://github.com/unjs/db0/commit/84c52d8))
- Update drizzle integration ([74c909e](https://github.com/unjs/db0/commit/74c909e))

### documentation

- Initialize new docs ([c897405](https://github.com/unjs/db0/commit/c897405))

## destr

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v2.0.3](https://github.com/unjs/destr/releases/tag/v2.0.3)

### fixes

- Improve compatibility with runtimes not supporting `String.prototype.at()` ([#102](https://github.com/unjs/destr/pull/102))

## h3

This month, we release 3 new releases (0 major release, 1 minor release and 2 patch releases):

- [v1.11.1](https://github.com/unjs/h3/releases/tag/v1.11.1)
- [v1.11.0](https://github.com/unjs/h3/releases/tag/v1.11.0)
- [v1.10.2](https://github.com/unjs/h3/releases/tag/v1.10.2)

### fixes

- **ws:** Resolve pathname for matching ([4f211f8](https://github.com/unjs/h3/commit/4f211f8))

### documentation

- Update bun ws example ([da464c3](https://github.com/unjs/h3/commit/da464c3))

### ⭐ highlights

- H3 now has a new documentation website (https://h3.unjs.io)
- WebSocket and SSE support added ([read more](https://h3.unjs.io/guide/websocket))

### enhancements

- Add utilities for server-sent events (SSE) ([#586](https://github.com/unjs/h3/pull/586))
- **response:** Add `sendIterable` util ([#655](https://github.com/unjs/h3/pull/655))
- Handler resolver ([#669](https://github.com/unjs/h3/pull/669))
- WebSocket support ([#671](https://github.com/unjs/h3/pull/671))
### fixes
- **serveStatic:** Ensure `etag` header is set before sending 304 response ([#653](https://github.com/unjs/h3/pull/653))
### documentation
- Add basic jsdocs for utils ([c8aa150](https://github.com/unjs/h3/commit/c8aa150))
- Fix typos ([#668](https://github.com/unjs/h3/pull/668), [#665](https://github.com/unjs/h3/pull/665), [#662](https://github.com/unjs/h3/pull/662), [#661](https://github.com/unjs/h3/pull/661), [#658](https://github.com/unjs/h3/pull/658))
- **examples** Add node middleware usage ([#663](https://github.com/unjs/h3/pull/663))
- Refine function usages ([#667](https://github.com/unjs/h3/pull/667))
- Add jsdoc examples ([#672](https://github.com/unjs/h3/pull/672), [#673](https://github.com/unjs/h3/pull/673))

## ipx

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v3.0.1](https://github.com/unjs/ipx/releases/tag/v3.0.1)

### fixes

- **http:** Properly respect `ignoreCacheControl` option ([96a8489](https://github.com/unjs/ipx/commit/96a8489))

## listhen

This month, we release 3 new releases (0 major release, 1 minor release and 2 patch releases):

- [v1.7.2](https://github.com/unjs/listhen/releases/tag/v1.7.2)
- [v1.7.1](https://github.com/unjs/listhen/releases/tag/v1.7.1)
- [v1.7.0](https://github.com/unjs/listhen/releases/tag/v1.7.0)

### fixes

- **dev:** Call dynamic websocket resolver ([7360d27](https://github.com/unjs/listhen/commit/7360d27))

### refactors

- Update to crossws 0.2 api ([b29607f](https://github.com/unjs/listhen/commit/b29607f))

### enhancements

- **ws:** Support dynamic websocket resolver ([7b006e2](https://github.com/unjs/listhen/commit/7b006e2))

## mlly

This month, we release 2 new releases (0 major release, 1 minor release and 1 patch release):

- [v1.6.1](https://github.com/unjs/mlly/releases/tag/v1.6.1)
- [v1.6.0](https://github.com/unjs/mlly/releases/tag/v1.6.0)

### fixes

- **parseStaticImport:** Omit empty import names ([#232](https://github.com/unjs/mlly/pull/232))

### enhancements

- Add declaration type in ESMExport ([#227](https://github.com/unjs/mlly/pull/227))
- **utils:** Add `pathToFileURL` ([cdcbcb7](https://github.com/unjs/mlly/commit/cdcbcb7))

### 🔥 performance

- **resolver:** Stat absolute paths once in fast path ([#229](https://github.com/unjs/mlly/pull/229))
- **resolver:** Remove intermediate `pcall` util ([#230](https://github.com/unjs/mlly/pull/230))
- **resolve:** Enable fast path for file urls ([#231](https://github.com/unjs/mlly/pull/231))
### fixes
- **resolver:** Strictly check input ([778bd73](https://github.com/unjs/mlly/commit/778bd73))

### refactors

- **resolver:** Use pathToFileURL from mlly ([982a7a9](https://github.com/unjs/mlly/commit/982a7a9))
- Strict type checks ([77ebe50](https://github.com/unjs/mlly/commit/77ebe50))

## node-fetch-native

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v1.6.2](https://github.com/unjs/node-fetch-native/releases/tag/v1.6.2)



## scule

This month, we release 1 new release (0 major release, 1 minor release and 0 patch release):

- [v1.3.0](https://github.com/unjs/scule/releases/tag/v1.3.0)

### enhancements

- `titleCase` util ([#74](https://github.com/unjs/scule/pull/74))

## ufo

This month, we release 1 new release (0 major release, 1 minor release and 0 patch release):

- [v1.4.0](https://github.com/unjs/ufo/releases/tag/v1.4.0)

### enhancements

- Add `withFragment` utility ([#193](https://github.com/unjs/ufo/pull/193))
- Add `withoutFragment` util ([#199](https://github.com/unjs/ufo/pull/199))

### 🔥 performance

- **withFragment:** Early return when no hash changes required ([d6ce037](https://github.com/unjs/ufo/commit/d6ce037))

### fixes

- **encodeQueryValue:** Encode the slash character ([#198](https://github.com/unjs/ufo/pull/198))
- Stringify protocol-relative URLs ([#207](https://github.com/unjs/ufo/pull/207))
- **withFragment:** Use `encodeHash` for encoding ([48237ab](https://github.com/unjs/ufo/commit/48237ab))

### refactors

- **resolveUrl:** Decouple from $URL ([#186](https://github.com/unjs/ufo/pull/186))
- Deprecate `$URL` and `createURL` ([f1af9b3](https://github.com/unjs/ufo/commit/f1af9b3))
- **normalizeURL:** Decouple from `$URL` ([9013029](https://github.com/unjs/ufo/commit/9013029))
- **withoutFragment:** Decouple from `withFragment` ([712b8d5](https://github.com/unjs/ufo/commit/712b8d5))

### documentation

- Remove mentioning `$URL` ([65e6be8](https://github.com/unjs/ufo/commit/65e6be8))
- Update normalizeURL example ([011777a](https://github.com/unjs/ufo/commit/011777a))
- Use jsdocs and automd ([#209](https://github.com/unjs/ufo/pull/209))

## undocs

This month, we release 18 new releases (0 major release, 1 minor release and 17 patch releases):

- [v0.2.17](https://github.com/unjs/undocs/releases/tag/v0.2.17)
- [v0.2.16](https://github.com/unjs/undocs/releases/tag/v0.2.16)
- [v0.2.15](https://github.com/unjs/undocs/releases/tag/v0.2.15)
- [v0.2.14](https://github.com/unjs/undocs/releases/tag/v0.2.14)
- [v0.2.13](https://github.com/unjs/undocs/releases/tag/v0.2.13)
- [v0.2.12](https://github.com/unjs/undocs/releases/tag/v0.2.12)
- [v0.2.11](https://github.com/unjs/undocs/releases/tag/v0.2.11)
- [v0.2.10](https://github.com/unjs/undocs/releases/tag/v0.2.10)
- [v0.2.9](https://github.com/unjs/undocs/releases/tag/v0.2.9)
- [v0.2.8](https://github.com/unjs/undocs/releases/tag/v0.2.8)
- [v0.2.7](https://github.com/unjs/undocs/releases/tag/v0.2.7)
- [v0.2.6](https://github.com/unjs/undocs/releases/tag/v0.2.6)
- [v0.2.5](https://github.com/unjs/undocs/releases/tag/v0.2.5)
- [v0.2.4](https://github.com/unjs/undocs/releases/tag/v0.2.4)
- [v0.2.3](https://github.com/unjs/undocs/releases/tag/v0.2.3)
- [v0.2.2](https://github.com/unjs/undocs/releases/tag/v0.2.2)
- [v0.2.1](https://github.com/unjs/undocs/releases/tag/v0.2.1)
- [v0.2.0](https://github.com/unjs/undocs/releases/tag/v0.2.0)

### enhancements

- Add `mdc` on landing card description ([#64](https://github.com/unjs/undocs/pull/64))

### fixes

- Default `themeColor` to `amber` ([e086941](https://github.com/unjs/undocs/commit/e086941))
- Check `item.description` before using `MDC` ([c5f473b](https://github.com/unjs/undocs/commit/c5f473b))
- **nav:** Autmatically resolve to first child if has no index ([28d9d39](https://github.com/unjs/undocs/commit/28d9d39))

### refactors

- Use `yaml` config ([038198a](https://github.com/unjs/undocs/commit/038198a))

### documentation

- Add config page to test automd ([0105f4c](https://github.com/unjs/undocs/commit/0105f4c))

### 🔥 performance

- Use js for CLI impl for now ([8db3a91](https://github.com/unjs/undocs/commit/8db3a91))
- Remove studio to investigate perf ([c258897](https://github.com/unjs/undocs/commit/c258897))
### fixes
- Check first child existence before access ([1b300b6](https://github.com/unjs/undocs/commit/1b300b6))
- Dedup children ([#47](https://github.com/unjs/undocs/pull/47))
- Exclude alerts from first child ([8731ece](https://github.com/unjs/undocs/commit/8731ece))
- Hotfix landing height ([3b689b2](https://github.com/unjs/undocs/commit/3b689b2))
### refactors
- Move config to `.config` ([6f66f9d](https://github.com/unjs/undocs/commit/6f66f9d))

## webpackbar

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v6.0.1](https://github.com/unjs/webpackbar/releases/tag/v6.0.1)

### fixes

- Node 14 compatibility ([#138](https://github.com/unjs/webpackbar/pull/138))