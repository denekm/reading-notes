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
