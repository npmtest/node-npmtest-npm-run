# test coverage for  [npm-run (v4.1.2)](https://github.com/timoxley/npm-run)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-run.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-run) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-run.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-run)
#### Run executables for locally-installed packages without using ./node_modules/.bin

[![NPM](https://nodei.co/npm/npm-run.png?downloads=true)](https://www.npmjs.com/package/npm-run)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-run/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-run/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-run/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-run/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-run/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-run/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-run/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-run/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-npm-run/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-run/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-npm-run%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-run/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-run/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-npm-run%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-run/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-run/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-run/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Oxley"
    },
    "bin": {
        "npm-run": "bin/npm-run.js"
    },
    "bugs": {
        "url": "https://github.com/timoxley/npm-run/issues"
    },
    "dependencies": {
        "cross-spawn": "^5.1.0",
        "minimist": "^1.2.0",
        "npm-path": "^2.0.3",
        "npm-which": "^3.0.1",
        "serializerr": "^1.0.3",
        "sync-exec": "^0.6.2"
    },
    "description": "Run executables for locally-installed packages without using ./node_modules/.bin",
    "devDependencies": {
        "bl": "^1.2.0",
        "standard": "^9.0.0",
        "tape": "^4.6.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "1030e1ec56908c89fcc3fa366d03a2c2ba98eb99",
        "tarball": "https://registry.npmjs.org/npm-run/-/npm-run-4.1.2.tgz"
    },
    "engines": {
        "node": ">=4.2.0"
    },
    "gitHead": "80a842e1509b8faaefaca65f06a8c23c2c971a2b",
    "homepage": "https://github.com/timoxley/npm-run",
    "keywords": [
        "npm",
        "path",
        "executable",
        ".bin",
        "run"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "timoxley",
            "email": "secoif@gmail.com"
        }
    ],
    "name": "npm-run",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/timoxley/npm-run.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "tape test/*.js && npm run lint"
    },
    "version": "4.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
