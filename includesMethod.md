## String.prototype.includes()
- [String.prototype.includes()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes)
```
My definition: The string.prototype.includes() method is a string method that takes 2 parameters 
    the first parameter is the string you would like to test against the original string. The second parameter takes a number, this number will determine the 
    position of the starting point within the test string, proportionally to the index value of the test string. This method will return a boolean value.
    Either true or false, and the method is case sensitive.

The includes() method determines whether one string may be found within another string,
returning true or false as appropriate.

examples: 
  var str = 'To be, or not to be, that is the question.';

  console.log(str.includes('question'));    // true
  console.log(str.includes('nonexistent')); // false
  console.log(str.includes('To be', 1));    // false
