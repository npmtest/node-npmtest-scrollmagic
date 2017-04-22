# npmtest-scrollmagic

#### basic test coverage for  [scrollmagic (v2.0.5)](http://ScrollMagic.io)  [![npm package](https://img.shields.io/npm/v/npmtest-scrollmagic.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-scrollmagic) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-scrollmagic.svg)](https://travis-ci.org/npmtest/node-npmtest-scrollmagic)

#### The javascript library for magical scroll interactions.

[![NPM](https://nodei.co/npm/scrollmagic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/scrollmagic)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-scrollmagic/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-scrollmagic/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-scrollmagic/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-scrollmagic/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-scrollmagic/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-scrollmagic/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-scrollmagic/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-scrollmagic/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-scrollmagic/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-scrollmagic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-scrollmagic/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-scrollmagic/build/test-report.html](https://npmtest.github.io/node-npmtest-scrollmagic/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-scrollmagic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-scrollmagic/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-scrollmagic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-scrollmagic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-scrollmagic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-scrollmagic/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-scrollmagic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-scrollmagic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "scrollmagic",
    "title": "ScrollMagic",
    "version": "2.0.5",
    "description": "The javascript library for magical scroll interactions.",
    "author": {
        "name": "Jan Paepke",
        "url": "http://www.janpaepke.de"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/janpaepke/ScrollMagic.git"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/janpaepke/ScrollMagic/blob/master/LICENSE.md"
        },
        {
            "type": "GPL-3.0+",
            "url": "http://www.gnu.org/licenses/gpl-3.0.html"
        }
    ],
    "main": "scrollmagic/uncompressed/ScrollMagic.js",
    "engines": {
        "node": "0.10.x"
    },
    "devDependencies": {
        "del": "^0.1.3",
        "gulp": "^3.8.10",
        "gulp-beautify": "^1.1.1",
        "gulp-concat-util": "^0.5.1",
        "gulp-file-include": "^0.7.0",
        "gulp-jshint": "^1.9.0",
        "gulp-json-editor": "^2.2.1",
        "gulp-karma": "0.0.4",
        "gulp-open": "^0.3.0",
        "gulp-plumber": "^0.6.6",
        "gulp-rename": "^1.2.0",
        "gulp-replace-task": "^0.1.0",
        "gulp-uglify": "^1.0.1",
        "gulp-util": "^3.0.1",
        "gzip-size": "^1.0.0",
        "jsdoc": "^3.3.0-beta1",
        "jshint-stylish": "^1.0.0",
        "karma": "^0.12.21",
        "karma-chrome-launcher": "^0.1.4",
        "karma-jasmine": "^0.2.2",
        "karma-requirejs": "^0.2.2",
        "pretty-bytes": "^1.0.2",
        "semver": "^3.0.1",
        "through2": "^0.6.3",
        "yargs": "^1.3.2"
    },
    "directories": {
        "lib": "./scrollmagic",
        "doc": "./doc",
        "example": "./examples"
    },
    "scripts": {
        "test": "./node_modules/karma/bin/karma start ./dev/tests/karma.conf.js",
        "start": "node ./node_modules/gulp/bin/gulp open-demo"
    },
    "homepage": "http://ScrollMagic.io",
    "keywords": [
        "scroll",
        "scrolling",
        "animation",
        "sticky",
        "pin",
        "fixed",
        "scrollbar",
        "scrub",
        "sync",
        "position",
        "progress",
        "parallax",
        "events",
        "classes",
        "jquery-plugin",
        "ecosystem:jquery"
    ],
    "bugs": "https://github.com/janpaepke/ScrollMagic/issues",
    "files": [
        "scrollmagic",
        "LICENSE.md",
        "README.md"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
