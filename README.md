<h1 align="center">
  Lyne Design System
</h1>

> *Lyne* is an open source Design System built by SBB–CFF–FFS. We provide a common [terminology](/docs/TERMINOLOGY.md), [working code](#our-projects), design decisions,
> resources and human interface guidelines which all together define our shared, common language.

<p align="center">
  <a href="https://github.com/lyne-design-system/lyne/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="Lyne is released under the MIT license" />
  </a>
  <a href="https://lyne-components-storybook.netlify.com">
    <img src="https://cdn.jsdelivr.net/gh/storybookjs/brand@master/badge/badge-storybook.svg" alt="Lyne Storybook" />
  </a>
</p>

<br>

## ⚠️ Notice
***Lyne Design System* is 🧪 experimental at the moment — with enthusiasm.<br>Don't use the project until it has left infancy.**
<br>
<br>
<br>

## 🎯 Our aim
To fulfill our [Vision](./docs/VISION.md), we are building and maintaining [Lyne](./docs/TERMINOLOGY.md#lyne), our [Design System](./docs/TERMINOLOGY.md#design-system), which is and acts as our common language —  our [Single Source of Truth](./docs/TERMINOLOGY.md#single-source-of-truth). For this purpose we use [Design Tokens](./docs/TERMINOLOGY.md#design-token) as our design abstractions. Those Design Tokens are consumed by [Lyne Components](./docs/TERMINOLOGY.md#lyne-components) via our [Design (Token) API](./docs/TERMINOLOGY.md#design-token-api) and are integrated within our documentation.

Lyne Design Tokens and Lyne Components are available for developer and designer(coming).

## 🚀 Getting started
First things first: This repository acts as the entry point for everything related to the *Lyne Design System* and is it's common ground — it's common denominator. See [our projects](#our-projects) below for more details and their specific implementations.

### Documentation
Check the [docs](docs/README.md) directory for our documentation and resources which we will continuously enhance.

Besides our markdown-only documentation on GitHub – mentioned above – we host the [Lyne documentation platform](https://lyne-documentation.netlify.app/) to provide a holistic but less technical understanding of Lyne.

### Our projects

| Project/repository | Purpose | Version                                                                                                                                                                            
| --------| ------------------| ----
| [`lyne-components`](https://github.com/lyne-design-system/lyne-components) | 🧱 Lyne building blocks — standard compliant Web Components | ![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-components?label=release)
| [`lyne-design-tokens`](https://github.com/lyne-design-system/lyne-design-tokens) | 💄 Lyne design primitives — design decisions stored as Design Tokens and used across the system | ![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-design-tokens?label=release)
| [`lyne-icons`](https://github.com/lyne-design-system/lyne-icons) | 🎎 Lyne iconography - icons used across the system | ![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-icons?label=release)
| [`lyne-documentation`](https://github.com/lyne-design-system/lyne-documentation) | 📚 Documentation platform for Lyne | ![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-documentation?label=release)
|<br/><br/>*Integration and application repositories*||
| [`lyne-getting-started`](https://github.com/lyne-design-system/lyne-getting-started) | 🕹️ Integration examples for Lyne Components within React, Angular, Vue, Svelte and Plain JavaScript |(no versions)
|[`lyne-hydration-playground`](https://github.com/lyne-design-system/lyne-hydration-playground) |Repo to play around with hydration of Lyne Components|(no versions)
|[`lyne-components-demo`](https://github.com/lyne-design-system/lyne-components-demo) |Showcase of how Lyne components could be used to create a fully fledged website|![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-components-demo?label=release)
|<br/><br/>*Helper and behind the curtain repositories*||
|[`lyne-figma-listener`](https://github.com/lyne-design-system/lyne-figma-listener) |Server listening to webhooks from Figma|![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-figma-listener?label=release)
|[`lyne-helper-figma-api`](https://github.com/lyne-design-system/lyne-helper-figma-api) |Helpers to simplify requests against the Figma API|![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-helper-figma-api?label=release)
|[`lyne-helper-eslint-config`](https://github.com/lyne-design-system/lyne-helper-eslint-config) |ESLint Configuration for all Lyne Repos|![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-helper-eslint-config?label=release)
|[`lyne-helper-trigger-travis`](https://github.com/lyne-design-system/lyne-helper-trigger-travis) |Helper to trigger a build on TravisCI|![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/lyne-design-system/lyne-helper-trigger-travis?label=release)

## 🙌 Contributing
See our [contributing guide](CONTRIBUTING.md) and check also our [code of conduct](CODE_OF_CONDUCT.md) 👀.

## 📝 License
This software is published by SBB-CFF-FFS under the [MIT](/LICENSE) licence and unsupported unless otherwise clearly stated. Use at your own risk.
