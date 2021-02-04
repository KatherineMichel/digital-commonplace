# Python Doc- Basic

## Kenneth Reitz Advice to Me 

* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

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

## Print Data Structure and Ascertain Data Type

```python
print(data_structure)
print(type(data_structure))
```


## Math

3.2. First Steps Towards Programming
https://docs.python.org/3/tutorial/introduction.html#first-steps-towards-programming

3.1. Using Python as a Calculator
https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator
3.1.1. Numbers
https://docs.python.org/3/tutorial/introduction.html#numbers

10.6. Mathematics
https://docs.python.org/3/tutorial/stdlib.html#mathematics

9.7.4. Exceptions
exception statistics.StatisticsError


9. Numeric and Mathematical Modules
https://docs.python.org/3/library/numeric.html
9.1. numbers — Numeric abstract base classes
https://docs.python.org/3/library/numbers.html
9.2. math — Mathematical functions
https://docs.python.org/3/library/math.html
9.3. cmath — Mathematical functions for complex numbers
https://docs.python.org/3/library/cmath.html
9.4. decimal — Decimal fixed point and floating point arithmetic
https://docs.python.org/3/library/decimal.html
9.5. fractions — Rational numbers
https://docs.python.org/3/library/fractions.html
9.6. random — Generate pseudo-random numbers
https://docs.python.org/3/library/random.html
9.7. statistics — Mathematical statistics functions
https://docs.python.org/3/library/statistics.html



https://docs.python.org/3/library/numeric.html#numeric-and-mathematical-modules

https://docs.python.org/3/library/numbers.html#module-numbers
https://docs.python.org/3/library/numbers.html#the-numeric-tower
https://docs.python.org/3/library/numbers.html#notes-for-type-implementors
https://docs.python.org/3/library/numbers.html#adding-more-numeric-abcs
https://docs.python.org/3/library/numbers.html#implementing-the-arithmetic-operations

9.2. math — Mathematical functions
https://docs.python.org/3/library/math.html#module-math
https://docs.python.org/3/library/math.html#number-theoretic-and-representation-functions
https://docs.python.org/3/library/math.html#power-and-logarithmic-functions
https://docs.python.org/3/library/math.html#trigonometric-functions
https://docs.python.org/3/library/math.html#angular-conversion
https://docs.python.org/3/library/math.html#hyperbolic-functions
https://docs.python.org/3/library/math.html#special-functions
https://docs.python.org/3/library/math.html#constants

https://docs.python.org/3/library/cmath.html#module-cmath
https://docs.python.org/3/library/cmath.html#conversions-to-and-from-polar-coordinates
https://docs.python.org/3/library/cmath.html#power-and-logarithmic-functions
https://docs.python.org/3/library/cmath.html#trigonometric-functions
https://docs.python.org/3/library/cmath.html#hyperbolic-functions
https://docs.python.org/3/library/cmath.html#classification-functions
https://docs.python.org/3/library/cmath.html#constants

9.4. decimal — Decimal fixed point and floating point arithmetic
https://docs.python.org/3/library/decimal.html#module-decimal
https://docs.python.org/3/library/decimal.html#quick-start-tutorial
https://docs.python.org/3/library/decimal.html#decimal-objects
https://docs.python.org/3/library/decimal.html#logical-operands
https://docs.python.org/3/library/decimal.html#context-objects
https://docs.python.org/3/library/decimal.html#constants
https://docs.python.org/3/library/decimal.html#rounding-modes
https://docs.python.org/3/library/decimal.html#signals
https://docs.python.org/3/library/decimal.html#floating-point-notes
https://docs.python.org/3/library/decimal.html#mitigating-round-off-error-with-increased-precision
https://docs.python.org/3/library/decimal.html#special-values
https://docs.python.org/3/library/decimal.html#working-with-threads
https://docs.python.org/3/library/decimal.html#recipes
https://docs.python.org/3/library/decimal.html#decimal-faq

9.5. fractions — Rational numbers
https://docs.python.org/3/library/fractions.html#module-fractions

9.6. random — Generate pseudo-random numbers
See also section
https://docs.python.org/3/library/random.html#module-random
https://docs.python.org/3/library/random.html#bookkeeping-functions
https://docs.python.org/3/library/random.html#functions-for-integers
https://docs.python.org/3/library/random.html#functions-for-sequences
https://docs.python.org/3/library/random.html#real-valued-distributions
https://docs.python.org/3/library/random.html#alternative-generator
https://docs.python.org/3/library/random.html#notes-on-reproducibility
tutorials
https://docs.python.org/3/library/random.html#examples-and-recipes

https://docs.python.org/3/library/statistics.html#module-statistics
https://docs.python.org/3/library/statistics.html#averages-and-measures-of-central-location
https://docs.python.org/3/library/statistics.html#measures-of-spread
https://docs.python.org/3/library/statistics.html#function-details
https://docs.python.org/3/library/statistics.html#exceptions

9.3. cmath — Mathematical functions for complex numbers


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
