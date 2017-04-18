# npmdoc-react-helmet

#### api documentation for  [react-helmet (v5.0.3)](https://github.com/nfl/react-helmet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-helmet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-helmet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-helmet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-helmet)

#### A document head manager for React

[![NPM](https://nodei.co/npm/react-helmet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-helmet)

- [https://npmdoc.github.io/node-npmdoc-react-helmet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-helmet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-helmet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-helmet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-helmet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-helmet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "NFL"
    },
    "bugs": {
        "url": "https://github.com/nfl/react-helmet/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Chris Welch"
        }
    ],
    "dependencies": {
        "deep-equal": "^1.0.1",
        "object-assign": "^4.1.1",
        "prop-types": "^15.5.4",
        "react-side-effect": "^1.1.0"
    },
    "description": "A document head manager for React",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-core": "^6.24.0",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.4.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-istanbul": "^4.0.0",
        "babel-plugin-transform-class-properties": "^6.23.0",
        "babel-plugin-transform-export-extensions": "^6.22.0",
        "babel-plugin-transform-object-rest-spread": "^6.23.0",
        "babel-plugin-transform-remove-strict-mode": "^0.0.2",
        "babel-preset-env": "^1.2.2",
        "babel-preset-react": "^6.23.0",
        "chai": "^3.5.0",
        "codecov": "^2.1.0",
        "conventional-changelog-cli": "^1.3.1",
        "cross-env": "^3.2.4",
        "cz-conventional-changelog": "^2.0.0",
        "eslint": "^3.18.0",
        "eslint-config-nfl": "^11.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-mocha": "^4.9.0",
        "eslint-plugin-react": "^6.10.2",
        "istanbul": "^0.4.5",
        "karma": "^1.5.0",
        "karma-chai": "^0.1.0",
        "karma-chai-sinon": "^0.1.5",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "^1.0.1",
        "karma-html-reporter": "^0.2.7",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.4",
        "karma-phantomjs-shim": "^1.4.0",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-spec-reporter": "^0.0.30",
        "karma-tap-reporter": "^0.0.6",
        "karma-webpack": "^2.0.3",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "^2.1.14",
        "react": "^15.x",
        "react-dom": "^15.x",
        "rimraf": "^2.6.1",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.8.0",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c6da63ee96e83aa7c8fe6d041f28dd288b1b006d",
        "tarball": "https://registry.npmjs.org/react-helmet/-/react-helmet-5.0.3.tgz"
    },
    "gitHead": "a39211b169f12bdcb0bbb6c113979e6425c31be7",
    "homepage": "https://github.com/nfl/react-helmet#readme",
    "keywords": [
        "react-helmet",
        "nfl",
        "react",
        "document",
        "head",
        "title",
        "meta",
        "link",
        "script",
        "base",
        "noscript",
        "style"
    ],
    "license": "MIT",
    "main": "./lib/Helmet.js",
    "maintainers": [
        {
            "name": "nfl"
        }
    ],
    "name": "react-helmet",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nfl/react-helmet.git"
    },
    "scripts": {
        "changelog": "conventional-changelog -p angular -i CHANGELOG.md -s",
        "clean": "rimraf lib coverage es",
        "commit": "git-cz",
        "compile": "npm run compile:commonjs && npm run compile:es",
        "compile:commonjs": "cross-env BABEL_ENV=commonjs babel src --out-dir lib",
        "compile:es": "cross-env BABEL_ENV=es babel src --out-dir es --ignore test.js",
        "lint": "eslint --ignore-path .gitignore -- .",
        "posttest": "istanbul report lcov text",
        "prepublish": "npm run compile",
        "pretest": "npm run clean && npm run lint",
        "test": "cross-env BABEL_ENV=test karma start karma.config.js"
    },
    "version": "5.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
