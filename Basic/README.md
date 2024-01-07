# Review The Basic concepts of Node

## 1 - NodeJs Program lifecycle

We have a simple node application

- app.js
  - Start Script
  - Parse code, register variabels & functions ...
  - event loop
  - proccess.exit

all of this processes are beteween responsibility of Node

**important** : we never left a dead program

The reason of this important concept of Nodecalled event loop. This is basically a loop process wich is managed by Node, wich keeps on running as long as work as there are event listeners registered.

## 2 - Understanding Http Requests

A HTTP request is a message sent by a client to a server, typically to request the retrieval or manipulation of information on the server. It consists of a method (such as GET or POST) indicating the desired action, a URI (Uniform Resource Identifier) specifying the resource, and optional headers providing additional information. This communication follows the rules of the Hypertext Transfer Protocol (HTTP) and is fundamental to the exchange of data on the World Wide Web.

**important** : in node, the request object is the object who node generate for us with all the data of the request
