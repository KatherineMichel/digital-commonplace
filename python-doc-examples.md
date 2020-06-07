# Python Doc Examples

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
print('Hello world!') # Comment
```

Pound sign will print within string

```python
print('#1')
```

Docstring- (multi-line, dumb quotes versus smart quotes)

```python
"""Write docstrings for ALL public classes, functions and methods.
First line of a docstring is short and next to the quotes.
Closing quotes are on their own line
"""
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

### Statements Versus Expressions

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

### Membership Operators

```
in
not in
```

(built-in sequences, set types, and dictionaries)

https://docs.python.org/3/reference/expressions.html#membership-test-operations
https://docs.python.org/3/reference/expressions.html#in
https://docs.python.org/3/reference/expressions.html#not-in

## Negation (Null Object, ```None```, ```NotImplemented```)

### Logical Operators

```
and
or
not
```

## Boolean Values (See also: Logical Operators)

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

## Built-In Functions- Numbers

Take two (non complex) numbers as arguments and return a pair of numbers consisting of their quotient and remainder when using integer division. 
```divmod()```

Return x to the power y; if z is present, return x to the power y, modulo z

```pow()```

Return number rounded to ndigits precision after the decimal point. 
```round()```

Return the absolute value of a number. The argument may be an integer or a floating point number. If the argument is a complex number, its magnitude is returned.
```abs()```

## Python Code Block Examples

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

## pass Statements

Nothing happens when the pass statement executes.

null operation
4.5. pass Statements
https://docs.python.org/3/tutorial/controlflow.html#pass-statements
7.4. The pass statement
https://docs.python.org/3/reference/simple_stmts.html#the-pass-statement

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
