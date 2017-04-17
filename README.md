# test coverage for  [mochify (v3.1.1)](https://github.com/mantoni/mochify.js)  [![npm package](https://img.shields.io/npm/v/npmtest-mochify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mochify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mochify.svg)](https://travis-ci.org/npmtest/node-npmtest-mochify)
#### TDD with Browserify, Mocha, PhantomJS and WebDriver

[![NPM](https://nodei.co/npm/mochify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mochify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mochify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mochify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mochify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mochify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mochify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mochify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mochify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mochify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mochify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mochify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mochify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mochify/build/test-report.html](https://npmtest.github.io/node-npmtest-mochify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mochify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mochify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mochify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mochify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mochify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mochify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mochify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mochify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maximilian Antoni",
        "url": "http://maxantoni.de"
    },
    "bin": {
        "mochify": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/mantoni/mochify.js/issues"
    },
    "contributors": [
        {
            "name": "Andrey Popp"
        },
        {
            "name": "JP Richardson"
        },
        {
            "name": "Jerome Gravel-Niquet"
        },
        {
            "name": "Barney"
        },
        {
            "name": "Daniel Davidson"
        },
        {
            "name": "Fernando Lores"
        },
        {
            "name": "Ryohei Ikegami"
        },
        {
            "name": "Max Goodman"
        },
        {
            "name": "Phil Jepsen"
        },
        {
            "name": "Jacob Waller"
        },
        {
            "name": "Dylan Fogarty-MacDonald"
        },
        {
            "name": "Paul"
        },
        {
            "name": "James Newell"
        },
        {
            "name": "Adrian Chang"
        },
        {
            "name": "Christopher Hiller"
        },
        {
            "name": "Scott Corgan"
        },
        {
            "name": "Chris Wheatley"
        },
        {
            "name": "Moshe Kolodny"
        },
        {
            "name": "Juha Hytönen"
        },
        {
            "name": "Koki Takahashi"
        },
        {
            "name": "Jonny Reeves"
        },
        {
            "name": "Jarrett Cruger"
        },
        {
            "name": "Tomer Lahav"
        },
        {
            "name": "Wes"
        }
    ],
    "dependencies": {
        "brout": "^1.1.0",
        "browserify": "^14.1.0",
        "consolify": "^2.1.0",
        "coverify": "^1.4.1",
        "glob": "^7.0.5",
        "min-wd": "^2.9.0",
        "mocaccino": "^2.0.0",
        "mocha": "^3.2.0",
        "phantomic": "^1.4.0",
        "resolve": "^1.1.6",
        "source-mapper": "^2.0.0",
        "subarg": "^1.0.0",
        "through2": "^2.0.0",
        "watchify": "^3.7.0",
        "which": "^1.2.1"
    },
    "description": "TDD with Browserify, Mocha, PhantomJS and WebDriver",
    "devDependencies": {
        "@studio/changes": "^1.1.0",
        "eslint": "^1.10.3",
        "tmp": "0.0.28"
    },
    "directories": {},
    "dist": {
        "shasum": "0499c7a70d38156772ea09e4f043b9ab9460c6ff",
        "tarball": "https://registry.npmjs.org/mochify/-/mochify-3.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "bin",
        "lib",
        "scripts",
        "README.md",
        "LICENSE"
    ],
    "gitHead": "23cae90982dc4ebb1c72d1d3db3ba6c419ebba0d",
    "homepage": "https://github.com/mantoni/mochify.js",
    "keywords": [
        "mocha",
        "browserify",
        "watchify",
        "phantomjs",
        "webdriver",
        "selenium",
        "saucelabs",
        "tdd"
    ],
    "license": "MIT",
    "main": "lib/mochify.js",
    "maintainers": [
        {
            "name": "mantoni"
        },
        {
            "name": "boneskull"
        }
    ],
    "name": "mochify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mantoni/mochify.js.git"
    },
    "scripts": {
        "lint": "eslint .",
        "postinstall": "node scripts/postinstall.js",
        "posttest": "npm run lint",
        "postversion": "git push --follow-tags && npm publish",
        "preversion": "npm test",
        "test": "mocha",
        "version": "changes",
        "watch": "mocha --watch"
    },
    "version": "3.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
