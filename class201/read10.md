# **Debugging in Java Script**
Debugging is the process of finding errors. It involves a process of deduction.

JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.

**ORDER OF EXECUTION**

To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

**EXECUTION CONTEXTS**

The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

**The STACK**

The JavaScript interpreter processes one line of code at a time. What a statement needs data from another function, it stacks (or piles) the new function on top of the current task.

Understanding Errors
If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

HOW TO DEAL WITH ERRORS

1: DEBUG THE SCRIPT TO FIX ERRORS
2: HANDLE ERRORS GRACEFULLY
