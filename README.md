# npmtest-fast-levenshtein

#### test coverage for  [fast-levenshtein (v2.0.6)](https://github.com/hiddentao/fast-levenshtein#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-fast-levenshtein.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fast-levenshtein) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fast-levenshtein.svg)](https://travis-ci.org/npmtest/node-npmtest-fast-levenshtein)

#### Efficient implementation of Levenshtein algorithm  with locale-specific collator support.

[![NPM](https://nodei.co/npm/fast-levenshtein.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fast-levenshtein)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fast-levenshtein/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fast-levenshtein/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fast-levenshtein/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fast-levenshtein/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fast-levenshtein/build/test-report.html](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fast-levenshtein/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fast-levenshtein/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fast-levenshtein/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fast-levenshtein/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fast-levenshtein/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ramesh Nair",
        "url": "http://www.hiddentao.com/"
    },
    "bugs": {
        "url": "https://github.com/hiddentao/fast-levenshtein/issues"
    },
    "dependencies": {},
    "description": "Efficient implementation of Levenshtein algorithm  with locale-specific collator support.",
    "devDependencies": {
        "chai": "~1.5.0",
        "grunt": "~0.4.1",
        "grunt-benchmark": "~0.2.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-jshint": "~0.4.3",
        "grunt-contrib-uglify": "~0.2.0",
        "grunt-mocha-test": "~0.2.2",
        "grunt-npm-install": "~0.1.0",
        "load-grunt-tasks": "~0.6.0",
        "lodash": "^4.0.1",
        "mocha": "~1.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3d8a5c66883a16a30ca8643e851f19baa7797917",
        "tarball": "https://registry.npmjs.org/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz"
    },
    "files": [
        "levenshtein.js"
    ],
    "gitHead": "5bffe7151f99fb02f319f70a004e653105a760fb",
    "homepage": "https://github.com/hiddentao/fast-levenshtein#readme",
    "keywords": [
        "levenshtein",
        "distance",
        "string"
    ],
    "license": "MIT",
    "main": "levenshtein.js",
    "maintainers": [
        {
            "name": "hiddentao"
        }
    ],
    "name": "fast-levenshtein",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hiddentao/fast-levenshtein.git"
    },
    "scripts": {
        "benchmark": "grunt benchmark",
        "build": "grunt build",
        "prepublish": "npm run build",
        "test": "mocha"
    },
    "version": "2.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
