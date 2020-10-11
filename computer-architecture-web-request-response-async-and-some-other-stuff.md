# Computer Architecture, Web, Request/Response, Async, and Some Other Stuff

<!--
https://github.com/tiangolo/fastapi
https://fastapi.tiangolo.com/#performance

Postman	
https://github.com/liyasthomas/postwoman | liyasthomas/postwoman: 👽 API request builder - A free, fast, and beautiful alternative to Postman https://postwoman.io 🔥	


https://www.datadoghq.com/blog/hadoop-architecture-overview/ | Hadoop architectural overview
https://resources.mongodb.com/mongodb-architects | MongoDB for Architects

https://riscv.org/ | RISC-V International
https://en.wikipedia.org/wiki/Active_Directory
https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol | Lightweight Directory Access Protocol - Wikipedia
https://en.wikipedia.org/wiki/SQL_Server_Reporting_Services | SQL Server Reporting Services - Wikipedia
https://www.geeksforgeeks.org/computer-organization-risc-and-cisc/ | Computer Organization | RISC and CISC - GeeksforGeeks

https://elegantnetwork.github.io/posts/What-Ive-learned-about-OSPF/

APIs
https://insomnia.rest/ | Insomnia | The API Design Platform and REST Client
https://twitter.com/vipulgupta2048/status/1301721412420251655 | Vipul Gupta 🐣 on Twitter: "@KatiMichel I can recommend 2 more if you like to check out. https://t.co/EjKlnN2gxi and @FirecampHQ" / Twitter
https://hoppscotch.io/
https://firecamp.io/

Authenticate bearer
Swarm testing

Real time services
chat protocols, IoT protocols
https://en.wikipedia.org/wiki/Comparison_of_instant_messaging_protocols
https://en.wikipedia.org/wiki/Online_chat#Software_and_protocols

https://en.wikipedia.org/wiki/Real-Time_Messaging_Protocol | Real-Time Messaging Protocol - Wikipedia

http://restcookbook.com/Miscellaneous/rest-and-http/

https://chmodcommand.com
https://httpstatuses.com/409 | 409 Conflict — httpstatuses.com
-->

## Request and Response Cycle, HTTP

Request and Response Cycle
* [Request Response Wikipedia](https://en.wikipedia.org/wiki/Request%E2%80%93response)

Request and Response Cycle- HTTP
* [List of HTTP Header Fields Wikipedia](http://en.wikipedia.org/wiki/List_of_HTTP_header_fields) 
* [HTTP Body Data Response Example Wikipedia](http://en.wikipedia.org/wiki/HTTP_body_data#Response_example)
* [Post (HTTP) Wikipedia](https://en.wikipedia.org/wiki/POST_(HTTP)) 
* [List of HTTP Request Methods Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods) 
* [List of HTTP Status Codes Wikipedia](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)
* [HTTP Referer Wikipedia](https://en.wikipedia.org/wiki/HTTP_referer)

Sessions
* [Web Browsing History Wikipedia](https://en.wikipedia.org/wiki/Web_browsing_history)
* [Session Wikipedia](https://en.wikipedia.org/wiki/Session_(computer_science))
* [Session ID Wikipedia](https://en.wikipedia.org/wiki/Session_ID)

Cookies
* [HTTP Cookie Wikipedia](http://en.wikipedia.org/wiki/HTTP_cookie)  
* [Browser Cookie Wikipedia](http://en.wikipedia.org/wiki/Browser_cookie) 
* [jQuery Cookie GitHub](https://github.com/carhartl/jquery-cookie)  

<!--
https://en.wikipedia.org/wiki/HTTP_message_body

https://en.wikipedia.org/wiki/List_of_HTTP_header_fields#Request_fields
https://en.wikipedia.org/wiki/List_of_HTTP_header_fields#Response_fields

https://en.wikipedia.org/wiki/HTTP_cookie#Http-only_cookie
"Cookies were designed to be a reliable mechanism for websites to remember stateful information"
Authentication cookie

https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#Generic_syntax
https://en.wikipedia.org/wiki/Uniform_Resource_Identifier | Uniform Resource Identifier - Wikipedia
https://en.wikipedia.org/wiki/UTM_parameters | UTM parameters - Wikipedia
https://en.wikipedia.org/wiki/Query_string | Query string - Wikipedia
https://en.wikipedia.org/wiki/Content_sniffing | Content sniffing - Wikipedia

https://en.wikipedia.org/wiki/Server_log
-->

## Computer Architecture

CPU versus IO
* [Central Processing Unit Wikipedia](https://en.wikipedia.org/wiki/Central_processing_unit)
* [Input/Output (I/O) Wikipedia](https://en.wikipedia.org/wiki/Input/output)
* [I/O Bound Wikipedia](https://en.wikipedia.org/wiki/I/O_bound)
* [CPU Bound Wikipedia](https://en.wikipedia.org/wiki/CPU-bound)
* [I/O Bound Comparison with CPU Bound Wikipedia](https://en.wikipedia.org/wiki/I/O_bound#Comparison_with_CPU-bound)

Ports
* [Port Wikipedia](https://en.wikipedia.org/wiki/Port_(computer_networking))

HTTP and HTTPS
* [Hypertext Wikipedia](https://en.wikipedia.org/wiki/Hypertext)
* [Hypertext Transfer Protocol (HTTP) Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
* [Hypertext Transfer Protocol Secure (HTTPS) Wikipedia](https://en.wikipedia.org/wiki/HTTPS)

HTTP Versions
* [HTTP/3 Wikipedia](https://en.wikipedia.org/wiki/HTTP/3)
* [HTTP/2 Wikipedia](https://en.wikipedia.org/wiki/HTTP/2)
* [HTTP/2- Differences from HTTP/1.1 Wikipedia](https://en.wikipedia.org/wiki/HTTP/2#Differences_from_HTTP_1.1)

<!--
See GraphQL

https://en.wikipedia.org/wiki/HTTP_Live_Streaming | HTTP Live Streaming - Wikipedia
https://en.wikipedia.org/wiki/HTTP/2_Server_Push | HTTP/2 Server Push - Wikipedia
-->

HTTP versus WebSocket (HTTP is uni-directional; WebSocket is bi-directional)
* [Network Socket Wikipedia](https://en.wikipedia.org/wiki/Network_socket)
* [WebSocket Wikipedia](https://en.wikipedia.org/wiki/WebSocket)

Application Programming Interface (API... usually HTTP + XML or JSON)
* [Application Programming Interface Web APIs](https://en.wikipedia.org/wiki/Application_programming_interface#Web_APIs)
* [Web API Wikipedia](https://en.wikipedia.org/wiki/Web_API#Endpoints)
* [Web API Endpoints Wikipedia](https://en.wikipedia.org/wiki/Web_API#Endpoints)

REST (API architecture style; versus SOAP or GraphQL)
* [Representational State Transfer Wikipedia](https://en.wikipedia.org/wiki/Representational_state_transfer)
* [Stateless Protocol Wikipedia](https://en.wikipedia.org/wiki/Stateless_protocol)

REST Alternatives
* [GraphQL](http://graphql.org/)
* [Simple Object Access Protocol (SOAP)](https://en.wikipedia.org/wiki/SOAP)

<!--
https://sqlite.org/appfileformat.html | SQLite As An Application File Format

Python Database
* [SQLAlchemy](https://www.sqlalchemy.org/) and [SQLAlchemy Docs](https://docs.sqlalchemy.org)

https://medium.com/@__xuorig__/is-graphql-still-relevant-in-an-http2-world-64964f207b8

https://github.com/graphql/graphql-js | graphql/graphql-js: A reference implementation of GraphQL for JavaScript
https://github.com/graphql-python | GraphQL Python
-->

REST payload formatted in HTML, JSON, XML, etc. (Most commonly HTTP is used; HTTP methods available are GET, HEAD, POST, PUT, PATCH, DELETE, CONNECT, OPTIONS and TRACE.)
* [JSON Wikipedia](https://en.wikipedia.org/wiki/JSON)
* [XML Wikipedia](https://en.wikipedia.org/wiki/XML)

<!--
JSON versus s-expression
https://en.wikipedia.org/wiki/S-expression
-->

Serialization- Google's Protocol Buffers (Alternative to XML/JSON)
* [Protocol Buffers](https://developers.google.com/protocol-buffers/)

Remote Procedure Call (RPC) Framework (Uses Protocol Buffers)
* [Remote Procedure Call (RPC) Wikipedia](https://en.wikipedia.org/wiki/Remote_procedure_call)
* [gRPC Remote Procedure Call (gRPC) Wikipedia](https://en.wikipedia.org/wiki/GRPC)

<!--
https://developers.google.com/protocol-buffers/docs/overview

https://github.com/protocolbuffers/protobuf | protocolbuffers/protobuf: Protocol Buffers - Google's data interchange format
https://en.wikipedia.org/wiki/Protocol_Buffers | Protocol Buffers - Wikipedia
https://codeclimate.com/blog/choose-protocol-buffers/ | 5 Reasons to Use Protocol Buffers Instead of JSON for Your Next Service - Code Climate

https://grpc.io/
https://grpc.io/docs/guides/
-->

Webhooks (Event-driven, custom callback... the format is usually JSON. The request is done as a HTTP POST request.)
* [Webhook Wikipedia](https://en.wikipedia.org/wiki/Webhook)

Callbacks (implemented often as subroutines, lambda expressions, blocks, or function pointers)
* [Callback Wikipedia](https://en.wikipedia.org/wiki/Callback_(computer_programming))

Ajax: Asynchronous JavaScript and XML (Uses XHTML + CSS + DOM/JavaScript)
* [Ajax Wikipedia](https://en.wikipedia.org/wiki/Ajax_(programming))
* [List of Ajax Frameworks Wikipedia](https://en.wikipedia.org/wiki/List_of_Ajax_frameworks#JavaScript)

<!--
www.json.org

https://en.m.wikipedia.org/wiki/Serialization

API... usually HTTP + XML or JSON
https://en.wikipedia.org/wiki/Application_programming_interface
"When used in the context of web development, an API is typically defined as a set of specifications, such as Hypertext Transfer Protocol (HTTP) request messages, along with a definition of the structure of response messages, usually in an Extensible Markup Language (XML) or JavaScript Object Notation (JSON) format."

https://jsonapi.org/ | JSON:API — A specification for building APIs in JSON

Important
"HTTP is a uni-directional communicational protocol, whereas WebSocket is bi-directional."
https://www.quora.com/What-is-the-difference-between-HTTP-and-WebSocket-in-simple-words
https://stackoverflow.com/questions/152457/what-is-the-difference-between-a-port-and-a-socket
https://hackernoon.com/webhook-vs-api-whats-the-difference-8d41e6661652

https://en.wikipedia.org/wiki/Representational_state_transfer#Relationship_between_URI_and_HTTP_methods
https://en.wikipedia.org/wiki/Representational_state_transfer#Architectural_constraints | Representational state transfer - Wikipedia

https://simpleisbetterthancomplex.com/tutorial/2016/10/31/how-to-handle-github-webhooks-using-django.html
https://simpleisbetterthancomplex.com/tutorial/2016/07/27/how-to-return-json-encoded-response.html
https://simpleisbetterthancomplex.com/tutorial/2016/08/29/how-to-work-with-ajax-request-with-django.html

https://en.wikipedia.org/wiki/Memory_bound_function

Interesting!
https://en.wikipedia.org/wiki/Execution_model
https://en.wikipedia.org/wiki/Scheduling_(computing)

https://en.wikipedia.org/wiki/Concurrency_(computer_science)#Models
https://en.wikipedia.org/wiki/Message_passing | Message passing - Wikipedia
https://en.wikipedia.org/wiki/Event-driven_programming
https://en.wikipedia.org/wiki/Event-driven_messaging
-->

## Auth

<!--
https://en.wikipedia.org/wiki/Role-based_access_control | Role-based access control - Wikipedia
https://twitter.com/mojombo/status/1296591273361461248 | Tom Preston-Werner on Twitter: "A huge amount of work is represented in @RedwoodJS v0.16 and a testament to our amazing and growing set of contributors. I'm especially excited to announce role-based access control (RBAC) in this release (special thanks to @dthyresson and @appfactory)! More on Vercel later. =)" / Twitter

https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm

https://en.wikipedia.org/wiki/Single_sign-on
https://en.wikipedia.org/wiki/SAML_2.0
https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language

https://mherman.org/presentations/node-oauth-openid/#1 | Introduction to OAuth 2.0 and OpenID Connect
https://github.com/mjhea0/node-oauth-openid | mjhea0/node-oauth-openid

https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication | HTTP authentication - HTTP | MDN

https://en.wikipedia.org/wiki/Basic_access_authentication
https://en.wikipedia.org/wiki/Initiative_for_Open_Authentication

Third-party services
https://en.wikipedia.org/wiki/OpenID
OpenID identity provider
https://en.wikipedia.org/wiki/Identity_provider_(SAML)
"OpenID Connect 1.0 is a simple identity layer on top of the OAuth 2.0 protocol"
https://en.wikipedia.org/wiki/OpenID_Connect
https://openid.net/ | OpenID Foundation website

Web, mobile and desktop apps
https://en.wikipedia.org/wiki/OAuth
https://en.wikipedia.org/wiki/OAuth#OAuth_2.0_2
https://oauth.net/ | OAuth Community Site
https://oauth.net/2/ | OAuth 2.0 — OAuth

https://developers.google.com/identity/protocols/OAuth2


Authentication
JSON Web Token (JWT)
https://en.wikipedia.org/wiki/JSON_Web_Token
https://jwt.io/ | JSON Web Tokens - jwt.io
https://github.com/dwyl/learn-json-web-tokens | dwyl/learn-json-web-tokens: Learn how to use JSON Web Token (JWT) to secure your next Web App! (Tutorial/Example with Tests!!)

https://auth0.com/ | Single Sign On & Token Based Authentication - Auth0
https://auth0.com/blog/cookies-vs-tokens-definitive-guide/ | Cookies vs Tokens: The Definitive Guide
https://auth0.com/learn/token-based-authentication-made-easy/ | Token Based Authentication Made Easy - Auth0
https://github.com/auth0/auth0-python | auth0/auth0-python: All information regarding using Auth0 with Python

https://twofactorauth.org/ | 502 Bad Gateway
https://twofactorauth.org/#banking | Two Factor Auth List


https://docs.djangoproject.com/en/2.2/topics/http/sessions/ | How to use sessions | Django documentation | Django
Social Auth

https://github.com/OAI/OpenAPI-Specification/releases/tag/3.0.1 | Release OAS 3.0.1 Released! · OAI/OpenAPI-Specification

Google Auth
https://google-auth.readthedocs.io/en/latest/reference/google.oauth2.service_account.html#google.oauth2.service_account.Credentials.from_service_account_file | google.oauth2.service_account module — google-auth 1.6.2 documentation
-->

## JSON

<!--
Schema
http://json-schema.org/ | JSON Schema | The home of JSON Schema
https://schema.org/
https://dev.to/juliannatetreault/json-ld-what-it-is-and-how-dev-uses-it-4d25 | JSON-LD: What It Is and How DEV Uses It
-->

## Web Browser, Client/Server

Web Browsers and Servers
* [Web Browser Wikipedia](https://en.wikipedia.org/wiki/Web_browser)
* [Application Server Wikipedia](https://en.wikipedia.org/wiki/Application_server)
* [Web Server Wikipedia](https://en.wikipedia.org/wiki/Web_server)

Servers
* [Types of Servers Wikipedia](https://en.wikipedia.org/wiki/Server_(computing)#Purpose)

Client and Server-Side
* [Client Wikipedia](https://en.wikipedia.org/wiki/Client_(computing))
* [Server Wikipedia](https://en.wikipedia.org/wiki/Server_(computing))
* [Client Server Wikipedia](https://en.wikipedia.org/wiki/Client%E2%80%93server)
* [Client-Server Model Wikipedia](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)

Client-Side
* [Client-Side Wikipedia](https://en.wikipedia.org/wiki/Client-side)
* [Client-Side Scripting Wikipedia](https://en.wikipedia.org/wiki/Client-side_scripting)

Server-Side
* [Server-Side Wikipedia](https://en.wikipedia.org/wiki/Server-side)
* [Server-Side Scripting Wikipedia](https://en.wikipedia.org/wiki/Server-side_scripting)

Scripting, Client-Side and Server-Side
* [Scripting Language Wikipedia](https://en.wikipedia.org/wiki/Scripting_language)
* [Server Side Scripting Languages Wikipedia](https://en.wikipedia.org/wiki/Server-side_scripting#Languages)  
* [Client Side Scripting Languages Wikipedia](https://en.wikipedia.org/wiki/Dynamic_web_page#Client-side_scripting) 

## Networks

<!--
https://en.wikipedia.org/wiki/5G
https://en.wikipedia.org/wiki/4G | 4G - Wikipedia
-->

## Async- Other Languages

Rust Async
* [Rust async-await Hits Beta](https://blog.rust-lang.org/2019/09/30/Async-await-hits-beta.html)

<!--
https://github.com/tc39/proposal-top-level-await
https://v8.dev/features/top-level-await | Top-level await · V8

https://en.wikipedia.org/wiki/Node.js#Threading | Node.js - Wikipedia
https://nodejs.org/de/docs/guides/blocking-vs-non-blocking/
https://nodejs.org/en/knowledge/getting-started/control-flow/what-are-callbacks/
https://nodejs.org/en/knowledge/errors/what-are-the-error-conventions/
https://nodejs.org/api/worker_threads.html | Worker Threads | Node.js v12.4.0 Documentation

https://www.quora.com/Which-programming-languages-are-asynchronous
JavaScript
Promises
EcmaScript 2017- async and await keyword
setTimeout, setInterval, and setImmediate (Node.js only) 
https://nodejs.org/api/timers.html
https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout
https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval
https://developer.mozilla.org/en-US/docs/Web/API/Window/setImmediate

Node.js
Event-driven, asynchronous IO
https://www.tutorialspoint.com/nodejs/nodejs_event_loop
https://www.tutorialspoint.com/nodejs/nodejs_event_emitter.htm
-->

## Sync and Async

Runtime System, Execution, Thread, Process
* [Runtime System Wikipedia](https://en.wikipedia.org/wiki/Runtime_system)
* [Execution Wikipedia](https://en.wikipedia.org/wiki/Execution_(computing))
* [Thread Wikipedia](https://simple.wikipedia.org/wiki/Thread_(computer_science))
* [Thread Wikipedia](https://en.wikipedia.org/wiki/Thread_(computing))
* [Process Wikipedia](https://en.wikipedia.org/wiki/Process_(computing))

Threads and Multiprocessing
* [Multithreading Wikipedia](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture))
* [Thread Single vs. Multiprocessor System Wikipedia](https://en.wikipedia.org/wiki/Thread_(computing)#Single_vs_multiprocessor_systems)
* [Multiprocessing Wikipedia](https://en.wikipedia.org/wiki/Multiprocessing)

Avoiding Race Condition, Mutex or Semaphore, Global Interpreter Lock (GIL)
* [Race Condition- Software Wikipedia](https://en.wikipedia.org/wiki/Race_condition#Software)
* [Mutual Exclusion (Mutex) Wikipedia](https://en.wikipedia.org/wiki/Mutual_exclusion)
* [Semaphore Wikipedia](https://en.wikipedia.org/wiki/Semaphore_(programming))
* [Global Interpreter Lock (GIL) Wikipedia](https://en.wikipedia.org/wiki/Global_interpreter_lock)

Non-Blocking
* [Non-Blocking Algorithm Wikipedia](https://en.wikipedia.org/wiki/Non-blocking_algorithm)

Concurrency
* [Concurrency Wikipedia](https://en.wikipedia.org/wiki/Concurrency_(computer_science))
* [Concurrent Computing Wikipedia](https://en.wikipedia.org/wiki/Concurrent_computing)

Subroutine and Coroutine
* [Subroutine Wikipedia](https://en.wikipedia.org/wiki/Subroutine)
* [Coroutine Wikipedia](https://en.wikipedia.org/wiki/Coroutine)

Asynchrony
* [Asynchronous I/O Wikipedia](https://en.wikipedia.org/wiki/Asynchronous_I/O)
* [Asynchrony Wikipedia](https://en.wikipedia.org/wiki/Asynchrony_(computer_programming))
* [Asynchronous System Wikipedia](https://en.wikipedia.org/wiki/Asynchronous_system)
* [Asynchronous Communication Wikipedia](https://en.wikipedia.org/wiki/Asynchronous_communication)

Async/Await, Futures, Promises
* [Async/Await Wikipedia](https://en.wikipedia.org/wiki/Async/await)
* [Futures and Promises Wikipedia](https://en.wikipedia.org/wiki/Futures_and_promises)
* [Event Loop](https://en.wikipedia.org/wiki/Event_loop)

Benefits
* [WebSocket Wikipedia](https://en.wikipedia.org/wiki/WebSocket)
* [(Long) Polling Wikipedia](https://en.wikipedia.org/wiki/Polling_(computer_science))
* [Server-Sent Events](https://en.wikipedia.org/wiki/Server-sent_events)

<!--
https://slikts.github.io/concurrency-glossary/ | Concurrency Glossary

See Tom's Talk
Real time
non-blocking http requests
light-weight parallelization
https://en.wikipedia.org/wiki/Parallel_computing
explicit i/o

https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet
Also, Ajax Polling explained

polling versus webhooks
https://zapier.com/blog/what-are-webhooks/ | What Are Webhooks?
-->

<!--
Sockets
https://realpython.com/python-sockets
https://www.geeksforgeeks.org/socket-programming-python

Websockets
https://stackoverflow.com/questions/19169427/how-websockets-can-be-faster-than-a-simple-http-request
https://www.tutorialspoint.com/html5/html5_websocket.htm

Concurrency
https://www.tutorialspoint.com/concurrency_in_python/concurrency_in_python_eventdriven_programming.htm | Concurrency in Python Event-Driven Programming
https://www.geeksforgeeks.org/operating-system-difference-multitasking-multithreading-multiprocessing/
-->

## Benchmarking

Performance
* [Latency Wikipedia](https://en.wikipedia.org/wiki/Latency_(engineering))
* [Bandwidth Wikipedia](https://en.wikipedia.org/wiki/Bandwidth_(computing))
* [Throughput Wikipedia](https://en.wikipedia.org/wiki/Throughput)

Throttling and Rate Limiting
* [Throttling Wikipedia](https://en.wikipedia.org/wiki/Throttling_process_(computing))
* [Bandwidth Throttling Wikipedia](https://en.wikipedia.org/wiki/Bandwidth_throttling)
* [Rate Limiting Wikipedia](https://en.wikipedia.org/wiki/Rate_limiting)

<!--
What are the Numbers that Every Computer Engineer Should Know http://www.quora.com/What-are-the-numbers-that-every-computer-engineer-should-know-according-to-Jeff-Dean
https://gist.github.com/jboner/2841832
http://www.eecs.berkeley.edu/~rcs/research/interactive_latency.html
http://highscalability.com/numbers-everyone-should-know
http://static.googleusercontent.com/media/research.google.com/en//people/jeff/stanford-295-talk.pdf
http://norvig.com/21-days.html#answers
https://dzone.com/articles/every-programmer-should-know

https://en.wikipedia.org/wiki/Latency_(engineering)#Computer_hardware_and_operating_system_latency | Latency (engineering) - Wikipedia
-->

## Database Architectures and Principles

CAP Theorem
* [CAP Theorem Wikipedia](https://en.wikipedia.org/wiki/CAP_theorem)
* [Consistency (Database Systems) Wikipedia](https://en.wikipedia.org/wiki/Consistency_(database_systems))
* [Availability Wikipedia](https://en.wikipedia.org/wiki/Availability)
* [Network Partition Wikipedia](https://en.wikipedia.org/wiki/Network_partition)

Database Principles
* [Database Transaction Wikipedia](https://en.wikipedia.org/wiki/Database_transaction)
* [Atomicity, Consistency, Isolation, Durability (ACID) Wikipedia](https://en.wikipedia.org/wiki/ACID_(computer_science))
* [Basically Available, Soft state, Eventual Consistency (BASE) Wikipedia](https://en.wikipedia.org/wiki/Eventual_consistency)
* [Create, Read, Update and Delete (CRUD) Wikipedia](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete)

Distributed and Parallel Computing
* [Load Balancing Wikipedia](http://en.wikipedia.org/wiki/Load_balancing_(computing))  
* [Fallacies of Distributed Computing Wikipedia](http://en.wikipedia.org/wiki/Fallacies_of_Distributed_Computing)  
* [Parallel Computing Wikipedia](http://en.wikipedia.org/wiki/Parallel_computing) 

Shard
* [Shard Wikipedia](http://en.wikipedia.org/wiki/Shard_(database_architecture)) 

<!--
https://en.wikipedia.org/wiki/Online_analytical_processing
https://en.wikipedia.org/wiki/Create,_read,_update_and_delete#Database_applications | Create, read, update and delete - Wikipedia

https://en.wikipedia.org/wiki/Multitenancy
https://en.wikipedia.org/wiki/Federated_database_system
delegated database
Google Spanner versus Calvin Protocol - Google Search

AP, CP or CA Databases

https://en.wikipedia.org/wiki/Distributed_transaction
https://en.wikipedia.org/wiki/Atomic_commit
https://en.wikipedia.org/wiki/Two-phase_commit_protocol | Two-phase commit protocol - Wikipedia

OOP
https://en.wikipedia.org/wiki/Cohesion_(computer_science)#High_cohesion

System
https://en.wikipedia.org/wiki/High_availability
https://en.wikipedia.org/wiki/Failover
https://en.wikipedia.org/wiki/Fault_tolerance
-->

## Database Options

Databases
* [Database Wikipedia](http://en.wikipedia.org/wiki/Database)  
* [Databases (Category) Wikipedia](http://en.wikipedia.org/wiki/Category:Databases)  
* [Types of Databases (Category) Wikipedia](http://en.wikipedia.org/wiki/Category:Types_of_databases)  
* [Database Management Systems (Category) Wikipedia](http://en.wikipedia.org/wiki/Category:Database_management_systems)
* [Comparison of Database Tools Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_database_tools)  

Schema and Model
* [Database Schema Wikipedia](http://en.wikipedia.org/wiki/Database_schema)  
* [Database Model Wikipedia](http://en.wikipedia.org/wiki/Database_model) 

Relational
* [Relational Algebra Wikipedia](https://en.wikipedia.org/wiki/Relational_algebra)
* [Relational Model Wikipedia](https://en.wikipedia.org/wiki/Relational_model)
* [Relational Database Wikipedia](https://en.wikipedia.org/wiki/Relational_database)
* [The General Structure of a Relational Database Wikipedia](https://en.wikipedia.org/wiki/Relational_database_management_system#/media/File:RDBMS_structure.png)

Examples of Popular Relational Databases
* [SQLite Wikipedia](https://en.wikipedia.org/wiki/SQLite)
* [PostgreSQL Wikipedia](https://en.wikipedia.org/wiki/PostgreSQL)
* [MySQL Wikipedia](https://en.wikipedia.org/wiki/MySQL)

Relational
* [Relational Database Management System (RDBMS) Wikipedia](http://en.wikipedia.org/wiki/Relational_database_management_system) 
* [Comparison of Relational Database Management Systems (RDBMS) Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_relational_database_management_systems)
* [List of Relational Database Management Systems (RDBMS) Wikipedia](https://en.wikipedia.org/wiki/List_of_relational_database_management_systems)

Object-Relational Database
* [Object-Relational Mapping Wikipedia](https://en.wikipedia.org/wiki/Object-relational_mapping)
* [Object Relational Database Wikipedia](http://en.wikipedia.org/wiki/Object-relational_database)  
* [Comparison of Object-Relational Database Management Systems Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_object-relational_database_management_systems)

Architecture
* [The Active Record Paradigm](https://en.wikipedia.org/wiki/Active_record_pattern) and the [concept](http://stackoverflow.com/a/1152323) of an Object/Relational Mapper (ORM)  

<!--
* [Online Database Wikipedia](http://en.wikipedia.org/wiki/Online_database)  
-->

More Database Stuff
* [Object Database Wikipedia](http://en.wikipedia.org/wiki/Object_database)  
* [Document Oriented Databases (Category) Wikipedia](http://en.wikipedia.org/wiki/Category:Document-oriented_databases)
* [NoSQL (Category) Wikipedia](http://en.wikipedia.org/wiki/Category:NoSQL)  
* [NoSQL Wikipedia](http://en.wikipedia.org/wiki/NoSQL)  
* [Document Oriented Databases (Category) Wikipedia](http://en.wikipedia.org/wiki/Category:Document-oriented_databases)  
* [Document Oriented Databases Wikipedia](http://en.wikipedia.org/wiki/Document-oriented_database)  
* [Column Oriented Database Management System Wikipedia](http://en.wikipedia.org/wiki/Column-oriented_DBMS)  

<!--
ORM, MRO
https://www.fullstackpython.com/object-relational-mappers-orms.html
-->

<!--
https://en.wikipedia.org/wiki/Primary_key

https://twitter.com/simonw/status/1113134366601838592
https://backchannel.org/blog/friendfeed-schemaless-mysql | How FriendFeed uses MySQL to store schema-less data

https://stackoverflow.com/questions/31641504/adjacency-list-model-vs-nested-set-model-for-mysql-hierarchical-data

http://en.wikipedia.org/wiki/Database_normalization
http://en.wikibooks.org/wiki/Relational_Database_Design/Normalization

http://en.wikipedia.org/wiki/Comparison_of_relational_database_management_systems#Fundamental_features
http://en.wikipedia.org/wiki/Relational_database#Relations_or_Tables
-->

## SQL

* [SQL (RDBMS) Wikipedia](https://en.wikipedia.org/wiki/SQL)  
* [W3Schools SQL](http://www.w3schools.com/sql/default.asp)
* [Learn to Code the Hard Way- SQL](http://sql.learncodethehardway.org/book/introduction.html)  
* [Khan Academy Intro to SQL](https://www.khanacademy.org/computing/computer-programming/sql)

<!--
http://en.wikipedia.org/wiki/SQL#Queries
-->

Stanford Open Classroom- Introduction to Databases
* [Stanford Open Classroom- Introduction to Databases](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=IntroToDatabases)  

## Protocols

Network Protocols
* [Lists of Network Protocols - Wikipedia](https://en.wikipedia.org/wiki/Lists_of_network_protocols)

Request and Response Cycle- TCP-IP and OSI Protocols
* [OSI Model Wikipedia](https://en.wikipedia.org/wiki/OSI_model) and [OSI Protocols Wikipedia](https://en.wikipedia.org/wiki/OSI_protocols)
* [Transmission Control Protocol Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
* [Internet Protocol Suite Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
* [Internet Protocol Wikipedia](https://en.wikipedia.org/wiki/Internet_Protocol)

<!--
https://en.wikipedia.org/wiki/OSI_model
https://en.wikipedia.org/wiki/Application_layer
https://en.wikipedia.org/wiki/Presentation_layer
https://en.wikipedia.org/wiki/Session_layer
https://en.wikipedia.org/wiki/Transport_layer
https://en.wikipedia.org/wiki/Network_layer
https://en.wikipedia.org/wiki/Data_link_layer
https://en.wikipedia.org/wiki/Physical_layer

https://en.wikipedia.org/wiki/Internet_Protocol
https://en.wikipedia.org/wiki/Internet_protocol_suite
https://en.wikipedia.org/wiki/Transmission_Control_Protocol
https://en.wikipedia.org/wiki/Internet_layer
https://en.wikipedia.org/wiki/Link_layer
-->

TCP
* [Transmission Control Protocol (TCP) Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
* [Persistent Connection Wikipedia](https://en.wikipedia.org/wiki/HTTP_persistent_connection)
* [HTTP Persistent Connection Wikipedia](https://en.wikipedia.org/wiki/HTTP_persistent_connection)

## How Do It Work

<!--
https://en.wikipedia.org/wiki/CPU_cache
https://en.wikipedia.org/wiki/Cache_(computing)

https://www.amazon.com/But-How-Know-Principles-Computers-ebook/dp/B00F25LEVC | Amazon.com: But How Do It Know? - The Basic 
https://www.amazon.com/Ones-and-Zeros-Understanding-Boolean-Algebra-Digital-Circuits-and-the-Logic-of-Sets/dp/0780334264/ref=cm_cr_arp_d_rvw_txt?ie=UTF8 | Ones and Zeros: Understanding Boolean Algebra, Digital Circuits, and the Logic of Sets: John R. Gregg: 9780780334267: Amazon.com: Books
http://www.buthowdoitknow.com/ | But How Do It Know - the book. The basic principles of computers
http://www.buthowdoitknow.com/cpu_model_intro.html | But How Do It Know - the book. The basic principles of computers
http://www.buthowdoitknow.com/but_how_do_it_know_cpu_model.html | but_how_do_it_know_cpu_model
https://www.youtube.com/watch?v=cNN_tTXABUA | (1) How a CPU Works - YouTube
https://www.youtube.com/watch?v=NKYgZH7SBjk | (1) This is What's Inside a CPU - YouTube
http://buthowdoitknow.com/preview.html | But How Do It Know - the book. The basic principles of computers
https://djhworld.github.io/post/2019/05/21/i-dont-know-how-cpus-work-so-i-simulated-one-in-code/ | I don't know how CPUs work so I simulated one in code - djhworld
https://github.com/djhworld/simple-computer | djhworld/simple-computer: the scott CPU from "But How Do It Know?" by J. Clark Scott
https://github.com/nullseed/scott-cpu-assembler | nullseed/scott-cpu-assembler: A machine code assembler for the CPU designed in the book But How Do It Know? by J. Clark Scott

https://read.amazon.com/?asin=B00F25LEVC | Kindle Cloud Reader
-->

## General

Binary
* [Binary Number Wikipedia](https://en.wikipedia.org/wiki/Binary_number)
* [Binary Code Wikipedia](https://en.wikipedia.org/wiki/Binary_code)
* [Units of Information Wikipedia](https://en.wikipedia.org/wiki/Units_of_information)
* [Power of Two Wikipedia](https://en.wikipedia.org/wiki/Power_of_two)

Low-Level Programming Language, Machine Code, Assembly Language
* [Low-Level Programming Language Wikipedia](https://en.wikipedia.org/wiki/Low-level_programming_language)
* [Machine Code Wikipedia](https://en.wikipedia.org/wiki/Machine_code)
* [Assembly Language Wikipedia](https://en.wikipedia.org/wiki/Assembly_language)

<!--
https://en.wikipedia.org/wiki/Register_transfer_language | Register transfer language - Wikipedia
https://en.wikipedia.org/wiki/ANSI_C | ANSI C - Wikipedia
https://en.wikipedia.org/wiki/Arithmetic_logic_unit | Arithmetic logic unit - Wikipedia
https://en.wikipedia.org/wiki/Control_unit | Control unit - Wikipedia
https://en.wikipedia.org/wiki/Processor_register | Processor register - Wikipedia
https://en.wikipedia.org/wiki/Memory_address_register
https://en.wikipedia.org/wiki/XOR_gate | XOR gate - Wikipedia
https://en.wikipedia.org/wiki/NAND_gate | NAND gate - Wikipedia
https://en.wikipedia.org/wiki/Logical_shift | Logical shift - Wikipedia

http://sparksandflames.com/files/x86InstructionChart.html | Intel x86 Assembler Instruction Set Opcode Table
-->

<!--
https://en.wikipedia.org/wiki/256-bit | 256-bit - Wikipedia
https://en.wikipedia.org/wiki/8-bit | 8-bit - Wikipedia

https://en.wikipedia.org/wiki/Decimal_system | Decimal system - Wikipedia
http://www.asciitable.com/ | Ascii Table - ASCII character codes and html, octal, hex and decimal chart conversion
https://en.wikipedia.org/wiki/ASCII
https://en.wikipedia.org/wiki/Hexadecimal | Hexadecimal - Wikipedia
-->

## Architecture- Important Concepts

Computer Architecture
* [Computer Architecture Wikipedia](https://en.wikipedia.org/wiki/Computer_architecture)
* [von Neumann Architecture Wikipedia](https://en.wikipedia.org/wiki/Von_Neumann_architecture)
* [John von Neumann Wikipedia](https://en.wikipedia.org/wiki/John_von_Neumann)

<!--
https://en.wikipedia.org/wiki/MIPS_architecture | MIPS architecture - Wikipedia
-->

Microprocessor
* [Microprocessor Wikipedia](https://en.wikipedia.org/wiki/Microprocessor)
* [Microprocessor Design Wikipedia](https://en.wikibooks.org/wiki/Microprocessor_Design)

CPU
* [Central Processing Unit Wikipedia](https://en.wikipedia.org/wiki/Central_processing_unit)
* [List of CPU Architectures Wikipedia](https://en.wikipedia.org/wiki/List_of_CPU_architectures)

Instruction Set (CPU)
* [Instruction Set Wikipedia](https://en.wikipedia.org/wiki/Instruction_set)
* [Comparison of Instruction Set Architectures Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_instruction_set_architectures)
* [Instruction Set Architecture Wikipedia](https://en.wikipedia.org/wiki/Instruction_set_architecture)
* [Instruction Set Architecture Instructions Wikipedia](https://en.wikipedia.org/wiki/Instruction_set_architecture#Instructions)
* [Computer Architecture Instruction Set Architecture Wikipedia](https://en.wikipedia.org/wiki/Computer_architecture#Instruction_set_architecture)
* [Machine Code Instruction Set Wikipedia](https://en.wikipedia.org/wiki/Machine_code#Instruction_set)
* [Comparison of Instruction Set Architectures Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_instruction_set_architectures)

<!--
https://en.wikipedia.org/wiki/Comparison_of_CPU_microarchitectures
https://en.wikipedia.org/wiki/X86_instruction_listings

https://en.wikipedia.org/wiki/Reduced_instruction_set_computer | Reduced instruction set computer - Wikipedia

RISC versus CISC
https://en.wikipedia.org/wiki/Complex_instruction_set_computer#:~:text=A%20complex%20instruction%20set%20computer,addressing%20modes%20within%20single%20instructions. | Complex instruction set computer - Wikipedia

https://en.wikipedia.org/wiki/Modern_Operating_Systems | Modern Operating Systems - Wikipedia
-->

Types of CPUs
* [Intel Core Wikipedia](https://en.wikipedia.org/wiki/Intel_Core)
* [Apple–Intel Architecture Wikipedia](https://en.wikipedia.org/wiki/Apple%E2%80%93Intel_architecture)

Components
* [Instruction Register Wikipedia](https://en.wikipedia.org/wiki/Instruction_register)

Comparison of File Systems
* [Comparison of File Systems Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_file_systems)

Unix
* [Unix Wikipedia](http://en.wikipedia.org/wiki/Unix)  
* [Unix History SVG Wikipedia](http://en.wikipedia.org/wiki/File:Unix_history-simple.svg) 
* [Unix Wars Wikipedia](https://en.wikipedia.org/wiki/Unix_wars) 
* [List of Web Browsers for Unix and Unix-Like Operating Systems Wikipedia](https://en.wikipedia.org/wiki/List_of_web_browsers_for_Unix_and_Unix-like_operating_systems)
* [Unix-Like Wikipedia](https://en.wikipedia.org/wiki/Unix-like)
* [POSIX (Compatible with Unix) Wikipedia](https://en.wikipedia.org/wiki/POSIX)

Unix File System
* [Unix File System Wikipedia](https://en.wikipedia.org/wiki/Unix_File_System)
* [Unix Filesystem Hierarchy Standard Wikipedia](http://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard)
* [Unix Filesystem Conventional Directory Layout](https://en.wikipedia.org/wiki/Unix_filesystem#Conventional_directory_layout)

<!--
https://en.wikipedia.org/wiki/Intel
https://en.wikipedia.org/wiki/Advanced_Micro_Devices

https://en.wikipedia.org/wiki/Unix_philosophy#Do_One_Thing_and_Do_It_Well | Unix philosophy - Wikipedia

https://en.wikipedia.org/wiki/Lions'_Commentary_on_UNIX_6th_Edition,_with_Source_Code | Lions' Commentary on UNIX 6th Edition, with Source Code - Wikipedia
https://github.com/qrush/unix | qrush/unix: Mirror of the Restoration of 1st Edition UNIX kernel sources from pdf document.
-->

Linux
* [Linux GitHub](https://github.com/torvalds/linux)

<!--
https://makelinux.github.io/kernel/map/ | Interactive map of Linux kernel

Linux Performance Observability Tools
https://twitter.com/0xUID/status/1060642608630980609 | Anis ⣢ on Twitter: "Wow nice, haven't seen this before. #Linux 

Linux networking tools
https://twitter.com/b0rk/status/1204839971913379840

https://www.cs.helsinki.fi/u/kutvonen/index_files/linus.pdf
https://linux-kernel-labs.github.io/refs/heads/master/index.html

https://www.quora.com/What-is-the-difference-between-a-CPU-and-an-OS
https://stackoverflow.com/questions/23857542/how-does-an-os-communicate-with-the-cpu
http://pages.cs.wisc.edu/~remzi/OSTEP/

https://en.wikipedia.org/wiki/Unix_architecture | Unix architecture - Wikipedia
https://en.wikipedia.org/wiki/Unix_architecture#Kernel | Unix architecture - Wikipedia
https://en.wikipedia.org/wiki/Linux_kernel | Linux kernel - Wikipedia
https://en.wikipedia.org/wiki/Linux_kernel_interfaces#Linux_API | Linux kernel interfaces - Wikipedia

Important! A Heavily Commented Linux Kernel Source Code
http://www.oldlinux.org/download/ECLK-5.0-WithCover.pdf | ECLK-5.0-WithCover.pdf

https://github.com/0xAX/linux-insides | 0xAX/linux-insides: A little bit about a linux kernel

https://github.com/microsoft/WSLv2-Linux-Kernel | microsoft/WSLv2-Linux-Kernel: The Linux kernel underpinning the new Windows Subsystem for Linux v2

https://twitter.com/mattblaze/status/1092222055754489856 | matt blaze on Twitter: "This handy pocket guide to Unix (what your grandparents called Linux) was printed 35 years ago and is still mostly current.… https://t.co/5NKjFRAu0R"
https://opensource.com/article/18/5/differences-between-linux-and-unix | Linux vs. Unix: What's the difference? | Opensource.com

https://twitter.com/Alra3ees/status/1181028153944358913 | Emad Shanab on Twitter: "Linux directories cheat sheet. https://t.co/qClnTgfioI" / Twitter
https://twitter.com/brendangregg/status/1150796412931600384/photo/2
https://twitter.com/brendangregg/status/1150796412931600384 | Brendan Gregg on Twitter: "Announcing my next book: BPF Performance Tools: Linux System and Application Observability, for which I developed over 100 new tools https://t.co/GiYiBPICo5… https://t.co/bhGDofUj7Z"
http://www.brendangregg.com/blog/2019-07-15/bpf-performance-tools-book.html | BPF Performance Tools: Linux System and Application Observability (book)
https://www.google.com/search?q=linux+performance+tools&source=lnms&tbm=isch&sa=X&ved=0ahUKEwj6xP6t27fjAhWEZs0KHQd_D0wQ_AUIECgB&biw=1365&bih=614#imgrc=ZXehEkMmqZ0v3M: | linux performance tools - Google Search

Commands
http://man7.org/linux/man-pages/man2/ptrace.2.html | ptrace(2) - Linux manual page
https://en.wikipedia.org/wiki/Ptrace | ptrace - Wikipedia
http://man7.org/linux/man-pages/ | Linux man pages online
https://www.tutorialspoint.com/unix/unix-manpage-help | Unix / Linux Shell Manpage Help
-->

Compiler
* [Compiler Wikipedia](http://en.wikipedia.org/wiki/Compiler) 	
* [GNU Compiler Collection (Unix, BSD)](https://gcc.gnu.org) and [GNU Compiler Collection Wikipedia](https://en.wikipedia.org/wiki/GNU_Compiler_Collection)	
* [LLVM (FreeBSD, Mac OS X)](http://llvm.org) and [LLVM Wikipedia](https://en.wikipedia.org/wiki/LLVM)	
* [Clang C Language Frontend for LLVM](https://clang.llvm.org), [Clang GitHub](https://github.com/llvm-mirror/clang ), [Clang Wikipedia](https://en.wikipedia.org/wiki/Clang)

<!--	
https://clang.llvm.org/comparison.html

Apple
https://github.com/opensource-apple/xnu | opensource-apple/xnu: The Darwin Kernel (mirror)
https://en.wikipedia.org/wiki/XNU | XNU - Wikipedia
https://en.wikipedia.org/wiki/Darwin_(operating_system) | Darwin (operating system) - Wikipedia

https://stackoverflow.com/questions/44632432/what-does-gcc-have-to-do-with-a-python-interpreter | What does GCC have to do with a python interpreter? - Stack Overflow	
-->

<!--
KLEE LLVM Execution Engine
https://klee.github.io/ | KLEE	

Deep Learning
https://github.com/dmlc/tvm | dmlc/tvm: bring deep learning workloads to bare metal	
https://github.com/dlvm-team/ | DLVM	

https://github.com/ovh | OVH
https://github.com/ovh/cds | ovh/cds: Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform

https://erlef.org/ | Erlang Ecosystem Foundation – The Erlang Ecosystem 
https://elixir-lang.org/ | Elixir
-->
