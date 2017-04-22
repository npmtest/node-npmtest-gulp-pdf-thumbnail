# npmtest-gulp-pdf-thumbnail

#### basic test coverage for  [gulp-pdf-thumbnail (v1.0.0)](https://github.com/samuelmartineau/gulp-pdf-thumbnail#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-pdf-thumbnail.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-pdf-thumbnail) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-pdf-thumbnail.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-pdf-thumbnail)

#### Gulp plugin that generate PNG thumbnail from PDF files.

[![NPM](https://nodei.co/npm/gulp-pdf-thumbnail.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-pdf-thumbnail)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-pdf-thumbnail/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-pdf-thumbnail/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-pdf-thumbnail/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-pdf-thumbnail/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-pdf-thumbnail/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-pdf-thumbnail/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-pdf-thumbnail/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Samuel Martineau",
        "url": "samuelmartineau.github.io"
    },
    "bugs": {
        "url": "https://github.com/samuelmartineau/gulp-pdf-thumbnail/issues"
    },
    "dependencies": {
        "gm": "1.23.0",
        "gulp-util": "3.0.7",
        "replace-ext": "1.0.0",
        "through2": "2.0.1"
    },
    "description": "Gulp plugin that generate PNG thumbnail from PDF files.",
    "devDependencies": {
        "coveralls": "2.11.14",
        "istanbul": "0.4.5",
        "nock-exec": "0.1.0",
        "tape": "4.6.0",
        "vinyl": "1.2.0",
        "vinyl-file": "2.0.0",
        "xo": "0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9f11435f03941ee9d3fcfb26f9566754da925e1f",
        "tarball": "https://registry.npmjs.org/gulp-pdf-thumbnail/-/gulp-pdf-thumbnail-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "8a3010d438ed8f8a33385ce1b519596b4a0a7e54",
    "homepage": "https://github.com/samuelmartineau/gulp-pdf-thumbnail#readme",
    "keywords": [
        "gulpplugin",
        "thumbnail",
        "pdf",
        "gm"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "samuelmartineau"
        }
    ],
    "name": "gulp-pdf-thumbnail",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/samuelmartineau/gulp-pdf-thumbnail.git"
    },
    "scripts": {
        "coveralls": "istanbul cover tape -R spec ./tests/**/*.js",
        "tape": "tape tests/**/*.js",
        "test": "xo && npm run tape"
    },
    "version": "1.0.0",
    "xo": {
        "esnext": true
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
