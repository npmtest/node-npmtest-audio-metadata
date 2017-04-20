# npmtest-audio-metadata

#### basic test coverage for  [audio-metadata (v0.3.0)](https://github.com/tmont/audio-metadata)  [![npm package](https://img.shields.io/npm/v/npmtest-audio-metadata.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-audio-metadata) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-audio-metadata.svg)](https://travis-ci.org/npmtest/node-npmtest-audio-metadata)

#### Extract metadata from audio files

[![NPM](https://nodei.co/npm/audio-metadata.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/audio-metadata)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-audio-metadata/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-audio-metadata/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-audio-metadata/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-audio-metadata/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-audio-metadata/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-audio-metadata/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-audio-metadata/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-audio-metadata/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-audio-metadata/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-audio-metadata/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-audio-metadata/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-audio-metadata/build/test-report.html](https://npmtest.github.io/node-npmtest-audio-metadata/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-audio-metadata/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-audio-metadata/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-audio-metadata/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-audio-metadata/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-audio-metadata/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-audio-metadata/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-audio-metadata/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-audio-metadata/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Montgomery",
        "url": "http://tmont.com/"
    },
    "bin": {
        "audio-metadata": "bin/audio-metadata.js"
    },
    "bugs": {
        "url": "https://github.com/tmont/audio-metadata/issues"
    },
    "dependencies": {},
    "description": "Extract metadata from audio files",
    "devDependencies": {
        "browserify": "3.19.1",
        "mocha": "1.16.2",
        "serve": "1.3.0",
        "should": "2.1.1",
        "uglify-js": "2.4.8"
    },
    "directories": {},
    "dist": {
        "shasum": "7d554031f0c244ee296231a1a55e00ff788d6ceb",
        "tarball": "https://registry.npmjs.org/audio-metadata/-/audio-metadata-0.3.0.tgz"
    },
    "files": [
        "index.js",
        "audio-metadata.min.js",
        "src",
        "bin",
        "README.md"
    ],
    "homepage": "https://github.com/tmont/audio-metadata",
    "keywords": [
        "id3",
        "metadata",
        "mp3",
        "ogg",
        "wav",
        "audio"
    ],
    "license": "WTFPL",
    "maintainers": [
        {
            "name": "tmont"
        }
    ],
    "name": "audio-metadata",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tmont/audio-metadata.git"
    },
    "scripts": {
        "build": "./node_modules/.bin/browserify -s AudioMetadata -e index.js --bare > audio-metadata.js",
        "minify": "npm run build && ./node_modules/.bin/uglifyjs audio-metadata.js > audio-metadata.min.js && rm audio-metadata.js",
        "start": "./node_modules/.bin/serve -p 24578 .",
        "test": "./node_modules/.bin/mocha -R spec tests"
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
