# test coverage for  [st (v1.2.0)](https://github.com/isaacs/st#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-st.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-st) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-st.svg)](https://travis-ci.org/npmtest/node-npmtest-st)
#### A module for serving static files.  Does etags, caching, etc.

[![NPM](https://nodei.co/npm/st.png?downloads=true)](https://www.npmjs.com/package/st)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-st/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-st/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-st/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-st/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-st/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-st/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-st/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-st/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-st/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-st/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-st%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-st/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-st/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-st%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-st/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-st/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-st/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "email": "i@izs.me",
        "url": "http://blog.izs.me/"
    },
    "bin": {
        "st": "bin/server.js"
    },
    "bugs": {
        "url": "https://github.com/isaacs/st/issues"
    },
    "dependencies": {
        "async-cache": "~1.1.0",
        "bl": "~1.1.2",
        "fd": "~0.0.2",
        "graceful-fs": "~4.1.4",
        "mime": "~1.3.4",
        "negotiator": "~0.6.1"
    },
    "description": "A module for serving static files.  Does etags, caching, etc.",
    "devDependencies": {
        "request": "~2.72.0",
        "rimraf": "~2.5.2",
        "tap": "~5.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e6313c1836a0889e8507be5bb189b2245266c2df",
        "tarball": "https://registry.npmjs.org/st/-/st-1.2.0.tgz"
    },
    "gitHead": "2a5f970083ee44a03c3cbcb21a12d0ac90230200",
    "homepage": "https://github.com/isaacs/st#readme",
    "keywords": [
        "static",
        "file",
        "serve",
        "etag",
        "autoindex",
        "cache"
    ],
    "license": "ISC",
    "main": "st.js",
    "maintainers": [
        {
            "name": "isaacs",
            "email": "i@izs.me"
        },
        {
            "name": "rvagg",
            "email": "rod@vagg.org"
        }
    ],
    "name": "st",
    "optionalDependencies": {
        "graceful-fs": "~4.1.4"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/isaacs/st.git"
    },
    "scripts": {
        "test": "tap test/*.js test/cli/*-test.js"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
