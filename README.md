# npmtest-json2yaml

#### basic test coverage for  json2yaml (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-json2yaml.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json2yaml) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json2yaml.svg)](https://travis-ci.org/npmtest/node-npmtest-json2yaml)

#### A commandline utility to convert JSON to YAML / YML

[![NPM](https://nodei.co/npm/json2yaml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json2yaml)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json2yaml/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json2yaml/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json2yaml/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json2yaml/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json2yaml/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json2yaml/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json2yaml/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json2yaml/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json2yaml/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json2yaml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json2yaml/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json2yaml/build/test-report.html](https://npmtest.github.io/node-npmtest-json2yaml/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json2yaml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json2yaml/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json2yaml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json2yaml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json2yaml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json2yaml/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json2yaml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json2yaml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "AJ ONeal <coolaj86@gmail.com> (http://coolaj86.com)",
    "name": "json2yaml",
    "description": "A commandline utility to convert JSON to YAML / YML",
    "keywords": [
        "yml",
        "yaml",
        "json",
        "cli",
        "util"
    ],
    "version": "1.1.0",
    "license": "Apache-2.0",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/coolaj86/json2yaml.git"
    },
    "bin": {
        "json2yaml": "./cli.js",
        "jsontoyaml": "./cli.js",
        "jsontoyml": "./cli.js",
        "json2yml": "./cli.js"
    },
    "engines": {
        "node": ">= 0.2.0"
    },
    "test": "echo 'error no test'; exit 1",
    "dependencies": {
        "remedial": "1.x"
    },
    "devDependencies": {},
    "preferGlobal": true
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
