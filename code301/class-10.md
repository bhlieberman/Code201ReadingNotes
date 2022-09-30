# JavaScript call stack

1. A call is a function invocation, meaning the function is supplied with its inputs.
2. One, because of the structure of the call stack.
3. LIFO is an acronym standing for 'Last In, First Out'.
4. ``````
-------------
|___________|
|console.log
|___________|
|countNumbers
|___________|

function countNumbers(i) {
   for (let j = 0; j < i; j++) {
     console.log(j);
   }
}
``````
5. Stack overflow can occur when a function recurses infinitely. Most languages have a built-in recursion limit that when exceeded triggers a stack overflow error. This means that too many stack frames have been put on the stack and they are not being removed.

# JavaScript errors

1. A 'reference error' occurs when an undefined variable or object is named.
2. A 'syntax error' occurs when a delimiter or other expected token is not present in the required position.
3. A 'range error' is the product of indexing past the end of an array, also known as buffer overflow or overrun.
4. A 'type error' can be any sort of mismatch between a type and an operator or function.
5. A 'breakpoint' is a programmer-included stoppage in the execution of a program for debugging purposes.
6. It creates a breakpoint so that the programmer can see the call stack prior to the program reaching the statement.
