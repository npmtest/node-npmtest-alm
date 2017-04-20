# npmtest-alm

#### basic test coverage for  [alm (v2.35.1)](https://github.com/alm-tools/alm#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-alm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-alm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-alm.svg)](https://travis-ci.org/npmtest/node-npmtest-alm)

#### The best IDE for TypeScript

[![NPM](https://nodei.co/npm/alm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/alm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-alm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-alm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-alm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-alm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-alm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-alm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-alm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-alm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-alm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-alm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-alm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-alm/build/test-report.html](https://npmtest.github.io/node-npmtest-alm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-alm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-alm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-alm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-alm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-alm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-alm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-alm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-alm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "basaratali@gmail.com"
    },
    "bin": {
        "alm": "./bin/alm"
    },
    "bugs": {
        "url": "https://github.com/alm-tools/alm/issues"
    },
    "dependencies": {
        "basic-auth-connect": "^1.0.0",
        "byots": "2.3.0-dev.20170308.4.4",
        "chalk": "^1.1.3",
        "chokidar": "1.6.1",
        "cookie-parser": "^1.3.5",
        "deep-equal": "^1.0.1",
        "editorconfig": "^0.13.2",
        "escape-html": "^1.0.3",
        "express": "4.13.0",
        "fuzzaldrin": "^2.1.0",
        "glob": "^7.0.5",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "mocha": "3.1.1",
        "monaco": "1.201701230409.0",
        "monaco-css": "1.3.0",
        "monaco-languages": "0.7.0",
        "multimatch": "^2.1.0",
        "mv": "^2.1.1",
        "ncp": "^2.0.0",
        "node-fetch": "1.6.3",
        "open": "0.0.5",
        "ora": "^0.2.0",
        "resolve": "^1.2.0",
        "rimraf": "^2.4.2",
        "socket.io": "^1.3.6",
        "source-map-support": "0.4.3",
        "ts-loader": "2.0.0",
        "ts-node": "2.1.0",
        "tslint": "5.0.0-dev.0",
        "typescript": "2.3.0-dev.20170308",
        "update-notifier": "1.0.2",
        "webpack": "^1.11.0"
    },
    "description": "The best IDE for TypeScript",
    "devDependencies": {
        "@types/electron": "^1.4.31",
        "@types/node": "^7.0.4",
        "@types/socket.io": "^1.4.27",
        "@types/socket.io-client": "^1.4.29",
        "@types/webpack": "2.1.0",
        "clipboard": "^1.4.2",
        "css-loader": "^0.24.0",
        "d3": "^3.5.12",
        "file-loader": "^0.8.4",
        "font-awesome": "^4.4.0",
        "golden-layout": "1.5.7",
        "hint.css": "^2.0.0",
        "http-proxy": "^1.11.1",
        "jquery": "^2.1.4",
        "json-loader": "^0.5.4",
        "less": "^2.5.3",
        "less-loader": "^2.2.2",
        "marked": "^0.3.5",
        "mousetrap": "^1.5.3",
        "nodemon": "1.11.0",
        "normalize.css": "^5.0.0",
        "onresize": "^1.0.1",
        "react": "15.3.2",
        "react-dom": "15.3.2",
        "react-draggable": "2.2.2",
        "react-modal": "1.2.1",
        "react-redux": "4.4.5",
        "react-toggle": "2.1.1",
        "redux": "3.5.2",
        "style-loader": "^0.12.3",
        "toastr": "^2.1.2",
        "typestyle": "1.1.1",
        "url-loader": "^0.5.6",
        "viewerjs": "^0.4.0",
        "webpack-dev-server": "^1.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d03449ee3caa4dba0a644b8c0d775dce1e4b45d2",
        "tarball": "https://registry.npmjs.org/alm/-/alm-2.35.1.tgz"
    },
    "engines": {
        "node": ">=6.0.0",
        "npm": ">=3.0.0"
    },
    "gitHead": "547db92e44354f498bad7430e5e7335f101fb7b7",
    "greenkeeper": {
        "ignore": [
            "d3",
            "jquery",
            "react-modal",
            "monaco",
            "typescript"
        ]
    },
    "homepage": "https://github.com/alm-tools/alm#readme",
    "keywords": [
        "javascript",
        "typescript",
        "ide",
        "editor",
        "code"
    ],
    "license": "MIT",
    "main": "src/server.js",
    "maintainers": [
        {
            "name": "basarat"
        },
        {
            "name": "blakeembrey"
        },
        {
            "name": "jbrantly"
        },
        {
            "name": "nycdotnet"
        }
    ],
    "name": "alm",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alm-tools/alm.git"
    },
    "scripts": {
        "alm": "node ./node_modules/alm_src/server -o",
        "clean": "rm ./src/public/build/bundle.js",
        "mochaw": "mocha ./src/tests -w",
        "postversion": "git push --follow-tags",
        "prepublish": "bash ./scripts/prepublish.sh",
        "preversion": "npm run tsc",
        "resume": "bash ./scripts/resume.sh",
        "start": "nodemon src/server.js --debug",
        "test": "echo \"Testing is just build at the moment, run from prepublish\"",
        "tsc": "tsc -p ./src",
        "tscw": "tsc -p ./src -w",
        "ualm": "rm -rf ./node_modules/alm_src && cp -rf ./src ./node_modules/alm_src",
        "umonaco": "npm install monaco@latest monaco-css@latest monaco-languages@latest --save --save-exact && npm run tsc",
        "ureact": "npm install react@latest react-dom@latest --save-dev --save-exact",
        "utest": "npm install ts-node@latest mocha@latest --save --save-exact && npm run tsc",
        "uts": "npm install typescript@next tslint@next byots@latest --save --save-exact && npm run tsc"
    },
    "version": "2.35.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
