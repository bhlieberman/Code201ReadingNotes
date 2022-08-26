# Reading 10

## Troubleshooting JavaScript

### Difference between syntax and logic errors

Syntax errors can be succinctly described in non-technical terms as 
"spelling" errors. These occur if a bracket or semicolon is not included, or a keyword or function name is spelled incorrectly.

Logic errors happen when the program is parsed successfully by the JavaScript engine but the way the programmer has written the program gives results that are unexpected or incorrect.

### Some errors I've had

I frequently encounter `Type Error: cannot read properties of undefined` when writing JavaScript. Usually this means I'm trying to call a function or method on a type for which it is not available. When I get this error, I usually refer to the variable or name the stack trace points to and try to determine why the type it is giving me is not the one I expect. The type annotations provided by VSCode are usually helpful when going through this process.

JavaScript's dynamic typing can be both a blessing and a curse. As I advance in this course, I will try to be more deliberate about writing code, but in terms of day-to-day work, I hope that the usage of frameworks and other tools like TypeScript will help me code more effectively by providing better error messages and more static guarantees of program correctness.

## The JavaScript debugger

### What is it?

A debugger is a tool either on a command line or with a graphical user interface (GUI) that helps programmers incrementally walk through their program and determine where an error or errors is stopping the program from executing effectively. It allows the programmer to inspect variables and objects to see if their values at certain points are what they are expected to be or something different.

### Breakpoints

A breakpoint can be set in a debugger. This suspends the execution of a program at the point which it is set.

### The call stack

The call stack is the fundamental order of execution of a program. When a program begins, the various functions and other global variables that are declared are put on the call stack, and as the function bodies execute, they are popped off the stack. Each function has its own stack frame, which contains all the locals declared in the function's body. The call stack works in a so-called Last In, First Out (LIFO) order. 
