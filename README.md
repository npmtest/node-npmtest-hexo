# test coverage for  [hexo (v3.3.1)](https://hexo.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-hexo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hexo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hexo.svg)](https://travis-ci.org/npmtest/node-npmtest-hexo)
#### A fast, simple & powerful blog framework, powered by Node.js.

[![NPM](https://nodei.co/npm/hexo.png?downloads=true)](https://www.npmjs.com/package/hexo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hexo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hexo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hexo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hexo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hexo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hexo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hexo/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hexo/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-hexo/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-hexo/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-hexo%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hexo/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hexo/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-hexo%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hexo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hexo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hexo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Chen",
        "email": "tommy351@gmail.com",
        "url": "http://zespia.tw"
    },
    "bin": {
        "hexo": "./bin/hexo"
    },
    "bugs": {
        "url": "https://github.com/hexojs/hexo/issues"
    },
    "dependencies": {
        "abbrev": "^1.0.7",
        "archy": "^1.0.0",
        "bluebird": "^3.4.0",
        "chalk": "^1.1.3",
        "cheerio": "^0.20.0",
        "deep-assign": "^2.0.0",
        "hexo-cli": "^1.0.2",
        "hexo-front-matter": "^0.2.2",
        "hexo-fs": "^0.1.5",
        "hexo-i18n": "^0.2.1",
        "hexo-log": "^0.1.2",
        "hexo-util": "^0.6.0",
        "js-yaml": "^3.6.1",
        "lodash": "^4.13.1",
        "minimatch": "^3.0.0",
        "moment": "~2.13.0",
        "moment-timezone": "^0.5.4",
        "nunjucks": "^2.4.2",
        "pretty-hrtime": "^1.0.2",
        "strip-indent": "^1.0.1",
        "swig": "1.4.2",
        "swig-extras": "0.0.1",
        "text-table": "^0.2.0",
        "tildify": "^1.2.0",
        "titlecase": "^1.1.2",
        "warehouse": "^2.2.0"
    },
    "description": "A fast, simple & powerful blog framework, powered by Node.js.",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^5.3.0",
        "eslint": "^2.12.0",
        "eslint-config-hexo": "^1.0.3",
        "hexo-renderer-marked": "^0.2.10",
        "istanbul": "^0.4.3",
        "jscs": "^3.0.4",
        "jscs-preset-hexo": "^1.0.1",
        "mocha": "^2.5.3",
        "rewire": "^2.5.1",
        "sinon": "^1.17.4"
    },
    "directories": {
        "lib": "./lib",
        "bin": "./bin"
    },
    "dist": {
        "shasum": "6c38653b7239536a21036bfcf2e306cb24b98f63",
        "tarball": "https://registry.npmjs.org/hexo/-/hexo-3.3.1.tgz"
    },
    "gitHead": "d3054c6c143a97f4653bada24db31a34dbd20a23",
    "homepage": "https://hexo.io/",
    "keywords": [
        "website",
        "blog",
        "cms",
        "framework",
        "hexo"
    ],
    "license": "MIT",
    "main": "lib/hexo",
    "maintainers": [
        {
            "name": "abnerchou",
            "email": "zhcjtht@hotmail.com"
        },
        {
            "name": "tommy351",
            "email": "tommy351@gmail.com"
        }
    ],
    "name": "hexo",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hexojs/hexo.git"
    },
    "scripts": {
        "eslint": "eslint .",
        "jscs": "jscs .",
        "test": "mocha test/index.js",
        "test-cov": "istanbul cover --print both _mocha -- test/index.js"
    },
    "version": "3.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
