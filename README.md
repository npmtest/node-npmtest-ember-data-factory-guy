# npmtest-ember-data-factory-guy

#### basic test coverage for  [ember-data-factory-guy (v2.12.3)](https://github.com/danielspaniel/ember-data-factory-guy)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-data-factory-guy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-data-factory-guy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-data-factory-guy.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-data-factory-guy)

#### Factories for testing Ember applications using EmberData

[![NPM](https://nodei.co/npm/ember-data-factory-guy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-data-factory-guy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-data-factory-guy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-data-factory-guy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-data-factory-guy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-data-factory-guy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-data-factory-guy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-data-factory-guy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-data-factory-guy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Sudol"
    },
    "bugs": {
        "url": "https://github.com/danielspaniel/ember-data-factory-guy/issues"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.1",
        "broccoli-merge-trees": "^1.1.1",
        "ember-cli-babel": "latest",
        "jquery-mockjax": "^2.2.1"
    },
    "description": "Factories for testing Ember applications using EmberData",
    "devDependencies": {
        "active-model-adapter": "2.1.1",
        "broccoli-asset-rev": "^2.1.2",
        "ember-cli": "^2.12.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-htmlbars": "1.1.1",
        "ember-cli-htmlbars-inline-precompile": "0.3.6",
        "ember-cli-qunit": "^3.1.2",
        "ember-cli-shims": "1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "1.1.1",
        "ember-cli-uglify": "1.2.0",
        "ember-data": "2.12",
        "ember-data-model-fragments": "~2.11.0",
        "ember-disable-prototype-extensions": "1.1.0",
        "ember-django-adapter": "1.1.3",
        "ember-load-initializers": "^0.6.3",
        "ember-resolver": "3.0.0",
        "ember-sinon": "0.6.0",
        "ember-source": "2.12",
        "loader.js": "4.2.3"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "19b3030a14566706eb7722508a02809f0617ffe8",
        "tarball": "https://registry.npmjs.org/ember-data-factory-guy/-/ember-data-factory-guy-2.12.3.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "7631c0a12a4562b66f6c4878def76c3670f9775a",
    "homepage": "https://github.com/danielspaniel/ember-data-factory-guy",
    "keywords": [
        "ember-addon",
        "testing",
        "factories",
        "ember-data"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "daniel.sudol"
        }
    ],
    "name": "ember-data-factory-guy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danielspaniel/ember-data-factory-guy.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember test"
    },
    "version": "2.12.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
