# Read09

## Functional Programming
- Is a programming paradigm a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## Pure functions
- Does not use global obj unless it was passed as a parameter.
- Does not read external files.
- Does not rely on a random number generator Math.random() .
- Does not cause any observable side effects.

**Why pure functions -> Code is easier to test.**

**Immutability -> When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.**

**Referential transparency -> Always have the same output, given the same input. pure functions + immutable data = referential transparency .**

## Modules and require();
- Module is a js file with a certain functionality in the application, called whenever needed by assigning require('module's path') to a variable(calling using the variable) and must be available to use by exporting the module module.exports .

[Go Back ](README.md)