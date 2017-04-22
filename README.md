# npmtest-url

#### basic test coverage for  [url (v0.11.0)](https://github.com/defunctzombie/node-url#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-url.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-url) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-url.svg)](https://travis-ci.org/npmtest/node-npmtest-url)

#### The core `url` packaged standalone for use with Browserify.

[![NPM](https://nodei.co/npm/url.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/url)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-url/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-url/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-url/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-url/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-url/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-url/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-url/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-url/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-url/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-url/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-url/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-url/build/test-report.html](https://npmtest.github.io/node-npmtest-url/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-url/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-url/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-url/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-url/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-url/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-url/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-url/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-url/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/defunctzombie/node-url/issues"
    },
    "dependencies": {
        "punycode": "1.3.2",
        "querystring": "0.2.0"
    },
    "description": "The core 'url' packaged standalone for use with Browserify.",
    "devDependencies": {
        "assert": "1.1.1",
        "mocha": "1.18.2",
        "zuul": "3.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3838e97cfc60521eb73c525a8e55bfdd9e2e28f1",
        "tarball": "https://registry.npmjs.org/url/-/url-0.11.0.tgz"
    },
    "gitHead": "7f82d6b09acba099163fede09b4226b4e55a5377",
    "homepage": "https://github.com/defunctzombie/node-url#readme",
    "license": "MIT",
    "main": "./url.js",
    "maintainers": [
        {
            "name": "coolaj86"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "url",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/defunctzombie/node-url.git"
    },
    "scripts": {
        "test": "mocha --ui qunit test.js && zuul -- test.js",
        "test-local": "zuul --local -- test.js"
    },
    "version": "0.11.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
