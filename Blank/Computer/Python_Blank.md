## 1. Python Fundamentals

### Syntax and Variables

1. {What is Python?} : {Python is a readable, high-level programming language used to build applications, automate tasks, and analyze data.}
2. {What is a variable in Python?} : {A variable is a named reference used to store a value.}
3. {How do you assign a value to a variable?} : {You assign a value with the equals sign, as in `age = 25`.}
4. {What are Python’s basic data types?} : {Common basic data types include integers, floats, strings, booleans, and `None`.}
5. {Why is indentation important in Python?} : {Indentation defines blocks of code belonging to functions, loops, conditions, and classes.}

### Operators and Input

6. {What does the `==` operator do?} : {The `==` operator checks whether two values are equal.}
7. {What is the difference between `/` and `//`?} : {The `/` operator performs regular division, while `//` performs floor division.}
8. {How do you receive input from a user?} : {You receive user input by calling the `input()` function.}
9. {How do you convert a string to an integer?} : {You convert a string to an integer with `int()`.}
10. {What is an f-string?} : {An f-string inserts expressions into a string using braces, as in `f"Hello, {name}"`.}

## 2. Control Flow

### Conditions

11. {What is an `if` statement?} : {An `if` statement executes a block of code when its condition is true.}
12. {When is `elif` used?} : {The `elif` keyword tests another condition when preceding conditions are false.}
13. {What does the `else` block do?} : {The `else` block runs when none of the preceding conditions are true.}
14. {What values are considered false in Python?} : {Values such as `False`, `None`, zero, and empty collections are considered false.}
15. {What are logical operators in Python?} : {The logical operators `and`, `or`, and `not` combine or reverse conditions.}

### Loops

16. {What is a `for` loop used for?} : {A `for` loop processes each item in an iterable.}
17. {What is a `while` loop used for?} : {A `while` loop repeats code while a condition remains true.}
18. {What does `break` do inside a loop?} : {The `break` statement immediately stops the nearest enclosing loop.}
19. {What does `continue` do inside a loop?} : {The `continue` statement skips the rest of the current iteration.}
20. {What does the `range()` function produce?} : {The `range()` function produces a sequence of integers commonly used in loops.}

## 3. Data Structures

### Lists and Tuples

21. {What is a list?} : {A list is an ordered and mutable collection of values.}
22. {How do you add an item to a list?} : {You add an item to the end of a list with the `append()` method.}
23. {What is list slicing?} : {List slicing extracts part of a list by using start, stop, and optional step positions.}
24. {What is a tuple?} : {A tuple is an ordered collection whose elements cannot be reassigned.}
25. {When should you use a tuple instead of a list?} : {You should use a tuple when the collection is intended to remain unchanged.}

### Dictionaries and Sets

26. {What is a dictionary?} : {A dictionary stores values under unique keys.}
27. {How do you safely retrieve a dictionary value?} : {You can use `get()` to retrieve a value without raising an error when the key is absent.}
28. {What is a set?} : {A set is an unordered collection containing no duplicate elements.}
29. {How do you remove duplicate values from a list?} : {You can remove duplicates by converting the list to a set, although this may change its order.}
30. {What is a dictionary comprehension?} : {A dictionary comprehension constructs a dictionary through a concise expression and iteration.}

## 4. Functions and Modules

### Functions

31. {How do you define a function?} : {You define a function with the `def` keyword followed by its name and parameters.}
32. {What is the difference between a parameter and an argument?} : {A parameter appears in a function definition, while an argument is the value supplied during a call.}
33. {What does `return` do?} : {The `return` statement ends a function and sends a value back to its caller.}
34. {What are default arguments?} : {Default arguments provide parameter values that are used when callers omit those arguments.}
35. {What are `*args` and `**kwargs`?} : {The `*args` syntax collects positional arguments, while `**kwargs` collects keyword arguments.}

### Modules

36. {What is a Python module?} : {A module is a Python file containing reusable code.}
37. {How do you import a module?} : {You import a module by using an `import` statement.}
38. {Why should imports usually appear at the top of a file?} : {Top-level imports make dependencies easy to identify and follow common Python conventions.}
39. {What does `if __name__ == "__main__"` mean?} : {This condition runs selected code only when the file is executed directly.}
40. {What is a Python package?} : {A package is a collection of related modules organized under a common namespace.}

## 5. Object-Oriented Programming

### Classes and Objects

41. {What is a class?} : {A class is a blueprint that defines the data and behavior of its objects.}
42. {What is an object?} : {An object is an instance created from a class.}
43. {What does the `__init__()` method do?} : {The `__init__()` method initializes an object after it is created.}
44. {What does `self` represent?} : {The `self` parameter refers to the current instance of a class.}
45. {What is inheritance?} : {Inheritance allows a class to reuse or extend another class’s behavior.}

### Design Principles

46. {What is encapsulation?} : {Encapsulation groups related data and behavior while controlling how internal details are accessed.}
47. {What is polymorphism?} : {Polymorphism allows different object types to respond to the same operation in their own ways.}
48. {What is composition?} : {Composition creates complex objects by combining simpler objects.}
49. {When should you create a class?} : {You should create a class when related state and behavior form a meaningful reusable concept.}
50. {Why should classes have focused responsibilities?} : {Focused classes are easier to understand, test, modify, and reuse.}

## 6. Errors and Testing

### Exception Handling

51. {What is an exception?} : {An exception is an event that interrupts normal program execution because an error or unusual condition occurred.}
52. {How do you handle an exception?} : {You handle an exception with `try` and `except` blocks.}
53. {What does the `finally` block do?} : {A `finally` block runs whether or not an exception occurs.}
54. {Why should you avoid a bare `except` statement?} : {A bare `except` can hide unexpected problems and make debugging difficult.}
55. {How do you raise an exception?} : {You raise an exception with the `raise` keyword.}

### Testing and Debugging

56. {What is a unit test?} : {A unit test verifies one small unit of behavior in isolation.}
57. {Why are automated tests valuable?} : {Automated tests detect regressions and give developers confidence when changing code.}
58. {What does an `assert` statement do?} : {An `assert` statement raises an error when its condition is false.}
59. {How does a debugger help a programmer?} : {A debugger lets a programmer pause execution and inspect program state step by step.}
60. {Why should a bug be reproduced before it is fixed?} : {Reproducing a bug clarifies its cause and provides a way to verify the solution.}

## 7. Files and Data

### File Handling

61. {How do you safely open a file in Python?} : {You safely open a file with a `with` statement so it closes automatically.}
62. {What is the difference between file modes `r` and `w`?} : {Mode `r` reads a file, while mode `w` writes a file and replaces its existing contents.}
63. {How do you read an entire text file?} : {You read an entire text file by calling its `read()` method.}
64. {Why should text encoding be specified?} : {Specifying an encoding such as UTF-8 helps text behave consistently across systems.}
65. {What is a context manager?} : {A context manager handles setup and cleanup around a block introduced by `with`.}

### Structured Data

66. {What is JSON?} : {JSON is a text format commonly used to exchange structured data.}
67. {How do you parse JSON text in Python?} : {You parse JSON text with `json.loads()`.}
68. {How do you convert a Python value to JSON text?} : {You convert a compatible Python value to JSON text with `json.dumps()`.}
69. {What is CSV commonly used for?} : {CSV is commonly used to store tabular data in plain text.}
70. {Why should input data be validated?} : {Validation prevents malformed or unexpected data from causing incorrect behavior.}

## 8. Writing Better Python

### Readability and Style

71. {What is PEP 8?} : {PEP 8 is the primary style guide for writing readable Python code.}
72. {Why are meaningful variable names important?} : {Meaningful names reveal intent and reduce the need for explanatory comments.}
73. {What is a docstring?} : {A docstring explains the purpose and usage of a module, class, or function.}
74. {What does DRY mean?} : {DRY means avoiding unnecessary duplication by keeping each piece of knowledge in one clear place.}
75. {Why should functions usually be small?} : {Small functions are generally easier to understand, test, reuse, and maintain.}

### Pythonic Techniques

76. {What is a list comprehension?} : {A list comprehension creates a list concisely from an iterable, with optional filtering.}
77. {What does `enumerate()` do?} : {The `enumerate()` function produces each item together with its index.}
78. {What does `zip()` do?} : {The `zip()` function combines corresponding items from multiple iterables.}
79. {What is unpacking?} : {Unpacking assigns elements from a collection to multiple variables in one operation.}
80. {Why is `is` different from `==`?} : {The `is` operator checks object identity, while `==` checks value equality.}

## 9. Intermediate Python

### Iteration and Generators

81. {What is an iterable?} : {An iterable is an object that can provide its elements one at a time.}
82. {What is an iterator?} : {An iterator tracks iteration state and returns successive values through `next()`.}
83. {What is a generator?} : {A generator is an iterator that produces values lazily using `yield`.}
84. {Why are generators memory-efficient?} : {Generators calculate values as needed instead of storing the complete sequence.}
85. {What does `yield` do?} : {The `yield` keyword pauses a function, returns a value, and preserves its state for later execution.}

### Decorators and Type Hints

86. {What is a decorator?} : {A decorator wraps a function or class to extend its behavior without directly modifying it.}
87. {What is a lambda function?} : {A lambda is a small anonymous function containing a single expression.}
88. {What are type hints?} : {Type hints describe expected value types for readers and static analysis tools.}
89. {Do type hints enforce types at runtime?} : {Python normally does not enforce type hints at runtime.}
90. {What is a dataclass?} : {A dataclass automatically generates common methods for a class primarily used to hold data.}

## 10. Professional Coding Skills

### Tools and Workflow

91. {Why should Python developers learn Git?} : {Git records code changes and supports safe experimentation and collaboration.}
92. {What is a virtual environment?} : {A virtual environment isolates a project’s Python packages from other projects.}
93. {What is a dependency file?} : {A dependency file records the external packages required by a project.}
94. {What is a linter?} : {A linter detects suspicious code and style problems before execution.}
95. {What is a formatter?} : {A formatter automatically applies consistent code styling.}

### Problem-Solving

96. {How should you approach a difficult coding problem?} : {Break the problem into small parts, define expected results, and solve each part separately.}
97. {What is an algorithm?} : {An algorithm is a precise sequence of steps for solving a problem.}
98. {Why should edge cases be considered?} : {Edge cases reveal failures that may not appear with ordinary inputs.}
99. {How can you become better at Python coding?} : {Build projects, practice regularly, study strong code, test your work, and reflect on mistakes.}
100. {What is the most important habit of a good coder?} : {A good coder continuously learns while writing clear, correct, and maintainable solutions.}