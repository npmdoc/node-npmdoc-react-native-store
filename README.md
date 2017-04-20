# npmdoc-react-native-store

#### api documentation for  [react-native-store (v0.4.1)](https://github.com/thewei/react-native-store)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-native-store.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-native-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-native-store.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-native-store)

#### A simple database base on react-native AsyncStorage.

[![NPM](https://nodei.co/npm/react-native-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-store)

- [https://npmdoc.github.io/node-npmdoc-react-native-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-store/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-native-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-native-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-store",
    "version": "0.4.1",
    "description": "A simple database base on react-native AsyncStorage.",
    "main": "./lib/index.js",
    "scripts": {
        "watch": "babel src --watch --presets es2015,stage-0 --out-dir lib",
        "build": "babel src --presets es2015,stage-0 --out-dir lib",
        "test": "jest --verbose"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/thewei/react-native-store.git"
    },
    "jest": {
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "testPathIgnorePatterns": [
            "/node_modules/"
        ],
        "testFileExtensions": [
            "js"
        ],
        "testPathDirs": [
            "src"
        ],
        "unmockedModulePathPatterns": [
            "promise",
            "source-map"
        ]
    },
    "keywords": [
        "react-component",
        "react-native",
        "ios",
        "android",
        "react",
        "AsyncStorage",
        "dataBase"
    ],
    "author": "thewei",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/thewei/react-native-store/issues"
    },
    "homepage": "https://github.com/thewei/react-native-store",
    "devDependencies": {
        "babel-cli": "^6.4.0",
        "babel-jest": "^6.0.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "jest": "^0.1.40",
        "jest-cli": "^0.8.2",
        "react-native": "^0.18.0-rc"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
