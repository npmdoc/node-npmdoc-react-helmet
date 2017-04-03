# api documentation for  [react-helmet (v5.0.2)](https://github.com/nfl/react-helmet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-helmet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-helmet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-helmet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-helmet)
#### A document head manager for React

[![NPM](https://nodei.co/npm/react-helmet.png?downloads=true)](https://www.npmjs.com/package/react-helmet)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-helmet/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-helmet_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-helmet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-helmet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-helmet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "NFL",
        "email": "engineers@nfl.com"
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
            "name": "Chris Welch",
            "email": "chris.welch@nfl.com"
        }
    ],
    "dependencies": {
        "deep-equal": "^1.0.1",
        "object-assign": "^4.1.1",
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
        "shasum": "2905f9e174650b74c26983d75dc45f3ebf561890",
        "tarball": "https://registry.npmjs.org/react-helmet/-/react-helmet-5.0.2.tgz"
    },
    "gitHead": "ce5a7b1e391f7af9e9cfc9d57b7cf3771d539b7c",
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
            "name": "nfl",
            "email": "richard.herrera@nfl.com"
        }
    ],
    "name": "react-helmet",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=15.0.0"
    },
    "readme": "ERROR: No README data found!",
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
    "version": "5.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-helmet](#apidoc.module.react-helmet)
1.  boolean <span class="apidocSignatureSpan">react-helmet.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-helmet.</span>Helmet ()](#apidoc.element.react-helmet.Helmet)
1.  [function <span class="apidocSignatureSpan">react-helmet.</span>default ()](#apidoc.element.react-helmet.default)
1.  object <span class="apidocSignatureSpan">react-helmet.</span>Helmet.propTypes
1.  object <span class="apidocSignatureSpan">react-helmet.</span>Helmet.prototype
1.  object <span class="apidocSignatureSpan">react-helmet.</span>HelmetUtils

#### [module react-helmet.Helmet](#apidoc.module.react-helmet.Helmet)
1.  [function <span class="apidocSignatureSpan">react-helmet.</span>Helmet ()](#apidoc.element.react-helmet.Helmet.Helmet)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.</span>peek ()](#apidoc.element.react-helmet.Helmet.peek)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.</span>renderStatic ()](#apidoc.element.react-helmet.Helmet.renderStatic)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.</span>rewind ()](#apidoc.element.react-helmet.Helmet.rewind)
1.  object <span class="apidocSignatureSpan">react-helmet.Helmet.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-helmet.Helmet.</span>propTypes

#### [module react-helmet.Helmet.propTypes](#apidoc.module.react-helmet.Helmet.propTypes)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>base ()](#apidoc.element.react-helmet.Helmet.propTypes.base)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>bodyAttributes ()](#apidoc.element.react-helmet.Helmet.propTypes.bodyAttributes)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>children ()](#apidoc.element.react-helmet.Helmet.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>defaultTitle ()](#apidoc.element.react-helmet.Helmet.propTypes.defaultTitle)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>encodeSpecialCharacters ()](#apidoc.element.react-helmet.Helmet.propTypes.encodeSpecialCharacters)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>htmlAttributes ()](#apidoc.element.react-helmet.Helmet.propTypes.htmlAttributes)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>link ()](#apidoc.element.react-helmet.Helmet.propTypes.link)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>meta ()](#apidoc.element.react-helmet.Helmet.propTypes.meta)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>noscript ()](#apidoc.element.react-helmet.Helmet.propTypes.noscript)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>onChangeClientState ()](#apidoc.element.react-helmet.Helmet.propTypes.onChangeClientState)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>script ()](#apidoc.element.react-helmet.Helmet.propTypes.script)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>style ()](#apidoc.element.react-helmet.Helmet.propTypes.style)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>title ()](#apidoc.element.react-helmet.Helmet.propTypes.title)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>titleAttributes ()](#apidoc.element.react-helmet.Helmet.propTypes.titleAttributes)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>titleTemplate ()](#apidoc.element.react-helmet.Helmet.propTypes.titleTemplate)

#### [module react-helmet.Helmet.prototype](#apidoc.module.react-helmet.Helmet.prototype)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>flattenArrayTypeChildren (_ref)](#apidoc.element.react-helmet.Helmet.prototype.flattenArrayTypeChildren)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapArrayTypeChildrenToProps (arrayTypeChildren, newProps)](#apidoc.element.react-helmet.Helmet.prototype.mapArrayTypeChildrenToProps)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapChildrenToProps (children, newProps)](#apidoc.element.react-helmet.Helmet.prototype.mapChildrenToProps)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapNestedChildrenToProps (child, nestedChildren)](#apidoc.element.react-helmet.Helmet.prototype.mapNestedChildrenToProps)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapObjectTypeChildren (_ref2)](#apidoc.element.react-helmet.Helmet.prototype.mapObjectTypeChildren)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>render ()](#apidoc.element.react-helmet.Helmet.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.react-helmet.Helmet.prototype.shouldComponentUpdate)
1.  [function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>warnOnInvalidChildren (child, nestedChildren)](#apidoc.element.react-helmet.Helmet.prototype.warnOnInvalidChildren)

#### [module react-helmet.HelmetUtils](#apidoc.module.react-helmet.HelmetUtils)
1.  boolean <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>convertReactPropstoHtmlAttributes (props)](#apidoc.element.react-helmet.HelmetUtils.convertReactPropstoHtmlAttributes)
1.  [function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>handleClientStateChange (newState)](#apidoc.element.react-helmet.HelmetUtils.handleClientStateChange)
1.  [function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>mapStateOnServer (_ref)](#apidoc.element.react-helmet.HelmetUtils.mapStateOnServer)
1.  [function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>reducePropsToState (propsList)](#apidoc.element.react-helmet.HelmetUtils.reducePropsToState)
1.  [function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>requestIdleCallback (cb)](#apidoc.element.react-helmet.HelmetUtils.requestIdleCallback)
1.  [function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>warn (msg)](#apidoc.element.react-helmet.HelmetUtils.warn)



# <a name="apidoc.module.react-helmet"></a>[module react-helmet](#apidoc.module.react-helmet)

#### <a name="apidoc.element.react-helmet.Helmet"></a>[function <span class="apidocSignatureSpan">react-helmet.</span>Helmet ()](#apidoc.element.react-helmet.Helmet)
- description and source-code
```javascript
function HelmetWrapper() {
    _classCallCheck(this, HelmetWrapper);

    return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.default"></a>[function <span class="apidocSignatureSpan">react-helmet.</span>default ()](#apidoc.element.react-helmet.default)
- description and source-code
```javascript
function HelmetWrapper() {
    _classCallCheck(this, HelmetWrapper);

    return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-helmet.Helmet"></a>[module react-helmet.Helmet](#apidoc.module.react-helmet.Helmet)

#### <a name="apidoc.element.react-helmet.Helmet.Helmet"></a>[function <span class="apidocSignatureSpan">react-helmet.</span>Helmet ()](#apidoc.element.react-helmet.Helmet.Helmet)
- description and source-code
```javascript
function HelmetWrapper() {
    _classCallCheck(this, HelmetWrapper);

    return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.peek"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.</span>peek ()](#apidoc.element.react-helmet.Helmet.peek)
- description and source-code
```javascript
function peek() {
  return state;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.renderStatic"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.</span>renderStatic ()](#apidoc.element.react-helmet.Helmet.renderStatic)
- description and source-code
```javascript
renderStatic = function () {
    var mappedState = Component.rewind();
    if (!mappedState) {
        // provide fallback if mappedState is undefined
        mappedState = (0, _HelmetUtils.mapStateOnServer)({
            baseTag: [],
            bodyAttributes: {},
            encodeSpecialCharacters: true,
            htmlAttributes: {},
            linkTags: [],
            metaTags: [],
            noscriptTags: [],
            scriptTags: [],
            styleTags: [],
            title: "",
            titleAttributes: {}
        });
    }

    return mappedState;
}
```
- example usage
```shell
...

npm:
'''bash
npm install --save react-helmet
'''

## Server Usage
To use on the server, call 'Helmet.renderStatic()' after 'ReactDOMServer.renderToString' or 'ReactDOMServer.renderToStaticMarkup
' to get the head data for use in your prerender.

Because this component keeps track of mounted instances, **you have to make sure to call 'renderStatic' on server**, or you'll get
 a memory leak.

'''javascript
ReactDOMServer.renderToString(<Handler />);
const helmet = Helmet.renderStatic();
'''
...
```

#### <a name="apidoc.element.react-helmet.Helmet.rewind"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.</span>rewind ()](#apidoc.element.react-helmet.Helmet.rewind)
- description and source-code
```javascript
rewind = function () {
    var mappedState = Component.rewind();
    if (!mappedState) {
        // provide fallback if mappedState is undefined
        mappedState = (0, _HelmetUtils.mapStateOnServer)({
            baseTag: [],
            bodyAttributes: {},
            encodeSpecialCharacters: true,
            htmlAttributes: {},
            linkTags: [],
            metaTags: [],
            noscriptTags: [],
            scriptTags: [],
            styleTags: [],
            title: "",
            titleAttributes: {}
        });
    }

    return mappedState;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-helmet.Helmet.propTypes"></a>[module react-helmet.Helmet.propTypes](#apidoc.module.react-helmet.Helmet.propTypes)

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.base"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>base ()](#apidoc.element.react-helmet.Helmet.propTypes.base)
- description and source-code
```javascript
base = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.bodyAttributes"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>bodyAttributes ()](#apidoc.element.react-helmet.Helmet.propTypes.bodyAttributes)
- description and source-code
```javascript
bodyAttributes = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>children ()](#apidoc.element.react-helmet.Helmet.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.defaultTitle"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>defaultTitle ()](#apidoc.element.react-helmet.Helmet.propTypes.defaultTitle)
- description and source-code
```javascript
defaultTitle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.encodeSpecialCharacters"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>encodeSpecialCharacters ()](#apidoc.element.react-helmet.Helmet.propTypes.encodeSpecialCharacters)
- description and source-code
```javascript
encodeSpecialCharacters = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.htmlAttributes"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>htmlAttributes ()](#apidoc.element.react-helmet.Helmet.propTypes.htmlAttributes)
- description and source-code
```javascript
htmlAttributes = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.link"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>link ()](#apidoc.element.react-helmet.Helmet.propTypes.link)
- description and source-code
```javascript
link = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.meta"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>meta ()](#apidoc.element.react-helmet.Helmet.propTypes.meta)
- description and source-code
```javascript
meta = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.noscript"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>noscript ()](#apidoc.element.react-helmet.Helmet.propTypes.noscript)
- description and source-code
```javascript
noscript = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.onChangeClientState"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>onChangeClientState ()](#apidoc.element.react-helmet.Helmet.propTypes.onChangeClientState)
- description and source-code
```javascript
onChangeClientState = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.script"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>script ()](#apidoc.element.react-helmet.Helmet.propTypes.script)
- description and source-code
```javascript
script = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.style"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>style ()](#apidoc.element.react-helmet.Helmet.propTypes.style)
- description and source-code
```javascript
style = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>title ()](#apidoc.element.react-helmet.Helmet.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.titleAttributes"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>titleAttributes ()](#apidoc.element.react-helmet.Helmet.propTypes.titleAttributes)
- description and source-code
```javascript
titleAttributes = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.propTypes.titleTemplate"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.propTypes.</span>titleTemplate ()](#apidoc.element.react-helmet.Helmet.propTypes.titleTemplate)
- description and source-code
```javascript
titleTemplate = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-helmet.Helmet.prototype"></a>[module react-helmet.Helmet.prototype](#apidoc.module.react-helmet.Helmet.prototype)

#### <a name="apidoc.element.react-helmet.Helmet.prototype.flattenArrayTypeChildren"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>flattenArrayTypeChildren (_ref)](#apidoc.element.react-helmet.Helmet.prototype.flattenArrayTypeChildren)
- description and source-code
```javascript
function flattenArrayTypeChildren(_ref) {
    var _extends2;

    var child = _ref.child,
        arrayTypeChildren = _ref.arrayTypeChildren,
        newChildProps = _ref.newChildProps,
        nestedChildren = _ref.nestedChildren;

    return _extends({}, arrayTypeChildren, (_extends2 = {}, _extends2[child.type] = [].concat(arrayTypeChildren[child.type] || [], [
_extends({}, newChildProps, this.mapNestedChildrenToProps(child, nestedChildren))]), _extends2));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.mapArrayTypeChildrenToProps"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapArrayTypeChildrenToProps (arrayTypeChildren, newProps)](#apidoc.element.react-helmet.Helmet.prototype.mapArrayTypeChildrenToProps)
- description and source-code
```javascript
function mapArrayTypeChildrenToProps(arrayTypeChildren, newProps) {
    var newFlattenedProps = _extends({}, newProps);

    Object.keys(arrayTypeChildren).forEach(function (arrayChildName) {
        var _extends5;

        newFlattenedProps = _extends({}, newFlattenedProps, (_extends5 = {}, _extends5[arrayChildName] = arrayTypeChildren[arrayChildName
], _extends5));
    });

    return newFlattenedProps;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.mapChildrenToProps"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapChildrenToProps (children, newProps)](#apidoc.element.react-helmet.Helmet.prototype.mapChildrenToProps)
- description and source-code
```javascript
function mapChildrenToProps(children, newProps) {
    var _this2 = this;

    var arrayTypeChildren = {};

    _react2.default.Children.forEach(children, function (child) {
        if (!child || !child.props) {
            return;
        }

        var _child$props = child.props,
            nestedChildren = _child$props.children,
            childProps = _objectWithoutProperties(_child$props, ["children"]);

        var newChildProps = (0, _HelmetUtils.convertReactPropstoHtmlAttributes)(childProps);

        _this2.warnOnInvalidChildren(child, nestedChildren);

        switch (child.type) {
            case _HelmetConstants.TAG_NAMES.LINK:
            case _HelmetConstants.TAG_NAMES.META:
            case _HelmetConstants.TAG_NAMES.NOSCRIPT:
            case _HelmetConstants.TAG_NAMES.SCRIPT:
            case _HelmetConstants.TAG_NAMES.STYLE:
                arrayTypeChildren = _this2.flattenArrayTypeChildren({
                    child: child,
                    arrayTypeChildren: arrayTypeChildren,
                    newChildProps: newChildProps,
                    nestedChildren: nestedChildren
                });
                break;

            default:
                newProps = _this2.mapObjectTypeChildren({
                    child: child,
                    newProps: newProps,
                    newChildProps: newChildProps,
                    nestedChildren: nestedChildren
                });
                break;
        }
    });

    newProps = this.mapArrayTypeChildrenToProps(arrayTypeChildren, newProps);
    return newProps;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.mapNestedChildrenToProps"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapNestedChildrenToProps (child, nestedChildren)](#apidoc.element.react-helmet.Helmet.prototype.mapNestedChildrenToProps)
- description and source-code
```javascript
function mapNestedChildrenToProps(child, nestedChildren) {
    if (!nestedChildren) {
        return null;
    }

    switch (child.type) {
        case _HelmetConstants.TAG_NAMES.SCRIPT:
        case _HelmetConstants.TAG_NAMES.NOSCRIPT:
            return {
                innerHTML: nestedChildren
            };

        case _HelmetConstants.TAG_NAMES.STYLE:
            return {
                cssText: nestedChildren
            };
    }

    throw new Error("<" + child.type + " /> elements are self-closing and can not contain children. Refer to our API for more information
.");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.mapObjectTypeChildren"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>mapObjectTypeChildren (_ref2)](#apidoc.element.react-helmet.Helmet.prototype.mapObjectTypeChildren)
- description and source-code
```javascript
function mapObjectTypeChildren(_ref2) {
    var _extends3, _extends4;

    var child = _ref2.child,
        newProps = _ref2.newProps,
        newChildProps = _ref2.newChildProps,
        nestedChildren = _ref2.nestedChildren;

    switch (child.type) {
        case _HelmetConstants.TAG_NAMES.TITLE:
            return _extends({}, newProps, (_extends3 = {}, _extends3[child.type] = nestedChildren, _extends3.titleAttributes = _extends
({}, newChildProps), _extends3));

        case _HelmetConstants.TAG_NAMES.BODY:
            return _extends({}, newProps, {
                bodyAttributes: _extends({}, newChildProps)
            });

        case _HelmetConstants.TAG_NAMES.HTML:
            return _extends({}, newProps, {
                htmlAttributes: _extends({}, newChildProps)
            });
    }

    return _extends({}, newProps, (_extends4 = {}, _extends4[child.type] = _extends({}, newChildProps), _extends4));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.render"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>render ()](#apidoc.element.react-helmet.Helmet.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        children = _props.children,
        props = _objectWithoutProperties(_props, ["children"]);

    var newProps = _extends({}, props);

    if (children) {
        newProps = this.mapChildrenToProps(children, newProps);
    }

    return _react2.default.createElement(Component, newProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.react-helmet.Helmet.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps) {
    return !(0, _deepEqual2.default)(this.props, nextProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.Helmet.prototype.warnOnInvalidChildren"></a>[function <span class="apidocSignatureSpan">react-helmet.Helmet.prototype.</span>warnOnInvalidChildren (child, nestedChildren)](#apidoc.element.react-helmet.Helmet.prototype.warnOnInvalidChildren)
- description and source-code
```javascript
function warnOnInvalidChildren(child, nestedChildren) {
    if (process.env.NODE_ENV !== "production") {
        if (!_HelmetConstants.VALID_TAG_NAMES.some(function (name) {
            return child.type === name;
        })) {
            if (typeof child.type === "function") {
                return (0, _HelmetUtils.warn)("You may be attempting to nest <Helmet> components within each other, which is not
 allowed. Refer to our API for more information.");
            }

            return (0, _HelmetUtils.warn)("Only elements types " + _HelmetConstants.VALID_TAG_NAMES.join(", ") + " are allowed.
Helmet does not support rendering <" + child.type + "> elements. Refer to our API for more information.");
        }

        if (nestedChildren && typeof nestedChildren !== "string") {
            throw new Error("Helmet expects a string as a child of <" + child.type + ">. Did you forget to wrap your children in
 braces? ( <" + child.type + ">{''}</" + child.type + "> ) Refer to our API for more information.");
        }
    }

    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-helmet.HelmetUtils"></a>[module react-helmet.HelmetUtils](#apidoc.module.react-helmet.HelmetUtils)

#### <a name="apidoc.element.react-helmet.HelmetUtils.convertReactPropstoHtmlAttributes"></a>[function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>convertReactPropstoHtmlAttributes (props)](#apidoc.element.react-helmet.HelmetUtils.convertReactPropstoHtmlAttributes)
- description and source-code
```javascript
function convertReactPropstoHtmlAttributes(props) {
    var initAttributes = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

    return Object.keys(props).reduce(function (obj, key) {
        obj[_HelmetConstants.HTML_TAG_MAP[key] || key] = props[key];
        return obj;
    }, initAttributes);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.HelmetUtils.handleClientStateChange"></a>[function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>handleClientStateChange (newState)](#apidoc.element.react-helmet.HelmetUtils.handleClientStateChange)
- description and source-code
```javascript
function handleClientStateChange(newState) {
    var baseTag = newState.baseTag,
        bodyAttributes = newState.bodyAttributes,
        htmlAttributes = newState.htmlAttributes,
        linkTags = newState.linkTags,
        metaTags = newState.metaTags,
        noscriptTags = newState.noscriptTags,
        onChangeClientState = newState.onChangeClientState,
        scriptTags = newState.scriptTags,
        styleTags = newState.styleTags,
        title = newState.title,
        titleAttributes = newState.titleAttributes;


    if (_helmetIdleCallback) {
        cancelIdleCallback(_helmetIdleCallback);
    }

    _helmetIdleCallback = requestIdleCallback(function () {
        updateAttributes(_HelmetConstants.TAG_NAMES.BODY, bodyAttributes);
        updateAttributes(_HelmetConstants.TAG_NAMES.HTML, htmlAttributes);

        updateTitle(title, titleAttributes);

        var tagUpdates = {
            baseTag: updateTags(_HelmetConstants.TAG_NAMES.BASE, baseTag),
            linkTags: updateTags(_HelmetConstants.TAG_NAMES.LINK, linkTags),
            metaTags: updateTags(_HelmetConstants.TAG_NAMES.META, metaTags),
            noscriptTags: updateTags(_HelmetConstants.TAG_NAMES.NOSCRIPT, noscriptTags),
            scriptTags: updateTags(_HelmetConstants.TAG_NAMES.SCRIPT, scriptTags),
            styleTags: updateTags(_HelmetConstants.TAG_NAMES.STYLE, styleTags)
        };

        var addedTags = {};
        var removedTags = {};

        Object.keys(tagUpdates).forEach(function (tagType) {
            var _tagUpdates$tagType = tagUpdates[tagType],
                newTags = _tagUpdates$tagType.newTags,
                oldTags = _tagUpdates$tagType.oldTags;


            if (newTags.length) {
                addedTags[tagType] = newTags;
            }
            if (oldTags.length) {
                removedTags[tagType] = tagUpdates[tagType].oldTags;
            }
        });

        _helmetIdleCallback = null;
        onChangeClientState(newState, addedTags, removedTags);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.HelmetUtils.mapStateOnServer"></a>[function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>mapStateOnServer (_ref)](#apidoc.element.react-helmet.HelmetUtils.mapStateOnServer)
- description and source-code
```javascript
function mapStateOnServer(_ref) {
    var baseTag = _ref.baseTag,
        bodyAttributes = _ref.bodyAttributes,
        encode = _ref.encode,
        htmlAttributes = _ref.htmlAttributes,
        linkTags = _ref.linkTags,
        metaTags = _ref.metaTags,
        noscriptTags = _ref.noscriptTags,
        scriptTags = _ref.scriptTags,
        styleTags = _ref.styleTags,
        _ref$title = _ref.title,
        title = _ref$title === undefined ? "" : _ref$title,
        titleAttributes = _ref.titleAttributes;
    return {
        base: getMethodsForTag(_HelmetConstants.TAG_NAMES.BASE, baseTag, encode),
        bodyAttributes: getMethodsForTag(_HelmetConstants.ATTRIBUTE_NAMES.BODY, bodyAttributes, encode),
        htmlAttributes: getMethodsForTag(_HelmetConstants.ATTRIBUTE_NAMES.HTML, htmlAttributes, encode),
        link: getMethodsForTag(_HelmetConstants.TAG_NAMES.LINK, linkTags, encode),
        meta: getMethodsForTag(_HelmetConstants.TAG_NAMES.META, metaTags, encode),
        noscript: getMethodsForTag(_HelmetConstants.TAG_NAMES.NOSCRIPT, noscriptTags, encode),
        script: getMethodsForTag(_HelmetConstants.TAG_NAMES.SCRIPT, scriptTags, encode),
        style: getMethodsForTag(_HelmetConstants.TAG_NAMES.STYLE, styleTags, encode),
        title: getMethodsForTag(_HelmetConstants.TAG_NAMES.TITLE, { title: title, titleAttributes: titleAttributes }, encode)
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.HelmetUtils.reducePropsToState"></a>[function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>reducePropsToState (propsList)](#apidoc.element.react-helmet.HelmetUtils.reducePropsToState)
- description and source-code
```javascript
function reducePropsToState(propsList) {
    return {
        baseTag: getBaseTagFromPropsList([_HelmetConstants.TAG_PROPERTIES.HREF], propsList),
        bodyAttributes: getAttributesFromPropsList(_HelmetConstants.ATTRIBUTE_NAMES.BODY, propsList),
        encode: getInnermostProperty(propsList, _HelmetConstants.HELMET_PROPS.ENCODE_SPECIAL_CHARACTERS),
        htmlAttributes: getAttributesFromPropsList(_HelmetConstants.ATTRIBUTE_NAMES.HTML, propsList),
        linkTags: getTagsFromPropsList(_HelmetConstants.TAG_NAMES.LINK, [_HelmetConstants.TAG_PROPERTIES.REL, _HelmetConstants.TAG_PROPERTIES
.HREF], propsList),
        metaTags: getTagsFromPropsList(_HelmetConstants.TAG_NAMES.META, [_HelmetConstants.TAG_PROPERTIES.NAME, _HelmetConstants.
TAG_PROPERTIES.CHARSET, _HelmetConstants.TAG_PROPERTIES.HTTPEQUIV, _HelmetConstants.TAG_PROPERTIES.PROPERTY, _HelmetConstants.TAG_PROPERTIES
.ITEM_PROP], propsList),
        noscriptTags: getTagsFromPropsList(_HelmetConstants.TAG_NAMES.NOSCRIPT, [_HelmetConstants.TAG_PROPERTIES.INNER_HTML], propsList
),
        onChangeClientState: getOnChangeClientState(propsList),
        scriptTags: getTagsFromPropsList(_HelmetConstants.TAG_NAMES.SCRIPT, [_HelmetConstants.TAG_PROPERTIES.SRC, _HelmetConstants
.TAG_PROPERTIES.INNER_HTML], propsList),
        styleTags: getTagsFromPropsList(_HelmetConstants.TAG_NAMES.STYLE, [_HelmetConstants.TAG_PROPERTIES.CSS_TEXT], propsList),
        title: getTitleFromPropsList(propsList),
        titleAttributes: getAttributesFromPropsList(_HelmetConstants.ATTRIBUTE_NAMES.TITLE, propsList)
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.HelmetUtils.requestIdleCallback"></a>[function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>requestIdleCallback (cb)](#apidoc.element.react-helmet.HelmetUtils.requestIdleCallback)
- description and source-code
```javascript
requestIdleCallback = function (cb) {
    var start = Date.now();
    return setTimeout(function () {
        cb({
            didTimeout: false,
            timeRemaining: function timeRemaining() {
                return Math.max(0, 50 - (Date.now() - start));
            }
        });
    }, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-helmet.HelmetUtils.warn"></a>[function <span class="apidocSignatureSpan">react-helmet.HelmetUtils.</span>warn (msg)](#apidoc.element.react-helmet.HelmetUtils.warn)
- description and source-code
```javascript
function warn(msg) {
    return console && typeof console.warn === "function" && console.warn(msg);
}
```
- example usage
```shell
...

return function (id) {
    return clearTimeout(id);
};
}();

var warn = function warn(msg) {
return console && typeof console.warn === "function" && console.warn(msg);
};

var _helmetIdleCallback = null;

var handleClientStateChange = function handleClientStateChange(newState) {
var baseTag = newState.baseTag,
    bodyAttributes = newState.bodyAttributes,
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
