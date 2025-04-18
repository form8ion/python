# python

Python language plugin for the @form8ion tool suite

<!--status-badges start -->

[![Node CI Workflow Status][github-actions-ci-badge]][github-actions-ci-link]
[![Codecov][coverage-badge]][coverage-link]
![SLSA Level 2][slsa-badge]

<!--status-badges end -->

## Table of Contents

* [Usage](#usage)
  * [Installation](#installation)
  * [Example](#example)
* [Contributing](#contributing)
  * [Dependencies](#dependencies)
  * [Verification](#verification)

## Usage

<!--consumer-badges start -->

[![npm][npm-badge]][npm-link]
[![Try @form8ion/python on RunKit][runkit-badge]][runkit-link]
[![license][license-badge]][license-link]

<!--consumer-badges end -->

### Installation

```sh
$ npm install @form8ion/python
```

### Example

#### Import

```javascript
import {scaffold} from '@form8ion/python';
```

#### Execute

```javascript
(async () => {
  await scaffold({projectRoot: process.cwd()});
})();
```

## Contributing

<!--contribution-badges start -->

[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Renovate][renovate-badge]][renovate-link]
[![PRs Welcome][PRs-badge]][PRs-link]
[![semantic-release: angular][semantic-release-badge]][semantic-release-link]

<!--contribution-badges end -->

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[github-actions-ci-link]: https://github.com/form8ion/python/actions?query=workflow%3A%22Node.js+CI%22+branch%3Amaster

[github-actions-ci-badge]: https://img.shields.io/github/actions/workflow/status/form8ion/python/node-ci.yml.svg?branch=master&logo=github

[coverage-link]: https://codecov.io/github/form8ion/python

[coverage-badge]: https://img.shields.io/codecov/c/github/form8ion/python?logo=codecov

[slsa-badge]: https://slsa.dev/images/gh-badge-level2.svg

[commitizen-link]: http://commitizen.github.io/cz-cli/

[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg

[commit-convention-link]: https://conventionalcommits.org

[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg

[renovate-link]: https://renovatebot.com

[renovate-badge]: https://img.shields.io/badge/renovate-enabled-brightgreen.svg?logo=renovatebot

[PRs-link]: https://makeapullrequest.com

[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

[semantic-release-link]: https://github.com/semantic-release/semantic-release

[semantic-release-badge]: https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release

[npm-link]: https://www.npmjs.com/package/@form8ion/python

[npm-badge]: https://img.shields.io/npm/v/@form8ion/python?logo=npm

[runkit-link]: https://npm.runkit.com/@form8ion/python

[runkit-badge]: https://badge.runkitcdn.com/@form8ion/python.svg

[license-link]: LICENSE

[license-badge]: https://img.shields.io/github/license/form8ion/python.svg?logo=opensourceinitiative
