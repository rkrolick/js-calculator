### Javascript Calculator

Your task is to create a Javascript object that represents a calculator. It should have methods that provide it with the following functionality...
* Addition
* Subtraction
* Multiplication
* Division
* Exponents

You should be able to run these methods like so from your browser's Javascript console...
```js
calculator.add(1,2);
// => 3
```

### Bonus

Give your calculator memory and allow it to persist the result of multiple operations.
* Store this result in a `value` property.
* Example: running `calculator.add(1,2)`, `calculator.add(2,2)` and `calculator.mutliply(2,2)` in sequence would result in a `value` of 10.
* Give your calculator a `clear` method that resets `value`.
