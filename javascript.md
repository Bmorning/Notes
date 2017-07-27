* #### In JavaScript all variables and function names are case sensitive.
* **Variable names** can be made up of numbers, letters, and`$`or`_`, but may not contain spaces or start with a number.

* When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be `NaN` which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".

* In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash \(\\) in front of the quote.                                                                                                                                            ![](/assets/无标题.jpg)

* append element to the end: function.push\(\)

* append element to the front: function.unshift\(\)

* remove element off of the end: function.pop\(\)

* remove element off of the front: function.shift\(\)

---

| Convert type |  | Tests both type and value |  |
| :--- | :--- | :--- | :--- |
| == | 3 == '3' //true | === | 3 === '3' //false |
| != | 3 != '3' //false | !== | 3 !== '3' //true |

|  |  |
| :--- | :--- |
| \|\| | logical or |
| && | logicall and |

* `case` \(in switch-case statements\) values are tested with strict equality \(===\).

![](/assets/switch-case.png)

properties:[JSON](http://www.json.org/)

* myDog.name

* myDog\["name"\]

* ![](/assets/properties.png)

`.hasOwnProperty()` returns true or false if the property is found or not.

---

`Regular expressions`  are used to find certain words or patterns inside of strings.

* `/` is the start of the regular expression.
* `the` is the pattern we want to match.
* `/` is the end of the regular expression.
* `g` means global, which causes the pattern to return all matches in the string, not just the first one.
* `i` means that we want to ignore the case \(uppercase or lowercase\) when searching for the pattern.
* `\d`  is used to retrieve one digit \(e.g. numbers 0 to 9\) in a string.
* `+` after the selector, e.g. /\d+/g, allows this regular expression to **match one or more digits.**
* `\s` to find whitespace in a string.
* `\r` \(the carriage return
* `\n` \(newline\)
* `\t` \(tab
* `\f` \(the form feed\).



