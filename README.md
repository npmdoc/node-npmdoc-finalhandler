# npmdoc-finalhandler

#### api documentation for  [finalhandler (v1.0.1)](https://github.com/pillarjs/finalhandler#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-finalhandler.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-finalhandler) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-finalhandler.svg)](https://travis-ci.org/npmdoc/node-npmdoc-finalhandler)

#### Node.js final http responder

[![NPM](https://nodei.co/npm/finalhandler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/finalhandler)

- [https://npmdoc.github.io/node-npmdoc-finalhandler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-finalhandler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-finalhandler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-finalhandler/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-finalhandler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-finalhandler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/finalhandler/issues"
    },
    "dependencies": {
        "debug": "2.6.3",
        "encodeurl": "~1.0.1",
        "escape-html": "~1.0.3",
        "on-finished": "~2.3.0",
        "parseurl": "~1.3.1",
        "statuses": "~1.3.1",
        "unpipe": "~1.0.0"
    },
    "description": "Node.js final http responder",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "readable-stream": "2.1.2",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bcd15d1689c0e5ed729b6f7f541a6df984117db8",
        "tarball": "https://registry.npmjs.org/finalhandler/-/finalhandler-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "7643136085e8c178902a93d6ef43ad42cd3936f1",
    "homepage": "https://github.com/pillarjs/finalhandler#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "finalhandler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/finalhandler.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
