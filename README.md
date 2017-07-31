# dep

A little Node.js dependency installer with the bare minimum features for module **end-users**.

### Table of Contents

<li><a href="#features">Features</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#scope">Scope</a></li>
<li><a href="#license">License</a></li>

## Features
+ **Install** the dependencies defined in a local package.json.
+ **Lock** the dependencies installed in a local node_modules.
+ **Run** an arbitrary command from scripts in a local package.json.

## Usage
```console
$ dep -h
A little Node.js dependency installer

Commands:
  install  Install dependencies defined in package.json.            [aliases: i]
  lock     Lock dependencies installed in node_modules.             [aliases: l]
  run      Run an arbitrary command from scripts in package.json    [aliases: r]

Options:
  --help, -h     Show help                                             [boolean]
  --version, -v  Show version information                              [boolean]
```

## Installation
Currently, [npm] is the only way to install dep:
```console
$ npm install -g dep
```

## Scope
This table is about what dep is caring.

| Mac/Linux | Windows | Node.js LTS | Coverage |
| :-: | :-: | :-: | :-: |
| [![travis][t-img]][t-url] | [![appveyor][a-img]][a-url] | [![Node.js LTS][n-img]][n-url] | [![coverage][c-img]][c-url] |

## License
[MIT](./LICENSE)

[t-img]: https://img.shields.io/travis/watilde/dep/master.svg
[t-url]: https://travis-ci.org/watilde/dep
[a-img]: https://img.shields.io/appveyor/ci/watilde/dep/master.svg
[a-url]: https://ci.appveyor.com/project/watilde/dep/branch/master
[n-img]: https://img.shields.io/node/v/lts.svg
[n-url]: https://github.com/nodejs/LTS#lts-schedule1
[c-img]: https://img.shields.io/coveralls/watilde/dep/master.svg
[c-url]: https://coveralls.io/github/watilde/dep
[npm]: https://github.com/npm/npm
