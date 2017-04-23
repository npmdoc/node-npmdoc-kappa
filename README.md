# npmdoc-kappa

#### api documentation for  [kappa (v1.0.0-rc.14)](https://github.com/krakenjs/kappa#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-kappa.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-kappa) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-kappa.svg)](https://travis-ci.org/npmdoc/node-npmdoc-kappa)

#### A hierarchical npm-registry proxy to make private registries easier. (Based on npm-delegate by @jden)

[![NPM](https://nodei.co/npm/kappa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kappa)

- [https://npmdoc.github.io/node-npmdoc-kappa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kappa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kappa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kappa/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-kappa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-kappa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Toth"
    },
    "bin": {
        "kappa": "kappa.js"
    },
    "bugs": {
        "url": "https://github.com/krakenjs/kappa/issues"
    },
    "contributors": [
        {
            "name": "Trevor Livingston"
        }
    ],
    "dependencies": {
        "async": "^0.9.0",
        "content-type": "^1.0.1",
        "hapi": "^7.0.0",
        "hoek": "^2.4.1",
        "minimist": "^1.1.0",
        "shortstop": "^1.0.1",
        "shortstop-handlers": "^1.0.0",
        "wreck": "^5.0.0"
    },
    "description": "A hierarchical npm-registry proxy to make private registries easier. (Based on npm-delegate by @jden)",
    "devDependencies": {
        "istanbul": "^0.3.0",
        "jshint": "^2.5.4",
        "nock": "^0.45.0",
        "tape": "^2.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fc51d10741ff00647cf48240dd7ba8a147a02e52",
        "tarball": "https://registry.npmjs.org/kappa/-/kappa-1.0.0-rc.14.tgz"
    },
    "engineStrict": true,
    "engines": {
        "node": ">=0.10.30"
    },
    "gitHead": "760cf6e4c4119641abdded1768f8e36696dd7be6",
    "homepage": "https://github.com/krakenjs/kappa#readme",
    "keywords": [
        "npm",
        "registry",
        "private",
        "proxy"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "totherik"
        },
        {
            "name": "jeffharrell"
        },
        {
            "name": "tlivings"
        },
        {
            "name": "jasisk"
        }
    ],
    "name": "kappa",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krakenjs/kappa.git"
    },
    "scripts": {
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "jshint -c .jshintrc index.js lib/*.js",
        "test": "tape test/*.js"
    },
    "version": "1.0.0-rc.14"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
