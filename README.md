# npmdoc-winreg

#### api documentation for  [winreg (v1.2.3)](http://fresc81.github.io/node-winreg)  [![npm package](https://img.shields.io/npm/v/npmdoc-winreg.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-winreg) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-winreg.svg)](https://travis-ci.org/npmdoc/node-npmdoc-winreg)

#### provides access to the windows registry through the REG tool

[![NPM](https://nodei.co/npm/winreg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/winreg)

- [https://npmdoc.github.io/node-npmdoc-winreg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-winreg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winreg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winreg/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-winreg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-winreg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paul Bottin"
    },
    "bugs": {
        "url": "https://github.com/fresc81/node-winreg/issues"
    },
    "dependencies": {},
    "description": "provides access to the windows registry through the REG tool",
    "devDependencies": {
        "ink-docstrap": "^1.1.4",
        "jsdoc": "^3.4.0",
        "mocha": "^3.0.2",
        "moment": "^2.11.2",
        "unit.js": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "93ad116b2696da87d58f7265a8fcea5254a965d5",
        "tarball": "https://registry.npmjs.org/winreg/-/winreg-1.2.3.tgz"
    },
    "gitHead": "36cfe63a8dcb700cf44b0b7317827099d19c26c1",
    "homepage": "http://fresc81.github.io/node-winreg",
    "keywords": [
        "windows",
        "registry"
    ],
    "license": "BSD-2-Clause",
    "main": "lib/registry.js",
    "maintainers": [
        {
            "name": "justinmchase"
        },
        {
            "name": "paul.bottin"
        }
    ],
    "name": "winreg",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fresc81/node-winreg.git"
    },
    "scripts": {
        "checkout-docs": "git clone -b gh-pages git@github.com:fresc81/node-winreg.git docs",
        "download-docs": "git clone -b gh-pages https://github.com/fresc81/node-winreg.git docs",
        "generate-docs": "jsdoc -c ./jsdoc.conf.json",
        "test": "mocha test"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
