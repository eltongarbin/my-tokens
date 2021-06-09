# 1.0.0 (2021-06-09)

### Bug Fixes

- package.json & yarn.lock to reduce vulnerabilities ([#133](https://github.com/eltongarbin/my-tokens/issues/133)) ([0585a7d](https://github.com/eltongarbin/my-tokens/commit/0585a7d79c3c7fb652ad26be55c27f00e9809cae))

### Features

- Include fonts declaration file ([#53](https://github.com/eltongarbin/my-tokens/issues/53)) ([46c8c24](https://github.com/eltongarbin/my-tokens/commit/46c8c245890d8418ab9ceacd35071988b61c32c9))
- includes font types ([#50](https://github.com/eltongarbin/my-tokens/issues/50)) ([9af4c00](https://github.com/eltongarbin/my-tokens/commit/9af4c0074735a9acc27dd7201701fd7d1017f8b7))
- mobile build configs ([#51](https://github.com/eltongarbin/my-tokens/issues/51)) ([b6da9f2](https://github.com/eltongarbin/my-tokens/commit/b6da9f26f02caac395d39c43a935630bdb6b68b4))

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.0.1](https://github.com/eltongarbin/my-tokens/compare/v2.0.0...v2.0.1) (2021-06-07)

### Bug Fixes

- package.json & yarn.lock to reduce vulnerabilities ([#133](https://github.com/eltongarbin/my-tokens/issues/133)) ([0585a7d](https://github.com/eltongarbin/my-tokens/commit/0585a7d79c3c7fb652ad26be55c27f00e9809cae))

## 2.0.0 (July 21, 2020)

### Changed

- Package structure to maintain a separation between platforms (PRs: [#51](https://github.com/eltongarbin/my-tokens/pull/51), [#50](https://github.com/eltongarbin/my-tokens/pull/50))

  ```
    /dist
      - /android
      - /assets
      - /ios
      - /web
  ```

### Added

- Font files used in design-system (Avenir, NunitoSans). (PR [#50](https://github.com/eltongarbin/my-tokens/pull/50))
- Mobile token files. (PR [#51](https://github.com/eltongarbin/my-tokens/pull/51))
- Font declaration file for web (@font-faces). (PR [#53](https://github.com/eltongarbin/my-tokens/pull/53))

## 1.0.0 (June 23, 2020)

### First stable release :rocket:

- Tokens remodeled and separated by categories, follow the [document](https://eltongarbin.github.io/my-tokens/)
- Design tokens avaliable in:
  - @eltongarbin/tokens (npm)

## 0.1.0 (September 29, 2019)

### First tokens :tada::clap:

- Added base colors tokens [See Adobe XD prototype](https://xd.adobe.com/spec/780b750c-c8d9-4a3c-7d41-042f4c68f830-0e3a/)
- Added base font-family by platform
