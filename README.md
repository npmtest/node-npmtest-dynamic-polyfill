# npmtest-dynamic-polyfill

#### basic test coverage for  dynamic-polyfill (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-dynamic-polyfill.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dynamic-polyfill) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dynamic-polyfill.svg)](https://travis-ci.org/npmtest/node-npmtest-dynamic-polyfill)

#### Dynamically polyfill only when needed by the browser. Complementary to Polyfill.io

[![NPM](https://nodei.co/npm/dynamic-polyfill.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dynamic-polyfill)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dynamic-polyfill/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dynamic-polyfill/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dynamic-polyfill/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/test-report.html](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dynamic-polyfill/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dynamic-polyfill",
    "version": "1.0.0",
    "description": "Dynamically polyfill only when needed by the browser. Complementary to Polyfill.io",
    "main": "index.js",
    "scripts": {
        "build": "babel src --presets babel-preset-es2015 --out-dir ./"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/pascalaoms/dynamic-polyfill"
    },
    "keywords": [
        "es6",
        "es7",
        "es2015",
        "es2016",
        "polyfill",
        "dynamic",
        "polfill.io"
    ],
    "author": "Pascal Klau <email@artofmyself.com> (http://artofmyself.com)",
    "license": "MIT",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-preset-es2015": "^6.22.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
