# npmtest-hyperspace

#### basic test coverage for  [hyperspace (v2.1.4)](https://github.com/substack/hyperspace)  [![npm package](https://img.shields.io/npm/v/npmtest-hyperspace.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hyperspace) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hyperspace.svg)](https://travis-ci.org/npmtest/node-npmtest-hyperspace)

#### render streams of html on the client and the server

[![NPM](https://nodei.co/npm/hyperspace.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperspace)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hyperspace/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperspace/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hyperspace/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hyperspace/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hyperspace/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hyperspace/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hyperspace/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hyperspace/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hyperspace/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperspace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hyperspace/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hyperspace/build/test-report.html](https://npmtest.github.io/node-npmtest-hyperspace/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hyperspace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hyperspace/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hyperspace/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperspace/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperspace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperspace/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hyperspace/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hyperspace/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "browser": "browser.js",
    "bugs": {
        "url": "https://github.com/substack/hyperspace/issues"
    },
    "dependencies": {
        "domify": "~0.2.0",
        "has": "~0.0.1",
        "he": "^0.5.0",
        "hyperglue": "^1.3.0",
        "hyperstream": "^1.0.0",
        "isarray": "~0.0.1",
        "jsonify": "~0.0.0",
        "split": "~0.3.0",
        "stream-combiner2": "^1.0.1",
        "stream-splicer": "^1.3.0",
        "through2": "^1.0.0",
        "utf8-stream": "~0.0.0"
    },
    "description": "render streams of html on the client and the server",
    "devDependencies": {
        "concat-stream": "^1.4.4",
        "tape": "^2.12.3"
    },
    "directories": {},
    "dist": {
        "shasum": "bbb19be50eebffa869f0c9b4113e7c994e091956",
        "tarball": "https://registry.npmjs.org/hyperspace/-/hyperspace-2.1.4.tgz"
    },
    "gitHead": "bddbcef0905ae11c206549a1e7b087cb72b72eaf",
    "homepage": "https://github.com/substack/hyperspace",
    "keywords": [
        "html",
        "browser",
        "server",
        "render",
        "seo",
        "indexable",
        "realtime",
        "template"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        }
    ],
    "name": "hyperspace",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/hyperspace.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "testling": {
        "files": [
            "test/*.js",
            "test/browser/*.js"
        ],
        "browsers": [
            "ie/8..latest",
            "firefox/15",
            "firefox/latest",
            "firefox/nightly",
            "chrome/15",
            "chrome/latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "2.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
