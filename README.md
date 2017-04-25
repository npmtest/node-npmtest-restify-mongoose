# npmtest-restify-mongoose

#### basic test coverage for  [restify-mongoose (v2.0.1)](https://github.com/saintedlama/restify-mongoose#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-restify-mongoose.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-restify-mongoose) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-restify-mongoose.svg)](https://travis-ci.org/npmtest/node-npmtest-restify-mongoose)

#### Expose mongoose models as REST resources

[![NPM](https://nodei.co/npm/restify-mongoose.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/restify-mongoose)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-restify-mongoose/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-restify-mongoose/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-restify-mongoose/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-restify-mongoose/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-restify-mongoose/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-restify-mongoose/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-restify-mongoose/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-restify-mongoose/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-restify-mongoose/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-restify-mongoose/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-restify-mongoose/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-restify-mongoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-restify-mongoose/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-restify-mongoose/build/test-report.html](https://npmtest.github.io/node-npmtest-restify-mongoose/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-restify-mongoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-restify-mongoose/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-restify-mongoose/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-restify-mongoose/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-restify-mongoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-restify-mongoose/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-restify-mongoose/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-restify-mongoose/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "christoph.walcher@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/saintedlama/restify-mongoose/issues"
    },
    "contributors": [
        {
            "name": "Matthieu Bacconnier",
            "url": "http://blog.neamar.fr"
        },
        {
            "name": "Dave Jensen",
            "url": "http://build47.com"
        },
        {
            "name": "Ismar Slomic"
        }
    ],
    "dependencies": {
        "async": "~2.3.0",
        "mongoose": "~4.9.3",
        "restify": "~4.3.0"
    },
    "description": "Expose mongoose models as REST resources",
    "devDependencies": {
        "changelog": "^1.0.7",
        "cross-env": "^1.0.8",
        "istanbul": "^0.4.5",
        "jshint": "^2.9.4",
        "mocha": "~3.2.0",
        "shelljs": "^0.7.7",
        "should": "~11.2.1",
        "supertest": "~3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dd358218c94456762cc8695c5a3d83a7ba6fb84b",
        "tarball": "https://registry.npmjs.org/restify-mongoose/-/restify-mongoose-2.0.1.tgz"
    },
    "gitHead": "7a243195097adac809f714936a9a5446fc10a14b",
    "homepage": "https://github.com/saintedlama/restify-mongoose#readme",
    "keywords": [
        "restify",
        "mongoose",
        "REST",
        "resource"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ismarslomic"
        },
        {
            "name": "matthieu.bacconnier"
        },
        {
            "name": "saintedlama"
        }
    ],
    "name": "restify-mongoose",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/saintedlama/restify-mongoose.git"
    },
    "scripts": {
        "changelog": "changelog all -m > CHANGELOG.md",
        "cover": "cross-env NODE_ENV=test istanbul cover ./node_modules/mocha/bin/_mocha --report html -- -R spec",
        "lint": "jshint **.js",
        "test": "cross-env NODE_ENV=test mocha -R spec test/"
    },
    "version": "2.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
