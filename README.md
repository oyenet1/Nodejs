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

You can also export object like this

```js
const people = ["Bowofade", "Adeoluwa", "Babalola", "Ajanaku", "Akindele"];
const ages = [23, 56, 32, 16, 67];
module.exports = { people, ages };

// usage
const xyz = require("./peoples");
console.log(xyz.ages, xyz.people);

// You can also use destructring
const { people, ages } = require("./peoples");
```

Ypu can also use destructring
