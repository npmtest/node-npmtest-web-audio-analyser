# npmtest-web-audio-analyser

#### basic test coverage for  web-audio-analyser (v2.0.1)  [![npm package](https://img.shields.io/npm/v/npmtest-web-audio-analyser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-web-audio-analyser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-web-audio-analyser.svg)](https://travis-ci.org/npmtest/node-npmtest-web-audio-analyser)

#### A thin wrapper around the Web Audio API that lets you take some audio and get its waveform/frequency data in return.

[![NPM](https://nodei.co/npm/web-audio-analyser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web-audio-analyser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-web-audio-analyser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-web-audio-analyser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-web-audio-analyser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-web-audio-analyser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-web-audio-analyser/build/test-report.html](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web-audio-analyser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-web-audio-analyser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "web-audio-analyser",
    "version": "2.0.1",
    "description": "A thin wrapper around the Web Audio API that lets you take some audio and get its waveform/frequency data in return.",
    "main": "index.js",
    "scripts": {
        "test": "npm start",
        "start": "beefy demo.js:bundle.js --live -- -t brfs",
        "prepublish": "browserify -t brfs demo.js > bundle.js"
    },
    "author": "Hugh Kennedy <hughskennedy@gmail.com> (http://hughskennedy.com/)",
    "license": "MIT",
    "devDependencies": {
        "beefy": "^2.1.5",
        "brfs": "~0.0.8",
        "game-shell-orbit-camera": "0.0.0",
        "gl-buffer": "~0.1.1",
        "gl-matrix": "~2.0.0",
        "gl-now": "0.0.4",
        "gl-shader": "0.0.6",
        "gl-vao": "0.0.2",
        "soundcloud-badge": "0.0.0"
    },
    "dependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/web-audio-analyser.git"
    },
    "keywords": [
        "audio",
        "web",
        "api",
        "browserify",
        "analysis",
        "fft",
        "waveform",
        "reactive"
    ],
    "bugs": {
        "url": "https://github.com/hughsk/web-audio-analyser/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
