# Session 2: Variables, Data Types, Booleans, and Strings

## Lesson Objectives

- Understand how variables are declared and used in Python
- Learn about basic data types in Python: numbers, booleans, strings
- Comprehend the differences in booleans and truthiness between Python and JavaScript
- Learn Python naming conventions: snake_case vs. JavaScript's camelCase
- Utilize string methods for manipulating text data
- Compare Python's dynamic typing with JavaScript's variable declarations
- Understand string formatting in Python using f-strings compared to template literals in JavaScript

## Topics Covered

### Variables in Python

- Declaration and assignment without explicit type declarations
- Dynamic typing allows variables to change type
- Naming Conventions
  - Python uses snake_case for variable and function names
  - JavaScript typically uses camelCase
  - Importance of following language-specific conventions
- Comparison with JavaScript
  - Python variables don't require var, let, or const

### Basic Data Types

#### Numbers

- Integers and floats
- Arithmetic operations
- Differences in division operations (e.g., integer division using // in Python)

#### Booleans

- Truthy and Falsy Values
  - Python Falsy Values: False, None, 0, 0.0, '' (empty string), [], {}, ()
  - JavaScript Falsy Values: false, 0, -0, 0n, '', null, undefined, NaN
  - Implications:
    - Empty data structures like lists [] and dictionaries {} are falsy in Python but truthy in JavaScript
    - Understanding these differences when writing conditional statements
- Type Coercion and Equality Operators
  - Python:
    - Uses strict equality with ==
    - No implicit type coercion during comparisons
  - JavaScript:
    - Loose Equality (==): Performs type coercion
    - Strict Equality (===): No type coercion
  - Implications:
    - Importance of using === in JavaScript to avoid unexpected results

### Strings in Python

- String Literals
  - Single ('), double ("), and triple quotes (''' or """)
- String Indexing and Slicing
  - Accessing individual characters and substrings
- String Methods
  - .upper(), .lower(), .replace(), .split(), .strip(), etc.
- String Formatting
  - Using f-strings (f"Hello, {name}!") in Python
  - Comparison with JavaScript:
    - Python's f-strings vs. JavaScript's template literals (`Hello, ${name}!`)
- Immutable Nature of Strings
  - Strings in Python are immutable; they cannot be changed after creation

## Additional Resources

- [Python Data Types - Official Documentation](https://docs.python.org/3/library/stdtypes.html)
- [Python Strings - GeeksforGeeks](https://www.geeksforgeeks.org/python-string/)
- [Python String Methods - W3Schools](https://www.w3schools.com/python/python_ref_string.asp)
- [JavaScript to Python Syntax Comparison - Python Wiki](https://wiki.python.org/moin/JavascriptPython)
