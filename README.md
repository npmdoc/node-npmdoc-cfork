# api documentation for  [cfork (v1.6.0)](https://github.com/node-modules/cfork)  [![npm package](https://img.shields.io/npm/v/npmdoc-cfork.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cfork) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cfork.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cfork)
#### cluster fork and restart easy way

[![NPM](https://nodei.co/npm/cfork.png?downloads=true)](https://www.npmjs.com/package/cfork)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cfork/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-cfork%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cfork/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cfork/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cfork/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "email": "fengmk2@gmail.com",
        "url": "http://fengmk2.com"
    },
    "bugs": {
        "url": "https://github.com/node-modules/cfork/issues",
        "email": "fengmk2@gmail.com"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "JacksonTian",
            "email": "shyvo1987@gmail.com",
            "url": "https://github.com/JacksonTian"
        },
        {
            "name": "dead-horse",
            "email": "heyiyu.deadhorse@gmail.com",
            "url": "https://github.com/dead-horse"
        },
        {
            "name": "coderhaoxin",
            "email": "coderhaoxin@outlook.com",
            "url": "https://github.com/coderhaoxin"
        },
        {
            "name": "luckydrq",
            "email": "drqzju@gmail.com",
            "url": "https://github.com/luckydrq"
        },
        {
            "name": "hustxiaoc",
            "email": "xiaoc.hust@gmail.com",
            "url": "https://github.com/hustxiaoc"
        },
        {
            "name": "Flandre Scarlet",
            "email": "i@2333.moe",
            "url": "https://github.com/XadillaX"
        }
    ],
    "dependencies": {},
    "description": "cluster fork and restart easy way",
    "devDependencies": {
        "childprocess": "1",
        "contributors": "*",
        "eslint": "3.9.0",
        "graceful": "1",
        "istanbul": "^0.4.0",
        "mocha": "2",
        "pedding": "1",
        "should": "11.1.1",
        "urllib": "2"
    },
    "directories": {},
    "dist": {
        "shasum": "24fba60015d4ad9c648040247a85401bb664c390",
        "tarball": "https://registry.npmjs.org/cfork/-/cfork-1.6.0.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "6696f6089e155d8639771099f7c59a2d5b2c8ba2",
    "homepage": "https://github.com/node-modules/cfork",
    "keywords": [
        "cluster",
        "cluster-fork",
        "cfork",
        "restart"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com"
        }
    ],
    "name": "cfork",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/cfork.git",
        "web": "https://github.com/node-modules/cfork"
    },
    "scripts": {
        "ci": "mocha -t 15000 test/*.test.js",
        "clean": "rm -rf coverage",
        "cover": "node --harmony node_modules/.bin/istanbul cover --include-all-sources --report none --print none node_modules/.bin/_mocha -- -t 15000 test/*.test.js",
        "lint": "eslint index.js test",
        "test": "npm run clean && npm run lint && npm run cover && istanbul report json lcov html text"
    },
    "version": "1.6.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cfork](#apidoc.module.cfork)



# <a name="apidoc.module.cfork"></a>[module cfork](#apidoc.module.cfork)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
