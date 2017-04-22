# npmtest-bell.js

#### basic test coverage for  bell.js (v2.0.5)  [![npm package](https://img.shields.io/npm/v/npmtest-bell.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bell.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bell.js.svg)](https://travis-ci.org/npmtest/node-npmtest-bell.js)

#### Real-time anomalies(outliers) detection system for periodic time series

[![NPM](https://nodei.co/npm/bell.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bell.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bell.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bell.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bell.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bell.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bell.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bell.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bell.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bell.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bell.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bell.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bell.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bell.js/build/test-report.html](https://npmtest.github.io/node-npmtest-bell.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bell.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bell.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bell.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bell.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bell.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bell.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bell.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bell.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bell.js",
    "version": "2.0.5",
    "repository": {
        "type": "git",
        "url": "https://github.com/eleme/bell.js"
    },
    "description": "Real-time anomalies(outliers) detection system for periodic time series",
    "author": {
        "name": "Chao Wang",
        "url": "https://github.com/hit9"
    },
    "keywords": [
        "anomaly",
        "outlier",
        "metric",
        "realtime",
        "statsd"
    ],
    "engines": {
        "iojs": ">=1.1",
        "node": ">=0.12"
    },
    "main": "./statsd.js",
    "dependencies": {
        "bluebird": "2.3.11",
        "clone": "1.0.2",
        "co": "^4.4.0",
        "commander": "2.3.0",
        "fivebeans": "1.1.1",
        "koa": "^1.1.2",
        "koa-basic-auth": "1.1.2",
        "koa-bodyparser": "2.0.1",
        "koa-mount": "1.3.0",
        "koa-route": "2.0.0",
        "koa-static": "1.4.6",
        "minimatch": "1.0.0",
        "nunjucks": "2.1.0",
        "sequelize": "3.12.1",
        "sqlite3": "3.1.1",
        "ssdb": "~0.3.8"
    },
    "devDependencies": {
        "bower": "~1.6.3",
        "del": "~2.0.2",
        "gulp": "~3.9.0",
        "gulp-concat": "~2.6.0",
        "gulp-debug": "~2.1.2",
        "gulp-if": "~2.0.0",
        "gulp-minify-css": "~1.2.1",
        "gulp-uglify": "~1.4.2",
        "jshint": "~2.8.0",
        "ntt": ">=0.0.5",
        "yargs": "~3.29.0",
        "bootstrap": "3.3.5",
        "bootswatch": "3.3.5",
        "cubism": "1.6.0",
        "d3": "3.5.6",
        "jquery": "2.1.4"
    },
    "scripts": {
        "test": "node --harmony test.js"
    },
    "bin": {
        "bell": "./bin/bell.js"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
