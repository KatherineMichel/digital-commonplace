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

## Important Data Questions

https://docs.python.org/3/reference/expressions.html#atoms
https://docs.python.org/3/reference/expressions.html#atom-identifiers
https://docs.python.org/3/reference/expressions.html#literals
https://docs.python.org/3/reference/expressions.html#parenthesized-forms

Dictionaries, lists, sets
https://docs.python.org/3/reference/expressions.html#displays-for-lists-sets-and-dictionaries
https://docs.python.org/3/reference/expressions.html#list-displays
https://docs.python.org/3/reference/expressions.html#set-displays
https://docs.python.org/3/reference/expressions.html#dictionary-displays

https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects

Data Structures
* Is order important?
* Does your data need to shrink or grow?

## Data Types

Data Types
* [Data Type Wikipedia](https://en.wikipedia.org/wiki/Data_type) 

https://docs.python.org/3/library/datatypes.html

https://docs.python.org/3/reference/lexical_analysis.html#literals
Escape sequence chart
https://docs.python.org/3/reference/lexical_analysis.html#string-and-bytes-literals
https://docs.python.org/3/reference/lexical_analysis.html#numeric-literals
https://docs.python.org/3/reference/lexical_analysis.html#integer-literals
https://docs.python.org/3/reference/lexical_analysis.html#imaginary-literals

## Mutability

* Mutable- individual item can be changed
* Immutable- individual item cannot be changed
* Sequence- 
* Non-Sequence-
* Iterable-

After change
* mutable data structure will have same id
* immutable data structure will have new id

## Data Types and Structures- Primitives 

Methods
https://docs.python.org/3/library/stdtypes.html#additional-methods-on-integer-types
https://docs.python.org/3/library/stdtypes.html#additional-methods-on-float

Primitive (a.k.a. atomic data types)
* integer (numeric)
* float (numeric)
* string (sequence, "This is a string.", 'This is also a string.')
* boolean
* complex number (numeric)

## Data Types and Structures- User Defined

User Defined
* list []
* tuple () or (item,) (singleton)
* range
* set {}
* dictionary {}

## Data Types Categorized by Mutable or Immutable, Sequence or Non-Sequence

<!--
Sequence/looping
lists: item
strings: character
-->

Immutable Sequence Types- Common
* string (text sequence type, primitive)

Mutable Sequence Types- Common
* list

Mutable Non-Sequence Types
* dictionary (built-in mapping/hash table)
* set

Set Types
* set
* frozenset (immutable and hashable)

Immutable Sequence Types- Less Common
* tuple

Sequence Types
* range (immutable)

Other Data Structures
* hashes

## Linear and Non-Linear

Linear Data Structures (left to right, top to bottom)
* list, stack, queue, deque, array are examples

List (Sequence) Linear and Non-Linear Implementations
* Linear: stack and queue
* Non-Linear: graph and tree

<!--
5.1.1. Using Lists as Stacks
https://docs.python.org/3/tutorial/datastructures.html#using-lists-as-stacks

5.1.2. Using Lists as Queues
https://docs.python.org/3/tutorial/datastructures.html#using-lists-as-queues
-->


## Sorting, Queues

https://docs.python.org/3/howto/sorting.html

Collections
https://docs.python.org/3/library/collections.html#collections.deque

8.5. heapq — Heap queue algorithm
https://docs.python.org/3/library/heapq.html
https://docs.python.org/3/library/heapq.html#basic-examples
https://docs.python.org/3/library/heapq.html#theory

https://en.wikipedia.org/wiki/Priority_queue
https://docs.python.org/3/library/heapq.html#priority-queue-implementation-notes


## Data Types

6.3. Primaries
https://docs.python.org/3/reference/expressions.html#primaries

4.4. Numeric Types — int, float, complex
https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex

4.7. Text Sequence Type — str
https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str

## Binary

Binary Sequence Types
* bytes (immutable)
* byte array/bytearray (mutable)
* memoryview

4.8. Binary Sequence Types — bytes, bytearray, memoryview
https://docs.python.org/3/library/stdtypes.html#binary-sequence-types-bytes-bytearray-memoryview

https://docs.python.org/3/library/stdtypes.html#bytes-objects
https://docs.python.org/3/library/stdtypes.html#bytearray-objects
https://docs.python.org/3/library/stdtypes.html#printf-style-bytes-formatting
https://docs.python.org/3/library/stdtypes.html#memory-views

## Strings

Common string operations
https://docs.python.org/3/library/string.html | 6.1. string — Common string operations — Python 3.4.10 documentation

https://docs.python.org/3/tutorial/introduction.html#strings

https://docs.python.org/3/library/stdtypes.html#str

<!--
operator overloading
https://docs.python.org/3/glossary.html#term-coercion

https://docs.python.org/3/reference/lexical_analysis.html#string-literal-concatenation
-->

## Lists

11.7. Tools for Working with Lists
https://docs.python.org/3/tutorial/stdlib2.html#tools-for-working-with-lists

https://docs.python.org/3/library/stdtypes.html#lists

3.1.3. Lists
https://docs.python.org/3/tutorial/introduction.html#lists

5.1. More on Lists
https://docs.python.org/3/tutorial/datastructures.html#more-on-lists

## Arrays

array — Efficient arrays of numeric values
https://docs.python.org/3/library/array.html

bisect — Array bisection algorithm
https://docs.python.org/3/library/bisect.html
https://docs.python.org/3/library/bisect.html#searching-sorted-lists
https://docs.python.org/3/library/bisect.html#other-examples

## Tuples

https://docs.python.org/3/library/stdtypes.html#tuples
https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences

Tuple
https://docs.python.org/3/glossary.html#term-struct-sequence

## Dictionaries

https://docs.python.org/3/library/stdtypes.html#dict

https://docs.python.org/3/tutorial/datastructures.html#dictionaries

https://docs.python.org/3/library/stdtypes.html#mapping-types-dict

https://docs.python.org/3/glossary.html#term-mapping
https://docs.python.org/3/glossary.html#term-hashable

## Sets

"A set object is an unordered collection of distinct hashable objects"

set, frozenset
https://docs.python.org/3/library/stdtypes.html#set-types-set-frozenset
https://docs.python.org/3/tutorial/datastructures.html#sets


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

## Built-In Functions for Scope

Return a dictionary representing the current global symbol table. 
```globals()```

Update and return a dictionary representing the current local symbol table. 
```locals()```

## Built-In Functions for Formatting and Printing

Convert a value to a “formatted” representation, as controlled by format_spec. 
```format()```

Return a string containing a printable representation of an object. 
```repr()```

## Built-In Functions- ```eval()``` and ```exec()```

```eval()```

This function supports dynamic execution of Python code. 
```exec()```

Compile the source into a code or AST object. 
```compile()```

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
