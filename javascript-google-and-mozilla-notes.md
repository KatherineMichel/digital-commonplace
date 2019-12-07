# JavaScript- Google and Mozilla Notes

<!--
https://twitter.com/js_tut/status/1199735352392650754
https://twitter.com/js_tut/status/1141698543712972801 | JavaScript Teacher on Twitter: "console.log("good morning"); vanilla #JavaScript let morning:good = true; #TypeScript $(good).morning(); #jQuery <GoodMorning /> #ReactJS <p v-good="morning"> #VueJS { good { morning } } #GraphQL print "good morning" #Python echo "good morning"; #PHP Good morning. #Human"
https://twitter.com/js_tut/status/1141838103763701760 | JavaScript Teacher on Twitter: "If you've never spoken JavaScript, here's a good start: 1. class / import / new 2. () => {} arrow functions 3. understanding === operator 4. Learn Array.* higher-order functions (.filter, .map & .reduce) 5. async / await 6. import / export 7. [] is iterable 8. {} is enumerable"
https://twitter.com/_ericelliott/status/1141405592294219782 | Eric Elliott on Twitter: "Every JS app developer needs to know: -FP basics: pure functions, curry, function composition -objects: composition vs inheritance -async patterns: callbacks, promises, events, streams"
https://twitter.com/rwieruch/status/1150796165702660096 | Robin Wieruch on Twitter: "Enough JavaScript to learn React 👇🏽 ✅ Classes ✅ Arrow Functions ✅ Template Literals ✅ Map, Filter, Reduce ✅ Conditionals ✅ Import/Export ✅ Libraries ✅ Async/Await ✅ Higher-Order Functions and much more. Revamped from last year 🎉 https://t.co/rB9ouzYrzj"
-->

WebSockets and Server-Sent Events
* [Mozilla WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket), [Mozilla WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API), and [Mozilla Writing WebSocket servers](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_servers)
* [Mozilla Server-Sent Event](https://developer.mozilla.org/en-US/docs/Web/API/EventSource)

Mozilla WebRTC
* [Mozilla WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)

WebAssembly
* [WebAssembly](https://webassembly.org/)
* [Mozilla WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly)

<!--
https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/ | Standardizing WASI: A system interface to run WebAssembly outside the web - Mozilla Hacks - the Web developer blog

WebAssembly
https://hacks.mozilla.org/2018/04/sneak-peek-at-webassembly-studio/ | Sneak Peek at WebAssembly Studio – Mozilla Hacks – the Web developer blog
https://hacks.mozilla.org/2018/10/calls-between-javascript-and-webassembly-are-finally-fast-%F0%9F%8E%89/ | Calls between JavaScript and WebAssembly are finally fast 🎉 - Mozilla Hacks - the Web developer blog
-->

Mobile-y Kinds of Things
* [Google Push Notifications](https://developers.google.com/web/fundamentals/push-notifications)
* [Mozilla Permissions](https://developer.mozilla.org/en-US/docs/Web/API/Permissions_API)
* [Mozilla Geolocation](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation)
* [Mozilla Web Notifications](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API) 
* [Mozilla Vibration](https://developer.mozilla.org/en-US/docs/Web/API/Vibration_API)

Application Shell Architecture (PWA and Service Workers)
* [Instant Loading Web Apps with an Application Shell Architecture](https://developers.google.com/web/updates/2015/11/app-shell)

Web Workers
* [Mozilla Web Workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API)

Service Workers (Offline)
* [Mozilla Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) and [Mozilla Using Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
* [Google Service Workers: an Introduction](https://developers.google.com/web/fundamentals/primers/service-workers) and [Google The Service Worker Lifecycle](https://developers.google.com/web/fundamentals/primers/service-workers/lifecycle)
* [Google Introduction to Service Worker](https://developers.google.com/web/ilt/pwa/introduction-to-service-worker)

Offline
* [Mozilla Web Storage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)
* [Mozilla IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API#database_connection)
* [Mozilla FileReader](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)
* [Mozilla File](https://developer.mozilla.org/en-US/docs/Web/API/File)
* [Mozilla Blob](https://developer.mozilla.org/en-US/docs/Web/API/Blob)
 
<!--
* [Service Workers Explained](https://github.com/w3c/ServiceWorker/blob/master/explainer.md)

https://github.com/w3c/payment-request | w3c/payment-request: W3C Web Payments Browser API
https://github.com/w3c/webpayments | w3c/webpayments: The document repo for the Web Payments Working Group
https://github.com/w3c/webauthn | w3c/webauthn: Web Authentication WG: https://www.w3.org/Webauthn Editors' Draft:

https://www.w3.org/TR/push-api
https://www.w3.org/TR/notifications

* Access
  * [URL](https://developer.mozilla.org/en-US/docs/Web/API/URL), [History](https://developer.mozilla.org/en-US/docs/Web/API/History), [Navigator](https://developer.mozilla.org/en-US/docs/Web/API/Navigator), [Screen](https://developer.mozilla.org/en-US/docs/Web/API/Screen), [Page Visibility](https://developer.mozilla.org/en-US/docs/Web/API/Page_Visibility_API), [Clipboard](https://developer.mozilla.org/en-US/docs/tag/Clipboard%20API), [Performance](https://developer.mozilla.org/en-US/docs/Web/API/Performance), [Console](https://developer.mozilla.org/en-US/docs/Web/API/Console)

HTTP
* [Google HTTP Caching (Performance)](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching) and [Mozilla HTTP Caching](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)
* [Compression in HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Compression)
* [HTTP Strict-Transport-Security (HSTS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Strict-Transport-Security)

* [Google Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)  
   
* [Is TLS Fast Yet?](https://istlsfastyet.com/) / [HTTP vs HTTPS Test](https://www.httpvshttps.com/)

HTTP/2
* [Google Introduction to HTTP/2](https://developers.google.com/web/fundamentals/performance/http2/)

* UDP
  * [QUIC](https://www.chromium.org/quic)
  
Mutation Observers
* [Detect DOM changes with Mutation Observers](https://developers.google.com/web/updates/2012/02/Detect-DOM-changes-with-Mutation-Observers)

Appearance
  * [Web Components](https://developers.google.com/web/updates/2017/01/webcomponents-org)
    * [Shadow DOM v1](https://developers.google.com/web/fundamentals/getting-started/primers/shadowdom), [Custom Elements v1](https://developers.google.com/web/fundamentals/getting-started/primers/customelements)
  * [Web Animations](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API)
-->

## Mozilla- HTTP, Request and Response Cycle

Mozilla- HTTP- General
* [Mozilla An Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
* [Mozilla Evolution of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP)
* [Mozilla HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)

Mozilla- HTTP- Specifics
* [Mozilla HTTP Methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)
* [Mozilla HTTP Messages](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages)
* [Mozilla HTTP Headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
* [Mozilla HTTP Response Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
* [Mozilla HTTP Sessions](https://developer.mozilla.org/en-US/docs/Web/HTTP/Session)
* [Mozilla Redirections in HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Redirections)
* [Mozilla Identifying resources on the Web](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Identifying_resources_on_the_Web)
* [Mozilla MIME types](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_Types)
     
<!--
https://en.wikipedia.org/wiki/Web_framework | Web framework - Wikipedia

https://www.udacity.com/course/http-web-servers--ud303
https://github.com/udacity/course-ud303

https://developer.mozilla.org/en-US/docs/Web/API/Request | Request - Web APIs | MDN
https://developer.mozilla.org/en-US/docs/Web/API/Response | Response - Web APIs | MDN

https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines | What is the difference between webpage, website, web server, and search engine? - Learn web development | MDN

https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Introduction | Introduction to the server side - Learn web development | MDN

https://developer.mozilla.org/en-US/docs/Glossary/Proxy_server | Proxy server - MDN Web Docs Glossary: Definitions of Web-related terms | MDN

https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Type
https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Length
https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms
-->

<!--
https://developer.mozilla.org/en-US/docs/tag/Web

https://mdn.dev

https://developer.mozilla.org/en-US/docs/

https://developer.mozilla.org/en-US/Apps

https://developer.mozilla.org/en-US/docs/Web/Reference
https://developer.mozilla.org/en-US/docs/Web/Guide
https://developer.mozilla.org/en-US/docs/Web/Tutorials
https://developer.mozilla.org/en-US/docs/Web/Accessibility
https://developer.mozilla.org/en-US/docs/Web/Security

https://developer.mozilla.org/en-US/docs/Web/Reference/API

https://developer.mozilla.org/en-US/docs/Web/Guide/API

https://developer.mozilla.org/en-US/docs/Web/Guide/Mobile
https://developer.mozilla.org/en-US/docs/Web/Guide/Performance

https://developer.mozilla.org/en-US/docs/Web/Guide/Events
https://developer.mozilla.org/en-US/docs/Web/Guide/Localizations_and_character_encodings
https://developer.mozilla.org/en-US/docs/Web/API/FormData/Using_FormData_Objects
-->

## Mozilla, Microsoft, and Google- General Docs

Mozilla- Documentation
* [Mozilla Developer](https://developer.mozilla.org/en-US), [Mozilla Developer Docs](https://developer.mozilla.org/en-US/docs/Web)
* [Mozilla Learning Area](https://developer.mozilla.org/en-US/docs/Learn) and [Mozilla Learning Area GitHub](https://github.com/mdn/learning-area)

Microsoft- Web Development
* [Microsoft Web Development](https://msdn.microsoft.com/en-us/library/aa155073.aspx)

Google Developers
* [Google Developers](https://developers.google.com), [Google Developer Products](https://developers.google.com/products)
* [Google Developer Web](https://developers.google.com/web)
* [Google Developer Web Fundamentals](https://developers.google.com/web/fundamentals)
* [Google Developer Web Tools](https://developers.google.com/web/tools)

Glossaries
* [Google Glossary](https://developers.google.com/web/fundamentals/glossary)
* [Mozilla Developer Glossary](https://developer.mozilla.org/en-US/docs/Glossary)

<!--
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management | Memory Management - JavaScript | MDN

https://developers.google.com/web/tools/chrome-devtools/memory-problems/memory-101 | Memory Terminology  |  Tools for Web Developers  |  Google Developers

https://hacks.mozilla.org/2017/06/a-crash-course-in-memory-management/ | A crash course in memory management ★ Mozilla Hacks – the Web developer blog
-->

## Document Object Model

Browser Object Model (BOM) and Document Object Model (DOM)
* [Browser Object Model (BOM) Wikipedia](https://en.wikipedia.org/wiki/Browser_Object_Model)
* [Document Object Model (DOM) Wikipedia](https://en.wikipedia.org/wiki/Document_Object_Model), [DOM Events Wikipedia](https://en.wikipedia.org/wiki/DOM_events)

Mozilla- Document Object Model
* [Mozilla Document Object Model Reference](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)
* [Mozilla Document Object Model Examples](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Examples)

<!--
https://developer.mozilla.org/en-US/docs/Tools/Add-ons/DOM_Inspector | DOM Inspector - Firefox Developer Tools | MDN
https://developers.google.com/web/tools/lighthouse/audits/dom-size | Uses An Excessive DOM Size  |  Tools for Web Developers  |  Google Developers
-->

## JavaScript Events

Events
* [Event Wikipedia](https://en.wikipedia.org/wiki/Event_(computing))
* [Event Handler Wikipedia](https://en.wikipedia.org/wiki/Event_(computing)#Event_handler)
* [DOM/JavaScript Events](https://en.wikipedia.org/wiki/Document_Object_Model#JavaScript)
* [DOM Events/HTML Events Wikipedia](https://en.wikipedia.org/wiki/DOM_events#HTML_events)

<!--
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents#The_important_parts_of_a_web_browser

https://developer.mozilla.org/en-US/docs/Web/API/Using_the_Browser_API | Using the Browser API - Web APIs | MDN

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction | Introduction to web APIs - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction#Common_browser_APIs
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction#They_are_based_on_objects

https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model#Specifications
https://developer.mozilla.org/en-US/docs/Web/API/Window

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents#The_document_object_model

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#A_series_of_fortunate_events
-->

Mozilla- Events and Web APIs
* [Mozilla Document Object Model Events](https://developer.mozilla.org/en-US/docs/Web/Events)
* [Mozilla Document Object Model Event Handlers](https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Event_handlers)
* [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API) 

<!--
https://developer.mozilla.org/en-US/docs/Web/API/Document/Document
https://developer.mozilla.org/en-US/docs/Web/API/Node
https://developer.mozilla.org/en-US/docs/Web/API/EventTarget
-->

<!--
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Third_party_APIs
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Drawing_graphics
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Client-side_storage
-->

Desktop
* [Mozilla MouseEvent](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent), [Mozilla WheelEvent](https://developer.mozilla.org/en-US/docs/Web/API/WheelEvent), [Mozilla KeyboardEvent](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent)
* [Mozilla Drag and Drop](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API), [Mozilla Pointer Lock](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_Lock_API)
       
Mobile
* [Mozilla TouchEvent](https://developer.mozilla.org/en-US/docs/Web/API/TouchEvent)
* [Google 300ms tap delay, gone away](https://developers.google.com/web/updates/2013/12/300ms-tap-delay-gone-away), [WebKit More Responsive Tapping on iOS](https://webkit.org/blog/5610/more-responsive-tapping-on-ios/)
* [Mozilla DeviceOrientationEvent + DeviceMotionEvent](https://developer.mozilla.org/en-US/docs/Web/API/Detecting_device_orientation)

Mobile- Hardware Agnostic
* [Mozilla PointerEvent](https://developer.mozilla.org/en-US/docs/Web/API/PointerEvent), [Mozilla Selection](https://developer.mozilla.org/en-US/docs/Web/API/Selection)
* [Mozilla Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API), [Google Intro](https://developers.google.com/web/updates/2016/04/intersectionobserver)
   * [Google Resize Observer API](https://developers.google.com/web/updates/2016/10/resizeobserver)
* [Mozilla Gamepad](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API), [Mozilla Web Speech](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)

## JavaScript

Web technology for developers JavaScript
Related Topics
JavaScript

Tutorials:
Complete beginners
JavaScript basics
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
JavaScript first steps
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps
JavaScript building blocks
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks
Introducing JavaScript objects
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects

Documentation:
Useful lists
All pages index
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Index
Pages tagged "JavaScript"
https://developer.mozilla.org/en-US/docs/tag/JavaScript

Very Useful
JavaScript Guide
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide

Introduction
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction
Grammar and types
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_Types
Numbers and dates
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates
Text formatting
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Text_formatting
Regular expressions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

Control flow and error handling
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling
Loops and iteration
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration
Functions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
Expressions and operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators
Indexed collections
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections
Keyed collections
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Keyed_collections
Working with objects
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects
Details of the object model
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model
Using promises
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises
Iterators and generators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_generators

Meta programming
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Meta_programming

Intermediate
Introducing JavaScript objects
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects
Client-side web APIs
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs
A re-introduction to JavaScript
https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript
JavaScript data structures
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
Equality comparisons and sameness
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness
Closures
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures

Advanced
Inheritance and the prototype chain
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain
Strict mode
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode
JavaScript typed arrays
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Typed_arrays
Memory Management
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management
Concurrency model and Event Loop
https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop

Misc
JavaScript technologies overview
https://developer.mozilla.org/en-US/docs/Web/JavaScript/JavaScript_technologies_overview
Lexical grammar
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar
JavaScript data structures
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
Enumerability and ownership of properties
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties
Iteration protocols
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols
Strict mode
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode
Transitioning to strict mode
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode/Transitioning_to_strict_mode
Template literals
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals

Deprecated features
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features

<!--
https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/JavaScript_basics
Arrays and object literals
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals

Promises/Asynchronous Requests
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
Create and receive promises
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises
https://developers.google.com/web/fundamentals/primers/promises
.then() and .catch() syntax
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch
Async/Await
Fetch API for making HTTP requests
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data

See also Fetch API?
* [Mozilla XMLHttpRequest2](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
  
  
DataView
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView

Expression closures
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Expression_closures
Object initializer
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer
Property accessors
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors
new.target
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new.target


https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects
https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript#Objects
[Inheritance and the prototype chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

* [A Re-introduction to JS (JavaScript Tutorial)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

Simon
http://simon.incutio.com/slides/2006/etech/javascript/js-reintroduction-notes.html
https://web.archive.org/web/20070116062727/http://simon.incutio.com/slides/2006/etech/javascript/js-reintroduction-notes.html
-->

Async:

Promise
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

AsyncFunction
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/AsyncFunction

async function expression
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/async_function

async function
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function

await
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await

Async
for await...of
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for-await...of

JSON
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON

<!--
Mozilla Ajax and JSON
* [Mozilla Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
* [Mozilla Ajax Getting Started](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started)
* [Mozilla Ajax Developer Guide](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX)
-->

WebAssembly
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly

import
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import

import.meta
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import.meta

debugger
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/debugger

Built-in objects

Seven data types:

Primitives:
* Boolean. true and false.
* Number. An integer or floating point number. For example: 42 or 3.14159.
* String
* Symbol
* null
* undefined

Non-Primitive:
* Object

Boolean
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean
Number
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number
String
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String
Symbol
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol

Object
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object

null
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null
undefined
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined

Literals
* Boolean literals
* Floating-point literals
* Integers
* String literals
* Object literals
* Array literals
* RegExp literals

Date
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date
BigInt
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt

parseFloat()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat
parseInt()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt

RegExp	
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp

let, const, var
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var

Set
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set

function expression
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function

function declaration
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function

Function (security issue)
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function

Functions
Arrow functions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
Default parameters
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters
Method definitions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Method_definitions
Rest parameters
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters
The arguments object
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments
getter
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get
setter
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set

<!--
https://developer.mozilla.org/en-US/docs/Glossary/Call_stack
[Concurrency model and Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)
[Memory Management](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management)

https://developer.mozilla.org/en-US/docs/Glossary/Hoisting
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function#Function_declaration_hoisting
-->

block
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block

return
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return

try...catch
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch
throw
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw

Operators:

<!--
[Equality comparisons and sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness)

Operator precedence
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator

https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment_()
-->

Logical operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators
Comma operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comma_Operator
Conditional (ternary) operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator
Grouping operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping
void operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void
Pipeline operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Pipeline_operator

Arithmetic operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators
Assignment operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Assignment_Operators
Comparison operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators
Bitwise operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators

class expression
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/class

class declaration
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/class

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes

Methods index
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index
Properties index
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Properties_Index

eval()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/eval
uneval()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/uneval

delete operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete

Classes
constructor
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor
extends
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/extends
static
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/static

new operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new
super
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super

(Scope and lexical "this")
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this

globalThis
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/globalThis

Proxy
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy
Reflect
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect

Iterators and Generators (repeat):

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators

Loop Statements:

for
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for
for...in
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in
for...of
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of

if...else
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else

while
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while
do...while
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while

Deprecated?
for each...in
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for_each...in

break
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/break
continue
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/continue
label
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label

default
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/default
export
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export
switch
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch

with (not recommended)
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/with
Legacy generator function
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/Legacy_generator_function

empty
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/Empty

Membership and such:

instanceof
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof
typeof
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof

in operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/in

NaN
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN
isNaN()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/isNaN

Infinity
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Infinity

isFinite()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/isFinite

Utilities:

Destructuring assignment
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment

Spread Operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax

Array:

Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
TypedArray
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray
ArrayBuffer
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer
SharedArrayBuffer
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SharedArrayBuffer
Atomics
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics

Deprecated
Array comprehensions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Array_comprehensions

High Order Array Functions:

forEach()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach
map()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map
filter()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter

Map
WeakMap
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap
WeakSet
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet

Float32Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Float32Array
Float64Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Float64Array

Int16Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int16Array
Int32Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int32Array
Int8Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int8Array
Uint16Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint16Array
Uint32Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint32Array
Uint8Array
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array
Uint8ClampedArray
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8ClampedArray

Generator function:

Deprecated
Generator comprehensions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Generator_comprehensions
Legacy generator function expression
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Legacy_generator_function

Generator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator
GeneratorFunction
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/GeneratorFunction

function* expression
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function*

generator function: function*
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*

yield
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield
yield*
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*

Math
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math

Intl
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl
Intl.Collator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Collator
Intl.DateTimeFormat
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DateTimeFormat
Intl.ListFormat
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ListFormat
Intl.NumberFormat
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NumberFormat
Intl.RelativeTimeFormat
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RelativeTimeFormat
Intl.PluralRules
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/PluralRules

Becoming Deprecated
escape()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/escape
unescape()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/unescape

decodeURI()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURI
decodeURIComponent()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURIComponent
encodeURI()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURI
encodeURIComponent()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURIComponent

Warnings
Warning: -file- is being assigned a //# sourceMappingURL, but already has one
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Already_has_pragma
Warning: 08/09 is not a legal ECMA-262 octal constant
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Bad_octal
Warning: Date.prototype.toLocaleFormat is deprecated
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Deprecated_toLocaleFormat
Warning: JavaScript 1.6's for-each-in loops are deprecated
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/For-each-in_loops_are_deprecated
Warning: String.x is deprecated; use String.prototype.x instead
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Deprecated_String_generics
Warning: expression closures are deprecated
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Deprecated_expression_closures
Warning: unreachable code after return statement
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Stmt_after_return

Error
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error
EvalError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/EvalError
InternalError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/InternalError
RangeError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RangeError
ReferenceError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ReferenceError
SyntaxError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SyntaxError
TypeError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypeError
URIError
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/URIError

Errors
Error: Permission denied to access property "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Property_access_denied

Internal Errors
InternalError: too much recursion
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Too_much_recursion

Range Errors
RangeError: argument is not a valid code point
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Not_a_codepoint
RangeError: invalid array length
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Invalid_array_length
RangeError: invalid date
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Invalid_date
RangeError: precision is out of range
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Precision_range
RangeError: radix must be an integer
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Bad_radix
RangeError: repeat count must be less than infinity
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Resulting_string_too_large
RangeError: repeat count must be non-negative
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Negative_repetition_count

Reference Errors
ReferenceError: "x" is not defined
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Not_defined
ReferenceError: assignment to undeclared variable "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Undeclared_var
ReferenceError: can't access lexical declaration'X' before initialization
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cant_access_lexical_declaration_before_init
ReferenceError: deprecated caller or arguments usage
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Deprecated_caller_or_arguments_usage
ReferenceError: invalid assignment left-hand side
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Invalid_assignment_left-hand_side
ReferenceError: reference to undefined property "x"

Syntax Errors
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Undefined_prop
SyntaxError: "0"-prefixed octal literals and octal escape seq. are deprecated
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Deprecated_octal
SyntaxError: "use strict" not allowed in function with non-simple parameters
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Strict_Non_Simple_Params
SyntaxError: "x" is a reserved identifier
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Reserved_identifier
SyntaxError: JSON.parse: bad parsing
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/JSON_bad_parse
SyntaxError: Malformed formal parameter
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Malformed_formal_parameter
SyntaxError: Unexpected token
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Unexpected_token
SyntaxError: Using //@ to indicate sourceURL pragmas is deprecated. Use //# instead
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Deprecated_source_map_pragma
SyntaxError: a declaration in the head of a for-of loop can't have an initializer
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Invalid_for-of_initializer
SyntaxError: applying the 'delete' operator to an unqualified name is deprecated
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Delete_in_strict_mode
SyntaxError: for-in loop head declarations may not have initializers
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Invalid_for-in_initializer
SyntaxError: function statement requires a name
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Unnamed_function_statement
SyntaxError: identifier starts immediately after numeric literal
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Identifier_after_number
SyntaxError: illegal character
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Illegal_character
SyntaxError: invalid regular expression flag "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Bad_regexp_flag
SyntaxError: missing ) after argument list
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_parenthesis_after_argument_list
SyntaxError: missing ) after condition
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_parenthesis_after_condition
SyntaxError: missing : after property id
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_colon_after_property_id
SyntaxError: missing ; before statement
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_semicolon_before_statement
SyntaxError: missing = in const declaration
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_initializer_in_const
SyntaxError: missing ] after element list
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_bracket_after_list
SyntaxError: missing formal parameter
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_formal_parameter
SyntaxError: missing name after . operator
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_name_after_dot_operator
SyntaxError: missing variable name
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/No_variable_name
SyntaxError: missing } after function body
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_curly_after_function_body
SyntaxError: missing } after property list
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Missing_curly_after_property_list
SyntaxError: redeclaration of formal parameter "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Redeclared_parameter
SyntaxError: return not in function
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Bad_return_or_yield
SyntaxError: test for equality (==) mistyped as assignment (=)?
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Equal_as_assign
SyntaxError: unterminated string literal
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Unterminated_string_literal

Type Errors
TypeError: "x" has no properties
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/No_properties
TypeError: "x" is (not) "y"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Unexpected_type
TypeError: "x" is not a constructor
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Not_a_constructor
TypeError: "x" is not a function
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Not_a_function
TypeError: "x" is not a non-null object
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/No_non-null_object
TypeError: "x" is read-only
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Read-only
TypeError: 'x' is not iterable
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/is_not_iterable
TypeError: More arguments needed
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/More_arguments_needed
TypeError: Reduce of empty array with no initial value
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Reduce_of_empty_array_with_no_initial_value
TypeError: can't access dead object
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Dead_object
TypeError: can't access property "x" of "y"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cant_access_property
TypeError: can't define property "x": "obj" is not extensible
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cant_define_property_object_not_extensible
TypeError: can't delete non-configurable array element
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Non_configurable_array_element
TypeError: can't redefine non-configurable property "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cant_redefine_property
TypeError: cannot use 'in' operator to search for 'x' in 'y'
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/in_operator_no_object
TypeError: cyclic object value
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cyclic_object_value
TypeError: invalid 'instanceof' operand 'x'
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/invalid_right_hand_side_instanceof_operand
TypeError: invalid Array.prototype.sort argument
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Array_sort_argument
TypeError: invalid arguments
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Typed_array_invalid_arguments
TypeError: invalid assignment to const "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Invalid_const_assignment
TypeError: property "x" is non-configurable and can't be deleted
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cant_delete
TypeError: setting getter-only property "x"
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Getter_only
TypeError: variable "x" redeclares argument
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Var_hides_argument

URI Errors
URIError: malformed URI sequence
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Malformed_URI

X.prototype.y called on incompatible type
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Called_on_incompatible_type


# JavaScript Mozilla Notes

New in JavaScript
ECMAScript 2015 support in Mozilla
ECMAScript 5 support in Mozilla
ECMAScript Next support in Mozilla
Firefox JavaScript changelog
New in JavaScript 1.1
New in JavaScript 1.2
New in JavaScript 1.3
New in JavaScript 1.4
New in JavaScript 1.5
New in JavaScript 1.6
New in JavaScript 1.7
New in JavaScript 1.8
New in JavaScript 1.8.1
New in JavaScript 1.8.5

Contribute
JavaScript doc status
The MDN project

### Client-Side APIs

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs

Client-side web APIs
Client-side web APIs
Introduction to web APIs
Manipulating documents
Fetching data from the server
Third party APIs
Drawing graphics
Video and audio APIs
Client-side storage

Express Web Framework (node.js/JavaScript)
Express Web Framework (Node.js/JavaScript) overview
Express/Node introduction
Setting up a Node (Express) development environment
Express tutorial: The Local Library website
Express Tutorial Part 2: Creating a skeleton website
Express Tutorial Part 3: Using a database (with Mongoose)
Express Tutorial Part 4: Routes and controllers
Express Tutorial Part 5: Displaying library data
Express Tutorial Part 6: Working with forms
Express Tutorial Part 7: Deploying to production

Django web framework (Python)
Django web framework (Python) overview
Introduction
Setting up a development environment
Tutorial: The Local Library website
Tutorial Part 2: Creating a skeleton website
Tutorial Part 3: Using models
Tutorial Part 4: Django admin site
Tutorial Part 5: Creating our home page
Tutorial Part 6: Generic list and detail views
Tutorial Part 7: Sessions framework
Tutorial Part 8: User authentication and permissions
Tutorial Part 9: Working with forms
Tutorial Part 10: Testing a Django web application
Tutorial Part 11: Deploying Django to production
Web application security
Assessment: DIY mini blog

JavaScript first steps
JavaScript first steps overview
What is JavaScript?
A first splash into JavaScript
What went wrong? Troubleshooting JavaScript
Storing the information you need — Variables
Basic math in JavaScript — Numbers and operators
Handling text — Strings in JavaScript
Useful string methods
Arrays
Assessment: Silly story generator

JavaScript building blocks
JavaScript building blocks overview
Making decisions in your code — Conditionals
Looping code
Functions — Reusable blocks of code
Build your own function
Function return values
Introduction to events
Assessment: Image gallery

Introducing JavaScript objects
Introducing JavaScript objects overview
Object basics
Object-oriented JavaScript for beginners
Object prototypes
Inheritance in JavaScript
Working with JSON data
Object building practise
Assessment: Adding features to our bouncing balls demo

Client-side web APIs

Accessibility — Make the web usable by everyone
Accessibility guides
Accessibility overview
What is accessibility?
HTML: A good basis for accessibility
CSS and JavaScript accessibility best practices
WAI-ARIA basics
Accessible multimedia
Mobile accessibility
Accessibility assessment
Assessment: Accessibility troubleshooting

Tools and testing
Cross browser testing
Cross browser testing overview
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing
Introduction to cross browser testing
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing
Strategies for carrying out testing
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Testing_strategies
Handling common HTML and CSS problems
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/HTML_and_CSS
Handling common JavaScript problems
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/JavaScript
Handling common accessibility problems
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Accessibility
Implementing feature detection
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Feature_detection
Introduction to automated testing
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Automated_testing
Setting up your own test automation environment
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Your_own_automation_environment
Server-side website programming

First steps
First steps overview
Introduction to the server-side
Client-Server overview
Server-side web frameworks
Website security

Related Topics
Complete beginners start here!

Getting started with the Web
Getting started with the Web overview
Installing basic software
What will your website look like?
Dealing with files
HTML basics
CSS basics
JavaScript basics
Publishing your website
How the Web works
HTML — Structuring the Web

Introduction to HTML
Introduction to HTML overview
Getting started with HTML
What's in the head? Metadata in HTML
HTML text fundamentals
Creating hyperlinks
Advanced text formatting
Document and website structure
Debugging HTML
Assessment: Marking up a letter
Assessment: Structuring a page of content

Multimedia and embedding
Multimedia and embedding overview
Images in HTML
Video and audio content
From object to iframe — other embedding technologies
Adding vector graphics to the Web
Responsive images
Assessment: Mozilla splash page

HTML tables
HTML tables overview
HTML table basics
HTML Table advanced features and accessibility
Assessment: Structuring planet data

HTML forms
HTML forms overview
Your first HTML form
How to structure an HTML form
The native form widgets
Sending form data
Form validation
How to build custom form widgets
Sending forms through JavaScript
HTML forms in legacy browsers
Styling HTML forms
Advanced styling for HTML forms
Property compatibility table for form widgets
CSS — Styling the Web

Introduction to CSS
Introduction to CSS overview
How CSS works
CSS syntax
Selectors introduction
Simple selectors
Attribute selectors
Pseudo-classes and pseudo-elements
Combinators and multiple selectors
CSS values and units
Cascade and inheritance
The box model
Debugging CSS
Assessment: Fundamental CSS comprehension

Styling text
Styling text overview
Fundamental text and font styling
Styling lists
Styling links
Web fonts
Assessment: Typesetting a community school homepage

Styling boxes
Styling boxes overview
Box model recap
Backgrounds
Borders
Styling tables
Advanced box effects
Assessment: Creating fancy letterheaded paper
Assessment: A cool-looking box

CSS layout
CSS layout overview
Introduction
Normal Flow
Flexbox
Grids
Floats
Positioning
Multiple-column Layout
Legacy Layout Methods
Supporting Older Browsers
Fundamental Layout Comprehension
JavaScript — Dynamic client-side scripting

Further resources
Advanced learning material
WebGL: Graphics processing

Common questions
HTML questions
CSS questions
JavaScript questions
How the Web works
Tools and setup
Design and accessibility
How to contribute

### APIS

https://developer.mozilla.org/en-US/docs/Web/API
https://developer.mozilla.org/en-US/docs/Web/Events

Specifications Section
This is a list of all the APIs that are available.

A
Alarm API
Ambient Light Events
Apps
Audio Channels API

B
Background Tasks
Battery API
Beacon
Bluetooth API
Bluetooth API (Firefox OS)
Broadcast Channel API
Browser API

C
CSS Counter Styles
CSS Font Loading API 
CSSOM
https://developer.mozilla.org/en-US/docs/Web/API/CSS_Object_Model
Camera API
Canvas API
Channel Messaging API
Clipboard API
Contacts API
Credential Management API

D
DOM
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model
Data Store API
Device Storage API

E
Encoding API
Encrypted Media Extensions

F
FMRadio API
Fetch API 
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
File System API 
Firefox OS
Frame Timing API
Fullscreen API

G
Gamepad API 
Geolocation API
https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API

H
HTML Drag and Drop API
High Resolution Time

I
Idle API
IndexedDB
Intersection Observer API

K

L
L10N API

M
Media Capabilities API 
Media Capture and Streams
Media Session API
MediaStream Recording
Mobile Connection API
Mobile Messaging API

N
NFC API
Navigation Timing
Network Information API 
Network Stats API

P
Page Visibility API
Payment Request API
https://developer.mozilla.org/en-US/docs/Web/API/Payment_Request_API
Performance API
Performance Timeline API
Permissions API
Permissions API (Firefox OS)
Pointer Events
Pointer Lock API
Power Management API
Presentation API 
Proximity Events 
Push API 
https://developer.mozilla.org/en-US/docs/Web/API/Push_API

R
Resource Timing API

S
Screen Capture API
Selection API
Server Sent Events
Service Workers API
https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API
Settings API
Simple Push API
Storage
Streams 

T
TCP Socket API
Time and Clock API
Touch Events

U
UDP Socket API
User Timing API

V
Vibration API

W
Wake Lock API
Web Activities
Web Animations 
Web Audio API
Web Authentication API
https://developer.mozilla.org/en-US/docs/Web/API/Web_Authentication_API
Web Crypto API
Web Notifications
https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API
Web Speech API 
Web Storage API
Web Telephony API
Web Workers API
https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API
WebGL
WebRTC
https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API
WebVR API 
Websockets API
https://developer.mozilla.org/en-US/docs/Web/API/Websockets_API
WiFi Information API

X
XMLHttpRequest

Deleted
App Cache
Application Compatibility Layer
Archive API
CSSOM View
Console API
DOM (Non-standard)
DOM Events
Device Orientation Events
Directory Upload API
Download API
Engineering Mode API
File API
Geometry Interfaces
HTML DOM
HTML Microdata API
HTML Undo Manager API
Identity
Image Capture API
Input Port API
Inter-App Connection API
Kill Switch API
Long Tasks
MSISDN Verification API
Media Source Extensions
Mozilla Payment API
Request Sync API
Resize Observer API
Resource Statistics API
SVG
Screen Orientation API
Social API
Speaker Manager API
System Update API
TV API
URL API
Voicemail API
Web Components
Web MIDI API
Web Manifest
WebVTT
WiFi P2P API
WiFi Tethering API
XDomain

### JavaScript Events

https://developer.mozilla.org/en-US/docs/Web/Events

Related Topics

Events
Ambient Light events
App Cache events
Audio Channels API events
Battery API events
Broadcast Channel API events
Browser API events
Channel Messaging API events
Clipboard API events
Contacts API events
CSS Font Loading API events
CSSOM events
CSSOM View events
Device Orientation events
Device Storage API events
DOM events
Download API events
Encrypted Media Extensions events
Engineering Mode API events
File API events
File System API events
FMRadio API events
Fullscreen API events
Gamepad API events
HTML DOM events
HTML Drag and Drop API events
IndexedDB events
Inter-App Connection API events
Media Capture and Streams events
Media Source Extensions events
MediaStream Recording events
Mobile Connection API events
Mobile Messaging API events
Network Information API events
Page Visibility API events
Payment Request API events
Performance API events
Pointer events
Pointer Lock API events
Presentation API events
Proximity events
Push API events
Screen Orientation API events
Selection API events
Server Sent events
Service Workers API events
Settings API events
Simple Push API events
Speaker Manager API events
SVG events
TCP Socket API events
Time and Clock API events
Touch events
TV API events
UDP Socket API events
Web Audio API events
Web Components events
WebGL events
Web Manifest events
Web MIDI API events
Web Notifications events
WebRTC events
Websockets API events
Web Speech API events
Web Storage API events
Web Telephony API events
WebVR API events
WebVTT events
WiFi Information API events
WiFi P2P API events
XMLHttpRequest events

## React

### Main Concepts

1. Hello World
2. Introducing JSX
3. Rendering Elements
4. Components and Props
5. State and Lifecycle
6. Handling Events
7. Conditional Rendering
8. Lists and Keys
9. Forms
10. Lifting State Up
11. Composition vs Inheritance
12. Thinking In React

### Advanced Guides

* Accessibility
* Code-Splitting
* Context
* Error Boundaries
* Forwarding Refs
* Fragments
* Higher-Order Components
* Integrating with Other Libraries
* JSX In Depth
* Optimizing Performance
* Portals
* React Without ES6
* React Without JSX
* Reconciliation
* Refs and the DOM
* Render Props
* Static Type Checking
* Strict Mode
* Typechecking With PropTypes
* Uncontrolled Components
* Web Components

### API Reference

* API REFERENCE
* React
* React.Component
* ReactDOM
* ReactDOMServer
* DOM Elements
* SyntheticEvent
* Test Utilities
* Shallow Renderer
* Test Renderer
* JS Environment Requirements
* Glossary

### Hooks

1. Introducing Hooks
2. Hooks at a Glance
3. Using the State Hook
4. Using the Effect Hook
5. Rules of Hooks
6. Building Your Own Hooks
7. Hooks API Reference
8. Hooks FAQ

## Express

## Node

* Assertion Testing
* Async Hooks
* Buffer
* C++ Addons
* C/C++ Addons - N-API
* Child Processes
* Cluster
* Command Line Options
* Console
* Crypto
* Debugger
* Deprecated APIs
* DNS
* Domain
* ECMAScript Modules
* Errors
* Events
* File System
* Globals
* HTTP
* HTTP/2
* HTTPS
* Inspector
* Internationalization
* Modules
* Net
* OS
* Path
* Performance Hooks
* Policies
* Process
* Punycode
* Query Strings
* Readline
* REPL
* Report
* Stream
* String Decoder
* Timers
* TLS/SSL
* Trace Events
* TTY
* UDP/Datagram
* URL
* Utilities
* V8
* VM
* Worker Threads
* Zlib
