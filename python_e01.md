# Uregion Python E01

## 1. Python Basics
### 1.1. Introduction
Python is a very simple language, and has a very straightforward syntax. It is a high-level programming language created by Guido van Rossum in 1991, who originally started it as his personal project, and made principal contributions to the development of Python. He named it after his favourite British comedy series **Monty Python's Flying Circus**.

![ksajldf](https://upload.wikimedia.org/wikipedia/commons/thumb/6/66/Guido_van_Rossum_OSCON_2006.jpg/440px-Guido_van_Rossum_OSCON_2006.jpg)

Python supports multiple programming paradigms, such as **procedural programming**, **object-oriented programming** and **functional programming**.

Python is also a cross-platform language, with its interpreters available for all major operating systems.


### 1.2. Hello World
The simplest and most basic function in Python is `print`, which is a built-in function for print something. So a Hello World programme in Python would be:

```
print("Hello World");
```

Note that, the current Python community is divided into two worlds: **Python 2** and **Python 3**. This is because Python 3 was designed to cater for backward-compatibility, and a lot of old codes in Python 2 was not easy to export to Python 3.

For example, even the basic hello world programme is different in Python 2 and Python 3.

```
print "Hello World" # Only in Python 2
print("Hello World") # Only in Python 3
```

This is because in Python 2 it was a *key word*, but in Python 3, it's changed to a *built-in function*. There are many such fundamental differences. But for new comers, we can start with Python 3.


### 1.3. Execution environment
Python is an **interpretation language**, which means programme written in python needs to be **interpreted** on the fly by another programme, which is the **python interpreter**. If you use Mac/Linux, you can open your terminal and type `python`, which literally starts this programme.

There exists many different implementations of python interpreter, the most common ones are *CPython* (written in C), *Jython* (written in Java), and *PyPy* (written in a subset of Python). Different implementations vary differently in execution speed and other aspects. The *CPython* interpreter is the reference implementation, and it's usually the one you get in your PC.

There're mainly two ways to run a Python programme, either within an interactive shell, or as a script file.

#### 1.3.1. Interactive Shell
Interactive shell is very suitable for new learners to test and run. It's also useful for prototyping, or just playing around. The most common and basic way is to run `python` in your terminal, when you see something like:
```
Python 3.5.3 (default, Sep  7 2017, 17:08:23)
[GCC 5.3.1 20160406 (Red Hat 5.3.1-6)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
You're in the interactive shell now. Now you can type python code and execute it line by line, but these codes are not saved, so after you exit the interactive shell (Press Ctrl+D), they're lost.

**Important notice:** in interactive shell, each expression result is automatically printed on next line, so you don't need to use `print()` directly. But this is not the case in script file, which is confusing to new learners.

### 1.3.2. Script files
Another way is to write your codes in a file and save it with `.py` extension to make it a python script. This is more persistent and organizable to form a large-scale python programme.

To run a python file, you need to use the interpreter again to execute it:
```
python my_file.py
```

Note that sometimes interpreter may generate some intermediate files with extensions `.pyw` or `.pyc`, which are used to accelerate the execution when you run it next time. But they're safe to delete.

### 1.2. Basic Syntax
Python syntax is designed to be close to natural English and highly readable. It has much fewer punctuations and syntactical constructions than other languages. In the meantime, Python is also famous for being strict in formatting, especially intendation. It uses indentation to indicate blocks for class, function definitions, or control flows, rather than use braces in many other languages.

All statements within the block must be indented with the same amount of spaces.

Statements can be separated into multi-lines using the line continuation character (\\):

```
# OK, separated into 3 lines 
total = item_one + \
		item_two + \
		item_three
```

#### 1.2.1. Identifiers
Identifiers are names used to identify a variable, function, class, module or other object. An identifier starts with a letter A to Z or a to z or an underscore (\_) followed by zero or more letters, underscores and digits (0 to 9).

Below are some valid and invalid identifiers:
```
# valid identifiers
a = 0
Aa1 = 0
_ = 0

# invalid identifiers
1ab = 0 # ERROR: can't start with number
a@b = 0 # ERROR: ^ is not allowed

```

Python is also a case sensitive language, thus `name` and `Name` are two different identifiers.

Some good naming conventions:

* Class names start with an Uppercase letter. All other identifiers start with a lowercase letter.
* Starting an identifier with a single leading underscore indicates that the identifier is private.
* If the identifier also ends with two trailing underscores, the identifier is a language-defined special name.

There're a list of reserved keywords, that cannot be used as identifiers, including `if`, `else`, `class`, `for`, etc. See a full list: https://www.tutorialspoint.com/python3/python_basic_syntax.htm.

#### 1.2.2. Comments
Python uses hash sign (\#) to denote the beginning of a commnet. All characters on this line after the hash sign is considered comments, and not executed by the interpreter.

Python unfortunately doesn't have multi-line comments delimit, so you have to comment each line separately.

#### 1.2.3. Docstrings
#???


### 1.3. Variable Types

### 1.4. Basic Operators

### 1.5. Decision Making

### 1.6. Loops

### 1.7. Primitive Types
#### 1.7.1. Numbers

#### 1.7.2. Strings

A string literal is denoted by using single quotation ('), double quotation (") or triple quotation (''' or """), as long as the same type of quotes starts and ends the string.

#### 1.7.3. Lists
// slicing

// range (in python 2 was a list)

#### 1.7.4. Tuples

#### 1.7.5. Dictionary

### 1.8. Functions
// recursion

// built-in functions: input, print

### Comprehensions
// list comprehension
// dictionary comprehension

### 1.9. Date & Time

### 1.10. Exceptions

## 2. Python Advanced
### 2.1. Object-Oriented Python

### 2.2. Multi-Threading

### 2.3. Python Modules
// if __name__ === main

#### 2.3.1 Built-in modules
// os

// math

// random


#### 2.3.2 Custom modules

### 2.4. Third-Party Libraries
#### 2.4.5. Numpy
#### 2.4.6. Matplotlib

## 3. Resources
// tutorial point

// div into python

// teamtreehouse

// codeschool

// leetcode
