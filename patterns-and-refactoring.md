# Patterns and Refactoring

## Programming Paradigms

Programming Paradigms
* [Programming Paradigm Wikipedia](https://en.wikipedia.org/wiki/Programming_paradigm)
* [Comparison of Programming Paradigms Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_programming_paradigms)

Software Paradigm Types
* [Functional Programming Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)
* [Purely Functional Programming Wikipedia](https://en.wikipedia.org/wiki/Purely_functional_programming)
* [Object Oriented Programming Wikipedia](https://en.wikipedia.org/wiki/Object-oriented_programming)
* [Class Based Programming Wikipedia](https://en.wikipedia.org/wiki/Class-based_programming)
* [Prototype Based Programming Wikipedia](https://en.wikipedia.org/wiki/Prototype-based_programming)

React?
* [Imperative Programming Wikipedia](https://en.wikipedia.org/wiki/Imperative_programming)
* [Declarative Programming Wikipedia](https://en.wikipedia.org/wiki/Declarative_programming)
* [Reactive Programming Wikipedia](https://en.wikipedia.org/wiki/Reactive_programming)

<!--
taxonomy of programming paradigms
https://www.info.ucl.ac.be/~pvr/paradigmsDIAGRAMeng108.jpg

Programming Paradigms for Dummies: What Every Programmer Should Know
https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf | VanRoyChapter.pdf
https://www.info.ucl.ac.be/~pvr/paradigms.html | Classification of the principal programming paradigms
Programming concepts Section 4 explains the four most important concepts in programming: records, lexically scoped closures, independence (concurrency), and named
state.
Data abstraction Section 5 explains how to define new forms of data with their operations in a program. We show the four kinds of data abstractions: objects and abstract
data types are the two most popular, but there exist two others, declarative objects and
stateful abstract data types.

https://famicol.in/language_checklist.html | Programming Language Checklist
https://twitter.com/davecheney/status/1032519492641816576 | Dave Cheney on Twitter: "… "
-->

<!--
https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95

Interview Series
https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36
https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9
https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976#.4256pjcfq
https://medium.com/javascript-scene/master-the-javascript-interview-what-is-function-composition-20dfb109a1a0#.i84zm53fb
https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0
https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261
https://medium.com/javascript-scene/master-the-javascript-interview-soft-skills-a8a5fb02c466

https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3
https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4

https://medium.com/javascript-scene/composing-software-an-introduction-27b72500d6ea

Composition Series
https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c
https://medium.com/javascript-scene/why-learn-functional-programming-in-javascript-composing-software-ea13afc7a257
https://medium.com/javascript-scene/a-functional-programmers-introduction-to-javascript-composing-software-d670d14ede30
https://medium.com/javascript-scene/higher-order-functions-composing-software-5365cf2cbe99
https://medium.com/javascript-scene/reduce-composing-software-fe22f0c39a1d
https://medium.com/javascript-scene/functors-categories-61e031bac53f
https://medium.com/javascript-scene/functional-mixins-composing-software-ffb66d5e731c
https://medium.com/javascript-scene/javascript-factory-functions-with-es6-4d224591a8b1
https://medium.com/javascript-scene/why-composition-is-harder-with-classes-c3e627dcd0aa
https://medium.com/javascript-scene/composable-datatypes-with-functions-aec72db3b093
https://medium.com/javascript-scene/javascript-monads-made-simple-7856be57bfe8
-->

## Useful Terminology

Object
* [Object Composition Wikipedia](https://en.wikipedia.org/wiki/Object_composition)
* [Constructor Python Wikipedia](https://en.wikipedia.org/wiki/Constructor_(object-oriented_programming)#Python)

Object Oriented Software Characteristics
* [Abstraction Wikipedia](https://en.wikipedia.org/wiki/Abstraction_(computer_science))
* [Encapsulation Wikipedia](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming))
* [Inheritance Wikipedia](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming))
* [Polymorphism Wikipedia](https://en.wikipedia.org/wiki/Polymorphism_(computer_science))

State
* [State Wikipedia](https://en.wikipedia.org/wiki/State_(computer_science))
* [Stateless Protocol Wikipedia](https://en.wikipedia.org/wiki/Stateless_protocol)
* [Persistence Wikipedia](https://en.wikipedia.org/wiki/Persistence_(computer_science))
* [Persistent Data Structure Wikipedia](https://en.wikipedia.org/wiki/Persistent_data_structure)

Functional Programming
* [Immutable Object Wikipedia](https://en.wikipedia.org/wiki/Immutable_object)

<!--
Python/Django state
JavaScript state

Stateless
"Examples of stateless protocols include the Internet Protocol (IP), which is the foundation for the Internet, and the Hypertext Transfer Protocol (HTTP), which is the foundation of data communication for the World Wide Web."

https://github.com/getify/Functional-Light-JS/blob/master/manuscript/ch1.md/#chapter-1-why-functional-programming | Functional-Light-JS/ch1.md at master · getify/Functional-Light-JS

https://developer.mozilla.org/en-US/docs/Glossary/First-class_Function | First-class Function - MDN Web Docs Glossary: Definitions of Web-related terms | MDN
https://en.wikipedia.org/wiki/First-class_function
https://en.wikipedia.org/wiki/Higher-order_function
https://en.wikipedia.org/wiki/Anonymous_function | Anonymous function - Wikipedia
https://en.wikipedia.org/wiki/Map_(higher-order_function) | Map (higher-order function) - Wikipedia

https://en.wikipedia.org/wiki/State_diagram

https://en.wikipedia.org/wiki/Persistent_data_structure#Partially_persistent | Persistent data structure - Wikipedia

https://en.wikipedia.org/wiki/Memoization

https://medium.com/javascript-scene/encapsulation-in-javascript-26be60e325b4

functional programming- immutability/immutable data structures

https://realpython.com/courses/functional-programming-python/
https://realpython.com/lessons/immutable-data-structures-namedtuple/

https://realpython.com/modeling-polymorphism-django-python/

https://github.com/hemanth/functional-programming-jargon | hemanth/functional-programming-jargon: Jargon from the functional programming world in simple terms!
https://github.com/xgrommx/awesome-functional-programming | xgrommx/awesome-functional-programming: Yet another resource for collecting articles, videos etc. regarding functional programming
https://github.com/fantasyland/fantasy-land/blob/master/README.md | fantasy-land/README.md at master · fantasyland/fantasy-land

https://en.wikipedia.org/wiki/Functional_programming
Closure
https://en.wikipedia.org/wiki/Closure_(computer_programming)
Currying
https://en.wikipedia.org/wiki/Currying
Idempotent
https://en.wikipedia.org/wiki/Idempotence
Functor
https://en.wikipedia.org/wiki/Functor
Lambda
https://en.wikipedia.org/wiki/Lambda
Lambda Calculus
https://en.wikipedia.org/wiki/Lambda_calculus
Lazy evaluation
https://en.wikipedia.org/wiki/Lazy_evaluation
Monoid
https://en.wikipedia.org/wiki/Monoid
Monad
https://en.wikipedia.org/wiki/Monad_(functional_programming)
Isomorphism
Function
Partial function
-->

## GRASP and Clean Architecture (Follows SOLID Principles)

Object Oriented Software Construction Principles
* [GRASP (Object Oriented Design) Wikipedia](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))
* [SOLID (Object Oriented Design) Wikipedia](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design))

Software Principles (SOLID)
* [Single Responsibility Principle Wikipedia](https://en.wikipedia.org/wiki/Single_responsibility_principle)
* [Separation of Concerns Wikipedia](https://en.wikipedia.org/wiki/Separation_of_concerns)
* [Open-Closed Principle Wikipedia](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)
* [Liskov Substitution Principle Wikipedia](https://en.wikipedia.org/wiki/Liskov_substitution_principle)
* [Interface Segregation Principle Wikipedia](https://en.wikipedia.org/wiki/Interface_segregation_principle)
* [Dependency Inversion Principle Wikipedia](https://en.wikipedia.org/wiki/Dependency_inversion_principle)

<!--
Pattern
https://en.wikipedia.org/wiki/Dependency_injection
https://en.wikipedia.org/wiki/Separation_of_concerns
https://en.wikipedia.org/wiki/Inversion_of_control

https://en.wikipedia.org/wiki/Interface_(computing)

Clean Architectures in Python - Leonardo Giordani - PyLondinium19
https://www.youtube.com/watch?v=wtCQalq7L-E
-->

## General Software Design Patterns

Types of Patterns
* [Creational Pattern Wikipedia](https://en.wikipedia.org/wiki/Creational_pattern)
* [Structural Pattern Wikipedia](https://en.wikipedia.org/wiki/Structural_pattern)
* [Behavioral Pattern Wikipedia](https://en.wikipedia.org/wiki/Behavioral_pattern)

Creational Patterns (object creation)
* [Singleton Pattern Wikipedia](https://en.wikipedia.org/wiki/Singleton_pattern)
* [Factory Method Pattern Wikipedia](https://en.wikipedia.org/wiki/Factory_method_pattern)

Creational Patterns- Can use Singleton in Implementation
* [Abstract Factory Pattern Wikipedia](https://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [Builder Pattern Wikipedia](https://en.wikipedia.org/wiki/Builder_pattern)
* [Prototype Pattern Wikipedia](https://en.wikipedia.org/wiki/Prototype_pattern)

Structural Patterns (relationships among entities)
* [Adapter Pattern Wikipedia](https://en.wikipedia.org/wiki/Adapter_pattern)
* [Bridge Pattern Wikipedia](https://en.wikipedia.org/wiki/Bridge_pattern)
* [Composite Pattern Wikipedia](https://en.wikipedia.org/wiki/Composite_pattern)
* [Decorator Pattern (similar to Chain of Responsibility Pattern; implements Single Responsibility Principal) Wikipedia](https://en.wikipedia.org/wiki/Decorator_pattern)
* [Facade Pattern Wikipedia](https://en.wikipedia.org/wiki/Facade_pattern)
* [Flyweight Pattern Wikipedia](https://en.wikipedia.org/wiki/Flyweight_pattern)
* [Proxy Pattern Wikipedia](https://en.wikipedia.org/wiki/Proxy_pattern)

Behavioral Patterns
* [Observer Pattern Wikipedia](https://en.wikipedia.org/wiki/Observer_pattern)
* [Chain-of-Responsibility Pattern (similar to Decorator Pattern) Wikipedia](https://en.wikipedia.org/wiki/Chain-of-responsibility_pattern)
* [Command Pattern Wikipedia](https://en.wikipedia.org/wiki/Command_pattern)
* [Interpreter Pattern Wikipedia](https://en.wikipedia.org/wiki/Interpreter_pattern)
* [Mediator Pattern Wikipedia](https://en.wikipedia.org/wiki/Mediator_pattern)
* [Memento Pattern Wikipedia](https://en.wikipedia.org/wiki/Memento_pattern)
* [State Pattern Wikipedia](https://en.wikipedia.org/wiki/State_pattern)
* [Strategy Pattern Wikipedia](https://en.wikipedia.org/wiki/Strategy_pattern)
* [Template Method Pattern Wikipedia](https://en.wikipedia.org/wiki/Template_method_pattern)
* [Visitor Pattern Wikipedia](https://en.wikipedia.org/wiki/Visitor_pattern)

Behavioral Patterns- Built into Python
* [Iterator Pattern Wikipedia Article](https://en.wikipedia.org/wiki/Iterator_pattern)

JavaScript Patterns
* [Stoyan Stefanov: TLDR JavaScript Design Patterns](https://github.com/karlpatrickespiritu/TLDR-Learning-JS-Design-Patterns-by-Addy-Osmani)
* [Addy Osmani: JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book) and [Addy Osmani: JavaScript Design Patterns GitHub](https://github.com/addyosmani/essential-js-design-patterns)
* [Addy Osmani: Patterns For Large-Scale JavaScript Application Architecture](https://addyosmani.com/largescalejavascript/)

<!--
https://github.com/sohamkamani/javascript-design-patterns-for-humans | sohamkamani/javascript-design-patterns-for-humans: An ultra-simplified explanation of design patterns implemented in javascript

Important
https://web.archive.org/web/20170104081026/https://github.com/ericelliott/essential-javascript-links

https://en.wikipedia.org/wiki/State_pattern
https://en.wikipedia.org/wiki/Finite-state_machine
-->

## Refactoring

<!--
Tags
basic
encapsulation
moving-features
organizing-data
simplify-conditional-logic
refactoring-apis
dealing-with-inheritance
collections
delegation
errors
extract
parameters
fragments
grouping-function
immutability
inline
remove
rename
split-phase
variables

Change Function Declaration
• Add Parameter 
• Change Signature 
• Remove Parameter 
• Rename Function 
• Rename Method

Change Reference to Value
Change Value to Reference
Collapse Hierarchy
Combine Functions into Class
Combine Functions into Transform
Consolidate Conditional Expression
Decompose Conditional
Encapsulate Collection
Encapsulate Record
• Replace Record with Data Class

Encapsulate Variable
• Encapsulate Field 
• Self-Encapsulate Field

Extract Class
Extract Function
Extract Method

Extract Superclass
Extract Variable
• Introduce Explaining Variable

Hide Delegate
Inline Class
Inline Function
• Inline Method

Inline Variable
• Inline Temp

Introduce Assertion
Introduce Parameter Object
Introduce Special Case
• Introduce Null Object

Move Field
Move Function
• Move Method

Move Statements into Function
Move Statements to Callers
Parameterize Function
• Parameterize Method

Preserve Whole Object
Pull Up Constructor Body
Pull Up Field
Pull Up Method
Push Down Field
Push Down Method
Remove Dead Code
Remove Flag Argument
• Replace Parameter with Explicit Methods

Remove Middle Man
Remove Setting Method
Remove Subclass
• Replace Subclass with Fields

Rename Field
Rename Variable
Replace Command with Function
Replace Conditional with Polymorphism
Replace Constructor with Factory Function
• Replace Constructor with Factory Method

Replace Control Flag with Break
• Remove Control Flag

Replace Derived Variable with Query
Replace Error Code with Exception
Replace Exception with Precheck
• Replace Exception with Test

Replace Function with Command
• Replace Method with Method Object

Replace Inline Code with Function Call
Replace Loop with Pipeline
Replace Magic Literal
• Replace Magic Number with Symbolic Constant

Replace Nested Conditional with Guard Clauses
Replace Parameter with Query
• Replace Parameter with Method

Replace Primitive with Object
• Replace Data Value with Object 
• Replace Type Code with Class

Replace Query with Parameter
Replace Subclass with Delegate
Replace Superclass with Delegate
• Replace Inheritance with Delegation

Replace Temp with Query
Replace Type Code with Subclasses
• Extract Subclass 
• Replace Type Code with State/Strategy

Return Modified Value
Separate Query from Modifier
Slide Statements
• Consolidate Duplicate Conditional Fragments

Split Loop
Split Phase
Split Variable
• Remove Assignments to Parameters 
• Split Temp

Substitute Algorithm
-->
