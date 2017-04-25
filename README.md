# npmtest-react-motion

#### basic test coverage for  [react-motion (v0.4.8)](https://github.com/chenglou/react-motion#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-motion.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-motion) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-motion.svg)](https://travis-ci.org/npmtest/node-npmtest-react-motion)

#### A spring that solves your animation problems.

[![NPM](https://nodei.co/npm/react-motion.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-motion)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-motion/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-motion/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-motion/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-motion/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-motion/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-motion/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-motion/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-motion/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-motion/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-motion/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-motion/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-motion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-motion/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-motion/build/test-report.html](https://npmtest.github.io/node-npmtest-react-motion/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-motion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-motion/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-motion/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-motion/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-motion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-motion/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-motion/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-motion/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "chenglou"
    },
    "bugs": {
        "url": "https://github.com/chenglou/react-motion/issues"
    },
    "contributors": [
        {
            "name": "Adrian le Bas"
        },
        {
            "name": "Amadeus Junqueira"
        },
        {
            "name": "Benjamin San Souci"
        },
        {
            "name": "Bishop Zareh"
        },
        {
            "name": "Brenton Simpson"
        },
        {
            "name": "Cesar Andreu"
        },
        {
            "name": "Cheng Lou"
        },
        {
            "name": "Dan Abramov"
        },
        {
            "name": "Daniel Dunderfelt"
        },
        {
            "name": "Dustan Kasten"
        },
        {
            "name": "Frederick Fogerty"
        },
        {
            "name": "Gaëtan Renaudeau"
        },
        {
            "name": "Google, Inc."
        },
        {
            "name": "Henry Zhu"
        },
        {
            "name": "Ivan Starkov"
        },
        {
            "name": "Jeroen van Aert"
        },
        {
            "name": "Jesper Petersson"
        },
        {
            "name": "Jevgeni Geimanen"
        },
        {
            "name": "Joe Lencioni"
        },
        {
            "name": "John Amiah Ford"
        },
        {
            "name": "Jon Lebensold"
        },
        {
            "name": "Justin Morris"
        },
        {
            "name": "Kyle Mathews"
        },
        {
            "name": "Ludovico Fischer"
        },
        {
            "name": "Michael J Hoffman"
        },
        {
            "name": "Mirko Mariani"
        },
        {
            "name": "Neil Kistner"
        },
        {
            "name": "Nik Butenko"
        },
        {
            "name": "Nikhil Baradwaj"
        },
        {
            "name": "Olivier Tassinari"
        },
        {
            "name": "Paolo Moretti"
        },
        {
            "name": "Raymond Zhou"
        },
        {
            "name": "Robert Haritonov"
        },
        {
            "name": "Sorin Iclanzan"
        },
        {
            "name": "Stefan Dombrowski"
        },
        {
            "name": "Stephen J. Collings"
        },
        {
            "name": "Sundeep Malladi"
        },
        {
            "name": "Sunil Pai"
        },
        {
            "name": "Travis Arnold"
        },
        {
            "name": "Wilfred Denton"
        }
    ],
    "dependencies": {
        "create-react-class": "^15.5.2",
        "performance-now": "^0.2.0",
        "prop-types": "^15.5.8",
        "raf": "^3.1.0"
    },
    "description": "A spring that solves your animation problems.",
    "devDependencies": {
        "babel": "^5.8.23",
        "babel-browser-transform": "^0.1.0",
        "babel-core": "^5.6.18",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^5.3.1",
        "codemirror": "^5.5.0",
        "css-loader": "^0.19.0",
        "eslint": "^3.5.0",
        "eslint-config-airbnb": "^11.1.0",
        "eslint-loader": "^1.1.0",
        "eslint-plugin-import": "^1.15.0",
        "eslint-plugin-jsx-a11y": "^2.2.2",
        "eslint-plugin-react": "^6.3.0",
        "flow-bin": "^0.32.0",
        "flow-copy-source": "^1.1.0",
        "inject-loader": "^2.0.1",
        "isparta-loader": "^0.2.0",
        "jasmine-core": "^2.3.4",
        "karma": "^0.13.10",
        "karma-coverage": "^0.5.2",
        "karma-jasmine": "^0.3.6",
        "karma-jasmine-diff-reporter": "^0.3.2",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-webpack": "^1.7.0",
        "lodash.range": "^3.0.1",
        "phantomjs": "^1.9.17",
        "react": ">=15.0.1",
        "react-addons-test-utils": "^15.0.1",
        "react-codemirror": ">=0.1.2",
        "react-dom": ">=15.0.1",
        "react-hot-loader": "^1.2.8",
        "style-loader": "^0.12.4",
        "webpack": "^1.10.1",
        "webpack-dev-server": "^1.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "23bb2dd27c2d8e00d229e45572d105efcf40a35e",
        "tarball": "https://registry.npmjs.org/react-motion/-/react-motion-0.4.8.tgz"
    },
    "gitHead": "b4859146a19adba5d3fbc8bc7020aa1ca2073c22",
    "homepage": "https://github.com/chenglou/react-motion#readme",
    "keywords": [
        "react",
        "component",
        "react-component",
        "transitiongroup",
        "spring",
        "tween",
        "motion",
        "animation",
        "transition",
        "ui"
    ],
    "license": "MIT",
    "main": "lib/react-motion.js",
    "maintainers": [
        {
            "name": "chenglou"
        },
        {
            "name": "nkbt"
        }
    ],
    "name": "react-motion",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.13.2 || ^0.14 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/chenglou/react-motion.git"
    },
    "scripts": {
        "build-demos": "webpack",
        "flow_check": "flow check",
        "gh-pages": "git fetch origin && git checkout gh-pages && git reset --hard origin/gh-pages && git rebase origin/master --force-rebase && npm run build-demos && git add . && git commit --amend --no-edit && git push origin gh-pages --force && git checkout master",
        "lint": "eslint --ext .js,.jsx .",
        "prepublish": "rm -rf lib && babel src --out-dir lib && flow-copy-source -v src lib && webpack --config webpack.prod.config.js",
        "start": "node server.js",
        "test": "karma start ./karma.conf.js --single-run",
        "test:cov": "karma start ./karma.conf.js --single-run --reporters coverage",
        "test:dev": "karma start ./karma.conf.js --no-single-run --auto-watch",
        "test:travis": "karma start ./karma.conf.js --single-run"
    },
    "version": "0.4.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
