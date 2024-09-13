# Session 3: Lists, Tuples, and Loops

## Lesson Objectives

- Understand how to create and manipulate lists in Python
- Learn about list methods and how they compare to JavaScript array methods
- Comprehend list slicing and list comprehensions in Python
- Explore tuples and their immutable nature
- Know when to use lists versus tuples in Python
- Learn about loops in Python: for loops
- Understand the differences between Python and JavaScript loops
- Use range(), enumerate(), and indexing in loops

## Topics Covered

### Lists in Python

- Creation using square brackets []
- Indexing, slicing, and negative indices
- Common List Methods
  - .append(), .extend(), .insert(), .remove(), .pop(), .sort(), .reverse()
- List Comprehensions
  - Creating lists using [expression for item in iterable if condition]
- Comparison with JavaScript Arrays
  - Similarities in creation and manipulation
  - Differences in methods and capabilities

### Tuples in Python

- Creation and Declaration Syntax
  - Tuples are created by placing comma-separated values within parentheses ()
  - Example: my_tuple = (1, 2, 3)
  - Single-element tuples require a comma:
    - Correct: single_element = (5,)
    - Incorrect (not a tuple): not_a_tuple = (5)
- Immutability
  - Tuples are immutable; once created, their elements cannot be changed
  - Attempting to modify a tuple results in a TypeError
- Comparison with Strings
  - Like strings, tuples cannot be altered after creation
- Use Cases
  - Fixed collections of items
  - Tuples as keys in dictionaries because they are hashable

### Loops in Python

- For Loops
  - Syntax: for item in iterable:
  - Iterating over sequences (lists, tuples, strings)
- Using range()
  - Generating sequences of numbers
  - Syntax: for i in range(start, stop, step):
- Using enumerate()
  - Accessing both index and value
  - Syntax: for index, value in enumerate(iterable):
- Comparison with JavaScript
  - Python's for item in iterable vs. JavaScript's for...of
  - No direct equivalent of JavaScript's traditional for (let i = 0; i < length; i++) loop; use range() in Python
  - Python's for key in dict vs. JavaScript's for...in
- Loop Control Statements
  - break, continue, and pass
- Indexes in Loops
  - Accessing elements by index
  - Difference between zero-based indexing in Python and JavaScript

## Additional Resources

- [Python Lists - Official Documentation](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
- [Python Tuples - Official Documentation](https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences)
- [Python for Loops - Real Python](https://realpython.com/python-for-loop/)
- [List Comprehensions in Python - Real Python](https://realpython.com/list-comprehension-python/)
