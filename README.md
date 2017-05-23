# nedb-node

> NeDB for Node

**This is an experimental work in progress. Not ready for use.**

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
