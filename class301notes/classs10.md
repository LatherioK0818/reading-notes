# Understanding the JavaScript Call Stack

## Call Stack

- **What is a 'call'?**
  A 'call' refers to the invocation of a function in JavaScript.

- **How many 'calls' can happen at once?**
  JavaScript is single-threaded, so only one call can happen at a time due to the single call stack.

- **What does LIFO mean?**
  LIFO stands for Last In, First Out. It means that the last function added to the call stack is the first to be executed.

- **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**
main()	main()
functionA()	functionA()
functionB()	functionB()
functionC()	functionC()

- **What causes a Stack Overflow?**
A stack overflow occurs when the call stack exceeds its maximum size. This often happens due to infinite or very deep recursion.

## JavaScript Error Messages

- **What is a 'reference error'?**
A 'reference error' occurs when trying to use a variable that is not declared or is out of scope.

- **What is a 'syntax error'?**
A 'syntax error' occurs when there is a mistake in the structure of the code, violating the language's syntax rules.

- **What is a 'range error'?**
A 'range error' occurs when a value is not within the acceptable range, such as indexing an array with an out-of-bounds value.

- **What is a 'type error'?**
A 'type error' occurs when a value is not of the expected type, for example, trying to perform an operation on a non-compatible data type.

- **What is a breakpoint?**
A breakpoint is a point in the code where execution will pause, allowing developers to inspect variables and step through code for debugging purposes.

- **What does the word 'debugger' do in your code?**
The 'debugger' statement in code activates the debugging tool. It pauses code execution at that point, allowing developers to inspect variables, step through code, and identify issues.
