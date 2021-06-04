# Python Doc- Basic

<!--
1.2. Notation
https://docs.python.org/3/reference/introduction.html#notation

https://docs.python.org/3/tutorial/controlflow.html#intermezzo-coding-style

http://akaptur.com/blog/2014/03/16/reading-ebnf/ | Reading EBNF - Allison Kaptur
https://en.wikipedia.org/wiki/Extended_Backus%E2%80%93Naur_form | Extended Backus–Naur form - Wikipedia
https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form	
https://www.iso.org/standard/26153.html | ISO/IEC 14977:1996 - Information technology -- Syntactic metalanguage -- Extended BNF
https://standards.iso.org/ittf/PubliclyAvailableStandards/s026153_ISO_IEC_14977_1996(E).zip | Publicly Available Standards
-->

## Kenneth Reitz Advice to Me 

* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

<!--
## Lexical Analysis

https://en.wikipedia.org/wiki/Lexical_analysis | Lexical analysis - Wikipedia

Lexical Analysis
https://docs.python.org/3/reference/lexical_analysis.html#logical-lines
https://docs.python.org/3/reference/lexical_analysis.html#physical-lines
https://docs.python.org/3/reference/lexical_analysis.html#comments
https://docs.python.org/3/reference/lexical_analysis.html#encoding-declarations
https://docs.python.org/3/reference/lexical_analysis.html#explicit-line-joining
https://docs.python.org/3/reference/lexical_analysis.html#implicit-line-joining
https://docs.python.org/3/reference/lexical_analysis.html#blank-lines
https://docs.python.org/3/reference/lexical_analysis.html#indentation
https://docs.python.org/3/reference/lexical_analysis.html#whitespace-between-tokens

https://docs.python.org/3/reference/lexical_analysis.html#line-structure
https://docs.python.org/3/reference/lexical_analysis.html#other-tokens
https://docs.python.org/3/reference/lexical_analysis.html#identifiers

## Method Resolution Order

Method Resolution Order
* [C3 Linearization Wikipedia](https://en.wikipedia.org/wiki/C3_linearization)
* [Multiple Inheritance Wikipedia](https://en.wikipedia.org/wiki/Multiple_inheritance)
* [The Python 2.3 Method Resolution Order](https://www.python.org/download/releases/2.3/mro)

MRO
http://python-history.blogspot.com/2010/06/method-resolution-order.html
https://docs.python.org/3/library/stdtypes.html#class.__mro__

New Style
https://www.python.org/doc/newstyle/ | New-style Classes | Python.org
https://docs.python.org/2/glossary.html#term-new-style-class | Glossary — Python 2.7.16 documentation
http://python-history.blogspot.com/2010/06/inside-story-on-new-style-classes.html

## Data Model

https://docs.python.org/3/reference/datamodel.html#implementing-descriptors
https://docs.python.org/3/reference/datamodel.html#invoking-descriptors
https://docs.python.org/3/reference/datamodel.html#slots
https://docs.python.org/3/reference/datamodel.html#customizing-class-creation
https://docs.python.org/3/reference/datamodel.html#metaclasses
https://docs.python.org/3/reference/datamodel.html#resolving-mro-entries
https://docs.python.org/3/reference/datamodel.html#determining-the-appropriate-metaclass
https://docs.python.org/3/reference/datamodel.html#preparing-the-class-namespace
https://docs.python.org/3/reference/datamodel.html#executing-the-class-body
https://docs.python.org/3/reference/datamodel.html#creating-the-class-object
https://docs.python.org/3/reference/datamodel.html#metaclass-example
https://docs.python.org/3/reference/datamodel.html#customizing-instance-and-subclass-checks

https://docs.python.org/3/reference/datamodel.html#emulating-generic-types
https://docs.python.org/3/reference/datamodel.html#emulating-callable-objects
https://docs.python.org/3/reference/datamodel.html#emulating-container-types
https://docs.python.org/3/reference/datamodel.html#emulating-numeric-types
https://docs.python.org/3/reference/datamodel.html#with-statement-context-managers
https://docs.python.org/3/reference/datamodel.html#special-method-lookup


## Standard

https://docs.python.org/3/reference/lexical_analysis.html

https://docs.python.org/3/library/stdtypes.html#internal-objects
https://docs.python.org/3/reference/datamodel.html#the-standard-type-hierarchy

https://docs.python.org/3/library/stdtypes.html#code-objects
https://docs.python.org/3/library/stdtypes.html#type-objects

https://docs.python.org/3/reference/datamodel.html#types
https://docs.python.org/3/library/stdtypes.html#built-in-types
https://docs.python.org/3/library/stdtypes.html#other-built-in-types


https://docs.python.org/3/library/functions.html | Built-in Functions — Python 3.8.3 documentation

https://docs.python.org/3/library/builtins.html
https://docs.python.org/3/library/constants.html#built-in-consts


https://docs.python.org/3/reference/expressions.html
https://docs.python.org/3/reference/expressions.html#expression-lists
https://docs.python.org/3/reference/simple_stmts.html#expression-statements

https://docs.python.org/3/tutorial/modules.html#standard-modules

3.1. Constants added by the site module

Special attribute and method names
https://docs.python.org/3/glossary.html#term-special-method
https://docs.python.org/3/reference/datamodel.html#special-method-names
"Some of these are not reported by the dir() built-in function."
https://docs.python.org/3/library/stdtypes.html#special-attributes
https://docs.python.org/3/reference/lexical_analysis.html#reserved-classes-of-identifiers


https://docs.python.org/3/glossary.html#term-decorator
https://docs.python.org/3/glossary.html#term-descriptor
https://docs.python.org/3/reference/datamodel.html#descriptors

dot notation
https://docs.python.org/3/library/stdtypes.html#modules

## Classes, Objects, Functions, Methods, Attributes

https://docs.python.org/3/glossary.html#term-new-style-class
https://docs.python.org/3/glossary.html#term-object
https://docs.python.org/3/reference/datamodel.html#objects-values-and-types
https://docs.python.org/3/reference/datamodel.html#objects
https://docs.python.org/3/reference/datamodel.html#basic-customization

https://docs.python.org/3/reference/datamodel.html#customizing-attribute-access
https://docs.python.org/3/reference/datamodel.html#customizing-module-attribute-access

https://docs.python.org/3/glossary.html#term-class
https://docs.python.org/3/tutorial/classes.html#classes
https://docs.python.org/3/reference/compound_stmts.html#class-definitions

https://docs.python.org/3/tutorial/classes.html#a-first-look-at-classes
https://docs.python.org/3/tutorial/classes.html#class-definition-syntax

https://docs.python.org/3/library/stdtypes.html#classes-and-class-instances

Important!
https://docs.python.org/3/tutorial/classes.html#class-objects
https://docs.python.org/3/tutorial/classes.html#instance-objects
https://docs.python.org/3/tutorial/classes.html#method-objects

https://docs.python.org/3/tutorial/classes.html#random-remarks
https://docs.python.org/3/tutorial/classes.html#inheritance
https://docs.python.org/3/tutorial/classes.html#multiple-inheritance

https://docs.python.org/3/tutorial/classes.html#class-and-instance-variables
https://docs.python.org/3/tutorial/classes.html#private-variables

Function Objects
https://docs.python.org/3/library/stdtypes.html#functions

Calls!
https://docs.python.org/3/reference/expressions.html#calls

"A series of statements which returns some value to a caller. It can also be passed zero or more arguments which may be used in the execution of the body. See also parameter, method, and the Function definitions section."
https://stackoverflow.com/questions/53485906/what-exactly-is-a-caller-in-python
https://docs.python.org/3/glossary.html#term-function

https://docs.python.org/3/reference/compound_stmts.html#function-definitions

https://docs.python.org/3/tutorial/controlflow.html#defining-functions
https://docs.python.org/3/tutorial/controlflow.html#more-on-defining-functions

"There are really two flavors of function objects: built-in functions and user-defined functions. Both support the same operation (to call the function), but the implementation is different, hence the different object types."
https://docs.python.org/3/library/stdtypes.html#functions

Look again
https://docs.python.org/3/glossary.html#term-generic-function

Usually used for type hints
https://docs.python.org/3/tutorial/controlflow.html#function-annotations

"Methods are functions that are called using the attribute notation. There are two flavors: built-in methods (such as append() on lists) and class instance methods. Built-in methods are described with the types that support them.
If you access a method (a function defined in a class namespace) through an instance, you get a special object: a bound method (also called instance method) object."
https://docs.python.org/3/library/stdtypes.html#methods

"A function which is defined inside a class body. If called as an attribute of an instance of that class, the method will get the instance object as its first argument (which is usually called self). See function and nested scope."
https://docs.python.org/3/glossary.html#term-method

https://docs.python.org/3/glossary.html#term-attribute

https://docs.python.org/3/reference/expressions.html#attribute-references

## Mapping Operators to Functions

Mapping Operators to Functions

"For backward compatibility, many of these have a variant with the double underscores kept."
https://docs.python.org/3/library/operator.html
https://docs.python.org/3/library/operator.html#module-operator
https://docs.python.org/3/library/operator.html#mapping-operators-to-functions
https://docs.python.org/3/library/operator.html#inplace-operators

## Arguments and Parameters

Difference between kwargs and zip

Information passed to a function is called an argument
information received by a function is called a parameter.

Interpreter
2.1.1. Argument Passing
https://docs.python.org/3/tutorial/interpreter.html#argument-passing
sys.argv[0]

4.7.1. Default Argument Values
https://docs.python.org/3/tutorial/controlflow.html#default-argument-values
4.7.2. Keyword Arguments
https://docs.python.org/3/tutorial/controlflow.html#keyword-arguments
4.7.3. Arbitrary Argument Lists
https://docs.python.org/3/tutorial/controlflow.html#arbitrary-argument-lists
4.7.4. Unpacking Argument Lists
https://docs.python.org/3/tutorial/controlflow.html#unpacking-argument-lists

positional, keyword
https://docs.python.org/3/glossary.html#term-argument
https://docs.python.org/3/glossary.html#term-parameter

## Scope

Scope
* [Scope Wikipedia](https://en.wikipedia.org/wiki/Scope_(computer_science))

https://en.wikipedia.org/wiki/Scope_(computer_science)#Lexical_scope_vs._dynamic_scope

7.12. The global statement
https://docs.python.org/3/reference/simple_stmts.html#the-global-statement
7.13. The nonlocal statement
https://docs.python.org/3/reference/simple_stmts.html#the-nonlocal-statement

Classes
9.1. A Word About Names and Objects
https://docs.python.org/3/tutorial/classes.html#a-word-about-names-and-objects
9.2. Python Scopes and Namespaces
https://docs.python.org/3/tutorial/classes.html#python-scopes-and-namespaces
9.2.1. Scopes and Namespaces Example
https://docs.python.org/3/tutorial/classes.html#scopes-and-namespaces-example

https://docs.python.org/3/glossary.html#term-nested-scope
-->

## Enter and Exit the Python Interactive Shell

Enter the Python interactive shell

```python
$ python
```

You will know you are in the Python interactive shell when you see the Python prompt.

```python
>>>
```

The default prompt of Python interactive shell when entering code for an indented code block

```python
...
```

Exit the Python interactive shell

```python
>>> exit()
```

## Python Version and Run a Program

Import a module

```python
>>> import <module>
```

Python version

```python
>>> import sys
>>> print(sys.version)
```

<!--
https://docs.python.org/3/library/sys.html#sys.version
-->

Run program

```bash
$ python program.py
```

Alternatively

```bash
$ python directory/program.py
```

## Help

<!--
https://docs.python.org/3/library/functions.html#help
-->

Enter the Python help utility

```python
>>> help()
```

Obtain help for a specific object

```python
>>> help(object)
```

Exit the Python help utility

```python
>>> q
```

## General

The Zen of Python by Tim Peters
* [The Zen of Python by Tim Peters](https://www.python.org/dev/peps/pep-0020)

The Zen of Python, by Tim Peters

```bash
>>> import this
```

Simple is Better than Complex
* if two solutions work, but one is simple, choose the simple one

## Python and Django Style

### General Style Rules

* Readability counts
* Use four spaces per indentation level.
* Keep your lines to 79 characters or fewer.
* Use single blank lines to group parts of your program visually.

### Comments

Comment- One Line

```python
# Comment
```

Alternatively

```python
print("Hello world!") # Comment
```

Pound sign will print within string

```python
print("#1")
```

Docstring- (multi-line, dumb quotes versus smart quotes)

```python
"""Write docstrings for ALL public classes, functions and methods.
First line of a docstring is short and next to the quotes.
Closing quotes are on their own line
"""
```

## Python and Django Style
  
### Hacks for Understanding Code

* write comments explaining what code does and how it works
* read the code backwards, so not attaching meaning to code
* read your code out loud

### Whitespace

Whitespace
* nonprinting character

Whitespace Examples
* spaces
* tabs
* end-of-line symbols

String escape

```python
\t
\n (one line)
\n\n (two lines)
```

## Statements Versus Expressions

* Simple statement, expression statement, assignment statement
* A statement is executed
* An expression is evaluated
* An assignment statement assigns a value to a variable

### Assignment Statement

Variable

```python
>>> <variable> = x
>>> <variable>
x
```

### Three Types of Assignment

```python
>>> my_string = "Hello World"                # right hand side is a simple expression
>>> another_string = my_string               # right hand side is another variable
>>> another_string = another_string + "!"    # right hand side is an operation
```

## Variables and Strings

Hello World

```python
>>> print("Hello World")
```

Hello World stored in variable

```python
>>> greeting = "Hello World"
>>> print(greeting)
Hello World
```

## Print and Return Statements

Parentheses are not needed in Python 2. Print is a function in Python 3, which is why parentheses are needed.

```print()``` 

Store data in a variable, then print it

```python
variable = <variable>

print(variable)
``` 
  
```return()```

7.6. The return statement
https://docs.python.org/3/reference/simple_stmts.html#the-return-statement

## Naming Conventions

Variable Names

* Can start with a letter or an underscore, but not with a number.
* Can only contain letters, numbers, and underscores. 
* Spaces not allowed
* Do not use Python keywords and function names as variable names
* Should be short but descriptive.
* Lowercase letter l and the uppercase letter O could be confused with the numbers 1 and 0.

Anti-Pattern
```python
l as 1
O as 0
```

<!--
anti-pattern
O = 2
I = 3
-->

### Common Naming Conventions

<!--
case sensitivity
underscore
starting underscore
-->

```python
CapWords
snake_case
MACRO_CASE
camelCase
```

snake_case

<!--
https://en.wikipedia.org/wiki/Snake_case | Snake case - Wikipedia
-->

```python
module_name
package_name
function_name
method_name
variable_name
```

CapWords

```python
ClassName
ExceptionName
```

MACRO_CASE

```python
CONSTANT_NAME
```

## Example Module File

Attribution
* [RichardBronosky PEP8 Cheatsheet](https://gist.github.com/RichardBronosky/454964087739a449da04)

```python
"""This module's multi-line docstring.
Paragraphs are separated with blank lines.
Lines conform to 79 character rule.
1234567891011121314151617181920212223242526272829303132333435363738394041424344
"""


import standard_library  # STD lib imports first, alphabetical

import third_party_library  # 3rd party library imports next, alphabetical

import local_library  # local library imports last
import library_one, library_two  # anti-pattern
from library import *  # anti-pattern, including pyflake problem # noqa
# Using # noqa in the line above avoids flake8 warnings about line length!


# 2 empty lines between top-level functions + classes
def new_function(): # snake_case
    """Description"""
    action
    

class NewClass(object): #CapWords
    """Description"""

    def __init__(self, attribute):
        self.attribute = attribute

    # 1 empty line between in-class definitions
    def new_method(self): # snake_class, always use self as first argument
        """Description"""
        action

    @classmethod
    def new_class_method(cls):
        """Description"""
        action

# Newline at end of file
```

## Class or Function Syntax

<!--
Super
https://docs.python.org/2/library/functions.html#super | 2. Built-in Functions — Python 2.7.16 documentation
-->

Define a function or class

```python
def function():
class Class:
```

Function statement

```python
def function():
    """Description"""
    action

function()
```

Class statement

```python
class Class:
    """Description"""
    def __init__(self, attribute):
        self.attribute = attribute
 
    def method(self):
        action
```

## Modules

* Store functions in a seperate file (called a module)
* Store module in same directory as your main program
* Import the functions you need into the file containing your main program

## UTF-8 and ASCII encodings

For special language characters, put this at top of file to avoid ASCII encodings errors

```python
# -*- coding: utf-8 -*-
```

https://en.wikipedia.org/wiki/ASCII
https://en.wikipedia.org/wiki/Unicode
https://en.wikipedia.org/wiki/UTF-8

## Import

Import an entire module (every function in the module is available in the program file)

```python
import module

module.function()
```

Selective import (only imported function is available in the program file)

```python
from module import function

function()
```

Give a module an alias

```python
import module as alias

alias.function()
```

Give a function an alias

```python
from module import function as alias

alias()
```

Import all functions from a module (anti-pattern)

```python
from module import *

function()
```


## Python Code Block Examples

<!--
See also: exceptions and pass statement
-->

Python structuring
* colons
* indentation (a.k.a. nesting)

## Colons

Python structures that end blocks with a colon (:)
* function statement
* class statement
* if-elif-else statement (branching)
* for-else statement (loop)
* while-else statement (loop)
* with statement

* try-except-else statement

Python structures that don't end blocks with a colon (:)
* range/list comprehension functions
       
## Control Flow Statement Examples

### Control Flow and Sequences

for statement and sequence

```python
for item in items:
    action
```

while statement and sequence

```python
while item in items:
    action
```


try-except-else statement

```python
```
  	 
	
## Python and Django Control Flow

3 Types of Control structures
* true or false branch evaluation (if statement)
* repeating while a condition is True (while loop)
* sequential processing (for loop)

https://docs.python.org/3/tutorial/controlflow.html | 4. More Control Flow Tools — Python 3.8.2 documentation


## Compound or complex statements

```python
header: 
   suite
header:
   suite 
header:
   suite
```


## if Statements

Conditional test
* evaluates statements one by one until one is found to be True (Boolean operation)
* that statement is executed (no other part of if statement is executed or evaluated)
* if all statements are False, else statement, if present, is executed

Number of statements
* can have as many elif statement as needed
* else statement is always optional

https://docs.python.org/3/tutorial/controlflow.html#if-statements
https://docs.python.org/3/reference/compound_stmts.html#the-if-statement

if statement

```python
if condition true:
    action
```

if-else statement

```python
if condition true:
    action
else:
    action
```

if-elif-else statement

```python
if condition true:
    action
elif condition true:
    action
else:
    action
```

## while Statements

Conditional test
* repeats a block of code while the condition is True (Boolean operation)
* if the condition does not become False, the loop runs indefinitely as an infinite loop.
* if the while statements becomes False, the else statement, if present, is executed

https://docs.python.org/3/reference/compound_stmts.html#the-while-statement | 8. Compound statements — Python 3.8.2 documentation

while statement

```python
while condition true:
    action
```

while-else statement

```python
while condition true:
    action
else:
    action
```

## for Statements

What it does
* iterates over the items of any sequence in the order in which they appear in the sequence
* when all iteration has been completed, the else statement, if present, is executed

https://docs.python.org/3/tutorial/controlflow.html#for-statements
https://docs.python.org/3/reference/compound_stmts.html#the-for-statement

for-else statement

```python
for condition:
    action
else:
    action
```


## Common Built-In Data Type and Data Structure Conversions (Casting)

Return an integer object constructed from a number or string x, or return 0 if no arguments are given. 

```int()```

Return a floating point number constructed from a number or string x.

```float()```

Return a Boolean value, i.e. one of True or False. 

```bool()```

Return a complex number with the value real + imag*1j or convert a string or number to a complex number. 

```complex()```	

Return a str version of object. 

```str()```
    
Rather than being a function, list is actually a mutable sequence type.

```list()```

Create a new dictionary. 

```dict()```

Rather than being a function, tuple is actually an immutable sequence type

```tuple()```

Rather than being a function, range is actually an immutable sequence type, 

```range()```

Return a new set object, optionally with elements taken from iterable. 

```set()```


## Object-Oriented Programming

### Built-In Object Methods

Return a new featureless object. object is a base for all classes. It has the methods that are common to all instances of Python classes. 

```object()```

Return a proxy object that delegates method calls to a parent or sibling class of type. This is useful for accessing inherited methods that have been overridden in a class. 

```super()```

https://docs.python.org/3/library/functions.html#super | 2. Built-in Functions — Python 3.6.3 documentation

### Class and Object `Is` Functions

Return true if the object argument is an instance of the classinfo argument, or of a (direct, indirect or virtual) subclass thereof. 

```isinstance()```

https://docs.python.org/3/library/numbers.html#implementing-the-arithmetic-operations

Return true if class is a subclass (direct, indirect or virtual) of classinfo. 

```issubclass()```

### Attributes and Properties

Object attributes

```delattr()```
```getattr()```
```__getattribute__()```
```hasattr()```
```setattr()```

https://en.wikipedia.org/wiki/Mutator_method
https://docs.python.org/3/library/functions.html#setattr
https://docs.python.org/3/library/functions.html#getattr
https://docs.python.org/3/library/functions.html#hasattr
https://docs.python.org/3/library/functions.html#delattr
https://en.wikipedia.org/wiki/Property_(programming)

Return a property attribute.
```property()```


## dir() and builtins

Without arguments, return the list of names in the current local scope. With an argument, attempt to return a list of valid attributes for that object.

```dir()```

dir() does not list the names of built-in functions and variables. Tthey are defined in the standard module builtins.

```python
>>> import builtins
>>> dir(builtins)
```

6.3. The dir() Function
https://docs.python.org/3/tutorial/modules.html#the-dir-function
https://docs.python.org/3/library/functions.html#dir

Return True if the object argument appears callable, False if not. 
```callable()```


## Type, Identity, Hash Value

With one argument, return the type of an object. 

```type()```

https://docs.python.org/3/library/functions.html#type

Return the “identity” of an object. 

```id()```

https://docs.python.org/3/library/functions.html#id

Return the hash value of the object (if it has one). Hash values are integers. 

```hash()```

https://docs.python.org/3/library/functions.html#hash
https://docs.python.org/3/library/stdtypes.html#hashing-of-numeric-types

## Print Data Structure and Ascertain Data Type

```python
print(data_structure)
print(type(data_structure))
```

## Built-In Functions- Formatting and Printing

Convert a value to a “formatted” representation, as controlled by format_spec. 
```format()```

Return a string containing a printable representation of an object. 
```repr()```

## Built-In Functions- Numbers

Take two (non complex) numbers as arguments and return a pair of numbers consisting of their quotient and remainder when using integer division. 
```divmod()```

Return x to the power y; if z is present, return x to the power y, modulo z

```pow()```

Return number rounded to ndigits precision after the decimal point. 
```round()```

Return the absolute value of a number. The argument may be an integer or a floating point number. If the argument is a complex number, its magnitude is returned.
```abs()```

## Built-In Functions- Data Sequence/Iterator- Addressed in Sequences Section

Return the largest item in an iterable or the largest of two or more arguments.

```max()```

Return the smallest item in an iterable or the smallest of two or more arguments.

```min()```

## Built-In Functions- Length and Sum- Addressed in Sequences Section

Return the length (the number of items) of an object. The argument may be a sequence (such as a string, bytes, tuple, list, or range) or a collection (such as a dictionary, set, or frozen set).

```len()```

Sums start and the items of an iterable from left to right and returns the total. start defaults to 0. The iterable’s items are normally numbers, and the start value is not allowed to be a string. The preferred, fast way to concatenate a sequence of strings is by calling ''.join(sequence). To add floating point values with extended precision, see math.fsum(). To concatenate a series of iterables, consider using itertools.chain().

```sum()```

## Less Common Built-In Function

### Built-In Functions- Modules

This function is invoked by the import statement. It can be replaced (by importing the builtins module and assigning to builtins.__import__) in order to change semantics of the import statement, but doing so is strongly discouraged
```__import__()```

### Built-In Functions- Scope

Return a dictionary representing the current global symbol table. 
```globals()```

Update and return a dictionary representing the current local symbol table. 
```locals()```

### Data Type and Data Structure Conversions (Casting)

Return a new frozenset object, optionally with elements taken from iterable. frozenset is a built-in class. 

```frozenset()```

Return a new “bytes” object, which is an immutable sequence of integers in the range 0 <= x < 256. 

```bytes()```

Return a new array of bytes. The bytearray class is a mutable sequence of integers in the range 0 <= x < 256. 

```bytearray()```

Return a “memory view” object created from the given argument. 

```memoryview()```

### Built-In Functions- ```eval()``` and ```exec()```

```eval()```

This function supports dynamic execution of Python code. 
```exec()```

Compile the source into a code or AST object. 
```compile()```

### Various	

Return the __dict__ attribute for a module, class, instance, or any other object with a __dict__ attribute.
```vars()```

Convert an integer number to a binary string prefixed with “0b”. 
```bin()```

As repr(), return a string containing a printable representation of an object, but escape the non-ASCII characters in the string returned by repr() 
```ascii()```

Return the string representing a character whose Unicode code point is the integer i. 
```chr()```

Convert an integer number to a lowercase hexadecimal string prefixed with “0x”. 
```hex()```

Convert an integer number to an octal string prefixed with “0o”. 
```oct()```

Given a string representing one Unicode character, return an integer representing the Unicode code point of that character. 
```ord()```


## Operators and Delimiters

2.5. Operators
https://docs.python.org/3/reference/lexical_analysis.html#operators
2.6. Delimiters
https://docs.python.org/3/reference/lexical_analysis.html#delimiters

## Evaluation Order/Operator Precedence

6.15. Evaluation order
https://docs.python.org/3/reference/expressions.html#evaluation-order
6.16. Operator precedence
https://docs.python.org/3/reference/expressions.html#operator-precedence

6.1. Arithmetic conversions
https://docs.python.org/3/reference/expressions.html#arithmetic-conversions

<!--
## Operators in Order of Operation
-->

### PEDMAS

* Generally speaking Python follows PEDMAS (Parentheses, Exponents, Multiplication, Division, Addition, Subtraction)

### Parenthesis

```()```

### Exponentiation

```**```

6.5. The power operator
https://docs.python.org/3/reference/expressions.html#the-power-operator

### Unary Operators: Plus, Minus, Invert (interact with a single variable or expression)

```+ - ~```

6.6. Unary arithmetic and bitwise operations
https://docs.python.org/3/reference/expressions.html#unary-arithmetic-and-bitwise-operations

### Multiplication, Floating Point Division, Floor Division, Modulo/Modulus/Remainder 

```* / // %```

Python 2 and 3- different behavior when mixing division by integers and floats

https://docs.python.org/3/reference/lexical_analysis.html#floating-point-literals
https://docs.python.org/3/tutorial/floatingpoint.html#floating-point-arithmetic-issues-and-limitations

11.8. Decimal Floating Point Arithmetic
https://docs.python.org/3/tutorial/stdlib2.html#decimal-floating-point-arithmetic

15. Floating Point Arithmetic: Issues and Limitations
https://docs.python.org/3/tutorial/floatingpoint.html
15.1. Representation Error
https://docs.python.org/3/tutorial/floatingpoint.html#representation-error

### Addition and Subtraction

```+ -```

### Bitwise

* Right and left bitwise shift (>> <<)
* Bitwise AND (&)
* Bitwise exclusive OR and standard OR (^|)

6.7. Binary arithmetic operations
https://docs.python.org/3/reference/expressions.html#binary-arithmetic-operations
6.8. Shifting operations
https://docs.python.org/3/reference/expressions.html#shifting-operations
6.9. Binary bitwise operations
https://docs.python.org/3/reference/expressions.html#binary-bitwise-operations

https://docs.python.org/3/library/stdtypes.html#bitwise-operations-on-integer-types
https://docs.python.org/3/library/stdtypes.html#bytes-and-bytearray-operations

### Comparison Operators: Greater Than, Greater Than or Equal, Less Than, Less Than or Equal

```> >= < <=```

### Equality Operators: Equivalent, Not equivalent

```== !=```

### Assignment Operators

Assignment 

```=```

Addition, Subtraction

```+= -=```

Multiplication, Floating Point Division, Floor Division, Modulo/Remainder

```*= /= //= %=```

Exponentiation

```**=```

7.2. Assignment statements	
https://docs.python.org/3/reference/simple_stmts.html#assignment-statements

https://docs.python.org/3/reference/simple_stmts.html#augmented-assignment-statements
https://docs.python.org/3/reference/simple_stmts.html#annotated-assignment-statements

## Reserved Keywords

<!--
(See Python Crash Course “Python Keywords and Built-in Functions” on page 489.)

Keywords!
https://docs.python.org/3/reference/lexical_analysis.html#keywords
-->

```python
class
def
```

```python
try
except
raise
assert
```

```python
for
while
else
if
elif
with
```

```python
continue
pass
break
```

Boolean

```python
True
False
```

```python
and
not
or
```

```python
import
from
```

```python
global
nonlocal
```

```python
async
await
```

```python
None
as
del
finally
in
is
lambda
return
yield
```

## Input

Accept input from a user. Input is stored as a string.

```python
<variable> = input()
print(<variable>)
```

Example

```python
name = input("Name? ")
print("Hello, " + name + "!")
```

Convert input from string into integer

```python
age = input("Age? ")
age = int(age)
```
