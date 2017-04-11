# test coverage for  [natural (v0.5.0)](https://github.com/NaturalNode/natural)  [![npm package](https://img.shields.io/npm/v/npmtest-natural.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-natural) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-natural.svg)](https://travis-ci.org/npmtest/node-npmtest-natural)
#### General natural language (tokenizing, stemming (English, Russian, Spanish), classification, inflection, phonetics, tfidf, WordNet, jaro-winkler, Levenshtein distance, Dice's Coefficient) facilities for node.

[![NPM](https://nodei.co/npm/natural.png?downloads=true)](https://www.npmjs.com/package/natural)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-natural/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-natural/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-natural/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-natural/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-natural/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-natural/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-natural/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-natural/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-natural/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-natural/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-natural%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-natural/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-natural/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-natural%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-natural/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-natural/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-natural/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chris Umbel",
        "email": "chris@chrisumbel.com"
    },
    "bugs": {
        "url": "https://github.com/NaturalNode/natural/issues"
    },
    "dependencies": {
        "apparatus": ">= 0.0.9",
        "sylvester": ">= 0.0.12",
        "underscore": ">=1.3.1"
    },
    "description": "General natural language (tokenizing, stemming (English, Russian, Spanish), classification, inflection, phonetics, tfidf, WordNet, jaro-winkler, Levenshtein distance, Dice's Coefficient) facilities for node.",
    "devDependencies": {
        "jasmine-node": "~1.13.1",
        "uubench": "0.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "55a9bb68eccf5ece5535486004a57de264ae3180",
        "tarball": "https://registry.npmjs.org/natural/-/natural-0.5.0.tgz"
    },
    "engines": {
        "node": ">=0.4.10"
    },
    "gitHead": "378ec2b1511b8103ac483eb1a3a73ae6c335da3a",
    "homepage": "https://github.com/NaturalNode/natural",
    "keywords": [
        "natural",
        "language",
        "porter",
        "lancaster",
        "stemmer",
        "bayes",
        "classifier",
        "phonetic",
        "metaphone",
        "inflector",
        "wordnet",
        "tf-idf",
        "logistic",
        "regression",
        "doublemetaphone",
        "double",
        "jaro-winkler",
        "levenshtein",
        "distance",
        "tagger"
    ],
    "license": "MIT",
    "main": "./lib/natural/index.js",
    "maintainers": [
        {
            "name": "chrisumbel",
            "email": "chris@chrisumbel.com"
        },
        {
            "name": "kkoch986",
            "email": "kkoch986@gmail.com"
        }
    ],
    "name": "natural",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/NaturalNode/natural.git"
    },
    "scripts": {
        "test": "NODE_PATH=. node_modules/jasmine-node/bin/jasmine-node spec/"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
