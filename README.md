# Jaaziel Raighne M. Pagulayan
## 2ECE-C
## 08/27/2026

### I. Intended Learning Outcomes At the end of this laboratory activity, the student should be able to:

use basic Python functions, operators, and string operations;
manipulate strings using indexing, slicing, and built-in string methods;
apply sequence unpacking to manipulate the elements of a list; and
construct simple Python functions that return a specified result.

### A. WORD ROTATION PROBLEM

Create a function named rotate word() that accepts a non-empty string. Move the first character of the string to the end while keeping all remaining characters in their original order. Preserve the capitalization of every character. Function format: rotate word(text)

`Explanation`:

* text[1:] uses string slicing to extract all characters from index 1 (the second letter) through the very end of the string.

* text[0] accesses the very first character of the string.

* The + operator concatenates (joins) these two parts back together, placing the original first character at the end while preserving capitalization and character order.




