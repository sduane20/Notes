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
    - Plus sign with strings and numbers
    - Assignment Operators
    - Comparison and Ternary Operators
    - The effect of 'use strict'

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
