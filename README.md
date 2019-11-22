# JSON Files Merger ✨

## Exammple

You wanna load all json files located in `/de` and merge the json data to a single json object.

For example, you have two json fils in folder `/de`

```
.example/de
├── 01_user.json
└── 02_home.json
```

```
// .example/demo.js
const jsonMerger = require("json-files-merger");

const targetFolder = "de";
const mergedJsonObject = jsonMerger.load(targetFolder);

console.log(mergedJsonObject);

```

# License

MIT © Xun Zhou
