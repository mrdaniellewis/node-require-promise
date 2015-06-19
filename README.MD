# Promise polyfill wrapper

This is a wrapper around promise-polyfill.  It either returns the native Promise (in Node >= 0.12), or promise-polyfill (in Node <= 0.10).

It just makes it easier to add the require.

```js
var Promise = require('polyfill-promise');
```

If you did this with `promise-polyfill` you would always get the polyfill.