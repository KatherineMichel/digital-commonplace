# Python Doc- Data

## General Notes

<!--
pathlib
https://twitter.com/wsv3000/status/1286022846939107329 | Will Vincent on Twitter: "I'm a fan of switching to pathlib in Django 3.1 but it's gonna brick A LOT of older tutorials for newbies who can't get their https://t.co/dr8oMArbJE files to work right. Not sure how to mitigate this..." / Twitter

File path
https://www.python.org/dev/peps/pep-0519/ | PEP 519 -- Adding a file system path protocol | Python.org

https://en.wikipedia.org/wiki/Decomposition | Decomposition - Wikipedia
https://en.wikipedia.org/wiki/Recursive_definition | Recursive definition - Wikipedia
https://www.geeksforgeeks.org/recursion/ | Recursion - GeeksforGeeks
https://en.wikipedia.org/wiki/Recursion
https://realpython.com/python-thinking-recursively/


https://en.wikipedia.org/wiki/Backward_compatibility | Backward compatibility - Wikipedia
https://en.wikipedia.org/wiki/Self-documenting_code | Self-documenting code - Wikipedia

https://twitter.com/unclebobmartin/status/1010660993851117569 | Uncle Bob Martin on Twitter: "Programs are made up of Dijkstra’s three structures: Sequence, Selection, and Iteration. Each of these is based upon jumps. Sequential statements jump from the end of the first to be beginning of the second."

os and pathlib
https://github.com/chris1610/pbpython/blob/master/extras/Pathlib-Cheatsheet.pdf | pbpython/Pathlib-Cheatsheet.pdf at master · chris1610/pbpython
https://twitter.com/treyhunner/status/1317105113614360576 | ✨ Trey Hunner 🐍 on Twitter: "@KatiMichel A bit more demonstration that the "os" module is the junk drawer: it has more variable names in it than any of the other standard library modules "Operating System" includes a *lot* of stuff 😜 https://t.co/qFUVGPdRgX" / Twitter
https://twitter.com/jeremyphoward/status/1316586950170615809 | Jeremy Howard on Twitter: "Python 3.9's standard library has 331 modules, exporting 8329 symbols. `os` exports the most, with 331 symbols https://t.co/UCR8Jd3eKl" / Twitter

dir()
https://www.youtube.com/watch?v=LxCdn18eGng&feature=emb_logo

https://codeinplace2020.github.io/faqs/7-Functions.pdf | 7-Functions

https://stackoverflow.com/questions/373419/whats-the-difference-between-passing-by-reference-vs-passing-by-value | language agnostic - What's the difference between passing by reference vs. passing by value? - Stack Overflow
https://developer.mozilla.org/en-US/docs/Glossary/Parameter | Parameter - MDN Web Docs Glossary: Definitions of Web-related terms | MDN
-->

<!--
https://en.wikipedia.org/wiki/Precondition | Precondition - Wikipedia
https://en.wikipedia.org/wiki/Postcondition | Postcondition - Wikipedia

https://en.wikipedia.org/wiki/Off-by-one_error | Off-by-one error - Wikipedia
https://en.wikipedia.org/wiki/Off-by-one_error#Fencepost_error | Off-by-one error - Wikipedia

https://en.wikipedia.org/wiki/Increment_and_decrement_operators
https://en.wikipedia.org/wiki/Concatenation | Concatenation - Wikipedia
negative indexes python - Google Search

https://en.wikipedia.org/wiki/Control_flow
https://en.wikipedia.org/wiki/Conditional_(computer_programming) | Conditional (computer programming) - Wikipedia
https://en.wikipedia.org/wiki/Conditional_(computer_programming)#If%E2%80%93then(%E2%80%93else) | Conditional (computer programming) - Wikipedia



Super
https://docs.python.org/2/library/functions.html#super | 2. Built-in Functions — Python 2.7.16 documentation

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypeError | TypeError - JavaScript | MDN
https://eli.thegreenplace.net/2011/05/15/understanding-unboundlocalerror-in-python/ | Understanding UnboundLocalError in Python - Eli Bendersky's website

Path
https://docs.python.org/3/library/filesys.html | File and Directory Access — Python 3.8.6 documentation
https://docs.python.org/3/library/os.path.html#os.path.join
https://docs.python.org/3/library/pathlib.html#pathlib.Path.replace | pathlib — Object-oriented filesystem paths — Python 3.8.5 documentation
-->

<!--
## Utilities

https://pypi.org/project/ipdb/ | ipdb · PyPI

28. Debugging and Profiling
28.3. pdb — The Python Debugger
28.1. bdb — Debugger framework

https://docs.python.org/3/library/debug.html

https://docs.python.org/3/library/pdb.html#debugger-commands

29.9. traceback — Print or retrieve a stack traceback
https://docs.python.org/3/library/traceback.html
-->



## Useful

https://www.python.org/dev/peps/pep-0008/ | PEP 8 -- Style Guide for Python Code | Python.org
https://docs.python.org/3/reference/expressions.html#operator-precedence

Built-in functions
https://docs.python.org/3/library/functions.html#built-in-funcs

Popular string methods
https://www.w3schools.com/python/python_ref_string.asp
Popular list methods
https://www.w3schools.com/python/python_ref_list.asp

https://docs.python.org/3/library/stdtypes.html
https://docs.python.org/3/tutorial/datastructures.html

https://www.geeksforgeeks.org/difference-between-list-and-array-in-python

Data Structures- Linear
* [Linked List Wikipedia](https://en.wikipedia.org/wiki/Linked_list)
* [Stack Wikipedia](https://en.wikipedia.org/wiki/Stack_(abstract_data_type))
* [Queue Wikipedia](https://en.wikipedia.org/wiki/Queue_(abstract_data_type))
* [Double-Ended Queue (Deque) Wikipedia](https://en.wikipedia.org/wiki/Double-ended_queue)
* Vectors/Arraylists 

* Trees, Tries, & Graphs
* [Heap (tree) Wikipedia](https://en.wikipedia.org/wiki/Heap_(data_structure))
* [Trie Wikipedia](https://en.wikipedia.org/wiki/Trie)

Data Structures- Hash
* [Hash Table Wikipedia](https://en.wikipedia.org/wiki/Hash_table)

Algorithms- Search
* [Breadth-First Search Wikipedia](https://en.wikipedia.org/wiki/Breadth-first_search)
* [Depth-First Search Wikipedia](https://en.wikipedia.org/wiki/Depth-first_search)
* [Binary Search Algorithm](https://en.wikipedia.org/wiki/Binary_search_algorithm)

Algorithms- Sort
* [Merge Sort Wikipedia](https://en.wikipedia.org/wiki/Merge_sort)
* [Quicksort Wikipedia](https://en.wikipedia.org/wiki/Quicksort)

Concepts- Memory (Stack vs. Heap)
* [Stack Wikipedia](https://en.wikipedia.org/wiki/Stack_(abstract_data_type))
* [Heap Wikipedia](https://en.wikipedia.org/wiki/Heap_(data_structure))

Concepts- Problem Solving
* [Recursion Wikipedia](https://en.wikipedia.org/wiki/Recursion)
* Dynamic Programming

Concepts- Time and Space Complexity
* Big O [Time Complexity Wikipedia](https://en.wikipedia.org/wiki/Time_complexity)
* Big O [Space Complexity Wikipedia](https://en.wikipedia.org/wiki/Space_complexity)

Concepts- Bits
* [Bit Manipulation Wikipedia](https://en.wikipedia.org/wiki/Bit_manipulation)

http://bigocheatsheet.com/
https://en.wikipedia.org/wiki/Big_O_notation
https://github.com/ro31337/bigoposter/blob/master/bigoposter.pdf

Problem Solving Flowchart


## Lists as Stack or Queue

### List Pop

Pop the last item from a list

```python
items.pop()
```

### List as Stack

<!--
5.1.1. Using Lists as Stacks
https://docs.python.org/3/tutorial/datastructures.html#using-lists-as-stacks
-->

```python
>>> stack = []
>>> stack.append()
>>> stack.pop()
>>> stack
[]
```

### List as Queue

<!--
5.1.2. Using Lists as Queues
https://docs.python.org/3/tutorial/datastructures.html#using-lists-as-queues

Collections
https://docs.python.org/3/library/collections.html#collections.deque
-->

```python
>>> from collections import deque
>>> queue = deque([])
>>> queue.append()  
>>> queue.popleft()
>>> queue
deque([])
```

## Sorting, Queues

https://docs.python.org/3/howto/sorting.html

8.5. heapq — Heap queue algorithm
https://docs.python.org/3/library/heapq.html
https://docs.python.org/3/library/heapq.html#basic-examples
https://docs.python.org/3/library/heapq.html#theory

https://en.wikipedia.org/wiki/Priority_queue
https://docs.python.org/3/library/heapq.html#priority-queue-implementation-notes



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

## Data Types

6.3. Primaries
https://docs.python.org/3/reference/expressions.html#primaries

4.4. Numeric Types — int, float, complex
https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex

4.7. Text Sequence Type — str
https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str

## Mutability

* Mutable- individual item can be changed
* Immutable- individual item cannot be changed
* Sequence- 
* Non-Sequence-
* Iterable-

After change
* mutable data structure will have same id
* immutable data structure will have new id

## Sequences and Iterables

* List (mutable, sequence, iterable)
* String (immutable, sequence, iterable)
* Tuple (immutable, sequence, iterable)
* Dict (mutable, non-sequence, iterable)
* Set (mutable, non-sequence, iterable)

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

Linear (Sequential) Data Structures
* [Linear Data Structures Wikipedia](https://en.wikipedia.org/wiki/List_of_data_structures#Linear_data_structures)

Linear Data Structure Examples (left to right, top to bottom)
* list (including linked list, doubly linked list), stack, queue, deque, array

List (Sequence) Linear and Non-Linear Implementations
* Linear: stack and queue
* Non-Linear: graph and tree

Queue Implementations
* Queue Using Linked List
* Queue Using Stack


## Sequences

Sequence
* [Sequence Wikipedia](https://en.wikipedia.org/wiki/Sequence)

Types of order
* [Alphabetical Order Wikipedia](https://en.wikipedia.org/wiki/Alphabetical_order)
* [Lexicographical Order (Alphabetical Order) Wikipedia](https://en.wikipedia.org/wiki/Lexicographical_order)
* [Numerical Wikipedia](https://en.wiktionary.org/wiki/numerical)
* [Numerical Order Wikipedia](https://en.wikipedia.org/wiki/Numerical_order)
* [Alphanumeric Wikipedia](https://en.wikipedia.org/wiki/Alphanumeric)

<!--
https://en.wikipedia.org/wiki/Character_encoding
https://en.wikipedia.org/wiki/Letter_case
https://en.wikipedia.org/wiki/Numeral_system
https://en.wikipedia.org/wiki/Punctuation

https://www.geeksforgeeks.org/ord-function-python/
https://en.wikipedia.org/wiki/Unicode

https://en.wikipedia.org/wiki/ASCII
-->

## Sequences

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


List, dictionaries, etc. 
https://docs.python.org/3/tutorial/datastructures.html#the-del-statement
https://docs.python.org/3/reference/simple_stmts.html#the-del-statement

Not common
https://docs.python.org/3/library/stdtypes.html#binaryseq

## List Comprehensions and Range

Range
https://docs.python.org/3/reference/expressions.html#slicings

Explanation of `j`
https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions


Range
https://docs.python.org/3/library/functions.html#func-range | Built-in Functions — Python 3.8.2 documentation
https://docs.python.org/3.3/library/stdtypes.html?highlight=range#ranges | 4. Built-in Types — Python 3.3.7 documentation

Slicing
https://docs.python.org/2.3/whatsnew/section-slices.html | 15 Extended Slices


## Strings

Common string operations
https://docs.python.org/3/library/string.html | 6.1. string — Common string operations — Python 3.4.10 documentation

String methods
https://docs.python.org/3/library/stdtypes.html#string-methods

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

List methods
5.1. More on Lists
https://docs.python.org/3/tutorial/datastructures.html#more-on-lists

3.1.3. Lists
https://docs.python.org/3/tutorial/introduction.html#lists
https://docs.python.org/3/library/stdtypes.html#lists

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




## Common String Operations

### Strings

Strip whitespace (right, left, both sides)

```python
lstrip()
rstrip()
strip()
```

<!--
String
https://docs.python.org/3/library/stdtypes.html#str.join
https://docs.python.org/3/library/stdtypes.html#str.replace
https://docs.python.org/3/library/stdtypes.html#str.split

https://docs.python.org/3/library/stdtypes.html#str.lstrip
https://docs.python.org/3/library/stdtypes.html#str.rstrip
https://docs.python.org/3/library/stdtypes.html#str.strip

6.1. string — Common string operations
https://docs.python.org/3/library/string.html#module-string
https://docs.python.org/3/library/string.html#string-constants
https://docs.python.org/3/library/string.html#custom-string-formatting
https://docs.python.org/3/library/string.html#format-string-syntax
https://docs.python.org/3/library/string.html#format-specification-mini-language
https://docs.python.org/3/library/string.html#format-examples
https://docs.python.org/3/library/string.html#template-strings
https://docs.python.org/3/library/string.html#helper-functions
-->


## Identity and Membership

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

while-else statement

```python
while condition true:
    action
else:
    action
```


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

## List Comprehensions (range() function)

What it does
* a more efficient way to do a for loop

5.1.3. List Comprehensions
https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions



## break, continue, and pass Statements

### break and continue Statements (for or while Loops), and else Clauses on Loops

4.4. break and continue Statements, and else Clauses on Loops
https://docs.python.org/3/tutorial/controlflow.html#break-and-continue-statements-and-else-clauses-on-loops

"The break statement breaks out of the innermost enclosing for or while loop."

7.9. The break statement
https://docs.python.org/3/reference/simple_stmts.html#the-break-statement

"The continue statement continues with the next iteration of the (for or while) loop."

7.10. The continue statement
https://docs.python.org/3/reference/simple_stmts.html#the-continue-statement

### pass Statements

Nothing happens when the pass statement executes.

null operation
4.5. pass Statements
https://docs.python.org/3/tutorial/controlflow.html#pass-statements
7.4. The pass statement
https://docs.python.org/3/reference/simple_stmts.html#the-pass-statement



## for Statement Examples

### Loop Through a List (for Statement)

Print all items in a list

```python
items = []
for item in items:
    print(item)
```

Example

```python
numbers = [1, 2, 3, 4]
for number in numbers:
    print(number)
```

### Loop Through a Tuple (for Statement)

Print all items in a tuple

```python
items = ()
for item in items:
    print(item)
```

### Loop Through a Dictionary (for Statement)

Three Ways to Loop through a Dictionary
* loop through all the key/value pairs
* loop through all the keys
* loop through all the values
   
A dictionary

```python
a_dictionary = {key: value, key: value}
```

Loop through all the key-value pairs

```python
for key, value in a_dictionary.items():
    print(key, value)
```

Sometimes also written as

```python
for k, v in a_dictionary.items():
    print(k, v)
```

Loop through all the keys

```python
for key in a_dictionary.keys():
    print(key)
```

Loop through all the values

```python
for value in a_dictionary.values():
    print(value)
```

Example of value as integer made into string

```python
for value in a_dictionary.values():
    print(str(value))
```

### range() Function Examples (for Statement)

Print the numbers 0 to 1000

```python
for number in range(1001):
    print(number)
```

Print the numbers 1 to 1000

```python
for number in range(1, 1001):
    print(number)
```

Generate a million dictionaries using a for loop

```python
items = []

for item_number in range(1000000):
    new_item = {}
    new_item[key] = value
    items.append(new_item)

number_of_items = len(items)

print(number_of_items)
```

Make a list of numbers from 1 to a million

```python
numbers = list(range(1, 1000001))
```

### range() Function Versus List Comprehension (for Statement)

range() function

```python
for i in range():
    action
```

List comprehensions

```python
list = [action for i in range()]
```

```python
list = [value, value, value]

new_list = [list.action() for items in list]
```

### Loop Versus List Comprehension- Squared Numbers Example

Use a loop to generate a list of squared numbers

```python
squares = []
for i in range(1, 20): 
    square = i**2
    squares.append(square)
print(squares)
```

Similar

```python
squares = []
for i in range(1, 20): 
    squares.append(i**2)
print(squares)
```

Use a list comprehension to generate a list of squared numbers

```python
squares = [i**2 for i in range(1, 20)]
print(squares)
```

### Loop Versus List Comprehension- Convert List of Names to Upper Case

Use a loop to convert a list of names to upper case

```python
names = ['name1', 'name2', 'name3']

upper_names = []
for name in names:
    upper_names.append(name.upper())
```

Use a list comprehension to convert a list of names to upper case

```python
names = ['name1', 'name2', 'name3']

upper_names = [name.upper() for name in names]
```


## for Statement Alternatives

* list comprehension (see above)
* map function
* generator expressions

## List Comprehensions (range() function)

Two Types of Listed Comprehensions
* List Comprehensions
* Nested List Comprehensions

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


## Lambda Expressions

4.7.5. Lambda Expressions
https://docs.python.org/3/tutorial/controlflow.html#lambda-expressions
6.13. Lambdas
https://docs.python.org/3/reference/expressions.html#lambda


## with Statements

8.5. The with statement
https://docs.python.org/3/reference/compound_stmts.html#the-with-statement

https://docs.python.org/3/reference/compound_stmts.html#with

with statement

```python
with condition:
```

### Context Manager (with Statement)

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



## Built-In Functions- Range

Return a slice object representing the set of indices specified by range(start, stop, step). See itertools.islice() for an alternate version that returns an iterator.

```slice()```

https://docs.python.org/3.7/library/itertools.html#itertools.islice

## Built-In Looping Functions- Dictionary

dictionary views
"The objects returned by dict.keys(), dict.values() and dict.items() are view objects. They provide a dynamic view on the dictionary’s entries, which means that when the dictionary changes, the view reflects these changes."
https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects

Dictionaries

```items()```

https://docs.python.org/3/library/stdtypes.html#dict.items

### More dictionary helpers

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


<!--
Unix
https://docs.python.org/3/tutorial/appendix.html#executable-python-scripts
https://docs.python.org/3/tutorial/appendix.html#the-interactive-startup-file

https://docs.python.org/3/tutorial/appendix.html#interactive-mode


https://docs.python.org/3/tutorial/appendix.html#the-customization-modules


File
https://docs.python.org/3/library/os.html#file-object-creation
https://docs.python.org/3/library/os.html#os.open
https://docs.python.org/3/library/functions.html#open
https://docs.python.org/3/library/fileinput.html#module-fileinput
https://docs.python.org/3/library/tempfile.html#module-tempfile
https://docs.python.org/3/library/shutil.html#module-shutil


## Platform

https://docs.python.org/3/library/allos.html

16.14. platform — Access to underlying platform’s identifying data
https://docs.python.org/3/library/platform.html

10.1. Operating System Interface
https://docs.python.org/3/tutorial/stdlib.html#operating-system-interface

https://treyhunner.com/2018/12/why-you-should-be-using-pathlib/

16.1. os — Miscellaneous operating system interfaces
https://docs.python.org/3/library/os.html

11.2. os.path — Common pathname manipulations
https://docs.python.org/3/library/os.path.html

11.4. stat — Interpreting stat() results
https://docs.python.org/3/library/stat.html
https://docs.python.org/3/library/os.html#os.stat

11.1. pathlib — Object-oriented filesystem paths
https://docs.python.org/3/library/pathlib.html
Interesting (os and os.path versus pathlib)
https://docs.python.org/3/library/pathlib.html#correspondence-to-tools-in-the-os-module

29.1. sys — System-specific parameters and functions
https://docs.python.org/3/library/sys.html
https://docs.python.org/3/library/sys.html#sys.path
https://docs.python.org/3/library/sys.html#sys.stdin
https://docs.python.org/3/library/sys.html#sys.stdout
https://docs.python.org/3/library/sys.html#sys.stderr

10.4. Error Output Redirection and Program Termination
https://docs.python.org/3/tutorial/stdlib.html#error-output-redirection-and-program-termination

30.2. sysconfig — Provide access to Python’s configuration information
https://docs.python.org/3/library/sysconfig.html

11.10. shutil — High-level file operations
https://docs.python.org/3/library/shutil.html


## Tutorial

3. An Informal Introduction to Python
https://docs.python.org/3/tutorial/introduction.html
https://docs.python.org/3/tutorial/introduction.html#an-informal-introduction-to-python
https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator
https://docs.python.org/3/tutorial/introduction.html#numbers
https://docs.python.org/3/tutorial/introduction.html#strings
https://docs.python.org/3/library/stdtypes.html#textseq
https://docs.python.org/3/reference/lexical_analysis.html#f-strings
Fibonacci series 
https://docs.python.org/3/tutorial/introduction.html#first-steps-towards-programming


11.1. Output Formatting
https://docs.python.org/3/tutorial/stdlib2.html#output-formatting
https://docs.python.org/3/library/functions.html#repr
https://docs.python.org/3/library/pprint.html#module-pprint

f-string
https://docs.python.org/3/whatsnew/3.6.html#whatsnew36-pep498
https://docs.python.org/3/glossary.html#term-f-string
https://docs.python.org/3/reference/lexical_analysis.html#f-strings
https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals


10.6. Mathematics
https://docs.python.org/3/tutorial/stdlib.html#mathematics
https://docs.python.org/3/library/random.html | random — Generate pseudo-random numbers — Python 3.9.0a5 documentation
https://docs.python.org/3/library/math.html | math — Mathematical functions — Python 3.8.2 documentation
https://docs.python.org/3/library/math.html#math.floor
https://docs.python.org/3/library/fractions.html | fractions — Rational numbers — Python 3.8.3 documentation

10.8. Dates and Times
https://docs.python.org/3/tutorial/stdlib.html#dates-and-times
https://docs.python.org/3/library/datetime.html#module-datetime

16.3. time — Time access and conversions
https://docs.python.org/3/library/time.html
8.1. datetime — Basic date and time types
https://docs.python.org/3/library/datetime.html
8.2. calendar — General calendar-related functions
https://docs.python.org/3/library/calendar.html


11.7. Tools for Working with Lists
https://docs.python.org/3/tutorial/stdlib2.html#tools-for-working-with-lists
https://docs.python.org/3/library/array.html#module-array
https://docs.python.org/3/library/array.html#array.array
https://docs.python.org/3/library/collections.html#module-collections
https://docs.python.org/3/library/collections.html#collections.deque
https://docs.python.org/3/library/bisect.html#module-bisect
https://docs.python.org/3/library/heapq.html#module-heapq
11.8. Decimal Floating Point Arithmetic
https://docs.python.org/3/tutorial/stdlib2.html#decimal-floating-point-arithmetic

11.4. Multi-threading
https://docs.python.org/3/tutorial/stdlib2.html#multi-threading
https://docs.python.org/3/library/threading.html#module-threading
https://docs.python.org/3/library/queue.html#module-queue
https://docs.python.org/3/library/queue.html#queue.Queue


https://docs.python.org/3/library/http.html#http-status-codes

https://requests.readthedocs.io/en/master/
https://requests.readthedocs.io/en/master/#beloved-features


10.5. String Pattern Matching
https://docs.python.org/3/tutorial/stdlib.html#string-pattern-matching
https://docs.python.org/3/library/re.html | re — Regular expression operations — Python 3.8.3 documentation
https://en.wikipedia.org/wiki/Regular_expression | Regular expression - Wikipedia

10.2. File Wildcards
https://docs.python.org/3/tutorial/stdlib.html#file-wildcards
11.7. glob — Unix style pathname pattern expansion
https://docs.python.org/3/library/glob.html
https://docs.python.org/3/library/fnmatch.html


10.12. Batteries Included
https://docs.python.org/3/library/json.html#module-json
https://docs.python.org/3/library/csv.html#module-csv
https://docs.python.org/3/library/sqlite3.html#module-sqlite3

14.1. csv — CSV File Reading and Writing
https://docs.python.org/3/library/csv.html
https://docs.python.org/3/library/csv.html#module-contents
https://docs.python.org/3/library/csv.html#dialects-and-formatting-parameters
https://docs.python.org/3/library/csv.html#reader-objects
https://docs.python.org/3/library/csv.html#writer-objects
https://docs.python.org/3/library/csv.html#examples

https://docs.python.org/3.8/library/xml.etree.elementtree.html#xml.etree.ElementTree.Element.findall | xml.etree.ElementTree — The ElementTree XML API — Python 3.8.3 documentation

21. Internet Protocols and Support

19.2. json — JSON encoder and decoder
20.2. json — JSON encoder and decoder
7.2.2. Saving structured data with json
https://docs.python.org/3/tutorial/inputoutput.html#saving-structured-data-with-json

https://docs.python.org/3/library/json.html

https://docs.python.org/3/library/json.html#basic-usage
https://docs.python.org/3/library/json.html#encoders-and-decoders
https://docs.python.org/3/library/json.html#exceptions
https://docs.python.org/3/library/json.html#standard-compliance-and-interoperability
https://docs.python.org/3/library/json.html#character-encodings
https://docs.python.org/3/library/json.html#infinite-and-nan-number-values
https://docs.python.org/3/library/json.html#repeated-names-within-an-object
https://docs.python.org/3/library/json.html#top-level-non-object-non-array-values
https://docs.python.org/3/library/json.html#implementation-limitations
https://docs.python.org/3/library/json.html#module-json.tool
https://docs.python.org/3/library/json.html#command-line-options

12.4. marshal — Internal Python object serialization
https://docs.python.org/3/library/marshal.html


10.3. Command Line Arguments
https://docs.python.org/3/tutorial/stdlib.html#command-line-arguments
https://docs.python.org/3/library/sys.html#sys.argv

22.1. webbrowser — Convenient Web-browser controller
https://docs.python.org/3/library/webbrowser.html
https://docs.python.org/3/library/webbrowser.html#browser-controller-objects

https://docs.python.org/3/howto/argparse.html
"The program defines what arguments it requires, and argparse will figure out how to parse those out of sys.argv. The argparse module also automatically generates help and usage messages and issues errors when users give the program invalid arguments."

Alternative
16.5. getopt — C-style parser for command line options
https://docs.python.org/3/library/getopt.html

16.4. argparse — Parser for command-line options, arguments and sub-commands
https://docs.python.org/3/library/argparse.html
https://docs.python.org/3/library/argparse.html#example
https://docs.python.org/3/library/argparse.html#creating-a-parser
https://docs.python.org/3/library/argparse.html#adding-arguments
https://docs.python.org/3/library/argparse.html#parsing-arguments
https://docs.python.org/3/library/argparse.html#argumentparser-objects
https://docs.python.org/3/library/argparse.html#prog
https://docs.python.org/3/library/argparse.html#usage
https://docs.python.org/3/library/argparse.html#description
https://docs.python.org/3/library/argparse.html#epilog
https://docs.python.org/3/library/argparse.html#parents
https://docs.python.org/3/library/argparse.html#formatter-class
https://docs.python.org/3/library/argparse.html#prefix-chars
https://docs.python.org/3/library/argparse.html#fromfile-prefix-chars
https://docs.python.org/3/library/argparse.html#argument-default
https://docs.python.org/3/library/argparse.html#allow-abbrev
https://docs.python.org/3/library/argparse.html#conflict-handler
https://docs.python.org/3/library/argparse.html#add-help
https://docs.python.org/3/library/argparse.html#the-add-argument-method
https://docs.python.org/3/library/argparse.html#name-or-flags
https://docs.python.org/3/library/argparse.html#action
https://docs.python.org/3/library/argparse.html#nargs
https://docs.python.org/3/library/argparse.html#const
https://docs.python.org/3/library/argparse.html#default
https://docs.python.org/3/library/argparse.html#type
https://docs.python.org/3/library/argparse.html#choices
https://docs.python.org/3/library/argparse.html#required
https://docs.python.org/3/library/argparse.html#help
https://docs.python.org/3/library/argparse.html#metavar
https://docs.python.org/3/library/argparse.html#dest
https://docs.python.org/3/library/argparse.html#action-classes
https://docs.python.org/3/library/argparse.html#the-parse-args-method
https://docs.python.org/3/library/argparse.html#option-value-syntax
https://docs.python.org/3/library/argparse.html#invalid-arguments
https://docs.python.org/3/library/argparse.html#arguments-containing
https://docs.python.org/3/library/argparse.html#argument-abbreviations-prefix-matching
https://docs.python.org/3/library/argparse.html#beyond-sys-argv
https://docs.python.org/3/library/argparse.html#the-namespace-object
https://docs.python.org/3/library/argparse.html#other-utilities
https://docs.python.org/3/library/argparse.html#sub-commands
https://docs.python.org/3/library/argparse.html#filetype-objects
https://docs.python.org/3/library/argparse.html#argument-groups
https://docs.python.org/3/library/argparse.html#mutual-exclusion
https://docs.python.org/3/library/argparse.html#parser-defaults
https://docs.python.org/3/library/argparse.html#printing-help
https://docs.python.org/3/library/argparse.html#partial-parsing
https://docs.python.org/3/library/argparse.html#customizing-file-parsing
https://docs.python.org/3/library/argparse.html#exiting-methods
https://docs.python.org/3/library/argparse.html#intermixed-parsing
https://docs.python.org/3/library/argparse.html#upgrading-optparse-code


Regular Expression HOWTO
https://docs.python.org/3/howto/regex.html

6.2. re — Regular expression operations
https://docs.python.org/3/library/re.html#regular-expression-syntax
https://docs.python.org/3/library/re.html#module-contents
https://docs.python.org/3/library/re.html#regular-expression-objects
https://docs.python.org/3/library/re.html#match-objects
https://docs.python.org/3/library/re.html#regular-expression-examples
https://docs.python.org/3/library/re.html#checking-for-a-pair
https://docs.python.org/3/library/re.html#simulating-scanf
https://docs.python.org/3/library/re.html#search-vs-match
https://docs.python.org/3/library/re.html#making-a-phonebook
https://docs.python.org/3/library/re.html#text-munging
https://docs.python.org/3/library/re.html#finding-all-adverbs
https://docs.python.org/3/library/re.html#finding-all-adverbs-and-their-positions
https://docs.python.org/3/library/re.html#raw-string-notation
https://docs.python.org/3/library/re.html#writing-a-tokenizer


Unicode HOWTO
https://docs.python.org/3/howto/unicode.html


https://www.sqlite.org/index.html
https://docs.python.org/3/library/sqlite3.html

https://docs.python.org/3/library/cgi.html
https://docs.python.org/3/library/wsgiref.html

22.5. urllib — URL handling modules

https://docs.python.org/3/library/urllib.html


26.1. typing — Support for type hints
https://docs.python.org/3/library/typing.html


14. File Formats
https://docs.python.org/3/library/fileformats.html

6. Text Processing Services
https://docs.python.org/3/library/text.html

21. Structured Markup Processing Tools
21.1. html — HyperText Markup Language support
21.2. html.parser — Simple HTML and XHTML parser
21.3. html.entities — Definitions of HTML general entities

20. Structured Markup Processing Tools
https://docs.python.org/3/library/markup.html
20.1. html — HyperText Markup Language support
https://docs.python.org/3/library/html.html

https://docs.python.org/3/library/html.parser.html
https://docs.python.org/3/library/html.parser.html#example-html-parser-application
https://docs.python.org/3/library/html.parser.html#htmlparser-methods
https://docs.python.org/3/library/html.parser.html#examples
https://docs.python.org/3/library/html.entities.html


22.22. http.server — HTTP servers
22.23. http.cookies — HTTP state management
22.24. http.cookiejar — Cookie handling for HTTP clients

Not recommended for production
https://docs.python.org/3/library/http.server.html
https://docs.python.org/3/library/http.cookies.html
https://docs.python.org/3/library/http.cookiejar.html
-->


## Django System Checks, Error Reporting, Exceptions

* [Django System Checks](https://docs.djangoproject.com/en/dev/topics/checks)
* [Django Error Reporting](https://docs.djangoproject.com/en/dev/howto/error-reporting)
* [Django Exceptions](https://docs.djangoproject.com/en/dev/ref/exceptions)

<!--
https://docs.djangoproject.com/en/2.1/topics/testing/tools/#transactiontestcase

Django Core Exceptions
AppRegistryNotReady, 1014
ObjectDoesNotExist, 1015 
EmptyResultSet, 1015 
FieldDoesNotExist, 1015 
MultipleObjectsReturned, 1015 
SuspiciousOperation, 1015 
PermissionDenied, 1016 
ViewDoesNotExist, 1016 
MiddlewareNotUsed, 1016 
ImproperlyConfigured, 1016 
FieldError, 1016 
ValidationError, 1016 
NON_FIELD_ERRORS

URL Resolver exceptions
Resolver404
NoReverseMatch, 1017 

Database Exceptions

Http Exceptions
UnreadablePostError, 1018 

Transaction Exceptions
TransactionManagementError, 1018 

Testing Framework Exceptions
RedirectCycleError

Python Exceptions


## Django Errors and Exceptions

DoesNotExist
Model.DoesNotExist, 1155
TemplateDoesNotExist, 276 

Django Errors
PageNotAnInteger, 507 
ContextPopException, 1376 
EmptyPage, 507 

Errors
IntegrityError, 1017 
InterfaceError, 1017 
InternalError, 1017 
models.ProtectedError, 1017 
OperationalError, 1017 
NotSupportedError, 1017 
CommandError, 545 
DatabaseError, 1017 
DataError, 1017 
Error, 1017 
client.RedirectCycleError, 1018  
ProgrammingError, 1017 
TemplateSyntaxError, 276 
-->
   
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
https://docs.python.org/3/reference/compound_stmts.html#try
https://docs.python.org/3/reference/compound_stmts.html#except
https://docs.python.org/3/reference/compound_stmts.html#finally

from
https://docs.python.org/3/reference/simple_stmts.html#from

7.8. The raise statement
https://docs.python.org/3/reference/simple_stmts.html#raise
-->

## Exceptions and Errors

Repeat
16.1.1. Error Handling
https://docs.python.org/3/tutorial/appendix.html#error-handling

8. Errors and Exceptions
8.1. Syntax Errors
8.2. Exceptions
8.3. Handling Exceptions
8.4. Raising Exceptions
8.5. User-defined Exceptions
8.6. Defining Clean-up Actions
8.7. Predefined Clean-up Actions

* [errors](https://docs.python.org/3/tutorial/errors.html)

https://docs.python.org/3/tutorial/errors.html#errors-and-exceptions
https://docs.python.org/3/tutorial/errors.html#syntax-errors
https://docs.python.org/3/tutorial/errors.html#exceptions
https://docs.python.org/3/tutorial/errors.html#handling-exceptions
https://docs.python.org/3/tutorial/errors.html#raising-exceptions
https://docs.python.org/3/tutorial/errors.html#user-defined-exceptions
https://docs.python.org/3/tutorial/errors.html#defining-clean-up-actions
https://docs.python.org/3/tutorial/errors.html#predefined-clean-up-actions

## Python Built-In Exceptions Hierarchy

<!--
The most common exceptions?

https://docs.python.org/3/library/exceptions.html#KeyboardInterrupt
https://docs.python.org/3/library/exceptions.html#TypeError | Built-in Exceptions — Python 3.8.3 documentation
https://docs.python.org/3/library/exceptions.html#NameError | Built-in Exceptions — Python 3.8.3 documentation
https://docs.python.org/3/library/exceptions.html#ValueError | Built-in Exceptions — Python 3.8.3 documentation
-->

5. Built-in Exceptions
5.1. Base classes
5.2. Concrete exceptions
5.3. Warnings
5.4. Exception hierarchy

* [exceptions](https://docs.python.org/3/library/exceptions.html)

https://docs.python.org/3/library/exceptions.html#base-classes
https://docs.python.org/3/library/exceptions.html#concrete-exceptions

https://docs.python.org/3/library/exceptions.html#os-exceptions


Django raises built-in Python exceptions when appropriate.
https://docs.python.org/3/library/exceptions.html#built-in-exceptions

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
        
## Warnings

https://docs.python.org/3/library/exceptions.html#warnings

Python Warnings
* [warnings](https://docs.python.org/3/library/warnings.html)

30.5. warnings — Warning control
https://docs.python.org/3/library/warnings.html#warning-categories
https://docs.python.org/3/library/warnings.html#the-warnings-filter
https://docs.python.org/3/library/warnings.html#describing-warning-filters
https://docs.python.org/3/library/warnings.html#default-warning-filter
https://docs.python.org/3/library/warnings.html#overriding-the-default-filter
https://docs.python.org/3/library/warnings.html#temporarily-suppressing-warnings
https://docs.python.org/3/library/warnings.html#testing-warnings
https://docs.python.org/3/library/warnings.html#updating-code-for-new-versions-of-dependencies
https://docs.python.org/3/library/warnings.html#available-functions
https://docs.python.org/3/library/warnings.html#available-context-managers

## Performance

36.11. resource — Resource usage information
https://docs.python.org/3/library/resource.html
https://docs.python.org/3/library/resource.html#resource-limits
https://docs.python.org/3/library/resource.html#resource-usage

10.11. Quality Control
https://docs.python.org/3/tutorial/stdlib.html#quality-control

10.10. Performance Measurement
https://docs.python.org/3/tutorial/stdlib.html#performance-measurement

28.4. The Python Profilers
28.5. timeit — Measure execution time of small code snippets
28.6. trace — Trace or track Python statement execution
https://docs.python.org/3/library/profile.html
https://docs.python.org/3/library/timeit.html
https://docs.python.org/3/library/trace.html

https://docs.python.org/3/library/profile.html#module-profile
https://docs.python.org/3/library/timeit.html#module-timeit
https://docs.python.org/3/library/profile.html#module-pstats


https://docs.python.org/3/library/profile.html
https://docs.python.org/3/library/profile.html#introduction-to-the-profilers
https://docs.python.org/3/library/profile.html#instant-user-s-manual
https://docs.python.org/3/library/profile.html#module-cProfile
https://docs.python.org/3/library/profile.html#the-stats-class
https://docs.python.org/3/library/profile.html#what-is-deterministic-profiling
https://docs.python.org/3/library/profile.html#limitations
https://docs.python.org/3/library/profile.html#calibration
https://docs.python.org/3/library/profile.html#using-a-custom-timer

https://docs.python.org/3/library/timeit.html
https://docs.python.org/3/library/timeit.html#basic-examples
https://docs.python.org/3/library/timeit.html#python-interface
https://docs.python.org/3/library/timeit.html#command-line-interface
https://docs.python.org/3/library/timeit.html#examples

https://docs.python.org/3/library/trace.html
https://docs.python.org/3/library/trace.html#command-line-usage
https://docs.python.org/3/library/trace.html#main-options
https://docs.python.org/3/library/trace.html#modifiers
https://docs.python.org/3/library/trace.html#filters
https://docs.python.org/3/library/trace.html#programmatic-interface

29.9. traceback — Print or retrieve a stack traceback
https://docs.python.org/3/library/traceback.html
https://docs.python.org/3/library/traceback.html#tracebackexception-objects
https://docs.python.org/3/library/traceback.html#stacksummary-objects
https://docs.python.org/3/library/traceback.html#framesummary-objects
https://docs.python.org/3/library/traceback.html#traceback-examples

## Logging

11.5. Logging
https://docs.python.org/3/tutorial/stdlib2.html#logging
https://docs.python.org/3/library/logging.html#module-logging

## Tests

27.3. doctest — Test interactive Python examples
https://docs.python.org/3/library/doctest.html
https://docs.python.org/3/library/doctest.html#simple-usage-checking-examples-in-docstrings
https://docs.python.org/3/library/doctest.html#simple-usage-checking-examples-in-a-text-file
https://docs.python.org/3/library/doctest.html#how-it-works
https://docs.python.org/3/library/doctest.html#which-docstrings-are-examined
https://docs.python.org/3/library/doctest.html#how-are-docstring-examples-recognized
https://docs.python.org/3/library/doctest.html#what-s-the-execution-context
https://docs.python.org/3/library/doctest.html#what-about-exceptions
https://docs.python.org/3/library/doctest.html#option-flags
https://docs.python.org/3/library/doctest.html#directives
https://docs.python.org/3/library/doctest.html#warnings
https://docs.python.org/3/library/doctest.html#basic-api
https://docs.python.org/3/library/doctest.html#unittest-api
https://docs.python.org/3/library/doctest.html#advanced-api
https://docs.python.org/3/library/doctest.html#doctest-objects
https://docs.python.org/3/library/doctest.html#example-objects
https://docs.python.org/3/library/doctest.html#doctestfinder-objects
https://docs.python.org/3/library/doctest.html#doctestparser-objects
https://docs.python.org/3/library/doctest.html#doctestrunner-objects
https://docs.python.org/3/library/doctest.html#outputchecker-objects
https://docs.python.org/3/library/doctest.html#debugging
https://docs.python.org/3/library/doctest.html#soapbox


https://docs.pytest.org/en/stable/

27.4. unittest — Unit testing framework
27.5. unittest.mock — mock object library
27.6. unittest.mock — getting started
27.8. test — Regression tests package for Python
27.9. test.support — Utilities for the Python test suite
27.10. test.support.script_helper — Utilities for the Python execution tests

https://docs.python.org/3/library/unittest.html#unittest.TestCase

7.3. The assert statement
https://docs.python.org/3/reference/simple_stmts.html#the-assert-statement
AssertionError

Where is this?
https://docs.python.org/3/library/unittest.html#assert-methods

https://docs.python.org/3/library/unittest.html#test-discovery

https://docs.python.org/3/library/unittest.html
https://docs.python.org/3/library/unittest.html#basic-example
https://docs.python.org/3/library/unittest.html#command-line-interface
https://docs.python.org/3/library/unittest.html#command-line-options
https://docs.python.org/3/library/unittest.html#organizing-test-code
https://docs.python.org/3/library/unittest.html#re-using-old-test-code
https://docs.python.org/3/library/unittest.html#skipping-tests-and-expected-failures
https://docs.python.org/3/library/unittest.html#distinguishing-test-iterations-using-subtests
https://docs.python.org/3/library/unittest.html#classes-and-functions
https://docs.python.org/3/library/unittest.html#test-cases
https://docs.python.org/3/library/unittest.html#deprecated-aliases
https://docs.python.org/3/library/unittest.html#grouping-tests
https://docs.python.org/3/library/unittest.html#loading-and-running-tests
https://docs.python.org/3/library/unittest.html#class-and-module-fixtures
https://docs.python.org/3/library/unittest.html#setupclass-and-teardownclass
https://docs.python.org/3/library/unittest.html#setupmodule-and-teardownmodule
https://docs.python.org/3/library/unittest.html#signal-handling

unittest.mock patch
https://docs.python.org/3/library/unittest.mock.html
https://docs.python.org/3/library/unittest.mock.html#quick-guide
https://docs.python.org/3/library/unittest.mock.html#the-mock-class
https://docs.python.org/3/library/unittest.mock.html#calling
https://docs.python.org/3/library/unittest.mock.html#deleting-attributes
https://docs.python.org/3/library/unittest.mock.html#mock-names-and-the-name-attribute
https://docs.python.org/3/library/unittest.mock.html#attaching-mocks-as-attributes
https://docs.python.org/3/library/unittest.mock.html#the-patchers
https://docs.python.org/3/library/unittest.mock.html#patch
https://docs.python.org/3/library/unittest.mock.html#patch-object
https://docs.python.org/3/library/unittest.mock.html#patch-dict
https://docs.python.org/3/library/unittest.mock.html#patch-multiple
https://docs.python.org/3/library/unittest.mock.html#patch-methods-start-and-stop
https://docs.python.org/3/library/unittest.mock.html#patch-builtins
https://docs.python.org/3/library/unittest.mock.html#test-prefix
https://docs.python.org/3/library/unittest.mock.html#nesting-patch-decorators
https://docs.python.org/3/library/unittest.mock.html#where-to-patch
https://docs.python.org/3/library/unittest.mock.html#patching-descriptors-and-proxy-objects
https://docs.python.org/3/library/unittest.mock.html#magicmock-and-magic-method-support
https://docs.python.org/3/library/unittest.mock.html#mocking-magic-methods
https://docs.python.org/3/library/unittest.mock.html#magic-mock
https://docs.python.org/3/library/unittest.mock.html#helpers
https://docs.python.org/3/library/unittest.mock.html#sentinel
https://docs.python.org/3/library/unittest.mock.html#default
https://docs.python.org/3/library/unittest.mock.html#call
https://docs.python.org/3/library/unittest.mock.html#create-autospec
https://docs.python.org/3/library/unittest.mock.html#any
https://docs.python.org/3/library/unittest.mock.html#filter-dir
https://docs.python.org/3/library/unittest.mock.html#mock-open
https://docs.python.org/3/library/unittest.mock.html#autospeccing
https://docs.python.org/3/library/unittest.mock.html#sealing-mocks

https://docs.python.org/3/library/unittest.mock-examples.html
https://docs.python.org/3/library/unittest.mock-examples.html#unittest-mock-getting-started
https://docs.python.org/3/library/unittest.mock-examples.html#using-mock
https://docs.python.org/3/library/unittest.mock-examples.html#mock-patching-methods
https://docs.python.org/3/library/unittest.mock-examples.html#mock-for-method-calls-on-an-object
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-classes
https://docs.python.org/3/library/unittest.mock-examples.html#naming-your-mocks
https://docs.python.org/3/library/unittest.mock-examples.html#tracking-all-calls
https://docs.python.org/3/library/unittest.mock-examples.html#setting-return-values-and-attributes
https://docs.python.org/3/library/unittest.mock-examples.html#raising-exceptions-with-mocks
https://docs.python.org/3/library/unittest.mock-examples.html#side-effect-functions-and-iterables
https://docs.python.org/3/library/unittest.mock-examples.html#creating-a-mock-from-an-existing-object
https://docs.python.org/3/library/unittest.mock-examples.html#patch-decorators
https://docs.python.org/3/library/unittest.mock-examples.html#further-examples
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-chained-calls
https://docs.python.org/3/library/unittest.mock-examples.html#partial-mocking
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-a-generator-method
https://docs.python.org/3/library/unittest.mock-examples.html#applying-the-same-patch-to-every-test-method
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-unbound-methods
https://docs.python.org/3/library/unittest.mock-examples.html#checking-multiple-calls-with-mock
https://docs.python.org/3/library/unittest.mock-examples.html#coping-with-mutable-arguments
https://docs.python.org/3/library/unittest.mock-examples.html#nesting-patches
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-a-dictionary-with-magicmock
https://docs.python.org/3/library/unittest.mock-examples.html#mock-subclasses-and-their-attributes
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-imports-with-patch-dict
https://docs.python.org/3/library/unittest.mock-examples.html#tracking-order-of-calls-and-less-verbose-call-assertions
https://docs.python.org/3/library/unittest.mock-examples.html#more-complex-argument-matching
