# TanderBolt

> TanderBolt is an open source project developed by the JavaScript community with the aim of exporting functions from Webpack modules

## Usage
```js
var TanderBolt = require('@tanderbolt/loader');

var loader = new TanderBolt();

// Get module by id
loader.get(moduleId);

// Get module by search function
loader.searchModule(m => m.default.MyFunctionTest);

// Get module ID by search function
loader.searchModuleId(m => m.default.MyFunctionTest);

// Return a promise with resolved módule
loader.waitForModule(m => m.default.MyFunctionTest);
```
