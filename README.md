# @kt3k/conditional-exports-example

Example of [conditional exports](https://nodejs.org/api/packages.html#packages_conditional_exports).

```js
import x from "@kt3k/conditional-exports-example";
console.log(x); // => "mjs"
```

```js
const x = require("@kt3k/conditional-exports-example");
console.log(x); // => "cjs"
```

# LICENSE

MIT
