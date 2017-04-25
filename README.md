# npmdoc-node-plantuml

#### basic api documentation for  [node-plantuml (v0.5.0)](https://github.com/markushedvall/node-plantuml)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-plantuml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-plantuml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-plantuml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-plantuml)

#### A Node.js module and CLI for running PlantUML

[![NPM](https://nodei.co/npm/node-plantuml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-plantuml)

- [https://npmdoc.github.io/node-npmdoc-node-plantuml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Markus Hedvall"
    },
    "bin": {
        "puml": "index.js"
    },
    "bugs": {
        "url": "https://github.com/markushedvall/node-plantuml/issues"
    },
    "dependencies": {
        "commander": "^2.8.1",
        "node-nailgun-client": "^0.1.0",
        "node-nailgun-server": "^0.1.3",
        "plantuml-encoder": "^1.2.4"
    },
    "description": "A Node.js module and CLI for running PlantUML",
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^2.3.1",
        "shelljs": "^0.5.3",
        "standard": "^5.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "03c2ed856e6b272c714a1568453a747c266fdc1f",
        "tarball": "https://registry.npmjs.org/node-plantuml/-/node-plantuml-0.5.0.tgz"
    },
    "gitHead": "0b8d48c58c9632536180c4b10fe7e9af67a48f7d",
    "homepage": "https://github.com/markushedvall/node-plantuml",
    "keywords": [
        "plantuml",
        "uml",
        "diagram"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "markushedvall"
        }
    ],
    "name": "node-plantuml",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/markushedvall/node-plantuml.git"
    },
    "scripts": {
        "build": "node nail/build.js",
        "test": "standard && node test/fixtures/prepare.js && mocha"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
