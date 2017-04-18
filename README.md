# npmtest-phantomjs

#### test coverage for  [phantomjs (v2.1.7)](https://github.com/Medium/phantomjs)  [![npm package](https://img.shields.io/npm/v/npmtest-phantomjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-phantomjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-phantomjs.svg)](https://travis-ci.org/npmtest/node-npmtest-phantomjs)

#### Headless WebKit with JS API

[![NPM](https://nodei.co/npm/phantomjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phantomjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-phantomjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-phantomjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-phantomjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-phantomjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-phantomjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-phantomjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-phantomjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-phantomjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-phantomjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-phantomjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-phantomjs/build/test-report.html](https://npmtest.github.io/node-npmtest-phantomjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-phantomjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-phantomjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phantomjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phantomjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-phantomjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-phantomjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Pupius",
        "url": "http://pupius.co.uk"
    },
    "bin": {
        "phantomjs": "./bin/phantomjs"
    },
    "bugs": {
        "url": "https://github.com/Medium/phantomjs/issues"
    },
    "dependencies": {
        "extract-zip": "~1.5.0",
        "fs-extra": "~0.26.4",
        "hasha": "^2.2.0",
        "kew": "~0.7.0",
        "progress": "~1.1.8",
        "request": "~2.67.0",
        "request-progress": "~2.0.1",
        "which": "~1.2.2"
    },
    "deprecated": "Package renamed to phantomjs-prebuilt. Please update 'phantomjs' package references to 'phantomjs-prebuilt'",
    "description": "Headless WebKit with JS API",
    "devDependencies": {
        "eslint": "1.10.3",
        "nodeunit": "0.9.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c6910f67935c37285b6114329fc2f27d5f3e3134",
        "tarball": "https://registry.npmjs.org/phantomjs/-/phantomjs-2.1.7.tgz"
    },
    "gitHead": "21e7232131b60f2573e110cf89d156a33e8f293c",
    "homepage": "https://github.com/Medium/phantomjs",
    "keywords": [
        "phantomjs",
        "headless",
        "webkit"
    ],
    "license": "Apache-2.0",
    "main": "lib/phantomjs",
    "maintainers": [
        {
            "name": "dpup"
        },
        {
            "name": "nicks"
        },
        {
            "name": "medium"
        }
    ],
    "name": "phantomjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Medium/phantomjs.git"
    },
    "scripts": {
        "install": "node install.js",
        "test": "nodeunit --reporter=minimal test/tests.js && eslint install.js"
    },
    "version": "2.1.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
