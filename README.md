# test coverage for  [mssql (v4.0.1)](https://github.com/patriksimek/node-mssql#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mssql.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mssql) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mssql.svg)](https://travis-ci.org/npmtest/node-npmtest-mssql)
#### Microsoft SQL Server client for Node.js.

[![NPM](https://nodei.co/npm/mssql.png?downloads=true)](https://www.npmjs.com/package/mssql)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mssql/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mssql/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mssql/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mssql/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mssql/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mssql/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mssql/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mssql/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-mssql/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-mssql/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-mssql%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mssql/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mssql/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mssql%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mssql/build/apidoc.html)

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
        "shasum": "5ac0028245f99a6bc8bd8dcd117c34244eba9f5b",
        "tarball": "https://registry.npmjs.org/mssql/-/mssql-4.0.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "e36e30aba611866b2095f8f7f1405911f9d273ca",
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
            "name": "patriksimek",
            "email": "patrik@patriksimek.cz"
        }
    ],
    "name": "mssql",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "4.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
