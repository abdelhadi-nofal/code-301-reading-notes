# Call stack:

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

Temporarily store: When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

Manage function invocation (call): The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.

How does the call stack handle function calls?
function firstFunction(){
console.log(“Hello from firstFunction”); *}

function secondFunction(){
firstFunction();
console.log(“The end from secondFunction”);
}

secondFunction();
This is what happens when the code is run:
When secondFunction() gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.
secondFunction() then calls firstFunction()which is pushed into the stack.
firstFunction() returns and prints “Hello from firstFunction” to the console.
firstFunction() is pop off the stack.
The execution order then move to secondFunction().
secondFunction() returns and print “The end from secondFunction” to the console.
secondFunction() is pop off the stack, clearing the memory.
