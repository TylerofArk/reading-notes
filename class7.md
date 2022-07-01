# Programming with JavaScript

## Control Flow

The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

## Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

function name(parameter1, parameter2, parameter3) {
    code to be executed
}

Why Functions?

You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

This helps with keeping code DRY also.
(Don't Repeat Yourself!)

## Math Operators

Operator | Description

+          Addition

-          Subtraction

*          Multiplication
**         Exponentiation (ES2016)
/          Division
%          Modulus (Division Remainder)
++         Increment

## Assignment Operators

Operator  Example  Same as

=         x = y     x = y
+=        x += y    x = x + y
-=        x -= y    x = x - y
*=        x *= y    x = x * y
/=        x /= y    x = x / y
%=        x %= y    x = x % y
**=       x **= y   x = x ** y