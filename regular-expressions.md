[**Regular expressions**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions) are used to find certain words or patterns inside of strings. example: `/\s+/gi`

* `/`  is the start of the regular expression.
* `the` is the pattern we want to match.
* `/` is the end of the regular expression.
* `g` means global, which causes the pattern to return all matches in the string, not just the first one.
* `i` means that we want to ignore the case \(uppercase or lowercase\) when searching for the pattern.
* `\d` is used to retrieve one digit \(e.g. numbers 0 to 9\) in a string.
* `+` after the selector, e.g. /\d+/g, allows this regular expression to **match one or more digits.**
* `\s` to find whitespace
* `\S` will match anything that\*\* isn't\*\* whitespace.\(with no '+'\)
* `\r`  the carriage return
* `\n`  newline\)
* `\t`  tab
* `\f`  the form feed\).



