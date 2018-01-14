# three-collada-loader-2
The three.js collada loader introduced in r88, [taken from the three.js repository](https://github.com/mrdoob/three.js/blob/dev/examples/js/loaders/ColladaLoader.js).

## Usage

```
const ColladaLoader = require('three-collada-loader-2');

const colladaLoader = new ColladaLoader();
colladaLoader.load('example-path/example.dae', colladaModel => {
  ...
});
```


