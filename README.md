# npmdoc-image-diff

#### api documentation for  [image-diff (v1.6.3)](https://github.com/uber/image-diff)  [![npm package](https://img.shields.io/npm/v/npmdoc-image-diff.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-image-diff) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-image-diff.svg)](https://travis-ci.org/npmdoc/node-npmdoc-image-diff)

#### Create image differential between two images

[![NPM](https://nodei.co/npm/image-diff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-diff)

- [https://npmdoc.github.io/node-npmdoc-image-diff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-image-diff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-diff/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-image-diff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-image-diff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Todd Wolfson",
        "url": "http://twolfson.com/"
    },
    "bin": {
        "image-diff": "bin/image-diff"
    },
    "bugs": {
        "url": "https://github.com/uber/image-diff/issues"
    },
    "dependencies": {
        "async": "~0.2.9",
        "buffered-spawn": "~1.1.1",
        "commander": "~2.9.0",
        "gm": "~1.21.1",
        "mkdirp": "~0.3.5",
        "tmp": "0.0.23"
    },
    "description": "Create image differential between two images",
    "devDependencies": {
        "foundry": "~3.1.0",
        "foundry-release-git": "~1.1.0",
        "foundry-release-npm": "~1.1.0",
        "get-pixels": "~1.0.1",
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.11",
        "grunt-contrib-jshint": "~0.6.0",
        "grunt-contrib-watch": "~0.4.0",
        "mocha": "~1.11.0",
        "rimraf": "~2.2.6"
    },
    "directories": {},
    "dist": {
        "shasum": "818a0e656ae89480e802e7ef14db460826f730fc",
        "tarball": "https://registry.npmjs.org/image-diff/-/image-diff-1.6.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "40b49d8f8055a8385182b507fa84a510b4c68a46",
    "homepage": "https://github.com/uber/image-diff",
    "keywords": [
        "image",
        "diff"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/uber/image-diff/blob/master/LICENSE-MIT"
        }
    ],
    "main": "lib/image-diff",
    "maintainers": [
        {
            "name": "twolfson"
        },
        {
            "name": "mlmorg"
        },
        {
            "name": "uber"
        }
    ],
    "name": "image-diff",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/uber/image-diff.git"
    },
    "scripts": {
        "test": "grunt jshint && mocha"
    },
    "version": "1.6.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
