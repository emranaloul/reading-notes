# Error Handling and Debugging
## ORDER OF EXECUTION
* To find the source of an error, it helps to know how scripts are processed.

## EXECUTION CONTEXTS
* The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

### Every statement in a script lives in one of three execution contexts:
1. GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
2. EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eval {).
3. GLOBAL SCOPE
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.

# EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases
of activity:
1. PREPARE
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined
2. EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements
## Error Objects
* Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

**When an Error object is created, it will contain the
following properties:**
![objects](https://h.top4top.io/p_188150avp1.png)
**There are seven types of built-in error objects in
JavaScript:**

![objects2](https://j.top4top.io/p_1881hd7031.png)

### JavaScript Errors - Throw and Try to Catch

The **try** statement lets you test a block of code for errors.

The **catch** statement lets you handle the error.

The **throw** statement lets you create custom errors.

The **finally** statement lets you execute code, after try and catch, regardless of the result.

### JavaScript try and catch

The **try** statement allows you to define a block of code to be tested for errors while it is being executed.

The **catch** statement allows you to define a block of code to be executed, if an error occurs in the try block.

### JavaScript Throws Errors
When an error occurs, JavaScript will normally stop and generate an error message.

The technical term for this is: JavaScript will throw an exception (throw an error).

JavaScript will actually create an Error object with two properties: name and message.

### The throw Statement
The throw statement allows you to create a custom error.

Technically you can throw an exception (throw an error).