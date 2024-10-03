# Coding environment

## Basic concepts

### Computer:

A computer is like a super-smart tool that helps you solve problems, make calculations, and manage information. Think
of it as a machine that takes your instructions and does what you ask it to do, whether that’s typing a document, 
playing a game, or browsing the web. It’s a combination of hardware (the physical parts) and software (the programs 
that make it work).

### Data In, Data Out Process:

- This is how a computer interacts with the world. It’s like when you ask a question and get an answer:

- Input (Data In): The information you give the computer, like typing on a keyboard or clicking with a mouse. It's 
similar to telling the computer what you want it to do.

- Processing: The computer takes that input and works with it (using its brain, called a processor). It figures out 
what to do, like solving a puzzle or following steps.

Output (Data Out): The result or response from the computer. This could be showing something on the screen, playing a 
sound, or printing a document. It’s like getting the answer after the computer finishes its work.

### Hardware:

Hardware is all the physical stuff you can touch in a computer—like the keyboard, mouse, monitor, and processor inside
the computer box. It’s the body of the computer. Just like a car needs an engine and wheels to work, a computer needs 
its hardware to function.

### Software:

Software is the set of instructions or programs that tell the computer what to do. It’s like the brain or mind of the 
computer. While hardware is the body, the software is the ideas and knowledge that make it work. Examples include your 
web browser, games, and operating systems like Windows or macOS.

### Computing:

Computing is basically problem-solving using a computer. It’s the process of inputting data, processing it, and then
outputting results. When you use a computer for anything—like sending an email, solving math problems, or making 
music—you’re doing computing.

In simple terms, computing is making the computer do work for you based on the instructions or programs (software) 
it’s given, using its hardware to handle information and get results.

## Python coding style

Python is a simple, easy-to-read programming language. It uses plain English-like syntax, making it a great choice for 
beginners. Python emphasizes writing code in a clear and organized way, using indentation and following specific rules.

**Reserved Words in Python:**

Reserved words (or keywords) are special words that Python uses for specific purposes. You cannot use these as variable
names because they have predefined meanings in the language.

Here’s a list of Python's reserved words:

```
False      await      else       import     pass
None       break      except     in         raise
True       class      finally    is         return
and        continue   for        lambda     try
as         def        from       nonlocal   while
assert     del        global     not        with
async      elif       if         or         yield
```

**Indentation:**

Indentation in Python refers to adding spaces or tabs at the beginning of lines to define blocks of code. Unlike many
other languages, Python uses indentation to organize code and show the structure (e.g., for loops or conditionals).

*Incorrect Example (without indentation):*

```python
if True:
print("This will cause an error")
```

*Correct Example:*

```python
if True:
    print("This is indented")
```

Python requires indentation, so make sure you indent consistently, usually by 4 spaces, to keep your code readable and
error-free.

### Comments

In Python, comments are pieces of text in your code that Python ignores when running the program. They are extremely
useful for leaving notes, explaining what certain parts of the code do, and documenting important information for 
yourself or other developers.

**Types of Comments in Python:**

*Single-line Comments:*
- Use the `#` symbol to write a comment. Anything after the `#` on that line is ignored by Python.
- Example:

```python
# This is a single-line comment
print("Hello, world!")  # This prints a message
```

*Multi-line Comments:*

- You can create multi-line comments using triple quotes (''' or """). Technically, these are treated as multi-line
    strings, but they can be used as comments if not assigned to any variable.
- Example:

```python
"""
This is a multi-line comment.
It can span multiple lines.
"""
print("Hello, world!")
```

**Why Comments Are Important:**

From my experience, comments are one of the first and most useful tools in any programming language. They help in
several key ways:

- Clarity: Comments explain complex or tricky parts of the code, making it easier to understand, especially when
revisiting the code after a long time.

- Collaboration: In teams, comments make your code readable and understandable for others, improving collaboration.
- Debugging: Comments allow you to track thought processes and decisions, which is useful when debugging or revising
code.

As someone who’s navigated through many layers of IT and programming, I believe comments are invaluable, not only for
beginners learning to code but also for experienced programmers who need to document their thought process or clarify 
logic. They create a “roadmap” within the code, guiding both the writer and future readers through what’s happening.

## Variables and Values

In Python, a variable is like a container or a label that holds a value. You can think of it as naming a box where you
store information, and the value is what's inside the box.

**How Values Work with Variables:**

*Assigning Values to Variables:*

- You assign a value to a variable using the `=` operator. The variable can then hold that value until you change it.
- Example:

```python
name = "Alice"
age = 16
```

> Here, the variable `name` stores the value `"Alice"`, and `age` holds the value `25`.

*Changing Variable Values:*

- Once a variable is assigned a value, you can change it anytime by assigning a new value.
- Example:

```python
age = 25
age = 26  # Now the value of age is updated to 26
```

*Dynamic Typing:*

- Python is dynamically typed, meaning you don't need to declare the variable's type explicitly (like in some other
languages). Python figures it out based on the value you assign.
- Example:

```python
my_variable = 10  # my_variable is an integer
my_variable = "Hello"  # Now, my_variable holds a string
```
*Variable Naming Rules:*

- Variables should have meaningful names to make your code easy to understand. Python has a few rules for naming
variables:

> Names must start with a letter (a-z, A-Z) or an underscore (`_`).
> Names can include letters, numbers (0-9), and underscores.
> Variable names are case-sensitive (e.g., `age` and `Age` are different).
> Avoid using Python reserved words (e.g., `for`, `while`, `if`).

*Referencing Variables:*

- Once you assign a value to a variable, you can use it later in your program by referencing the variable's name.
- Example:

```python
first_name = "Alice"
last_name = "Wonderland"
print(first_name + " " + last_name)  # Outputs: Alice Wonderland
```

*Important Concepts:*

- Immutable vs Mutable:

> Some values, like numbers and strings, are immutable, meaning you can’t change them after assignment. Instead, a new
> value is assigned.
> Others, like lists and dictionaries, are mutable, meaning their contents can be changed without creating a new
> variable.

*Multiple Assignments:*

Python allows you to assign multiple variables in one line.

```python
x, y, z = 1, 2, 3
```

- This assigns `x = 1`, `y = 2`, and `z = 3` in a single statement.

**Summary:**

In Python, variables are used to store values, which can be anything like numbers, text (strings), or more complex data
types like lists. Python dynamically handles the type of the variable based on the value assigned, making it flexible
and easy to work with. Understanding how values are stored and managed in variables is key to writing effective Python
code.

## Data types

### String

### Integer

### Float

### Bolean

### Conversion type

## Examples

## Exercises

## Summary

---

| ..Go back | Home | Next.. |
|---------- | ---- |--------|
| [Chapter 1](chapter_1.md) | [TOC](../index.md) | [Chapter 3](chapter_3.md) |
