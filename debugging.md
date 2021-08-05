##  Debugging 
* The JavaScript **interpreter** uses the concept of **execution contexts**. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

###### EXECUTION CONTEXT
Every statement in a script lives in one of three execution contexts:
1. **GLOBAL CONTEXT** Code that is in the script, but not in a function. There is only one global context in any page.
2. **FUNCTION CONTEXT** Code that is being run within a function.Each function has its own function context.
3. **EVAL CONTEXT (NOT SHOWN)** Text is executed like code in an internal function called eval()


###### VARIABLE SCOPE
 The first two execution contexts correspond with the notion of scope (which you met on p98):
1. **GLOBAL SCOPE** If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.
2. **FUNCTION-LEVEL SCOPE** When a variable is declared within a function,it can only be used within that function. This is because it has function-level scope.

###### EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE
     * The new scope is created
     * Variables, functions, and arguments are created
     * The value of the this keyword is determined
2. EXECUTE
     * Now it can assign values to variables
     * Reference functions and run their code
     * Execute statements
* Each execution context also creates its own variab1es object. This object contains details of all of the variables, functions, and parameters for that execution context.


###### ERROR OBJECTS
* Error objects can help you find where your mistakes are and browsers have tools to help you read them.

* error object contanin:

PROPERTY | DESCRIPTION
---------|------------
name  |Type of execution
message| Description
fileNumber | Name of the JavaScript file
lineNumber | Line number of error


* There are seven types of built-in error objects in JavaScript. You'll see them on the next two pages:



OBJECT | DESCRIPTION
-------|-----------
Error | Generic error - the other errors are all based upon this error
Syntax Error | Syntax has not been followed
ReferenceError| Tried to reference a variable that is not declared/within scope
TypeError | An unexpected data type that cannot be coerced
Range Error | Numbers not in acceptable range
URI Error |encodeURI ().decodeURI(),and similar methods used incorrectly
EvalError |eval () function used incorrectly
