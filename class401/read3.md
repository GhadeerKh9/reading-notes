## Java Primitives versus Objects

Java has a two-fold type system consisting of primitives such as int, boolean and reference types such as Integer, Boolean. Every primitive type corresponds to a reference type.

Every object contains a single value of the corresponding primitive type. The wrapper classes are immutable (so that their state can't change once the object is constructed) and are final (so that we can't inherit from them).

Single Item Memory Footprint
boolean – 1 bit
byte – 8 bits
short, char – 16 bits
int, float – 32 bits
long, double – 64 bits

## Exception

An exception is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions.

## The Catch or Specify Requirement

Valid Java programming language code must honor the Catch or Specify Requirement. This means that code that might throw certain exceptions must be enclosed by either of the following:
A try statement that catches the exception. The try must provide a handler for the exception, as described in Catching and Handling Exceptions.

A method that specifies that it can throw the exception. The method must provide a throws clause that lists the exception, as described in Specifying the Exceptions Thrown by a Method.

## Scanning

Objects of type Scanner are useful for breaking down formatted input into tokens and translating individual tokens according to their data type.
By default, a scanner uses white space to separate tokens. (White space characters include blanks, tabs, and line terminators.
