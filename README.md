# :page_with_curl: tslint-log readme

A custom tslint rule that logs out all visited source code files.

Use to diagnose tslint configuration, to see that expected files are being linted.

## status - stable

tslint-log is stable and tested on Linux and Windows.

[![Size](https://packagephobia.now.sh/badge?p=tslint-log)](https://packagephobia.now.sh/result?p=tslint-log)

[![Dependencies](https://david-dm.org/mrseanryan/tslint-log.svg)](https://david-dm.org/mrseanryan/tslint-log)
[![Dev Dependencies](https://david-dm.org/mrseanryan/tslint-log/dev-status.svg)](https://david-dm.org/mrseanryan/tslint-log?type=dev)

[![npm Package](https://img.shields.io/npm/v/tslint-log.svg?style=flat-square)](https://www.npmjs.org/package/tslint-log)
[![NPM Downloads](https://img.shields.io/npm/dm/tslint-log.svg)](https://npmjs.org/package/tslint-log)

[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg)](https://paypal.me/mrseanryan)


## dependencies

No special dependencies - just `TypeScript` and of course `tslint`.

## features

- a custom tslint rule that logs out the path to each visited TypeScript file

## usage

### 1 Install via npm (or yarn) into your TypeScript project

```
npm install tslint-log
```

### 2 Configure tslint to pick up the custom rule

Edit your `tslint.json` to have an entry `"rulesDirectory"` that points to tslint-log.

Normally this would be like:

```json
{
    "rulesDirectory": "node_modules/tslint-log/dist/lib",
    "rules": {
        "tslLog": true

        // more tslint rules here...
    }
}
```

## sites

| site                 | URL                                               |
| -------------------- | ------------------------------------------------- |
| source code (github) | https://github.com/mrseanryan/tslint-log |
| github page          | https://mrseanryan.github.io/tslint-log/ |
| npm                  | https://www.npmjs.com/package/tslint-log |

## developing code in _this_ repository

see the [contributing readme](CONTRIBUTING.md).

## authors

Original work by Sean Ryan - mr.sean.ryan(at gmail.com)

## licence = MIT

This project is licensed under the MIT License - see the [LICENSE](https://github.com/mrseanryan/tslint-log/blob/master/LICENSE) file for details
