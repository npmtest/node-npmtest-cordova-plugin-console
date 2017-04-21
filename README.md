# npmtest-cordova-plugin-console

#### basic test coverage for  cordova-plugin-console (v1.0.6)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-plugin-console.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-plugin-console) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-plugin-console.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-plugin-console)

#### Cordova Console Plugin

[![NPM](https://nodei.co/npm/cordova-plugin-console.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-plugin-console)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-plugin-console/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-plugin-console/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-plugin-console/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-plugin-console/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-plugin-console/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-plugin-console/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-plugin-console/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-plugin-console/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova-plugin-console",
    "version": "1.0.6",
    "description": "Cordova Console Plugin",
    "cordova": {
        "id": "cordova-plugin-console",
        "platforms": [
            "ios",
            "ubuntu",
            "wp7",
            "wp8",
            "windows8",
            "windows"
        ]
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/apache/cordova-plugin-console"
    },
    "keywords": [
        "cordova",
        "console",
        "ecosystem:cordova",
        "cordova-ios",
        "cordova-ubuntu",
        "cordova-wp7",
        "cordova-wp8",
        "cordova-windows8",
        "cordova-windows"
    ],
    "scripts": {
        "test": "npm run jshint",
        "jshint": "node node_modules/jshint/bin/jshint www && node node_modules/jshint/bin/jshint src && node node_modules/jshint/bin/jshint tests"
    },
    "author": "Apache Software Foundation",
    "license": "Apache-2.0",
    "engines": {
        "cordovaDependencies": {
            "2.0.0": {
                "cordova": ">100"
            }
        }
    },
    "devDependencies": {
        "jshint": "^2.6.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
