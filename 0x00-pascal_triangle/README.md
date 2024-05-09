# Project Name
**0x00. Pascal's Triangle**

## Resources
- [What is Pascal’s triangle](https://www.cuemath.com/algebra/pascals-triangle/)
- [Pascal’s Triangle - Numberphile](https://www.youtube.com/watch?feature=shared&v=0iMtlus-afo)
- [What are Python Algorithms](https://builtin.com/data-science/python-algorithms)

## Additional Resources
- [Mock Technical Interview](https://www.youtube.com/watch?v=1qw5ITr3k9E)

## Must Know
To successfully complete this project, you should revise the following Python concepts:

1.### Lists and List Comprehensions:

- Understand how to create, access, modify, and iterate over lists.
- Utilize list comprehensions for more concise and readable code, especially for generating rows of Pascal’s Triangle.

2.### Functions:

- Know how to define and call functions.
- Pass parameters and return values, particularly how to return a list of lists representing Pascal’s Triangle.

3.### Loops:

- Use for and while loops to iterate through sequences.
- Nested loops may be necessary for generating each row and calculating the values of Pascal’s Triangle.

4.### Conditional Statements:

- Apply if, elif, and else conditions to implement logic based on the position within Pascal’s Triangle (e.g., the edges of the triangle always being 1).

5.### Recursion (Optional):

- While not strictly necessary, understanding recursion can provide an alternative approach to generating Pascal’s Triangle.
- Recognize base cases and recursive cases for a function that generates the triangle’s rows.

6.### Arithmetic Operations:

- Perform addition, a fundamental operation for calculating each element of Pascal’s Triangle as the sum of the two elements directly above it.

7.### Indexing and Slicing:

- Access elements and slices of lists, crucial for identifying and summing the correct elements when constructing each row of the triangle.

8.### Memory Management:

- Be mindful of how lists are stored and copied, especially when creating new rows based on the values of the previous row.

9.### Error and Exception Handling (Optional):

- Use try-except blocks as needed to handle potential errors, such as invalid input types or values.

10.### Efficiency and Optimization:

- Consider the time and space complexity of different approaches to generating Pascal’s Triangle.
- Evaluate and apply optimizations to improve the performance of the solution.

By revisiting these concepts, you will be well-prepared to tackle the challenges of implementing Pascal’s Triangle in Python, applying both your mathematical understanding and programming skills to develop an efficient and effective solution.

##  Requirements

### Python Scripts
*   Allowed editors: `vi`, `vim`, `emacs`.
*   All your files will be interpreted/compiled on Ubuntu 20.04 LTS using gcc, using python3 (version 3.8.5).
*   All your files should end with a new line.
*   The `main.py` files are used to test your functions, but you don’t have to push them to your repo.
*   The first line of all your files should be exactly `#!/usr/bin/python3`.
*   Your code should use the pycodestyle (version `2.8.*`).
*   All your files must be executable.
*   All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`).
*   All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)`' and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`).
*   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified).


## Project Description

* **0. Pascal's Triangle** - Create a function that returns a list of lists of integers representing the Pascal’s triangle of n. - `0-pascal_triangle.py`.
