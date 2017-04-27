# npmtest-simplify-js

#### basic test coverage for  [simplify-js (v1.2.1)](http://mourner.github.com/simplify-js/)  [![npm package](https://img.shields.io/npm/v/npmtest-simplify-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-simplify-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-simplify-js.svg)](https://travis-ci.org/npmtest/node-npmtest-simplify-js)

#### A high-performance JavaScript 2D/3D polyline simplification library

[![NPM](https://nodei.co/npm/simplify-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/simplify-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-simplify-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-simplify-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-simplify-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-simplify-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-simplify-js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-simplify-js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-simplify-js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-simplify-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-simplify-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-simplify-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-simplify-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-simplify-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-simplify-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-simplify-js/build/test-report.html](https://npmtest.github.io/node-npmtest-simplify-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-simplify-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-simplify-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-simplify-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-simplify-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-simplify-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-simplify-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-simplify-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-simplify-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vladimir Agafonkin"
    },
    "bugs": {
        "url": "https://github.com/mourner/simplify-js/issues"
    },
    "dependencies": {},
    "description": "A high-performance JavaScript 2D/3D polyline simplification library",
    "devDependencies": {
        "faucet": "0.0.1",
        "jshint": "^2.5.0",
        "tape": "^2.12.3"
    },
    "directories": {},
    "dist": {
        "shasum": "fa216b40454f48175450e0fea1bd1e6ab39fcbc0",
        "tarball": "https://registry.npmjs.org/simplify-js/-/simplify-js-1.2.1.tgz"
    },
    "homepage": "http://mourner.github.com/simplify-js/",
    "jshintConfig": {
        "quotmark": "single",
        "trailing": true,
        "unused": true
    },
    "keywords": [
        "math",
        "geometry",
        "polyline",
        "simplification"
    ],
    "main": "simplify.js",
    "maintainers": [
        {
            "name": "mourner"
        }
    ],
    "name": "simplify-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mourner/simplify-js.git"
    },
    "scripts": {
        "test": "jshint simplify.js test.js && node test.js | faucet"
    },
    "version": "1.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
