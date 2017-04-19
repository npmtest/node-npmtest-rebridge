# npmtest-rebridge

#### basic test coverage for  [rebridge (v2.2.0)](https://github.com/CapacitorSet/rebridge)  [![npm package](https://img.shields.io/npm/v/npmtest-rebridge.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rebridge) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rebridge.svg)](https://travis-ci.org/npmtest/node-npmtest-rebridge)

#### A transparent bridge to Redis.

[![NPM](https://nodei.co/npm/rebridge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rebridge)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rebridge/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rebridge/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rebridge/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rebridge/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rebridge/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rebridge/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rebridge/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rebridge/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rebridge/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rebridge/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rebridge/build/test-report.html](https://npmtest.github.io/node-npmtest-rebridge/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rebridge/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rebridge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rebridge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rebridge/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rebridge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rebridge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "@CapacitorSet"
    },
    "bugs": {
        "url": "https://github.com/CapacitorSet/rebridge/issues"
    },
    "dependencies": {
        "deasync": "0.1.9",
        "redlock": "2.1.0"
    },
    "description": "A transparent bridge to Redis.",
    "devDependencies": {
        "eslint": "2.9.0",
        "eslint-config-google": "0.5.0",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "12a770d630745b590f40602f3726233d5f4cff31",
        "tarball": "https://registry.npmjs.org/rebridge/-/rebridge-2.2.0.tgz"
    },
    "engines": {
        "node": ">=6.0.0"
    },
    "gitHead": "c4e9f303892ee0c8abcb5d68142cdc6f5aeef8dc",
    "homepage": "https://github.com/CapacitorSet/rebridge",
    "keywords": [
        "redis",
        "database"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "capacitorset"
        }
    ],
    "name": "rebridge",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/CapacitorSet/rebridge.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha test/deasync.js && mocha test/promiseful.js"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
