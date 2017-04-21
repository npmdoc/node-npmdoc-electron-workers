# npmdoc-electron-workers

#### api documentation for  [electron-workers (v1.10.1)](https://github.com/bjrmatos/electron-workers)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-workers.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-workers) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-workers.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-workers)

#### Run electron scripts in managed workers

[![NPM](https://nodei.co/npm/electron-workers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-workers)

- [https://npmdoc.github.io/node-npmdoc-electron-workers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-workers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-workers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-workers/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-workers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-workers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "BJR Matos"
    },
    "bugs": {
        "url": "https://github.com/bjrmatos/electron-workers/issues"
    },
    "dependencies": {
        "debug": "2.3.3",
        "lodash.findindex": "4.6.0",
        "net-cluster": "0.0.2",
        "portscanner": "1.2.0",
        "uuid": "3.0.1",
        "which": "1.2.12"
    },
    "description": "Run electron scripts in managed workers",
    "devDependencies": {
        "babel": "5.8.38",
        "electron": "1.4.12",
        "eslint": "2.13.1",
        "eslint-config-airbnb-base": "3.0.1",
        "eslint-plugin-import": "1.16.0",
        "in-publish": "2.0.0",
        "mocha": "2.5.3",
        "npm-run-all": "2.3.0",
        "rimraf": "2.5.4",
        "should": "9.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "62079b1fc443cda10b245d018d65303950b9b4cf",
        "tarball": "https://registry.npmjs.org/electron-workers/-/electron-workers-1.10.1.tgz"
    },
    "gitHead": "b1942d87f02676ec6e0e5705f3c0ef481863c640",
    "homepage": "https://github.com/bjrmatos/electron-workers",
    "keywords": [
        "electron",
        "headless",
        "workers",
        "electron spawn"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "bjrmatos"
        }
    ],
    "name": "electron-workers",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/bjrmatos/electron-workers.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "clean": "rimraf lib",
        "lint": "eslint src test",
        "prepublish": "in-publish && npm-run-all lint clean build || not-in-publish",
        "test": "mocha --timeout 9000"
    },
    "version": "1.10.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
