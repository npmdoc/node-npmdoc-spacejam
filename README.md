# npmdoc-spacejam

#### api documentation for  [spacejam (v1.6.1)](https://github.com/practicalmeteor/spacejam)  [![npm package](https://img.shields.io/npm/v/npmdoc-spacejam.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-spacejam) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-spacejam.svg)](https://travis-ci.org/npmdoc/node-npmdoc-spacejam)

#### Run your meteor package tinytests and mocha tests from the command line with phantomjs.

[![NPM](https://nodei.co/npm/spacejam.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spacejam)

- [https://npmdoc.github.io/node-npmdoc-spacejam/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spacejam/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spacejam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spacejam/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-spacejam/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-spacejam/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "spacejam",
    "version": "1.6.1",
    "dependencies": {
        "chai": "1.9.2",
        "glob": "4.0.6",
        "loglevel": "1.1.0",
        "phantomjs-prebuilt": "^2.1.7",
        "psext": "0.0.4",
        "rc": "0.5.1",
        "semver": "4.1.0",
        "underscore": "1.7.0"
    },
    "devDependencies": {
        "coffee-script": "1.8.0",
        "mocha": "1.21.5",
        "sinon-chai": "2.6.0",
        "tmp": "0.0.25",
        "xmldom": "0.1.19",
        "xpath": "0.0.9"
    },
    "main": "lib/main.js",
    "scripts": {
        "test": "bin/npm-test.sh",
        "compile": "cake compile",
        "prepublish": "cake compile"
    },
    "bin": {
        "spacejam": "bin/spacejam",
        "spacejam-mocha": "bin/spacejam-mocha",
        "spacejam-init-bashrc": "bin/spacejam-init-bashrc",
        "meteor-mocha": "bin/meteor-mocha",
        "mrun": "bin/mrun",
        "mtp": "bin/mtp",
        "set-meteor-env": "bin/set-meteor-env",
        "unset-meteor-env": "bin/unset-meteor-env",
        "mongo-reset": "bin/mongo-reset",
        "mdeploy": "bin/mdeploy",
        "mpublish": "bin/mpublish",
        "mmpublish": "bin/mmpublish",
        "npm-publish": "bin/npm-publish"
    },
    "description": "Run your meteor package tinytests and mocha tests from the command line with phantomjs.",
    "homepage": "https://github.com/practicalmeteor/spacejam",
    "bugs": "https://github.com/practicalmeteor/spacejam/issues",
    "keywords": [
        "spacejam",
        "meteor",
        "test-packages",
        "test-in-console",
        "tinytest",
        "mocha",
        "mocha.js",
        "practicalmeteor",
        "practicalmeteor:mocha",
        "practicalmeteor:mocha-console-runner",
        "ci",
        "continuous integration",
        "cd",
        "continuous delivery"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/practicalmeteor/spacejam/blob/master/LICENSE.txt"
        }
    ],
    "engines": {
        "node": ">= 0.10.x",
        "npm": ">= 1.4.x"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/practicalmeteor/spacejam.git"
    },
    "author": {
        "name": "Spacejam.io",
        "url": "http://spacejam.io/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
