To recreate, run `pnpm i && pnpm build` then you can open up dist/assets/polyfills-legacy.[hash].js
Expect to see valid es5 code, but contains arrow functions. Which is unexpected due to targetting
ie 11 with legacy plugin
