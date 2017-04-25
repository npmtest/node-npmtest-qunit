# npmtest-qunit

#### basic test coverage for  [qunit (v1.0.0)](https://github.com/kof/node-qunit#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-qunit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-qunit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-qunit.svg)](https://travis-ci.org/npmtest/node-npmtest-qunit)

#### QUnit testing framework for Node.js

[![NPM](https://nodei.co/npm/qunit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qunit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-qunit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-qunit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-qunit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-qunit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-qunit/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-qunit/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-qunit/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-qunit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-qunit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-qunit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-qunit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-qunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-qunit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-qunit/build/test-report.html](https://npmtest.github.io/node-npmtest-qunit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-qunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-qunit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-qunit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qunit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qunit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-qunit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-qunit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Oleg Slobodskoi"
    },
    "bin": {
        "qunit": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/kof/node-qunit/issues"
    },
    "contributors": [
        {
            "name": "Jonathan Buchanan"
        },
        {
            "name": "Ashar Voultoiz"
        },
        {
            "name": "Drew Fyock"
        },
        {
            "name": "Timo Tijhof"
        }
    ],
    "dependencies": {
        "argsparser": "^0.0.7",
        "cli-table": "^0.3.0",
        "co": "^4.6.0",
        "istanbul": "0.4.5",
        "qunitjs": "2.1.1",
        "tracejs": "^0.1.8",
        "underscore": "^1.6.0"
    },
    "description": "QUnit testing framework for Node.js",
    "devDependencies": {
        "chainer": "^0.0.5",
        "eslint": "^3.17.1",
        "timekeeper": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1d3dcfbfaec81979cb4bdaee45450bb5e5914f8c",
        "tarball": "https://registry.npmjs.org/qunit/-/qunit-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.6.0 < 8.0"
    },
    "gitHead": "f083e7da90f6702a8ee5f6ef5f74dc1add599940",
    "homepage": "https://github.com/kof/node-qunit#readme",
    "keywords": [
        "TDD",
        "QUnit",
        "unit",
        "testing",
        "tests",
        "async"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jzaefferer"
        },
        {
            "name": "kof"
        },
        {
            "name": "krinkle"
        },
        {
            "name": "leobalter"
        }
    ],
    "name": "qunit",
    "optionalDependencies": {
        "istanbul": "0.4.5"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kof/node-qunit.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "node ./test/testrunner.js && eslint ."
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
