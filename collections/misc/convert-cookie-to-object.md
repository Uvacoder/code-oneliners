---
title: Convert cookie to object
category: Misc
---

```js
const cookies = document.cookie
    .split(';')
    .map((item) => item.split('='))
    .reduce((acc, [k, v]) => (acc[k.trim().replace('"', '')] = v) && acc, {});
```
