# npmdoc-feedparser

#### basic api documentation for  [feedparser (v2.2.0)](http://github.com/danmactough/node-feedparser)  [![npm package](https://img.shields.io/npm/v/npmdoc-feedparser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-feedparser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-feedparser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-feedparser)

#### Robust RSS Atom and RDF feed parsing using sax js

[![NPM](https://nodei.co/npm/feedparser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/feedparser)

- [https://npmdoc.github.io/node-npmdoc-feedparser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-feedparser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-feedparser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-feedparser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-feedparser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-feedparser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan MacTough"
    },
    "bin": {
        "feedparser": "./bin/feedparser.js"
    },
    "bugs": {
        "url": "http://github.com/danmactough/node-feedparser/issues"
    },
    "dependencies": {
        "addressparser": "^1.0.1",
        "array-indexofobject": "~0.0.1",
        "lodash.assign": "^4.2.0",
        "lodash.get": "^4.4.2",
        "lodash.has": "^4.5.2",
        "lodash.uniq": "^4.5.0",
        "readable-stream": "^2.2.2",
        "sax": "^1.2.1"
    },
    "description": "Robust RSS Atom and RDF feed parsing using sax js",
    "devDependencies": {
        "eslint": "^3.17.1",
        "iconv": "2.2.2",
        "mocha": "^3.2.0",
        "request": "~2.81.0"
    },
    "directories": {},
    "dist": {
        "shasum": "90279e46af711649a2135307085c9377865adcf3",
        "tarball": "https://registry.npmjs.org/feedparser/-/feedparser-2.2.0.tgz"
    },
    "engines": {
        "node": ">= 4.2.0"
    },
    "gitHead": "8e731028274870a1120f4d99e62bb624fbe684b7",
    "homepage": "http://github.com/danmactough/node-feedparser",
    "keywords": [
        "rss",
        "feed",
        "atom",
        "rdf",
        "xml",
        "syndication",
        "rsscloud",
        "pubsubhubbub"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "danmactough"
        }
    ],
    "name": "feedparser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/danmactough/node-feedparser.git"
    },
    "scripts": {
        "lint": "eslint .",
        "pretest": "npm run lint",
        "test": "mocha",
        "version": "git changelog ; git add History.md"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
