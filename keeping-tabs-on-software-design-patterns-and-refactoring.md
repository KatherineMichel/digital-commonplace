# Software Design Patterns and Refactoring

<!--
## Functional Programming

https://github.com/readme/guides/functional-programming-basics | Functional Programming 101
https://www.quora.com/Why-dont-pure-functional-programming-languages-provide-a-loop-construct | Why don't pure functional programming languages provide a loop construct? - Quora


Algos by category
https://www.linkedin.com/pulse/list-algorithms-computer-programming-pranam-bhat/


## Scaling Django

https://technobeans.com/2020/12/01/scaling-django-for-millions-of-users/ | Scaling Django for millions of users - TechnoBeans
https://www.digitalocean.com/community/tutorials/how-to-scale-django-beyond-the-basics | How to Scale Django: Beyond the Basics | DigitalOcean


## Software Architecture/Design Patterns

https://a16z.com/2020/10/15/emerging-architectures-for-modern-data-infrastructure/ | Emerging Architectures for Modern Data Infrastructure | Andreessen Horowitz

https://docs.gitlab.com/ee/development/architecture.html | GitLab architecture overview | GitLab

https://en.wikibooks.org/wiki/Introduction_to_Software_Engineering/Architecture/Design_Patterns | Software design patterns - Wikibooks, open books for an open world
https://en.wikipedia.org/wiki/Software_design_pattern | Software design pattern - Wikipedia
https://www.redhat.com/architect/14-software-architecture-patterns | 14 software architecture design patterns to know | Enable Architect
https://martinfowler.com/ieeeSoftware/whoNeedsArchitect.pdf | s5des.lo

https://javarevisited.blogspot.com/2021/09/microservices-design-patterns-principles.html#axzz7UN64FOOL | Top 10 Microservices Design Patterns and Principles - Examples


## Clean Code, Architecture

https://www.agilealliance.org/contact/ | Contact Us | Agile Alliance

https://twitter.com/dhh/status/1699910613777141895 | DHH on X: "On Microservices vs Monolith. https://t.co/ZuyGrwrM0Q" / X

https://github.com/sivaprasadreddy/tomato-architecture | sivaprasadreddy/tomato-architecture: Tomato Architecture - A common sense driven approach to software architecture

Thinking in Systems
https://twitter.com/sarah_edo/status/1597598815959527425 | https://twitter.com/sarah_edo/status/1597598815959527425



## Software Architecture Tools

Devs Need System Design Tools, Not Diagramming Tools
https://thenewstack.io/devs-need-system-design-tools-not-diagramming-tools/

https://www.infoq.com/articles/framework-architectural-decisions/ | A Simple Framework for Architectural Decisions

Domain Driven Model

TLA+
https://www.youtube.com/watch?v=SYtkbv8LNv0&t=1s | (20) Software Architecture Principles From 5 Leading Experts - YouTube
https://www.thestrangeloop.com/2021/tla-plus-conference.html
https://c4model.com/ | The C4 model for visualising software architecture
https://en.wikipedia.org/wiki/C4_model | C4 model - Wikipedia
https://plantuml.com/ | Open-source tool that uses simple textual descriptions to draw beautiful UML diagrams.
https://en.wikipedia.org/wiki/4%2B1_architectural_view_model | 4+1 architectural view model - Wikipedia


## Socratic Method

https://opensource.com/open-organization/17/5/better-it-socratic-method?sc_cid=7016000000127L3AAI | Using the Socratic method with your IT team | Opensource.com
https://en.wikipedia.org/wiki/Socratic_method | Socratic method - Wikipedia
-->

<!--
## Effective Python

Chapter 1: Pythonic Thinking
Item 1: Know Which Version of Python You’re Using
Item 2: Follow the PEP 8 Style Guide
Item 3: Know the Differences Between bytes and str
Item 4: Prefer Interpolated F-Strings Over C-style Format Strings and str.format
Item 5: Write Helper Functions Instead of Complex Expressions
Item 6: Prefer Multiple Assignment Unpacking Over Indexing
Item 7: Prefer enumerate Over range
Item 8: Use zip to Process Iterators in Parallel
Item 9: Avoid else Blocks After for and while Loops
Item 10: Prevent Repetition with Assignment Expressions

Chapter 2: Lists and Dictionaries
Item 11: Know How to Slice Sequences
Item 12: Avoid Striding and Slicing in a Single Expression
Item 13: Prefer Catch-All Unpacking Over Slicing
Item 14: Sort by Complex Criteria Using the key Parameter
Item 15: Be Cautious When Relying on dict Insertion Ordering
Item 16: Prefer get Over in and KeyError to Handle Missing Dictionary Keys
Item 17: Prefer defaultdict Over setdefault to Handle Missing Items in Internal State
Item 18: Know How to Construct Key-Dependent Default Values with __missing__

Chapters 3: Functions
Item 19: Never Unpack More Than Three Variables When Functions Return Multiple Values
Item 20: Prefer Raising Exceptions to Returning None
Item 21: Know How Closures Interact with Variable Scope
Item 22: Reduce Visual Noise with Variable Positional Arguments
Item 23: Provide Optional Behavior with Keyword Arguments
Item 24: Use None and Docstrings to Specify Dynamic Default Arguments
Item 25: Enforce Clarity with Keyword-Only and Positional-Only Arguments
Item 26: Define Function Decorators with functools.wraps

Chapter 4: Comprehensions and Generators
Item 27: Use Comprehensions Instead of map and filter
Item 28: Avoid More Than Two Control Subexpressions in Comprehensions
Item 29: Avoid Repeated Work in Comprehensions by Using Assignment Expressions
Item 30: Consider Generators Instead of Returning Lists
Item 31: Be Defensive When Iterating Over Arguments
Item 32: Consider Generator Expressions for Large List Comprehensions
Item 33: Compose Multiple Generators with yield from
Item 34: Avoid Injecting Data into Generators with send
Item 35: Avoid Causing State Transitions in Generators with throw
Item 36: Consider itertools for Working with Iterators and Generators

Chapter 5: Classes and Interfaces
Item 37: Compose Classes Instead of Nesting Many Levels of Built-in Types
Item 38: Accept Functions Instead of Classes for Simple Interfaces
Item 39: Use @classmethod Polymorphism to Construct Objects Generically
Item 40: Initialize Parent Classes with super
Item 41: Consider Composing Functionality with Mix-in Classes
Item 42: Prefer Public Attributes Over Private Ones
Item 43: Inherit from collections.abc for Custom Container Types

Chapter 6: Metaclasses and Attributes
Item 44: Use Plain Attributes Instead of Setter and Getter Methods
Item 45: Consider @property Instead of Refactoring Attributes
Item 46: Use Descriptors for Reusable @property Methods
Item 47: Use __getattr__, __getattribute__, and __setattr__ for Lazy Attributes
Item 48: Validate Subclasses with __init_subclass__
Item 49: Register Class Existence with __init_subclass__
Item 50: Annotate Class Attributes with __set_name__
Item 51: Prefer Class Decorators Over Metaclasses for Composable Class Extensions

Chapter 7: Concurrency and Parallelism
Item 52: Use subprocess to Manage Child Processes
Item 53: Use Threads for Blocking I/O, Avoid for Parallelism
Item 54: Use Lock to Prevent Data Races in Threads
Item 55: Use Queue to Coordinate Work Between Threads
Item 56: Know How to Recognize When Concurrency Is Necessary
Item 57: Avoid Creating New Thread Instances for On-demand Fan-out
Item 58: Understand How Using Queue for Concurrency Requires Refactoring
Item 59: Consider ThreadPoolExecutor When Threads Are Necessary for Concurrency
Item 60: Achieve Highly Concurrent I/O with Coroutines
Item 61: Know How to Port Threaded I/O to asyncio
Item 62: Mix Threads and Coroutines to Ease the Transition to asyncio
Item 63: Avoid Blocking the asyncio Event Loop to Maximize Responsiveness
Item 64: Consider concurrent.futures for True Parallelism

Chapter 8: Robustness and Performance
Item 65: Take Advantage of Each Block in try/except /else/finally
Item 66: Consider contextlib and with Statements for Reusable try/finally Behavior
Item 67: Use datetime Instead of time for Local Clocks
Item 68: Make pickle Reliable with copyreg
Item 69: Use decimal When Precision Is Paramount
Item 70: Profile Before Optimizing
Item 71: Prefer deque for Producer–Consumer Queues
Item 72: Consider Searching Sorted Sequences with bisect
Item 73: Know How to Use heapq for Priority Queues
Item 74: Consider memoryview and bytearray for Zero-Copy Interactions with bytes

Chapter 9: Testing and Debugging
Item 75: Use repr Strings for Debugging Output
Item 76: Verify Related Behaviors in TestCase Subclasses
Item 77: Isolate Tests from Each Other with setUp, tearDown, setUpModule, and tearDownModule
Item 78: Use Mocks to Test Code with Complex Dependencies
Item 79: Encapsulate Dependencies to Facilitate Mocking and Testing
Item 80: Consider Interactive Debugging with pdb
Item 81: Use tracemalloc to Understand Memory Usage and Leaks

Chapter 10: Collaboration
Item 82: Know Where to Find Community-Built Modules
Item 83: Use Virtual Environments for Isolated and Reproducible Dependencies
Item 84: Write Docstrings for Every Function, Class, and Module
Item 85: Use Packages to Organize Modules and Provide Stable APIs
Item 86: Consider Module-Scoped Code to Configure Deployment Environments
Item 87: Define a Root Exception to Insulate Callers from APIs
Item 88: Know How to Break Circular Dependencies
Item 89: Consider warnings to Refactor and Migrate Usage
Item 90: Consider Static Analysis via typing to Obviate Bugs
-->

<!--
## Language Creators

https://en.wikipedia.org/wiki/James_Gosling | James Gosling - Wikipedia
https://en.wikipedia.org/wiki/Anders_Hejlsberg | Anders Hejlsberg - Wikipedia
https://en.wikipedia.org/wiki/Larry_Wall | Larry Wall - Wikipedia
https://thenewstack.io/a-conversation-with-the-creators-behind-python-java-typescript-and-perl/ | A Conversation with the Creators Behind Python, Java, TypeScript, and Perl - The New Stack
-->

## Compilers Book

### Programming Language Classification

First generation
* Machine languages

Second generation
* Assembly languages

Third generation (higher-level languages)
* [Fortran Wikipedia](https://en.wikipedia.org/wiki/Lisp_(programming_language))
* [Cobol Wikipedia](https://en.wikipedia.org/wiki/COBOL)
* [Lisp Wikipedia](https://en.wikipedia.org/wiki/Lisp_(programming_language))
* C 
* C++
* C#
* Java

Fourth-generation (languages are languages designed for specific applications)
* NOMAD for report generation
* SQL for database queries
* Postscript for text formatting 

Fifth-generation (logic- and constraint-based languages)
* Prolog
* OPS5

Imperative (program specifies how a computation is to be done- there is a notion of program state and statements that change the state)
* C
* C++
* C#
* Java

Declarative (program specifies what computation is to be done)
* ML (functional)
* Haskell (functional)
* Prolog (constraint logic)

Functional
* ML (declarative)
* Hasell (declarative)

von Neumann (computational model is based on the von Neumann computer architecture)
* Many of today's languages
* Fortrain
* C

Object-oriented (a programming style in which a program consists of a collection of objects that interact with one another)
* C++
* C#
* Java
* Ruby

Scripting (interpreted languages with high-level operators de­signed for "gluing together" computations)
* Awk
* JavaScript
* Perl
* PHP
* Python
* Ruby
* Tel

<!--
https://famicol.in/language_checklist.html | Programming Language Checklist
What was this?
https://twitter.com/davecheney/status/1032519492641816576 | Dave Cheney on Twitter: "… "
-->

## Programming Languages, Types, and Paradigms

Programming Languages
* [History of Programming Languages Wikipedia](https://en.wikipedia.org/wiki/History_of_programming_languages)
* [Generational List of Programming Languages Wikipedia](https://en.wikipedia.org/wiki/Generational_list_of_programming_languages)
* [Programming Languages by Type Wikipedia](https://en.wikipedia.org/wiki/List_of_programming_languages_by_type)
  
Programming Paradigms
* [Programming Paradigm Wikipedia](https://en.wikipedia.org/wiki/Programming_paradigm)
* [Comparison of Programming Paradigms Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_programming_paradigms)

<!--
* [Dynamic Programming Language Wikipedia](https://en.wikipedia.org/wiki/Dynamic_programming_language)
-->

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
-->

### von Neumann

<!--
https://en.wikipedia.org/wiki/Von_Neumann_architecture
https://en.wikipedia.org/wiki/Von_Neumann_programming_languages

## RISC-V and ARM

RISC-V and ARM
https://en.wikipedia.org/wiki/RISC-V
https://www.arm.com/
https://en.wikipedia.org/wiki/ARM_architecture_family
-->

<!--
## Protocols

Network Communication Protocols Map
https://www.blackmagicboxes.com/wp-content/uploads/2016/12/Network-Protocols-Map-Poster.jpg 

Internet protocol suite
Application layer
BGP
DHCP (v6)
DNS
FTP
HTTP (HTTP/3)
HTTPS
IMAP
IRC
LDAP
MGCP
MQTT
NNTP
NTP
OSPF
POP
PTP
ONC/RPCRTP
RTSP
RIP
SIP
SMTP
SNMP
SSH
Telnet
TLS/SSL
XMPPmore...

Transport layer
TCP
UDP
DCCP
SCTP
RSVP
QUIC

Internet layer
IP v4v6
ICMP (v6)
NDP
ECNIGMP
IPsec

Link layer
ARP
Tunnels
PPP
MAC

https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern | Publish–subscribe pattern - Wikipedia

Pub-Sub protocol
https://en.wikipedia.org/wiki/MQTT | MQTT - Wikipedia
https://en.wikipedia.org/wiki/Comparison_of_MQTT_implementations
https://en.wikipedia.org/wiki/Message_broker
https://en.wikipedia.org/wiki/Message_queue
https://en.wikipedia.org/wiki/Message_queuing_service
https://en.wikipedia.org/wiki/Advanced_Message_Queuing_Protocol
https://en.wikipedia.org/wiki/Streaming_Text_Oriented_Messaging_Protocol
https://en.wikipedia.org/wiki/Constrained_Application_Protocol

https://en.wikipedia.org/wiki/Category:Application_layer_protocols

https://wiki.c2.com/?DataBusPattern | Data Bus Pattern

Command Query Responsibility Segregation
https://martinfowler.com/bliki/CQRS.html | CQRS

## Quic

https://en.wikipedia.org/wiki/QUIC
https://en.wikipedia.org/wiki/User_Datagram_Protocol
https://en.wikipedia.org/wiki/HTTP/3

https://en.wikipedia.org/wiki/Transport_Layer_Security
https://en.wikipedia.org/wiki/HTTP/3#Comparison_with_HTTP/1.1_and_HTTP/2
https://en.wikipedia.org/wiki/HTTP/2
https://en.wikipedia.org/wiki/HTTP
-->

## Martin Fowler

<!--
Books
https://martinfowler.com/books/

https://martinfowler.com/architecture/ | Software Architecture Guide
https://martinfowler.com/microservices/ | Microservices Guide

Service Design Patterns
Robert Daigneau
https://www.amazon.com/gp/product/032154420X

Chapter 1: From Objects to Web Services
What Are Web Services?
From Local Objects to Distributed Objects
Why Use Web Services?
Web Service Considerations and Alternatives
Services and the Promise of Loose Coupling
What about SOA?
Chapter 2: Web Service API Styles
Design Considerations for Web Service APIs
RPC API
Message API
Resource API

Chapter 3: Client-Service Interactions
Request/Response
Request/Acknowledge
Media Type Negotiation
Linked Service

Chapter 4: Request and Response Management
Service Controller
Data Transfer Object
Data-Binding Considerations
Request Mapper
Response Mapper

Chapter 5: Web Service Implementation Styles
Design Considerations for Web Service Implementation
Transaction Script
Datasource Adapter
Operation Script
Command Invoker
Workflow Connector

Chapter 6: Web Service Infrastructures
Service Connector
Service Descriptor
Asynchronous Response Handler
Service Interceptor
Idempotent Retry
A Quick Review of SOA Infrastructure Patterns
The Service Registry
The Enterprise Service Bus
The Orchestration Engine

Chapter 7: Web Service Evolution
What Causes Breaking Changes?
Structural Changes to Media Types or Messages
Service Descriptor Changes
Common Versioning Strategies
Single-Message Argument
Dataset Amendment
Tolerant Reader
Consumer-Driven Contracts
How the Patterns Promote or Hinder Service Evolution
-->

### Enterprise Application Architecture

* [Catalog of Patterns of Enterprise Application Architecture](https://martinfowler.com/eaaCatalog/)

<!--
https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=asc_df_0321127420/?tag=hyprod-20&linkCode=df0&hvadid=312128454859&hvpos=&hvnetw=g&hvrand=18143029452003884474&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9023957&hvtargid=pla-422923047050&psc=1 | Patterns of Enterprise Application Architecture: Fowler, Martin: 8601300201672: Amazon.com: Books

https://martinfowler.com/articles/enterprisePatterns.html | Enterprise Patterns
-->

### Enterprise Application Architecture Examples

<!--
Domain Logic Patterns: 
* Transaction Script (110)
* Domain Model (116) https://martinfowler.com/eaaCatalog/domainModel.html
* Table Module (125)
* Service Layer (133)

Data Source Architectural Patterns: 
* Table Data Gateway (144)
* Row Data Gateway (152)
* Active Record (160) https://www.martinfowler.com/eaaCatalog/activeRecord.html 
* Data Mapper (165)

Django
https://en.wikipedia.org/wiki/Active_record_pattern | Active record pattern - Wikipedia
https://martinfowler.com/bliki/AnemicDomainModel.html | AnemicDomainModel

Object-Relational Behavioral Patterns
* Unit of Work (184)
* Identity Map (195)
* Lazy Load (200)

Object-Relational Structural Patterns: 
* Identity Field (216)
* Foreign Key Mapping (236)
* Association Table Mapping (248)
* Dependent Mapping (262)
* Embedded Value (268)
* Serialized LOB (272)
* Single Table Inheritance (278)
* Class Table Inheritance (285)
* Concrete Table Inheritance (293)
* Inheritance Mappers (302)

Object-Relational Metadata Mapping Patterns: 
* Metadata Mapping (306)
* Query Object (316)
* Repository (322)

Web Presentation Patterns: 
* Model View Controller (330)
* Template View (350)

MVCs
* [Model View Controller Wikipedia](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)
* [Model View Controller Wikibook](http://en.wikibooks.org/wiki/Computer_Science_Design_Patterns/Model%E2%80%93view%E2%80%93controller)
* [Model–view–viewmodel Wikipedia](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)

Web Presentation Patterns: 
* Page Controller (333)
* Front Controller (344)
* Transform View (361)
* Two-Step View (365)
* Application Controller (379)

Distribution Patterns: 
* Remote Facade (388)
* Data Transfer Object (401)

Offline Concurrency Patterns: 
* Optimistic Offline Lock (416)
* Pessimistic Offline Lock (426)
* Coarse Grained Lock (438)
* Implicit Lock (449)

Session State Patterns: 
* Client Session State (456)
* Server Session State (458)
* Database Session State (462)

Base Patterns: 
* Gateway (466)
* Mapper (473)
* Layer Supertype (475)
* Separated Interface (476)
* Registry (480)
* Value Object (486)
* Money (488)
* Special Case (496)
* Plugin (499)
* Service Stub (504)
* Record Set (508)
-->

## Gregor Hohpe

<!--
https://architectelevator.com/blog/ | Architect Elevator Blog - The Architect Elevator
https://architectelevator.com/architecture/architect-bookshelf/ | The Architect’s Path (Part 2 - Bookshelf) - The Architect Elevator
https://architectelevator.com/architecture/classic-architecture-books/ | Old Books that Every Architect Should Read - The Architect Elevator
Platform Strategy
https://leanpub.com/platformstrategy
-->

### Enterprise Integration Patterns

<!--
https://www.enterpriseintegrationpatterns.com/patterns/messaging/
https://www.enterpriseintegrationpatterns.com/ramblings/eip1_examples_updated.html
https://enterpriseintegrationpatterns.com/patterns/messaging/toc.html
-->

<!--
Modern examples
https://www.enterpriseintegrationpatterns.com/ramblings/eip1_examples_updated.html
Code
https://github.com/spac3lord/eip

Publish-Subscribe Channel	Google Cloud Pub/sub
Dead Letter Channel	Amazon SQS, Kafka Connect
Return Address	GoLang
Message Expiration	Azure Service Bus, Amazon EventBridge, Google Cloud PubSub
Content-based Router	Apache Camel
Scatter-Gather	Serverless Loan Broker on AWS, Mulesoft ESB, Azure Durable Functions: Fan out/fan in
Message Filter	RabbitMQ
Aggregator	Serverless Loan Broker on AWS (Lambda, DynamoDB), Serverless Loan Broker on GCP (Cloud Function, Datastore)
Process Manager	Serverless Loan Broker with AWS Step Functions, Serverless Loan Broker with GCP Workflows
Content Enricher	Amazon EventBridge Pipes
Transactional Client	Amazon SQS
Event-driven Consumer	RabbitMQ
Competing Consumers	Apache Kafka
Channel Purger	Amazon SQS


Integration Styles
Introduction to Integration Styles
https://www.enterpriseintegrationpatterns.com/patterns/messaging/Chapter1.html
File Transfer	How can I integrate multiple applications so that they work together and can exchange information?
Shared Database	How can I integrate multiple applications so that they work together and can exchange information?
Remote Procedure Invocation	How can I integrate multiple applications so that they work together and can exchange information?
How can I integrate multiple applications so that they work together and can exchange information?

Messaging Systems
Introduction to Messaging Systems	 
Message Channel	How does one application communicate with another using messaging?
Message	How can two applications connected by a message channel exchange a piece of information?
Pipes and Filters	How can we perform complex processing on a message while maintaining independence and flexibility?
Message Router	How can you decouple individual processing steps so that messages can be passed to different filters depending on a set of conditions?
Message Translator	How can systems using different data formats communicate with each other using messaging?
Message Endpoint	How does an application connect to a messaging channel to send and receive messages?

Messaging Channels
Introduction to Messaging Channels	 
Point-to-Point Channel	How can the caller be sure that exactly one receiver will receive the document or perform the call?
Publish-Subscribe Channel	How can the sender broadcast an event to all interested receivers?
Datatype Channel	How can the application send a data item such that the receiver will know how to process it?
Invalid Message Channel	How can a messaging receiver gracefully handle receiving a message that makes no sense?
Dead Letter Channel	What will the messaging system do with a message it cannot deliver?
Guaranteed Delivery	How can the sender make sure that a message will be delivered, even if the messaging system fails?
Channel Adapter	How can you connect an application to the messaging system so that it can send and receive messages?
Messaging Bridge	How can multiple messaging systems be connected so that messages available on one are also available on the others?
Message Bus	What is an architecture that enables separate applications to work together, but in a decoupled fashion such that applications can be easily added or removed without affecting the others?

Message Construction
Introduction to Message Construction	 
Command Message	How can messaging be used to invoke a procedure in another application?
Document Message	How can messaging be used to transfer data between applications?
Event Message	How can messaging be used to transmit events from one application to another?
Request-Reply	When an application sends a message, how can it get a response from the receiver?
Return Address	How does a replier know where to send the reply?
Correlation Identifier	How does a requestor that has received a reply know which request this is the reply for?
Message Sequence	How can messaging transmit an arbitrarily large amount of data?
Message Expiration	How can a sender indicate when a message should be considered stale and thus shouldn’t be processed?
Format Indicator	How can a message’s data format be designed to allow for possible future changes?

Interlude: Simple Messaging

Message Routing
Introduction to Message Routing	 
Content-Based Router	How do we handle a situation where the implementation of a single logical function (e.g., inventory check) is spread across multiple physical systems?
Message Filter	How can a component avoid receiving uninteresting messages?
Dynamic Router	How can you avoid the dependency of the router on all possible destinations while maintaining its efficiency?
Recipient List	How do we route a message to a list of dynamically specified recipients?
Splitter	How can we process a message if it contains multiple elements, each of which may have to be processed in a different way?
Aggregator	How do we combine the results of individual, but related messages so that they can be processed as a whole?
Resequencer	How can we get a stream of related but out-of-sequence messages back into the correct order?
Composed Message Processor	How can you maintain the overall message flow when processing a message consisting of multiple elements, each of which may require different processing?
Scatter-Gather	How do you maintain the overall message flow when a message needs to be sent to multiple recipients, each of which may send a reply?
Routing Slip	How do we route a message consecutively through a series of processing steps when the sequence of steps is not known at design-time and may vary for each message?
Process Manager	How do we route a message through multiple processing steps when the required steps may not be known at design-time and may not be sequential?
Message Broker	How can you decouple the destination of a message from the sender and maintain central control over the flow of messages?

Message Transformation
Introduction to Message Transformation	 
Envelope Wrapper	How can existing systems participate in a messaging exchange that places specific requirements on the message format, such as message header fields or encryption?
Content Enricher	How do we communicate with another system if the message originator does not have all the required data items available?
Content Filter	How do you simplify dealing with a large message, when you are interested only in a few data items?
Claim Check	How can we reduce the data volume of message sent across the system without sacrificing information content?
Normalizer	How do you process messages that are semantically equivalent, but arrive in a different format?
Canonical Data Model	How can you minimize dependencies when integrating applications that use different data formats?

Interlude: Composed Messaging

Messaging Endpoints
Introduction to Messaging Endpoints	 
Messaging Gateway	How do you encapsulate access to the messaging system from the rest of the application?
Messaging Mapper	How do you move data between domain objects and the messaging infrastructure while keeping the two independent of each other?
Transactional Client	How can a client control its transactions with the messaging system?
Polling Consumer	How can an application consume a message when the application is ready?
Event-Driven Consumer	How can an application automatically consume messages as they become available?
Competing Consumers	How can a messaging client process multiple messages concurrently?
Message Dispatcher	How can multiple consumers on a single channel coordinate their message processing?
Selective Consumer	How can a message consumer select which messages it wishes to receive?
Durable Subscriber	How can a subscriber avoid missing messages while it’s not listening for them?
Idempotent Receiver	How can a message receiver deal with duplicate messages?
Service Activator	How can an application design a service to be invoked both via various messaging technologies and via non-messaging techniques?

System Management
Introduction to System Management	 
Control Bus	How can we effectively administer a messaging system that is distributed across multiple platforms and a wide geographic area?
Detour	How can you route a message through intermediate steps to perform validation, testing or debugging functions?
Wire Tap	How do you inspect messages that travel on a point-to-point channel?
Message History	How can we effectively analyze and debug the flow of messages in a loosely coupled system?
Message Store	How can we report against message information without disturbing the loosely coupled and transient nature of a messaging system?
Smart Proxy	How can you track messages on a service that publishes reply messages to the Return Address specified by the requestor?
Test Message	What happens, though, if a component is actively processing messages, but garbles outgoing messages due to an internal fault?
Channel Purger	How can you keep 'left-over' messages on a channel from disturbing tests or running systems?
-->

### Patterns of Distributed Systems

<!--
## Distributed Systems

https://github.com/pingcap/talent-plan | pingcap/talent-plan: open source training courses about distributed database and distributed systems

https://ferd.ca/a-distributed-systems-reading-list.html
https://news.ycombinator.com/from?site=ferd.ca
https://news.ycombinator.com/item?id=39303160

https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/

https://www.geeksforgeeks.org/types-of-distributed-system/

Distributed Systems
https://en.wikipedia.org/wiki/Distributed_computing
https://www.atlassian.com/microservices/microservices-architecture/distributed-architecture
https://www.atlassian.com/microservices/microservices-architecture/distributed-architecture#:~:text=A%20distributed%20system%20is%20a,of%20failure%20from%20a%20system. | What is a distributed system? | Atlassian
https://www.splunk.com/en_us/blog/learn/distributed-systems.html
-->

<!--
https://en.wikipedia.org/wiki/Multiversion_concurrency_control | Multiversion concurrency control - Wikipedia
https://en.wikipedia.org/wiki/Non-lock_concurrency_control

https://en.wikipedia.org/wiki/Three-phase_commit_protocol | Three-phase commit protocol - Wikipedia
https://en.wikipedia.org/wiki/Two-phase_commit_protocol | Two-phase commit protocol - Wikipedia
https://en.wikipedia.org/wiki/Two-phase_locking | Two-phase locking - Wikipedia
https://en.wikipedia.org/wiki/Atomic_commit | Atomic commit - Wikipedia
https://en.wikipedia.org/wiki/Non-blocking_algorithm | Non-blocking algorithm - Wikipedia

https://en.wikipedia.org/wiki/Distributed_algorithm | Distributed algorithm - Wikipedia
https://en.wikipedia.org/wiki/Replication_(computing) | Replication (computing) - Wikipedia

https://en.wikipedia.org/wiki/Paxos_(computer_science) | Paxos (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Raft_(algorithm) | Raft (algorithm) - Wikipedia
https://en.wikipedia.org/wiki/Consensus_(computer_science) | Consensus (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Leader_election | Leader election - Wikipedia

Serial Algorithm- RAM
https://en.wikipedia.org/wiki/Parallel_algorithm | Parallel algorithm - Wikipedia
-->

<!--
https://martinfowler.com/articles/patterns-of-distributed-systems/ | Patterns of Distributed Systems
https://www.compileralchemy.com/blog/praise-for-patterns-of-distributed-computing/ | Praise for Patterns of Distributed Computing
https://www.amazon.com/Patterns-Distributed-Systems-Addison-Wesley-Signature/dp/0138221987/ref=asc_df_0138221987/?tag=hyprod-20&linkCode=df0&hvadid=693617400601&hvpos=&hvnetw=g&hvrand=1540816189329461302&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9024386&hvtargid=pla-2087849617622&psc=1&mcid=070f6a23df7b35429086d7aacabf3e13&gad_source=1 | Patterns of Distributed Systems (Addison-Wesley Signature Series (Fowler)): Joshi, Unmesh: 9780138221980: Amazon.com: Books

Gossip Dissemination
Use a random selection of nodes to pass on information to ensure it reaches all the nodes in the cluster without flooding the network

HeartBeat
Show a server is available by periodically sending a message to all the other servers.

Lease
Use time-bound leases for cluster nodes to coordinate their activities.


## Clock

Clock-Bound Wait
Wait to cover the uncertainty in time across cluster nodes before reading and writing values so that values can be correctly ordered across cluster nodes.

Generation Clock
A monotonically increasing number indicating the generation of the server.

Hybrid Clock
Use a combination of system timestamp and logical timestamp to have versions as date and time, which can be ordered

Lamport Clock
Use logical timestamps as a version for a value to allow ordering of values across servers

## Consistency, Election, Quorum, Consensus Algorithm

Consistent Core
Maintain a smaller cluster providing stronger consistency to allow the large data cluster to coordinate server activities without implementing quorum-based algorithms.

Emergent Leader
Order cluster nodes based on their age within the cluster to allow nodes to select a leader without running an explicit election.

Leader and Followers
Have a single server to coordinate replication across a set of servers.

Majority Quorum
Avoid two groups of servers making independent decisions by requiring majority for taking every decision.

Paxos
Use two consensus building phases to reach safe consensus even when nodes disconnect

## Read Requests

Follower Reads
Serve read requests from followers to achieve better throughput and lower latency

## Requests

Idempotent Receiver
Identify requests from clients uniquely so you can ignore duplicate requests when client retries

Request Batch
Combine multiple requests to optimally utilise the network

Request Pipeline
Improve latency by sending multiple requests on the connection without waiting for the response of the previous requests.

Request Waiting List
Track client requests which require responses after the criteria to respond is met based on responses from other cluster nodes.

Single-Socket Channel
Maintain the order of the requests sent to a server by using a single TCP connection

Singular Update Queue
Use a single thread to process requests asynchronously to maintain order without blocking the caller.

## Updates

State Watch 
Notify clients when specific values change on the server

Two-Phase Commit
Update resources on multiple nodes in one atomic operation
https://martinfowler.com/articles/patterns-of-distributed-systems/two-phase-commit.html | Two-Phase Commit

Version Vector 
Maintain a list of counters, one per cluster node, to detect concurrent updates

Versioned Value
Store every update to a value with a new version, to allow reading historical values.

## Partitions

Fixed Partitions
Keep the number of partitions fixed to keep the mapping of data to partition unchanged when the size of a cluster changes.

Key-Range Partitions
Partition data in sorted key ranges to efficiently handle range queries.

## Logs

Segmented Log
Split log into multiple smaller files instead of a single large file for easier operations.

Write-Ahead Log
Provide durability guarantee without the storage data structures to be flushed to disk, by persisting every state change as a command to the append only log.

Replicated Log
Keep the state of multiple nodes synchronized by using a write-ahead log that is replicated to all the cluster nodes.

High-Water Mark
An index in the write-ahead log showing the last successful replication.

Low-Water Mark
An index in the write-ahead log showing which portion of the log can be discarded.
-->

### Refactoring

Martin Fowler, Refactoring, Patterns, ThoughtWorks
* [Martin Fowler: Refactoring 2nd Edition](https://martinfowler.com/articles/refactoring-2nd-ed.html)
* [Refactoring Catalog](https://refactoring.com/catalog/)

<!--
https://github.com/ittus/Refactoring-summary-2nd-javascript| ittus/Refactoring-summary-2nd-javascript: Summary of "Refactoring: Improving the Design of Existing Code (2nd Edition)" by Martin Fowler)
-->

### Refactoring Book Examples

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

Inverse
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

Inverse
Extract Class
Inline Class

Inverse
Extract Function
Inline Function
• Inline Method

Extract Method

Extract Superclass

Inverse
Extract Variable
• Introduce Explaining Variable
Inline Variable
• Inline Temp

Inverse
Hide Delegate
Remove Middle Man

Introduce Assertion
Introduce Parameter Object
Introduce Special Case
• Introduce Null Object

Move Field
Move Function
• Move Method

Inverse
Move Statements into Function
Move Statements to Callers

Parameterize Function
• Parameterize Method

Preserve Whole Object
Pull Up Constructor Body

Inverse
Pull Up Field
Push Down Field

Inverse
Pull Up Method
Push Down Method

Remove Dead Code
Remove Flag Argument
• Replace Parameter with Explicit Methods

Remove Setting Method

Inverse
Remove Subclass
• Replace Subclass with Fields
Replace Type Code with Subclasses
• Extract Subclass 
• Replace Type Code with State/Strategy

Rename Field
Rename Variable

Inverse
Replace Command with Function
Replace Function with Command
• Replace Method with Method Object

Replace Conditional with Polymorphism
Replace Constructor with Factory Function
• Replace Constructor with Factory Method

Replace Control Flag with Break
• Remove Control Flag

Replace Derived Variable with Query
Replace Error Code with Exception
Replace Exception with Precheck
• Replace Exception with Test

Replace Inline Code with Function Call
Replace Loop with Pipeline
Replace Magic Literal
• Replace Magic Number with Symbolic Constant

Replace Nested Conditional with Guard Clauses

Inverse
Replace Parameter with Query
• Replace Parameter with Method
Replace Query with Parameter

Replace Primitive with Object
• Replace Data Value with Object 
• Replace Type Code with Class

Replace Subclass with Delegate
Replace Superclass with Delegate
• Replace Inheritance with Delegation

Replace Temp with Query

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

<!--
## Refactoring to Patterns

by Joshua Kerievsky 
https://www.amazon.com/gp/product/0321213351

Chain Constructors*
Replace Multiple Constructors with Creation Methods*
Parameterized Creation Methods
Encapsulate Subclasses with Creation Methods*
Extract Creation Class*
Replace Conditional Calculations with Strategy*
Replace Implicit Tree with Composite*
Encapsulate Composite with Builder**
Extract Special-Case Logic into Decorators
Replace Hard-Coded Notifications with Observer*
Move Accumulation to Collecting Parameter*
Replace One/Many Distinctions with Composite
Compose Method**
Separate Versions with Adapters *
Adapt Interface

## Tidy First?

I. Tidyings
1. Guard Clauses: https://refactoring.com/catalog/replaceNestedConditionalWithGuardClauses.html
2. Dead Code: https://refactoring.com/catalog/removeDeadCode.html
3. Normalize Symmetries
4. New Interface, Old Implementation
5. Reading Order
6. Cohesion Order
7. Move Declaration and Initialization Together
8. Explaining Variables
9. Explaining Constants
10. Explicit Parameters
11. Chunk Statements
12. Extract Helper
13. One Pile
14. Explaining Comments
15. Delete Redundant Comments

II. Managing
17. Separate Tidying
18. Chaining
Conclusion

19. Batch Sizes
20. Rhythm
21. Getting Untangled
22. First, After, Later, Never
Summary

III. Theory
23. Beneficially Relating Elements
24. Structure and Behavior
25. Economics: Time Value and Optionality
26. A Dollar Today > A Dollar Tomorrow
27. Options
28. Options Versus Cash Flows
29. Reversible Structure Changes
30. Coupling
31. Constantine’s Equivalence
32. Coupling Versus Decoupling
33. Cohesion
34. Conclusion
    
Appendix. Annotated Reading List and References
Index
About the Author
-->

## Software Design Patterns

Design Patterns for Humans
* [Design Patterns for Humans GitHub](https://github.com/kamranahmedse/design-patterns-for-humans)

<!--
https://github.com/sohamkamani/javascript-design-patterns-for-humans | sohamkamani/javascript-design-patterns-for-humans: An ultra-simplified explanation of design patterns implemented in javascript
-->

## General Software Design Patterns

Design Patterns- Gang of Four (GoF)
* [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612) and [Design Patterns: Elements of Reusable Object-Oriented Software Wikipedia](https://en.wikipedia.org/wiki/Design_Patterns)
* [Design Patterns Wikipedia](https://en.wikipedia.org/wiki/Design_Patterns)

Software Design Patterns
* [Software Design Pattern Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern)

## General Software Design Patterns- Types

Types of Patterns
* [Creational Pattern Wikipedia](https://en.wikipedia.org/wiki/Creational_pattern)
* [Structural Pattern Wikipedia](https://en.wikipedia.org/wiki/Structural_pattern)
* [Behavioral Pattern Wikipedia](https://en.wikipedia.org/wiki/Behavioral_pattern)

Creational Patterns (object creation)
* [Factory Method Pattern Wikipedia](https://en.wikipedia.org/wiki/Factory_method_pattern)

Creational Patterns- Can use Singleton in Implementation
* [Abstract Factory Pattern Wikipedia](https://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [Builder Pattern Wikipedia](https://en.wikipedia.org/wiki/Builder_pattern)
* [Prototype Pattern Wikipedia](https://en.wikipedia.org/wiki/Prototype_pattern)

Structural Patterns (relationships among entities)
* [Adapter Pattern Wikipedia](https://en.wikipedia.org/wiki/Adapter_pattern)
* [Bridge Pattern Wikipedia](https://en.wikipedia.org/wiki/Bridge_pattern)
* [Composite Pattern Wikipedia](https://en.wikipedia.org/wiki/Composite_pattern)
* [Facade Pattern Wikipedia](https://en.wikipedia.org/wiki/Facade_pattern)
* [Flyweight Pattern Wikipedia](https://en.wikipedia.org/wiki/Flyweight_pattern)
* [Proxy Pattern Wikipedia](https://en.wikipedia.org/wiki/Proxy_pattern)

Structural Patterns (relationships among entities)- Familiar
* [Decorator Pattern (similar to Chain of Responsibility Pattern; implements Single Responsibility Principal) Wikipedia](https://en.wikipedia.org/wiki/Decorator_pattern)

Behavioral Patterns
* [Command Pattern Wikipedia](https://en.wikipedia.org/wiki/Command_pattern)
* [Mediator Pattern Wikipedia](https://en.wikipedia.org/wiki/Mediator_pattern)
* [Memento Pattern Wikipedia](https://en.wikipedia.org/wiki/Memento_pattern)
* [Strategy Pattern Wikipedia](https://en.wikipedia.org/wiki/Strategy_pattern)
* [Template Method Pattern Wikipedia](https://en.wikipedia.org/wiki/Template_method_pattern)
* [Visitor Pattern Wikipedia](https://en.wikipedia.org/wiki/Visitor_pattern)

Behavioral Patterns- Familiar
* [Observer Pattern Wikipedia](https://en.wikipedia.org/wiki/Observer_pattern)
* [State Pattern Wikipedia](https://en.wikipedia.org/wiki/State_pattern)
* [Chain-of-Responsibility Pattern (handler, similar to Decorator Pattern) Wikipedia](https://en.wikipedia.org/wiki/Chain-of-responsibility_pattern)

## Software Design Patterns- Built Into Python

Creational Patterns (object creation)
* Singleton Pattern is not needed due to module namespacing
* [Singleton Pattern Wikipedia](https://en.wikipedia.org/wiki/Singleton_pattern)

Behavioral Patterns
* [Iterator Pattern Wikipedia Article](https://en.wikipedia.org/wiki/Iterator_pattern)

## Python Software Design Patterns and Refactoring

Patterns Talks
* [Christopher Neugebauer "You Don't Need That"](https://www.youtube.com/watch?v=dg-Vm9W3Tlc&list=PL2k6bbM_wgjvY02EFUMhwHRyaSaEokT2B&index=37)

Brandon
* [Brandon Rhodes: Python Patterns](http://python-patterns.guide) and [Brandon Rhodes: Python Patterns GitHub](https://github.com/brandon-rhodes/python-patterns)

Gang of Four: Principles

Composition over Inheritance: https://python-patterns.guide/gang-of-four/composition-over-inheritance/
Problem: the subclass explosion
Solution #1: The Adapter Pattern
Solution #2: The Bridge Pattern
Solution #3: The Decorator Pattern
Solution #4: Beyond the Gang of Four patterns

* Dodge: “if” statements
* Dodge: Multiple Inheritance: https://fuhm.net/super-harmful/
* Dodge: Mixins
* Dodge: Building classes dynamically

Python-Specific Patterns

The Global Object Pattern
The Constant Pattern
Import-time computation
Dunder Constants
The Global Object Pattern
Global Objects that are mutable
Import-time I/O

The Prebound Method Pattern
Alternatives
The pattern
The Sentinel Object Pattern

Sentinel Value
The Null Pointer Pattern
The Null Object Pattern
Sentinel Objects

Gang of Four: Creational Patterns¶

The Abstract Factory Pattern
The Pythonic approach: callable factories
Restriction: outlaw passing callables
Restriction: outlaw passing classes
Generalizing: the complete Abstract Factory

The Builder Pattern
The Builder as convenience
Nuance
Dueling builders
A degenerate case: simulating optional arguments

The Factory Method Pattern
Dodge: use Dependency Injection
Instead: use a Class Attribute Factory
Instead: use an Instance Attribute Factory
Instance attributes override class attributes
Any callables accepted
Implementing

The Prototype Pattern
The problem
Pythonic solutions
Implementing

The Singleton Pattern
Disambiguation
The Gang of Four’s implementation
A more Pythonic implementation
Verdict

Gang of Four: Structural Patterns

The Composite Pattern
Example: the UNIX file system
On hierarchies
Example: GUI programming with Tkinter
Implementation: to inherit, or not?

The Decorator Pattern
Definition
Implementing: Static wrapper
Implementing: Tactical wrapper
Implementing: Dynamic wrapper
Caveat: Wrapping doesn’t actually work
Hack: Monkey-patch each object
Hack: Monkey-patch the class
Further Reading

The Flyweight Pattern
Factory or Constructor
Implementing

Gang of Four: Behavioral Patterns

The Iterator Pattern
Iterating with the “for” loop
The pattern: the iterable and its iterator
A twist: objects which are their own iterator
Implementing an Iterable and Iterator
Python’s extra level of indirection

Bibliography
Gang of Four book
Refactoring by Martin Fowler

<!--
Adapter/facade can work together
Observer- the inverse of adapter/facade, can take their place? (Django signals is an implentation of observer)

simply visit the commit history of this site’s project repository on GitHub, where you can also select “Watch” to get updates.
With those preliminaries complete, here are the patterns!

https://www.youtube.com/watch?v=Er5K_nR5lDQ&t=1045s | Python Design Patterns 1 - YouTube
http://rhodesmill.org/brandon/talks/#design-patterns-1 | Talks
http://rhodesmill.org/brandon/slides/2012-07-pyohio/ | slides.rst

https://www.pyohio.org/2018/schedule/presentation/17/ | PyOhio | Presentation: You Don't Need That!
-->


<!--
## Architecture Types

Software Stacks
* [Solution Stack Wikipedia](http://en.wikipedia.org/wiki/Solution_stack)  
* [Digital Ocean 5 Common Server Setups](https://www.digitalocean.com/community/tutorials/5-common-server-setups-for-your-web-application)
-->

<!--
## Architecture Types

https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure/ | Emerging Architectures for Modern Data Infrastructure

https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749
-->

## Architectures

Hawt
* [Monolith Application Wikipedia](https://en.wikipedia.org/wiki/Monolithic_application)
* [Microservices Wikipedia](https://en.wikipedia.org/wiki/Microservices)

Architectures
* [Distributed Computing Wikipedia](https://en.wikipedia.org/wiki/Distributed_computing)
* [Enterprise Architecture Framework Wikipedia](https://en.wikipedia.org/wiki/Enterprise_architecture_framework)
* [Service Oriented Architecture Wikipedia](https://en.wikipedia.org/wiki/Service-oriented_architecture)
* [Resource Oriented Architecture Wikipedia](https://en.wikipedia.org/wiki/Resource-oriented_architecture)
* [Micro Architecture Wikipedia](https://en.wikipedia.org/wiki/Microarchitecture)
* [Loose Coupling Wikipedia](https://en.wikipedia.org/wiki/Loose_coupling)
* [Multitenancy Wikipedia](https://en.wikipedia.org/wiki/Multitenancy)


Interesting
https://www.enterpriseintegrationpatterns.com/patterns/messaging/toc.html
https://en.wikipedia.org/wiki/Software_architecture#Architectural_styles_and_patterns
https://en.wikipedia.org/wiki/List_of_software_architecture_styles_and_patterns
https://en.wikipedia.org/wiki/Software_architecture
https://en.wikipedia.org/wiki/Architectural_pattern

https://en.wikipedia.org/wiki/Messaging_pattern

https://en.wikipedia.org/wiki/Post/Redirect/Get
https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop | Read–eval–print loop - Wikipedia
-->

<!--
https://www.youtube.com/watch?v=ZQ5_u8Lgvyk | (1) Designing and Evaluating Reusable Components - 2004 - YouTube
https://caseymuratori.com/blog_0024 | Designing and Evaluating Reusable Components (2004)
https://web.archive.org/web/20160424063525/http://mollyrocket.com:80/9438 | mollyrocket.com - API Design
-->

## Software Design Pattern Catalogs

Catalogs
* [Computer Science Design Patterns Wikibook](https://en.wikibooks.org/wiki/Computer_Science_Design_Patterns)

<!--
Interesting opinions
https://en.wikibooks.org/wiki/Introduction_to_Software_Engineering/Architecture/Design_Patterns

General
https://github.com/DovAmir/awesome-design-patterns | DovAmir/awesome-design-patterns: A curated list of software and architecture related design patterns.

https://en.wikipedia.org/wiki/Category:Software_design_patterns | Category:Software design patterns - Wikipedia

https://refactoring.guru/design-patterns/ | Design Patterns

https://sourcemaking.com
https://sourcemaking.com/antipatterns/ | AntiPatterns
https://sourcemaking.com/design-patterns-ebook | Design Patterns eBook

Patterns
http://www.hillside.net/patterns/patterns-catalog
http://django.wikispaces.asu.edu/Observer+Design+Pattern
-->


## Python Design Patterns

Python Design Patterns and Algorithms
* [Python Design Patterns GitHub](https://github.com/faif/python-patterns)

<!--
https://www.tutorialspoint.com/python_design_patterns/index.htm | Python Design Patterns Tutorial
https://github.com/tylerlaberge/PyPattyrn | tylerlaberge/PyPattyrn: A simple library for implementing common design patterns.
-->

## Django Design Patterns

<!--
* [Django Design Patterns and Best Practices GitHub](https://github.com/cundi/Django-Design-Patterns-and-Best-Practices)

https://www.agiliq.com/books/djangodesignpatterns/ | Index — Django Design Patterns
https://github.com/agiliq/django-design-patterns | agiliq/django-design-patterns: Commonly occuring design patterns in Django
https://github.com/DjangoPatternsBook/superbook2 | DjangoPatternsBook/superbook2: Code for the second edition of Django Design Patterns and Best Practices book by Arun Ravindran
https://github.com/DjangoPatternsBook/DjangoPatternsBook.github.io | DjangoPatternsBook/DjangoPatternsBook.github.io: The site for the book

https://github.com/PacktPublishing/Django-Design-Patterns-and-Best-Practices-Second-Edition/tree/master/src | Django-Design-Patterns-and-Best-Practices-Second-Edition/src at master · PacktPublishing/Django-Design-Patterns-and-Best-Practices-Second-Edition

https://media.readthedocs.org/pdf/django-design-patterns/latest/django-design-patterns.pdf | Django design patterns Documentation

https://arunrocks.com/static/book/django-design-patterns-best-practices-2-ed/ | Django Design Patterns and Best Practices (2nd Ed) by Arun Ravindran for Django 2.0
https://books.google.com/books?id=FnxeDwAAQBAJ&pg=PA4&lpg=PA4&dq=file:pdf+django+design+patterns+and+best+practices&source=bl&ots=yRhTMffqiB&sig=UMGTE2TAhj3tOMrBYmQVOexHrMQ&hl=en&sa=X&ved=2ahUKEwiMgqru_-_dAhVsk-AKHRGaCRE4ChDoATAFegQIAxAB#v=onepage&q=file%3Apdf%20django%20design%20patterns%20and%20best%20practices&f=false | Django Design Patterns and Best Practices: Industry-standard web development ... - Arun Ravindran - Google Books

https://thoughtbot.com/upcase/videos/design-patterns-in-django-and-python | Design Patterns in Django and Python | Online Video Tutorial by thoughtbot
-->

## Patterns and Design Patterns- General

Design Patterns- General
* [Pattern Language Wikipedia](https://en.wikipedia.org/wiki/Pattern_language)
* [Design Pattern Wikipedia](https://en.wikipedia.org/wiki/Design_pattern)


## Programming Paradigms- Object Oriented Software

Object-Oriented Programming Languages
* [Object-Oriented Programming Languages Wikipedia](https://en.wikipedia.org/wiki/List_of_object-oriented_programming_languages)
* [Object Oriented Programming Wikipedia](https://en.wikipedia.org/wiki/Object-oriented_programming)
* [List of Object-Oriented Programming Languages Wikipedia](https://en.wikipedia.org/wiki/List_of_object-oriented_programming_languages)
* [Class Based Programming Wikipedia](https://en.wikipedia.org/wiki/Class-based_programming)
* [Prototype Based Programming Wikipedia](https://en.wikipedia.org/wiki/Prototype-based_programming)

Object Oriented Software Construction
* [Object-Oriented Software Construction Wikipedia](https://en.wikipedia.org/wiki/Object-Oriented_Software_Construction)
* [Object-Oriented Analysis and Design Wikipedia](https://en.wikipedia.org/wiki/Object-oriented_analysis_and_design)

Object
* [Object Composition Wikipedia](https://en.wikipedia.org/wiki/Object_composition)

Constructor
* [Constructor Python Wikipedia](https://en.wikipedia.org/wiki/Constructor_(object-oriented_programming)#Python)

Object Oriented Software Characteristics
* [Abstraction Wikipedia](https://en.wikipedia.org/wiki/Abstraction_(computer_science))
* [Encapsulation Wikipedia](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming))
* [Inheritance Wikipedia](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming))
* [Polymorphism Wikipedia](https://en.wikipedia.org/wiki/Polymorphism_(computer_science))

## Programming Paradigms- Functional, Imperative, Declarative, Reactive

Functional Programming
* [Functional Programming Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)
* [Purely Functional Programming Wikipedia](https://en.wikipedia.org/wiki/Purely_functional_programming)
* [Side Effect Wikipedia](https://en.wikipedia.org/wiki/Side_effect_(computer_science))

Imperative and Declarative
* [Imperative Programming Wikipedia](https://en.wikipedia.org/wiki/Imperative_programming)
* [Declarative Programming Wikipedia](https://en.wikipedia.org/wiki/Declarative_programming)

React?
* [Reactive Programming Wikipedia](https://en.wikipedia.org/wiki/Reactive_programming)

## Programming Paradigms- Functional Programming

* [Immutable Object Wikipedia](https://en.wikipedia.org/wiki/Immutable_object)

<!--
Functional programming
pure function

https://github.com/hemanth/functional-programming-jargon | hemanth/functional-programming-jargon: Jargon from the functional programming world in simple terms!

https://en.wikipedia.org/wiki/State_pattern
https://en.wikipedia.org/wiki/Finite-state_machine

https://github.com/getify/Functional-Light-JS/blob/master/manuscript/ch1.md/#chapter-1-why-functional-programming | Functional-Light-JS/ch1.md at master · getify/Functional-Light-JS
-->

## Inheritance versus Composition

Composition
* [Functional Composition Wikipedia](https://en.wikipedia.org/wiki/Function_composition_(computer_science))

## Useful Terminology

Example of stateless protocols
* [Stateless Protocol Wikipedia](https://en.wikipedia.org/wiki/Stateless_protocol)
* [HTTP](https://en.wikipedia.org/wiki/HTTP)

State
* [State Wikipedia](https://en.wikipedia.org/wiki/State_(computer_science))
* [Persistence Wikipedia](https://en.wikipedia.org/wiki/Persistence_(computer_science))
* [Persistent Data Structure Wikipedia](https://en.wikipedia.org/wiki/Persistent_data_structure)


## Code Complete and Clean Code

Checklists and Cheat Sheets
* [Code Complete Checklist](https://www.matthewjmiller.net/files/cc2e_checklists.pdf)
* [Clean Code Cheat Sheet](https://github.com/charlax/professional-programming/blob/master/cheatsheets/Clean-Code-V2.4.pdf)

## GRASP and Clean Architecture (Follows SOLID Principles)

Object Oriented Software Construction Principles
* [GRASP (Object Oriented Design) Wikipedia](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))
* [SOLID (Object Oriented Design) Wikipedia](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design))

<!--
https://ourmachinery.com/files/guidebook.md.html
https://en.wikipedia.org/wiki/Data-oriented_design
-->

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
https://en.wikipedia.org/wiki/Inversion_of_control

https://en.wikipedia.org/wiki/Interface_(computing)

Clean Architectures in Python - Leonardo Giordani - PyLondinium19
https://www.youtube.com/watch?v=wtCQalq7L-E
-->

## Clean Architecture

<!--
Robert C. Martin
https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164 | Clean Architecture: A Craftsman's Guide to Software Structure and Design (Robert C. Martin Series): Robert C. Martin: 9780134494166: Amazon.com: Books

http://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html | Clean Coder Blog

https://dev.to/bosepchuk/why-i-cant-recommend-clean-architecture-by-robert-c-martin-ofd | Why I can't recommend Clean Architecture by Robert C Martin - DEV Community 👩‍💻👨‍💻

https://medium.freecodecamp.org/how-to-write-robust-apps-consistently-with-the-clean-architecture-9bdca93e17b | How to write robust apps every time, using “The Clean Architecture”
https://medium.freecodecamp.org/a-quick-introduction-to-clean-architecture-990c014448d2 | A quick introduction to clean architecture – freeCodeCamp.org
-->

## Clean Architecture in Python and Django

<!--
Clean Code
https://github.com/zedr/clean-code-python

https://engineering.21buttons.com/clean-architecture-in-django-d326a4ab86a9 | Clean Architecture in Django – 21 Buttons Engineering

Brandon Rhodes
http://rhodesmill.org/brandon/slides/2014-07-pyohio/clean-architecture/ | slides.rst
http://pyvideo.org/pyohio-2014/the-clean-architecture-in-python.html | PyVideo.org · The Clean Architecture in Python
https://www.youtube.com/watch?v=DJtef410XaM | The Clean Architecture in Python - YouTube
https://www.reddit.com/r/Python/comments/41llbh/the_clean_architecture_with_python/ | The Clean Architecture with Python : Python

https://github.com/pgrzesik/python-clean-architecture | pgrzesik/python-clean-architecture

https://github.com/Enforcer | Enforcer (Sebastian Buczyński)
https://github.com/Enforcer/clean-architecture-example-1 | Enforcer/clean-architecture-example-1: Exemplary project using Clean Architecture in Python
https://speakerdeck.com/enforcer/clean-architecture-in-python | Clean Architecture in Python - Speaker Deck
-->

## Software Laws

<!--
https://en.wikipedia.org/wiki/Lehman%27s_laws_of_software_evolution

http://users.ece.utexas.edu/~adnan/pike.html
-->

## Programming Anti Patterns

* [Anti-Pattern Wikipedia](https://en.wikipedia.org/wiki/Anti-pattern)
* [Don't Repeat Yourself Wikipedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
* [KISS Principle Wikipedia](https://en.wikipedia.org/wiki/KISS_principle)

## Refactoring

* [Technical Debt](https://www.techopedia.com/definition/27913/technical-debt)
* [Code Reuse Wikipedia](https://en.wikipedia.org/wiki/Code_reuse)
* [Code Refactoring Wikipedia](https://en.wikipedia.org/wiki/Code_refactoring)

<!--
## JavaScript Design Patterns

JavaScript Patterns
* [Stoyan Stefanov: TLDR JavaScript Design Patterns](https://github.com/karlpatrickespiritu/TLDR-Learning-JS-Design-Patterns-by-Addy-Osmani)
* [Addy Osmani: JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book) and [Addy Osmani: JavaScript Design Patterns GitHub](https://github.com/addyosmani/essential-js-design-patterns)
* [Addy Osmani: Patterns For Large-Scale JavaScript Application Architecture](https://addyosmani.com/largescalejavascript/)

https://github.com/addyosmani/essential-js-design-patterns | addyosmani/essential-js-design-patterns: Repo for my 'Learning JavaScript Design Patterns' book
https://addyosmani.com/resources/essentialjsdesignpatterns/book/#whatisapattern | Learning JavaScript Design Patterns

https://addyosmani.com/largescalejavascript/ | Patterns For Large-Scale JavaScript Application Architecture
https://github.com/karlpatrickespiritu/TLDR-Learning-JS-Design-Patterns-by-Addy-Osmani

  * [Understanding MVC And MVP (For JavaScript And Backbone Developers)](https://addyosmani.com/blog/understanding-mvc-and-mvp-for-javascript-and-backbone-developers/)
  * [Understanding MVVM - A Guide For JavaScript Developers](https://addyosmani.com/blog/understanding-mvvm-a-guide-for-javascript-developers/)
  
https://github.com/Badacadabra/JavaScript-Design-Patterns | Badacadabra/JavaScript-Design-Patterns: ES5 + ES6 + CoffeeScript + TypeScript design patterns with some theory, real-world examples and UML diagrams

https://github.com/ryanmcdermott/clean-code-javascript

https://github.com/AllThingsSmitty/must-watch-javascript | AllThingsSmitty/must-watch-javascript: A useful list of must-watch talks about JavaScript
-->
