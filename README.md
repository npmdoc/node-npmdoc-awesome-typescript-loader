# npmdoc-awesome-typescript-loader

#### api documentation for  [awesome-typescript-loader (v3.1.2)](https://github.com/s-panferov/awesome-typescript-loader)  [![npm package](https://img.shields.io/npm/v/npmdoc-awesome-typescript-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-awesome-typescript-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-awesome-typescript-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-awesome-typescript-loader)

#### Awesome TS loader for webpack

[![NPM](https://nodei.co/npm/awesome-typescript-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/awesome-typescript-loader)

- [https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "awesome-typescript-loader",
    "version": "3.1.2",
    "description": "Awesome TS loader for webpack",
    "main": "dist/entry.js",
    "typings": "./dist/index.d.ts",
    "scripts": {
        "prepublish": "npm run build",
        "watch": "npm run watch:ts",
        "watch:ts": "npm run build:ts -- --watch --diagnostics",
        "prebuild": "npm run lint",
        "compile": "tsc --pretty",
        "build": "rimraf dist && tsc --pretty",
        "lint": "tslint src/*.ts",
        "release": "standard-version",
        "test": "rimraf .test && mocha --timeout 30000 dist/__test__"
    },
    "author": "Stanislav Panferov <fnight.m@gmail.com> (http://panferov.me/)",
    "repository": {
        "type": "git",
        "url": "https://github.com/s-panferov/awesome-typescript-loader.git"
    },
    "license": "MIT",
    "keywords": [
        "webpack",
        "loader",
        "webpack-loader",
        "typescript"
    ],
    "bugs": {
        "url": "https://github.com/s-panferov/awesome-typescript-loader/issues"
    },
    "homepage": "https://github.com/s-panferov/awesome-typescript-loader",
    "dependencies": {
        "colors": "^1.1.2",
        "enhanced-resolve": "^3.1.0",
        "loader-utils": "^1.0.2",
        "lodash": "^4.17.4",
        "mkdirp": "^0.5.1",
        "object-assign": "^4.1.1",
        "source-map-support": "^0.4.11"
    },
    "devDependencies": {
        "@types/chai": "^3.4.35",
        "@types/colors": "^1.1.1",
        "@types/lodash": "^4.14.54",
        "@types/mocha": "^2.2.39",
        "@types/node": "^7.0.5",
        "@types/shelljs": "^0.7.0",
        "@types/sinon": "^1.16.35",
        "@types/webpack": "^2.2.8",
        "bluebird": "^3.5.0",
        "chai": "^3.5.0",
        "empty-module": "0.0.2",
        "fs-extra": "^2.0.0",
        "mocha": "^3.2.0",
        "ps-node": "^0.1.1",
        "rimraf": "^2.6.1",
        "shelljs": "^0.7.6",
        "standard-version": "^4.0.0",
        "temp": "^0.8.3",
        "tslint": "^4.5.1",
        "typescript": "^2.2.1",
        "webpack": "^2.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
