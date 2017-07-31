**Array:**

1. index:
   1. `arr.indexOf(searchElement[, fromIndex])`
   2. `arr.lastIndexOf(searchElement, fromIndex)`
   3. `arr.findIndex(callback)` The findIndex\(\) method returns the index of the **first** element in the array that satisfies the provided testing function. Otherwise -1 is returned.
2. `arr.sort(function(a,b){return a-b;})` ATTENTION! this method sorts strings rather then numbers,19 ranks before 2.
3. join:
   1. `oldArray.concat(otherArray)` being used to concatenate `otherArray` onto the end of `oldArray`
   2. `array.join(" and ")` to join all of the elements of an array into a string separated by whatever delimiter you provided.
4. `array.splice(start, deleteCount, item1, item2, ...)`
5. `.hasOwnProperty()` returns true or false if the property is found or not
6. append and remove array elements:
   1. `array.push()` append element to the end
   2. `array.unshift()` append element to the front
   3. `array.pop()` remove element off of the end
   4. `array.shift()` remove element off of the front
7. arguments：`Array.from(arguments)`  `Array.prototype.slice.call(arguments)` 
8. `arr.inclues(searchElements)`
9. `arr.every(callback)`  The `every()` method tests whether all elements in the array pass the test implemented by the provided function.

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
4. str.repeat\(times\):
   1. `str.repeat(0)//''`
   2. `str.repeat(2)//str.str`
   3. `str.repeat(-1)//error`
5. `str.inclues(searchElements)`

---

* `isNaN()`

* `Number.isNaN()`  //very different

---



