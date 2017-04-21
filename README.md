# npmtest-maildev

#### basic test coverage for  [maildev (v0.14.0)](http://djfarrelly.github.io/MailDev/)  [![npm package](https://img.shields.io/npm/v/npmtest-maildev.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-maildev) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-maildev.svg)](https://travis-ci.org/npmtest/node-npmtest-maildev)

#### SMTP Server and Web Interface for reading and testing emails during development

[![NPM](https://nodei.co/npm/maildev.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/maildev)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-maildev/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-maildev/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-maildev/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-maildev/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-maildev/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-maildev/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-maildev/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-maildev/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-maildev/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-maildev/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-maildev/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-maildev/build/test-report.html](https://npmtest.github.io/node-npmtest-maildev/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-maildev/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-maildev/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-maildev/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-maildev/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-maildev/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-maildev/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-maildev/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-maildev/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "maildev",
    "description": "SMTP Server and Web Interface for reading and testing emails during development",
    "version": "0.14.0",
    "keywords": [
        "email",
        "e-mail",
        "mail",
        "mailcatcher"
    ],
    "author": "Dan Farrelly",
    "homepage": "http://djfarrelly.github.io/MailDev/",
    "maintainers": [
        {
            "name": "Dan Farrelly"
        }
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/djfarrelly/maildev.git"
    },
    "scripts": {
        "test": "./node_modules/.bin/istanbul cover _mocha"
    },
    "main": "./index.js",
    "bin": {
        "maildev": "./bin/maildev"
    },
    "license": "MIT",
    "dependencies": {
        "async": "1.5.1",
        "commander": "2.9.0",
        "express": "4.13.4",
        "mailparser": "0.5.3",
        "open": "0.0.5",
        "simplesmtp": "0.3.35",
        "smtp-connection": "2.3.1",
        "smtp-server": "1.4.0",
        "socket.io": "1.4.5",
        "wildstring": "1.0.8"
    },
    "devDependencies": {
        "grunt": "0.4.5",
        "grunt-concurrent": "2.2.1",
        "grunt-contrib-jshint": "1.0.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-nodemon": "0.4.1",
        "grunt-sass": "1.1.0",
        "http-proxy-middleware": "0.12.0",
        "istanbul": "0.4.4",
        "matchdep": "1.0.1",
        "mocha": "2.2.5",
        "nodemailer": "2.3.0",
        "request": "2.69.0"
    },
    "engines": {
        "node": ">=0.10.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
