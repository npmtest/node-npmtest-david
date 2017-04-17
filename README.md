# test coverage for  [david (v11.0.0)](https://github.com/alanshaw/david#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-david.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-david) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-david.svg)](https://travis-ci.org/npmtest/node-npmtest-david)
#### Node.js module that tells you when your project npm dependencies are out of date.

[![NPM](https://nodei.co/npm/david.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/david)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-david/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-david/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-david/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-david/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-david/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-david/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-david/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-david/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-david/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-david/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-david/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-david/build/test-report.html](https://npmtest.github.io/node-npmtest-david/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-david/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-david/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-david/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-david/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-david/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-david/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-david/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-david/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alan Shaw"
    },
    "bin": {
        "david": "bin/david.js"
    },
    "bugs": {
        "url": "https://github.com/alanshaw/david/issues"
    },
    "dependencies": {
        "async": "^2.0.1",
        "cli-color-tty": "^2.0.0",
        "cli-table": "^0.3.1",
        "exit": "^0.1.2",
        "minimist": "^1.1.0",
        "npm": "^4.0.3",
        "semver": "^5.3.0",
        "xtend": "^4.0.0"
    },
    "description": "Node.js module that tells you when your project npm dependencies are out of date.",
    "devDependencies": {
        "coveralls": "^2.11.12",
        "istanbul": "^0.4.0",
        "jshint": "^2.5.1",
        "rewire": "^2.1.0",
        "rimraf": "^2.5.4",
        "standard": "^9.0.0",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "039da9427072fb7767f4daa56a54eca24dcc2bc3",
        "tarball": "https://registry.npmjs.org/david/-/david-11.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.1"
    },
    "files": [
        "bin",
        "lib",
        "LICENCE"
    ],
    "gitHead": "90c8beee96cb2cb927e28f18796e2d58c1dd6760",
    "homepage": "https://github.com/alanshaw/david#readme",
    "license": "MIT",
    "main": "lib/david.js",
    "maintainers": [
        {
            "name": "alanshaw"
        }
    ],
    "name": "david",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/alanshaw/david.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "test": "standard && istanbul cover node_modules/tape/bin/tape test/*.js"
    },
    "version": "11.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
