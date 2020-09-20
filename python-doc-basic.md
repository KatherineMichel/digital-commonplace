# Python Doc- Basic

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

### Identity Operators (```is```/```is not```)

True if same object/identify (id)

```is``` 

True if different object/identity (id)

```is not```

https://docs.python.org/3/reference/expressions.html#is
https://docs.python.org/3/reference/expressions.html#is-not

### Membership Operators

```
in
not in
```

(built-in sequences, set types, and dictionaries)

https://docs.python.org/3/reference/expressions.html#membership-test-operations
https://docs.python.org/3/reference/expressions.html#in
https://docs.python.org/3/reference/expressions.html#not-in

### Logical Operators

```
and
or
not
```

### Boolean Values (See also: Logical Operators)

```python
True
False
```

Assigning Boolean Values ("boolean values are often used to keep track of certain conditions within a program")

```python
true_value = True
false_value = False
```

6.11. Boolean operations
https://docs.python.org/3/reference/expressions.html#boolean-operations

https://docs.python.org/3/library/stdtypes.html#boolean-values

4.2. Boolean Operations — and, or, not
https://docs.python.org/3/library/stdtypes.html#boolean-operations-and-or-not

## Conditions, Comparisons

5.7. More on Conditions
https://docs.python.org/3/tutorial/datastructures.html#more-on-conditions

"Chapter Objects, values and types states that objects have a value (in addition to type and identity)."
https://docs.python.org/3/reference/expressions.html#value-comparisons

6.10. Comparisons
https://docs.python.org/3/reference/expressions.html#comparisons

4.3. Comparisons
https://docs.python.org/3/library/stdtypes.html#comparisons

4.1. Truth Value Testing
https://docs.python.org/3/library/stdtypes.html#truth-value-testing

“ternary operator” have the lowest priority of all Python operations
6.12. Conditional expressions
https://docs.python.org/3/reference/expressions.html#conditional-expressions

5.8. Comparing Sequences and Other Types
https://docs.python.org/3/tutorial/datastructures.html#comparing-sequences-and-other-types

## Negation (Null Object, ```None```, ```NotImplemented```)

https://docs.python.org/3/reference/datamodel.html#the-standard-type-hierarchy

https://docs.python.org/3/library/stdtypes.html#the-null-object
https://docs.python.org/3/library/stdtypes.html#the-notimplemented-object

None
https://docs.python.org/3/library/constants.html#None

NotImplemented

## Built-In Data Type and Data Structure Conversions (Casting)

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

Return a new frozenset object, optionally with elements taken from iterable. frozenset is a built-in class. 

```frozenset()```

Return a new “bytes” object, which is an immutable sequence of integers in the range 0 <= x < 256. 

```bytes()```

Return a new array of bytes. The bytearray class is a mutable sequence of integers in the range 0 <= x < 256. 

```bytearray()```

Return a “memory view” object created from the given argument. 

```memoryview()```

## Less Common Built-in Functions		

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
