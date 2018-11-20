# Lighthouse CI
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
[![npm version](https://badge.fury.io/js/lighthouse-ci.svg)](https://badge.fury.io/js/lighthouse-ci)
[![npm](https://img.shields.io/npm/dt/lighthouse-ci.svg)](https://www.npmjs.com/package/lighthouse-ci)
[![Known Vulnerabilities](https://snyk.io/test/github/andreasonny83/lighthouse-ci/badge.svg?targetFile=package.json)](https://snyk.io/test/github/andreasonny83/lighthouse-ci?targetFile=package.json)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/xojs/xo)

> A useful wrapper around Google Lighthouse CLI

<img alt="Lighthouse CI logo" src="https://raw.githubusercontent.com/andreasonny83/lighthouse-ci/master/logo.png" width="800px">

<img src="https://raw.githubusercontent.com/andreasonny83/lighthouse-ci/master/lighthouse-cli.gif" width="700">

## Install

```
$ npm install -g lighthouse-ci
```

## Usage

```sh
lighthouse-ci --help
```

## CLI

```
$ lighthouse-ci --help

  Usage
    $ lighthouse-ci <target-url>

  Example
    $ lighthouse-ci https://example.com/
    $ lighthouse-ci -s https://example.com/
    $ lighthouse-ci https://example.com/ --score=75
    $ lighthouse-ci https://example.com/ --accessibility=90 --seo=80

  Options
    --report=<path>               Generate an HTML report inside a specified folder
    -s, --silent                  Run Lighthouse without printing report log.
    --score=<threshold>           Specify a score threshold for the CI to pass.
    --performance=<threshold>     Specify a minimal performance score for the CI to pass.
    --pwa=<threshold>             Specify a minimal pwa score for the CI to pass.
    --accessibility=<threshold>   Specify a minimal accessibility score for the CI to pass.
    --best-practice=<threshold>   [DEPRECATED] Use best-practices instead.
    --best-practices=<threshold>  Specify a minimal best-practice score for the CI to pass.
    --seo=<threshold>             Specify a minimal seo score for the CI to pass.
```

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/8806300?v=4" width="100px;"/><br /><sub><b>Andrea Sonny</b></sub>](https://about.me/andreasonny83)<br />[💬](#question-andreasonny83 "Answering Questions") [💻](https://github.com/andreasonny83/lighthouse-ci/commits?author=andreasonny83 "Code") [📖](https://github.com/andreasonny83/lighthouse-ci/commits?author=andreasonny83 "Documentation") |
| :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!

## License

MIT

---

Created with 🦄 by [andreasonny83](https://about.me/andreasonny83)
