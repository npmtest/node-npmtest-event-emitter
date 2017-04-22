# npmtest-event-emitter

#### basic test coverage for  [event-emitter (v0.3.5)](https://github.com/medikoo/event-emitter#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-event-emitter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-event-emitter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-event-emitter.svg)](https://travis-ci.org/npmtest/node-npmtest-event-emitter)

#### Environment agnostic event emitter

[![NPM](https://nodei.co/npm/event-emitter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/event-emitter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-event-emitter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-event-emitter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-event-emitter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-event-emitter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-event-emitter/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-event-emitter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-event-emitter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-event-emitter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-event-emitter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-event-emitter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-event-emitter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-event-emitter/build/test-report.html](https://npmtest.github.io/node-npmtest-event-emitter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-event-emitter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-event-emitter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-event-emitter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-event-emitter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-event-emitter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-event-emitter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-event-emitter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-event-emitter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/event-emitter/issues"
    },
    "dependencies": {
        "d": "1",
        "es5-ext": "~0.10.14"
    },
    "description": "Environment agnostic event emitter",
    "devDependencies": {
        "tad": "~0.2.7",
        "xlint": "~0.2.2",
        "xlint-jslint-medikoo": "~0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "df8c69eef1647923c7157b9ce83840610b02cc39",
        "tarball": "https://registry.npmjs.org/event-emitter/-/event-emitter-0.3.5.tgz"
    },
    "gitHead": "b951397b8f0d55fc7ae8aea7fa7699e48132a53d",
    "homepage": "https://github.com/medikoo/event-emitter#readme",
    "keywords": [
        "event",
        "events",
        "trigger",
        "observer",
        "listener",
        "emitter",
        "pubsub"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "event-emitter",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/event-emitter.git"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node ./node_modules/tad/bin/tad"
    },
    "version": "0.3.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
