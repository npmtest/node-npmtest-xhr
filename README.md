# test coverage for  [xhr (v2.4.0)](https://github.com/naugtur/xhr)  [![npm package](https://img.shields.io/npm/v/npmtest-xhr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xhr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xhr.svg)](https://travis-ci.org/npmtest/node-npmtest-xhr)
#### small xhr abstraction

[![NPM](https://nodei.co/npm/xhr.png?downloads=true)](https://www.npmjs.com/package/xhr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xhr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xhr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xhr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xhr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xhr/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xhr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xhr/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xhr/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-xhr/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-xhr/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-xhr%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xhr/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xhr/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-xhr%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xhr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xhr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xhr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos",
        "email": "raynos2@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/naugtur/xhr/issues",
        "email": "naugtur@gmail.com"
    },
    "contributors": [
        {
            "name": "Jake Verbaten"
        },
        {
            "name": "Zbyszek Tenerowicz",
            "email": "naugtur@gmail.com"
        }
    ],
    "dependencies": {
        "global": "~4.3.0",
        "is-function": "^1.0.1",
        "parse-headers": "^2.0.0",
        "xtend": "^4.0.0"
    },
    "description": "small xhr abstraction",
    "devDependencies": {
        "for-each": "^0.3.2",
        "pre-commit": "1.0.10",
        "run-browser": "github:naugtur/run-browser",
        "tap-spec": "^4.0.2",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e16e66a45f869861eeefab416d5eff722dc40993",
        "tarball": "https://registry.npmjs.org/xhr/-/xhr-2.4.0.tgz"
    },
    "gitHead": "a7b434418b6164a5e23439c5bb7466e5f82d457e",
    "homepage": "https://github.com/naugtur/xhr",
    "keywords": [
        "xhr",
        "http",
        "xmlhttprequest",
        "xhr2",
        "browserify"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "raynos",
            "email": "raynos2@gmail.com"
        },
        {
            "name": "naugtur",
            "email": "naugtur@gmail.com"
        }
    ],
    "name": "xhr",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/naugtur/xhr.git"
    },
    "scripts": {
        "browser": "run-browser -m test/mock-server.js test/index.js",
        "test": "run-browser test/index.js -b -m test/mock-server.js | tap-spec"
    },
    "version": "2.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
