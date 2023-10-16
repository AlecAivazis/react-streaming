## 0.3.16 (2023-10-16)


### Bug Fixes

* `useAsync()`: tolerate functions that don't return a promise ([70b2e86](https://github.com/brillout/react-streaming/commit/70b2e869d634b9bd2bf417db746e2a7f13dd495a))
* add `default` in exports field ([50f2edb](https://github.com/brillout/react-streaming/commit/50f2edb32283193d8829c073835c62db237dc3ca))
* add version to assertion messages ([7e020c1](https://github.com/brillout/react-streaming/commit/7e020c11e080d89c17008d6baf73e4d333f8dcb3))
* align chunk TypeScript type ([0ef0c37](https://github.com/brillout/react-streaming/commit/0ef0c37219e06f0d38cf4b54454fd1d93642c0e7))
* also handle promise rejections ([228013e](https://github.com/brillout/react-streaming/commit/228013e41d3a4431c7d79ae88b296fba8bcfb152))
* avoid 'react-dom/server.node' to be bundled ([02449a7](https://github.com/brillout/react-streaming/commit/02449a76343ce3318622a5578b4a7a97e8039b68))
* disable mode for Node.js Stream Pipe ([65a0cca](https://github.com/brillout/react-streaming/commit/65a0cca9a1893599afefb8b98733c4297223827a))
* disable write after stream destoryed ([660d252](https://github.com/brillout/react-streaming/commit/660d2524400830ec0512a23d7ca360909075f7a7))
* dynamically import required stream implementation ([ee5623b](https://github.com/brillout/react-streaming/commit/ee5623b28138353bcaea6e62b99cca9d49c9cc07))
* ensure suspense state is updated before promise resolves ([9d7c554](https://github.com/brillout/react-streaming/commit/9d7c55402a2d56b3c5f780f835b5f272ab805f7d))
* ensure wrangler doesn't resolve browser entry ([a175d56](https://github.com/brillout/react-streaming/commit/a175d566eb233e0d90c1a891c913fb7fec70d4a6))
* expose disabled status ([f1117c4](https://github.com/brillout/react-streaming/commit/f1117c4b32174599e5634620d930e568c2fb2d9c))
* expose ESM build ([abab731](https://github.com/brillout/react-streaming/commit/abab731de9c9747c72e17cd15c8858f186795ab3))
* fix dynamically loading module once and for all ([351b9e7](https://github.com/brillout/react-streaming/commit/351b9e709d34a872774f6d783922cdb7d9ec519a))
* fix export for worker and deno ([8534637](https://github.com/brillout/react-streaming/commit/85346375cceb07d26de3a9cfcb424e2f52e4de6c))
* fix exports ([#17](https://github.com/brillout/react-streaming/issues/17)) ([b2cce88](https://github.com/brillout/react-streaming/commit/b2cce88e6a35c928fc2595cf07a806caf67f07f3))
* gracefully handle infinite loops ([52f997e](https://github.com/brillout/react-streaming/commit/52f997e532ac8504249d4c4bbc84e35dae490072))
* improve assertion that server files aren't loaded in browser (fix [#22](https://github.com/brillout/react-streaming/issues/22)) ([794dd95](https://github.com/brillout/react-streaming/commit/794dd95fa7332d30deba03e1bc66b1c7a40d8a38))
* improve assertUsage message ([5e94949](https://github.com/brillout/react-streaming/commit/5e94949351857c3141fa4d69d40d03aa5e7055de))
* improve DX upon wrong `useAsync()` usage ([0afba57](https://github.com/brillout/react-streaming/commit/0afba5768090783271ee725f94c801f78992450a))
* improve error handling upon wrong installation ([8802e67](https://github.com/brillout/react-streaming/commit/8802e67df73f2f33618fe82e82e9554f6aa0f8fd))
* improve error message ([4eed291](https://github.com/brillout/react-streaming/commit/4eed291caf45a781a5a095906aecec67dcbcdb75))
* improve import renderToReadableStream() in Node.js ([22494a1](https://github.com/brillout/react-streaming/commit/22494a17177c6f3a35eb7bbd25d791bba18f74c0))
* improve warning ([b5e9a13](https://github.com/brillout/react-streaming/commit/b5e9a139bb87890bd2fd5a52d266214016effb61))
* re-export useStream() for the client-side as well ([c754a78](https://github.com/brillout/react-streaming/commit/c754a780c4b5e6d3e8724eda352ed377f3f1b28c))
* replace export conditions `import`/`require` with `node` ([6f2408f](https://github.com/brillout/react-streaming/commit/6f2408fa219123a9bc4a84149d84ab8a58a284c1))
* simplify exports ([8fbde9c](https://github.com/brillout/react-streaming/commit/8fbde9c3f417535673e2931e50506feb46d1dfad))
* stop loading debug util in browser ([5161e96](https://github.com/brillout/react-streaming/commit/5161e96d701f500f58a96b81b56616a15afe8ccc))
* support being included in ESM bundles (fix [#6](https://github.com/brillout/react-streaming/issues/6)) ([73fad43](https://github.com/brillout/react-streaming/commit/73fad433137d72abdb869a40e71c10aeaf7094a6))
* support being included in webpack ESM bundles as well as webpack CJS bundles ([62f0fb1](https://github.com/brillout/react-streaming/commit/62f0fb17e034ef5c90e4704abedba195ea05d389))
* tolerate earlier injectStream call ([47b35b0](https://github.com/brillout/react-streaming/commit/47b35b0e759885c3216e1719f2c04c3cf4b60fab))
* use `typescript@4.7.0-beta` with `nodenext` instead of ([3293706](https://github.com/brillout/react-streaming/commit/32937062e80dc9275d7163832875d40434af07d8))
* workaround React swallowing errors ([ba4245f](https://github.com/brillout/react-streaming/commit/ba4245f4421714758046712f4256e094a31a76f4))
* writableForReact destory if writableFromUser not available ([68a4d65](https://github.com/brillout/react-streaming/commit/68a4d656df4d9202a28070848708fd8cdddeb74d))


### Features

* add `deps` options to hooks ([#10](https://github.com/brillout/react-streaming/issues/10)) ([b2d20e1](https://github.com/brillout/react-streaming/commit/b2d20e109de09e6c7a163cbbd0799a868260db27))
* add flush option to `injectToStream()` ([e677039](https://github.com/brillout/react-streaming/commit/e677039b6831fa742b1915e791e4d22680684e6a))
* improve hooks DX ([21a9814](https://github.com/brillout/react-streaming/commit/21a9814b97d93548884475f0a50222954024c3b9))


### Reverts

* Revert "dynamic import stream wrappers" ([0abebf6](https://github.com/brillout/react-streaming/commit/0abebf63e87cf0f7c85955fbf328602df797ef66))


### BREAKING CHANGES

* hooks `useAsync()` and `useSsrData()` consolidated into
a single new hook `useAsync()` with a new interface. See `README.md`.



## 0.3.15 (2023-10-16)


### Bug Fixes

* `useAsync()`: tolerate functions that don't return a promise ([70b2e86](https://github.com/brillout/react-streaming/commit/70b2e869d634b9bd2bf417db746e2a7f13dd495a))
* add `default` in exports field ([50f2edb](https://github.com/brillout/react-streaming/commit/50f2edb32283193d8829c073835c62db237dc3ca))
* add version to assertion messages ([7e020c1](https://github.com/brillout/react-streaming/commit/7e020c11e080d89c17008d6baf73e4d333f8dcb3))
* align chunk TypeScript type ([0ef0c37](https://github.com/brillout/react-streaming/commit/0ef0c37219e06f0d38cf4b54454fd1d93642c0e7))
* also handle promise rejections ([228013e](https://github.com/brillout/react-streaming/commit/228013e41d3a4431c7d79ae88b296fba8bcfb152))
* avoid 'react-dom/server.node' to be bundled ([02449a7](https://github.com/brillout/react-streaming/commit/02449a76343ce3318622a5578b4a7a97e8039b68))
* disable mode for Node.js Stream Pipe ([65a0cca](https://github.com/brillout/react-streaming/commit/65a0cca9a1893599afefb8b98733c4297223827a))
* disable write after stream destoryed ([660d252](https://github.com/brillout/react-streaming/commit/660d2524400830ec0512a23d7ca360909075f7a7))
* dynamically import required stream implementation ([ee5623b](https://github.com/brillout/react-streaming/commit/ee5623b28138353bcaea6e62b99cca9d49c9cc07))
* ensure suspense state is updated before promise resolves ([9d7c554](https://github.com/brillout/react-streaming/commit/9d7c55402a2d56b3c5f780f835b5f272ab805f7d))
* ensure wrangler doesn't resolve browser entry ([a175d56](https://github.com/brillout/react-streaming/commit/a175d566eb233e0d90c1a891c913fb7fec70d4a6))
* expose disabled status ([f1117c4](https://github.com/brillout/react-streaming/commit/f1117c4b32174599e5634620d930e568c2fb2d9c))
* expose ESM build ([abab731](https://github.com/brillout/react-streaming/commit/abab731de9c9747c72e17cd15c8858f186795ab3))
* fix dynamically loading module once and for all ([351b9e7](https://github.com/brillout/react-streaming/commit/351b9e709d34a872774f6d783922cdb7d9ec519a))
* fix export for worker and deno ([8534637](https://github.com/brillout/react-streaming/commit/85346375cceb07d26de3a9cfcb424e2f52e4de6c))
* fix exports ([#17](https://github.com/brillout/react-streaming/issues/17)) ([b2cce88](https://github.com/brillout/react-streaming/commit/b2cce88e6a35c928fc2595cf07a806caf67f07f3))
* gracefully handle infinite loops ([52f997e](https://github.com/brillout/react-streaming/commit/52f997e532ac8504249d4c4bbc84e35dae490072))
* improve assertion that server files aren't loaded in browser (fix [#22](https://github.com/brillout/react-streaming/issues/22)) ([794dd95](https://github.com/brillout/react-streaming/commit/794dd95fa7332d30deba03e1bc66b1c7a40d8a38))
* improve assertUsage message ([5e94949](https://github.com/brillout/react-streaming/commit/5e94949351857c3141fa4d69d40d03aa5e7055de))
* improve DX upon wrong `useAsync()` usage ([0afba57](https://github.com/brillout/react-streaming/commit/0afba5768090783271ee725f94c801f78992450a))
* improve error handling upon wrong installation ([8802e67](https://github.com/brillout/react-streaming/commit/8802e67df73f2f33618fe82e82e9554f6aa0f8fd))
* improve error message ([4eed291](https://github.com/brillout/react-streaming/commit/4eed291caf45a781a5a095906aecec67dcbcdb75))
* improve import renderToReadableStream() in Node.js ([22494a1](https://github.com/brillout/react-streaming/commit/22494a17177c6f3a35eb7bbd25d791bba18f74c0))
* improve warning ([b5e9a13](https://github.com/brillout/react-streaming/commit/b5e9a139bb87890bd2fd5a52d266214016effb61))
* re-export useStream() for the client-side as well ([c754a78](https://github.com/brillout/react-streaming/commit/c754a780c4b5e6d3e8724eda352ed377f3f1b28c))
* replace export conditions `import`/`require` with `node` ([6f2408f](https://github.com/brillout/react-streaming/commit/6f2408fa219123a9bc4a84149d84ab8a58a284c1))
* simplify exports ([8fbde9c](https://github.com/brillout/react-streaming/commit/8fbde9c3f417535673e2931e50506feb46d1dfad))
* stop loading debug util in browser ([5161e96](https://github.com/brillout/react-streaming/commit/5161e96d701f500f58a96b81b56616a15afe8ccc))
* support being included in ESM bundles (fix [#6](https://github.com/brillout/react-streaming/issues/6)) ([73fad43](https://github.com/brillout/react-streaming/commit/73fad433137d72abdb869a40e71c10aeaf7094a6))
* support being included in webpack ESM bundles as well as webpack CJS bundles ([62f0fb1](https://github.com/brillout/react-streaming/commit/62f0fb17e034ef5c90e4704abedba195ea05d389))
* tolerate earlier injectStream call ([47b35b0](https://github.com/brillout/react-streaming/commit/47b35b0e759885c3216e1719f2c04c3cf4b60fab))
* use `typescript@4.7.0-beta` with `nodenext` instead of ([3293706](https://github.com/brillout/react-streaming/commit/32937062e80dc9275d7163832875d40434af07d8))
* workaround React swallowing errors ([ba4245f](https://github.com/brillout/react-streaming/commit/ba4245f4421714758046712f4256e094a31a76f4))
* writableForReact destory if writableFromUser not available ([68a4d65](https://github.com/brillout/react-streaming/commit/68a4d656df4d9202a28070848708fd8cdddeb74d))


### Features

* add `deps` options to hooks ([#10](https://github.com/brillout/react-streaming/issues/10)) ([b2d20e1](https://github.com/brillout/react-streaming/commit/b2d20e109de09e6c7a163cbbd0799a868260db27))
* add flush option to `injectToStream()` ([e677039](https://github.com/brillout/react-streaming/commit/e677039b6831fa742b1915e791e4d22680684e6a))
* improve hooks DX ([21a9814](https://github.com/brillout/react-streaming/commit/21a9814b97d93548884475f0a50222954024c3b9))


### Reverts

* Revert "dynamic import stream wrappers" ([0abebf6](https://github.com/brillout/react-streaming/commit/0abebf63e87cf0f7c85955fbf328602df797ef66))


### BREAKING CHANGES

* hooks `useAsync()` and `useSsrData()` consolidated into
a single new hook `useAsync()` with a new interface. See `README.md`.



## [0.3.14](https://github.com/brillout/react-streaming/compare/v0.3.13...v0.3.14) (2023-06-04)


### Bug Fixes

* avoid 'react-dom/server.node' to be bundled ([02449a7](https://github.com/brillout/react-streaming/commit/02449a76343ce3318622a5578b4a7a97e8039b68))
* improve error message ([4eed291](https://github.com/brillout/react-streaming/commit/4eed291caf45a781a5a095906aecec67dcbcdb75))



## [0.3.13](https://github.com/brillout/react-streaming/compare/v0.3.12...v0.3.13) (2023-06-03)


### Bug Fixes

* improve assertUsage message ([5e94949](https://github.com/brillout/react-streaming/commit/5e94949351857c3141fa4d69d40d03aa5e7055de))
* improve import renderToReadableStream() in Node.js ([22494a1](https://github.com/brillout/react-streaming/commit/22494a17177c6f3a35eb7bbd25d791bba18f74c0))



## [0.3.12](https://github.com/brillout/react-streaming/compare/v0.3.11...v0.3.12) (2023-06-02)


### Bug Fixes

* improve assertion that server files aren't loaded in browser (fix [#22](https://github.com/brillout/react-streaming/issues/22)) ([794dd95](https://github.com/brillout/react-streaming/commit/794dd95fa7332d30deba03e1bc66b1c7a40d8a38))



## [0.3.11](https://github.com/brillout/react-streaming/compare/v0.3.10...v0.3.11) (2023-05-19)


### Bug Fixes

* disable write after stream destoryed ([660d252](https://github.com/brillout/react-streaming/commit/660d2524400830ec0512a23d7ca360909075f7a7))
* writableForReact destory if writableFromUser not available ([68a4d65](https://github.com/brillout/react-streaming/commit/68a4d656df4d9202a28070848708fd8cdddeb74d))



## [0.3.10](https://github.com/brillout/react-streaming/compare/v0.3.9...v0.3.10) (2023-05-05)


### Bug Fixes

* re-export useStream() for the client-side as well ([c754a78](https://github.com/brillout/react-streaming/commit/c754a780c4b5e6d3e8724eda352ed377f3f1b28c))



## [0.3.9](https://github.com/brillout/react-streaming/compare/v0.3.8...v0.3.9) (2023-04-20)


### Bug Fixes

* ensure wrangler doesn't resolve browser entry ([a175d56](https://github.com/brillout/react-streaming/commit/a175d566eb233e0d90c1a891c913fb7fec70d4a6))



## [0.3.8](https://github.com/brillout/react-streaming/compare/v0.3.7...v0.3.8) (2023-04-20)


### Bug Fixes

* fix export for worker and deno ([8534637](https://github.com/brillout/react-streaming/commit/85346375cceb07d26de3a9cfcb424e2f52e4de6c))



## [0.3.7](https://github.com/brillout/react-streaming/compare/v0.3.6...v0.3.7) (2023-03-21)


### Bug Fixes

* fix exports ([#17](https://github.com/brillout/react-streaming/issues/17)) ([b2cce88](https://github.com/brillout/react-streaming/commit/b2cce88e6a35c928fc2595cf07a806caf67f07f3))



## [0.3.6](https://github.com/brillout/react-streaming/compare/v0.3.5...v0.3.6) (2023-03-21)


### Bug Fixes

* add `default` in exports field ([50f2edb](https://github.com/brillout/react-streaming/commit/50f2edb32283193d8829c073835c62db237dc3ca))
* simplify exports ([8fbde9c](https://github.com/brillout/react-streaming/commit/8fbde9c3f417535673e2931e50506feb46d1dfad))



## [0.3.5](https://github.com/brillout/react-streaming/compare/v0.3.4...v0.3.5) (2022-10-07)


### Bug Fixes

* align chunk TypeScript type ([0ef0c37](https://github.com/brillout/react-streaming/commit/0ef0c37219e06f0d38cf4b54454fd1d93642c0e7))
* improve DX upon wrong `useAsync()` usage ([0afba57](https://github.com/brillout/react-streaming/commit/0afba5768090783271ee725f94c801f78992450a))



## [0.3.4](https://github.com/brillout/react-streaming/compare/v0.3.3...v0.3.4) (2022-10-06)


### Features

* add flush option to `injectToStream()` ([e677039](https://github.com/brillout/react-streaming/commit/e677039b6831fa742b1915e791e4d22680684e6a))



## [0.3.3](https://github.com/brillout/react-streaming/compare/v0.3.2...v0.3.3) (2022-09-14)


### Bug Fixes

* also handle promise rejections ([228013e](https://github.com/brillout/react-streaming/commit/228013e41d3a4431c7d79ae88b296fba8bcfb152))



## [0.3.2](https://github.com/brillout/react-streaming/compare/v0.3.1...v0.3.2) (2022-09-07)


### Bug Fixes

* ensure suspense state is updated before promise resolves ([9d7c554](https://github.com/brillout/react-streaming/commit/9d7c55402a2d56b3c5f780f835b5f272ab805f7d))
* gracefully handle infinite loops ([52f997e](https://github.com/brillout/react-streaming/commit/52f997e532ac8504249d4c4bbc84e35dae490072))



## [0.3.1](https://github.com/brillout/react-streaming/compare/v0.3.0...v0.3.1) (2022-09-07)


### Bug Fixes

* `useAsync()`: tolerate functions that don't return a promise ([70b2e86](https://github.com/brillout/react-streaming/commit/70b2e869d634b9bd2bf417db746e2a7f13dd495a))
* add version to assertion messages ([7e020c1](https://github.com/brillout/react-streaming/commit/7e020c11e080d89c17008d6baf73e4d333f8dcb3))



# [0.3.0](https://github.com/brillout/react-streaming/compare/v0.2.22...v0.3.0) (2022-09-06)


### Bug Fixes

* improve error handling upon wrong installation ([8802e67](https://github.com/brillout/react-streaming/commit/8802e67df73f2f33618fe82e82e9554f6aa0f8fd))
* tolerate earlier injectStream call ([47b35b0](https://github.com/brillout/react-streaming/commit/47b35b0e759885c3216e1719f2c04c3cf4b60fab))
* workaround React swallowing errors ([ba4245f](https://github.com/brillout/react-streaming/commit/ba4245f4421714758046712f4256e094a31a76f4))


### Features

* improve hooks DX ([21a9814](https://github.com/brillout/react-streaming/commit/21a9814b97d93548884475f0a50222954024c3b9))


### BREAKING CHANGES

* hooks `useAsync()` and `useSsrData()` consolidated into
a single new hook `useAsync()` with a new interface. See `README.md`.
