# Web-servers

### What are they?

whenever a browser needs a file that is hosted on a web server, the browser requests the file via HTTP. 
When the request reaches the correct (hardware) web server, the (software) HTTP server accepts the request, 
finds the requested document, and sends it back to the browser, also through HTTP.

## Node.js and Nginx
### What are they 

Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine. It allows developers to run JavaScript on 
the server side to build fast, scalable network applications. Nginx, on the other hand, is a web server and reverse 
proxy server. It is known for its high performance and low resource consumption.

### where are they used?

Some use cases of Node.js consist of:

- Developing Streaming Web Applications
- Developing Real-Time Chat-bots
- Developing Big Data and Analytics Solutions
- Developing Single-Page Applications
- The Crafting of Microservices Architecture

### Node.js Dependencies

There are 2 main dependencies Node.js relies on and they consist of libraries and tools.

<strong>Libraries are</strong>:

- v8
- libuv
- llhttp
- c-ares
- OpenSSL
- zlib

<strong>Tools are</strong>:

- npm
- gyp
- gtest

### What is a reverse proxy?

A reverse proxy is a server that sits in front of web servers and forwards client requests to those web servers. 
Reverse proxies are typically implemented to help increase security, performance, and reliability. 
