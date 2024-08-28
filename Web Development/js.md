# Javascript 7 Syntax and Operators

## All about the switch statement

    - Switch Statement
        - Use instead of multiple if..else statements
    - Case Statement
        - compare to expression in switch(exp)
    - Break Statement
        - exit out of each case
    - Default Statement
        - is used if there is no match
    - Switch does a strict comparison
        - Type and value must match
    - Each case statement is not a block
        - Must make statements a block by wrapping in braces
        - By wrapping a block of code in braces, any variable declared within that block is only visible within the block, and is released once the block ends.

## The Difference between for/in and for/of

    - For/In
        - Iterates over elements of a object (properties and methods)
        - Returns key (property / method) name
        - object[key] returns value
        - Any object in JavaScript can use the dot notation or an index to retrieve a value.
            - Ex: product.productId or product["productId"]
    - For/Of
        - Iterates over values in array, string, etc.
        - Returns object for each iteration
        - The 'of' keyword keeps track of which item in the array is currently being accessed
    - Break/Continue
        - Break: Leave a loop early
            - When used in a loop, the break statement goes to the line after the closing brace of the loop
            - Skips to the end of the code block
        - Continue: Next iteration of a loop
            - The continue statement goes back to the loop, and increments the internal variable keeping track of which item is the current one
            - Returns to the top of the loop and ignores the code below
    - Labeled Statements
        - Define a location to "goto"
        - Not recommended for use
        - A lable is any name you want and is followed by a colon
        - When you put a label, it does not return to the top of the loop but to the label and then drops in to the loop

## Using Math and Comparison

    - Mathematical Operators
        - Addition: (+)
        - Subtraction: (-)
        - Multiplication: (*)
        - Division: (/)
        - Exponentiation: (**)
        - Modulus: (%)
        - Increment: (++)
        - Decrement: (--)
    - Plus sign with strings and numbers
        - Plus sign is overloaded
        - When using with strings = concatentation
        - when using with number = addition
        - What happens if one is a number and one is a string?
            - If one is a string = concatenation
        - 'result = price + (+stringValue);
            - The plus sign immediately prior toa  string variable converts that string to a numeric data type if possible
    - Assignment Operators
        - Equal: (=) - assigns one value to another.
            - Ex: price = 10;
        - Addition: (+=)
            - Ex: price += 10;
        - Subtraction: (-=)
            - Ex: price -= 10;
        - Multiplication: (*=)
            - Ex: price *= 2;
        - Division: (/=)
            - Ex: price /= 2;
        - Exponentiation: (**=)
            - Ex: price **= 2;
        - Modulus: (%=)
            - Ex: price %= 3;
    - Comparison and Ternary Operators
        - Comparisons
            - Less Than: (<)
                - Ex: price < 10;
            - Less than or equal to: (<=)
                - Ex: price <= 10;
            - Greater Than: (>=)
                - Ex: price > 10;
            - Greater than or equal to: (>=)
                - Ex: price >= 10;
            - Equal in value: (==)
                - Ex: price == "10"; //true
            - Equal in value and type: (===)
                - Ex: price === 10; //false
            - Not equal in value: (!=)
                - Ex: price != "10"; //false
            - Not equal in value and type: (!==)
                - Ex: price !== "10"; //true
    - The effect of 'use strict'
        - Ignored by older browsers
        - Force all variables to be declared
        - Mistyped variable names are created globally scoped if not using `use strict;`
        - Can't use reserved words as variables
            - Ex: `let eval = 10;`
            - Ex:`let arguments = "some args";`
        - Can't delete a variable
            - Ex: `delete result;`
        - Can't delete a function
            - Ex: `delete functionName;`
        - If not using `use strict` then all of the above will work

## Working With Logical Operators and Short-circuit Evaluation

    - Truthy and Falsy
    - Logical Operators
    - Short Circuiting
    - Operator Precedence

## Utilizing Javascript Exception Handling

    - Try, Catch, and Finally blocks
    - Throw a custom error object
    - Detect the error type

## How to Determine Javascript Variable Data Types

    - Data types and detection methods
    - The typeof operator
    - Using the constructor property to determine type
    - Helper functions for the constructor property
    - the instanceof operator

## Understanding 'this' in Javascript

    - Introduction to 'this'
    - 'this' in global and function scope
    - 'this' in event handlers
    - 'this' in an object literal
    - 'this' with cal() and apply() methods
    - 'this' in constructor functions

## Using the Powerful Spread Operator

    - Copy a string to an array using spread
    - Copy an array of primitives using spread
    - Copy an array of objects
    - Concatenate two arrays together
    - Using spread to pass parameters to a constructor
    - Pass parameters to a function
    - Shallow copy on object literals
