* #### In JavaScript all variables and function names are case sensitive.
* **Variable names** can be made up of numbers, letters, and`$`or`_`, but may not contain spaces or start with a number.

* When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be `NaN` which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".

* In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash \(\\) in front of the quote.                                                                                                                                            ![](/assets/无标题.jpg)

* append element to the end: function.push\(\)

* append element to the front: function.unshift\(\)

* remove element off of the end: function.pop\(\)

* remove element off of the front: function.shift\(\)

---

* In order for JavaScript to compare two different data types \(for example, numbers and strings\), it must convert one type to another. Once it does, however, it can compare terms as follows:

```
   1   ==  1    // true
   1   ==  2    // false
   1   == '1'   // true
  "3"  ==  3    // true
```

* Strict equality \(===\) is the counterpart to the equality operator \(==\). Unlike the equality operator, strict equality tests both the data type and value of the compared elements.

```
3 === 3   // true
3 === '3' // false
```



