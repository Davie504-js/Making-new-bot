# **Making new __discord bot__**

# **Basically:**
1.1/ ghadi tmchi l Google w ghadi da5al 'node.js' ila knti deja md5lo bla md5lo.
1.2/ ghadi t3ml new folder f desktop smih li bghiti
1.3/ ghadi t3ml new file f dik l folder w smih 'bot.js'
1.4/ ghadi tfta7 'powershell' or 'cmd window'
1.5/ mli ghadi tfta7 powershell ghadi tktb 'npm init -y'
# **Coding:**
1.1/ mhm mli ghadi tm3l dik etaps li fl fo9 ghadi tfat7 file dyl 'bot.js'
1.2/ mli ghadi tfta7 bot.js ghadi t7ot fih source code hada howa :




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
