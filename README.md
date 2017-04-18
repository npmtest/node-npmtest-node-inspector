# npmtest-node-inspector

#### test coverage for  [node-inspector (v1.1.0)](http://github.com/node-inspector/node-inspector)  [![npm package](https://img.shields.io/npm/v/npmtest-node-inspector.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-inspector) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-inspector.svg)](https://travis-ci.org/npmtest/node-npmtest-node-inspector)

#### Web Inspector based nodeJS debugger

[![NPM](https://nodei.co/npm/node-inspector.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-inspector)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-inspector/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-inspector/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-inspector/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-inspector/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-inspector/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-inspector/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-inspector/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-inspector/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-inspector/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-inspector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-inspector/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-inspector/build/test-report.html](https://npmtest.github.io/node-npmtest-node-inspector/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-inspector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-inspector/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-inspector/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-inspector/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-inspector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-inspector/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-inspector/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-inspector/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Danny Coates"
    },
    "bin": {
        "node-inspector": "./bin/inspector.js",
        "node-debug": "./bin/node-debug.js"
    },
    "bugs": {
        "url": "https://github.com/node-inspector/node-inspector/issues"
    },
    "dependencies": {
        "async": "~0.9",
        "biased-opener": "~0.2.2",
        "debug": "^2.2.0",
        "express": "^4.12.3",
        "glob": "^5.0.5",
        "path-is-absolute": "^1.0.0",
        "rc": "^1.0.1",
        "semver": "^4.3.4",
        "serve-favicon": "^2.1.1",
        "strong-data-uri": "^1.0.0",
        "v8-debug": "~1.0.0",
        "v8-profiler": "~5.7.0",
        "which": "^1.1.1",
        "ws": "^1.0.1",
        "yargs": "^3.9.0"
    },
    "description": "Web Inspector based nodeJS debugger",
    "devDependencies": {
        "chai": "^3.5.0",
        "fs-extra": "~0.8.1",
        "install": "^0.8.7",
        "jshint": "^2.4.4",
        "mocha": "^1.21",
        "npm": "^4.4.1",
        "promise": "^7.0.3",
        "rimraf": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0f8ffffbf9a9b86540eb33c1d64e7ba546457622",
        "tarball": "https://registry.npmjs.org/node-inspector/-/node-inspector-1.1.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "624e6916ed51708fe32ff0dca644d46adefba312",
    "homepage": "http://github.com/node-inspector/node-inspector",
    "keywords": [
        "debug",
        "debugger",
        "inspector",
        "profiler"
    ],
    "maintainers": [
        {
            "name": "3y3"
        },
        {
            "name": "bajtos"
        },
        {
            "name": "dannycoates"
        },
        {
            "name": "piscisaureus"
        },
        {
            "name": "rmg"
        },
        {
            "name": "taojie"
        }
    ],
    "name": "node-inspector",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/node-inspector/node-inspector.git"
    },
    "scripts": {
        "generate-front-end": "node --harmony tools/generate-front-end",
        "pretest": "jshint .",
        "test": "mocha"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
