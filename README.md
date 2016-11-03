find-by-regex
==================

[![Build Status](https://travis-ci.org/ymkjp/find-by-regex.svg?branch=master)](https://travis-ci.org/ymkjp/find-by-regex)

This is a chrome extension to search the text of any page using regular expressions.
Pull requests are welcome, just base your changes on the dev branch instead of master, as master is only updated on every release and is often behind the dev branch.

#### Necessary build tools
- NodeJS: [http://nodejs.org/](http://nodejs.org/)

#### Build guide
1. Clone this repo and execute ```npm install``` inside the created directory,
2. Run ```npm run build``` in order to build the extension (```build/``` is the output directory).

#### License
* Forked from https://github.com/gsingh93/regex-search/tree/v1.8
* [MIT](https://github.com/ymkjp/find-by-regex/blob/master/LICENSE.txt)


#### Publish Chrome Extension

0. Run `npm run release` to minify files
0. Compress a `lib` directory to zip
0. Upload zip file on https://chrome.google.com/webstore/developer/edit/lmeeghblnndbojbcdahjgoakgclnpfcl
