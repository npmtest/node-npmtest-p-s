# npmtest-p-s

#### basic test coverage for  [p-s (v4.1.0)](https://github.com/kentcdodds/nps#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-p-s.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-p-s) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-p-s.svg)](https://travis-ci.org/npmtest/node-npmtest-p-s)

#### All the benefits of npm scripts without the cost of a bloated package.json and limits of json

[![NPM](https://nodei.co/npm/p-s.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/p-s)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-p-s/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-p-s/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-p-s/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-p-s/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-p-s/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-p-s/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-p-s/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-p-s/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-p-s/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-p-s/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-p-s/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-p-s/build/test-report.html](https://npmtest.github.io/node-npmtest-p-s/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-p-s/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-p-s/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-p-s/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-p-s/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-p-s/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-p-s/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-p-s/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-p-s/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kent C. Dodds",
        "url": "http://kentcdodds.com/"
    },
    "bin": {
        "nps": "./dist/bin/nps.js"
    },
    "bugs": {
        "url": "https://github.com/kentcdodds/nps/issues"
    },
    "config": {
        "commitizen": {
            "path": "node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "arrify": "^1.0.1",
        "chalk": "^1.1.3",
        "common-tags": "^1.4.0",
        "find-up": "^2.1.0",
        "js-yaml": "^3.7.0",
        "lodash": "^4.17.4",
        "manage-path": "^2.0.0",
        "prefix-matches": "^0.0.9",
        "prettier-eslint-cli": "^1.1.1",
        "readline-sync": "^1.4.6",
        "spawn-command-with-kill": "^1.0.0",
        "type-detect": "^4.0.0",
        "yargs": "^6.6.0"
    },
    "deprecated": "this has been renamed to nps. Uninstall p-s and install nps instead",
    "description": "All the benefits of npm scripts without the cost of a bloated package.json and limits of json",
    "devDependencies": {
        "all-contributors-cli": "^3.1.0",
        "babel-cli": "^6.22.2",
        "babel-eslint": "^7.1.1",
        "babel-jest": "^18.0.0",
        "babel-plugin-module-resolver": "^2.5.0",
        "babel-preset-env": "^1.1.8",
        "babel-preset-stage-2": "^6.22.0",
        "babel-register": "^6.22.0",
        "cli-tester": "^2.0.0",
        "codecov": "^1.0.1",
        "commitizen": "^2.9.5",
        "concurrently": "^3.3.0",
        "cross-env": "^3.1.4",
        "cz-conventional-changelog": "^1.2.0",
        "eslint": "^3.15.0",
        "eslint-config-kentcdodds": "^11.1.0",
        "husky": "^0.13.1",
        "jest-cli": "^18.1.0",
        "lint-staged": "^3.3.0",
        "nps": "*",
        "opt-cli": "^1.5.1",
        "rimraf": "^2.5.4",
        "semantic-release": "^6.3.6",
        "sinon": "^1.17.7",
        "validate-commit-msg": "^2.11.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5d81bcecfb47d5aa5c6b8d3a0e11d243ad1e79ca",
        "tarball": "https://registry.npmjs.org/p-s/-/p-s-4.1.0.tgz"
    },
    "eslintConfig": {
        "extends": [
            "kentcdodds",
            "kentcdodds/jest"
        ],
        "rules": {
            "max-len": [
                "error",
                80
            ]
        }
    },
    "files": [
        "dist"
    ],
    "gitHead": "d221a78e9a4847b26ea55e6ca0aba8038a67711b",
    "homepage": "https://github.com/kentcdodds/nps#readme",
    "keywords": [],
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "prettier-eslint --write --ignore \"**/fixtures/**\"",
            "git add"
        ]
    },
    "main": "dist/index",
    "maintainers": [
        {
            "name": "kentcdodds"
        }
    ],
    "name": "p-s",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kentcdodds/nps.git"
    },
    "scripts": {
        "commitmsg": "opt --in commit-msg --exec \"validate-commit-msg\"",
        "localstart": "npm start build && node ./dist/bin/nps.js",
        "precommit": "opt --in pre-commit --exec \"npm start validate\"",
        "start": "nps",
        "test": "nps test"
    },
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
