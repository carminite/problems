Methods are used to alter the value of a data type (e.g. change the characters in a String) based on the parameters (the variable values) they are given. They take those parameters, process them, and either return a result or change the data structure it is associated with; they are basically input-output machines.
In Java, only methods can be characterized by a set of parentheses () at the end which can contain values or stay empty. Methods can also be "stringed" together, where a variable which has a method attached to it (like `variable1.concat(variable2)`) can have another method pieced at the end to further process it (like `variable1.concat(variable2).length()`), creating a chain of methods.
Your job is to find, given a string `S`, the number of methods that have been "stringed" together.

### Input Specification
The input will consist of one line `S`, `5 ≤ |S| ≤ 500`. There may be spaces in the line.
It is guaranteed that all of the line is made of only "stringed" methods.

### Output Specification
The output will consist of one line consisting of one integer, the number of methods that make up `S`.

### Sample Input
```
nextInt().concat("COVID-19 is a real epidemic").length()
```

### Sample Output
```
3
```

### Sample I/O Explanation
There are three "methods" to this line: `nextInt()`, `concat("COVID-19 is a real epidemic")`, and `length()`, hence the `3`.
