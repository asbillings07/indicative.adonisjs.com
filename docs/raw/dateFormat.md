---
permalink: dateFormat
title: dateFormat
category: raw
gh_url: https://github.com/poppinss/indicative-rules/tree/develop/src/raw/dateFormat.ts
---

Returns a boolean telling if value is valid as per the given date format
or not.
 
```js
const { is } = require('indicative')
 
if (is.dateFormat('2010-11-20', ['YYYY-MM-DD'])) {
}
 
// You can also check against multiple format to see if it matches any one or not
if (is.dateFormat('2010-11-20', ['YYYY-MM-DD', 'YYYY/MM/DD'])) {
}
```