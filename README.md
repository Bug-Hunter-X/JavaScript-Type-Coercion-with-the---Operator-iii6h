# JavaScript Type Coercion Bug
This repository demonstrates a common JavaScript bug related to type coercion using the '+' operator.

## Description
The `bug.js` file contains a function that attempts to add a number and a string. Due to JavaScript's dynamic typing and loose type coercion rules, the '+' operator concatenates the string and the number instead of performing mathematical addition.

## Solution
The `bugSolution.js` file provides a corrected version of the function using the Number() function for explicit type conversion, ensuring proper numerical addition.