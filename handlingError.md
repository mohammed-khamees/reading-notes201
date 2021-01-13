# Debugging

If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error
in your code. **Debugging** is the process of finding errors. It involves a process of deduction.
The `console` helps narrow down the area in which the error is located, so you can try to find the exact error.
JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number
and gives a description of the error. If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.

The `try` statement lets you test a block of code for errors.

The `catch` statement lets you handle the error.

The `throw` statement lets you create custom errors.

The `finally` statement lets you execute code, after try and catch, regardless of the result.

`try {`
`Block of code to try`
`}`
`catch(err) {`
`Block of code to handle errors`
`}`

Six different values can be returned by the error name property:

| Error Name     | Description                                  |
| -------------- | -------------------------------------------- |
| EvalError      | An error has occurred in the eval() function |
| RangeError     | A number "out of range" has occurred         |
| ReferenceError | An illegal reference has occurred            |
| SyntaxError    | A syntax error has occurred                  |
| TypeError      | TypeError A type error has occurred          |
| URIError       | An error in encodeURI() has occurred         |
