# anonymous-function-name-in-export-default

```js
// anonymousFunction.js
export default function () {}

// <script type="module">
import anonymousFunction from "./anonymousFunction.js";

console.log(anonymousFunction.name); // "default"
```

[Demo](https://pirosikick.github.io/anonymous-function-name-in-export-default/index.html)
