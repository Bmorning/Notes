* #### In JavaScript all variables and function names are case sensitive.
* **Variable names** can be made up of numbers, letters, and`$`or`_`, but may not contain spaces or start with a number.

* When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be `NaN` which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".

* In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash \(\\) in front of the quote.                                                                                                                                            ![](/assets/无标题.jpg)

* 
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

---

object:[JSON](http://www.json.org/)

```js
var car {
  "wheels" : 4,
  "engines" : 1,
  "seats" : 5
};

console.log(car.wheels);
console.log(car["wheels"]);
```

constructor:

```js
var car = function(wheels,engines,seats,mirrors) {
    this.wheels = wheels;
    this.engines = engines;
    this.seats = seats;    //global
    var mirrors = mirrors; //private
};
```

---

Map

Reduce

Filter

Sort

[廖雪峰Js](https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000)

