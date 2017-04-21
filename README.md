# npmtest-codeceptjs

#### basic test coverage for  [codeceptjs (v0.6.3-pre)](http://codecept.io)  [![npm package](https://img.shields.io/npm/v/npmtest-codeceptjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-codeceptjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-codeceptjs.svg)](https://travis-ci.org/npmtest/node-npmtest-codeceptjs)

#### Modern Era Aceptance Testing Framework for NodeJS

[![NPM](https://nodei.co/npm/codeceptjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/codeceptjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-codeceptjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-codeceptjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-codeceptjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-codeceptjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-codeceptjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-codeceptjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-codeceptjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-codeceptjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-codeceptjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-codeceptjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-codeceptjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-codeceptjs/build/test-report.html](https://npmtest.github.io/node-npmtest-codeceptjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-codeceptjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-codeceptjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-codeceptjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-codeceptjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-codeceptjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-codeceptjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-codeceptjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-codeceptjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "codeceptjs",
    "version": "0.6.3-pre",
    "description": "Modern Era Aceptance Testing Framework for NodeJS",
    "homepage": "http://codecept.io",
    "repository": "Codeception/codeceptjs",
    "es6": true,
    "author": {
        "name": "DavertMik",
        "url": "http://codegyre.com"
    },
    "bin": {
        "codeceptjs": "./bin/codecept.js"
    },
    "files": [
        "bin",
        "docs",
        "lib",
        "translations"
    ],
    "main": "lib/index.js",
    "keywords": [
        "tdd",
        "bdd",
        "testing",
        "acceptance"
    ],
    "dependencies": {
        "chalk": "^1.1.3",
        "co": "^4.6.0",
        "commander": "^2.9.0",
        "escape-string-regexp": "^1.0.3",
        "get-parameter-names": "^0.3.0",
        "glob": "^6.0.1",
        "inquirer": "^0.11.0",
        "mkdirp": "^0.5.1",
        "mocha": "^3.1.2",
        "requireg": "^0.1.5"
    },
    "devDependencies": {
        "chai": "^3.4.1",
        "chai-as-promised": "^5.2.0",
        "co-mocha": "^1.1.2",
        "documentation": "^4.0.0-beta1",
        "git-guppy": "^1.0.1",
        "gulp": "^3.6.0",
        "gulp-coveralls": "^0.1.0",
        "gulp-documentation": "^2.2.0",
        "gulp-eslint": "^3.0.0",
        "gulp-exclude-gitignore": "^1.0.0",
        "gulp-gitmodified": "^1.1.0",
        "gulp-if": "^2.0.2",
        "gulp-istanbul": "^0.9.0",
        "gulp-mocha": "^2.0.0",
        "gulp-mustache": "^2.2.0",
        "gulp-plumber": "^1.0.0",
        "guppy-pre-commit": "^0.4.0",
        "nightmare": "^2.5.2",
        "nightmare-upload": "^0.1.1",
        "protractor": ">4.0.9 <6.0",
        "selenium-webdriver": "^2.53.1",
        "sinon": "^1.17.2",
        "webdriverio": ">3.4.0 <5.0.0"
    },
    "scripts": {
        "prepublish": "gulp prepublish",
        "test": "gulp"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
