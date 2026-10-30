# PYTHON
This is my PYTHON Programming Repository.
<br>
Author --Moynul Islam


# COMPLETE PYTHON COURSE ROADMAP
## Detailed guide to Parts 1–10 | Jupyter Notebook learning series

**Course context:** CSC5013 – Foundation in Computer Programming  
**Learning style:** Step-by-step lessons, Bangla + English explanations, runnable Python examples, expected outputs, mini-projects, practice questions and solutions.

---

## 1. How to use this course

This guide explains what each available part teaches and in what order to study them.

### Recommended study method
1. Study the lesson in order. Do not skip the explanation and jump straight to the solution.
2. Open the corresponding `.ipynb` file in Jupyter Notebook, JupyterLab, VS Code or Google Colab.
3. Run one cell at a time with **Shift + Enter**.
4. Before running a code cell, predict what the output will be.
5. Run the cell and compare your prediction with the actual output.
6. Change variable values and test the code again.
7. Complete the practice questions without looking at the solutions first.
8. Rebuild the mini-projects yourself, changing the input and adding at least one new feature.

### Recommended folder structure
Keep each part in its own folder so that the notebooks and their practice files remain organized.

```text
Python_Course/
    Part_01_Foundations/
    Part_02_Decision_Making_and_Loops/
    Part_03_Strings_and_Collections/
    Part_04_Functions_and_Recursion/
    Part_05_Not_Provided/
    Part_06_Object_Oriented_Programming/
    Part_07_File_Handling_and_Exceptions/
    Part_08_Modules_and_Packages/
    Part_09_Iterators_and_Generators/
    Part_10_Regular_Expressions/
```

### Opening a notebook
If Jupyter is not installed, open a terminal or Command Prompt and run:

```bash
python -m pip install notebook
```

Then move to the folder containing the notebook and run:

```bash
jupyter notebook
```

You can also upload `.ipynb` files to Google Colab or open them in VS Code with the Python and Jupyter extensions.

---

# 2. Detailed part-by-part roadmap

## PART 1 — Python Foundations
**Notebook:** `Python_Tutorial_Part_1_Foundations.ipynb`  
**Level:** Beginner

This part introduces Python and the basic building blocks required to write your first programs.

### What you will learn

1. **What is Python?**
   - What Python is and what it is used for.
   - Important features of Python.
   - A first small Python program.

2. **Python interpreter and program execution**
   - How Python executes instructions.
   - Running your first command in Jupyter.

3. **Basic syntax**
   - `print()` to display output.
   - Python is case-sensitive.
   - Indentation and why spaces matter.
   - Comments in Python.

4. **Variables**
   - Creating variables and assigning values.
   - Updating variable values.
   - Assigning multiple variables in one statement.
   - Assigning one value to multiple variables.

5. **Identifiers and naming rules**
   - Valid and invalid variable names.
   - Naming conventions and Python keywords.

6. **Data types**
   - Integer (`int`).
   - Floating-point (`float`).
   - String (`str`).
   - Boolean (`bool`).
   - Checking a value's type with `type()`.

7. **User input**
   - Taking input with `input()`.
   - Receiving numeric input and converting it.

8. **Type conversion**
   - Converting between strings, integers and floats.
   - Understanding common conversion errors.

9. **Operators**
   - Arithmetic operators.
   - Comparison operators.
   - Assignment operators.
   - Logical operators.
   - Membership operators.
   - Identity operators.

10. **Operator precedence**
    - Understanding which operation Python performs first.

11. **Useful built-in functions**
    - Basic built-in functions used in beginner programs.

### Mini-projects
- Student Information Program.
- Simple Calculator.

### By the end of Part 1, you should be able to
- Write and run a basic Python program.
- Store information in variables.
- Identify common data types.
- Take input from a user.
- Perform calculations and comparisons.
- Understand basic syntax and indentation.

---

## PART 2 — Decision Making and Loops
**Notebook:** `Python_Tutorial_Part_2_Decision_Making_and_Loops.ipynb`  
**Level:** Beginner

This part teaches how a program makes decisions and repeats instructions.

### What you will learn

1. **Control flow**
   - How Python normally executes code from top to bottom.
   - How decision statements and loops change the execution path.

2. **Conditions and Boolean results**
   - `True` and `False`.
   - Comparison operators in conditions.
   - Combining conditions with `and`, `or` and `not`.

3. **Decision-making statements**
   - `if`.
   - `if-else`.
   - `if-elif-else`.
   - Nested `if` statements.

4. **Practical decision examples**
   - Voting eligibility.
   - Pass or fail.
   - Positive or non-positive number.
   - Grade calculator.
   - Finding the largest of three numbers.
   - Simple login check.

5. **Loops**
   - Why loops are needed.
   - `for` loop.
   - `while` loop.
   - Looping through a string.
   - The `range()` function.
   - Tracing a loop step by step.

6. **Loop control**
   - `break` to stop a loop.
   - `continue` to skip to the next iteration.
   - `pass` as a placeholder statement.
   - Nested loops.

7. **Practical loop tasks**
   - Sum of numbers.
   - Multiplication table.
   - Searching for a value.
   - Printing odd and even numbers.
   - Star patterns.
   - Multiple multiplication tables.

8. **Comparing loops**
   - When a `for` loop is suitable.
   - When a `while` loop is suitable.
   - Understanding an infinite loop.

### Mini-projects
- Even and Odd Number Checker.
- Simple Login Attempts.
- Number Guessing Game.

### By the end of Part 2, you should be able to
- Write conditions for real problems.
- Build a grade calculator.
- Repeat tasks using loops.
- Control a loop with `break` and `continue`.
- Solve beginner programming problems involving decisions and repetition.

---

## PART 3 — Strings and Collections
**Notebook:** `Python_Tutorial_Part_3_Strings_and_Collections.ipynb`  
**Level:** Beginner to Intermediate

This part explains how Python stores and processes text and groups of values.

### Section A — Strings

1. What a string is.
2. String indexing and positive/negative indexes.
3. String slicing.
4. Slicing with a step.
5. String operators.
6. String immutability.
7. Common string methods:
   - Case conversion.
   - Removing spaces and characters.
   - Searching and counting.
   - Replacing and splitting.
   - Checking string content.
8. String formatting:
   - f-strings.
   - Formatting decimal places.
   - `format()` method.

**Mini-project:** Text Analyzer.

### Section B — Lists

1. What a list is.
2. Creating lists and accessing elements.
3. List slicing.
4. Updating list elements.
5. Adding items:
   - `append()`.
   - `extend()`.
6. Removing items.
7. Searching and counting.
8. Sorting and reversing.
9. Useful list functions.
10. Looping through lists.
11. Using `enumerate()`.
12. Nested lists.
13. List copying and the difference between shared references and independent copies.
14. List comprehension.

### Section C — Tuples

1. What a tuple is.
2. Creating tuples correctly.
3. Accessing tuple elements.
4. Tuple immutability.
5. Tuple methods and unpacking.

### Section D — Sets

1. What a set is.
2. Unique elements and duplicate removal.
3. Adding and removing set items.
4. Membership checking.
5. Set operations such as union, intersection and difference.

### Section E — Dictionaries

1. Key-value pairs.
2. Creating and accessing dictionaries.
3. Adding, updating and removing values.
4. Dictionary methods.
5. Iterating through keys and values.
6. Nested dictionaries.

### By the end of Part 3, you should be able to
- Process and format text.
- Store multiple values in lists and tuples.
- Remove duplicates with sets.
- Store structured information using dictionaries.
- Select the correct collection for a programming problem.

---

## PART 4 — Functions and Recursion
**Notebook:** `Python_Tutorial_Part_4_Functions_and_Recursion.ipynb`  
**Level:** Beginner to Intermediate

This part teaches how to divide a program into reusable blocks and how a function can call itself.

### Section A — Function fundamentals

1. What a function is and why functions are useful.
2. Built-in functions.
3. Defining and calling a user-defined function.
4. Calling a function more than once.
5. Function execution order.
6. Parameters and arguments.
7. Positional arguments.
8. Keyword arguments.
9. Default parameters.
10. The `return` statement.
11. Difference between `print()` and `return`.
12. Functions without an explicit return value.
13. Returning multiple values.
14. Practical function examples:
    - Rectangle area.
    - Even/odd checking.
    - Largest of three numbers.

### Section B — Flexible functions

1. Variable-length positional arguments: `*args`.
2. Looping through `*args`.
3. Variable-length keyword arguments: `**kwargs`.
4. Combining different parameter types.
5. Variable scope:
   - Local variables.
   - Global variables.
   - `global`.
   - Enclosing scope.
   - `nonlocal`.
6. Docstrings and function documentation.

### Section C — Lambda and functional tools

1. Lambda functions.
2. Lambda with multiple parameters.
3. Sorting with lambda.
4. `map()`.
5. `filter()`.
6. Using functions to process collections.

### Section D — Recursion

1. What recursion means.
2. Base case and recursive case.
3. How recursive calls work.
4. Tracing calls and returns.
5. Factorial.
6. Countdown.
7. Sum of numbers.
8. Fibonacci sequence.

### Mini-projects and practice
- Reusable calculation functions.
- Collection-processing exercises.
- Recursion tracing and problem-solving exercises.

### By the end of Part 4, you should be able to
- Write reusable functions.
- Pass different kinds of arguments.
- Return calculated results.
- Understand variable scope.
- Use lambda, map and filter.
- Solve basic recursive problems.

---

## PART 5 — Not Provided in the Uploaded Notebook Set
**Status:** No Part 5 `.ipynb` or README was found in the uploaded ZIP collection.

The Part 1 README originally mentions Part 5 as **Modules, Packages and Environments**. However, the later Part 8 notebook covers modules and packages in detail.

**Important:** Part 5 is not treated as a completed notebook in this course collection. Its exact lesson content cannot be confirmed from the uploaded files.

---

## PART 6 — Object-Oriented Programming (OOP)
**Notebook:** `Python_Tutorial_Part_6_Object_Oriented_Programming.ipynb`  
**Level:** Beginner to Intermediate

This part teaches how to organize programs using classes and objects.

### Section A — Classes and objects

1. What OOP is and why it is useful.
2. What a class is.
3. What an object is.
4. Attributes.
5. The `__init__()` constructor.
6. Instance methods.
7. Updating object attributes.

### Section B — Attributes and methods

1. Instance attributes.
2. Class attributes.
3. Updating class attributes.
4. Instance methods.
5. Class methods.
6. Static methods.

### Section C — Encapsulation

1. What encapsulation means.
2. Controlling access to object data.
3. Name mangling with double underscore.
4. Properties and controlled attribute access.

### Section D — Inheritance

1. What inheritance is.
2. Parent and child classes.
3. The `super()` function.
4. Method overriding.
5. Types of inheritance.
6. Method Resolution Order (MRO).

### Section E — Polymorphism and abstraction

1. Polymorphism.
2. Duck typing.
3. Abstraction.
4. Using abstract classes and methods.

### Section F — Composition and special methods

1. Composition.
2. Magic/dunder methods.
3. How special methods customize object behaviour.

### Mini-projects
- Bank Account System.
- Student Management.
- Employee and Manager Inheritance.

### By the end of Part 6, you should be able to
- Design classes and create objects.
- Use constructors, attributes and methods.
- Apply encapsulation.
- Build parent-child class relationships.
- Understand polymorphism and abstraction.
- Organize related objects using composition.

---

## PART 7 — File Handling and Exception Handling
**Notebook:** `Python_Tutorial_Part_7_File_Handling_and_Exception_Handling.ipynb`  
**Level:** Beginner to Intermediate

This part explains how Python reads, creates, updates and manages files, and how programs handle errors.

### Section A — File handling fundamentals

1. What file handling is.
2. Current working directory.
3. Creating text files.
4. Reading text files.
5. The `with open()` context manager.
6. File modes:
   - `r` — read.
   - `w` — write/overwrite.
   - `a` — append.
   - `x` — create exclusively.
7. `read()`, `readline()` and `readlines()`.
8. Looping through file contents.
9. Writing and appending.
10. File pointers:
    - `tell()`.
    - `seek()`.
11. File encoding.

### Section B — Paths and directories

1. Using `pathlib.Path`.
2. Creating directories.
3. Listing files.
4. Renaming and moving files.
5. Deleting practice files.

### Section C — CSV files

1. What CSV means.
2. Writing CSV with `csv.writer()`.
3. Reading CSV with `csv.reader()`.
4. Writing with `DictWriter`.
5. Reading with `DictReader`.

### Section D — JSON files

1. What JSON is.
2. Writing JSON with `json.dump()`.
3. Reading JSON with `json.load()`.
4. Converting between Python objects and JSON strings.
5. CSV versus JSON.

### Section E — Exception handling

1. What an exception is.
2. `try` and `except`.
3. Handling division by zero.
4. Multiple `except` blocks.
5. The `else` block.
6. The `finally` block.
7. Complete `try-except-else-finally` structure.
8. Raising exceptions and custom exception classes.

### By the end of Part 7, you should be able to
- Read and write files safely.
- Work with directories and paths.
- Store structured information in CSV and JSON.
- Handle common runtime errors.
- Make programs more reliable.

---

## PART 8 — Modules, Packages and Python Standard Library
**Notebook:** `Python_Tutorial_Part_8_Modules_Packages_and_Standard_Library.ipynb`  
**Level:** Beginner to Intermediate

This notebook teaches how to reuse code from other files and use useful modules supplied with Python.

### What you will learn

1. What a module is.
2. Why modules are useful.
3. Importing a complete module.
4. Importing with an alias using `as`.
5. Importing selected functions and variables.
6. Why `from module import *` is generally avoided.
7. Exploring modules with `dir()` and `help()`.
8. Standard-library modules:
   - `math` — mathematical functions.
   - `random` — random values and selections.
   - `datetime` — dates and times.
   - `statistics` — mean, median and mode.
   - `os` — operating-system features.
   - `pathlib` — file and folder paths.
   - `json` — JSON data conversion.
9. Creating your own `.py` module.
10. Importing functions, variables and classes from your own module.
11. What a package is.
12. Creating a package with `__init__.py`.
13. Importing modules from a package.
14. Understanding `sys.path`.
15. Third-party packages and `pip`.
16. Checking installed packages.

### Mini-projects
- Random Quiz Picker.
- Student Result Report.
- Date Difference Calculator.
- Save Student Data as JSON.

### By the end of Part 8, you should be able to
- Reuse code across Python files.
- Create a simple module and package.
- Use common standard-library modules.
- Install and inspect third-party packages.
- Organize a multi-file Python project.

---

## PART 9 — Iterators, Generators and Advanced Python Concepts
**Notebook:** `Python_Tutorial_Part_9_Iterators_Generators_and_Advanced_Concepts.ipynb`  
**Level:** Intermediate

This part explains how Python accesses data one item at a time and how to create efficient iterable objects.

### What you will learn

1. Iteration.
2. Difference between iterable and iterator.
3. Creating iterators with `iter()`.
4. Getting values with `next()`.
5. `StopIteration`.
6. How a `for` loop uses an iterator.
7. Creating custom iterator classes:
   - `__iter__()`.
   - `__next__()`.
8. What a generator is.
9. Generator functions and `yield`.
10. Difference between `return` and `yield`.
11. Generator expressions.
12. Lazy evaluation.
13. `yield from`.
14. Useful iterable functions:
   - `enumerate()`.
   - `zip()`.
   - `map()`.
   - `filter()`.
15. The `itertools` module:
   - `count()`.
   - `cycle()`.
   - `islice()`.
   - `chain()`.
16. Basic decorators.
17. Decorators that accept function arguments.
18. `functools.wraps`.
19. Context managers.
20. The `with` statement.

### Mini-projects
- Generate Even Numbers.
- Student Marks Generator.
- Simple Countdown Generator.

### By the end of Part 9, you should be able to
- Explain how iteration works internally.
- Create your own iterator and generator.
- Process values lazily.
- Use common iterator tools.
- Understand the basic purpose of decorators and context managers.

---

## PART 10 — Regular Expressions (RegEx)
**Notebook:** `Python_Tutorial_Part_10_Regular_Expressions.ipynb`  
**Level:** Beginner to Intermediate

This part teaches how to search, match, extract, replace and validate text patterns.

### What you will learn

1. What Regular Expressions are.
2. Python's `re` module.
3. Raw strings and escaping.
4. Matching functions:
   - `search()`.
   - `match()`.
   - `fullmatch()`.
5. Finding matches:
   - `findall()`.
   - `finditer()`.
6. Character classes.
7. Quantifiers.
8. Anchors and word boundaries.
9. Capturing groups and named groups.
10. Alternation (`|`) and non-capturing groups.
11. Replacing and splitting:
    - `sub()`.
    - `split()`.
12. Regex flags.
13. Compiling patterns with `re.compile()`.
14. Greedy and non-greedy matching.
15. Lookaheads.
16. Practical format checks:
    - Student ID examples.
    - Email-like text patterns.
    - Bangladesh-style mobile number format examples.
17. Extracting information from log lines.
18. Text analysis.
19. Whitespace normalization.
20. Redacting phone-like text.

### Mini-projects
- Text Analyzer.
- Normalize Whitespace.
- Redact Phone-like Text.
- Extract Information from Logs.

### By the end of Part 10, you should be able to
- Write basic regular-expression patterns.
- Search for patterns in text.
- Extract matching information.
- Replace or split text using patterns.
- Build simple classroom format checks.

**Important note:** The notebook's email and phone patterns are classroom format checks. A regex match does not prove that an email address or phone number is real, active or reachable.

---

# 3. Overall learning progression

The course moves from basic programming to more structured and reusable Python code.

```text
PART 1
Python Foundations
      |
      v
PART 2
Decision Making and Loops
      |
      v
PART 3
Strings and Collections
      |
      v
PART 4
Functions and Recursion
      |
      v
PART 5
Not provided in this notebook collection
      |
      v
PART 6
Object-Oriented Programming
      |
      v
PART 7
File Handling and Exception Handling
      |
      v
PART 8
Modules, Packages and Standard Library
      |
      v
PART 9
Iterators, Generators and Advanced Concepts
      |
      v
PART 10
Regular Expressions
```

---

# 4. Recommended study order and milestones

| Milestone | Parts | What you should be comfortable doing |
|---|---|---|
| Beginner foundation | 1–2 | Write basic programs, use variables, conditions and loops |
| Data handling | 3 | Process text and use lists, tuples, sets and dictionaries |
| Program structure | 4 | Write reusable functions and understand recursion |
| OOP | 6 | Design classes and use inheritance and polymorphism |
| Files and reliability | 7 | Work with files and handle exceptions |
| Code organization | 8 | Create modules and packages and use standard libraries |
| Advanced iteration | 9 | Use iterators, generators and decorators |
| Text pattern processing | 10 | Search, extract and transform text using RegEx |

### Suggested mastery rule
Do not move to the next part only because you have read the notebook. Move forward when you can:
- Explain the main concepts in your own words.
- Run and modify the examples.
- Solve most practice questions without copying.
- Complete the mini-project with limited help.

---

# 5. Important notes about the notebook collection

1. The uploaded collection contains notebooks for Parts **1, 2, 3, 4, 6 and 7**.
2. Part 5 was not included as a separate notebook. The Part 1 README describes the original Part 5 plan as “Modules, Packages and Environments,” while the later Part 8 notebook teaches modules and packages.
3. Parts 8, 9 and 10 were added as continuation tutorials in this learning series.
4. The Part 1 README lists an earlier planned sequence in which Part 8 was NumPy/Pandas/Data Visualization and Part 9 was Database Connectivity/Introductory Machine Learning. Those topics are **not covered by the current Part 8 and Part 9 notebooks described in this guide**.
5. This guide describes the actual notebook contents available in the collection. It does not claim that every topic in the wider course or original lecture slides has been covered.
6. The course sequence skips from Part 4 to Part 6 because no separate Part 5 notebook was supplied.

---

# 6. Final advice

Learn Python by writing code, not by memorizing code. For every concept:
- Read the explanation.
- Predict the output.
- Run the code.
- Change the input.
- Find and fix an error.
- Try a similar problem without looking at the example.

**Your target:** By completing Parts 1–10 and practising the exercises, you will build a strong foundation in Python syntax, problem-solving, data structures, functions, OOP, file operations, code organization, iteration and text processing.

**End of Overall Python Course Guide.**

