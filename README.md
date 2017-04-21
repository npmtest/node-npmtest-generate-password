# npmtest-generate-password

#### basic test coverage for  [generate-password (v1.3.0)](https://github.com/brendanashworth/generate-password)  [![npm package](https://img.shields.io/npm/v/npmtest-generate-password.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generate-password) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generate-password.svg)](https://travis-ci.org/npmtest/node-npmtest-generate-password)

#### Easy library for generating unique passwords.

[![NPM](https://nodei.co/npm/generate-password.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generate-password)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generate-password/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generate-password/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generate-password/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generate-password/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generate-password/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generate-password/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generate-password/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generate-password/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generate-password/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generate-password/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generate-password/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generate-password/build/test-report.html](https://npmtest.github.io/node-npmtest-generate-password/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generate-password/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generate-password/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generate-password/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generate-password/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generate-password/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generate-password/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generate-password/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generate-password/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generate-password",
    "version": "1.3.0",
    "description": "Easy library for generating unique passwords.",
    "main": "main.js",
    "scripts": {
        "test": "./node_modules/.bin/mocha",
        "coverage": "sh ./test/coverage.sh",
        "lint": "./node_modules/.bin/eslint src test main.js example.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/brendanashworth/generate-password"
    },
    "keywords": [
        "generate",
        "password",
        "generator",
        "unique"
    ],
    "author": "Brendan Ashworth",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/brendanashworth/generate-password/issues"
    },
    "homepage": "https://github.com/brendanashworth/generate-password",
    "dependencies": {},
    "devDependencies": {
        "chai": "^1.10.0",
        "codecov": "^1.0.1",
        "eslint": "^2.13.1",
        "jscover": "^1.0.0",
        "mocha": "^2.0.1",
        "mocha-lcov-reporter": "^1.2.0",
        "underscore": "^1.7.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
