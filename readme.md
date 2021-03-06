# domain.js

get the domain from an url

## installation

for [component](https://github.com/component/component):

    $ component install ramitos/domain.js

for [node.js](http://nodejs.org/):

    $ npm install domain.js

## usage

with string url:

```js
var domain = require('domain.js')

domain('http://www.example.co.uk') //=> example.co.uk
```

with parsed url:

```js
var domain = require('domain.js'),
    url = require('url')

domain(url.parse('http://www.example.co.uk')) //=> example.co.uk
```

## test [![Build Status](https://secure.travis-ci.org/ramitos/domain.js.png)](http://travis-ci.org/ramitos/domain.js)

    $ npm test

## credits

 * inspired by [URI.js](https://github.com/medialize/URI.js/)

## license

MIT