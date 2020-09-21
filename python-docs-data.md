# Python Docs- Data

<!--
https://en.wikipedia.org/wiki/Decomposition | Decomposition - Wikipedia

Coding problems
https://en.wikipedia.org/wiki/Recursive_definition | Recursive definition - Wikipedia
https://docs.python.org/3.10/library/string.html | string — Common string operations — Python 3.10.0a0 documentation
https://docs.python.org/3/library/array.html | array — Efficient arrays of numeric values — Python 3.8.6rc1 documentation
https://docs.python.org/3/library/functions.html#func-range | Built-in Functions — Python 3.8.2 documentation
https://docs.python.org/3.3/library/stdtypes.html?highlight=range#ranges | 4. Built-in Types — Python 3.3.7 documentation
https://docs.python.org/2.3/whatsnew/section-slices.html | 15 Extended Slices
https://docs.python.org/3.4/library/functions.html?highlight=ord#ord | 2. Built-in Functions — Python 3.4.10 documentation
https://en.wikipedia.org/wiki/Bit_array | Bit array - Wikipedia

https://en.wikipedia.org/wiki/Precondition | Precondition - Wikipedia
https://en.wikipedia.org/wiki/Postcondition | Postcondition - Wikipedia

https://en.wikipedia.org/wiki/Off-by-one_error | Off-by-one error - Wikipedia
https://en.wikipedia.org/wiki/Off-by-one_error#Fencepost_error | Off-by-one error - Wikipedia

https://en.wikipedia.org/wiki/Control_flow
https://docs.python.org/3/tutorial/controlflow.html | 4. More Control Flow Tools — Python 3.8.2 documentation
https://en.wikipedia.org/wiki/Conditional_(computer_programming) | Conditional (computer programming) - Wikipedia
https://en.wikipedia.org/wiki/Conditional_(computer_programming)#If%E2%80%93then(%E2%80%93else) | Conditional (computer programming) - Wikipedia
https://docs.python.org/3/reference/compound_stmts.html#the-while-statement | 8. Compound statements — Python 3.8.2 documentation

https://docs.python.org/3/library/functions.html | Built-in Functions — Python 3.8.3 documentation

https://en.wikipedia.org/wiki/Scope_(computer_science) | Scope (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Namespace | Namespace - Wikipedia
https://en.wikipedia.org/wiki/Metaclass | Metaclass - Wikipedia

https://en.wikipedia.org/wiki/Increment_and_decrement_operators

https://en.wikipedia.org/wiki/Pseudorandomness | Pseudorandomness - Wikipedia

https://en.wikipedia.org/wiki/Concatenation | Concatenation - Wikipedia

https://www.python.org/dev/peps/pep-0008/ | PEP 8 -- Style Guide for Python Code | Python.org

https://docs.python.org/3/library/functions.html#built-in-funcs
https://docs.python.org/3/library/constants.html#built-in-consts

Recommended
https://docs.python.org/3/library/pathlib.html | pathlib — Object-oriented filesystem paths — Python 3.8.3 documentation

Super
https://docs.python.org/2/library/functions.html#super | 2. Built-in Functions — Python 2.7.16 documentation

Use Often
https://realpython.com/python-f-strings/ | Python 3's f-Strings: An Improved String Formatting Syntax (Guide) – Real Python
https://docs.python.org/3/reference/lexical_analysis.html#f-strings | 2. Lexical analysis — Python 3.8.3 documentation
https://docs.python.org/3/library/random.html | random — Generate pseudo-random numbers — Python 3.9.0a5 documentation
https://docs.python.org/3/library/math.html | math — Mathematical functions — Python 3.8.2 documentation
https://docs.python.org/3/library/functions.html#open | Built-in Functions — Python 3.8.5 documentation
https://docs.python.org/3/library/stdtypes.html?highlight=split#str.split | 4. Built-in Types — Python 3.3.7 documentation
https://docs.python.org/3/library/pathlib.html#pathlib.Path.replace | pathlib — Object-oriented filesystem paths — Python 3.8.5 documentation

Regular expression
https://en.wikipedia.org/wiki/Regular_expression | Regular expression - Wikipedia
https://docs.python.org/3/library/re.html | re — Regular expression operations — Python 3.8.3 documentation

urllib
https://docs.python.org/3/library/urllib.request.html
https://docs.python.org/3/library/urllib.parse.html
https://docs.python.org/2/library/urllib.html#urllib.urlretrieve | 20.5. urllib — Open arbitrary resources by URL — Python 2.7.18 documentation
-->

## Strings

Strip whitespace (right, left, both sides)

```python
lstrip()
rstrip()
strip()
```

<!--
String methods
https://docs.python.org/3.7/library/stdtypes.html#string-methods

https://docs.python.org/3.7/library/stdtypes.html#str.lstrip
https://docs.python.org/3.7/library/stdtypes.html#str.rstrip
https://docs.python.org/3.7/library/stdtypes.html#str.strip
-->


## Kenneth Reitz Advice to Me 

* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

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

Compound or complex statements

```python
header: 
   suite
header:
   suite 
header:
   suite
```

## Class or Function Syntax

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
           
## Control Flow Statement Examples

if-elif-else statement

```python
if condition true:
    action
elif condition true:
    action
else:
    action
```

for-else statement

```python
for condition:
    action
else:
    action
```

while-else statement

```python
while condition true:
    action
else:
    action
```

with statement

```python
with condition:
```

with-else statement

```python

```

## Exceptions

Two kinds of errors
* syntax errors
* logical errors

Traceback
* 1: file name, line number, module (if applicable)
* 2: line, ^ (caret) where the error is
* 3: type of error and description
     
Example

```python
$ python program.py
  File "program.py", line 3, in <module>
print 'Hello world! ^
SyntaxError: EOL while scanning string literal
```

try-except-else statement

```python
try:
    something
except Exception:
    do something else
else:
    do something else
```

<!--
8.4. The try statement
https://docs.python.org/3/reference/compound_stmts.html#the-try-statement
https://docs.python.org/3/reference/compound_stmts.html#finally

7.8. The raise statement
https://docs.python.org/3/reference/simple_stmts.html#the-raise-statement
-->

## Python Built-In Exceptions Hierarchy

<!--
The most common exceptions?
-->

Django raises built-in Python exceptions when appropriate.
https://docs.python.org/3/library/exceptions.html#bltin-exceptions

5.4. Exception hierarchy
https://docs.python.org/3/library/exceptions.html#exception-hierarchy

BaseException
  +-- Exception
      +-- StopIteration
      +-- StopAsyncIteration
      
 +-- SystemExit
 +-- KeyboardInterrupt
 +-- GeneratorExit
 
      +-- ImportError
      |    +-- ModuleNotFoundError
      
      +-- SyntaxError
      |    +-- IndentationError
      |         +-- TabError
      
      +-- NameError
      |    +-- UnboundLocalError
      
      +-- TypeError
      +-- ValueError
      |    +-- UnicodeError
      |         +-- UnicodeDecodeError
      |         +-- UnicodeEncodeError
      |         +-- UnicodeTranslateError
      
      +-- AttributeError 
      
      +-- LookupError
      |    +-- IndexError
      |    +-- KeyError
      
      +-- ArithmeticError
      |    +-- FloatingPointError
      |    +-- OverflowError
      |    +-- ZeroDivisionError
      
      +-- EOFError
      
      +-- AssertionError
              
      +-- ReferenceError
      
      +-- OSError
      |    +-- BlockingIOError
      |    +-- ChildProcessError
      |    +-- ConnectionError
      |    |    +-- BrokenPipeError
      |    |    +-- ConnectionAbortedError
      |    |    +-- ConnectionRefusedError
      |    |    +-- ConnectionResetError
      |    +-- FileExistsError
      |    +-- FileNotFoundError
      |    +-- InterruptedError
      |    +-- IsADirectoryError
      |    +-- NotADirectoryError
      |    +-- PermissionError
      |    +-- ProcessLookupError
      |    +-- TimeoutError    
      
      +-- SystemError
      
      +-- RuntimeError
      |    +-- NotImplementedError
      |    +-- RecursionError
      
      +-- MemoryError     
      +-- BufferError
               
Python Warnings

      +-- Warning

           +-- SyntaxWarning
           +-- UserWarning
           +-- ImportWarning
	   
           +-- UnicodeWarning
           +-- BytesWarning
	   
           +-- RuntimeWarning
           +-- ResourceWarning
	   
           +-- FutureWarning	   
           +-- DeprecationWarning
           +-- PendingDeprecationWarning
           
	  
## Collections

collections- mutability?

8.3. collections — Container datatypes
https://docs.python.org/3/library/collections.html

"alternatives to Python’s general purpose built-in containers, dict, list, set, and tuple."

Container datatypes
* namedtuple()
* deque
* ChainMap
* Counter
* OrderedDict (see example)
* defaultdict
* UserDict
* UserList
* UserString

Abstract Base Classes for Containers
* collections.abc

https://docs.python.org/3/library/collections.html#collections.namedtuple	
https://docs.python.org/3/library/collections.html#collections.OrderedDict	

https://docs.python.org/3/library/collections.html#chainmap-objects
https://docs.python.org/3/library/collections.html#chainmap-examples-and-recipes
https://docs.python.org/3/library/collections.html#counter-objects
https://docs.python.org/3/library/collections.html#deque-objects
https://docs.python.org/3/library/collections.html#deque-recipes
https://docs.python.org/3/library/collections.html#defaultdict-objects
https://docs.python.org/3/library/collections.html#defaultdict-examples
https://docs.python.org/3/library/collections.html#namedtuple-factory-function-for-tuples-with-named-fields
https://docs.python.org/3/library/collections.html#ordereddict-objects
https://docs.python.org/3/library/collections.html#ordereddict-examples-and-recipes
https://docs.python.org/3/library/collections.html#userdict-objects
https://docs.python.org/3/library/collections.html#userlist-objects
https://docs.python.org/3/library/collections.html#userstring-objects

https://docs.python.org/3/glossary.html#term-abstract-base-class

8.4. collections.abc — Abstract Base Classes for Containers
https://docs.python.org/3/library/collections.abc.html
https://docs.python.org/3/library/collections.abc.html#collections-abstract-base-classes

29.7. abc — Abstract Base Classes
https://docs.python.org/3/library/abc.html


## Python and Django Control Flow

3 Types of Control structures
* true or false branch evaluation (if statement)
* repeating while a condition is True (while loop)
* sequential processing (for loop)

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

## while Statements

Conditional test
* repeats a block of code while the condition is True (Boolean operation)
* if the condition does not become False, the loop runs indefinitely as an infinite loop.
* if the while statements becomes False, the else statement, if present, is executed

https://docs.python.org/3/reference/compound_stmts.html#the-while-statement

## Sequences

Sequence Types — list, tuple, range, string

Sequence Types — list, tuple, range, string
https://docs.python.org/3/library/stdtypes.html#sequence-types-list-tuple-range
https://docs.python.org/3/library/stdtypes.html#textseq
https://docs.python.org/3/library/stdtypes.html#string-methods

immutable
https://docs.python.org/3/library/stdtypes.html#immutable-sequence-types
mutable
https://docs.python.org/3/library/stdtypes.html#mutable-sequence-types

mutable and immutable
https://docs.python.org/3/library/stdtypes.html#common-sequence-operations

https://docs.python.org/3/reference/expressions.html#subscriptions

Range
https://docs.python.org/3/reference/expressions.html#slicings

List, dictionaries, etc. 
https://docs.python.org/3/tutorial/datastructures.html#the-del-statement
https://docs.python.org/3/reference/simple_stmts.html#the-del-statement

Not common
https://docs.python.org/3/library/stdtypes.html#binaryseq

## Iterators

Difference between Sequences, Iterators, Iterables
https://stackoverflow.com/questions/9884132/what-exactly-are-iterator-iterable-and-iteration

Iterators
https://www.python.org/dev/peps/pep-0234/

string, list, tuple dict, set, or other iterator

4.5. Iterator Types
https://docs.python.org/3/library/stdtypes.html#iterator-types

5.6. Looping Techniques
https://docs.python.org/3/tutorial/datastructures.html#looping-techniques

## Built-In Functions- Data Sequence/Iterator

Return an iterator object. 

```iter()```

https://docs.python.org/3/library/functions.html#iter

Retrieve the next item from the iterator by calling its __next__() method. 

```next()```

Construct an iterator from those elements of iterable for which function returns true. 

```filter()```

Return True if all elements of the iterable are true (or if the iterable is empty). 

```all()```	

Return True if any element of the iterable is true. If the iterable is empty, return False. 

```any()```

Return a reverse iterator. 

```reversed()```

Return a new sorted list from the items in iterable.

```sorted()```

https://docs.python.org/3/library/functions.html#reversed
https://docs.python.org/3/library/functions.html#sorted

## Built-In Looping Functions- Data Sequence/Iterator

Return an enumerate object. iterable must be a sequence, an iterator, or some other object which supports iteration. 

```enumerate()```

https://docs.python.org/3/library/functions.html#enumerate

8.13. enum — Support for enumerations
https://docs.python.org/3/library/enum.html
https://docs.python.org/3/library/enum.html#module-contents
https://docs.python.org/3/library/enum.html#creating-an-enum
https://docs.python.org/3/library/enum.html#programmatic-access-to-enumeration-members-and-their-attributes
https://docs.python.org/3/library/enum.html#duplicating-enum-members-and-values
https://docs.python.org/3/library/enum.html#ensuring-unique-enumeration-values
https://docs.python.org/3/library/enum.html#using-automatic-values
https://docs.python.org/3/library/enum.html#iteration
https://docs.python.org/3/library/enum.html#comparisons
https://docs.python.org/3/library/enum.html#allowed-members-and-attributes-of-enumerations
https://docs.python.org/3/library/enum.html#restricted-subclassing-of-enumerations
https://docs.python.org/3/library/enum.html#pickling
https://docs.python.org/3/library/enum.html#functional-api
https://docs.python.org/3/library/enum.html#derived-enumerations
https://docs.python.org/3/library/enum.html#intenum
https://docs.python.org/3/library/enum.html#intflag
https://docs.python.org/3/library/enum.html#flag
https://docs.python.org/3/library/enum.html#others
https://docs.python.org/3/library/enum.html#interesting-examples
https://docs.python.org/3/library/enum.html#omitting-values
https://docs.python.org/3/library/enum.html#orderedenum
https://docs.python.org/3/library/enum.html#duplicatefreeenum
https://docs.python.org/3/library/enum.html#planet
https://docs.python.org/3/library/enum.html#timeperiod
https://docs.python.org/3/library/enum.html#how-are-enums-different
https://docs.python.org/3/library/enum.html#enum-classes
https://docs.python.org/3/library/enum.html#enum-members-aka-instances
https://docs.python.org/3/library/enum.html#finer-points

Make an iterator that aggregates elements from each of the iterables. Returns an iterator of tuples

```zip()```

https://docs.python.org/3/library/functions.html#zip

## for Statements

What it does
* iterates over the items of any sequence in the order in which they appear in the sequence
* when all iteration has been completed, the else statement, if present, is executed

https://docs.python.org/3/tutorial/controlflow.html#for-statements
https://docs.python.org/3/reference/compound_stmts.html#the-for-statement

## break and continue Statements (for or while Loops), and else Clauses on Loops

4.4. break and continue Statements, and else Clauses on Loops
https://docs.python.org/3/tutorial/controlflow.html#break-and-continue-statements-and-else-clauses-on-loops

"The break statement breaks out of the innermost enclosing for or while loop."

7.9. The break statement
https://docs.python.org/3/reference/simple_stmts.html#the-break-statement

"The continue statement continues with the next iteration of the (for or while) loop."

7.10. The continue statement
https://docs.python.org/3/reference/simple_stmts.html#the-continue-statement

## pass Statements

Nothing happens when the pass statement executes.

null operation
4.5. pass Statements
https://docs.python.org/3/tutorial/controlflow.html#pass-statements
7.4. The pass statement
https://docs.python.org/3/reference/simple_stmts.html#the-pass-statement

## range() Function (for Statement for Numbers)

What it does
* iterates over a sequence of numbers

How
* starts at 0 by default
* stops one number below the number passed to it

https://en.wikipedia.org/wiki/Increment_and_decrement_operators

https://docs.python.org/3/library/stdtypes.html#ranges

4.3. The range() Function
https://docs.python.org/3/tutorial/controlflow.html#the-range-function

## Built-In Functions- Range

Return a slice object representing the set of indices specified by range(start, stop, step). See itertools.islice() for an alternate version that returns an iterator.

```slice()```

https://docs.python.org/3.7/library/itertools.html#itertools.islice

## for Statement Alternatives

* list comprehension
* map function
* generator expressions

## List Comprehensions (range function)

What it does
* a more efficient way to do a for loop

Two Types of Listed Comprehensions
* List Comprehensions
* Nested List Comprehensions

5.1.3. List Comprehensions
https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions

## Nested List Comprehensions

matrix?
5.1.4. Nested List Comprehensions
https://docs.python.org/3/tutorial/datastructures.html#nested-list-comprehensions

## Built-In Function- ```map()```

Return an iterator that applies function to every item of iterable, yielding the results. see itertools.starmap().

```map()```

https://docs.python.org/3/library/functions.html#map
https://docs.python.org/3/library/itertools.html#itertools.starmap

## Generators

https://docs.python.org/3/glossary.html#term-generator

Types
https://docs.python.org/3/library/stdtypes.html#iterator-types
https://docs.python.org/3/library/stdtypes.html#generator-types

Classes
9.8. Iterators
https://docs.python.org/3/tutorial/classes.html#iterators
9.9. Generators
https://docs.python.org/3/tutorial/classes.html#generators
9.10. Generator Expressions
https://docs.python.org/3/tutorial/classes.html#generator-expressions

## Generator Expression

https://docs.python.org/3/glossary.html#term-generator-expression

https://docs.python.org/3/reference/expressions.html#generator-expressions

## Asynchronous Generator

https://docs.python.org/3/reference/expressions.html#asynchronous-generator-functions
https://docs.python.org/3/reference/expressions.html#asynchronous-generator-iterator-methods

## Generator Iterator

https://docs.python.org/3/glossary.html#term-generator-iterator
https://docs.python.org/3/reference/expressions.html#generator-iterator-methods
https://docs.python.org/3/reference/expressions.html#examples

## yield Statements (used with a generator function or asynchronous generator function)

https://docs.python.org/3/reference/expressions.html#yield-expressions

7.7. The yield statement
https://docs.python.org/3/reference/simple_stmts.html#the-yield-statement

## Coroutines

async/await
Similar to generator iterator

https://docs.python.org/3/reference/datamodel.html#coroutines
https://docs.python.org/3/reference/compound_stmts.html#coroutines

https://docs.python.org/3/reference/expressions.html#await-expression

https://docs.python.org/3/reference/compound_stmts.html#coroutine-function-definition
https://docs.python.org/3/reference/compound_stmts.html#the-async-for-statement
https://docs.python.org/3/reference/compound_stmts.html#the-async-with-statement

Data Model
https://docs.python.org/3/reference/datamodel.html#awaitable-objects
https://docs.python.org/3/reference/datamodel.html#coroutine-objects
https://docs.python.org/3/reference/datamodel.html#asynchronous-iterators
https://docs.python.org/3/reference/datamodel.html#asynchronous-context-managers

## Built-In Looping Functions- Dictionary

dictionary views
"The objects returned by dict.keys(), dict.values() and dict.items() are view objects. They provide a dynamic view on the dictionary’s entries, which means that when the dictionary changes, the view reflects these changes."
https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects

Dictionaries

```items()```

https://docs.python.org/3/library/stdtypes.html#dict.items

More dictionary helpers
* try statement
* get method
* dict.setdefault
* collections.defaultdict

Dictionary alternatives
https://docs.python.org/3/reference/compound_stmts.html#try
https://wiki.python.org/moin/KeyError

https://docs.python.org/3/library/stdtypes.html#dict.get

https://docs.python.org/3/library/stdtypes.html#dict.setdefault
https://docs.python.org/3/library/collections.html#collections.defaultdict

## Lambda Expressions

4.7.5. Lambda Expressions
https://docs.python.org/3/tutorial/controlflow.html#lambda-expressions
6.13. Lambdas
https://docs.python.org/3/reference/expressions.html#lambda

## with Statements

8.5. The with statement
https://docs.python.org/3/reference/compound_stmts.html#the-with-statement

https://docs.python.org/3/reference/compound_stmts.html#with

4.11. Context Manager Types
https://docs.python.org/3/library/stdtypes.html#context-manager-types

https://docs.python.org/3/reference/datamodel.html#context-managers

30.7. contextlib — Utilities for with-statement contexts

https://docs.python.org/3/library/contextlib.html
https://docs.python.org/3/library/contextlib.html#utilities
https://docs.python.org/3/library/contextlib.html#examples-and-recipes
https://docs.python.org/3/library/contextlib.html#supporting-a-variable-number-of-context-managers
https://docs.python.org/3/library/contextlib.html#catching-exceptions-from-enter-methods
https://docs.python.org/3/library/contextlib.html#cleaning-up-in-an-enter-implementation
https://docs.python.org/3/library/contextlib.html#replacing-any-use-of-try-finally-and-flag-variables
https://docs.python.org/3/library/contextlib.html#using-a-context-manager-as-a-function-decorator
https://docs.python.org/3/library/contextlib.html#single-use-reusable-and-reentrant-context-managers
https://docs.python.org/3/library/contextlib.html#reentrant-context-managers
https://docs.python.org/3/library/contextlib.html#reusable-context-managers

## Functional Programming: itertools, functools, and operator

"The functions fall into categories that perform object comparisons, logical operations, mathematical operations and sequence operations."

Functional programming modules
* itertools
* functools
* operator

10. Functional Programming Modules
10.1. itertools — Functions creating iterators for efficient looping
10.2. functools — Higher-order functions and operations on callable objects
10.3. operator — Standard operators as functions

https://docs.python.org/3/library/functional.html

https://docs.python.org/3/library/itertools.html
https://docs.python.org/3/library/itertools.html#itertool-functions
https://docs.python.org/3/library/itertools.html#itertools-recipes

https://docs.python.org/3/library/itertools.html#itertools.chain

https://docs.python.org/3/library/functools.html
https://docs.python.org/3/library/functools.html#partial-objects


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
