# npmtest-pouchdb

#### basic test coverage for  [pouchdb (v6.2.0)](https://github.com/pouchdb/pouchdb#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pouchdb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pouchdb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pouchdb.svg)](https://travis-ci.org/npmtest/node-npmtest-pouchdb)

#### PouchDB is a pocket-sized database

[![NPM](https://nodei.co/npm/pouchdb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pouchdb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pouchdb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pouchdb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pouchdb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pouchdb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pouchdb/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pouchdb/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pouchdb/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pouchdb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pouchdb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pouchdb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pouchdb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pouchdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pouchdb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pouchdb/build/test-report.html](https://npmtest.github.io/node-npmtest-pouchdb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pouchdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pouchdb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pouchdb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pouchdb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pouchdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pouchdb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pouchdb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pouchdb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dale Harvey"
    },
    "browser": {
        "./lib/index.js": "./lib/index-browser.js",
        "./lib/index.es.js": "./lib/index-browser.es.js"
    },
    "bugs": {
        "url": "https://github.com/pouchdb/pouchdb/issues"
    },
    "dependencies": {
        "argsarray": "0.0.1",
        "buffer-from": "0.1.1",
        "clone-buffer": "1.0.0",
        "debug": "2.6.1",
        "double-ended-queue": "2.1.0-0",
        "immediate": "3.0.6",
        "inherits": "2.0.3",
        "level-codec": "7.0.0",
        "level-write-stream": "1.0.0",
        "leveldown": "1.5.0",
        "levelup": "1.3.5",
        "lie": "3.1.1",
        "ltgt": "2.1.3",
        "readable-stream": "1.0.33",
        "request": "2.80.0",
        "spark-md5": "3.0.0",
        "through2": "2.0.3",
        "vuvuzela": "1.0.3"
    },
    "description": "PouchDB is a pocket-sized database",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5c8521b46cfc83644ca7fc61a7b240d2ce17dc0d",
        "tarball": "https://registry.npmjs.org/pouchdb/-/pouchdb-6.2.0.tgz"
    },
    "files": [
        "lib",
        "dist",
        "tonic-example.js"
    ],
    "homepage": "https://github.com/pouchdb/pouchdb#readme",
    "jsnext:main": "./lib/index.es.js",
    "jspm": {
        "main": "dist/pouchdb.js"
    },
    "keywords": [
        "db",
        "couchdb",
        "pouchdb"
    ],
    "license": "Apache-2.0",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "chesles"
        },
        {
            "name": "cwmma"
        },
        {
            "name": "daleharvey"
        },
        {
            "name": "eckoit"
        },
        {
            "name": "garrensmith"
        },
        {
            "name": "nickcolley"
        },
        {
            "name": "nolanlawson"
        },
        {
            "name": "willholley"
        }
    ],
    "name": "pouchdb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pouchdb/pouchdb.git"
    },
    "scripts": {},
    "tags": [
        "db",
        "couchdb",
        "pouchdb"
    ],
    "tonicExampleFilename": "tonic-example.js",
    "version": "6.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
