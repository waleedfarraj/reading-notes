# Read: 10 - JS Debugging

No one is above or immune to making mistakes and in coding just like life you will
make mistakes that **YOU** need to fix, this chapter will talk about debugging in js 
as the name suggests.

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run,the 
order is not always as the layout suggests .

## EXECUTION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.   

Every statement in a script lives in one of three
execution contexts:
Q GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
Q EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eval. 

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code. 

## Errors

![Errors](/images/errors.PNG)

Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors. 

1. DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it. 
1.  HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements. 

#### A DEBUGGING WORKFLOW 
WHERE IS THE PROBLEM?
First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.
1. Look at the error message, it tells you:
• The relevant script that caused the problem.
• The line number where it became a problem for
the interpreter. (As you will see, the cause of
the error may be earlier in a script; but this is the
point at which the script could not continue.)
• The type of error (although the underlying cause
of the error may be different).
1. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.
1. Use breakpoints where things are going wrong.
They let you pause execution and inspect the values
that are stored in variables.


WHAT EXACTLY IS THE PROBLEM?
Once you think that you might know the rough area
in which your problem is located, you can then try to
find the actual line of code that is causing the error.
- When you have set breakpoints, you can see if the
variables around them have the values you would
expect them to. If not, look earlier in the script.
- Break down I break out parts of the code to test
smaller pieces of the functionality.
  - Write values of variables into the console.
  - Calrfunctions from the console to check if they
are returning what you would expect them to.
  - Check if objects exist and have the methods I
properties that you think they do.
- Check the number of parameters for a function, or
the number of items in an array.
And be prepared to repeat the whole process if the
above solved one error just to uncover another ... 
