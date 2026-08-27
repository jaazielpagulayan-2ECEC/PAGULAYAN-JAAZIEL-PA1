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

B. USER BUILDER PROBLEM

Create a function named make username() that accepts two strings: first name and last name. The function must:

convert all letters to lowercase;
remove all spaces from the first name;
remove all spaces from the last name; and
join the processed first and last names using one period (.).
Explanation:

lower() converts every letter in both names to lowercase.
.replace(" ", "") searches for any space characters in multi-part names (like "Ana Maria") and replaces them with an empty string, effectively deleting the spaces.
The + operator joins the cleaned first name, a period ".", and the cleaned last name into a single continuous string

```python

def make_username(first_name, last_name):
    first_clean = first_name.lower().replace(" ", "")
    last_clean = last_name.lower().replace(" ", "")
    return first_clean + "." + last_clean
make_username("Ada", "Lovelace")

make_username("Alan", "Turing")

make_username("Ana Maria", "De Leon")

```



