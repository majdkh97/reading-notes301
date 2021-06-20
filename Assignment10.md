# Read10

## In Memory Storage

### JavaScript Call Stack
- What?... data structure that uses the Last In, First Out (LIFO; it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.) principle to temporarily store and manage function invocation (call).

- Why?... for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

- What causes a stak overflow?... A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

### Error Messages
- ‘refrence error’?.. when you try to use a variable that is not yet declared.

- ‘syntax error’?.. this occurs when you have something that cannot be parsed in terms of syntax.

- ‘range error’?.. ex. negative length of array.

- ‘tyep error’?.. when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

- In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

- You cab debug your code also using console.log();

[Go Back ](README.md)
