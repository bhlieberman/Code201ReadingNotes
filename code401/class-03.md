# Reading 3

## Differences between boxed and unboxed types

Java primitives like `int` and `boolean` are unboxed types. They are passed by value and are more efficient in memory usage than the boxed or reference types they correspond to, like `Integer` and `Boolean`. Boxed types can be created from primitives and vice versa.

## Java Exceptions

### What is it?
An exception is a runtime error that interrupts the program's execution. 

### Try or Specify Requirement
This is a contract of sorts upheld by Java code that may throw an exception. It means that properly written code should catch the exception with exception handling logic, or pass it along to a method with such a handler. Otherwise, it should _specify_ the exception using the `throws Exception` clause in the method declaration.

## Scanners
Java provides a `Scanner` class to read input and separate it by a specified token. This is whitespace by default. Scanners wrap various `Reader` objects like `BufferedReader` and `FileReader` that perform more granular or particular functionality on an input type.


## Things I want to know more about
1. How the JVM works under the hood, especially memory management and the garbage collector