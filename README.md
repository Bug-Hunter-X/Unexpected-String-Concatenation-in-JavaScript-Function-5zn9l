# Unexpected String Concatenation in JavaScript Function

This repository demonstrates a common yet subtle bug in JavaScript involving unexpected string concatenation when adding numbers.  The function `foo` is designed to add two numbers, but due to JavaScript's loose typing, it performs string concatenation if a string is provided as an argument.

## Bug Report

The function `foo` in `bug.js` unexpectedly concatenates strings instead of adding numbers when a string is passed as an argument. This can lead to unexpected results and make debugging more difficult.  The solution demonstrates how to avoid this using type checking or explicit type conversion.