# Web, Request/Response, Async

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

## Computer Architecture

CPU versus IO
* [Central Processing Unit Wikipedia](https://en.wikipedia.org/wiki/Central_processing_unit)
* [Input/Output (I/O) Wikipedia](https://en.wikipedia.org/wiki/Input/output)
* [I/O Bound Wikipedia](https://en.wikipedia.org/wiki/I/O_bound)
* [CPU Bound Wikipedia](https://en.wikipedia.org/wiki/CPU-bound | CPU-bound - Wikipedia)
* [I/O Bound Comparison with CPU Bound Wikipedia](https://en.wikipedia.org/wiki/I/O_bound#Comparison_with_CPU-bound)

Ports
* [Port Wikipedia](https://en.wikipedia.org/wiki/Port_(computer_networking))

HTTP versus Websocket
* [Hypertext Transfer Protocol (HTTP) Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
* [Network Socket Wikipedia](https://en.wikipedia.org/wiki/Network_socket)
* [WebSocket Wikipedia](https://en.wikipedia.org/wiki/WebSocket)

Application Programming Interface (API)
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
https://medium.com/@__xuorig__/is-graphql-still-relevant-in-an-http2-world-64964f207b8
https://github.com/graphql/graphql-js | graphql/graphql-js: A reference implementation of GraphQL for JavaScript
https://github.com/graphql-python | GraphQL Python
-->

REST payload formatted in HTML, JSON, XML, etc. (Most commonly HTTP is used; HTTP methods available are GET, HEAD, POST, PUT, PATCH, DELETE, CONNECT, OPTIONS and TRACE.)
* [JSON Wikipedia](https://en.wikipedia.org/wiki/JSON)

Webhooks (The format is usually JSON. The request is done as a HTTP POST request.)
* [Callback Wikipedia](https://en.wikipedia.org/wiki/Callback_(computer_programming))

Callbacks (implemented often as subroutines, lambda expressions, blocks, or function pointers)
* [Webhook Wikipedia](https://en.wikipedia.org/wiki/Webhook)

Ajax
* [Ajax Wikipedia](https://en.wikipedia.org/wiki/Ajax_(programming))
* [List of Ajax Frameworks Wikipedia](https://en.wikipedia.org/wiki/List_of_Ajax_frameworks#JavaScript)

<!--
https://en.wikipedia.org/wiki/Representational_state_transfer#Relationship_between_URI_and_HTTP_methods
https://en.wikipedia.org/wiki/Representational_state_transfer#Architectural_constraints | Representational state transfer - Wikipedia

https://simpleisbetterthancomplex.com/tutorial/2016/10/31/how-to-handle-github-webhooks-using-django.html
https://simpleisbetterthancomplex.com/tutorial/2016/07/27/how-to-return-json-encoded-response.html
https://simpleisbetterthancomplex.com/tutorial/2016/08/29/how-to-work-with-ajax-request-with-django.html

Important
https://www.quora.com/What-is-the-difference-between-HTTP-and-WebSocket-in-simple-words
https://stackoverflow.com/questions/152457/what-is-the-difference-between-a-port-and-a-socket

https://en.wikipedia.org/wiki/Application_programming_interface
"When used in the context of web development, an API is typically defined as a set of specifications, such as Hypertext Transfer Protocol (HTTP) request messages, along with a definition of the structure of response messages, usually in an Extensible Markup Language (XML) or JavaScript Object Notation (JSON) format."

https://en.wikipedia.org/wiki/Memory_bound_function

Interesting!
https://en.wikipedia.org/wiki/Execution_model
https://en.wikipedia.org/wiki/Scheduling_(computing)

https://en.wikipedia.org/wiki/Concurrency_(computer_science)#Models
https://en.wikipedia.org/wiki/Message_passing | Message passing - Wikipedia
https://en.wikipedia.org/wiki/Event-driven_programming
https://en.wikipedia.org/wiki/Event-driven_messaging

https://hackernoon.com/webhook-vs-api-whats-the-difference-8d41e6661652
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

## Request and Response Cycle, HTTP

Request and Response Cycle
* [Request Response Wikipedia](https://en.wikipedia.org/wiki/Request%E2%80%93response)

HTTP and HTTPS
* [Hypertext Wikipedia](https://en.wikipedia.org/wiki/Hypertext)
* [Hypertext Transfer Protocol (HTTP) Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
* [Hypertext Transfer Protocol Secure (HTTPS) Wikipedia](https://en.wikipedia.org/wiki/HTTPS)

Request and Response Cycle- HTTP
* [List of HTTP Status Codes Wikipedia](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)
* [List of HTTP Header Fields Wikipedia](http://en.wikipedia.org/wiki/List_of_HTTP_header_fields)  
* [List of HTTP Request Methods Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods) 
* [Post (HTTP) Wikipedia](https://en.wikipedia.org/wiki/POST_(HTTP)) 
* [HTTP Body Data Response Example Wikipedia](http://en.wikipedia.org/wiki/HTTP_body_data#Response_example)
* [HTTP Referer Wikipedia](https://en.wikipedia.org/wiki/HTTP_referer)

Sessions
* [Web Browing History Wikipedia](https://en.wikipedia.org/wiki/Web_browsing_history)
* [Session Wikipedia](https://en.wikipedia.org/wiki/Session_(computer_science))
* [Session ID Wikipedia](https://en.wikipedia.org/wiki/Session_ID)

Cookies
* [jQuery Cookie GitHub](https://github.com/carhartl/jquery-cookie)  
* [HTTP Cookie Wikipedia](http://en.wikipedia.org/wiki/HTTP_cookie)  
* [Browser Cookie Wikipedia](http://en.wikipedia.org/wiki/Browser_cookie) 

<!--
https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#Generic_syntax
https://en.wikipedia.org/wiki/Uniform_Resource_Identifier | Uniform Resource Identifier - Wikipedia
https://en.wikipedia.org/wiki/UTM_parameters | UTM parameters - Wikipedia
https://en.wikipedia.org/wiki/Query_string | Query string - Wikipedia
https://en.wikipedia.org/wiki/Content_sniffing | Content sniffing - Wikipedia

https://en.wikipedia.org/wiki/Server_log
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

