# nedb-node

[![Build Status](https://travis-ci.org/bullish-ventures/nedb-node.png?branch=master)](https://travis-ci.org/bullish-ventures/nedb-node)
[![Code Climate](https://codeclimate.com/github/bullish-ventures/nedb-node/badges/gpa.svg)](https://codeclimate.com/github/bullish-ventures/nedb-node)
[![Test Coverage](https://codeclimate.com/github/bullish-ventures/nedb-node/badges/coverage.svg)](https://codeclimate.com/github/bullish-ventures/nedb-node/coverage)
[![Dependency Status](https://img.shields.io/david/bullish-ventures/nedb-node.svg?style=flat-square)](https://david-dm.org/bullish-ventures/nedb-node)
[![Download Status](https://img.shields.io/npm/dm/nedb-node.svg?style=flat-square)](https://www.npmjs.com/package/nedb-node)

> NeDB for Node

## Installation

```
npm install nedb-node --save
```

## Documentation

TODO

## Complete Example

```js
const Datastore = require('nedb-node');

const db = new Datastore('file://users.db');

db.find({}, function(error, users) {

});
```

## License

Copyright (c) 2016

Licensed under the [MIT license](LICENSE).
