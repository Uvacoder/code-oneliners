---
title: Shallow copy an object
category: Object
---

```js
const shallowCopy = obj => Object.assign({}, obj);

// or
const shallowCopy = obj => {...obj};
```
