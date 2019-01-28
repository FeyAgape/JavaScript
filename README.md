# JavaScript Notes

### Logical operators

Logical operators can be used in conjunction with boolean values (true and false) to create complex logical expressions.
By combining two boolean values together with a logical operator, you create a logical expression that returns another boolean value. 
Here’s a description of the different logical operators:

1. &&  Logical AND value1 && value2  Returns true if both value1 and value2 evaluate to true.
2. ||  Logical OR  value1 || value2  Returns true if either value1 or value2 (or even both!) evaluates to true.
3. ! Logical NOT !value1 Returns the opposite of value1. If value1 is true, then !value1 is false.So adding it to the start of a value reverses it.


### Arrays

An array is useful because it stores multiple values into a single, organized data structure. You can define a new array by listing values separated with commas between square brackets [ ]

```
var donuts = ["glazed", "chocolate frosted", "cinnamon", "sprinkled"];
```

But strings aren’t the only type of data you can store in an array. You can also store numbers, booleans… and really anything!
You can create a **mixedData** array with mixed data types
```
var mixedData = ["abcd", 1, true, undefined, null, "all the things"];
```

You can even store an array in an array to create a nested array!

```
// creates a `arraysInArrays` array with three arrays
var arraysInArrays = [[1, 2, 3], ["Julia", "James"], [true, false, true, false]];
```

Nested arrays can be particularly hard to read, so it's common to write them on one line, using a newline after each comma:

```
var arraysInArrays = [
  [1, 2, 3], 
  ["Julia", "James"], 
  [true, false, true, false]
];
```
