**Array:**

1. index:
   1. `arr.indexOf(searchElement[, fromIndex])`
   2. `arr.lastIndexOf(searchElement, fromIndex)`
2. join:
   1. `oldArray.concat(otherArray)` being used to concatenate `otherArray` onto the end of `oldArray`
   2. `array.join(" and ")` to join all of the elements of an array into a string separated by whatever delimiter you provided.
3. `array.splice(start, deleteCount, item1, item2, ...)`
4. `.hasOwnProperty()` returns true or false if the property is found or not
5. append and remove array elements:
   1. `array.push()` append element to the end
   2. `array.unshift()` append element to the front
   3. `array.pop()` remove element off of the end
   4. `array.shift()` remove element off of the front
6. arguments：`Array.from(arguments)`  `Array.prototype.slice.call(arguments)` 

---

**String:**

1. index:
   1. `str.indexOf(searchValue[, fromIndex]`
   2. `str.lastIndexOf(searchValue[, fromIndex])`
2. cut:
   1. `str.substring(indexStart[, indexEnd])`  //one-based index
   2. `str.substr(start[, length])`  //one-based index
   3. `str.slice(beginIndex[,endIndex])`  //zero-based index, The character at `endIndex` will not be included.
3. `string.split("")` to split string into an array by specific string\(`string.split(' ')`\) or a regex\(`string.split(/\s+/g)`\)
4. `str.repeat(times)` :

```js
 str.repeat(0)//''  
 str.repeat(2)//str.str  
 str.repeat(-1)//error
```

---

* `isNaN()`

* `Number.isNaN()`  //very different

---



