# npmtest-svg4everybody

#### basic test coverage for  [svg4everybody (v2.1.8)](https://github.com/jonathantneal/svg4everybody#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-svg4everybody.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg4everybody) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg4everybody.svg)](https://travis-ci.org/npmtest/node-npmtest-svg4everybody)

#### Use external SVG spritemaps in any browser

[![NPM](https://nodei.co/npm/svg4everybody.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg4everybody)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg4everybody/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg4everybody/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg4everybody/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg4everybody/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg4everybody/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-svg4everybody/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-svg4everybody/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg4everybody/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg4everybody/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg4everybody/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg4everybody/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg4everybody/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg4everybody/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg4everybody/build/test-report.html](https://npmtest.github.io/node-npmtest-svg4everybody/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg4everybody/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg4everybody/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg4everybody/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg4everybody/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg4everybody/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg4everybody/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg4everybody/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg4everybody/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Neal",
        "url": "http://jonathantneal.com"
    },
    "bugs": {
        "url": "https://github.com/jonathantneal/svg4everybody/issues"
    },
    "contributors": [
        {
            "name": "Federico Brigante",
            "url": "https://github.com/bfred-it"
        },
        {
            "name": "Matija Marohnić",
            "url": "https://github.com/silvenon"
        },
        {
            "name": "Michał Rumanek",
            "url": "https://github.com/michal-rumanek"
        },
        {
            "name": "Oleg Andreyev",
            "url": "https://github.com/oleg-andreyev"
        },
        {
            "name": "Shawn Allen",
            "url": "https://github.com/shawnbot"
        }
    ],
    "dependencies": {},
    "description": "Use external SVG spritemaps in any browser",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-contrib-jshint": "^0.12.0",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-eslint": "^17.3.1",
        "grunt-jscs": "^2.7.0",
        "grunt-umd": "^2.4.0",
        "load-grunt-tasks": "^3.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c4fb648999104fc02225852f847ccfbc0b6d7586",
        "tarball": "https://registry.npmjs.org/svg4everybody/-/svg4everybody-2.1.8.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "377d27208fcad3671ed466e9511556cb9c8b5bd8",
    "homepage": "https://github.com/jonathantneal/svg4everybody#readme",
    "keywords": [
        "contents",
        "defs",
        "externals",
        "fallbacks",
        "icons",
        "ie8s",
        "ie9s",
        "oldies",
        "safaris",
        "sprites",
        "spritemaps",
        "svgs",
        "symbols",
        "uses"
    ],
    "license": "CC0-1.0",
    "main": "dist/svg4everybody.js",
    "maintainers": [
        {
            "name": "jonathantneal"
        },
        {
            "name": "nathanross"
        },
        {
            "name": "shawnbot"
        },
        {
            "name": "timeiscoffee"
        }
    ],
    "name": "svg4everybody",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonathantneal/svg4everybody.git"
    },
    "scripts": {
        "build": "grunt build",
        "clean": "git checkout dist/svg4everybody.js && git checkout dist/svg4everybody.min.js && git checkout dist/svg4everybody.legacy.js && git checkout dist/svg4everybody.legacy.min.js",
        "test": "grunt test",
        "watch": "grunt build:watch"
    },
    "version": "2.1.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
