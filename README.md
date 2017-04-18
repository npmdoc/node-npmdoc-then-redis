# npmdoc-then-redis

#### api documentation for  [then-redis (v2.0.1)](https://github.com/mjackson/then-redis#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-then-redis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-then-redis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-then-redis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-then-redis)

#### Promise-based Redis client

[![NPM](https://nodei.co/npm/then-redis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/then-redis)

- [https://npmdoc.github.io/node-npmdoc-then-redis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-then-redis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-then-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-then-redis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-then-redis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-then-redis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Jackson"
    },
    "bugs": {
        "url": "https://github.com/mjackson/then-redis/issues"
    },
    "dependencies": {},
    "description": "Promise-based Redis client",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-eslint": "^6.0.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-register": "^6.7.2",
        "eslint": "^2.4.0",
        "eslint-config-airbnb": "^6.1.0",
        "eslint-plugin-react": "^4.2.1",
        "expect": "^1.19.0",
        "mocha": "^2.0.1",
        "readline-sync": "^1.4.1",
        "rimraf": "^2.5.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e797f18fff7f3c50bfc2ae95a35db5ad0b0816ff",
        "tarball": "https://registry.npmjs.org/then-redis/-/then-redis-2.0.1.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "596bfd68e2510d7e3ae1ac7ef43aa06723b274f4",
    "homepage": "https://github.com/mjackson/then-redis#readme",
    "keywords": [
        "redis",
        "then",
        "promise",
        "promises"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "mjackson"
        }
    ],
    "name": "then-redis",
    "optionalDependencies": {},
    "peerDependencies": {
        "redis": "*",
        "redis-commands": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mjackson/then-redis.git"
    },
    "scripts": {
        "build": "rimraf lib && babel ./modules -d lib --ignore '__tests__'",
        "lint": "eslint modules",
        "prepublish": "npm run build",
        "release": "node ./scripts/release.js",
        "test": "npm run lint && mocha --compilers js:babel-register --reporter spec 'modules/**/*-test.js'"
    },
    "version": "2.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
