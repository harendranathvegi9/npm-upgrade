# npm-upgrade
Interactive CLI utility to easily update outdated NPM dependencies

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url]

## What is this for?
If you are tired of manually upgrading `package.json` every time your package dependencies are getting out of date then this utility is for you.

Take a look at this demo:

![npm-upgrade outdated packages](https://cloud.githubusercontent.com/assets/302213/11168821/08311b90-8bb2-11e5-9a71-5da73682ed44.gif)

## Installation
First, install [Node.js](https://nodejs.org) (at least `v0.10`).

Then install this utility as global npm-module:
```sh
npm i -g npm-upgrade
```

## Usage
Run `npm-upgrade` in the root directory of your Node.js project (it must contain `package.json` that you want to update):
```sh
cd ~/my-projects/my-node-project
npm-upgrade
```
Utility will find all of your outdated deps and ask to update them in `package.json`. Just answer the questions and you are done.
Use `Ctrl-C` to exit if you changed your mind.

## License

[MIT](LICENSE)

[downloads-image]: https://img.shields.io/npm/dt/npm-upgrade.svg
[npm-url]: https://www.npmjs.com/package/npm-upgrade
[npm-image]: https://img.shields.io/npm/v/npm-upgrade.svg