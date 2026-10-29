### Hi, I'm Kim Seongchan 👋

#### Open Source Contributions

**ktlint**

| Project | Contribution | Status |
|---|---|---|
| [ktlint/ktlint](https://github.com/ktlint/ktlint) | [#3395 – Add detekt for static analysis on ktlint's own codebase](https://github.com/ktlint/ktlint/pull/3395) | ![Merged](https://img.shields.io/github/pulls/detail/state/ktlint/ktlint/3395?label=merged&color=8250df) |

> Introduced [detekt](https://detekt.dev/) as a second static-analysis pass alongside ktlint's own `ktlintCheck`, resolving 325+ findings in code and landing with zero baseline after review from the ktlint maintainers.
> Resolves: [ktlint/ktlint#2923](https://github.com/ktlint/ktlint/issues/2923)

**NestJS**

| Project | Contribution | Status |
|---|---|---|
| [nestjs/serve-static](https://github.com/nestjs/serve-static) | [#2081 – feat: support transforming the spa fallback index html](https://github.com/nestjs/serve-static/pull/2081) | ![Merged](https://img.shields.io/github/pulls/detail/state/nestjs/serve-static/2081?label=merged&color=8250df) |
| [nestjs/schematics](https://github.com/nestjs/schematics) | [#2517 – fix: ship the application template package.json as .template](https://github.com/nestjs/schematics/pull/2517) | ![Merged](https://img.shields.io/github/pulls/detail/state/nestjs/schematics/2517?label=merged&color=8250df) |

> **serve-static** — Added support for transforming the SPA fallback `index.html` before it's served, merged by [@kamilmysliwiec](https://github.com/kamilmysliwiec) (NestJS creator).
>
> **schematics** — Fixed a supply-chain-scanner false positive where generated-project `package.json` templates bundled inside the published package were misattributed as the package's own license, by renaming them to `.template`. Merged by [@kamilmysliwiec](https://github.com/kamilmysliwiec).

**Spring**

| Project | Contribution | Status |
|---|---|---|
| [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework) | [#37586 – Detect overflow for floating-point numbers in `NumberUtils`](https://github.com/spring-projects/spring-framework/pull/37586) | ![Merged](https://img.shields.io/github/pulls/detail/state/spring-projects/spring-framework/37586?label=merged&color=8250df) |

> **spring-framework** — Fixed `NumberUtils`/`DefaultConversionService` silently saturating or zeroing out-of-range `Double`/`Float` values (including `NaN`) when converting to integral types, by extending the existing overflow check to floating-point sources. Merged by [@sbrannen](https://github.com/sbrannen) (Spring Framework maintainer).
