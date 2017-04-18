# npmtest-googleapis

#### test coverage for  [googleapis (v19.0.0)](https://github.com/google/google-api-nodejs-client#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-googleapis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-googleapis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-googleapis.svg)](https://travis-ci.org/npmtest/node-npmtest-googleapis)

#### Google APIs Client Library for Node.js

[![NPM](https://nodei.co/npm/googleapis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/googleapis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-googleapis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-googleapis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-googleapis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-googleapis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-googleapis/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-googleapis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-googleapis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-googleapis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-googleapis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-googleapis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-googleapis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-googleapis/build/test-report.html](https://npmtest.github.io/node-npmtest-googleapis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-googleapis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-googleapis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-googleapis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-googleapis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-googleapis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-googleapis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-googleapis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-googleapis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Google Inc."
    },
    "bugs": {
        "url": "https://github.com/google/google-api-nodejs-client/issues"
    },
    "contributors": [
        {
            "name": "Burcu Dogan"
        },
        {
            "name": "Jason Allor"
        },
        {
            "name": "Jason Dobry"
        },
        {
            "name": "Ryan Seys"
        },
        {
            "name": "Tim Emiola"
        },
        {
            "name": "Justin Beckwith"
        }
    ],
    "dependencies": {
        "async": "~2.3.0",
        "google-auth-library": "~0.10.0",
        "string-template": "~1.0.0"
    },
    "description": "Google APIs Client Library for Node.js",
    "devDependencies": {
        "ink-docstrap": "1.3.0",
        "intelli-espower-loader": "1.0.1",
        "js-beautify": "1.6.12",
        "jsdoc": "3.4.3",
        "minimist": "1.2.0",
        "mkdirp": "0.5.1",
        "mocha": "3.2.0",
        "nock": "9.0.12",
        "nyc": "10.2.0",
        "power-assert": "1.4.2",
        "rimraf": "2.6.1",
        "semistandard": "10.0.0",
        "swig": "1.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8700eb14294777e0c196152051fd6367061dde85",
        "tarball": "https://registry.npmjs.org/googleapis/-/googleapis-19.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "4a4cf041059ca86cd9ed5c91bd3c5c286385f8ff",
    "homepage": "https://github.com/google/google-api-nodejs-client#readme",
    "keywords": [
        "google",
        "api",
        "google apis",
        "client",
        "client library"
    ],
    "license": "Apache-2.0",
    "main": "./lib/googleapis.js",
    "maintainers": [
        {
            "name": "googleapis-packages"
        },
        {
            "name": "jdobry"
        },
        {
            "name": "ryanseys"
        },
        {
            "name": "tbetbetbe"
        },
        {
            "name": "thejbf"
        }
    ],
    "name": "googleapis",
    "nyc": {
        "exclude": [
            "apis"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/google-api-nodejs-client.git"
    },
    "scripts": {
        "build": "npm run generate-apis && npm test",
        "cover": "nyc --cache mocha test/ --recursive -t 10000 -S -R spec --require intelli-espower-loader && nyc report --reporter=html",
        "doc": "jsdoc -c jsdoc-conf.json",
        "generate-apis": "node scripts/generate",
        "lint": "semistandard \"**/*.js\"",
        "mocha": "mocha test/ --recursive -t 10000 -S -R spec --require intelli-espower-loader",
        "test": "npm run lint && npm run cover"
    },
    "semistandard": {
        "globals": [
            "after",
            "afterEach",
            "before",
            "beforeEach",
            "describe",
            "it"
        ],
        "ignore": [
            "apis",
            "templates/*"
        ]
    },
    "version": "19.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
