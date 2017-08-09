* `if`

```js
function testSize(num) {
    if(num<5){
        return "Tiny";
    }
    else if(num<10){
        return "Small";
    } 
    else if(num<15){
        return"Medium";
    }
    else if(num<20){
        return"Large";
    }
    else
        return "Huge";
}
```

* `case` \(in switch-case statements\) values are tested with strict equality \(===\).

```js
function sequentialSizes(val) {
    var answer = "";
    switch(val){
        case 1:
        case 2:
        case 3:
            answer="Low";
        break;
        case 4:
        case 5:
        case 6:
            answer="Mid";
        break;
        case 7:
        case 8:
        case 9:
            answer="High";
        break; 
        default:
            answer="None";
    } 
    return answer; 
}
```

* Conditional \(ternary\) Operator

```js
var x = false;
var s == x ? "yes" : "no";
console.log(s);  //→ "no"
```



