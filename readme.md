# Eloquent Object Tools

A Lightweight Javascript Object Tooling System written in ES6+

### Installation

```sh
$ npm i eloquent-object-tools --save
```

### Initialization

```js
const Eot = require('eloquent-object-tools');
const eot = new(Eot);
```

  - eot.clone(object) -> Clones an object
  - eot.getDeep(object, path, default) -> Gets a deep value from an object, and returns a default if not found, path can be an array or string
  - eot.setDeep(object, path, value) -> Sets a deep value from an object, path can be an array or string