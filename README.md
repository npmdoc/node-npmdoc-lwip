# npmdoc-lwip

#### basic api documentation for  [lwip (v0.0.9)](https://github.com/EyalAr/lwip)  [![npm package](https://img.shields.io/npm/v/npmdoc-lwip.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lwip) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lwip.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lwip)

#### Comprehensive, fast, and simple image processing and manipulation

[![NPM](https://nodei.co/npm/lwip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lwip)

- [https://npmdoc.github.io/node-npmdoc-lwip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lwip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lwip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lwip/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lwip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lwip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lwip",
    "version": "0.0.9",
    "main": "index.js",
    "dependencies": {
        "async": "^2.0.0-rc.5",
        "bindings": "^1.2.1",
        "decree": "0.0.6",
        "nan": "^2.3.2"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "./node_modules/.bin/mocha --opts tests/mocha.opts tests",
        "coverage": "./node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha -- --opts tests/mocha.opts tests",
        "travis": "./node_modules/.bin/istanbul cover --report lcovonly ./node_modules/.bin/_mocha -- --opts tests/mocha.opts --bail tests && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "gypfile": true,
    "description": "Comprehensive, fast, and simple image processing and manipulation",
    "directories": {
        "example": "examples"
    },
    "devDependencies": {
        "coveralls": "^2.11.9",
        "istanbul": "^0.4.3",
        "mkdirp": "^0.5.1",
        "mocha": "^2.4.5",
        "mocha-lcov-reporter": "^1.2.0",
        "should": "^8.3.2"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/EyalAr/lwip.git"
    },
    "keywords": [
        "image",
        "buffer",
        "manipulate",
        "process",
        "resize",
        "scale",
        "rotate",
        "jpeg",
        "jpg",
        "png",
        "gif",
        "crop",
        "blur",
        "sharpen",
        "batch",
        "flip",
        "mirror",
        "border",
        "padding",
        "hue",
        "saturation",
        "lightness",
        "alpha",
        "transparency",
        "fade",
        "opacity",
        "contain",
        "cover"
    ],
    "author": "Eyal Arubas <eyalarubas@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/EyalAr/lwip/issues"
    },
    "homepage": "https://github.com/EyalAr/lwip",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
