# npmtest-to-markdown

#### test coverage for  [to-markdown (v3.0.4)](https://github.com/domchristie/to-markdown#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-to-markdown.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-to-markdown) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-to-markdown.svg)](https://travis-ci.org/npmtest/node-npmtest-to-markdown)

#### HTML-to-Markdown converter

[![NPM](https://nodei.co/npm/to-markdown.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/to-markdown)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-to-markdown/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-to-markdown/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-to-markdown/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-to-markdown/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-to-markdown/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-to-markdown/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-to-markdown/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-to-markdown/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-to-markdown/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-to-markdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-to-markdown/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-to-markdown/build/test-report.html](https://npmtest.github.io/node-npmtest-to-markdown/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-to-markdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-to-markdown/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-to-markdown/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-to-markdown/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-to-markdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-to-markdown/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-to-markdown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-to-markdown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dom Christie"
    },
    "browser": {
        "jsdom": false
    },
    "bugs": {
        "url": "https://github.com/domchristie/to-markdown/issues"
    },
    "dependencies": {
        "collapse-whitespace": "1.1.2",
        "jsdom": "^9.0.0"
    },
    "description": "HTML-to-Markdown converter",
    "devDependencies": {
        "qunit": "^0.7.6",
        "saucie": "0.1.3",
        "standard": "^6.0.8",
        "testem": "^0.8.2",
        "watchify": "^2.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3c7822f9286bc294ff37f9e0e5e23154c122ce69",
        "tarball": "https://registry.npmjs.org/to-markdown/-/to-markdown-3.0.4.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "0ffa85ad0194e541dddd2fd5d6c2065adb0d4d41",
    "homepage": "https://github.com/domchristie/to-markdown#readme",
    "keywords": [
        "markdown"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "domchristie"
        }
    ],
    "name": "to-markdown",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/domchristie/to-markdown.git"
    },
    "scripts": {
        "start": "watchify -s toMarkdown -o dist/to-markdown.js index.js -v",
        "test": "standard index.js lib/**/*.js test/**/*.js && qunit -c ./index.js -t ./test/to-markdown-test.js ./test/gfm-test.js"
    },
    "url": "http://domchristie.github.com/to-markdown/",
    "version": "3.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
