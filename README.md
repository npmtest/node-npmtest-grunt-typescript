# npmtest-grunt-typescript

#### basic test coverage for  [grunt-typescript (v0.8.0)](https://github.com/k-maru/grunt-typescript)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-typescript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-typescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-typescript.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-typescript)

#### compile typescript to javascript

[![NPM](https://nodei.co/npm/grunt-typescript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-typescript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-typescript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-typescript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-typescript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-typescript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-typescript/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-typescript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-typescript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-typescript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-typescript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-typescript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-typescript/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-typescript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-typescript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-typescript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-typescript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-typescript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-typescript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-typescript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "kazuhide maruyama",
    "name": "grunt-typescript",
    "description": "compile typescript to javascript",
    "version": "0.8.0",
    "homepage": "https://github.com/k-maru/grunt-typescript",
    "repository": {
        "type": "git",
        "url": "git@github.com:k-maru/grunt-typescript.git"
    },
    "bugs": {
        "url": "https://github.com/k-maru/grunt-typescript/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/k-maru/grunt-typescript/blob/master/LICENSE"
        }
    ],
    "main": "Gruntfile.js",
    "scripts": {
        "start": "grunt build",
        "test": "grunt test"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "dependencies": {
        "typescript": "1.6.2",
        "bluebird": "~2.9.34",
        "chokidar": "^1.0.5"
    },
    "peerDependencies": {
        "grunt": "~0.4.5"
    },
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-contrib-nodeunit": "~0.4.1",
        "grunt-contrib-clean": "~0.6.0"
    },
    "optionalDependencies": {},
    "keywords": [
        "gruntplugin",
        "typescript"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
