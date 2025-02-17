# TypeScript Type Error: Adding Number and String

This repository demonstrates a common type error in TypeScript: attempting to add a number and a string. TypeScript's type system is designed to prevent such errors, but sometimes the error messages aren't always immediately clear.  This example shows the error and how to fix it.

## Bug
The `add` function is explicitly typed to accept two numbers and return a number. However, in the code, we attempt to call it with a string as the second argument.  This results in a type error.

## Solution
The solution involves ensuring the input to the `add` function is the correct type. This can be done through type guards, input validation, or by changing the function signature to handle strings.