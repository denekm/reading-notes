# Read: 10 JavaScript book, Ch. 10, “Error Handling & Debugging”

## Order Of Execution

- Some tasks will not execute until another function has ran.

## Execution Contexts

1. Global Context
2. Function Context
3. Eval Context

## The Stack

- JavaScript interpreter reads one line at a time
- If a statement needs data that is in another function then it stacks the function on top of the current task it is on.

## Execution Context & Hoisting

- When a script enters an execution context two phases of activity occur

1. Prepare (new scope is created)
2. Execute (statments are executed)

## What does error objects do?

- Error Objects can help us find where our errors are
- Examples of error objects
`uncaught SyntaxError: Unexpected token ILLEGAL , errors.js:13`
`URIError`
`NaN`- Not an error

## How can we deal with errors

1. In order to fix errors we can debug the script
2. Use try, catch, throw statments

## A Debugging Workflow

1. Where is the problem: look through the error message, look to see how far it is running, and figure out where things are going by using breakpoints
2. What exactly is the problem

## Browser DEV Tools & JavaScript Console

- In Safari

1.Go to **Develop** menu on the top left side of the page
2. Click **Show Error Console**

## Grouping Messages

`console.group()`
