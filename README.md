# npmtest-buffet

#### basic test coverage for  buffet (v1.0.10)  [![npm package](https://img.shields.io/npm/v/npmtest-buffet.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-buffet) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-buffet.svg)](https://travis-ci.org/npmtest/node-npmtest-buffet)

#### Static file server with in-memory cache

[![NPM](https://nodei.co/npm/buffet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/buffet)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-buffet/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-buffet/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-buffet/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-buffet/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-buffet/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-buffet/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-buffet/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-buffet/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-buffet/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-buffet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-buffet/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-buffet/build/test-report.html](https://npmtest.github.io/node-npmtest-buffet/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-buffet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-buffet/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-buffet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-buffet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-buffet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-buffet/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-buffet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-buffet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Carlos Rodriguez <carlos@s8f.org> (http://s8f.org/)",
    "name": "buffet",
    "description": "Static file server with in-memory cache",
    "version": "1.0.10",
    "main": "index.js",
    "scripts": {
        "test": "make test"
    },
    "bin": "./bin/buffet.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/carlos8f/buffet.git"
    },
    "license": "MIT",
    "dependencies": {
        "accesslog": "0.0.2",
        "commander": "^2.9.0",
        "dish": "^1.0.7",
        "mayonnaise": "^0.3.2",
        "middler": "^0.8.2"
    },
    "keywords": [
        "static",
        "middleware",
        "server",
        "file",
        "buffer"
    ],
    "devDependencies": {
        "benchmarx": "^0.2.5",
        "idgen": "^2.0.2",
        "mocha": "^2.4.5",
        "ncp": "^2.0.0",
        "request": "^2.72.0",
        "rimraf": "^2.5.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
