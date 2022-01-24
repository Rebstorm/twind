# @twind/sveltekit

## 1.0.0-next.22

### Patch Changes

- BREAKING: `tw` accepts only a single string argument (use `cx` for more feature) this reduces the bundle size for the shim mode by 0.25kb ([#251](https://github.com/tw-in-js/twind/pull/251))

* `inline` can accept an options object with a `minify` to minify the resulting CSS before injecting it ([#251](https://github.com/tw-in-js/twind/pull/251))

* Updated dependencies [[`877152d1`](https://github.com/tw-in-js/twind/commit/877152d1401287aaeaa3f5405ce3d4c9673f7bf0), [`059f8564`](https://github.com/tw-in-js/twind/commit/059f8564dad74c10125336aad582fccc32036e31), [`b9d64777`](https://github.com/tw-in-js/twind/commit/b9d64777993f824d4468d5ba415e7d8a4d17e6cf), [`f1c1d08f`](https://github.com/tw-in-js/twind/commit/f1c1d08f0661ccbfe0894a887a3c67abbe893bb8), [`efa7bbc0`](https://github.com/tw-in-js/twind/commit/efa7bbc03f1ffe78a4b9c67b4eedd4cacaf07837)]:
  - twind@1.0.0-next.22

## 1.0.0-next.21

### Patch Changes

- BREAKING: rename `inject` to `inline` ([`762c5153`](https://github.com/tw-in-js/twind/commit/762c515362f09e13e93ea8c10aa84109b65f13b3))

- Updated dependencies [[`0a2daf0f`](https://github.com/tw-in-js/twind/commit/0a2daf0f3daf7ebfde103407b5c0e914625c17c9), [`762c5153`](https://github.com/tw-in-js/twind/commit/762c515362f09e13e93ea8c10aa84109b65f13b3)]:
  - twind@1.0.0-next.21

## 1.0.0-next.20

### Patch Changes

- perf: optimize observe to only handle changes on element with class attribute ([`88eeb077`](https://github.com/tw-in-js/twind/commit/88eeb07798e70860c840278ac97e7a2ba6ee8366))

* revert: remove dom sheet ([`6d50cf5f`](https://github.com/tw-in-js/twind/commit/6d50cf5f7bd8fb79caf02a81c30060c8abf2382e))

* Updated dependencies [[`6d50cf5f`](https://github.com/tw-in-js/twind/commit/6d50cf5f7bd8fb79caf02a81c30060c8abf2382e)]:
  - twind@1.0.0-next.20

## 1.0.0-next.19

### Patch Changes

- Updated dependencies [[`1f578c9e`](https://github.com/tw-in-js/twind/commit/1f578c9ede1882ee714db249a6bed48c0e1e3059)]:
  - twind@1.0.0-next.19

## 1.0.0-next.18

### Patch Changes

- add inject(html) helper to simplify extracting CSS and injecting it into the head element ([#247](https://github.com/tw-in-js/twind/pull/247))

- Updated dependencies [[`d3728a92`](https://github.com/tw-in-js/twind/commit/d3728a92bcfd86ca83cb14d10d8dc29fdc181b03)]:
  - twind@1.0.0-next.18

## 1.0.0-next.17

### Patch Changes

- bump to same version ([`ca157601`](https://github.com/tw-in-js/twind/commit/ca1576017f172bfb0ba61e936f0f44d36102016c))

- Updated dependencies [[`ca157601`](https://github.com/tw-in-js/twind/commit/ca1576017f172bfb0ba61e936f0f44d36102016c)]:
  - twind@1.0.0-next.17

## 1.0.0-next.14

### Patch Changes

- add sveltekit integration (@twind/sveltekit) with example ([#245](https://github.com/tw-in-js/twind/pull/245))

- Updated dependencies [[`ed21b253`](https://github.com/tw-in-js/twind/commit/ed21b253ea1403ebfee0f38060b5fa8670bcaebb), [`5d40cc5b`](https://github.com/tw-in-js/twind/commit/5d40cc5bbf2f0f8b2f1769ca95630b7d83d6ef8f), [`f0715269`](https://github.com/tw-in-js/twind/commit/f0715269afe91c7cbaaf97ee7e21bb99080f37b0), [`13b806cd`](https://github.com/tw-in-js/twind/commit/13b806cd3f74550bdc43cdc995026ee6d65b894f), [`82de0d53`](https://github.com/tw-in-js/twind/commit/82de0d53755f35c72fe41200f9091bdc2c960f83)]:
  - @twind/core@1.0.0-next.14