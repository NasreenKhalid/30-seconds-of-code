---
title: uniqueElementsArary
tags: Array,beginner, filter method
---

Higher Order Method Javascript:

- Get all the unique elements of an array using array.filter method
- Use indexOf and lastIndexOf methods to do the comparison

```js
var arr = [-1, 2, 5, 6, 2, 9, -1, 6, 5, 6, -1, 3,33,55,74];
var result = arr.filter(e => arr.indexOf(e) === arr.lastIndexOf(e));
console.log(result);
//Output:[9, 3, 33, 55, 74] 
```

