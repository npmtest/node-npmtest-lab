# npmtest-lab

#### test coverage for  [lab (v13.0.2)](https://github.com/hapijs/lab#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lab.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lab) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lab.svg)](https://travis-ci.org/npmtest/node-npmtest-lab)

#### Test utility

[![NPM](https://nodei.co/npm/lab.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lab)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lab/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lab/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lab/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lab/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lab/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lab/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lab/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lab/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lab/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lab/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lab/build/test-report.html](https://npmtest.github.io/node-npmtest-lab/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lab/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lab/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lab/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lab/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lab/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lab/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "lab": "./bin/lab"
    },
    "bugs": {
        "url": "https://github.com/hapijs/lab/issues"
    },
    "contributors": [
        {
            "name": "Eran Hammer",
            "url": "http://hueniverse.com"
        },
        {
            "name": "Wyatt Preul",
            "url": "http://jsgeek.com"
        }
    ],
    "dependencies": {
        "bossy": "3.x.x",
        "diff": "3.x.x",
        "eslint": "3.17.x",
        "eslint-config-hapi": "10.x.x",
        "eslint-plugin-hapi": "4.x.x",
        "espree": "3.x.x",
        "find-rc": "3.0.x",
        "handlebars": "4.x.x",
        "hoek": "4.x.x",
        "items": "2.x.x",
        "json-stable-stringify": "1.x.x",
        "json-stringify-safe": "5.x.x",
        "mkdirp": "0.5.x",
        "seedrandom": "2.4.x",
        "source-map": "0.5.x",
        "source-map-support": "0.4.x"
    },
    "description": "Test utility",
    "devDependencies": {
        "code": "4.x.x",
        "cpr": "2.0.x",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "lab-event-reporter": "1.x.x",
        "rimraf": "2.6.x"
    },
    "directories": {},
    "dist": {
        "shasum": "1b2fefa079cca68a88d3567ee39ab84f75a80a1f",
        "tarball": "https://registry.npmjs.org/lab/-/lab-13.0.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "bcecf841680a877ccfbb1bbab8f94c6aac75dd03",
    "homepage": "https://github.com/hapijs/lab#readme",
    "keywords": [
        "test"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "marsup"
        },
        {
            "name": "nlf"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "lab",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/lab.git"
    },
    "scripts": {
        "lint": "node ./bin/_lab -d -f -L",
        "lint-md": "eslint --config hapi --rule 'strict: 0, eol-last: 0' --plugin markdown --ext md  .",
        "posttest": "npm run lint-md",
        "test": "node ./bin/_lab -fL -t 100 -m 3000",
        "test-cov-html": "node ./bin/_lab -fL -r html -m 3000 -o coverage.html"
    },
    "version": "13.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
