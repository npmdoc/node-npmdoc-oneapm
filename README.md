# npmdoc-oneapm

#### basic api documentation for  [oneapm (v2.0.0)](http://oneapm.com/features/nodejs.html)  [![npm package](https://img.shields.io/npm/v/npmdoc-oneapm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-oneapm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-oneapm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-oneapm)

#### OneAPM agent

[![NPM](https://nodei.co/npm/oneapm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/oneapm)

- [https://npmdoc.github.io/node-npmdoc-oneapm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-oneapm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oneapm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oneapm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-oneapm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-oneapm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "OneAPM Node.js agent team"
    },
    "dependencies": {
        "bunyan": "0.14.6",
        "continuation-local-storage": "^3.1.0",
        "debug": "^2.1.3",
        "is-docker": "^1.0.0",
        "oneapm-config": "^1.0.0",
        "oneapm-logger": "^2.0.0",
        "oneapm-server": "^1.0.0",
        "oneapm-util": "^1.0.0",
        "pidusage-fork": "^0.1.1",
        "semver": "^4.3.6"
    },
    "description": "OneAPM agent",
    "devDependencies": {},
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "1d4cd522d8f3e675c4d5a95daac62026bdeafb9a",
        "tarball": "https://registry.npmjs.org/oneapm/-/oneapm-2.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "api.js",
        "CHANGELOG.md",
        "index.js",
        "lib/",
        "locales.js",
        "oneapm.js",
        "README.md",
        "stub_api.js"
    ],
    "gitHead": "f74a8c42be8930800281d7465f7dd228fbca3511",
    "homepage": "http://oneapm.com/features/nodejs.html",
    "keywords": [
        "apm",
        "performance",
        "monitoring",
        "instrumentation",
        "debugging",
        "profiling"
    ],
    "maintainers": [
        {
            "name": "oneapm.com"
        },
        {
            "name": "wyvernnot"
        }
    ],
    "name": "oneapm",
    "optionalDependencies": {},
    "scripts": {
        "plato": "plato -r -d dist/plato lib/**/*.js lib/*.js index.js oneapm.js",
        "tarball": "./bin/tarball.sh",
        "test": "mocha --no-deprecation",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report cobertura -- --reporter xunit --reporter-options output=coverage/junit.xml test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha --report html -- --check-leaks test/"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
