# JS Debugging
- helps to know how scripts are processed to find the source of the error
- execution contexts are used by JS interpreter
- JS interpreter processes one line of code at a time
- stack - when a statement needs data from another function
- two phases of activity each time a script enters a new execution
- 1. prepare
- 2. execute
- each execution context, it has its own variable object
- holds the variable, functions, and parameters available within it
- when JS statement has an error, throws an exception 
- error objects can help find where the mistakes are made
- how to deal with errors
- 1. debug the script to fix errors
- 2. handle errors gracefully
- debugging is about deduction 
- console helps narrrow down the area to find the error
- JS has 7 different types of errors
- each creates its own error objects
- can tell you the line number and gives description of error
- `try`, `catch`, `finally` statements are used to give helpful feedbacks
