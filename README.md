# npmtest-ip-address

#### basic test coverage for  [ip-address (v5.8.8)](https://github.com/beaugunderson/ip-address#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ip-address.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ip-address) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ip-address.svg)](https://travis-ci.org/npmtest/node-npmtest-ip-address)

#### A library for parsing IPv4 and IPv6 IP addresses in node and the browser.

[![NPM](https://nodei.co/npm/ip-address.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ip-address)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ip-address/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ip-address/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ip-address/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ip-address/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ip-address/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ip-address/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ip-address/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ip-address/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ip-address/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ip-address/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ip-address/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ip-address/build/test-report.html](https://npmtest.github.io/node-npmtest-ip-address/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ip-address/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ip-address/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ip-address/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ip-address/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ip-address/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ip-address/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ip-address/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ip-address/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Beau Gunderson",
        "url": "https://beaugunderson.com/"
    },
    "bugs": {
        "url": "https://github.com/beaugunderson/ip-address/issues"
    },
    "dependencies": {
        "jsbn": "0.1.0",
        "lodash.find": "^4.6.0",
        "lodash.max": "^4.0.1",
        "lodash.merge": "^4.6.0",
        "lodash.padstart": "^4.6.1",
        "lodash.repeat": "^4.1.0",
        "sprintf-js": "^1.0.3",
        "util-deprecate": "^1.0.2"
    },
    "description": "A library for parsing IPv4 and IPv6 IP addresses in node and the browser.",
    "devDependencies": {
        "browserify": "^13.1.1",
        "chai": "^3.5.0",
        "codecov.io": "^0.1.6",
        "documentation": "^4.0.0-beta9",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "mochify": "^2.18.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5fd1f8f7465249fb7d2b3c1eec7b41d29d1f1b76",
        "tarball": "https://registry.npmjs.org/ip-address/-/ip-address-5.8.8.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "70f95e8c94192e2187d9cc694cfbd708dd647448",
    "homepage": "https://github.com/beaugunderson/ip-address#readme",
    "keywords": [
        "ipv6",
        "ipv4",
        "browser",
        "validation"
    ],
    "license": "MIT",
    "main": "ip-address.js",
    "maintainers": [
        {
            "name": "beaugunderson"
        }
    ],
    "name": "ip-address",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/beaugunderson/ip-address.git"
    },
    "scripts": {
        "docs": "documentation --github --output docs --format html ./ip-address.js",
        "prepublish": "browserify ./ip-address-globals.js > ./dist/ip-address-globals.js",
        "test": "mocha -R spec"
    },
    "version": "5.8.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
