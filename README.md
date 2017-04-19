# npmdoc-ms

#### api documentation for  [ms (v1.0.0)](https://github.com/zeit/ms#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ms.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ms) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ms.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ms)

#### Tiny milisecond conversion utility

[![NPM](https://nodei.co/npm/ms.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ms)

- [https://npmdoc.github.io/node-npmdoc-ms/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ms/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ms/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ms/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ms/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/zeit/ms/issues"
    },
    "dependencies": {},
    "description": "Tiny milisecond conversion utility",
    "devDependencies": {
        "eslint": "3.18.0",
        "expect.js": "0.3.1",
        "husky": "0.13.2",
        "lint-staged": "3.4.0",
        "mocha": "3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "59adcd22edc543f7b5381862d31387b1f4bc9473",
        "tarball": "https://registry.npmjs.org/ms/-/ms-1.0.0.tgz"
    },
    "eslintConfig": {
        "extends": "eslint:recommended",
        "env": {
            "node": true,
            "es6": true
        }
    },
    "files": [
        "index.js"
    ],
    "gitHead": "7daf984a9011e720cc3c165ed82c4506f3471b37",
    "homepage": "https://github.com/zeit/ms#readme",
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "npm run lint",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "main": "./index",
    "maintainers": [
        {
            "name": "leo"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "ms",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/ms.git"
    },
    "scripts": {
        "lint": "eslint lib/* bin/*",
        "precommit": "lint-staged",
        "test": "mocha tests.js"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
