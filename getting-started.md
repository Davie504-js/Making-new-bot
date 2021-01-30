# **Making new __discord bot__**

# **1:**
1.1/ ghadi tmchi l Google w ghadi da5al 'node.js'
# 1/ ghadi t3ml new folder f desktop smih li bghiti




```js
npm i mongoose
```

- mn ba3d ghadi trequiri `mongoose` flfile dyalk

```js
const mongoose = require("mongoose");
```
- db ghadi ntconnectaw ldatabase bmongoose

```js
mongoose.connect("mongodb://localhost:port/database_name", { // andiro localhost ka example
// flcodedya;l ghadi tbdl "localhost:port/database_name" blink dyal database lighadi tkhdm biha
    useNewUrlParser: true,
    useUnifiedTopology: true,
    useFindAndModify: true
});
```

db nta installiti mongoose, otconnectiti ldatabase!

[Next Page](schemas.md)
