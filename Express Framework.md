# Express Framework
* The framework that's build on top of Node that's going to help us create our backend with ease.
# Advantages 
* Readability
* Less code
* Middleware

* its enable us to choose which features we want to add to our website backend.
* There are six steps to creating an express server.
# Create an Express Server
1. Create directory.
2. Create index.js file.
3. Initialise NPM.
4. Install the Express package.
5. Write server application in index.js.
6. Start server.

# What is Localhost?
* Localhost is simply when we dont have a server on the internet and instead we want to host our server locally.
* so making our computer, the server of our websites back end and that is the local part of our hosting.

  # What is Port ?
  * The port is kind of equivalent to a bunch of doors on  our server computer, and each of these doors have an address.
  *  Each port is identified by a unique number, then different applications or different hardware can tap into a Particular port.
    And tjis way we can have multiple services running through the same computer withiout them interfering with each other so that eacj one can be listening on a particular port.
* we can check which port on our compute are currently.
command:
# netstat -ano|findstr"LISTENING"

# HTTP Request (Hyper Text Transfer Protocol)
* The transfer protocol basically describes this as a language, a language that allows computer to talk to each pther across the Internet.
* When computers want to talk to each other across the Internet, they need the hyper text transfer protocol,a different language that allows them to understsnd each other.

# Request Vocab
* Get- used to request data from a specified resource.
* Post- used to send data to a server to create/update a resource.
* Put-  is used to send data to a server to create/update a resource.
* Patch-  method is used to apply partial modifications to a resource.
* Delete- DELETE method deletes the specified resource.
* OPTIONS- OPTIONS method describes the communication options for the target resource.
* CONNECT- used to start a two-way communications (a tunnel) with the requested resource.
* TRACE- used to perform a message loop-back test that tests the path for the target resource (useful for debugging purposes).

# Middleware
Middleware functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.

<img width="740" alt="image" src="https://github.com/sudikshakawale/Full-Stack-Web-Development/assets/139041369/0c43c641-6393-4780-8f16-ae4bafacf34e">

