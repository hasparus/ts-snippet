<a name="5.0.1"></a>
## [5.0.1](https://github.com/cartant/ts-snippet/compare/v5.0.0...v5.0.1) (2020-11-21)

### Changes

* Include the actual error(s) when a failure expectation's regular expression does not match. ([55778a5](https://github.com/cartant/ts-snippet/commit/55778a5))

<a name="5.0.0"></a>
## [5.0.0](https://github.com/cartant/ts-snippet/compare/v4.3.0...v5.0.0) (2020-10-28)

### Breaking Changes

* `infer`/`toInfer` implies `succeed`/`toSucceed` and will throw if there are compilation errors. ([54e0819](https://github.com/cartant/ts-snippet/commit/54e0819))

<a name="4.3.0"></a>
## [4.3.0](https://github.com/cartant/ts-snippet/compare/v4.2.0...v4.3.0) (2020-08-28)

### Changes

* Widen TypeScript peer range. ([df3ef4e](https://github.com/cartant/ts-snippet/commit/df3ef4e))

<a name="4.2.0"></a>
## [4.2.0](https://github.com/cartant/ts-snippet/compare/v4.1.1...v4.2.0) (2019-04-22)

### Fixes

* Add a `Compiler` signature to `expecter` to facilitate faster tests. ([a3d9058](https://github.com/cartant/ts-snippet/commit/a3d9058))

<a name="4.1.1"></a>
## [4.1.1](https://github.com/cartant/ts-snippet/compare/v4.1.0...v4.1.1) (2019-04-22)

### Fixes

* Don't throw a TypeScript `Diagnostic` for options-related errors. ([0467d0e](https://github.com/cartant/ts-snippet/commit/0467d0e))

<a name="4.1.0"></a>
## [4.1.0](https://github.com/cartant/ts-snippet/compare/v4.0.0...v4.1.0) (2019-03-28)

### Features

* Added a `rootDirectory` option. ([b8c6411](https://github.com/cartant/ts-snippet/commit/b8c6411))

<a name="4.0.0"></a>
## [4.0.0](https://github.com/cartant/ts-snippet/compare/v3.1.2...v4.0.0) (2018-12-16)

### Breaking Changes

* Upgrade to AVA 1.0. ([3299ee3](https://github.com/cartant/ts-snippet/commit/3299ee3))

<a name="3.1.2"></a>
## [3.1.2](https://github.com/cartant/ts-snippet/compare/v3.1.1...v3.1.2) (2018-07-31)

### Build

* Widen TypeScript peer semver to allow for version 3.0. ([c036f9e](https://github.com/cartant/ts-snippet/commit/c036f9e))

<a name="3.1.1"></a>
## [3.1.1](https://github.com/cartant/ts-snippet/compare/v3.1.0...v3.1.1) (2018-04-28)

### Fixes

* **placeholders**: Add `T0` to `placeholders.ts`, etc. ([b54ba02](https://github.com/cartant/ts-snippet/commit/b54ba02))

<a name="3.1.0"></a>
## [3.1.0](https://github.com/cartant/ts-snippet/compare/v3.0.0...v3.1.0) (2018-04-28)

### Features

* **placeholders**: Add `placeholders.ts` so that snippets can import pre-declared placeholder types, constants and variables. ([a95f9a0](https://github.com/cartant/ts-snippet/commit/a95f9a0))

<a name="3.0.0"></a>
## [3.0.0](https://github.com/cartant/ts-snippet/compare/v2.1.0...v3.0.0) (2018-04-01)

### Breaking Changes

* **TypeScript:** Drop support for TypeScript 2.0. ([8f19247](https://github.com/cartant/ts-snippet/commit/8f19247))
* **expecter:** Rename `reuseCompiler` to `expecter`. ([0df6415](https://github.com/cartant/ts-snippet/commit/0df6415))

<a name="2.1.0"></a>
## [2.1.0](https://github.com/cartant/ts-snippet/compare/v2.0.1...v2.1.0) (2018-03-30)

### Features

* Add `reuseCompiler` to simplify use. ([90a6bce](https://github.com/cartant/ts-snippet/commit/90a6bce))

<a name="2.0.1"></a>
## [2.0.1](https://github.com/cartant/ts-snippet/compare/v2.0.0...v2.0.1) (2018-01-31)

### Fixes

* The `infer` expectation now supports variables in nested scopes. ([fa054bd](https://github.com/cartant/ts-snippet/commit/fa054bd))

### Changes

* The distribution now includes CommonJS, ES5 and ES2015 files.

<a name="2.0.0"></a>
## [2.0.0](https://github.com/cartant/ts-snippet/compare/v1.0.2...v2.0.0) (2017-11-03)

### Breaking Changes

* **Compiler:** The compiler now takes JSON options rather than options that use TypeScript's enums, etc. ([71d93a4](https://github.com/cartant/ts-snippet/commit/71d93a4))