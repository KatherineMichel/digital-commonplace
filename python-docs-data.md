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

## Kenneth Reitz Advice to Me 

* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

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
