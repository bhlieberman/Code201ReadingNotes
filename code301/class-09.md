# Functional programming

1. Functional programming is a programming style or paradigm. It uses functions to compose programs and encapsulate logic, as opposed to an object-oriented style that does this with classes and bound methods.
2. A pure function is one that has no side effects. This means it operates only on its inputs and returns these modified data as outputs. It does not touch any other part of the program's state and cannot perform IO.
3. Fewer unpredictable changes in program state, easier to reason about data that is being passed in and returned. Coupled with immutable data structures, it is difficult to cause some of the common pitfalls of OO languages, like aliasing variables, that cause bugs and logic errors.
4. Immutability is the property of a data structure that makes it unchangeable. Once a variable is declared and a value is assigned to it, that value cannot be changed. Any operations on the value will either fail or produce an entirely new data structure.
5. Referential transparency is the property of a function that it produces the same output given the same input, with no exceptions. This means that in some circumstances, the function invocation can be replaced by the data it is known to produce with no effect upon how the program works.

# Node

1. A module is a JavaScript file that exports definitions and variables to be used in other locations in the program.
2. `require` brings the exported definitions of one module into the scope of another.
3. Declare a variable (conventionally with the same name as the other module) and assign it the value of `require('foo')`, giving the correct location of the file using a relative path.
4. In order to export the contents of a module you must use the `module.exports` keyword and assign the definitions you want to export to it.
