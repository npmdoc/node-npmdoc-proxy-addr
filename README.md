# api documentation for  [proxy-addr (v1.1.4)](https://github.com/jshttp/proxy-addr#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-proxy-addr.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-proxy-addr) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-proxy-addr.svg)](https://travis-ci.org/npmdoc/node-npmdoc-proxy-addr)
#### Determine address of proxied request

[![NPM](https://nodei.co/npm/proxy-addr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/proxy-addr)

- [https://npmdoc.github.io/node-npmdoc-proxy-addr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-proxy-addr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-proxy-addr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-proxy-addr/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-proxy-addr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-proxy-addr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson"
    },
    "bugs": {
        "url": "https://github.com/jshttp/proxy-addr/issues"
    },
    "dependencies": {
        "forwarded": "~0.1.0",
        "ipaddr.js": "1.3.0"
    },
    "description": "Determine address of proxied request",
    "devDependencies": {
        "beautify-benchmark": "0.2.4",
        "benchmark": "2.1.3",
        "istanbul": "0.4.5",
        "mocha": "~1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "27e545f6960a44a627d9b44467e35c1b6b4ce2f3",
        "tarball": "https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.4.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "4c636264c036d9825e8a3cf50555a272e3246fe6",
    "homepage": "https://github.com/jshttp/proxy-addr#readme",
    "keywords": [
        "ip",
        "proxy",
        "x-forwarded-for"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "proxy-addr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/proxy-addr.git"
    },
    "scripts": {
        "bench": "node benchmark/index.js",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
