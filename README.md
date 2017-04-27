# npmtest-mssql

#### basic test coverage for  [mssql (v4.0.4)](https://github.com/patriksimek/node-mssql#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mssql.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mssql) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mssql.svg)](https://travis-ci.org/npmtest/node-npmtest-mssql)

#### Microsoft SQL Server client for Node.js.

[![NPM](https://nodei.co/npm/mssql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mssql)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mssql/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mssql/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mssql/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mssql/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mssql/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mssql/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mssql/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mssql/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mssql/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mssql/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mssql/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mssql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mssql/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mssql/build/test-report.html](https://npmtest.github.io/node-npmtest-mssql/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mssql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mssql/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mssql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mssql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mssql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mssql/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mssql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mssql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrik Simek",
        "url": "https://patriksimek.cz"
    },
    "bin": {
        "mssql": "./bin/mssql"
    },
    "bugs": {
        "url": "https://github.com/patriksimek/node-mssql/issues"
    },
    "dependencies": {
        "debug": "^2.6.3",
        "generic-pool": "^3.1.7",
        "tedious": "^2.0.0"
    },
    "description": "Microsoft SQL Server client for Node.js.",
    "devDependencies": {
        "mocha": "^2.1.0",
        "standard": "^9.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "416d67df7653536cb6384951891fa1a47572a49b",
        "tarball": "https://registry.npmjs.org/mssql/-/mssql-4.0.4.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "a16180bd4253656753093de08cb50a627808b6b2",
    "homepage": "https://github.com/patriksimek/node-mssql#readme",
    "keywords": [
        "database",
        "mssql",
        "sql",
        "server",
        "msnodesql",
        "sqlserver",
        "tds",
        "node-tds",
        "tedious",
        "node-sqlserver",
        "sqlserver",
        "msnodesqlv8",
        "azure",
        "node-mssql"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "patriksimek"
        }
    ],
    "name": "mssql",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/patriksimek/node-mssql.git"
    },
    "scripts": {
        "test": "standard && node_modules/.bin/mocha test/common/unit.js",
        "test-cli": "mocha test/common/cli.js",
        "test-msnodesqlv8": "mocha test/msnodesqlv8",
        "test-tedious": "mocha test/tedious"
    },
    "version": "4.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
