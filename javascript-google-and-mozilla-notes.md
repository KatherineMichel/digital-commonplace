# JavaScript- Google and Mozilla Notes

<!--
Memory

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management | Memory Management - JavaScript | MDN

https://developers.google.com/web/tools/chrome-devtools/memory-problems/memory-101 | Memory Terminology  |  Tools for Web Developers  |  Google Developers

https://hacks.mozilla.org/2017/06/a-crash-course-in-memory-management/ | A crash course in memory management ★ Mozilla Hacks – the Web developer blog
-->

## Stuff

WebSockets and Server-Sent Events
* [Mozilla WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket), [Mozilla WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API), and [Mozilla Writing WebSocket servers](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_servers)
* [Mozilla Server-Sent Event](https://developer.mozilla.org/en-US/docs/Web/API/EventSource)

Mozilla WebRTC
* [Mozilla WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)

WebAssembly
* [WebAssembly](https://webassembly.org/)
* [Mozilla WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly)

<!--
RTC Framework (Real Time Communication via APIs)
* [WebRTC Wikipedia](https://en.wikipedia.org/wiki/WebRTC)

* [WebAssembly GitHub](https://en.wikipedia.org/wiki/WebAssembly)
* [Web Worker Wikipedia](https://en.wikipedia.org/wiki/Web_worker)
* [Push Technology Wikipedia](https://en.wikipedia.org/wiki/Push_technology) and [Push Notification Wikipedia](https://en.wikipedia.org/wiki/Push_technology#Push_notification)

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

## Document and Window

<!--
https://developer.mozilla.org/en-US/docs/Web/API/Window
https://developer.mozilla.org/en-US/docs/Web/API/Document
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
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents#The_important_parts_of_a_web_browser
https://software.hixie.ch/utilities/js/live-dom-viewer/

https://developer.mozilla.org/en-US/docs/Web/API/Using_the_Browser_API | Using the Browser API - Web APIs | MDN

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction | Introduction to web APIs - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction#Common_browser_APIs
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction#They_are_based_on_objects

https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model#Specifications

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents#The_document_object_model

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#A_series_of_fortunate_events
-->

Mozilla- Events and Web APIs
* [Mozilla Document Object Model Events](https://developer.mozilla.org/en-US/docs/Web/Events)
* [Mozilla Document Object Model Event Handlers](https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Event_handlers)

Mozilla- Web APIs
* [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API) 

<!--
https://developer.mozilla.org/en-US/docs/Web/Events | Event reference | MDN
https://developer.mozilla.org/en-US/docs/Web/API/EventTarget

https://developer.mozilla.org/en-US/docs/Web/API/Document/Document
https://developer.mozilla.org/en-US/docs/Web/API/Node | Node - Web APIs | MDN
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
* [Mozilla KeyboardEvent](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent), [Mozilla MouseEvent](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent), [Mozilla WheelEvent](https://developer.mozilla.org/en-US/docs/Web/API/WheelEvent)
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
