# api documentation for  [rss (v1.2.2)](http://github.com/dylang/node-rss)  [![npm package](https://img.shields.io/npm/v/npmdoc-rss.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rss) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rss.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rss)
#### RSS feed generator. Add RSS feeds to any project. Supports enclosures and GeoRSS.

[![NPM](https://nodei.co/npm/rss.png?downloads=true)](https://www.npmjs.com/package/rss)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rss/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-rss_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rss/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dylan Greene",
        "email": "dylang@gmail.com"
    },
    "browserify": {
        "transform": [
            "folderify"
        ]
    },
    "bugs": {
        "url": "http://github.com/dylang/node-rss/issues"
    },
    "contributors": [
        {
            "name": "Dylan Greene",
            "email": "dylang@gmail.com"
        },
        {
            "name": "Xavier Damman",
            "email": "xdamman@gmail.com"
        },
        {
            "name": "Michael R. Lange"
        },
        {
            "name": "Victor Jonsson"
        },
        {
            "name": "Danny Graham"
        },
        {
            "name": "Patrick Garman",
            "email": "contact@pmgarman.me"
        },
        {
            "name": "Fred Morstatter"
        },
        {
            "name": "Eric Vantillard",
            "email": "eric.vantillard@evaxion.fr"
        },
        {
            "name": "Jason Karns",
            "email": "jasonkarns"
        },
        {
            "name": "Hannah Wolfe",
            "email": "github.erisds@gmail.com"
        }
    ],
    "dependencies": {
        "mime-types": "2.1.13",
        "xml": "1.0.1"
    },
    "description": "RSS feed generator. Add RSS feeds to any project. Supports enclosures and GeoRSS.",
    "devDependencies": {
        "folderify": "^1.1.0",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-release": "^0.13.0",
        "grunt-templates-dylang": "^1.0.10",
        "include-folder": "^1.0.0",
        "load-grunt-tasks": "^3.3.0",
        "mockdate": "^1.0.3",
        "prova": "^2.1.2",
        "q": "^1.4.1",
        "tap-difflet": "^0.4.0",
        "tape": "^4.2.1",
        "time-grunt": "^1.2.1",
        "xml2js": "^0.4.12"
    },
    "directories": {},
    "dist": {
        "shasum": "50a1698876138133a74f9a05d2bdc8db8d27a921",
        "tarball": "https://registry.npmjs.org/rss/-/rss-1.2.2.tgz"
    },
    "gitHead": "0c428434c9d415e285a23b84318ecdfd11f698d5",
    "homepage": "http://github.com/dylang/node-rss",
    "keywords": [
        "rss",
        "xml",
        "atom",
        "podcasts",
        "ghost",
        "feed",
        "feed builder",
        "rss feed"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "dylang",
            "email": "dylang@gmail.com"
        },
        {
            "name": "erisds",
            "email": "erisds@gmail.com"
        }
    ],
    "name": "rss",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/dylang/node-rss.git"
    },
    "scripts": {
        "lint": "grunt lint",
        "test": "tape test --tap | tap-difflet",
        "test:browser": "prova -b"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/9..latest",
            "chrome/latest",
            "firefox/latest",
            "safari/latest",
            "opera/latest",
            "iphone/latest",
            "ipad/latest",
            "android-browser/latest"
        ]
    },
    "version": "1.2.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module rss](#apidoc.module.rss)



# <a name="apidoc.module.rss"></a>[module rss](#apidoc.module.rss)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
