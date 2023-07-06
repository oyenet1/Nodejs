# Nodejs Tutorial

## Modules

`To use modules, it must be exported eg`

```js
const people = ["Bowofade", "Adeoluwa", "Babalola", "Ajanaku", "Akindele"];
module.exports = people;

// usage
const xyz = require("./peoples");
console.log(xyz);
```

Let use it in another place
