# npmdoc-grunt-gh-pages

#### basic api documentation for  [grunt-gh-pages (v2.0.0)](https://github.com/tschaub/grunt-gh-pages)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-gh-pages.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-gh-pages) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-gh-pages.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-gh-pages)

#### Publish to GitHub Pages with Grunt.

[![NPM](https://nodei.co/npm/grunt-gh-pages.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-gh-pages)

- [https://npmdoc.github.io/node-npmdoc-grunt-gh-pages/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-gh-pages/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-gh-pages/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-gh-pages/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-gh-pages/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-gh-pages/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Schaub",
        "url": "http://tschaub.net/"
    },
    "bugs": {
        "url": "https://github.com/tschaub/grunt-gh-pages/issues"
    },
    "dependencies": {
        "async": "2.0.1",
        "fs-extra": "^0.30.0",
        "graceful-fs": "4.1.5",
        "q": "0.9.3",
        "q-io": "2.0.2",
        "url-safe": "^2.0.0"
    },
    "description": "Publish to GitHub Pages with Grunt.",
    "devDependencies": {
        "chai": "1.8.1",
        "eslint": "^3.2.2",
        "eslint-config-tschaub": "^5.0.0",
        "grunt": "0.4.2",
        "grunt-cafe-mocha": "0.1.10",
        "grunt-cli": "0.1.11",
        "grunt-contrib-watch": "0.5.3",
        "tmp": "0.0.20"
    },
    "directories": {},
    "dist": {
        "shasum": "c82f48d7b6f8491be42694f5c2c93b1308fa777b",
        "tarball": "https://registry.npmjs.org/grunt-gh-pages/-/grunt-gh-pages-2.0.0.tgz"
    },
    "eslintConfig": {
        "extends": "tschaub"
    },
    "gitHead": "cae3356611fccd73ac57ea566b357636e1a893a0",
    "homepage": "https://github.com/tschaub/grunt-gh-pages",
    "keywords": [
        "gruntplugin",
        "git",
        "grunt",
        "gh-pages",
        "github"
    ],
    "license": "MIT",
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "tschaub"
        }
    ],
    "name": "grunt-gh-pages",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/tschaub/grunt-gh-pages.git"
    },
    "scripts": {
        "pretest": "eslint lib tasks test Gruntfile.js",
        "test": "grunt test"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
